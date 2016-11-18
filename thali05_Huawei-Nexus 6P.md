#### Test 921522864f1c710_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-18 08:33:07.732   928  2858 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
11-18 08:33:08.232   928  5329 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182825, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 08:33:08.774  5573  5573 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-18 08:33:08.779  5573  5573 D AndroidRuntime: CheckJNI is OFF
11-18 08:33:08.807  5573  5573 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-18 08:33:08.840  5573  5573 I Radio-JNI: register_android_hardware_Radio DONE
11-18 08:33:08.855  5573  5573 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-18 08:33:08.860   928  4143 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-18 08:33:08.901   928  4143 I ActivityManager: Start proc 5582:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-18 08:33:08.907  5573  5573 D AndroidRuntime: Shutting down VM
,11-18 08:33:09.248   928  3053 I WindowManager: Screenshot max retries 4 of Token{4fc5dfc ActivityRecord{16b0eef u0 com.test.thalitest/.MainActivity t8}} appWin=Window{33fece7 u0 Starting com.test.thalitest} drawState=2
,11-18 08:33:09.321  5582  5582 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-18 08:33:09.354  5582  5582 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-18 08:33:09.384  5582  5582 I LibraryLoader: Time to load native libraries: 26 ms (timestamps 3951-3977)
,11-18 08:33:09.384  5582  5582 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-18 08:33:09.407  5582  5582 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f1d99c8}
,11-18 08:33:09.407  5582  5582 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-18 08:33:09.408  5582  5582 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-18 08:33:09.414  5582  5582 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-18 08:33:09.415  5582  5582 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-18 08:33:09.451  5582  5582 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-18 08:33:09.465  5582  5582 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-18 08:33:09.465  5582  5582 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-18 08:33:09.465  5582  5582 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-18 08:33:09.465  5582  5582 I Adreno  : Build Date                       : 12/06/15
11-18 08:33:09.465  5582  5582 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-18 08:33:09.465  5582  5582 I Adreno  : Local Branch                     : mybranch17112971
11-18 08:33:09.465  5582  5582 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-18 08:33:09.465  5582  5582 I Adreno  : Remote Branch                    : NONE
11-18 08:33:09.465  5582  5582 I Adreno  : Reconstruct Branch               : NOTHING
,11-18 08:33:09.513   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42391df:true
,11-18 08:33:09.547  4052  4052 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14201]" dev="sockfs" ino=14201 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:09.547  4052  4052 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[14201]" dev="sockfs" ino=14201 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:09.560  5582  5582 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-18 08:33:09.568  5582  5582 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-18 08:33:09.590  4052  4052 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33829]" dev="sockfs" ino=33829 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:09.595  5582  5619 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-18 08:33:09.590  4052  4052 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33829]" dev="sockfs" ino=33829 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:09.594  3053  3053 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14213]" dev="sockfs" ino=14213 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:09.594  3053  3053 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14213]" dev="sockfs" ino=14213 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:09.602  5582  5606 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-18 08:33:09.620  5582  5619 I OpenGLRenderer: Initialized EGL, version 1.4
,11-18 08:33:09.693   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +444ms (total +817ms)
,11-18 08:33:09.739  5582  5582 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5582
,11-18 08:33:09.844  5582  5582 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-18 08:33:10.165  5582  5621 D jxcore_app_log: JniHelper::setJavaVM(0xf523c000), pthread_self() = -584058576
,11-18 08:33:10.177  5582  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-18 08:33:10.177  5582  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-18 08:33:10.177  5582  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-18 08:33:10.177  5582  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-18 08:33:10.177  5582  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-18 08:33:10.177  5582  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f6a259 added. We now have 1 listener(s)
,11-18 08:33:10.182  5582  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-18 08:33:10.183  5582  5621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:10.184  5582  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-18 08:33:10.184  5582  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-18 08:33:10.189  5582  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d134ccc added. We now have 1 listener(s)
11-18 08:33:10.189  5582  5621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 08:33:10.202   928  2868 D WifiService: New client listening to asynchronous messages
,11-18 08:33:10.204  5582  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 08:33:10.204  5582  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-18 08:33:10.205  5582  5621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-18 08:33:10.205  5582  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-18 08:33:10.205  5582  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-18 08:33:10.205  5582  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-18 08:33:10.205  5582  5621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-18 08:33:10.208  5582  5621 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-18 08:33:10.628  5582  5582 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-18 08:33:10.971  5582  5591 I art     : Background sticky concurrent mark sweep GC freed 77182(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 1.468ms total 243.885ms
,11-18 08:33:11.628  5582  5628 W jxcore-log: Initializing JXcore engine
,11-18 08:33:11.628  5582  5628 W jxcore-log: JXcore engine is ready
,11-18 08:33:11.647  5628  5628 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11728 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-18 08:33:11.647  5628  5628 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16470]" dev="sockfs" ino=16470 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-18 08:33:11.647  5628  5628 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-18 08:33:11.647  5628  5628 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30681]" dev="sockfs" ino=30681 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-18 08:33:11.664  5582  5628 W jxcore-log: Starting JXcore engine
,11-18 08:33:11.712  5582  5628 W jxcore-log: Platform android
11-18 08:33:11.712  5582  5628 W jxcore-log: 
,11-18 08:33:11.712  5582  5628 W jxcore-log: Process ARCH arm
11-18 08:33:11.712  5582  5628 W jxcore-log: 
,11-18 08:33:11.727  5582  5591 I art     : Background partial concurrent mark sweep GC freed 54667(5MB) AllocSpace objects, 6(1792KB) LOS objects, 38% free, 25MB/41MB, paused 1.105ms total 102.736ms
,11-18 08:33:11.874  5582  5628 I jxcore-log: JXcore Cordova bridge is ready!
11-18 08:33:11.874  5582  5628 I jxcore-log: 
,11-18 08:33:11.874  5582  5628 W jxcore-log: JXcore engine is started
,11-18 08:33:11.884  5582  5621 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-18 08:33:11.888  5582  5582 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-18 08:33:14.720   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:15.721   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:16.722   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:17.723   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:18.724   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:19.725   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-18 08:33:21.472  5582  5628 I jxcore-log: 2016-11-18 13:33:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-18 08:33:21.472  5582  5628 I jxcore-log: 
,11-18 08:33:21.474  5582  5628 I jxcore-log: 2016-11-18 13:33:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-18 08:33:21.474  5582  5628 I jxcore-log: 
,11-18 08:33:21.475  5582  5628 I jxcore-log: 2016-11-18 13:33:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
11-18 08:33:21.475  5582  5628 I jxcore-log: 
,11-18 08:33:21.480  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 08:33:21.480  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 08:33:21.481  5582  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 08:33:21.484  5582  5628 I jxcore-log: 2016-11-18 13:33:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-18 08:33:21.484  5582  5628 I jxcore-log: 
11-18 08:33:21.486  5582  5628 I jxcore-log: 2016-11-18 13:33:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-18 08:33:21.486  5582  5628 I jxcore-log: 
,11-18 08:33:21.734  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 08:33:21.734  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@908d524 added. We now have 2 listener(s)
,11-18 08:33:21.735  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:21.735  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 08:33:21.735  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-18 08:33:21.735  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 08:33:21.735  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78be88d added. We now have 2 listener(s)
11-18 08:33:21.735  5582  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 08:33:21.736  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 08:33:21.737  5582  5628 D ExecuteNativeTests: Running unit tests
11-18 08:33:21.738  5582  5628 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 08:33:21.738   928  3314 D WifiService: setWifiEnabled: true pid=5582, uid=10077
11-18 08:33:21.738   928  3314 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 08:33:27.736   928  2858 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-18 08:33:31.743  5582  5628 I com.test.thalitest.ThaliTestRunner: Running UT
,11-18 08:33:31.815  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-18 08:33:31.815  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5564a16 added. We now have 3 listener(s)
11-18 08:33:31.816  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:31.816  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 08:33:31.816  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 08:33:31.816  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 08:33:31.816  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3546f97 added. We now have 3 listener(s)
11-18 08:33:31.816  5582  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 08:33:31.817  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 08:33:31.822  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-18 08:33:31.823  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 08:33:31.823  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-18 08:33:31.823  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:31.823  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:31.824  5582  5628 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-18 08:33:31.824  5582  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-18 08:33:31.824  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-18 08:33:31.825  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:31.825  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:31.825  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:31.826  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-18 08:33:31.826  5582  5628 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-18 08:33:31.828  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-18 08:33:31.829  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-18 08:33:31.830  5582  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 08:33:31.832  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:31.833  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 08:33:31.851  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 08:33:31.854  5582  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 08:33:31.855  5582  5628 D io.jxcore.node.ConnectivityMonitor: start: OK
11-18 08:33:31.855  5582  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,11-18 08:33:31.855  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-18 08:33:31.856  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.856  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.856  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.857  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:31.857  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 08:33:31.857  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 08:33:31.857  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:31.857  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 08:33:31.858  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-18 08:33:31.858  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 08:33:31.858  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 08:33:31.858  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 08:33:31.858  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 08:33:31.858  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:31.858  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 08:33:31.859  5582  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 08:33:31.861  5582  5582 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 08:33:31.861  5582  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:31.862  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 08:33:31.862  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 08:33:31.862  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 08:33:31.860  4736  4736 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30719]" dev="sockfs" ino=30719 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:31.860  4736  4736 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30719]" dev="sockfs" ino=30719 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:31.868  5582  5582 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 08:33:31.868  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 08:33:31.869  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.869  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 08:33:31.870  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:31.870  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-18 08:33:31.871  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-18 08:33:31.871  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.872  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:31.872  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 08:33:31.872  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 08:33:31.872  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:31.872  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-18 08:33:31.872  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:31.872  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:31.873  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:31.873  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 08:33:31.873  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:31.873  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.873  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.873  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.873  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:31.876  4501  4712 D BtGatt.GattService: registerClient() - UUID=d58fddd2-cf8a-447c-a0ce-5c556e5623cc
,11-18 08:33:31.877  4501  4582 D BtGatt.GattService: onClientRegistered() - UUID=d58fddd2-cf8a-447c-a0ce-5c556e5623cc, clientIf=5
11-18 08:33:31.878  5582  5593 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 08:33:31.880  4501  4591 D BtGatt.AdvertiseManager: message : 0
,11-18 08:33:31.883  4501  4591 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 08:33:31.900  4501  4582 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 08:33:31.908  4501  4582 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 08:33:31.909  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.910  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:31.910  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 08:33:31.910  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.910  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.910  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.911  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:31.911  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.911  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 08:33:31.913  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 08:33:31.913  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.914  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.915  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:31.915  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:31.916  5582  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-18 08:33:31.916  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 08:33:31.917  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-18 08:33:31.917  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:31.917  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 08:33:31.917  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.918  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.918  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:31.918  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 08:33:31.919  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 08:33:31.919  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 08:33:31.919  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.919  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.919  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 08:33:31.920  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.923  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-18 08:33:31.923  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 08:33:31.924  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.924  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.924  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:31.924  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 08:33:32.420  5582  5628 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 08:33:32.421  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-18 08:33:32.421  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-18 08:33:32.421  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-18 08:33:32.421  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-18 08:33:32.421  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-18 08:33:32.422  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-18 08:33:32.423  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-18 08:33:32.423  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-18 08:33:32.423  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-18 08:33:32.423  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-18 08:33:32.423  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-18 08:33:32.424  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-18 08:33:32.425  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-18 08:33:32.425  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-18 08:33:32.425  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-18 08:33:32.425  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-18 08:33:32.425  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-18 08:33:32.425  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 08:33:32.425  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-18 08:33:32.426  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-18 08:33:32.426  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 08:33:32.426  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 08:33:32.429  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 08:33:32.429  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 08:33:32.430  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 08:33:32.431  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 08:33:32.431  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-18 08:33:32.431  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 08:33:32.432  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 08:33:32.432  5582  5630 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 08:33:32.432  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 08:33:32.432  5582  5630 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 08:33:32.432  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-18 08:33:32.432  5582  5630 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 08:33:32.432  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 08:33:32.432  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 08:33:32.432  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 08:33:32.433  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-18 08:33:32.434  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.434  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.434  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.434  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.437  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:32.439  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 08:33:32.442  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:32.442  5582  5628 D BluetoothLeScanner: could not find callback wrapper
,11-18 08:33:32.443  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 08:33:32.443  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.444  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.444  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.444  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 08:33:32.445  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.449  4501  4591 D BtGatt.AdvertiseManager: message : 1
,11-18 08:33:32.451  4501  4591 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 08:33:32.461  4501  4582 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 08:33:32.461  4501  4582 D BtGatt.GattService: Client app is not null!
,11-18 08:33:32.464  4501  4514 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 08:33:32.464  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 08:33:32.465  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.465  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:32.465  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.465  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.465  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.465  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 08:33:32.466  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 08:33:32.467  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 08:33:32.467  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.468  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.469  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:32.469  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.469  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.469  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 08:33:32.469  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 08:33:32.469  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 08:33:32.470  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 08:33:32.470  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:32.470  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:32.470  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:32.470  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 08:33:32.470  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 08:33:32.471  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 08:33:32.471  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.471  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.471  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-18 08:33:32.471  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.472  5582  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 08:33:32.472  5582  5628 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 08:33:32.472  5582  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-18 08:33:32.472  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-18 08:33:32.473  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.474  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.474  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.474  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:32.474  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 08:33:32.474  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 08:33:32.474  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:32.475  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.475  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.475  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-18 08:33:32.475  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.475  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:32.475  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 08:33:32.479  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 08:33:32.480  5582  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 08:33:32.480  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-18 08:33:32.480  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 08:33:32.480  4515  4515 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[35848]" dev="sockfs" ino=35848 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:32.480  4515  4515 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[35848]" dev="sockfs" ino=35848 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:32.481  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 08:33:32.481  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 08:33:32.481  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-18 08:33:32.481  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:32.482  5582  5633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:32.481  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 08:33:32.485  5582  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 08:33:32.492  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 08:33:32.492  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 08:33:32.492  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 08:33:32.496  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.497  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 08:33:32.498  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:32.498  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 08:33:32.498  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-18 08:33:32.502  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.502  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.502  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 08:33:32.502  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 08:33:32.502  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:32.502  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-18 08:33:32.502  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:32.502  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:32.502  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.503  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 08:33:32.503  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:32.503  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.503  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.503  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.504  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:32.508  4501  4515 D BtGatt.GattService: registerClient() - UUID=8fcc9e80-7ab8-42f0-bfc0-33930b34b6f8
11-18 08:33:32.509  4501  4582 D BtGatt.GattService: onClientRegistered() - UUID=8fcc9e80-7ab8-42f0-bfc0-33930b34b6f8, clientIf=5
11-18 08:33:32.509  5582  5592 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 08:33:32.511  4501  4591 D BtGatt.AdvertiseManager: message : 0
,11-18 08:33:32.514  4501  4591 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 08:33:32.526  4501  4582 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 08:33:32.534  4501  4582 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 08:33:32.535  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.535  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.535  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 08:33:32.535  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.536  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.536  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.536  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.536  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.536  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 08:33:32.538  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 08:33:32.538  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.539  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.539  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:32.539  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:32.540  5582  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-18 08:33:32.540  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 08:33:32.540  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.540  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:32.540  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 08:33:32.540  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.541  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.541  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 08:33:32.541  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 08:33:32.544  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.544  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 08:33:32.545  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.545  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:32.545  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 08:33:32.545  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 08:33:33.044  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-18 08:33:33.045  5582  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-18 08:33:33.045  5582  5628 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 08:33:33.045  5582  5628 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-18 08:33:33.045  5582  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-18 08:33:33.045  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-18 08:33:33.046  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.046  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.046  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 08:33:33.047  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 08:33:33.050  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.051  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-18 08:33:33.052  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.052  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.052  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.054  4501  4591 D BtGatt.AdvertiseManager: message : 1
11-18 08:33:33.055  4501  4591 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 08:33:33.069  4501  4582 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 08:33:33.069  4501  4582 D BtGatt.GattService: Client app is not null!
11-18 08:33:33.071  4501  4712 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 08:33:33.072  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 08:33:33.072  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.072  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:33.072  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.072  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.072  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.072  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 08:33:33.073  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.073  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.073  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.073  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 08:33:33.073  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 08:33:33.073  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:33.074  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
11-18 08:33:33.074  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:33.074  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 08:33:33.074  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 08:33:33.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:33.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.075  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.077  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:33.081  4501  4712 D BtGatt.GattService: registerClient() - UUID=42579073-9e58-4c4b-8c53-a67c6eaed2e6
11-18 08:33:33.082  4501  4582 D BtGatt.GattService: onClientRegistered() - UUID=42579073-9e58-4c4b-8c53-a67c6eaed2e6, clientIf=5
11-18 08:33:33.083  5582  5593 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 08:33:33.085  4501  4591 D BtGatt.AdvertiseManager: message : 0
,11-18 08:33:33.090  4501  4591 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 08:33:33.107  4501  4582 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 08:33:33.116  4501  4582 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 08:33:33.117  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.118  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.118  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-18 08:33:33.118  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.118  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.118  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.119  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.119  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.119  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.119  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:33.119  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.120  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 08:33:33.120  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 08:33:33.121  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-18 08:33:33.121  5582  5628 I io.jxcore.node.ConnectionHelper: start: OK
,11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-18 08:33:33.122  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 08:33:33.122  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 08:33:33.123  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.123  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.123  5582  5628 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-18 08:33:33.123  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-18 08:33:33.123  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-18 08:33:33.123  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 08:33:33.123  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 08:33:33.123  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 08:33:33.123  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 08:33:33.123  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 08:33:33.124  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 08:33:33.124  5582  5633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 08:33:33.124  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 08:33:33.124  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 08:33:33.124  5582  5633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 08:33:33.124  5582  5633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.124  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.125  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:33.125  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 08:33:33.126  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:33.126  5582  5628 D BluetoothLeScanner: could not find callback wrapper
,11-18 08:33:33.126  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 08:33:33.127  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.127  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.127  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.127  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 08:33:33.127  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.128  4501  4591 D BtGatt.AdvertiseManager: message : 1
,11-18 08:33:33.129  4501  4591 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 08:33:33.136  4501  4582 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 08:33:33.136  4501  4582 D BtGatt.GattService: Client app is not null!
,11-18 08:33:33.139  4501  4736 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 08:33:33.139  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 08:33:33.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:33.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 08:33:33.140  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-18 08:33:33.141  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 08:33:33.141  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.142  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.142  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:33.142  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.142  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.142  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 08:33:33.143  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-18 08:33:33.143  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 08:33:33.143  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 08:33:33.143  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 08:33:33.143  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:33.143  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:33.143  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.143  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 08:33:33.143  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 08:33:33.143  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.144  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.144  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 08:33:33.144  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.145  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-18 08:33:33.145  5582  5628 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-18 08:33:33.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.145  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:33.147  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-18 08:33:33.147  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-18 08:33:33.148  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-18 08:33:33.148  5582  5628 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-18 08:33:33.149  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-18 08:33:33.149  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-18 08:33:33.150  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-18 08:33:33.150  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:33.151  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:33.151  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:33.151  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-18 08:33:33.152  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-18 08:33:33.152  5582  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-18 08:33:33.152  5582  5628 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 08:33:33.155  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-18 08:33:33.155  5582  5628 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-18 08:33:33.157  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-18 08:33:33.157  5582  5628 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-18 08:33:33.158  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-18 08:33:33.158  5582  5628 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-18 08:33:33.158  5582  5628 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-18 08:33:33.158  5582  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-18 08:33:33.158  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 08:33:33.158  5582  5628 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-18 08:33:33.158  5582  5628 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 08:33:33.159  5582  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-18 08:33:33.159  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 08:33:33.159  5582  5628 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-18 08:33:33.159  5582  5628 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-18 08:33:33.159  5582  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-18 08:33:33.159  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 08:33:33.159  5582  5628 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-18 08:33:33.162  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-18 08:33:33.163  5582  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-18 08:33:33.163  5582  5628 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-18 08:33:33.163  5582  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-18 08:33:33.163  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-18 08:33:33.163  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.165  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.165  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.165  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:33.166  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 08:33:33.166  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 08:33:33.166  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:33.166  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 08:33:33.167  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 08:33:33.167  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 08:33:33.167  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 08:33:33.167  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 08:33:33.167  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 08:33:33.167  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:33.167  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-18 08:33:33.167  5582  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 08:33:33.168  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
1,1-18 08:33:33.168  5582  5637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:33.164  4736  4736 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:33.167  4736  4736 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:33.170  5582  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 08:33:33.174  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 08:33:33.174  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 08:33:33.174  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-18 08:33:33.181  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.181  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 08:33:33.181  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:33.181  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 08:33:33.181  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-18 08:33:33.184  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.184  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.184  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 08:33:33.184  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 08:33:33.184  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:33.184  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-18 08:33:33.184  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:33.185  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:33.185  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.185  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 08:33:33.185  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-18 08:33:33.185  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.185  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.185  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.186  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:33.189  4501  4736 D BtGatt.GattService: registerClient() - UUID=f7bd442d-afa1-4464-bc27-1c254ae4b62e
11-18 08:33:33.189  4501  4582 D BtGatt.GattService: onClientRegistered() - UUID=f7bd442d-afa1-4464-bc27-1c254ae4b62e, clientIf=5
11-18 08:33:33.189  5582  5593 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-18 08:33:33.190  4501  4591 D BtGatt.AdvertiseManager: message : 0
11-18 08:33:33.192  4501  4591 D BtGatt.AdvertiseManager: starting multi advertising
11-18 08:33:33.201  4501  4582 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-18 08:33:33.206  4501  4582 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-18 08:33:33.207  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.207  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.207  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 08:33:33.207  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.207  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.207  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.208  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.208  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.208  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 08:33:33.209  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 08:33:33.209  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.210  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.210  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.210  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.210  5582  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-18 08:33:33.210  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:33.210  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.211  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 08:33:33.211  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.214  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.214  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 08:33:33.214  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.214  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.214  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.214  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 08:33:33.711  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-18 08:33:33.711  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 08:33:33.712  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 08:33:33.712  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 08:33:33.712  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-18 08:33:33.712  5582  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 08:33:33.712  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 08:33:33.712  5582  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 08:33:33.713  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-18 08:33:33.713  5582  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 08:33:33.713  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 08:33:33.713  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 08:33:33.713  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 08:33:33.714  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5564a16 removed from the list
11-18 08:33:33.714  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 08:33:33.714  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 08:33:33.714  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 08:33:33.714  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 08:33:33.714  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 08:33:33.714  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.715  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.715  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.715  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.715  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-18 08:33:33.718  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:33.718  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 08:33:33.721  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:33.721  5582  5628 D BluetoothLeScanner: could not find callback wrapper
11-18 08:33:33.721  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-18 08:33:33.721  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.721  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.722  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.722  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 08:33:33.722  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.724  4501  4591 D BtGatt.AdvertiseManager: message : 1
,11-18 08:33:33.726  4501  4591 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 08:33:33.736  4501  4582 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-18 08:33:33.736  4501  4582 D BtGatt.GattService: Client app is not null!
11-18 08:33:33.737  4501  4712 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 08:33:33.737  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 08:33:33.737  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.737  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:33.738  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.738  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.738  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:33.738  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 08:33:33.738  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 08:33:33.738  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 08:33:33.739  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.740  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.740  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 08:33:33.740  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.740  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:33.740  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3546f97 removed from the list
11-18 08:33:33.740  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:33.741  5582  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-18 08:33:33.741  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 08:33:33.741  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-18 08:33:33.741  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:33.741  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.741  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 08:33:33.741  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-18 08:33:33.741  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.741  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-18 08:33:33.741  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 08:33:33.741  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.744  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.744  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.744  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:33.744  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 08:33:33.744  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 08:33:34.245  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 08:33:38.745  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-18 08:33:38.747  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 08:33:38.748  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 08:33:38.748  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-18 08:33:38.756  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 08:33:38.757  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 08:33:38.757  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-18 08:33:38.757  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 08:33:38.758  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 08:33:38.758  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 08:33:38.758  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 08:33:38.758  5582  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 08:33:38.759  5582  5638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 08:33:38.759  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-18 08:33:38.760  5582  5628 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-18 08:33:38.761  5582  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-18 08:33:38.761  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-18 08:33:38.761  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:38.761  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-18 08:33:38.757  4736  4736 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31932]" dev="sockfs" ino=31932 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:38.757  4736  4736 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31932]" dev="sockfs" ino=31932 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-18 08:33:38.762  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-18 08:33:38.763  5582  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-18 08:33:38.771  5582  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-18 08:33:38.772  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 08:33:38.772  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 08:33:38.772  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 08:33:38.772  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 08:33:38.773  5582  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 08:33:38.773  5582  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 08:33:38.773  5582  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-18 08:33:38.773  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 08:33:38.773  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-18 08:33:38.775  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-18 08:33:38.775  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 08:33:38.776  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 08:33:38.776  5582  5628 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5564a16 not in the list
11-18 08:33:38.776  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-18 08:33:38.776  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 08:33:38.776  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-18 08:33:38.776  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 08:33:38.777  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 08:33:38.777  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:38.779  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:38.779  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:38.779  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:38.779  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:38.779  5582  5628 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3546f97 not in the list
11-18 08:33:38.779  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:38.779  5582  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-18 08:33:38.779  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:38.779  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:38.781  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-18 08:33:38.782  5582  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-18 08:33:38.783  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-18 08:33:38.783  5582  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-18 08:33:38.783  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-18 08:33:38.783  5582  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-18 08:33:38.783  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-18 08:33:38.784  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-18 08:33:38.785  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-18 08:33:38.786  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-18 08:33:38.786  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-18 08:33:38.786  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-18 08:33:38.787  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-18 08:33:38.787  5582  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-18 08:33:38.787  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 08:33:38.788  5582  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-18 08:33:38.788  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-18 08:33:38.788  5582  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-18 08:33:38.788  5582  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-18 08:33:38.788  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-18 08:33:38.789  5582  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-18 08:33:38.789  5582  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-18 08:33:38.789  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-18 08:33:38.789  5582  5628 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-18 08:33:38.790  5582  5628 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-18 08:33:38.790  5582  5628 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-18 08:33:38.790  5582  5628 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-18 08:33:38.791  5582  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-18 08:33:38.792  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 08:33:38.792  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e9cfdd added. We now have 3 listener(s)
11-18 08:33:38.794  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:38.794  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 08:33:38.794  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 08:33:38.795  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 08:33:38.795  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd10752 added. We now have 3 listener(s)
11-18 08:33:38.795  5582  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-18 08:33:38.796  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-18 08:33:38.799  5582  5628 D BluetoothAdapter: enable(): BT is already enabled..!
11-18 08:33:38.800   928  3720 D WifiService: setWifiEnabled: true pid=5582, uid=10077
,11-18 08:33:38.800   928  3720 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 08:33:38.801  5582  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-18 08:33:38.805  5582  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-18 08:33:38.806  5582  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-18 08:33:38.809  5582  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-18 08:33:38.810  5582  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 08:33:38.815  5582  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 08:33:38.818  5582  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-18 08:33:38.818  4501  4573 D BluetoothAdapterState: Current state: ON, message: 23
11-18 08:33:38.818  4501  4573 D BluetoothAdapterProperties: Setting state to 13
11-18 08:33:38.818  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-18 08:33:38.819  4501  4573 D BluetoothAdapterProperties: onBluetoothDisable()
11-18 08:33:38.820  4501  4573 I BluetoothAdapterState: Entering PendingCommandState
,11-18 08:33:38.821  4501  4501 D BluetoothMapService: onReceive
,11-18 08:33:38.822  4501  4501 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 08:33:38.822  4501  4501 D BluetoothMapService: STATE_TURNING_OFF
,11-18 08:33:38.822  4501  4501 D BluetoothMapService: MAP Service closeService in
11-18 08:33:38.822  4501  4501 D BluetoothMapMasInstance0: MAP Service shutdown
11-18 08:33:38.822  4501  4501 D ObexServerSockets0: shutdown(block = true)
11-18 08:33:38.823  4501  4501 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 08:33:38.823  4501  4501 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-18 08:33:38.823  4501  4710 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-18 08:33:38.824  4501  4741 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-18 08:33:38.824  4501  4739 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-18 08:33:38.827  4501  4501 I BtOppRfcommListener: stopping Accept Thread
11-18 08:33:38.827  4501  5273 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-18 08:33:38.828  4501  5273 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-18 08:33:38.838   928   941 I ActivityManager: Start proc 5641:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-18 08:33:38.839  4501  4582 D BluetoothAdapterProperties: Scan Mode:20
11-18 08:33:38.840  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-18 08:33:38.842  4501  4501 D HeadsetService: Received stop request...Stopping profile...
,11-18 08:33:38.844  3702  3908 D BluetoothHeadset: Proxy object disconnected
11-18 08:33:38.844  3032  3886 D BluetoothHeadset: Proxy object disconnected
,11-18 08:33:38.845  3032  3032 D HeadsetProfile: Bluetooth service disconnected
11-18 08:33:38.845  4501  4501 D A2dpService: Received stop request...Stopping profile...
11-18 08:33:38.845   928   928 D BluetoothHeadset: Proxy object disconnected
11-18 08:33:38.845   928   928 D BluetoothHeadset: Proxy object disconnected
11-18 08:33:38.845   928   928 D BluetoothHeadset: Proxy object disconnected
11-18 08:33:38.845  4501  4715 D A2dpStateMachine: Exit Disconnected: -1
,11-18 08:33:38.847  3032  3032 D BluetoothA2dp: Proxy object disconnected
11-18 08:33:38.847   928   928 D BluetoothA2dp: Proxy object disconnected
11-18 08:33:38.847  4501  4501 V BluetoothAdapterState: isTurningOff()=true
11-18 08:33:38.848  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.848  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.848  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:38.848  4501  4501 D HidService: Received stop request...Stopping profile...
11-18 08:33:38.848  4501  4501 D HidService: Stopping Bluetooth HidService
,11-18 08:33:38.851  3032  3032 D BluetoothInputDevice: Proxy object disconnected
,11-18 08:33:38.852  3032  3032 D HidProfile: Bluetooth service disconnected
,11-18 08:33:38.854  4501  4501 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-18 08:33:38.854  4501  4501 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-18 08:33:38.854  4501  4705 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 08:33:38.854  4501  4705 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 08:33:38.854  4501  4705 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-18 08:33:38.855  4501  4582 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-18 08:33:38.855  4501  4582 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-18 08:33:38.855  4501  4501 D HealthService: Received stop request...Stopping profile...
11-18 08:33:38.856  4501  4501 V BluetoothAdapterState: isTurningOff()=true
11-18 08:33:38.856  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.856  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.856  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:38.857  4501  4501 D PanService: Received stop request...Stopping profile...
11-18 08:33:38.859  3032  3032 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-18 08:33:38.859  3032  3032 D PanProfile: Bluetooth service disconnected
11-18 08:33:38.860  4501  4705 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 08:33:38.860  4501  4705 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-18 08:33:38.860  4501  4582 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-18 08:33:38.861  4501  4705 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 08:33:38.861  4501  4705 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-18 08:33:38.861  4501  4705 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-18 08:33:38.861  4501  4705 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-18 08:33:38.865  4501  4501 D BluetoothMapService: Received stop request...Stopping profile...
,11-18 08:33:38.865  4501  4501 D BluetoothMapService: stop()
,11-18 08:33:38.866  4501  4501 D BluetoothMapAppObserver: deinitObservers()
,11-18 08:33:38.866  4501  4501 D BluetoothMapAppObserver: removeReceiver()
11-18 08:33:38.867  4501  4501 V BluetoothAdapterState: isTurningOff()=true
11-18 08:33:38.867  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.867  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.867  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:38.867  3032  3032 D BluetoothMap: Proxy object disconnected
11-18 08:33:38.867  3032  3032 D MapProfile: Bluetooth service disconnected
,11-18 08:33:38.868  4501  4501 D SapService: Received stop request...Stopping profile...
11-18 08:33:38.868  4501  4501 V SapService: stop()
11-18 08:33:38.869  4501  4501 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-18 08:33:38.869  4501  4501 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-18 08:33:38.869  4501  4501 V BluetoothAdapterState: isTurningOff()=true
11-18 08:33:38.869  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.869  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.870  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 08:33:38.870  4501  4501 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-18 08:33:38.870  4501  4501 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-18 08:33:38.870  4501  4501 V BluetoothAdapterState: isTurningOff()=true
,11-18 08:33:38.869  4501  4582 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-18 08:33:38.870  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.870  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.870  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:38.870  4501  4582 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-18 08:33:38.871  4501  4501 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-18 08:33:38.871  4501  4501 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-18 08:33:38.872  4501  4501 D BluetoothMapService: MAP Service closeService in
11-18 08:33:38.872  4501  4501 V BluetoothAdapterState: isTurningOff()=true
11-18 08:33:38.872  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.872  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.873  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
,11-18 08:33:38.873  4501  4501 D BluetoothMapService: cleanup()
11-18 08:33:38.873  4501  4501 D BluetoothMapService: MAP Service closeService in
11-18 08:33:38.873  4501  4501 V BluetoothAdapterState: isTurningOff()=true
11-18 08:33:38.873  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:38.873  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:38.873  4501  4501 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:38.874  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-18 08:33:38.874  4501  4573 D BluetoothAdapterProperties: Setting state to 15
11-18 08:33:38.874  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-18 08:33:38.874  3032  3886 D BluetoothPan: onBluetoothStateChange on: false
11-18 08:33:38.875   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 08:33:38.875  4501  4573 I BluetoothAdapterState: Entering BleOnState
11-18 08:33:38.875  3032  3044 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 08:33:38.876   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 08:33:38.876  3032  3045 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-18 08:33:38.877  3032  3831 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 08:33:38.877  3032  3886 D BluetoothMap: onBluetoothStateChange: up=false
11-18 08:33:38.878  3702  3907 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 08:33:38.878   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-18 08:33:38.878  3032  3044 D BluetoothPbap: onBluetoothStateChange: up=false
11-18 08:33:38.879   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-18 08:33:38.880  4501  4573 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-18 08:33:38.880  4501  4573 D BluetoothAdapterProperties: Setting state to 16
11-18 08:33:38.880  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-18 08:33:38.883  4501  4573 D BluetoothAdapterProperties: onBleDisable
11-18 08:33:38.883  4501  4573 I BluetoothAdapterState: Entering PendingCommandState
11-18 08:33:38.883  4501  4576 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-18 08:33:38.884  4501  4582 D BluetoothAdapterProperties: Scan Mode:20
,11-18 08:33:38.886  4501  4705 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-18 08:33:38.886  4501  4705 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-18 08:33:38.890  5641  5641 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-18 08:33:38.905  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 08:33:38.911   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4613453:true
,11-18 08:33:38.912  3478  3478 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 08:33:38.927   928  4143 I ActivityManager: Start proc 5653:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-18 08:33:38.933  5641  5641 D LocalBluetoothProfileManager: Adding local MAP profile
,11-18 08:33:38.935  5641  5641 D BluetoothMap: Create BluetoothMap proxy object
,11-18 08:33:38.943  5641  5641 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-18 08:33:38.950  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,11-18 08:33:38.958   928  3062 I ActivityManager: Killing 4902:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-18 08:33:38.975  5653  5653 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-18 08:33:39.091  4501  4582 I bt_hci  : shut_down
,11-18 08:33:39.096  4501  4593 I bt_vendor: low_power_mode_cb
,11-18 08:33:39.098  4501  4593 D bt_hwcfg: hw_epilog_process
,11-18 08:33:39.101  4501  4593 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-18 08:33:39.101  4501  4593 I bt_vendor: epilog_cb
11-18 08:33:39.101  4501  4593 I bt_hci  : epilog_finished_callback
11-18 08:33:39.103  4501  4582 I bt_hci_h4: hal_close
11-18 08:33:39.104  4501  4582 I bt_userial_vendor: device fd = 54 close
,11-18 08:33:39.170  5653  5653 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.170  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.k.d(PG:583)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.e.b(PG:170)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.File.exists(File.java:361)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.171  5653  5653 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-18 08:33:39.171  5653  5653 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-18 08:33:39.175  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-18 08:33:39.181  3478  3478 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 08:33:39.184  5641  5641 D DockEventReceiver: finishStartingService: stopping service
11-18 08:33:39.188   928  3315 I ActivityManager: Killing 5358:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-18 08:33:39.218  4501  4576 D bt_stack_manager: event_shut_down_stack finished.
11-18 08:33:39.218  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-18 08:33:39.220  4501  4573 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-18 08:33:39.220  4501  4501 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 08:33:39.220  4501  4501 D BtGatt.GattService: Received stop request...Stopping profile...
11-18 08:33:39.220  4501  4501 D BtGatt.GattService: stop()
11-18 08:33:39.220  4501  4501 D BtGatt.AdvertiseManager: advertise clients cleared
11-18 08:33:39.222  4501  4501 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:39.222  4501  4501 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:39.222  4501  4501 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:39.222  4501  4501 V BluetoothAdapterState: isBleTurningOff()=true
11-18 08:33:39.222  4501  4573 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-18 08:33:39.223  4501  4573 D BluetoothAdapterProperties: Setting state to 10
11-18 08:33:39.223  4501  4573 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-18 08:33:39.223  4501  4573 I BluetoothAdapterState: Entering OffState
11-18 08:33:39.224   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-18 08:33:39.234  4501  4501 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-18 08:33:39.234  4501  4501 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-18 08:33:39.234  4501  4501 I BluetoothServiceJni: cleanupNative: return from cleanup
11-18 08:33:39.236  4501  4576 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-18 08:33:39.245  4501  4501 I art     : System.exit called, status: 0
11-18 08:33:39.245  4501  4501 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-18 08:33:39.280  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 08:33:39.286   928  4143 I ActivityManager: Process com.android.bluetooth (pid 4501) has died
,11-18 08:33:39.319  5582  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 08:33:39.319  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-18 08:33:39.319  5582  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-18 08:33:39.320  5582  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 08:33:39.322  5582  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 08:33:39.334   928   945 I ActivityManager: Start proc 5685:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-18 08:33:39.389  5685  5685 D AdapterServiceConfig: Adding HeadsetService
,11-18 08:33:39.389  5685  5685 D AdapterServiceConfig: Adding A2dpService
11-18 08:33:39.390  5685  5685 D AdapterServiceConfig: Adding HidService
11-18 08:33:39.390  5685  5685 D AdapterServiceConfig: Adding HealthService
,11-18 08:33:39.390  5685  5685 D AdapterServiceConfig: Adding PanService
11-18 08:33:39.390  5685  5685 D AdapterServiceConfig: Adding GattService
,11-18 08:33:39.390  5685  5685 D AdapterServiceConfig: Adding BluetoothMapService
11-18 08:33:39.390  5685  5685 D AdapterServiceConfig: Adding SapService
11-18 08:33:39.394  5653  5673 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-18 08:33:39.401   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a295d8:true
,11-18 08:33:39.401  5685  5685 D BluetoothAdapterState: make() - Creating AdapterState
,11-18 08:33:39.404   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65f7c16:true
,11-18 08:33:39.404  5685  5685 I bt_bluedroid: init
,11-18 08:33:39.405  5685  5697 I BluetoothAdapterState: Entering OffState
,11-18 08:33:39.407  5685  5699 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-18 08:33:39.408  5685  5699 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-18 08:33:39.408  5685  5699 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-18 08:33:39.408  5685  5699 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-18 08:33:39.409  5685  5685 I bt_bluedroid: get_profile_interface socket
,11-18 08:33:39.410  5685  5702 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-18 08:33:39.411  5685  5685 I bt_bluedroid: get_profile_interface sdp
11-18 08:33:39.411  5685  5702 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 08:33:39.415  5685  5696 I bt_bluedroid: config_hci_snoop_log
11-18 08:33:39.416   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-18 08:33:39.420  5685  5697 D BluetoothAdapterState: Current state: OFF, message: 0
,11-18 08:33:39.420  5685  5697 D BluetoothAdapterProperties: Setting state to 14
11-18 08:33:39.420  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-18 08:33:39.421  5685  5697 D BluetoothBondStateMachine: make
11-18 08:33:39.422  5685  5703 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-18 08:33:39.424  5685  5697 I BluetoothAdapterState: Entering PendingCommandState
,11-18 08:33:39.425  5685  5685 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-18 08:33:39.427  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
,11-18 08:33:39.428  5685  5685 D BtGatt.DebugUtils: handleDebugAction() action=null
11-18 08:33:39.429  5685  5685 D BtGatt.GattService: Received start request. Starting profile...
11-18 08:33:39.429  5685  5685 D BtGatt.GattService: start()
11-18 08:33:39.429  5685  5685 I bt_bluedroid: get_profile_interface gatt
,11-18 08:33:39.429  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
11-18 08:33:39.430  5685  5685 D BtGatt.AdvertiseManager: advertise manager created
,11-18 08:33:39.434  5685  5685 V BluetoothAdapterState: isTurningOff()=false
,11-18 08:33:39.434  5685  5685 V BluetoothAdapterState: isTurningOn()=false
11-18 08:33:39.434  5685  5685 V BluetoothAdapterState: isBleTurningOn()=true
11-18 08:33:39.434  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:39.435  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-18 08:33:39.436  5685  5697 I bt_bluedroid: bt_bluedroid
11-18 08:33:39.436  5685  5699 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-18 08:33:39.436  5685  5699 I bt_hci  : start_up
,11-18 08:33:39.441  5685  5699 I bt_vendor: alloc value 0xf3eff871
,11-18 08:33:39.441  5685  5699 I bt_vendor: init
11-18 08:33:39.441  5685  5699 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-18 08:33:39.441  5685  5699 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-18 08:33:39.551  5685  5699 D bt_hci  : start_up starting async portion
,11-18 08:33:39.552  5685  5707 I bt_hci  : event_finish_startup
,11-18 08:33:39.552  5685  5707 I bt_hci_h4: hal_open
11-18 08:33:39.552  5685  5707 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-18 08:33:39.556  5685  5707 I bt_userial_vendor: device fd = 54 open
,11-18 08:33:39.550  5708  5708 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 08:33:39.571  5685  5707 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 08:33:39.575  5685  5707 D bt_hwcfg: Chipset BCM4358A3
,11-18 08:33:39.575  5685  5707 D bt_hwcfg: Target name = [BCM4358A3]
11-18 08:33:39.576  5685  5707 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-18 08:33:39.832  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 08:33:40.075  5685  5707 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-18 08:33:40.076  5685  5707 D bt_hwcfg: Settlement delay -- 100 ms
,11-18 08:33:40.076  5685  5707 I bt_hwcfg: Setting fw settlement delay to 100 
,11-18 08:33:40.202  5685  5707 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-18 08:33:40.202  5685  5707 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-18 08:33:40.204  5685  5707 I bt_hwcfg: vendor lib fwcfg completed
,11-18 08:33:40.204  5685  5707 I bt_vendor: firmware callback
,11-18 08:33:40.204  5685  5707 I bt_hci  : firmware_config_callback
,11-18 08:33:40.214  5685  5710 I bt_btu  : btu_task pending for preload complete event
11-18 08:33:40.215  5685  5710 I bt_btu_task: Bluetooth chip preload is complete
,11-18 08:33:40.215  5685  5710 I bt_btu  : btu_task received preload complete event
,11-18 08:33:40.220  5685  5710 I         : BTE_InitTraceLevels -- TRC_HCI
,11-18 08:33:40.220  5685  5710 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-18 08:33:40.220  5685  5710 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_AVDT
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_A2D
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_BNEP
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_BTM
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_GAP
,11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_PAN
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_SDP
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_GATT
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_SMP
11-18 08:33:40.221  5685  5710 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-18 08:33:40.222  5685  5710 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-18 08:33:40.314  5685  5710 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e7d549
,11-18 08:33:40.315  5685  5710 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e7d549 
,11-18 08:33:40.335  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-18 08:33:40.338  5685  5702 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,11-18 08:33:40.341  5685  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-18 08:33:40.341  5685  5702 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-18 08:33:40.343  5685  5702 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-18 08:33:40.346  5685  5702 D BluetoothAdapterProperties: Scan Mode:20
,11-18 08:33:40.347  5685  5702 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-18 08:33:40.347  5685  5702 D bt_hci  : do_postload posting postload work item
11-18 08:33:40.347  5685  5707 I bt_hci  : event_postload
,11-18 08:33:40.347  5685  5707 I bt_vendor: sco_config_cb
11-18 08:33:40.347  5685  5707 I bt_hci  : sco_config_callback postload finished.
11-18 08:33:40.349  5685  5702 D bt_bte_conf: Device ID record 1 : primary
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   vendorId            = 000f
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   vendorIdSource      = 0001
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   product             = 1200
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   version             = 1436
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   clientExecutableURL = 
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   serviceDescription  = 
11-18 08:33:40.350  5685  5702 D bt_bte_conf:   documentationURL    = 
11-18 08:33:40.350  5685  5702 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-18 08:33:40.351  5685  5699 D bt_stack_manager: event_start_up_stack finished
11-18 08:33:40.352  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-18 08:33:40.352  5685  5697 D BluetoothAdapterProperties: Setting state to 15
11-18 08:33:40.352  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-18 08:33:40.354  5685  5697 I BluetoothAdapterState: Entering BleOnState
,11-18 08:33:40.358  5685  5707 I bt_vendor: low_power_mode_cb
,11-18 08:33:40.360  5685  5697 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-18 08:33:40.360  5685  5697 D BluetoothAdapterProperties: Setting state to 11
11-18 08:33:40.360  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-18 08:33:40.368  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
,11-18 08:33:40.370  5685  5685 D HeadsetService: Received start request. Starting profile...
,11-18 08:33:40.373  5685  5685 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-18 08:33:40.374  5685  5685 D HeadsetStateMachine: make
,11-18 08:33:40.384  5685  5685 D HeadsetStateMachine: max_hf_connections = 1
,11-18 08:33:40.384  5685  5685 I bt_bluedroid: get_profile_interface handsfree
11-18 08:33:40.385  5685  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-18 08:33:40.385  5685  5702 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-18 08:33:40.386  5685  5697 I BluetoothAdapterState: Entering PendingCommandState
,11-18 08:33:40.388  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
11-18 08:33:40.388  5685  5685 D A2dpService: Received start request. Starting profile...
11-18 08:33:40.389  5685  5685 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-18 08:33:40.389  5685  5685 I bt_bluedroid: get_profile_interface avrcp
,11-18 08:33:40.395  5685  5685 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-18 08:33:40.395  5685  5685 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-18 08:33:40.395  5685  5685 D A2dpStateMachine: make
,11-18 08:33:40.397  5685  5685 I bt_bluedroid: get_profile_interface a2dp
,11-18 08:33:40.399  5685  5718 D A2dpStateMachine: Enter Disconnected: -2
,11-18 08:33:40.401  5685  5685 I BluetoothHidServiceJni: classInitNative: succeeds
,11-18 08:33:40.402  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
,11-18 08:33:40.402  3478  3478 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-18 08:33:40.398  5685  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-18 08:33:40.403  5641  5641 D BluetoothInputDevice: Proxy object connected
11-18 08:33:40.404  5641  5641 D HidProfile: Bluetooth service connected
11-18 08:33:40.404  5685  5685 D HidService: Received start request. Starting profile...
11-18 08:33:40.404  5685  5685 I bt_bluedroid: get_profile_interface hidhost
,11-18 08:33:40.405  5685  5685 D HidService: setHidService(): set to: null
11-18 08:33:40.405  5685  5702 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e5e56d
11-18 08:33:40.405  5685  5702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-18 08:33:40.405  5685  5685 I BluetoothHealthServiceJni: classInitNative: succeeds
11-18 08:33:40.406  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
11-18 08:33:40.407  5685  5685 D HealthService: Received start request. Starting profile...
,11-18 08:33:40.409  5685  5685 I bt_bluedroid: get_profile_interface health
,11-18 08:33:40.410  5685  5685 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-18 08:33:40.410  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
,11-18 08:33:40.411  5685  5685 D PanService: Received start request. Starting profile...
11-18 08:33:40.412  5641  5641 D BluetoothPan: BluetoothPAN Proxy object connected
,11-18 08:33:40.412  5685  5685 D BluetoothPanServiceJni: initializeNative(L110): pan
11-18 08:33:40.412  5685  5685 I bt_bluedroid: get_profile_interface pan
11-18 08:33:40.412  5685  5702 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-18 08:33:40.412  5641  5641 D PanProfile: Bluetooth service connected
,11-18 08:33:40.416  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
,11-18 08:33:40.417  5641  5641 D BluetoothMap: Proxy object connected
11-18 08:33:40.417  5685  5685 D BluetoothMapService: Received start request. Starting profile...
11-18 08:33:40.417  5685  5685 D BluetoothMapService: start()
,11-18 08:33:40.418  5641  5641 D MapProfile: Bluetooth service connected
,11-18 08:33:40.418  5641  5641 D BluetoothMap: getConnectedDevices()
11-18 08:33:40.419  5641  5641 D BluetoothMap: Bluetooth is Not enabled
,11-18 08:33:40.420  5685  5685 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-18 08:33:40.421  5685  5685 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-18 08:33:40.421  5685  5685 D BluetoothMapAppObserver: createReceiver()
11-18 08:33:40.422  5685  5685 D BluetoothMapAppObserver: initObservers()
11-18 08:33:40.422  5685  5685 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-18 08:33:40.429  5685  5685 V SapService: SapBinder()
11-18 08:33:40.429  5685  5685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
,11-18 08:33:40.430  5685  5685 D SapService: Received start request. Starting profile...
11-18 08:33:40.430  5685  5685 V SapService: start()
,11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isTurningOn()=true
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.432  5685  5715 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isTurningOn()=true
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.432  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOn()=true
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
,11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOn()=true
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOn()=true
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isTurningOn()=true
,11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:40.433  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.434  5685  5685 V BluetoothAdapterState: isTurningOff()=false
11-18 08:33:40.434  5685  5685 V BluetoothAdapterState: isTurningOn()=true
11-18 08:33:40.434  5685  5685 V BluetoothAdapterState: isBleTurningOn()=false
11-18 08:33:40.434  5685  5685 V BluetoothAdapterState: isBleTurningOff()=false
11-18 08:33:40.435  5685  5697 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-18 08:33:40.435  5685  5697 D BluetoothAdapterProperties: ScanMode =  20
,11-18 08:33:40.435  5685  5697 D BluetoothAdapterProperties: State =  11
11-18 08:33:40.435  5685  5697 D BluetoothAdapterProperties: Setting state to 12
11-18 08:33:40.435  5685  5697 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-18 08:33:40.436  5685  5702 D BluetoothAdapterProperties: Scan Mode:21
11-18 08:33:40.436  5685  5702 D BluetoothAdapterProperties: Discoverable Timeout:120
11-18 08:33:40.436  5685  5697 I BluetoothAdapterState: Entering OnState
11-18 08:33:40.437  5641  5652 D BluetoothPbap: onBluetoothStateChange: up=true
,11-18 08:33:40.439  3032  3044 D BluetoothPan: onBluetoothStateChange on: true
,11-18 08:33:40.441  3032  3032 D BluetoothPan: BluetoothPAN Proxy object connected
11-18 08:33:40.441  5641  5651 D BluetoothPan: onBluetoothStateChange on: true
11-18 08:33:40.441  3032  3032 D PanProfile: Bluetooth service connected
11-18 08:33:40.441   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 08:33:40.441  3032  3045 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 08:33:40.443   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 08:33:40.443  5641  5652 D BluetoothMap: onBluetoothStateChange: up=true
11-18 08:33:40.443  3032  3886 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 08:33:40.444  3032  3032 D BluetoothA2dp: Proxy object connected
11-18 08:33:40.445  3032  3831 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-18 08:33:40.446  3032  3045 D BluetoothMap: onBluetoothStateChange: up=true
11-18 08:33:40.446  3032  3032 D BluetoothInputDevice: Proxy object connected
11-18 08:33:40.446  3032  3032 D HidProfile: Bluetooth service connected
11-18 08:33:40.447  3702  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 08:33:40.447   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-18 08:33:40.448  3032  3032 D BluetoothMap: Proxy object connected
11-18 08:33:40.448  3032  3032 D MapProfile: Bluetooth service connected
,11-18 08:33:40.448  3032  3032 D BluetoothMap: getConnectedDevices()
11-18 08:33:40.448   928   928 D BluetoothA2dp: Proxy object connected
11-18 08:33:40.449  5685  5685 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 08:33:40.449  3032  3045 D BluetoothPbap: onBluetoothStateChange: up=true
11-18 08:33:40.449  5685  5685 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-18 08:33:40.450   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-18 08:33:40.450  5641  5651 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-18 08:33:40.450  5685  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:40.452   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-18 08:33:40.453  5685  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:40.455  5685  5685 D ObexServerSockets: Succeed to create listening sockets 
11-18 08:33:40.455  5641  5641 D LocalBluetoothProfileManager: Adding local A2DP profile
11-18 08:33:40.455  5685  5685 D ObexServerSockets0: startAccept()
11-18 08:33:40.455  5685  5685 D ObexServerSockets0: prepareForNewConnect()
11-18 08:33:40.457  5685  5685 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-18 08:33:40.457  5685  5685 D BluetoothSdpJni: SDP Create record success - handle: 0
11-18 08:33:40.458  5685  5725 D ObexServerSockets0: Accepting socket connection...
11-18 08:33:40.458  5641  5641 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-18 08:33:40.458  5685  5685 D BluetoothMapService: onReceive
11-18 08:33:40.458  5685  5685 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-18 08:33:40.458  5685  5685 D BluetoothMapService: STATE_ON
11-18 08:33:40.459  5685  5726 D ObexServerSockets0: Accepting socket connection...
,11-18 08:33:40.462  5685  5727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 08:33:40.463  5685  5727 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-18 08:33:40.463  5685  5727 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-18 08:33:40.466  5641  5641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-18 08:33:40.468  5641  5641 D BluetoothA2dp: Proxy object connected
,11-18 08:33:40.473  3478  3478 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-18 08:33:40.481  3032  3032 D BluetoothPbap: Proxy object connected
11-18 08:33:40.481  3032  3032 D PbapServerProfile: Bluetooth service connected
,11-18 08:33:40.484  5641  5641 D DockEventReceiver: finishStartingService: stopping service
,11-18 08:33:40.485  5641  5641 D BluetoothPbap: Proxy object connected
11-18 08:33:40.485  5641  5641 D PbapServerProfile: Bluetooth service connected
11-18 08:33:40.486  5685  5685 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-18 08:33:40.486  5685  5685 D ObexServerSockets0: prepareForNewConnect()
,11-18 08:33:40.490  5685  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 08:33:40.502  5685  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-18 08:33:40.504  5685  5735 I BtOppRfcommListener: Accept thread started.
,11-18 08:33:40.543   928   945 D BluetoothHeadset: Proxy object connected
,11-18 08:33:40.543  3702  3726 D BluetoothHeadset: Proxy object connected
,11-18 08:33:40.544  3032  3831 D BluetoothHeadset: Proxy object connected
11-18 08:33:40.544  3032  3032 D HeadsetProfile: Bluetooth service connected
11-18 08:33:40.544   928   928 D BluetoothHeadset: Proxy object connected
11-18 08:33:40.544   928   928 D BluetoothHeadset: Proxy object connected
11-18 08:33:40.544   928   928 D BluetoothHeadset: Proxy object connected
11-18 08:33:40.547  3032  3886 D BluetoothHeadset: Proxy object connected
,11-18 08:33:40.547  3032  3032 D HeadsetProfile: Bluetooth service connected
,11-18 08:33:40.548  3702  3906 D BluetoothHeadset: Proxy object connected
,11-18 08:33:40.550   928   945 D BluetoothHeadset: Proxy object connected
,11-18 08:33:40.562  5641  5651 D BluetoothHeadset: Proxy object connected
11-18 08:33:40.563  5641  5641 D HeadsetProfile: Bluetooth service connected
,11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-18 08:33:40.847  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-18 08:33:40.853  5582  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-18 08:33:40.856  5582  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-18 08:33:40.859   928  3720 D WifiService: setWifiEnabled: false pid=5582, uid=10077
11-18 08:33:40.859   928  3720 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 08:33:40.864  5582  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-18 08:33:40.864   928  2858 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-18 08:33:40.864   928  2858 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-18 08:33:40.866   928  2858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 08:33:40.866   928  2858 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 08:33:40.885   928  5330 D DhcpClient: Clearing IP address
,11-18 08:33:40.885   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-18 08:33:40.890   508   924 D CommandListener: Setting iface cfg
,11-18 08:33:40.896   928  5331 D DhcpClient: Receive thread stopped
,11-18 08:33:40.903  3478  5383 V NativeCrypto: Read error: ssl=0x7f6ce29900: I/O error during system call, Connection timed out
11-18 08:33:40.906  3478  5383 V NativeCrypto: SSL shutdown failed: ssl=0x7f6ce29900: I/O error during system call, Broken pipe
,11-18 08:33:40.908   928  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-18 08:33:40.908   928  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-18 08:33:40.914   540   540 E Parcel  : Reading a NULL string not supported here.
,11-18 08:33:40.918   928   928 D RttService: SCAN_AVAILABLE : 1
,11-18 08:33:40.919   928  2986 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-18 08:33:40.922   928  2871 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-18 08:33:40.924   928  2858 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-18 08:33:40.925  3664  3805 W QCNEJ   : |CORE| network lost: 100
11-18 08:33:40.926  3664  3805 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-18 08:33:40.932   928  2858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-18 08:33:40.953   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 08:33:40.973   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 08:33:40.973   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-18 08:33:40.974   508   924 D TetherController: Setting IP forward enable = 0
11-18 08:33:40.974   928  2871 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-18 08:33:40.974   928  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 08:33:40.977   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-18 08:33:40.985  5244  5244 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@10172e3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-18 08:33:40.986   928  2858 D DhcpClient: doQuit
11-18 08:33:40.986   928  2858 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-18 08:33:40.987   928  5330 D DhcpClient: onQuitting
,11-18 08:33:40.987  4859  4859 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-18 08:33:40.988  3353  3353 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-18 08:33:40.992  3608  3608 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-18 08:33:40.996  4995  5018 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 08:33:40.997  4995  5018 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 08:33:40.997  4995  5018 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-18 08:33:40.997  4995  5018 E SarControlService: no key has been found,reset the power
11-18 08:33:40.997  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-18 08:33:40.997  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 08:33:40.997  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 08:33:40.998  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 08:33:40.998  5020  5020 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-18 08:33:41.000  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-18 08:33:41.000  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 08:33:41.000  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 08:33:41.000  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 08:33:41.000  5020  5020 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-18 08:33:41.005  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7c493a1 HexData = [00000000ea03000000000000ffffffff]
11-18 08:33:41.005  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 08:33:41.005  5020  5034 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-18 08:33:41.006  3353  3353 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-18 08:33:41.007  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 08:33:41.007  4995  5005 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-18 08:33:41.007  3608  3608 D SystemUpdateService: onCreate
11-18 08:33:41.012  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7c493a1 HexData = [00000000eb03000000000000ffffffff]
11-18 08:33:41.012  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 08:33:41.012  5020  5034 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-18 08:33:41.012  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 08:33:41.013  4995  5006 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-18 08:33:41.013  3608  3608 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 08:33:41.016  3353  3353 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-18 08:33:41.018   508   917 W SocketClient: write error (Broken pipe)
11-18 08:33:41.018   508   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-18 08:33:41.018   508   917 W SocketListener: Error sending broadcast (Broken pipe)
,11-18 08:33:41.023  3608  5753 I SystemUpdateService: active receiver: enabled
,11-18 08:33:41.026  3608  3608 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-18 08:33:41.031  3608  5356 I iu.UploadsManager: num queued entries: 0
,11-18 08:33:41.032  3608  5356 I iu.UploadsManager: num updated entries: 0
11-18 08:33:41.032  3608  5356 I iu.SyncManager: NEXT; no task
,11-18 08:33:41.034  3608  3608 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-18 08:33:41.036  3608  3608 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 08:33:41.036   508   924 E Netd    : netlink response contains error (No such file or directory)
11-18 08:33:41.037   508   924 D TetherController: Setting IP forward enable = 0
,11-18 08:33:41.038  3608  5753 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 08:33:41.040  3608  5753 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-18 08:33:41.041  3608  5753 I SystemUpdateService: now status is 0 (complete)
11-18 08:33:41.041  3608  5753 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-18 08:33:41.041  3608  5753 I SystemUpdateService: file has been verified
,11-18 08:33:41.041  3608  5753 I SystemUpdateService: OTA package size = 21989297
,11-18 08:33:41.046  3608  5753 I SystemUpdateService: showing system update notification
11-18 08:33:41.047   928   938 I ActivityManager: Start proc 5757:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-18 08:33:41.050  3353  3353 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-18 08:33:41.065  3608  3608 D SystemUpdateService: onDestroy
,11-18 08:33:41.067  3353  3353 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-18 08:33:41.085  5757  5757 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-18 08:33:41.088  5757  5757 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 08:33:41.095  5757  5757 D SprintDMHelper: simOperator: 
11-18 08:33:41.095  5757  5757 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 08:33:41.105  4969  5770 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-18 08:33:41.108   928  3053 I ActivityManager: Killing 5244:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-18 08:33:41.141   928  3053 I ActivityManager: Start proc 5771:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-18 08:33:41.167  5771  5771 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-18 08:33:41.170   928  2858 D wifi    : In wifi stop Hal
,11-18 08:33:41.170   928  2858 D wifi    : halHandle = 0x7f5b31f080, mVM = 0x7f7794d140, mCls = 0x100a02
11-18 08:33:41.170   928  3352 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-18 08:33:41.170   928  3352 D WifiHAL : Got a signal to exit!!!
,11-18 08:33:41.170   928  3352 I WifiHAL : Exit wifi_event_loop
11-18 08:33:41.171   928  2858 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-18 08:33:41.171   928  2858 E WifiHAL : Event processing terminated
11-18 08:33:41.171   928  2858 D wifi    : In wifi cleaned up handler
11-18 08:33:41.171   928  2858 I WifiHAL : Internal cleanup completed
11-18 08:33:41.172  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 08:33:41.173  3974  4133 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-18 08:33:41.179   928   938 I ActivityManager: Killing 4599:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-18 08:33:41.193   928  3352 D wifi    : set interface wlan0 flags (DOWN)
,11-18 08:33:41.193   928  2858 D WifiNative-HAL: HAL event thread stopped successfully
,11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 08:33:41.368  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 08:33:41.370  5582  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 08:33:41.373   928  3314 D WifiService: setWifiEnabled: true pid=5582, uid=10077
,11-18 08:33:41.373   928  3314 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 08:33:41.374  5582  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-18 08:33:41.396   928   945 D Tethering: InitialState.processMessage what=4
11-18 08:33:41.398   508   924 D SoftapController: Softap fwReload - Ok
11-18 08:33:41.400   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-18 08:33:41.401   508   924 D CommandListener: Setting iface cfg
,11-18 08:33:41.402   508   924 D CommandListener: Trying to bring down wlan0
11-18 08:33:41.403   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-18 08:33:41.407   928  2858 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-18 08:33:41.877   928  3062 D WifiService: setWifiEnabled: true pid=5582, uid=10077
,11-18 08:33:41.881   928  3062 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-18 08:33:42.019   928  2858 D wifi    : set interface wlan0 flags (UP)
,11-18 08:33:42.020   928  2858 I WifiHAL : Initializing wifi
,11-18 08:33:42.020   928  2858 I WifiHAL : Creating socket
11-18 08:33:42.027   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-18 08:33:42.028   928  2858 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-18 08:33:42.028   928  2858 D wifi    : Did set static halHandle = 0x7f5b31f080
11-18 08:33:42.028   928  2858 D wifi    : halHandle = 0x7f5b31f080, mVM = 0x7f7794d140, mCls = 0x159e
11-18 08:33:42.029   928  2858 D wifi    : array field set
,11-18 08:33:42.029   928  2858 I WifiNative-HAL: interface[0] = wlan0
,11-18 08:33:42.033   928  5787 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546990846080
,11-18 08:33:42.033   928  5787 D wifi    : waitForHalEvents called, vm = 0x7f7794d140, obj = 0x159e, env = 0x7f58ff2500
,11-18 08:33:42.116  5788  5788 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-18 08:33:42.138  5788  5788 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 08:33:42.139   928  2858 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-18 08:33:42.167  5788  5788 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-18 08:33:42.167  5788  5788 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-18 08:33:42.184   928  2858 D WifiConfigStore: Loading config and enabling all networks 
,11-18 08:33:42.192   928  2858 D WifiConfigStore: loaded 0 passpoint configs
,11-18 08:33:42.192   928  2858 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-18 08:33:42.193   928  2858 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-18 08:33:42.194   928  2858 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-18 08:33:42.195   928  2858 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-18 08:33:42.195   928  2858 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-18 08:33:42.195   928  2858 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-18 08:33:42.195   928  2858 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-18 08:33:42.198   928  2858 D WifiNative-HAL: Setting external_sim to 1
,11-18 08:33:42.198  4969  4969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-18 08:33:42.199   928  2858 D wifi    : setting dfs flag to true, 0x7f5e8564a0
11-18 08:33:42.199   928  2858 D WifiStateMachine: Setting OUI to DA-A1-19
11-18 08:33:42.199   928  2858 D wifi    : setting scan oui 0x7f5e8564a0
11-18 08:33:42.199   928  2858 D WifiHAL : Sending mac address OUI
,11-18 08:33:42.203   928  2858 E native  : do suspend false
,11-18 08:33:42.210   928   928 D RttService: SCAN_AVAILABLE : 3
11-18 08:33:42.210   928  2858 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-18 08:33:42.210   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-18 08:33:42.211   928  2986 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-18 08:33:42.211   508   924 D CommandListener: Setting iface cfg
,11-18 08:33:42.215   928  2852 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-18 08:33:42.215   928  2852 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-18 08:33:42.225   928  2852 D WifiNative-HAL: p2pGetDeviceAddress
,11-18 08:33:42.225   928  2852 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-18 08:33:42.231   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=216824 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-18 08:33:42.391  5582  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-18 08:33:42.395  5582  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-18 08:33:42.402  5582  5628 D BluetoothAdapter: enable(): BT is already enabled..!
,11-18 08:33:42.402   928  3062 D WifiService: setWifiEnabled: true pid=5582, uid=10077
11-18 08:33:42.402   928  3062 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-18 08:33:42.403  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 08:33:42.403  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 08:33:42.403  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 08:33:42.404  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e9cfdd removed from the list
11-18 08:33:42.404  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 08:33:42.404  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd10752 removed from the list
,11-18 08:33:42.404  5582  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-18 08:33:42.407  5582  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-18 08:33:42.408  5582  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-18 08:33:42.409  5582  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-18 08:33:42.410  5582  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-18 08:33:42.414  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-18 08:33:42.415  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-18 08:33:42.416  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-18 08:33:42.416  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-18 08:33:42.417  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-18 08:33:42.419  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-18 08:33:42.419  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9335e Bundle[{}]
11-18 08:33:42.420  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-18 08:33:42.420  5582  5628 I io.jxcore.node.LifeCycleMonitor: start: OK
11-18 08:33:42.420  5582  5628 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-18 08:33:42.421  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-18 08:33:42.421  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-18 08:33:42.421  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-18 08:33:42.421  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-18 08:33:42.422  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-18 08:33:42.422  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-18 08:33:42.422  5582  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-18 08:33:42.423  5582  5628 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-18 08:33:42.424  5582  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-18 08:33:42.426  5582  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-18 08:33:42.427  5582  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-18 08:33:42.427  5582  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-18 08:33:42.427  5582  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-18 08:33:42.428  5582  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-18 08:33:42.429  5582  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-18 08:33:42.429  5582  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-18 08:33:42.430  5582  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
11-18 08:33:42.431  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-18 08:33:42.431  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-18 08:33:42.432  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-18 08:33:42.432  5582  5628 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,11-18 08:33:42.432  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-18 08:33:42.433  5582  5628 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-18 08:33:42.433  5582  5628 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-18 08:33:42.433  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-18 08:33:42.434  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-18 08:33:42.435  5582  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-18 08:33:42.435  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-18 08:33:42.435  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e36b20 added. We now have 3 listener(s)
11-18 08:33:42.437  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:42.437  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-18 08:33:42.437  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-18 08:33:42.437  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-18 08:33:42.437  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b388cd9 added. We now have 3 listener(s)
11-18 08:33:42.437  5582  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-18 08:33:42.438  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-18 08:33:42.442  5582  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-18 08:33:42.443  5582  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-18 08:33:42.443  5582  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,11-18 08:33:42.443  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-18 08:33:42.443  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.443  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.443  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.443  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-18 08:33:42.443  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-18 08:33:42.443  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 08:33:42.443  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-18 08:33:42.443  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-18 08:33:42.446  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-18 08:33:42.446  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 08:33:42.446  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 08:33:42.446  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-18 08:33:42.447  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 08:33:42.447  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-18 08:33:42.447  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 08:33:42.447  5582  5791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-18 08:33:42.447  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:42.447  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 08:33:42.447  5582  5791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:42.447  5696  5696 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32022]" dev="sockfs" ino=32022 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:42.447  5696  5696 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32022]" dev="sockfs" ino=32022 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:42.451  5582  5791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 08:33:42.452  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 08:33:42.452  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-18 08:33:42.452  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 08:33:42.456  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.456  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-18 08:33:42.457  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:42.457  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 08:33:42.458  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-18 08:33:42.460  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.460  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.460  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 08:33:42.460  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 08:33:42.460  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:42.460  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
11-18 08:33:42.461  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:42.461  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:42.461  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.461  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 08:33:42.461  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:42.461  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.461  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.461  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.462  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:42.464  5685  5716 D BtGatt.GattService: registerClient() - UUID=22b08113-4fde-4ffd-9c0c-2efab0f523b7
,11-18 08:33:42.465  5685  5702 D BtGatt.GattService: onClientRegistered() - UUID=22b08113-4fde-4ffd-9c0c-2efab0f523b7, clientIf=5
,11-18 08:33:42.466  5582  5593 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-18 08:33:42.468  5685  5705 D BtGatt.AdvertiseManager: message : 0
11-18 08:33:42.469  5685  5705 D BtGatt.AdvertiseManager: starting multi advertising
,11-18 08:33:42.479  5685  5702 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-18 08:33:42.484  5685  5702 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-18 08:33:42.485  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.485  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.485  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 08:33:42.487  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 08:33:42.487  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:42.488  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.489  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.489  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:42.489  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:42.489  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.489  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:42.489  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 08:33:42.489  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.489  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.489  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:42.489  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.490  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-18 08:33:42.490  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 08:33:42.490  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.490  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.490  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-18 08:33:42.490  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 08:33:42.492  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.492  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-18 08:33:42.492  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.492  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.492  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:42.492  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-18 08:33:42.993  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-18 08:33:42.994  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 08:33:42.994  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 08:33:44.726   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-18 08:33:44.726   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-18 08:33:45.289  5788  5788 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 08:33:45.293  5788  5788 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 08:33:45.297  5788  5788 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-18 08:33:45.349   928  2858 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-18 08:33:45.351   928  2858 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-18 08:33:45.351   928  2858 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 08:33:45.365   928  2858 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-18 08:33:45.398   928  2858 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-18 08:33:45.400  5788  5788 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-18 08:33:45.831  5788  5788 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-18 08:33:45.865  5788  5788 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-18 08:33:45.866  5788  5788 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-18 08:33:45.879   928  2858 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 08:33:45.879   928  2858 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-18 08:33:45.879   928  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-18 08:33:45.896   928  2858 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-18 08:33:45.908   508   924 D CommandListener: Setting iface cfg
,11-18 08:33:45.914   928  2858 D WifiStateMachine: Start Dhcp Watchdog 2
,11-18 08:33:45.921   928  5796 D DhcpClient: Receive thread started
,11-18 08:33:45.925   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:45.925   928  2858 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-18 08:33:45.925   928  2871 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-18 08:33:45.991  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-18 08:33:45.991  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-18 08:33:45.991  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-18 08:33:45.991  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-18 08:33:45.991  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 08:33:45.992  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 08:33:45.992  5582  5791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-18 08:33:45.992  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-18 08:33:45.992  5582  5791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 08:33:45.992  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 08:33:45.992  5582  5791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 08:33:45.992  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-18 08:33:45.993  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 08:33:45.993  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 08:33:45.993  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-18 08:33:45.993  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 08:33:45.993  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:45.993  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:45.993  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:45.994  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:45.996  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:45.997  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 08:33:45.999  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:45.999  5582  5628 D BluetoothLeScanner: could not find callback wrapper
11-18 08:33:45.999  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 08:33:46.000  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.000  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.000  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.000  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 08:33:46.000  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.003  5685  5705 D BtGatt.AdvertiseManager: message : 1
11-18 08:33:46.004  5685  5705 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-18 08:33:46.007   928  2858 E native  : do suspend false
,11-18 08:33:46.018  5685  5702 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-18 08:33:46.018  5685  5702 D BtGatt.GattService: Client app is not null!
11-18 08:33:46.020   928  5795 D DhcpClient: Broadcasting DHCPDISCOVER
11-18 08:33:46.020  5685  5695 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 08:33:46.022  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-18 08:33:46.022  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.022  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:46.022  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.023  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.023  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.023  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 08:33:46.023  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 08:33:46.024  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 08:33:46.024  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.026  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.026  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:46.027  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.027  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:46.028  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-18 08:33:46.028  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 08:33:46.028  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 08:33:46.028  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-18 08:33:46.028  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:46.029  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:46.029  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:46.029  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.029  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 08:33:46.029  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-18 08:33:46.030  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.030  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.030  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-18 08:33:46.030  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 08:33:46.032  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.032  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.032  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.032  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.032  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-18 08:33:46.034  5582  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-18 08:33:46.034  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 08:33:46.035   928  5796 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172622, domain null
11-18 08:33:46.035  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 08:33:46.035  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-18 08:33:46.035  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-18 08:33:46.035  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:46.035   928  5795 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172622 seconds
11-18 08:33:46.035  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-18 08:33:46.037   928  5795 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-18 08:33:46.038  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-18 08:33:46.041  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-18 08:33:46.042  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 08:33:46.042  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-18 08:33:46.046  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:46.046  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 08:33:46.047  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:46.047  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 08:33:46.047  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-18 08:33:46.049  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-18 08:33:46.053  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-18 08:33:46.053  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:46.053  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 08:33:46.053  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 08:33:46.053  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 08:33:46.053   928  5796 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-18 08:33:46.054  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-18 08:33:46.054  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.054   928  5795 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-18 08:33:46.055  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:46.056   508   924 D CommandListener: Setting iface cfg
11-18 08:33:46.059  5685  5724 D BtGatt.GattService: registerClient() - UUID=b9ef9aec-bfc0-4c31-8499-ff446153e40c
,11-18 08:33:46.059  5685  5702 D BtGatt.GattService: onClientRegistered() - UUID=b9ef9aec-bfc0-4c31-8499-ff446153e40c, clientIf=5
11-18 08:33:46.060  5582  5593 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-18 08:33:46.060   928  2858 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-18 08:33:46.061   928  5795 D DhcpClient: Scheduling renewal in 86399s
11-18 08:33:46.061  5685  5716 D BtGatt.GattService: start scan with filters
,11-18 08:33:46.065  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 08:33:46.065  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.066  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 08:33:46.066  5685  5706 D BtGatt.ScanManager: handling starting scan
,11-18 08:33:46.066  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.067  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-18 08:33:46.067  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:46.067  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.067  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 08:33:46.067  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 08:33:46.067  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.067  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.067  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-18 08:33:46.067   928  2858 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-18 08:33:46.068  5685  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28bd9e0
11-18 08:33:46.068   928  2858 D WifiConfigStore: No blacklist allowed without epno enabled
11-18 08:33:46.068  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-18 08:33:46.068  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.068   928  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-18 08:33:46.070   928  2858 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-18 08:33:46.071  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.071  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-18 08:33:46.071  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:46.071  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:46.073  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-18 08:33:46.075   928  2871 D ConnectivityService: Adding iface wlan0 to network 101
11-18 08:33:46.075  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.076  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.076  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:46.076  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 08:33:46.076  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-18 08:33:46.077  5685  5702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-18 08:33:46.077  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:46.078  5685  5706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-18 08:33:46.084  5685  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 08:33:46.085  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:46.085  5685  5706 D BtGatt.ScanManager: Starting BLE batch scan
11-18 08:33:46.085  5685  5706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-18 08:33:46.095  5685  5702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-18 08:33:46.095  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 08:33:46.100  5685  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 08:33:46.100  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 08:33:46.103   928  2871 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-18 08:33:46.103   928  2871 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-18 08:33:46.105   928  2871 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-18 08:33:46.106   928  2871 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-18 08:33:46.108   928  2871 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-18 08:33:46.112   928  2871 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:46.116   928  2871 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-18 08:33:46.116   928  2871 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:46.116   928  2871 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-18 08:33:46.116   928  2858 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-18 08:33:46.116   928  2871 D ConnectivityService:    accepting network in place of null
11-18 08:33:46.116   928  2858 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-18 08:33:46.117   928  2871 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-18 08:33:46.135   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 08:33:46.156   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-18 08:33:46.159   928  2871 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-18 08:33:46.159  3664  3805 W QCNEJ   : |CORE| network available: 101
,11-18 08:33:46.159   928  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-18 08:33:46.160   928  2871 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:46.161  3664  3805 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-18 08:33:46.162   928   945 D Tethering: MasterInitialState.processMessage what=3
11-18 08:33:46.166  3664  3805 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-18 08:33:46.167  3664  3805 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-18 08:33:46.171  4995  5018 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-18 08:33:46.171  4995  5018 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-18 08:33:46.174  4859  4859 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-18 08:33:46.171  4995  5018 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-18 08:33:46.175  4995  5018 E SarControlService: no key has been found,reset the power
11-18 08:33:46.176  3608  3608 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-18 08:33:46.181  3608  3608 D SystemUpdateService: onCreate
,11-18 08:33:46.182  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-18 08:33:46.182  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-18 08:33:46.182  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-18 08:33:46.182  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 08:33:46.183  5020  5020 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-18 08:33:46.184  4995  5030 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-18 08:33:46.184  4995  5030 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-18 08:33:46.184  4995  5030 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-18 08:33:46.185  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-18 08:33:46.185  5020  5020 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-18 08:33:46.188  3608  3608 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-18 08:33:46.189  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7c493a1 HexData = [00000000ec03000000000000ffffffff]
,11-18 08:33:46.189  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 08:33:46.189  5020  5034 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-18 08:33:46.189  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 08:33:46.189  4995  5005 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-18 08:33:46.190  5020  5034 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@7c493a1 HexData = [00000000ed03000000000000ffffffff]
11-18 08:33:46.190  5020  5034 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-18 08:33:46.190  5020  5034 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-18 08:33:46.190  5020  5020 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-18 08:33:46.191  4995  5006 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-18 08:33:46.199   928  5794 D NetlinkSocketObserver: NeighborEvent{elapsedMs=220792, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-18 08:33:46.202  3608  3608 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-18 08:33:46.220  3608  5356 I iu.UploadsManager: num queued entries: 0
,11-18 08:33:46.220  3608  5356 I iu.UploadsManager: num updated entries: 0
11-18 08:33:46.220  3608  5356 I iu.SyncManager: NEXT; no task
11-18 08:33:46.221  3608  3608 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-18 08:33:46.223  3608  3608 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-18 08:33:46.224  5757  5757 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-18 08:33:46.229  5757  5757 D SprintDMHelper: simOperator: 
11-18 08:33:46.229  5757  5757 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-18 08:33:46.238  3608  5807 I SystemUpdateService: active receiver: enabled
,11-18 08:33:46.268   928  5793 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-18 08:33:46.276  3608  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-18 08:33:46.281  3608  5807 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-18 08:33:46.281  3608  5807 I SystemUpdateService: now status is 0 (complete)
11-18 08:33:46.281  3608  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-18 08:33:46.282  3608  5807 I SystemUpdateService: file has been verified
11-18 08:33:46.282  3608  5807 I SystemUpdateService: OTA package size = 21989297
,11-18 08:33:46.288  3608  5807 I SystemUpdateService: showing system update notification
,11-18 08:33:46.298  3608  3608 D SystemUpdateService: onDestroy
,11-18 08:33:46.577  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-18 08:33:46.577  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-18 08:33:46.577  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 08:33:46.603  5685  5685 D BtGatt.ScanManager: awakened up at time 221196
,11-18 08:33:46.605  5685  5706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 08:33:46.612  4969  5812 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-18 08:33:46.613   928  5793 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Nov 2016 13:33:46 GMT], X-Android-Received-Millis=[1479476026612], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479476026580]}
11-18 08:33:46.615   928  2871 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-18 08:33:46.615   928  2871 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-18 08:33:46.615   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-18 08:33:46.618   928  2871 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-18 08:33:46.631  5685  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-18 08:33:46.631  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:46.632  5685  5702 D BtGatt.GattService: current time is 221225350364
11-18 08:33:46.632  5685  5702 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -76, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 30, -89, -67, -65, 107, 79, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 30, -89, -67, -65, 107, 79, 1, -128, -61, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0]
11-18 08:33:46.634  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,11-18 08:33:46.636  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
11-18 08:33:46.637  5685  5702 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
11-18 08:33:46.638  5685  5702 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
,11-18 08:33:46.647  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 4. Current thread: Thread[main,5,main], id: 1
,11-18 08:33:46.647  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=221126093593}
,11-18 08:33:46.648  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=221126093593}
11-18 08:33:46.649  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
11-18 08:33:46.649  5582  5582 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-18 08:33:46.650  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 5]
11-18 08:33:46.650  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-18 08:33:46.650  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 5]
,11-18 08:33:46.650  5582  5582 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
11-18 08:33:46.650  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [<no peer name> A8:81:95:E9:5F:6F 5]
11-18 08:33:46.651  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> A8:81:95:E9:5F:6F 5], added - the peer count is 1
11-18 08:33:46.652  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=221026093593}
11-18 08:33:46.652  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=221026093593}
11-18 08:33:46.652  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=221226093593}
,11-18 08:33:46.653  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=221226093593}
11-18 08:33:46.653  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 6]
11-18 08:33:46.653  5582  5582 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-18 08:33:46.653  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:46.653  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:46.653  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:46.654  5582  5582 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: true
11-18 08:33:46.654  5582  5582 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerUpdated. Listeners size = 1
11-18 08:33:46.654  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:46.654  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 6] updated - the peer count is 1
11-18 08:33:46.655  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=220876093593}
11-18 08:33:46.655  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=220876093593}
,11-18 08:33:46.655  5582  5582 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 5], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
11-18 08:33:46.656  5582  5582 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 6], device name: '', device address: ''
,11-18 08:33:47.135  5685  5685 D BtGatt.ScanManager: awakened up at time 221728
,11-18 08:33:47.137  5685  5706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 08:33:47.160   928  2871 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-18 08:33:47.167  5685  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-18 08:33:47.167  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:47.167  5685  5702 D BtGatt.GattService: current time is 221760813941
11-18 08:33:47.167  5685  5702 D BtGatt.GattService: Batch record : [30, -89, -67, -65, 107, 79, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 30, -89, -67, -65, 107, 79, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0]
11-18 08:33:47.167  5685  5702 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
,11-18 08:33:47.168  5685  5702 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
11-18 08:33:47.180  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
11-18 08:33:47.180  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=221711032119}
11-18 08:33:47.181  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=221711032119}
11-18 08:33:47.181  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 6]
11-18 08:33:47.181  5582  5582 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-18 08:33:47.181  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:47.181  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:47.181  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:47.181  5582  5582 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
11-18 08:33:47.181  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 6] updated - the peer count is 1
11-18 08:33:47.182  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=221661032119}
11-18 08:33:47.182  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-61, mTimestampNanos=221661032119}
11-18 08:33:47.182  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 6]
11-18 08:33:47.182  5582  5582 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-18 08:33:47.182  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScan,Result onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:47.182  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:47.182  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:47.182  5582  5582 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
11-18 08:33:47.182  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 6] updated - the peer count is 1
,11-18 08:33:47.737   928  2858 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 14 -> obsolete
,11-18 08:33:48.945   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:49.074  5582  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-18 08:33:49.074  5582  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-18 08:33:49.074  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-18 08:33:49.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.075  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.076  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-18 08:33:49.076  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.076  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.076  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-18 08:33:49.077  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-18 08:33:49.077  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.077  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.077  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.080  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:49.081  5685  5695 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 08:33:49.081  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 08:33:49.082  5685  5706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 08:33:49.083  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:49.085  5685  5724 D BtGatt.GattService: stopScan() - queue size =1
,11-18 08:33:49.089  5685  5716 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-18 08:33:49.090  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 08:33:49.091  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.091  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:49.091  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.091  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-18 08:33:49.091  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.091  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.091  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-18 08:33:49.091  5685  5685 D BtGatt.ScanManager: awakened up at time 223683
,11-18 08:33:49.092  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-18 08:33:49.092  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-18 08:33:49.092  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-18 08:33:49.092  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.093  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:49.096  5685  5723 D BtGatt.GattService: registerClient() - UUID=786c36b0-f2f2-4038-bbc9-908b85267422
11-18 08:33:49.097  5685  5702 D BtGatt.GattService: onClientRegistered() - UUID=786c36b0-f2f2-4038-bbc9-908b85267422, clientIf=5
11-18 08:33:49.097  5582  5592 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-18 08:33:49.098  5685  5716 D BtGatt.GattService: start scan with filters
,11-18 08:33:49.101  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-18 08:33:49.101  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.101  5685  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-18 08:33:49.101  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-18 08:33:49.101  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:49.102  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.102  5685  5702 D BtGatt.GattService: current time is 223695436220
11-18 08:33:49.102  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.102  5685  5702 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 30, -89, -67, -65, 107, 79, 1, -128, -58, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 116, -43, -111, -91, -20, -29, 1, -128, -87, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,11-18 08:33:49.102  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:49.102  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:49.102  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.102  5582  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-18 08:33:49.102  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-18 08:33:49.102  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-18 08:33:49.102  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-18 08:33:49.102  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 08:33:49.102  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-18 08:33:49.102  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 08:33:49.102  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.102  5685  5702 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
11-18 08:33:49.102  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-18 08:33:49.103  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-18 08:33:49.103  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-18 08:33:49.103  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.103  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-18 08:33:49.104  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-18 08:33:49.104  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-18 08:33:49.104  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=222195678504}
11-18 08:33:49.104  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,11-18 08:33:49.104  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=4F:6B:BF:BD:A7:1E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=222195678504}
11-18 08:33:49.104  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 6]
11-18 08:33:49.104  5582  5582 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
11-18 08:33:49.104  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:49.104  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:49.104  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [<no peer name> A8:81:95:E9:5F:6F 6]
11-18 08:33:49.104  5582  5582 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
11-18 08:33:49.104  5582  5819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-18 08:33:49.105  5582  5582 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> A8:81:95:E9:5F:6F 6] updated - the peer count is 1
11-18 08:33:49.105  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-87, mTimestampNanos=221995678504}
,11-18 08:33:49.105  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-87, mTimestampNanos=221995678504}
11-18 08:33:49.105  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-18 08:33:49.105  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=221895678504}
11-18 08:33:49.105  5582  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-18 08:33:49.105  5582  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-18 08:33:49.105  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-80, mTimestampNanos=221895678504}
11-18 08:33:49.105  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-18 08:33:49.108  5582  5819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-18 08:33:49.104  5724  5724 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35183]" dev="sockfs" ino=35183 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:49.110  5685  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-18 08:33:49.110  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:49.104  5724  5724 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35183]" dev="sockfs" ino=35183 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-18 08:33:49.111  5685  5706 D BtGatt.ScanManager: stopping BLe Batch
11-18 08:33:49.112  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.112  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.112  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.112  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-18 08:33:49.112  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-18 08:33:49.112  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-18 08:33:49.112  5582  5628 V org.thaliproject.p2p.btconnectorlib.in,ternal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-18 08:33:49.113  5582  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:49.113  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:49.113  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.113  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-18 08:33:49.113  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-18 08:33:49.113  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.113  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.113  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.114  5582  5628 D BluetoothAdapter: STATE_ON
11-18 08:33:49.116  5685  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-18 08:33:49.116  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 08:33:49.116  5685  5706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-18 08:33:49.117  5685  5723 D BtGatt.GattService: registerClient() - UUID=9496be40-4fa7-4ef9-a29f-fe094b879aad
11-18 08:33:49.117  5685  5702 D BtGatt.GattService: onClientRegistered() - UUID=9496be40-4fa7-4ef9-a29f-fe094b879aad, clientIf=6
11-18 08:33:49.118  5582  5593 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-18 08:33:49.119  5685  5705 D BtGatt.AdvertiseManager: message : 0
,11-18 08:33:49.121  5685  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 08:33:49.121  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:49.122  5685  5705 D BtGatt.AdvertiseManager: starting multi advertising
11-18 08:33:49.123  5685  5706 D BtGatt.ScanManager: handling starting scan
,11-18 08:33:49.131  5685  5702 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-18 08:33:49.135  5685  5702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-18 08:33:49.136  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:49.136  5685  5706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-18 08:33:49.139  5685  5702 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-18 08:33:49.140  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:49.140  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.140  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.141  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.141  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-18 08:33:49.141  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-18 08:33:49.141  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-18 08:33:49.142  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-18 08:33:49.142  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.143  5685  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-18 08:33:49.144  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:49.144  5685  5706 D BtGatt.ScanManager: Starting BLE batch scan
11-18 08:33:49.144  5685  5706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-18 08:33:49.145  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.145  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.145  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:49.145  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-18 08:33:49.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:49.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-18 08:33:49.145  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.146  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.146  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-18 08:33:49.146  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.149  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.149  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-18 08:33:49.149  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.149  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.149  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:49.149  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-18 08:33:49.154  5685  5702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-18 08:33:49.154  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 08:33:49.159  5685  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-18 08:33:49.159  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 08:33:49.650  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-18 08:33:49.651  5582  5582 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 08:33:49.651  5582  5582 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-18 08:33:51.971   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:52.149  5582  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-18 08:33:52.150  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-18 08:33:52.150  5582  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-18 08:33:52.151  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-18 08:33:52.151  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-18 08:33:52.151  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-18 08:33:52.151  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-18 08:33:52.152  5582  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-18 08:33:52.152  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-18 08:33:52.152  5582  5582 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-18 08:33:52.152  5582  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e36b20 removed from the list
11-18 08:33:52.152  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-18 08:33:52.152  5582  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-18 08:33:52.152  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-18 08:33:52.152  5582  5819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-18 08:33:52.153  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-18 08:33:52.153  5582  5819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-18 08:33:52.153  5582  5819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-18 08:33:52.154  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.158  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.158  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.158  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-18 08:33:52.159  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:52.161  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:52.162  5685  5696 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-18 08:33:52.163  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-18 08:33:52.163  5685  5706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 08:33:52.167  5582  5628 D BluetoothAdapter: STATE_ON
,11-18 08:33:52.168  5685  5695 D BtGatt.GattService: stopScan() - queue size =1
11-18 08:33:52.169  5685  5724 D BtGatt.GattService: unregisterClient() - clientIf=5
11-18 08:33:52.169  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-18 08:33:52.169  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.169  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:52.169  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.170  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.170  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.170  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-18 08:33:52.170  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.170  5685  5685 D BtGatt.ScanManager: awakened up at time 226764
11-18 08:33:52.171  5685  5705 D BtGatt.AdvertiseManager: message : 1
11-18 08:33:52.173  5685  5705 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-18 08:33:52.181  5685  5702 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-18 08:33:52.182  5685  5702 D BtGatt.GattService: Client app is not null!
,11-18 08:33:52.182  5685  5716 D BtGatt.GattService: unregisterClient() - clientIf=6
11-18 08:33:52.183  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-18 08:33:52.183  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:52.183  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-18 08:33:52.183  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.184  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.184  5582  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:52.184  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-18 08:33:52.184  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-18 08:33:52.184  5582  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-18 08:33:52.185  5582  5628 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
11-18 08:33:52.185  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:52.187  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.187  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:52.187  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-18 08:33:52.187  5582  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-18 08:33:52.188  5582  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b388cd9 removed from the list
11-18 08:33:52.188  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:52.188  5582  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-18 08:33:52.188  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-18 08:33:52.188  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.188  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.188  5582  5582 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-18 08:33:52.189  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-18 08:33:52.191  5582  5582 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-18 08:33:52.191  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-18 08:33:52.191  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-18 08:33:52.191  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.192  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-18 08:33:52.192  5582  5582 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-18 08:33:52.192  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-18 08:33:52.192  5582  5582 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-18 08:33:52.192  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-18 08:33:52.192  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-18 08:33:52.192  5582  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-18 08:33:52.193  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-18 08:33:52.195  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-18 08:33:52.196  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-18 08:33:52.197  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-18 08:33:52.198  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-18 08:33:52.199  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-18 08:33:52.200  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-18 08:33:52.201  5582  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-18 08:33:52.206  5685  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-18 08:33:52.206  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:52.206  5685  5702 D BtGatt.GattService: current time is 226800052222
,11-18 08:33:52.207  5685  5702 D BtGatt.GattService: Batch record : [30, -89, -67, -65, 107, 79, 1, -128, -58, 54, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 71, -122, -77, 84, 69, -12, 1, -128, -78, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -87, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -73, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -76, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-18 08:33:52.207  5685  5702 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
11-18 08:33:52.207  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-18 08:33:52.207  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-18 08:33:52.208  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-18 08:33:52.208  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-18 08:33:52.208  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-18 08:33:52.208  5685  5702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-18 08:33:52.214  5685  5702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-18 08:33:52.214  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:52.214  5685  5706 D BtGatt.ScanManager: stopping BLe Batch
,11-18 08:33:52.219  5685  5702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-18 08:33:52.219  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-18 08:33:52.219  5685  5706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-18 08:33:52.224  5685  5702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-18 08:33:52.224  5685  5702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-18 08:33:52.693  5582  5582 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-18 08:33:54.118   928  2871 D ConnectivityService: handlePromptUnvalidated 101
,11-18 08:33:54.206  5582  5628 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-18 08:33:54.357  5582  5821 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 08:33:54.357  5582  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:33:54.727   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:55.200  5582  5821 W !!      : call onHalfStreamCopied
,11-18 08:33:55.200  5582  5821 I testCopyDataAndClose: closing input stream
,11-18 08:33:55.730   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 08:33:55.978  5582  5821 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-18 08:33:55.979  5582  5821 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 08:33:55.979  5582  5821 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-18 08:33:55.979  5582  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 08:33:56.732   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:57.226   928  2858 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-18 08:33:57.733   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:58.015   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:33:58.734   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:33:59.734   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-18 08:33:59.754  5582  5628 I StreamCopyingThreadTest: Starting test: testRun
,11-18 08:33:59.759  5582  5822 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:33:59.759  5582  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:34:01.052   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:34:04.083   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:34:04.736   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:34:04.765  5582  5823 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-18 08:34:04.768  5582  5628 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-18 08:34:04.880  5582  5824 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 08:34:04.880  5582  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:34:05.737   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-18 08:34:06.557  5582  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-18 08:34:06.738   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:34:07.739   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:34:08.740   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,11-18 08:34:09.484   928  5794 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-18 08:34:09.741   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-18 08:34:10.308  5582  5628 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-18 08:34:10.311  5582  5825 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:34:10.311  5582  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-18 08:34:10.312  5582  5825 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-18 08:34:10.313  5582  5825 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-18 08:34:10.313  5582  5825 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-18 08:34:10.313  5582  5825 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:34:10.313  5582  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-18 08:34:10.315  5582  5628 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-18 08:34:10.315  5582  5628 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-18 08:34:10.316  5582  5628 I StreamCopyingThreadTest: Starting test: testRunWithException
11-18 08:34:10.318  5582  5826 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:34:10.318  5582  5826 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-18 08:34:10.318  5582  5826 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
11-18 08:34:10.319  5582  5826 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:34:10.319  5582  5826 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 08:34:10.319  5582  5826 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-18 08:34:10.319  5582  5826 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
11-18 08:34:10.319  5582  5826 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-18 08:34:10.320  5582  5628 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-18 08:34:10.320  5582  5628 E com.test.thalitest.ThaliTestRunner: 
11-18 08:34:10.320  5582  5628 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 08:34:10.320  5582  5628 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-18 08:34:10.321  5582,  5628 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 08:34:10.321  5582  5628 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-18 08:34:10.322  5582  5628 E com.test.,thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.Tha,liTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:10.322  5582  5628 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-18 08:34:10.324  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG UnitTest_app: 'Running unit tests'
11-18 08:34:10.324  5582  5628 I jxcore-log: 
11-18 08:34:10.324  5582  5628 I jxcore-log: *Native tests were executed*
11-18 08:34:10.324  5582  5628 I jxcore-log: 
11-18 08:34:10.324  5582  5628 I jxcore-log: Total number of executed tests:  82
11-18 08:34:10.324  5582  5628 I jxcore-log: 
11-18 08:34:10.324  5582  5628 I jxcore-log: Number of passed tests:  79
11-18 08:34:10.324  5582  5628 I jxcore-log: 
11-18 08:34:10.324  5582  5628 I jxcore-log: Number of failed tests:  3
11-18 08:34:10.324  5582  5628 I jxcore-log: 
11-18 08:34:10.325  5582  5628 I jxcore-log: Number of ignored tests:  0
11-18 08:34:10.325  5582  5628 I jxcore-log: 
11-18 08:34:10.325  5582  5628 I jxcore-log: Total duration:  38507
11-18 08:34:10.325  5582  5628 I jxcore-log: 
11-18 08:34:10.325  5582  5628 I jxcore-log: Failed to execute UT.
11-18 08:34:10.325  5582  5628 I jxcore-log: 
,11-18 08:34:10.325  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-18 08:34:10.325  5582  5628 I jxcore-log: 
11-18 08:34:10.326  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-18 08:34:10.326  5582  5628 I jxcore-log: 
11-18 08:34:10.329  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 08:34:10.329  5582  5628 I jxcore-log: 
11-18 08:34:10.329  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.329  5582  5628 I jxcore-log: 
11-18 08:34:10.331  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 08:34:10.331  5582  5628 I jxcore-log: 
11-18 08:34:10.331  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.331  5582  5628 I jxcore-log: 
,11-18 08:34:10.332  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 08:34:10.332  5582  5628 I jxcore-log: 
11-18 08:34:10.332  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 08:34:10.332  5582  5628 I jxcore-log: 
11-18 08:34:10.332  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.332  5582  5628 I jxcore-log: 
11-18 08:34:10.333  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 08:34:10.333  5582  5628 I jxcore-log: 
,11-18 08:34:10.333  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 08:34:10.333  5582  5628 I jxcore-log: 
11-18 08:34:10.333  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.333  5582  5628 I jxcore-log: 
11-18 08:34:10.334  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 08:34:10.334  5582  5628 I jxcore-log: 
11-18 08:34:10.334  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 08:34:10.334  5582  5628 I jxcore-log: 
11-18 08:34:10.334  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.334  5582  5628 I jxcore-log: 
,11-18 08:34:10.334  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 08:34:10.334  5582  5628 I jxcore-log: 
11-18 08:34:10.334  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.334  5582  5628 I jxcore-log: 
11-18 08:34:10.335  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 08:34:10.335  5582  5628 I jxcore-log: 
11-18 08:34:10.335  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.335  5582  5628 I jxcore-log: 
11-18 08:34:10.335  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 08:34:10.335  5582  5628 I jxcore-log: 
11-18 08:34:10.335  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.335  5582  5628 I jxcore-log: 
11-18 08:34:10.335  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 08:34:10.335  5582  5628 I jxcore-log: 
11-18 08:34:10.336  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.336  5582  5628 I jxcore-log: 
11-18 08:34:10.336  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-18 08:34:10.336  5582  5628 I jxcore-log: 
11-18 08:34:10.336  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.336  5582  5628 I jxcore-log: 
11-18 08:34:10.336  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-18 08:34:10.336  5582  5628 I jxcore-log: 
11-18 08:34:10.337  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.337  5582  5628 I jxcore-log: 
,11-18 08:34:10.337  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-18 08:34:10.337  5582  5628 I jxcore-log: 
11-18 08:34:10.337  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-18 08:34:10.337  5582  5628 I jxcore-log: 
11-18 08:34:10.338  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-18 08:34:10.338  5582  5628 I jxcore-log: 
11-18 08:34:10.339  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 08:34:10.339  5582  5628 I jxcore-log: 
11-18 08:34:10.339  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.339  5582  5628 I jxcore-log: 
11-18 08:34:10.339  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-18 08:34:10.339  5582  5628 I jxcore-log: 
,11-18 08:34:10.339  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 08:34:10.339  5582  5628 I jxcore-log: 
11-18 08:34:10.339  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.339  5582  5628 I jxcore-log: 
11-18 08:34:10.340  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}]'
11-18 08:34:10.340  5582  5628 I jxcore-log: 
11-18 08:34:10.340  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-5","peerAvailable":true,"pleaseConnect":false}'
11-18 08:34:10.340  5582  5628 I jxcore-log: 
11-18 08:34:10.340  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-18 08:34:10.340  5582  5628 I jxcore-log: 
11-18 08:34:10.341  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerIdentifier":"A8:81:95:E9:5F:6F-6","peerAvailable":true,"pleaseConnect":false}]'
11-18 08:34:10.341  5582  5628 I jxcore-log: 
,11-18 08:34:10.341  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8:81:95:E9:5F:6F-6","peerAvailable":true,"pleaseConnect":false}'
11-18 08:34:10.341  5582  5628 I jxcore-log: 
11-18 08:34:10.341  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
11-18 08:34:10.341  5582  5628 I jxcore-log: 
11-18 08:34:10.341  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-18 08:34:10.341  5582  5628 I jxcore-log: 
11-18 08:34:10.341  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-18 08:34:10.341  5582  5628 I jxcore-log: 
11-18 08:34:10.342  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.342  5582  5628 I jxcore-log: 
11-18 08:34:10.342  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-18 08:34:10.342  5582  5628 I jxcore-log: 
,11-18 08:34:10.342  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-18 08:34:10.342  5582  5628 I jxcore-log: 
11-18 08:34:10.347  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-18 08:34:10.347  5582  5628 I jxcore-log: 
11-18 08:34:10.347  5582  5628 I jxcore-log: 2016-11-18 13:34:10 - WARN testUtils: 'myNameCallback not set!'
11-18 08:34:10.347  5582  5628 I jxcore-log: 
11-18 08:34:10.353  5582  5582 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-18 08:34:12.397  5582  5628 I jxcore-log: 2016-11-18 13:34:12 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-18 08:34:12.397  5582  5628 I jxcore-log: 
,11-18 08:34:12.399  5582  5628 I jxcore-log: 2016-11-18 13:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-18 08:34:12.399  5582  5628 I jxcore-log: 
,11-18 08:34:12.739  5582  5628 I jxcore-log: 2016-11-18 13:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-18 08:34:12.739  5582  5628 I jxcore-log: 
,11-18 08:34:12.751  5582  5628 I jxcore-log: 2016-11-18 13:34:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-18 08:34:12.751  5582  5628 I jxcore-log: 
,11-18 08:34:13.145   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:34:13.845  5582  5628 I jxcore-log: 2016-11-18 13:34:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-18 08:34:13.845  5582  5628 I jxcore-log: 
,11-18 08:34:14.011  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-18 08:34:14.011  5582  5628 I jxcore-log: 
,11-18 08:34:14.016  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-18 08:34:14.016  5582  5628 I jxcore-log: 
,11-18 08:34:14.028  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-18 08:34:14.028  5582  5628 I jxcore-log: 
,11-18 08:34:14.508  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-18 08:34:14.508  5582  5628 I jxcore-log: 
,11-18 08:34:14.553  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-18 08:34:14.553  5582  5628 I jxcore-log: 
,11-18 08:34:14.566  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-18 08:34:14.566  5582  5628 I jxcore-log: 
,11-18 08:34:14.571  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-18 08:34:14.571  5582  5628 I jxcore-log: 
,11-18 08:34:14.853  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-18 08:34:14.853  5582  5628 I jxcore-log: 
,11-18 08:34:14.981  5582  5628 I jxcore-log: 2016-11-18 13:34:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-18 08:34:14.981  5582  5628 I jxcore-log: 
,11-18 08:34:15.362  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-18 08:34:15.362  5582  5628 I jxcore-log: 
,11-18 08:34:15.368  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-18 08:34:15.368  5582  5628 I jxcore-log: 
,11-18 08:34:15.373  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-18 08:34:15.373  5582  5628 I jxcore-log: 
,11-18 08:34:15.376  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-18 08:34:15.376  5582  5628 I jxcore-log: 
,11-18 08:34:15.382  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-18 08:34:15.382  5582  5628 I jxcore-log: 
,11-18 08:34:15.420  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-18 08:34:15.420  5582  5628 I jxcore-log: 
,11-18 08:34:15.426  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-18 08:34:15.426  5582  5628 I jxcore-log: 
,11-18 08:34:15.454  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-18 08:34:15.454  5582  5628 I jxcore-log: 
,11-18 08:34:15.491  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-18 08:34:15.491  5582  5628 I jxcore-log: 
,11-18 08:34:15.499  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-18 08:34:15.499  5582  5628 I jxcore-log: 
,11-18 08:34:15.505  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-18 08:34:15.505  5582  5628 I jxcore-log: 
,11-18 08:34:15.521  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-18 08:34:15.521  5582  5628 I jxcore-log: 
,11-18 08:34:15.536  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-18 08:34:15.536  5582  5628 I jxcore-log: 
,11-18 08:34:15.542  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-18 08:34:15.542  5582  5628 I jxcore-log: 
,11-18 08:34:15.547  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-18 08:34:15.547  5582  5628 I jxcore-log: 
,11-18 08:34:15.560  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-18 08:34:15.560  5582  5628 I jxcore-log: 
,11-18 08:34:15.577  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-18 08:34:15.577  5582  5628 I jxcore-log: 
,11-18 08:34:15.592  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-18 08:34:15.592  5582  5628 I jxcore-log: 
,11-18 08:34:15.602  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-18 08:34:15.602  5582  5628 I jxcore-log: 
,11-18 08:34:15.615  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-18 08:34:15.615  5582  5628 I jxcore-log: 
,11-18 08:34:15.625  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-18 08:34:15.625  5582  5628 I jxcore-log: 
,11-18 08:34:15.638  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-18 08:34:15.638  5582  5628 I jxcore-log: 
,11-18 08:34:15.648  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-18 08:34:15.648  5582  5628 I jxcore-log: 
,11-18 08:34:15.655  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-18 08:34:15.655  5582  5628 I jxcore-log: 
,11-18 08:34:15.676  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-18 08:34:15.676  5582  5628 I jxcore-log: 
,11-18 08:34:15.682  5582  5628 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-18 08:34:15.683  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - INFO testUtils: 'BLE multiple advertisement supported'
11-18 08:34:15.683  5582  5628 I jxcore-log: 
,11-18 08:34:15.812  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - DEBUG CoordinatedClient: 'connected to the test server'
11-18 08:34:15.812  5582  5628 I jxcore-log: 
,11-18 08:34:15.949  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-18 08:34:15.949  5582  5628 I jxcore-log: 
,11-18 08:34:15.951  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - DEBUG CoordinatedClient: 'test client failed'
11-18 08:34:15.951  5582  5628 I jxcore-log: 
,11-18 08:34:15.956  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-18 08:34:15.956  5582  5628 I jxcore-log: 
,11-18 08:34:15.961  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-18 08:34:15.961  5582  5628 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-18 08:34:15.961  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-18 08:34:15.961  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-18 08:34:15.961  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-18 08:34:15.961  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-18 08:34:15.961  5582  5628 I jxcore-log: 
11-18 08:34:15.961  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-18 08:34:15.961  5582  5628 I jxcore-log: 
,11-18 08:34:15.966  5582  5628 I jxcore-log: 2016-11-18 13:34:15 - ERROR runTests: 'Test client failed: Native unit tests failed
11-18 08:34:15.966  5582  5628 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:187:20
11-18 08:34:15.966  5582  5628 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-18 08:34:15.966  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-18 08:34:15.966  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-18 08:34:15.966  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-18 08:34:15.966  5582  5628 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
11-18 08:34:15.966  5582  5628 I jxcore-log: 
,11-18 08:34:16.156   928  2871 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-18 08:34:16.580  5835  5835 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-18 08:34:16.603  5835  5835 D AndroidRuntime: CheckJNI is OFF
,11-18 08:34:16.631  5835  5835 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-18 08:34:16.661  5835  5835 I Radio-JNI: register_android_hardware_Radio DONE
,11-18 08:34:16.676  5835  5835 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-18 08:34:16.683   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-18 08:34:16.684   928   941 I ActivityManager: Killing 5582:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-18 08:34:16.751   928  3053 D GraphicsStats: Buffer count: 2
,11-18 08:34:16.752   928  3780 I WindowState: WIN DEATH: Window{b6e2e3a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-18 08:34:16.753   928  2868 D WifiService: Client connection lost with reason: 4
,11-18 08:34:16.817   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-18 08:34:16.818   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-18 08:34:16.819   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-18 08:34:16.819   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-18 08:34:16.819   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:34:16.819   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:16.819   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 08:34:16.819   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-18 08:34:16.819   928   951 I art     : Starting a blocking GC Explicit
11-18 08:34:16.820   928   941 I ActivityManager:   Force finishing activity ActivityRecord{16b0eef u0 com.test.thalitest/.MainActivity t8}
,11-18 08:34:16.826   928  3062 W ActivityManager: Spurious death for ProcessRecord{f8cfa2b 0:com.test.thalitest/u0a77}, curProc for 5582: null
,11-18 08:34:16.830   928   946 W WindowManager: Attempted to add application window with unknown token Token{4fc5dfc ActivityRecord{16b0eef u0 com.test.thalitest/.MainActivity t8 f}}.  Aborting.
,11-18 08:34:16.830   928   946 W WindowManager: Token{4fc5dfc ActivityRecord{16b0eef u0 com.test.thalitest/.MainActivity t8 f}} already running, starting window not displayed. Unable to add window -- token Token{4fc5dfc ActivityRecord{16b0eef u0 com.test.thalitest/.MainActivity t8 f}} is not valid; is your activity running?
11-18 08:34:16.830   928   946 W WindowManager: view not successfully added to wm, removing view
11-18 08:34:16.831   928   946 W WindowManager: Exception when adding starting window
11-18 08:34:16.831   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{57136d2 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-18 08:34:16.831   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-18 08:34:16.831   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-18 08:34:16.831   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-18 08:34:16.831   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-18 08:34:16.831   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-18 08:34:16.831   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:34:16.831   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:16.831   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 08:34:16.831   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-18 08:34:16.909   928   951 I art     : Explicit concurrent mark sweep GC freed 67279(4MB) AllocSpace objects, 14(396KB) LOS objects, 33% free, 29MB/43MB, paused 1.676ms total 88.975ms
,11-18 08:34:16.928   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-18 08:34:16.931  5835  5835 I art     : System.exit called, status: 0
,11-18 08:34:16.931  5835  5835 I AndroidRuntime: VM exiting with result code 0.
,11-18 08:34:16.936   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-18 08:34:16.952   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-18 08:34:16.955  3566  3566 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-18 08:34:16.957  5685  5685 D BluetoothMapAppObserver: onReceive
,11-18 08:34:16.957  5685  5685 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-18 08:34:16.958  3974  4093 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-18 08:34:16.959   928  2845 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-18 08:34:16.986  3566  5846 I Keyboard.Facilitator.DecoderInitializer: run()
,11-18 08:34:16.997  3299  5847 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-18 08:34:17.000  3702  3702 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-18 08:34:17.012  3478  3478 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-18 08:34:17.012  3478  3478 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-18 08:34:17.014  3566  5846 I Decoder : createOrResetDecoder
,11-18 08:34:17.016   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-18 08:34:17.027  3608  5852 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-18 08:34:17.027    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 08:34:17.030    17    17 W kworker/2:0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 08:34:17.038  3608  5852 D AccountUtils: Clearing selected account for com.test.thalitest
,11-18 08:34:17.037    17    17 W kworker/2:0: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-18 08:34:17.049  3739  3860 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-18 08:34:17.054   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-18 08:34:17.055   928   940 E PackageManager: Failed to write settings, restoring backup
11-18 08:34:17.055   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-18 08:34:17.055   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-18 08:34:17.055   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-18 08:34:17.055   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-18 08:34:17.055   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-18 08:34:17.055   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:34:17.055   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:17.055   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 08:34:17.057   928   941 E DropBoxManagerService: Can't write: system_server_wtf
11-18 08:34:17.057   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-18 08:34:17.057   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 08:34:17.057   928   941 E DropBoxManagerService: 	... 13 more
,11-18 08:34:17.063   928  3780 I ActivityManager: Start proc 5854:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-18 08:34:17.063  3739  3860 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-18 08:34:17.063  3739  3860 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3739
11-18 08:34:17.063  3739  3860 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:17.063  3739  3860 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-18 08:34:17.067   928  3053 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-18 08:34:17.068   928  5861 E DropBoxManagerService: Can't write: system_app_crash
11-18 08:34:17.068   928  5861 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 08:34:17.068   928  5861 E DropBoxManagerService: 	... 5 more
,11-18 08:34:17.071  3739  3860 I Process : Sending signal. PID: 3739 SIG: 9
,11-18 08:34:17.089  3478  3478 I ConfigService: onCreate
,11-18 08:34:17.093  3478  5868 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 08:34:17.093  3478  5868 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-18 08:34:17.093  3299  3325 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj9E8AE290E) - 
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-18 08:34:17.093  3478  5868 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-18 08:34:17.095  3478  5868 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-18 08:34:17.109  3608  5852 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-18 08:34:17.122  3566  5846 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-18 08:34:17.143  3608  5852 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:17.143  3608  5852 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:17.160  3608  5852 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 08:34:17.169  3608  5852 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-18 08:34:17.178  3299  3325 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-18 08:34:17.178  3299  3325 E AndroidRuntime: Process: android.process.acore, PID: 3299
11-18 08:34:17.178  3299  3325 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-18 08:34:17.178  3299  3325 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-18 08:34:17.180   928  5872 E DropBoxManagerService: Can't write: system_app_crash
11-18 08:34:17.180   928  5872 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-18 08:34:17.180   928  5872 E DropBoxManagerService: 	... 5 more
,11-18 08:34:17.201   928  4143 D GraphicsStats: Buffer count: 1
11-18 08:34:17.201   928   938 I WindowState: WIN DEATH: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
,11-18 08:34:17.203  3299  3325 I Process : Sending signal. PID: 3299 SIG: 9
,11-18 08:34:17.206   928  3062 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3739) has died
,11-18 08:34:17.207   928  3062 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-18 08:34:17.211   928   946 E WindowState: getStack: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{e203991 token=Token{bcf77b8 ActivityRecord{c2fca1b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t7}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,11-18 08:34:17.212   928   946 E WindowState: getStack: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{e203991 token=Token{bcf77b8 ActivityRecord{c2fca1b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t7}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
11-18 08:34:17.212   928   946 E WindowState: getStack: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{e203991 token=Token{bcf77b8 ActivityRecord{c2fca1b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t7}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
11-18 08:34:17.212   928   946 E WindowState: getStack: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{e203991 token=Token{bcf77b8 ActivityRecord{c2fca1b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t7}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-18 08:34:17.212   928   946 E WindowState: getStack: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{e203991 token=Token{bcf77b8 ActivityRecord{c2fca1b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t7}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
11-18 08:34:17.213   928   946 E WindowState: getStack: Window{d561f30 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{e203991 token=Token{bcf77b8 ActivityRecord{c2fca1b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t7}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,11-18 08:34:17.258  3608  5874 I GMPM-SVC: App measurement is starting up
,11-18 08:34:17.270  3608  5874 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-18 08:34:17.271  3608  5874 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-18 08:34:17.425   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
