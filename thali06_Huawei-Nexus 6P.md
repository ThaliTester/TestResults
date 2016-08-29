#### Test 829140738625595_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 05:07:41.926   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:07:42.405  5652  5652 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 05:07:42.411  5652  5652 D AndroidRuntime: CheckJNI is OFF
08-29 05:07:42.436  5652  5652 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 05:07:42.473  5652  5652 I Radio-JNI: register_android_hardware_Radio DONE
08-29 05:07:42.491  5652  5652 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 05:07:42.499   929  3480 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 05:07:42.547   929  3480 I ActivityManager: Start proc 5662:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 05:07:42.551  5652  5652 D AndroidRuntime: Shutting down VM
08-29 05:07:42.654  5662  5662 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 05:07:42.684  5662  5662 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 05:07:42.708  5662  5662 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 5248-5266)
08-29 05:07:42.709  5662  5662 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 05:07:42.727  5662  5662 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {55ab924}
08-29 05:07:42.727  5662  5662 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 05:07:42.728  5662  5662 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 05:07:42.732  5662  5662 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 05:07:42.733  5662  5662 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 05:07:42.767  5662  5662 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 05:07:42.780  5662  5662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 05:07:42.781  5662  5662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 05:07:42.781  5662  5662 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 05:07:42.781  5662  5662 I Adreno  : Build Date                       : 10/21/15
08-29 05:07:42.781  5662  5662 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 05:07:42.781  5662  5662 I Adreno  : Local Branch                     : 
08-29 05:07:42.781  5662  5662 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 05:07:42.781  5662  5662 I Adreno  : Remote Branch                    : NONE
08-29 05:07:42.781  5662  5662 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 05:07:42.825   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@83bac40:true
,08-29 05:07:42.862  5662  5662 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 05:07:42.870  5662  5662 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 05:07:42.895  5662  5699 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 05:07:42.902  5662  5686 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 05:07:42.926   599   599 I ServiceManager: Waiting for service AtCmdFwd...
08-29 05:07:42.926  5662  5699 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 05:07:43.011   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +412ms (total +491ms)
,08-29 05:07:43.038  5662  5662 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5662
,08-29 05:07:43.125  5662  5662 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 05:07:43.362  5662  5702 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -584316624
,08-29 05:07:43.390  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 05:07:43.390  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 05:07:43.390  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 05:07:43.390  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 05:07:43.390  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 05:07:43.390  5662  5702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c29a5a added. We now have 1 listener(s)
,08-29 05:07:43.399  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 05:07:43.401  5662  5702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 05:07:43.403  5662  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 05:07:43.403  5662  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 05:07:43.412  5662  5702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce76181 added. We now have 1 listener(s)
,08-29 05:07:43.413  5662  5702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:07:43.419   929  3050 D WifiService: New client listening to asynchronous messages
,08-29 05:07:43.421  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 05:07:43.421  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 05:07:43.421  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 05:07:43.421  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 05:07:43.421  5662  5702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 05:07:43.427  5662  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 05:07:43.427  5662  5702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 05:07:43.438  5662  5702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 05:07:43.439  5662  5702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 05:07:43.439  5662  5702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 05:07:43.439  5662  5702 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 05:07:43.441  5662  5702 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 05:07:43.444  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:43.448  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:43.470  5662  5662 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 05:07:43.927   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:07:43.957  5662  5671 I art     : Background sticky concurrent mark sweep GC freed 78248(8MB) AllocSpace objects, 18(1604KB) LOS objects, 25% free, 24MB/32MB, paused 1.796ms total 236.335ms
,08-29 05:07:44.059  5662  5708 W jxcore-log: Initializing JXcore engine
,08-29 05:07:44.060  5662  5708 W jxcore-log: JXcore engine is ready
,08-29 05:07:44.095  5708  5708 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1316 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 05:07:44.095  5708  5708 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[6270]" dev="sockfs" ino=6270 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 05:07:44.095  5708  5708 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 05:07:44.095  5708  5708 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[32873]" dev="sockfs" ino=32873 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 05:07:44.120  5662  5708 W jxcore-log: Starting JXcore engine
,08-29 05:07:44.179  5662  5708 W jxcore-log: Platform android
08-29 05:07:44.179  5662  5708 W jxcore-log: 
,08-29 05:07:44.179  5662  5708 W jxcore-log: Process ARCH arm
08-29 05:07:44.179  5662  5708 W jxcore-log: 
,08-29 05:07:44.275  5662  5708 I jxcore-log: JXcore Cordova bridge is ready!
08-29 05:07:44.275  5662  5708 I jxcore-log: 
,08-29 05:07:44.275  5662  5708 W jxcore-log: JXcore engine is started
,08-29 05:07:44.288  5662  5702 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 05:07:44.296  5662  5662 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 05:07:44.928   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:07:45.929   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:07:46.929   599   599 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 05:07:47.983   929  5334 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170540, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 05:07:50.877  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 05:07:50.877  5662  5708 I jxcore-log: 
,08-29 05:07:50.879  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 05:07:50.879  5662  5708 I jxcore-log: 
,08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 05:07:50.883  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 05:07:50.884  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 05:07:50.886  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 05:07:50.886  5662  5708 I jxcore-log: 
,08-29 05:07:50.887  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 05:07:50.887  5662  5708 I jxcore-log: 
,08-29 05:07:50.983   929  5334 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173540, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,08-29 05:07:50.983   929  5334 W NetlinkSocketObserver: ALERT: NeighborEvent{elapsedMs=173540, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
08-29 05:07:50.984   929  5334 W IpReachabilityMonitor: FAILURE: LOST_PROVISIONING, NeighborEvent{elapsedMs=173540, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,08-29 05:07:50.986   929  3049 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 05:07:50.998  3732  3732 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 05:07:51.035   929  3049 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 05:07:51.036   929  3049 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{5}, ntable=[]
08-29 05:07:51.036   929  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 05:07:51.036   929  3049 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 05:07:51.037  3732  3732 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,08-29 05:07:51.054   929  3049 E native  : do suspend true
,08-29 05:07:51.062   929  5335 D DhcpClient: Clearing IP address
,08-29 05:07:51.063   508   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 05:07:51.066   508   922 D CommandListener: Setting iface cfg
,08-29 05:07:51.068  3692  5392 V NativeCrypto: Read error: ssl=0x7f69676380: I/O error during system call, Connection timed out
,08-29 05:07:51.071  3692  5392 V NativeCrypto: SSL shutdown failed: ssl=0x7f69676380: I/O error during system call, Broken pipe
,08-29 05:07:51.075   929   939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 05:07:51.076   929  5333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 05:07:51.079   929  5333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 05:07:51.081   929  3051 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 05:07:51.081   929  3051 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 05:07:51.083   929  3051 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 05:07:51.091   929  5336 D DhcpClient: Receive thread stopped
,08-29 05:07:51.095   929  3051 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 05:07:51.095   929  3051 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 05:07:51.101   597   597 E Parcel  : Reading a NULL string not supported here.
,08-29 05:07:51.103   929  3051 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-29 05:07:51.103   929  3049 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 05:07:51.104   929  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 05:07:51.104   929  3049 E native  : do suspend true
08-29 05:07:51.109  3582  3757 W QCNEJ   : |CORE| network lost: 100
08-29 05:07:51.110  3582  3757 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 05:07:51.136   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 05:07:51.158   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 05:07:51.159   508   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 05:07:51.160   929  3051 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 05:07:51.160   929  3051 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 05:07:51.161   508   922 D TetherController: Setting IP forward enable = 0
,08-29 05:07:51.164   929   946 D Tethering: MasterInitialState.processMessage what=3
,08-29 05:07:51.165  5219  5219 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@860b249 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 05:07:51.169  4940  4971 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-29 05:07:51.169  4940  4971 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 05:07:51.169  4940  4971 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 05:07:51.169  4940  4971 E SarControlService: no key has been found,reset the power
08-29 05:07:51.169  4940  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 05:07:51.169  4940  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 05:07:51.170  4940  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.170  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:07:51.170  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 05:07:51.170  4979  4979 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 05:07:51.175  3938  3938 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 05:07:51.176  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.176  4940  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 05:07:51.176  4940  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 05:07:51.176  4940  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 05:07:51.179   929  3049 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 05:07:51.179  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 05:07:51.180  4979  4979 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-29 05:07:51.183  3938  3938 D SystemUpdateService: onCreate
,08-29 05:07:51.185  4979  4996 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43abdb7 HexData = [00000000ea03000000000000ffffffff]
08-29 05:07:51.185  4979  4996 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 05:07:51.185  4979  4996 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 05:07:51.186  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 05:07:51.186  4940  4951 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 05:07:51.186  4979  4996 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@43abdb7 HexData = [00000000eb03000000000000ffffffff]
08-29 05:07:51.186  4979  4996 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 05:07:51.186  4979  4996 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 05:07:51.187  4979  4979 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 05:07:51.187  4940  4953 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 05:07:51.190  3938  3938 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 05:07:51.196  3938  5722 I SystemUpdateService: active receiver: enabled
,08-29 05:07:51.199  3938  3938 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 05:07:51.205  3938  5362 I iu.UploadsManager: num queued entries: 0
,08-29 05:07:51.206  3938  5362 I iu.UploadsManager: num updated entries: 0
08-29 05:07:51.206  3938  5362 I iu.SyncManager: NEXT; no task
,08-29 05:07:51.208  3938  3938 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 05:07:51.209  3938  3938 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 05:07:51.212  5364  5364 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 05:07:51.213  5662  5708 D executeNativeTests: Running unit tests
,08-29 05:07:51.215  5364  5364 D SprintDMHelper: simOperator: 
,08-29 05:07:51.215  5364  5364 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 05:07:51.225  3938  5722 I SystemUpdateService: showing system update notification
,08-29 05:07:51.227   508   922 E Netd    : netlink response contains error (No such file or directory)
08-29 05:07:51.227  4317  5729 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-29 05:07:51.227   508   922 D TetherController: Setting IP forward enable = 0
08-29 05:07:51.228   929  3051 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 05:07:51.228   929  3051 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 05:07:51.241  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 05:07:51.241  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa added. We now have 2 listener(s)
08-29 05:07:51.242  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:07:51.242  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:07:51.242  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:07:51.242  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:07:51.242  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b added. We now have 2 listener(s)
08-29 05:07:51.242  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:07:51.242  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 05:07:51.244  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.245  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:07:51.246  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:07:51.246  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:07:51.247  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.247  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 05:07:51.247  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 05:07:51.247  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 05:07:51.247  5662  5708 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 05:07:51.248  5662  5708 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 05:07:51.248  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 05:07:51.248  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 05:07:51.248  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 05:07:51.248  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.248  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.248  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 05:07:51.248  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.248  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.248  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.248  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.248  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:07:51.248  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa removed from the list
08-29 05:07:51.248  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.248  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b removed from the list
08-29 05:07:51.248  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.249  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.249  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.249  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.249  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.249  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.249  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.249  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.250  5662  5708 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 05:07:51.250  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.250  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 05:07:51.250  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.250  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.250  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.250  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.251  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.251  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.251  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.251  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.251  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.251  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.251  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.251  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.251  3938  5722 V SystemUpdateService: retry (wakeup: false) in 3599950 ms
08-29 05:07:51.251  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.251  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.251  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.251  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.253  3938  3938 D SystemUpdateService: onDestroy
08-29 05:07:51.253  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 05:07:51.253  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 05:07:51.253  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 05:07:51.253  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 05:07:51.253  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 05:07:51.254  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 05:07:51.254  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.254  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.254  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.254  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.254  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.254  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.254  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.254  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.254  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.255  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.255  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.255  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.255  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.255  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.255  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.255  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.255  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.255  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.255  5662  5708 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 05:07:51.256  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.257  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.258  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.258  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:07:51.258  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:07:51.258  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 05:07:51.258  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 05:07:51.258  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.258  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 05:07:51.260  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.261  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.263  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 05:07:51.263  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 05:07:51.267  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 05:07:51.268  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 05:07:51.269  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 05:07:51.270  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 05:07:51.273  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 05:07:51.273  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 05:07:51.273  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 05:07:51.274  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 05:07:51.274  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:07:51.278  4464  4710 D BtGatt.GattService: registerClient() - UUID=4e2ac12e-8621-42b0-8fe7-fc2c0e527a59
08-29 05:07:51.279  4464  4538 D BtGatt.GattService: onClientRegistered() - UUID=4e2ac12e-8621-42b0-8fe7-fc2c0e527a59, clientIf=5
,08-29 05:07:51.280  5662  5672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 05:07:51.281  4464  4712 D BtGatt.GattService: start scan with filters
08-29 05:07:51.284  4464  4545 D BtGatt.ScanManager: handling starting scan
08-29 05:07:51.284  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 05:07:51.284  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 05:07:51.284  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 05:07:51.284  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 05:07:51.285  4464  4545 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:07:51.285  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:07:51.285  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 05:07:51.286  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:07:51.286  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 05:07:51.287  5662  5708 I io.jxcore.node.ConnectionHelper: start: OK
08-29 05:07:51.288  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.288  5662  5708 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 05:07:51.288  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.288  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 05:07:51.288  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.288  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 05:07:51.288  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 05:07:51.288  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:07:51.288  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:07:51.288  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:07:51.289  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 05:07:51.289  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 05:07:51.289  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:07:51.289  4464  4710 D BtGatt.GattService: stopScan() - queue size =1
08-29 05:07:51.290  4464  4712 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 05:07:51.290  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 05:07:51.290  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 05:07:51.290  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 05:07:51.290  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 05:07:51.290  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 05:07:51.290  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.290  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 05:07:51.290  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 05:07:51.290  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 05:07:51.291  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.291  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.291  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.292  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.292  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.292  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.292  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.292  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.292  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.292  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.292  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.292  4464  4538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 05:07:51.292  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.292  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.293  5662  5708 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 05:07:51.293  4464  4545 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 05:07:51.293  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.296  4464  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 05:07:51.296  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.296  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.296  4464  4545 D BtGatt.ScanManager: Starting BLE batch scan
08-29 05:07:51.297  4464  4545 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 05:07:51.297  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.297  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:07:51.297  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:07:51.297  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 05:07:51.297  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 05:07:51.297  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.297  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 05:07:51.298  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.299  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 05:07:51.299  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 05:07:51.300  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.301  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 05:07:51.302  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 05:07:51.302  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 05:07:51.305  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 05:07:51.305  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 05:07:51.305  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 05:07:51.305  4464  4538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 05:07:51.305  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.305  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:07:51.306  4464  4710 D BtGatt.GattService: registerClient() - UUID=fe9cba7d-8b8f-4648-8e93-b95969e88b25
08-29 05:07:51.307  4464  4538 D BtGatt.GattService: onClientRegistered() - UUID=fe9cba7d-8b8f-4648-8e93-b95969e88b25, clientIf=5
08-29 05:07:51.307  5662  5673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 05:07:51.307  4464  4479 D BtGatt.GattService: start scan with filters
08-29 05:07:51.309  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 05:07:51.309  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 05:07:51.309  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 05:07:51.310  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 05:07:51.310  4464  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 05:07:51.310  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.310  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:07:51.311  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 05:07:51.311  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:07:51.311  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 05:07:51.312  5662  5708 I io.jxcore.node.ConnectionHelper: start: OK
08-29 05:07:51.314  4464  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 05:07:51.314  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.314  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.314  5662  5708 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 05:07:51.314  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.314  4464  4545 D BtGatt.ScanManager: stopping BLe Batch
08-29 05:07:51.314  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 05:07:51.315  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.315  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 05:07:51.315  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 05:07:51.315  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:07:51.315  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:07:51.315  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:07:51.315  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 05:07:51.315  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 05:07:51.315  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:07:51.315  4464  4477 D BtGatt.GattService: stopScan() - queue size =0
08-29 05:07:51.317  4464  4479 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 05:07:51.317  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 05:07:51.317  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 05:07:51.317  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 05:07:51.317  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 05:07:51.317  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 05:07:51.318  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.318  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 05:07:51.318  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 05:07:51.318  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 05:07:51.318  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.318  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.318  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.318  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.318  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.318  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.319  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.319  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.319  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.319  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.319  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.319  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.319  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.319  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.319  4464  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 05:07:51.319  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.319  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.319  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.319  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.319  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.319  4464  4545 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 05:07:51.320  5662  5708 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 05:07:51.320  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.323  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.323  4464  4538 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 05:07:51.323  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.323  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.324  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:07:51.324  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:07:51.324  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 05:07:51.324  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 05:07:51.324  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.324  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 05:07:51.325  4464  4545 D BtGatt.ScanManager: handling starting scan
08-29 05:07:51.325  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.326  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.326  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 05:07:51.326  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 05:07:51.328  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 05:07:51.329  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 05:07:51.329  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 05:07:51.330  4464  4538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 05:07:51.330  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.330  4464  4545 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 05:07:51.331  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 05:07:51.331  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 05:07:51.332  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 05:07:51.332  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:07:51.333  4464  4479 D BtGatt.GattService: registerClient() - UUID=e10efe09-a69f-4aa6-9ef0-21efdbcc8339
08-29 05:07:51.334  4464  4538 D BtGatt.GattService: onClientRegistered() - UUID=e10efe09-a69f-4aa6-9ef0-21efdbcc8339, clientIf=5
08-29 05:07:51.334  5662  5672 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 05:07:51.334  4464  4710 D BtGatt.GattService: start scan with filters
08-29 05:07:51.335  4464  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 05:07:51.335  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.335  4464  4545 D BtGatt.ScanManager: Starting BLE batch scan
08-29 05:07:51.335  4464  4545 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 05:07:51.337  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 05:07:51.337  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 05:07:51.337  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 05:07:51.337  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 05:07:51.338  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:07:51.338  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 05:07:51.338  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:07:51.339  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 05:07:51.340  5662  5708 I io.jxcore.node.ConnectionHelper: start: OK
08-29 05:07:51.340  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.340  5662  5708 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 05:07:51.340  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.340  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 05:07:51.340  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.340  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 05:07:51.340  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 05:07:51.340  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:07:51.340  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:07:51.340  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:07:51.340  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 05:07:51.340  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 05:07:51.341  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:07:51.341  4464  4712 D BtGatt.GattService: stopScan() - queue size =1
08-29 05:07:51.341  4464  4477 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 05:07:51.341  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 05:07:51.341  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 05:07:51.342  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 05:07:51.342  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 05:07:51.342  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 05:07:51.342  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.342  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 05:07:51.342  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 05:07:51.342  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 05:07:51.343  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.343  4464  4538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 05:07:51.343  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.344  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.344  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.344  5662  5708 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 05:07:51.344  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.344  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.344  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.344  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.345  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.345  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.345  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:07:51.345  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.345  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.345  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.345  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.345  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.345  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.345  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.346  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.346  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.347  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.347  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.347  5662  5708 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 05:07:51.347  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.347  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.347  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.347  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.347  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.348  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.348  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.348  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.348  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.348  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.348  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.348  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.348  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.348  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.348  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.348  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.348  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.348  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.349  4464  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 05:07:51.349  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.349  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 05:07:51.349  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.349  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.349  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.349  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.349  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.349  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.349  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.349  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.349  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.349  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.349  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.349  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.349  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.349  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.350  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.350  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.350  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.350  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.351  5662  5708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 05:07:51.351  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.351  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.351  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.351  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.351  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.351  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.351  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.351  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.351  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.351  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.351  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.351  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.351  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.351  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.352  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.352  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.352  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.352  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.352  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 05:07:51.352  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.352  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.352  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.352  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.352  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.353  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.353  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.353  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.353  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.353  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.353  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.353  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.353  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.353  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.353  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.353  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.353  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.353  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.354  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 05:07:51.354  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 05:07:51.354  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 05:07:51.354  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 05:07:51.354  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 05:07:51.354  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 05:07:51.354  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.354  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.354  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.354  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.354  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.354  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.354  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.354  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.354  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.354  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.354  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.354  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.355  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.355  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.355  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.355  4464  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 05:07:51.355  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.355  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.355  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.355  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.355  4464  4545 D BtGatt.ScanManager: stopping BLe Batch
08-29 05:07:51.355  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 05:07:51.355  5662  5708 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 05:07:51.356  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 05:07:51.357  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 05:07:51.357  5662  5708 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 05:07:51.357  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 05:07:51.358  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 05:07:51.358  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 05:07:51.358  5662  5708 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 05:07:51.358  5662  5708 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 05:07:51.358  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 05:07:51.358  5662  5708 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 05:07:51.359  5662  5708 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 05:07:51.359  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 05:07:51.359  5662  5708 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 05:07:51.359  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 05:07:51.360  4464  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 05:07:51.360  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.360  4464  4545 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 05:07:51.362  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 05:07:51.362  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 05:07:51.362  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 05:07:51.363  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 05:07:51.363  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 05:07:51.363  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 05:07:51.363  5662  5708 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 05:07:51.363  5662  5708 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 05:07:51.363  5662  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
08-29 05:07:51.363  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.363  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.363  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.364  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.364  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.364  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.364  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 05:07:51.364  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.364  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.364  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.364  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.364  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.364  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.364  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.364  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.365  4464  4538 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 05:07:51.365  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.366  4464  4545 D BtGatt.ScanManager: handling starting scan
08-29 05:07:51.367  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.367  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.367  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.367  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.367  5662  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
08-29 05:07:51.368  5662  5708 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 05:07:51.368  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.368  5662  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 05:07:51.368  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.369  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.369  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.369  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.369  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.369  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.369  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.369  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.369  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.369  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.369  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.369  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.369  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.371  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.371  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.371  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.371  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.372  5662  5708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 05:07:51.372  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.372  4464  4538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 05:07:51.372  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.372  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.372  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.372  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.372  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.372  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.372  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.372  4464  4545 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 05:07:51.373  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.373  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.373  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.373  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.373  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.373  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.373  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.377  4464  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 05:07:51.377  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.377  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.377  4464  4545 D BtGatt.ScanManager: Starting BLE batch scan
08-29 05:07:51.377  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.377  4464  4545 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 05:07:51.377  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.377  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.378  5662  5708 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 05:07:51.378  5662  5708 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 05:07:51.378  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 05:07:51.378  5662  5708 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 05:07:51.378  5662  5708 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 05:07:51.378  5662  5708 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 05:07:51.378  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 05:07:51.378  5662  5708 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 05:07:51.378  5662  5708 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 05:07:51.378  5662  5708 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 05:07:51.378  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 05:07:51.378  5662  5708 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 05:07:51.378  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.378  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.379  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.379  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.379  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.379  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.379  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.379  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.379  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.379  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.379  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.379  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.379  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.379  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.379  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.380  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.380  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.380  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.380  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.380  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.380  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.380  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.380  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.380  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.380  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.380  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.380  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.380  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.380  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.380  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.380  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.380  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.380  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.380  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.381  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.381  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.381  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.381  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.381  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.381  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.381  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.381  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.381  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.381  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.381  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.381  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.381  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.381  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.382  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.382  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.382  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.382  5662  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 05:07:51.382  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.383  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 05:07:51.383  5662  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 05:07:51.383  5662  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 05:07:51.383  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 05:07:51.383  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 05:07:51.383  5662  5662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 05:07:51.384  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.384  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 05:07:51.384  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 05:07:51.384  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 05:07:51.384  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.384  5662  5708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 05:07:51.384  5662  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 05:07:51.384  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.384  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.384  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:07:51.384  5662  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 05:07:51.384  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:07:51.384  5662  5662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 05:07:51.384  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:07:51.385  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.385  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.385  5662  5662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 05:07:51.385  4464  4538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 05:07:51.385  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.385  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.386  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.386  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.386  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.386  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.386  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.386  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.386  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.386  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.386  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:07:51.386  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.386  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:07:51.386  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.386  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.386  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.386  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.386  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.386  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.386  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.387  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.387  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.387  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.387  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.388  5662  5708 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 05:07:51.388  5662  5708 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 05:07:51.389  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 05:07:51.389  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 05:07:51.389  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.389  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.389  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.389  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.389  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.389  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.389  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.389  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.389  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.389  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.389  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.389  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.389  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.389  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.391  4464  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 05:07:51.391  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.392  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.392  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.392  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.392  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.396  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.396  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:07:51.396  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.396  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.396  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.396  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.396  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.396  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.396  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorli,b.DiscoveryManager@26b729b not in the list
08-29 05:07:51.396  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.396  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.396  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.396  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.397  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.398  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.398  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.398  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.398  4464  4538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 05:07:51.398  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.398  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
,08-29 05:07:51.398  4464  4545 D BtGatt.ScanManager: stopping BLe Batch
08-29 05:07:51.399  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:07:51.399  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 05:07:51.399  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:07:51.399  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:07:51.399  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.399  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.399  5662  5708 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1326aa not in the list
08-29 05:07:51.399  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.399  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.399  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:07:51.399  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.399  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:07:51.399  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:07:51.399  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:07:51.403  4464  4538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 05:07:51.403  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:07:51.403  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:07:51.403  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:07:51.404  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:07:51.404  4464  4545 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 05:07:51.404  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26b729b not in the list
08-29 05:07:51.404  5662  5708 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-29 05:07:51.404  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 05:07:51.405  5662  5708 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 05:07:51.405  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 05:07:51.405  5662  5708 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 05:07:51.405  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 05:07:51.406  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 05:07:51.406  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 05:07:51.407  5662  5708 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 05:07:51.407  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 05:07:51.407  5662  5708 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 05:07:51.407  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 05:07:51.407  5662  5708 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 05:07:51.407  5662  5708 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 05:07:51.408  5662  5708 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 05:07:51.408  5662  5708 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 05:07:51.408  5662  5708 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 05:07:51.408  5662  5708 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 05:07:51.408  5662  5708 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 05:07:51.408  4464  4538 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 05:07:51.408  5662  5708 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 05:07:51.408  4464  4538 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:07:51.409  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:07:51.409  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6286e05 added. We now have 2 listener(s)
08-29 05:07:51.409  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:07:51.411  5662  5708 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 05:07:51.411   929   940 D WifiService: setWifiEnabled: true pid=5662, uid=10077
08-29 05:07:51.411   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 05:07:51.412  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:07:51.412  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ca388b added. We now have 3 listener(s)
08-29 05:07:51.412  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:07:51.416  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:07:51.416  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad69d68 added. We now have 4 listener(s)
08-29 05:07:51.416  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:07:51.417  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:07:51.417  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c6e581 added. We now have 5 listener(s)
08-29 05:07:51.417  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:07:51.418   929  3621 D WifiService: setWifiEnabled: false pid=5662, uid=10077
08-29 05:07:51.418   929  3621 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 05:07:51.422  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:07:51.423  4464  4534 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 05:07:51.423  4464  4534 D BluetoothAdapterProperties: Setting state to 13
08-29 05:07:51.423  4464  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 05:07:51.423  4464  4534 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 05:07:51.424  4464  4534 I BluetoothAdapterState: Entering PendingCommandState
08-29 05:07:51.424  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.424  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.424  4464  4538 D BluetoothAdapterProperties: Scan Mode:20
08-29 05:07:51.424  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.425  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.425  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:07:51.425  4464  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 05:07:51.426  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.427  4464  4464 D HeadsetService: Received stop request...Stopping profile...
,08-29 05:07:51.427  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.428   929   929 D BluetoothHeadset: Proxy object disconnected
,08-29 05:07:51.429  3624  3658 D BluetoothHeadset: Proxy object disconnected
08-29 05:07:51.429   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 05:07:51.429  4464  4464 D A2dpService: Received stop request...Stopping profile...
08-29 05:07:51.430  4464  4714 D A2dpStateMachine: Exit Disconnected: -1
08-29 05:07:51.430  3205  3217 D BluetoothHeadset: Proxy object disconnected
08-29 05:07:51.430  3205  3205 D HeadsetProfile: Bluetooth service disconnected
08-29 05:07:51.430   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 05:07:51.430  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.430  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.431  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.431   929   929 D RttService: SCAN_AVAILABLE : 1
08-29 05:07:51.431  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.432   929  3158 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 05:07:51.433  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.434  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.436  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.443   929   942 I ActivityManager: Start proc 5738:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 05:07:51.444   929   929 D BluetoothA2dp: Proxy object disconnected
,08-29 05:07:51.444  4464  4464 V BluetoothAdapterState: isTurningOff()=true
08-29 05:07:51.445  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.445  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:07:51.445  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:07:51.445  4464  4464 D HidService: Received stop request...Stopping profile...
08-29 05:07:51.445  4464  4464 D HidService: Stopping Bluetooth HidService
,08-29 05:07:51.448   929  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 05:07:51.449   929  3049 E native  : do suspend true
,08-29 05:07:51.453  4464  4464 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 05:07:51.453  4464  4464 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 05:07:51.453  4464  4538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 05:07:51.454  4464  4464 D HealthService: Received stop request...Stopping profile...
08-29 05:07:51.454  3205  3205 D BluetoothA2dp: Proxy object disconnected
08-29 05:07:51.454  3205  3205 D BluetoothInputDevice: Proxy object disconnected
08-29 05:07:51.454  3205  3205 D HidProfile: Bluetooth service disconnected
08-29 05:07:51.454  4464  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:07:51.454  4464  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:07:51.454  4464  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:07:51.454  4464  4538 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 05:07:51.455  4464  4464 V BluetoothAdapterState: isTurningOff()=true
08-29 05:07:51.456  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.456  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:07:51.456  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:07:51.456  4464  4464 D BluetoothMapService: onReceive
08-29 05:07:51.456  4464  4464 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 05:07:51.456  4464  4464 D BluetoothMapService: STATE_TURNING_OFF
,08-29 05:07:51.458  4464  4538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 05:07:51.458  4464  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:07:51.458  4464  4464 D PanService: Received stop request...Stopping profile...
08-29 05:07:51.459  4464  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:07:51.459  4464  4690 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 05:07:51.459  4464  4690 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 05:07:51.459  4464  4690 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 05:07:51.459  4464  4690 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 05:07:51.460   508   922 D CommandListener: Clearing all IP addresses on wlan0
08-29 05:07:51.460  3205  3205 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 05:07:51.460  3205  3205 D PanProfile: Bluetooth service disconnected
,08-29 05:07:51.460  4464  4464 V BluetoothAdapterState: isTurningOff()=true
08-29 05:07:51.460  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.460  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:07:51.460  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:07:51.461  4464  4464 D BluetoothMapService: Received stop request...Stopping profile...
08-29 05:07:51.461  4464  4464 D BluetoothMapService: stop()
08-29 05:07:51.462  4464  4464 D BluetoothMapAppObserver: deinitObservers()
08-29 05:07:51.462  4464  4464 D BluetoothMapAppObserver: removeReceiver()
,08-29 05:07:51.463  3205  3205 D BluetoothMap: Proxy object disconnected
08-29 05:07:51.463  3205  3205 D MapProfile: Bluetooth service disconnected
,08-29 05:07:51.471  4464  4464 D SapService: Received stop request...Stopping profile...
08-29 05:07:51.471  4464  4464 V SapService: stop()
,08-29 05:07:51.474   929  3049 D DhcpClient: doQuit
,08-29 05:07:51.474   929  3049 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 05:07:51.475   929  5335 D DhcpClient: onQuitting
08-29 05:07:51.475  3732  3732 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 05:07:51.476  4464  4464 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 05:07:51.476  4464  4464 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 05:07:51.476  4464  4464 V BluetoothAdapterState: isTurningOff()=true
08-29 05:07:51.476  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.476  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 05:07:51.476  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 05:07:51.476  4464  4464 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 05:07:51.477  4464  4464 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 05:07:51.477  4464  4538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 05:07:51.477  4464  4464 I BtOppRfcommListener: stopping Accept Thread
,08-29 05:07:51.477  4464  4538 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 05:07:51.477  4464  5296 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 05:07:51.477  4464  5296 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 05:07:51.478  4464  4464 V BluetoothAdapterState: isTurningOff()=true
08-29 05:07:51.478  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.478  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:07:51.478  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 05:07:51.479  4464  4464 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 05:07:51.479  4464  4464 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 05:07:51.480  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.480  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.481  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.481  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.481  4464  4464 D BluetoothMapService: MAP Service closeService in
08-29 05:07:51.481  4464  4464 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 05:07:51.481  4464  4464 D ObexServerSockets0: shutdown(block = true)
08-29 05:07:51.482  4464  4734 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-29 05:07:51.482  4464  4464 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 05:07:51.482  4464  4464 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 05:07:51.482  4464  4738 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 05:07:51.483  4464  4707 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 05:07:51.483  4464  4464 V BluetoothAdapterState: isTurningOff()=true
08-29 05:07:51.483  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.483  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 05:07:51.483  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:07:51.483  4464  4464 D BluetoothMapService: cleanup()
08-29 05:07:51.483  4464  4464 D BluetoothMapService: MAP Service closeService in
08-29 05:07:51.483  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:51.484  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:51.484  4464  4464 V BluetoothAdapterState: isTurningOff()=true
,08-29 05:07:51.484  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.484  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:07:51.484  4464  4464 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 05:07:51.484  4464  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 05:07:51.484  4464  4534 D BluetoothAdapterProperties: Setting state to 15
08-29 05:07:51.484  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:51.485  4464  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 05:07:51.485  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:07:51.485   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:07:51.485  3205  3217 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 05:07:51.486  4464  4534 I BluetoothAdapterState: Entering BleOnState
08-29 05:07:51.486   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 05:07:51.487  3205  5661 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:07:51.487  3205  3216 D BluetoothMap: onBluetoothStateChange: up=false
08-29 05:07:51.488  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,08-29 05:07:51.490  3205  3813 D BluetoothPan: onBluetoothStateChange on: false
08-29 05:07:51.491   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:07:51.492  3624  3658 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:07:51.492  3205  3217 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 05:07:51.493  3205  5661 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 05:07:51.493   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:07:51.494  4464  4534 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 05:07:51.494  4464  4534 D BluetoothAdapterProperties: Setting state to 16
08-29 05:07:51.494  4464  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 05:07:51.496  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.497  4464  4534 D BluetoothAdapterProperties: onBleDisable
08-29 05:07:51.497  4464  4534 I BluetoothAdapterState: Entering PendingCommandState
08-29 05:07:51.497  4464  4535 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 05:07:51.498  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.498  4464  4538 D BluetoothAdapterProperties: Scan Mode:20
,08-29 05:07:51.502  4464  4690 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 05:07:51.502  4464  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:07:51.502  5662  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,08-29 05:07:51.503  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:07:51.503  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 05:07:51.504  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.508   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa24fe7:true
,08-29 05:07:51.509  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 05:07:51.513  3732  3732 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 05:07:51.531   929  3631 I ActivityManager: Start proc 5750:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 05:07:51.541  5738  5738 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 05:07:51.545  5738  5738 D BluetoothMap: Create BluetoothMap proxy object
,08-29 05:07:51.556  5738  5738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 05:07:51.563  5750  5750 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 05:07:51.568  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,08-29 05:07:51.575   929  3631 I ActivityManager: Killing 5076:com.google.android.gm/u0a68 (adj 15): empty #17
,08-29 05:07:51.585  3732  3732 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 05:07:51.602  3732  3732 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 05:07:51.705  4317  4317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 05:07:51.706   929  3049 D wifi    : In wifi stop Hal
08-29 05:07:51.706   929  3049 D wifi    : halHandle = 0x7f68274900, mVM = 0x7f8468d140, mCls = 0x100b46
08-29 05:07:51.706   929  3728 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 05:07:51.706   929  3728 D WifiHAL : Got a signal to exit!!!
08-29 05:07:51.706   929  3728 I WifiHAL : Exit wifi_event_loop
08-29 05:07:51.706   929  3049 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 05:07:51.706   929  3049 E WifiHAL : Event processing terminated
08-29 05:07:51.707   929  3049 D wifi    : In wifi cleaned up handler
08-29 05:07:51.707   929  3049 I WifiHAL : Internal cleanup completed
08-29 05:07:51.708  3714  4062 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 05:07:51.709  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.710  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:51.715  4464  4538 I bt_hci  : shut_down
,08-29 05:07:51.717  4464  4547 D bt_hwcfg: hw_epilog_process
,08-29 05:07:51.719  4464  4547 I bt_vendor: low_power_mode_cb
,08-29 05:07:51.722  4464  4547 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 05:07:51.722  4464  4547 I bt_vendor: epilog_cb
08-29 05:07:51.722  4464  4547 I bt_hci  : epilog_finished_callback
,08-29 05:07:51.725  4464  4538 I bt_hci_h4: hal_close
,08-29 05:07:51.725  4464  4538 I bt_userial_vendor: device fd = 51 close
,08-29 05:07:51.733   929  3728 D wifi    : set interface wlan0 flags (DOWN)
08-29 05:07:51.733   929  3049 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 05:07:51.799  5750  5750 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.799  5750  5750 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.799  5750  5750 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.799  5750  5750 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.799  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.800  5750  5750 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.800  5750  5750 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.800  5750  5750 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.800  5750  5750 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 05:07:51.800  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 05:07:51.814   929  3226 I ActivityManager: Start proc 5779:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-29 05:07:51.815   929  3226 I ActivityManager: Killing 5219:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 05:07:51.887  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 05:07:51.888  4464  4535 D bt_stack_manager: event_shut_down_stack finished.
,08-29 05:07:51.888  4464  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 05:07:51.890  4464  4534 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 05:07:51.890  4464  4464 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 05:07:51.890  4464  4464 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 05:07:51.891  4464  4464 D BtGatt.GattService: stop()
08-29 05:07:51.891  4464  4464 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 05:07:51.892  4464  4464 V BluetoothAdapterState: isTurningOff()=false
08-29 05:07:51.892  4464  4464 V BluetoothAdapterState: isTurningOn()=false
08-29 05:07:51.892  4464  4464 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:07:51.892  4464  4464 V BluetoothAdapterState: isBleTurningOff()=true
08-29 05:07:51.892  4464  4534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 05:07:51.893  4464  4534 D BluetoothAdapterProperties: Setting state to 10
08-29 05:07:51.893  4464  4534 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 05:07:51.893  4464  4534 I BluetoothAdapterState: Entering OffState
,08-29 05:07:51.894   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 05:07:51.899  4464  4464 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 05:07:51.899  4464  4464 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 05:07:51.899  4464  4464 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 05:07:51.900  4464  4535 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 05:07:51.902  4464  4535 D bt_stack_manager: event_clean_up_stack finished.
,08-29 05:07:51.910  5779  5779 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 05:07:51.912  4464  4464 I art     : System.exit called, status: 0
08-29 05:07:51.912  4464  4464 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 05:07:51.937   929   946 D Tethering: InitialState.processMessage what=4
,08-29 05:07:51.939   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 05:07:51.975  5779  5779 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 05:07:51.982   929  3535 I ActivityManager: Killing 4560:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 05:07:52.039   929  5075 I ActivityManager: Process com.android.bluetooth (pid 4464) has died
,08-29 05:07:52.044  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 05:07:52.060   929  3224 I ActivityManager: Start proc 5806:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 05:07:52.063  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,08-29 05:07:52.079  5750  5768 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 05:07:52.113  5806  5806 D AdapterServiceConfig: Adding HeadsetService
,08-29 05:07:52.113  5806  5806 D AdapterServiceConfig: Adding A2dpService
08-29 05:07:52.113  5806  5806 D AdapterServiceConfig: Adding HidService
08-29 05:07:52.113  5806  5806 D AdapterServiceConfig: Adding HealthService
08-29 05:07:52.113  5806  5806 D AdapterServiceConfig: Adding PanService
08-29 05:07:52.113  5806  5806 D AdapterServiceConfig: Adding GattService
08-29 05:07:52.114  5806  5806 D AdapterServiceConfig: Adding BluetoothMapService
08-29 05:07:52.114  5806  5806 D AdapterServiceConfig: Adding SapService
08-29 05:07:52.116   929  5075 I ActivityManager: Killing 5546:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 05:07:52.130   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36dfea9:true
,08-29 05:07:52.155  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 05:07:54.427   929   940 D WifiService: setWifiEnabled: true pid=5662, uid=10077
,08-29 05:07:54.427   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 05:07:54.436   508   922 D SoftapController: Softap fwReload - Ok
,08-29 05:07:54.441   508   922 D CommandListener: Setting iface cfg
08-29 05:07:54.441   508   922 D CommandListener: Trying to bring down wlan0
,08-29 05:07:54.443   508   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 05:07:54.446   929  3049 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 05:07:55.053   929  3049 D wifi    : set interface wlan0 flags (UP)
,08-29 05:07:55.056   929  3049 I WifiHAL : Initializing wifi
,08-29 05:07:55.056   929  3049 I WifiHAL : Creating socket
,08-29 05:07:55.062   929  3049 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 05:07:55.063   929  3049 D wifi    : Did set static halHandle = 0x7f68274900
08-29 05:07:55.064   929  3049 D wifi    : halHandle = 0x7f68274900, mVM = 0x7f8468d140, mCls = 0x20191a
08-29 05:07:55.064   929  3049 D wifi    : array field set
08-29 05:07:55.064   929  3049 I WifiNative-HAL: interface[0] = wlan0
,08-29 05:07:55.064   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 05:07:55.068   929  5821 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547208251648
08-29 05:07:55.069   929  5821 D wifi    : waitForHalEvents called, vm = 0x7f8468d140, obj = 0x20191a, env = 0x7f69f7af00
,08-29 05:07:55.131  5822  5822 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 05:07:55.153  5822  5822 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 05:07:55.168   929  3049 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 05:07:55.176  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:55.180  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:55.185  5822  5822 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 05:07:55.185  5822  5822 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 05:07:55.201   929  3049 D WifiConfigStore: Loading config and enabling all networks 
,08-29 05:07:55.201  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:55.201  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:55.201  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:55.201  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:07:55.203  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:55.203  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:55.203  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:55.203  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:07:55.208   929  3049 D WifiConfigStore: loaded 0 passpoint configs
,08-29 05:07:55.208   929  3049 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 05:07:55.208   929  3049 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 05:07:55.209   929  3049 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 05:07:55.209   929  3049 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 05:07:55.209   929  3049 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 05:07:55.213  4317  4317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 05:07:55.213   929  3049 D WifiNative-HAL: Setting external_sim to 1
08-29 05:07:55.215   929  3049 D wifi    : setting dfs flag to true, 0x7f6a2fc1a0
,08-29 05:07:55.215   929  3049 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 05:07:55.216   929  3049 D wifi    : setting scan oui 0x7f6a2fc1a0
08-29 05:07:55.216   929  3049 D WifiHAL : Sending mac address OUI
,08-29 05:07:55.230   929  3049 E native  : do suspend true
,08-29 05:07:55.236   929  3049 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 05:07:55.236   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 05:07:55.236   929   929 D RttService: SCAN_AVAILABLE : 3
08-29 05:07:55.236   929  3158 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 05:07:55.237   508   922 D CommandListener: Setting iface cfg
,08-29 05:07:55.242   929  3048 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '65 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 65 Failed to set address (No such device)'
,08-29 05:07:55.242   929  3048 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 05:07:55.245   929  3048 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 05:07:55.249   929  3048 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 05:07:55.267   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=177824 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,08-29 05:07:57.435   929   940 D WifiService: setWifiEnabled: false pid=5662, uid=10077
,08-29 05:07:57.435   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 05:07:57.460   929   929 D RttService: SCAN_AVAILABLE : 1
,08-29 05:07:57.461   929  3158 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 05:07:57.484   929  3049 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 05:07:57.486   508   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 05:07:57.492   929  3049 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 05:07:57.494  5822  5822 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 05:07:57.502  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:57.502  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:57.502  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:57.503  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:07:57.506  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:07:57.506  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:07:57.506  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:07:57.506  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:07:57.516  5822  5822 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 05:07:57.523  5822  5822 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 05:07:57.525  5822  5822 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 05:07:57.534  4317  4317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 05:07:57.534   929  3049 D wifi    : In wifi stop Hal
,08-29 05:07:57.535   929  3049 D wifi    : halHandle = 0x7f68274900, mVM = 0x7f8468d140, mCls = 0x20191a
08-29 05:07:57.535   929  5821 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 05:07:57.535   929  5821 D WifiHAL : Got a signal to exit!!!
,08-29 05:07:57.535   929  5821 I WifiHAL : Exit wifi_event_loop
08-29 05:07:57.536   929  3049 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 05:07:57.536   929  3049 E WifiHAL : Event processing terminated
08-29 05:07:57.537   929  3049 D wifi    : In wifi cleaned up handler
08-29 05:07:57.537  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:57.537   929  3049 I WifiHAL : Internal cleanup completed
08-29 05:07:57.539  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:07:57.541  3714  4062 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 05:07:57.567   929  5821 D wifi    : set interface wlan0 flags (DOWN)
,08-29 05:07:57.568   929  3049 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 05:07:57.775   929   946 D Tethering: InitialState.processMessage what=4
,08-29 05:07:57.780   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 05:08:00.469   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@224ecde:true
,08-29 05:08:00.470  5806  5806 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 05:08:00.476  5806  5806 I bt_bluedroid: init
,08-29 05:08:00.476  5806  5828 I BluetoothAdapterState: Entering OffState
,08-29 05:08:00.480  5806  5829 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 05:08:00.480  5806  5829 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 05:08:00.480  5806  5829 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 05:08:00.480  5806  5829 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 05:08:00.481  5806  5806 I bt_bluedroid: get_profile_interface socket
,08-29 05:08:00.486  5806  5806 I bt_bluedroid: get_profile_interface sdp
,08-29 05:08:00.486  5806  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 05:08:00.489  5806  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 05:08:00.491  5806  5817 I bt_bluedroid: config_hci_snoop_log
,08-29 05:08:00.494   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 05:08:00.500  5806  5828 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 05:08:00.500  5806  5828 D BluetoothAdapterProperties: Setting state to 14
08-29 05:08:00.500  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 05:08:00.503  5806  5828 D BluetoothBondStateMachine: make
,08-29 05:08:00.505  5806  5833 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 05:08:00.509  5806  5828 I BluetoothAdapterState: Entering PendingCommandState
,08-29 05:08:00.510  5806  5806 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 05:08:00.514  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:00.515  5806  5806 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 05:08:00.517  5806  5806 D BtGatt.GattService: Received start request. Starting profile...
08-29 05:08:00.517  5806  5806 D BtGatt.GattService: start()
08-29 05:08:00.517  5806  5806 I bt_bluedroid: get_profile_interface gatt
,08-29 05:08:00.519  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:00.519  5806  5806 D BtGatt.AdvertiseManager: advertise manager created
,08-29 05:08:00.526  5806  5806 V BluetoothAdapterState: isTurningOff()=false
,08-29 05:08:00.526  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:00.526  5806  5806 V BluetoothAdapterState: isBleTurningOn()=true
08-29 05:08:00.527  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:00.527  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 05:08:00.527  5806  5828 I bt_bluedroid: enable
08-29 05:08:00.527  5806  5829 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 05:08:00.528  5806  5829 I bt_hci  : start_up
,08-29 05:08:00.536  5806  5829 I bt_vendor: alloc value 0xf3bf904d
,08-29 05:08:00.536  5806  5829 I bt_vendor: init
08-29 05:08:00.536  5806  5829 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 05:08:00.536  5806  5829 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 05:08:00.656  5806  5829 D bt_hci  : start_up starting async portion
,08-29 05:08:00.657  5806  5836 I bt_hci  : event_finish_startup
08-29 05:08:00.657  5806  5836 I bt_hci_h4: hal_open
08-29 05:08:00.657  5806  5836 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 05:08:00.660  5806  5836 I bt_userial_vendor: device fd = 51 open
,08-29 05:08:00.645  5837  5837 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 05:08:00.674  5806  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 05:08:00.677  5806  5836 D bt_hwcfg: Chipset BCM4358A3
08-29 05:08:00.677  5806  5836 D bt_hwcfg: Target name = [BCM4358A3]
08-29 05:08:00.678  5806  5836 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 05:08:01.076  5806  5836 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-29 05:08:01.076  5806  5836 D bt_hwcfg: Settlement delay -- 100 ms
08-29 05:08:01.076  5806  5836 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 05:08:01.209  5806  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 05:08:01.210  5806  5836 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-29 05:08:01.211  5806  5836 I bt_hwcfg: vendor lib fwcfg completed
08-29 05:08:01.211  5806  5836 I bt_vendor: firmware callback
08-29 05:08:01.211  5806  5836 I bt_hci  : firmware_config_callback
,08-29 05:08:01.221  5806  5839 I bt_btu  : btu_task pending for preload complete event
08-29 05:08:01.221  5806  5839 I bt_btu_task: Bluetooth chip preload is complete
08-29 05:08:01.221  5806  5839 I bt_btu  : btu_task received preload complete event
,08-29 05:08:01.227  5806  5839 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 05:08:01.227  5806  5839 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 05:08:01.227  5806  5839 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 05:08:01.227  5806  5839 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 05:08:01.228  5806  5839 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 05:08:01.229  5806  5839 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 05:08:01.229  5806  5839 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 05:08:01.229  5806  5839 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 05:08:01.305  5806  5839 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b76c99
08-29 05:08:01.305  5806  5839 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b76c99 
,08-29 05:08:01.318  5806  5832 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 05:08:01.319  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 05:08:01.320  5806  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 05:08:01.322  5806  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 05:08:01.326  5806  5832 D BluetoothAdapterProperties: Scan Mode:20
08-29 05:08:01.327  5806  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 05:08:01.327  5806  5832 D bt_hci  : do_postload posting postload work item
08-29 05:08:01.327  5806  5836 I bt_hci  : event_postload
08-29 05:08:01.327  5806  5836 I bt_vendor: sco_config_cb
08-29 05:08:01.327  5806  5836 I bt_hci  : sco_config_callback postload finished.
,08-29 05:08:01.330  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:01.334  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:01.337  5806  5832 D bt_bte_conf: Device ID record 1 : primary
08-29 05:08:01.337  5806  5832 D bt_bte_conf:   vendorId            = 000f
,08-29 05:08:01.337  5806  5832 D bt_bte_conf:   vendorIdSource      = 0001
08-29 05:08:01.337  5806  5832 D bt_bte_conf:   product             = 1200
08-29 05:08:01.337  5806  5832 D bt_bte_conf:   version             = 1436
08-29 05:08:01.337  5806  5832 D bt_bte_conf:   clientExecutableURL = 
08-29 05:08:01.338  5806  5832 D bt_bte_conf:   serviceDescription  = 
08-29 05:08:01.338  5806  5832 D bt_bte_conf:   documentationURL    = 
08-29 05:08:01.338  5806  5832 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 05:08:01.338  5806  5829 D bt_stack_manager: event_start_up_stack finished
08-29 05:08:01.339  5806  5836 I bt_vendor: low_power_mode_cb
,08-29 05:08:01.339  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 05:08:01.339  5806  5828 D BluetoothAdapterProperties: Setting state to 15
08-29 05:08:01.339  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 05:08:01.340  5806  5828 I BluetoothAdapterState: Entering BleOnState
,08-29 05:08:01.347  5806  5828 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 05:08:01.347  5806  5828 D BluetoothAdapterProperties: Setting state to 11
08-29 05:08:01.347  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 05:08:01.352  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:01.353  5806  5806 D HeadsetService: Received start request. Starting profile...
,08-29 05:08:01.356  5806  5806 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 05:08:01.356  5806  5806 D HeadsetStateMachine: make
,08-29 05:08:01.361  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:01.363  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:01.368  5806  5828 I BluetoothAdapterState: Entering PendingCommandState
,08-29 05:08:01.368  5806  5806 D HeadsetStateMachine: max_hf_connections = 1
,08-29 05:08:01.368  5806  5806 I bt_bluedroid: get_profile_interface handsfree
08-29 05:08:01.369  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 05:08:01.369  5806  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-29 05:08:01.372  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:01.373  5806  5806 D A2dpService: Received start request. Starting profile...
08-29 05:08:01.373  5806  5806 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 05:08:01.374  5806  5806 I bt_bluedroid: get_profile_interface avrcp
,08-29 05:08:01.378  5806  5806 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 05:08:01.379  5806  5806 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 05:08:01.379  5806  5806 D A2dpStateMachine: make
08-29 05:08:01.380  5806  5806 I bt_bluedroid: get_profile_interface a2dp
,08-29 05:08:01.381  5806  5847 D A2dpStateMachine: Enter Disconnected: -2
,08-29 05:08:01.382  5806  5806 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 05:08:01.382  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 05:08:01.383  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:01.384  5738  5738 D BluetoothInputDevice: Proxy object connected
,08-29 05:08:01.385  5738  5738 D HidProfile: Bluetooth service connected
08-29 05:08:01.386  5806  5806 D HidService: Received start request. Starting profile...
08-29 05:08:01.386  5806  5806 I bt_bluedroid: get_profile_interface hidhost
08-29 05:08:01.386  5806  5806 D HidService: setHidService(): set to: null
08-29 05:08:01.386  5806  5832 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b582d9
08-29 05:08:01.386  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 05:08:01.387  5806  5806 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 05:08:01.387  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:01.388  5806  5806 D HealthService: Received start request. Starting profile...
,08-29 05:08:01.389  5806  5806 I bt_bluedroid: get_profile_interface health
,08-29 05:08:01.390  5806  5806 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 05:08:01.391  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:01.391  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 05:08:01.392  5806  5806 D PanService: Received start request. Starting profile...
08-29 05:08:01.392  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 05:08:01.392  5806  5806 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 05:08:01.392  5806  5806 I bt_bluedroid: get_profile_interface pan
08-29 05:08:01.393  5738  5738 D PanProfile: Bluetooth service connected
08-29 05:08:01.393  5806  5832 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 05:08:01.395  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:01.403  5738  5738 D BluetoothMap: Proxy object connected
08-29 05:08:01.404  5738  5738 D MapProfile: Bluetooth service connected
08-29 05:08:01.404  5738  5738 D BluetoothMap: getConnectedDevices()
08-29 05:08:01.404  5806  5806 D BluetoothMapService: Received start request. Starting profile...
08-29 05:08:01.405  5806  5806 D BluetoothMapService: start()
08-29 05:08:01.407  5806  5806 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 05:08:01.408  5806  5806 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 05:08:01.408  5806  5806 D BluetoothMapAppObserver: createReceiver()
,08-29 05:08:01.409  5806  5806 D BluetoothMapAppObserver: initObservers()
08-29 05:08:01.409  5806  5806 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 05:08:01.417  5806  5806 V SapService: SapBinder()
08-29 05:08:01.417  5806  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:01.417  5806  5806 D SapService: Received start request. Starting profile...
08-29 05:08:01.418  5806  5806 V SapService: start()
08-29 05:08:01.419  5806  5806 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:01.419  5806  5806 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:01.419  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.419  5806  5844 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 05:08:01.419  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOff()=false
,08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.420  5806  5806 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isTurningOn()=true
,08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.421  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.422  5806  5806 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:01.422  5806  5806 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:01.423  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:01.423  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:01.423  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 05:08:01.423  5806  5828 D BluetoothAdapterProperties: ScanMode =  20
08-29 05:08:01.423  5806  5828 D BluetoothAdapterProperties: State =  11
08-29 05:08:01.424  5738  5738 D BluetoothMap: Bluetooth is Not enabled
08-29 05:08:01.425  5806  5832 D BluetoothAdapterProperties: Scan Mode:21
08-29 05:08:01.425  5806  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 05:08:01.425  5806  5828 D BluetoothAdapterProperties: Setting state to 12
,08-29 05:08:01.425  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 05:08:01.425  5806  5828 I BluetoothAdapterState: Entering OnState
08-29 05:08:01.425   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:01.426  3205  3217 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 05:08:01.428   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 05:08:01.428  3205  3216 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:01.428  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:01.429  3205  3813 D BluetoothMap: onBluetoothStateChange: up=true
08-29 05:08:01.430   929   929 D BluetoothA2dp: Proxy object connected
08-29 05:08:01.431  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:01.431  3205  3217 D BluetoothPan: onBluetoothStateChange on: true
08-29 05:08:01.431  3205  3205 D BluetoothMap: Proxy object connected
08-29 05:08:01.431  3205  3205 D MapProfile: Bluetooth service connected
08-29 05:08:01.431  3205  3205 D BluetoothMap: getConnectedDevices()
08-29 05:08:01.433   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 05:08:01.434  5738  5748 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 05:08:01.434  3205  3205 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 05:08:01.434  3205  3205 D PanProfile: Bluetooth service connected
08-29 05:08:01.434  3624  3856 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:01.435  5738  5749 D BluetoothPan: onBluetoothStateChange on: true
08-29 05:08:01.435  3205  3813 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 05:08:01.435  5806  5806 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:01.436  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:01.436  5806  5806 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 05:08:01.437  3205  3205 D BluetoothInputDevice: Proxy object connected
08-29 05:08:01.437  3205  3205 D HidProfile: Bluetooth service connected
08-29 05:08:01.437  3205  5661 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 05:08:01.437  5806  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 05:08:01.439  3205  3205 D BluetoothA2dp: Proxy object connected
,08-29 05:08:01.439   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:01.439  5738  5748 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 05:08:01.440  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:01.441  5738  5749 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 05:08:01.443   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 05:08:01.443  5806  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 05:08:01.444  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:01.445  5738  5738 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 05:08:01.446  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:01.448  5806  5806 D ObexServerSockets: Succeed to create listening sockets 
08-29 05:08:01.448  5806  5806 D ObexServerSockets0: startAccept()
08-29 05:08:01.448  5806  5806 D ObexServerSockets0: prepareForNewConnect()
,08-29 05:08:01.449  5738  5738 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 05:08:01.450  5806  5806 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 05:08:01.450  5806  5806 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 05:08:01.450  5806  5853 D ObexServerSockets0: Accepting socket connection...
08-29 05:08:01.450  5806  5806 D BluetoothMapService: onReceive
08-29 05:08:01.450  5806  5806 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 05:08:01.451  5806  5806 D BluetoothMapService: STATE_ON
08-29 05:08:01.451  5806  5854 D ObexServerSockets0: Accepting socket connection...
08-29 05:08:01.453  5806  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 05:08:01.455  5806  5855 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 05:08:01.455  5806  5855 D BluetoothSdpJni: SDP Create record success - handle: 1
08-29 05:08:01.456  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 05:08:01.459  5738  5738 D BluetoothA2dp: Proxy object connected
,08-29 05:08:01.462  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 05:08:01.464  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,08-29 05:08:01.468  5738  5738 D BluetoothPbap: Proxy object connected
,08-29 05:08:01.469  5738  5738 D PbapServerProfile: Bluetooth service connected
,08-29 05:08:01.471  3205  3205 D BluetoothPbap: Proxy object connected
,08-29 05:08:01.472  3205  3205 D PbapServerProfile: Bluetooth service connected
,08-29 05:08:01.474  5806  5806 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 05:08:01.474  5806  5806 D ObexServerSockets0: prepareForNewConnect()
08-29 05:08:01.475  5806  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 05:08:01.489  5806  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 05:08:01.491  5806  5863 I BtOppRfcommListener: Accept thread started.
,08-29 05:08:01.527   929   929 D BluetoothHeadset: Proxy object connected
,08-29 05:08:01.527  3624  3660 D BluetoothHeadset: Proxy object connected
08-29 05:08:01.527   929   929 D BluetoothHeadset: Proxy object connected
08-29 05:08:01.527  3205  5661 D BluetoothHeadset: Proxy object connected
08-29 05:08:01.528  3205  3205 D HeadsetProfile: Bluetooth service connected
08-29 05:08:01.528   929   929 D BluetoothHeadset: Proxy object connected
08-29 05:08:01.528  3205  3813 D BluetoothHeadset: Proxy object connected
,08-29 05:08:01.529  3205  3205 D HeadsetProfile: Bluetooth service connected
,08-29 05:08:01.534   929   946 D BluetoothHeadset: Proxy object connected
,08-29 05:08:01.535  3624  3658 D BluetoothHeadset: Proxy object connected
,08-29 05:08:01.539   929   946 D BluetoothHeadset: Proxy object connected
,08-29 05:08:01.551  5738  5748 D BluetoothHeadset: Proxy object connected
,08-29 05:08:01.553  5738  5738 D HeadsetProfile: Bluetooth service connected
,08-29 05:08:03.453  5806  5828 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 05:08:03.453  5806  5828 D BluetoothAdapterProperties: Setting state to 13
,08-29 05:08:03.454  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 05:08:03.455  5806  5828 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 05:08:03.456  5806  5828 I BluetoothAdapterState: Entering PendingCommandState
08-29 05:08:03.461  5806  5806 D BluetoothMapService: onReceive
,08-29 05:08:03.461  5806  5806 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 05:08:03.462  5806  5806 D BluetoothMapService: STATE_TURNING_OFF
08-29 05:08:03.463  5806  5806 D BluetoothMapService: MAP Service closeService in
08-29 05:08:03.463  5806  5806 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 05:08:03.463  5806  5806 D ObexServerSockets0: shutdown(block = true)
08-29 05:08:03.464  5806  5853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 05:08:03.467  5806  5806 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 05:08:03.468  5806  5806 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 05:08:03.468  5806  5854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 05:08:03.468  5806  5841 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 05:08:03.470  5806  5806 I BtOppRfcommListener: stopping Accept Thread
08-29 05:08:03.470  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 05:08:03.470  5806  5863 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 05:08:03.471  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:03.471  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:03.471  5806  5863 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 05:08:03.473  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:08:03.473  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:08:03.478  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:03.479  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:03.480  5806  5832 D BluetoothAdapterProperties: Scan Mode:20
08-29 05:08:03.480  5662  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 05:08:03.480  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 05:08:03.480  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:03.482  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,08-29 05:08:03.486  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 05:08:03.487  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:03.489  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:03.492  5806  5806 D HeadsetService: Received stop request...Stopping profile...
,08-29 05:08:03.493  3205  3205 D BluetoothPbap: Proxy object disconnected
,08-29 05:08:03.493  3205  3205 D PbapServerProfile: Bluetooth service disconnected
,08-29 05:08:03.494   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 05:08:03.495  3624  3856 D BluetoothHeadset: Proxy object disconnected
08-29 05:08:03.495  5738  5738 D BluetoothPbap: Proxy object disconnected
08-29 05:08:03.496  5738  5738 D PbapServerProfile: Bluetooth service disconnected
08-29 05:08:03.496  5806  5806 D A2dpService: Received stop request...Stopping profile...
08-29 05:08:03.496   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 05:08:03.496  5806  5847 D A2dpStateMachine: Exit Disconnected: -1
08-29 05:08:03.497  3205  3216 D BluetoothHeadset: Proxy object disconnected
08-29 05:08:03.497  3205  3205 D HeadsetProfile: Bluetooth service disconnected
,08-29 05:08:03.498  5738  5748 D BluetoothHeadset: Proxy object disconnected
08-29 05:08:03.498   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 05:08:03.499  5738  5738 D HeadsetProfile: Bluetooth service disconnected
08-29 05:08:03.500  3205  3205 D BluetoothA2dp: Proxy object disconnected
08-29 05:08:03.500   929   929 D BluetoothA2dp: Proxy object disconnected
08-29 05:08:03.500  5738  5738 D BluetoothA2dp: Proxy object disconnected
08-29 05:08:03.502  5806  5806 D HidService: Received stop request...Stopping profile...
08-29 05:08:03.502  5806  5806 D HidService: Stopping Bluetooth HidService
,08-29 05:08:03.505  3205  3205 D BluetoothInputDevice: Proxy object disconnected
,08-29 05:08:03.505  5738  5738 D BluetoothInputDevice: Proxy object disconnected
,08-29 05:08:03.505  3205  3205 D HidProfile: Bluetooth service disconnected
08-29 05:08:03.505  5738  5738 D HidProfile: Bluetooth service disconnected
08-29 05:08:03.506  5806  5806 D HealthService: Received stop request...Stopping profile...
,08-29 05:08:03.508  5806  5806 V BluetoothAdapterState: isTurningOff()=true
08-29 05:08:03.508  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.508  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 05:08:03.508  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:03.510  5806  5806 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 05:08:03.510  5806  5806 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 05:08:03.510  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 05:08:03.510  5806  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:08:03.510  5806  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:08:03.510  5806  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:08:03.510  5806  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 05:08:03.510  5806  5806 D PanService: Received stop request...Stopping profile...
08-29 05:08:03.511  5738  5738 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 05:08:03.511  5738  5738 D PanProfile: Bluetooth service disconnected
08-29 05:08:03.512  3205  3205 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 05:08:03.512  3205  3205 D PanProfile: Bluetooth service disconnected
08-29 05:08:03.512  5806  5806 D BluetoothMapService: Received stop request...Stopping profile...
08-29 05:08:03.512  5806  5806 D BluetoothMapService: stop()
08-29 05:08:03.517  5806  5806 D BluetoothMapAppObserver: deinitObservers()
08-29 05:08:03.518  5806  5806 D BluetoothMapAppObserver: removeReceiver()
08-29 05:08:03.519  3205  3205 D BluetoothMap: Proxy object disconnected
08-29 05:08:03.519  3205  3205 D MapProfile: Bluetooth service disconnected
08-29 05:08:03.519  5806  5806 V BluetoothAdapterState: isTurningOff()=true
,08-29 05:08:03.519  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.519  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:03.519  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:03.519  5738  5738 D BluetoothMap: Proxy object disconnected
08-29 05:08:03.519  5738  5738 D MapProfile: Bluetooth service disconnected
,08-29 05:08:03.522  5806  5806 D SapService: Received stop request...Stopping profile...
08-29 05:08:03.522  5806  5806 V SapService: stop()
,08-29 05:08:03.524  5806  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:08:03.524  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 05:08:03.524  5806  5806 V BluetoothAdapterState: isTurningOff()=true
08-29 05:08:03.524  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.524  5806  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:08:03.524  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:03.524  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:03.524  5806  5839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 05:08:03.524  5806  5839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 05:08:03.524  5806  5839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 05:08:03.525  5806  5839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 05:08:03.525  5806  5806 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 05:08:03.525  5806  5806 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 05:08:03.525  5806  5806 V BluetoothAdapterState: isTurningOff()=true
08-29 05:08:03.525  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.525  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:03.525  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:03.525  5806  5806 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 05:08:03.525  5806  5806 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 05:08:03.526  5806  5806 V BluetoothAdapterState: isTurningOff()=true
,08-29 05:08:03.526  5806  5806 V BluetoothAdapterState: isTurningOn()=false
,08-29 05:08:03.526  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:03.526  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:03.526  5806  5806 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 05:08:03.526  5806  5806 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 05:08:03.527  5806  5806 D BluetoothMapService: MAP Service closeService in
08-29 05:08:03.527  5806  5806 V BluetoothAdapterState: isTurningOff()=true
08-29 05:08:03.527  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.527  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:03.527  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 05:08:03.527  5806  5806 D BluetoothMapService: cleanup()
08-29 05:08:03.527  5806  5806 D BluetoothMapService: MAP Service closeService in
08-29 05:08:03.528  5806  5806 V BluetoothAdapterState: isTurningOff()=true
08-29 05:08:03.528  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.528  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:03.528  5806  5806 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:03.528  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 05:08:03.528  5806  5828 D BluetoothAdapterProperties: Setting state to 15
08-29 05:08:03.528  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 05:08:03.529   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:08:03.529  3205  5661 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 05:08:03.529   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 05:08:03.530  3205  3813 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:08:03.530  3205  3217 D BluetoothMap: onBluetoothStateChange: up=false
08-29 05:08:03.530  3205  3216 D BluetoothPan: onBluetoothStateChange on: false
08-29 05:08:03.531  5806  5828 I BluetoothAdapterState: Entering BleOnState
08-29 05:08:03.531   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:08:03.531  5806  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 05:08:03.531  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 05:08:03.531  5806  5832 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 05:08:03.532  3624  3660 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:08:03.536  5738  5748 D BluetoothPan: onBluetoothStateChange on: false
,08-29 05:08:03.545  3205  5661 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 05:08:03.546  3205  3813 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 05:08:03.547  5738  5749 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 05:08:03.547   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:08:03.547  5738  5748 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 05:08:03.548  5738  5749 D BluetoothMap: onBluetoothStateChange: up=false
08-29 05:08:03.548  5738  5748 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 05:08:03.548  5806  5828 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 05:08:03.548  5806  5828 D BluetoothAdapterProperties: Setting state to 16
08-29 05:08:03.549  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 05:08:03.549  5806  5828 D BluetoothAdapterProperties: onBleDisable
08-29 05:08:03.549  5806  5828 I BluetoothAdapterState: Entering PendingCommandState
08-29 05:08:03.550  5806  5829 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 05:08:03.551  5806  5832 D BluetoothAdapterProperties: Scan Mode:20
08-29 05:08:03.552  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:03.552  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 05:08:03.553  5806  5839 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 05:08:03.553  5806  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 05:08:03.554  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:03.558  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,08-29 05:08:03.558  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 05:08:03.558  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:03.561  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:03.766  5806  5832 I bt_hci  : shut_down
,08-29 05:08:03.775  5806  5836 D bt_hwcfg: hw_epilog_process
,08-29 05:08:03.775  5806  5836 I bt_vendor: low_power_mode_cb
,08-29 05:08:03.778  5806  5836 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 05:08:03.778  5806  5836 I bt_vendor: epilog_cb
08-29 05:08:03.778  5806  5836 I bt_hci  : epilog_finished_callback
,08-29 05:08:03.784  5806  5832 I bt_hci_h4: hal_close
,08-29 05:08:03.785  5806  5832 I bt_userial_vendor: device fd = 51 close
,08-29 05:08:03.903  5806  5829 D bt_stack_manager: event_shut_down_stack finished.
,08-29 05:08:03.904  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 05:08:03.909  5806  5828 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 05:08:03.909  5806  5806 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 05:08:03.910  5806  5806 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 05:08:03.910  5806  5806 D BtGatt.GattService: stop()
,08-29 05:08:03.910  5806  5806 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 05:08:03.914  5806  5806 V BluetoothAdapterState: isTurningOff()=false
,08-29 05:08:03.914  5806  5806 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:03.914  5806  5806 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 05:08:03.914  5806  5806 V BluetoothAdapterState: isBleTurningOff()=true
08-29 05:08:03.915  5806  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 05:08:03.916  5806  5828 D BluetoothAdapterProperties: Setting state to 10
,08-29 05:08:03.916  5806  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 05:08:03.917  5806  5828 I BluetoothAdapterState: Entering OffState
08-29 05:08:03.918   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 05:08:03.932  5806  5806 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 05:08:03.934  5806  5806 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 05:08:03.935  5806  5806 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 05:08:03.936  5806  5829 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 05:08:03.939  5806  5829 D bt_stack_manager: event_clean_up_stack finished.
,08-29 05:08:03.942  5806  5806 I art     : System.exit called, status: 0
,08-29 05:08:03.942  5806  5806 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 05:08:03.976   929  3226 I ActivityManager: Process com.android.bluetooth (pid 5806) has died
,08-29 05:08:06.453  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 05:08:06.453  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:08:06.930   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:08:07.931   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:08:08.932   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:08:09.459  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 05:08:09.459  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@821d267 added. We now have 6 listener(s)
,08-29 05:08:09.460  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:09.465  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 05:08:09.466  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@72c2814 added. We now have 7 listener(s)
08-29 05:08:09.466  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:08:09.467  5662  5708 I System.out: IsBluetoothEnabled
,08-29 05:08:09.475  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:09.497   929   946 I ActivityManager: Start proc 5871:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding HeadsetService
,08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding A2dpService
08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding HidService
08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding HealthService
08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding PanService
08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding GattService
08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding BluetoothMapService
08-29 05:08:09.554  5871  5871 D AdapterServiceConfig: Adding SapService
,08-29 05:08:09.563   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e7ab27f:true
,08-29 05:08:09.564  5871  5871 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 05:08:09.567  5871  5871 I bt_bluedroid: init
,08-29 05:08:09.567  5871  5883 I BluetoothAdapterState: Entering OffState
,08-29 05:08:09.569  5871  5884 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 05:08:09.569  5871  5884 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 05:08:09.569  5871  5884 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 05:08:09.569  5871  5884 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 05:08:09.570  5871  5871 I bt_bluedroid: get_profile_interface socket
,08-29 05:08:09.571  5871  5887 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 05:08:09.572  5871  5871 I bt_bluedroid: get_profile_interface sdp
08-29 05:08:09.573  5871  5887 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 05:08:09.574  5871  5881 I bt_bluedroid: config_hci_snoop_log
,08-29 05:08:09.575   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 05:08:09.579  5871  5883 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 05:08:09.579  5871  5883 D BluetoothAdapterProperties: Setting state to 14
08-29 05:08:09.579  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 05:08:09.580  5871  5883 D BluetoothBondStateMachine: make
,08-29 05:08:09.582  5871  5888 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 05:08:09.584  5871  5883 I BluetoothAdapterState: Entering PendingCommandState
,08-29 05:08:09.585  5871  5871 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 05:08:09.587  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:09.588  5871  5871 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 05:08:09.588  5871  5871 D BtGatt.GattService: Received start request. Starting profile...
08-29 05:08:09.588  5871  5871 D BtGatt.GattService: start()
08-29 05:08:09.588  5871  5871 I bt_bluedroid: get_profile_interface gatt
08-29 05:08:09.589  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:09.589  5871  5871 D BtGatt.AdvertiseManager: advertise manager created
,08-29 05:08:09.593  5871  5871 V BluetoothAdapterState: isTurningOff()=false
,08-29 05:08:09.593  5871  5871 V BluetoothAdapterState: isTurningOn()=false
08-29 05:08:09.593  5871  5871 V BluetoothAdapterState: isBleTurningOn()=true
08-29 05:08:09.594  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:09.594  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 05:08:09.594  5871  5883 I bt_bluedroid: enable
08-29 05:08:09.594  5871  5884 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 05:08:09.594  5871  5884 I bt_hci  : start_up
,08-29 05:08:09.599  5871  5884 I bt_vendor: alloc value 0xf3c4704d
08-29 05:08:09.599  5871  5884 I bt_vendor: init
08-29 05:08:09.599  5871  5884 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 05:08:09.599  5871  5884 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 05:08:09.716  5871  5884 D bt_hci  : start_up starting async portion
,08-29 05:08:09.716  5871  5891 I bt_hci  : event_finish_startup
08-29 05:08:09.716  5871  5891 I bt_hci_h4: hal_open
08-29 05:08:09.716  5871  5891 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 05:08:09.705  5892  5892 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 05:08:09.721  5871  5891 I bt_userial_vendor: device fd = 51 open
,08-29 05:08:09.734  5871  5891 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 05:08:09.737  5871  5891 D bt_hwcfg: Chipset BCM4358A3
,08-29 05:08:09.737  5871  5891 D bt_hwcfg: Target name = [BCM4358A3]
08-29 05:08:09.737  5871  5891 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 05:08:09.933   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:08:10.141  5871  5891 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 05:08:10.142  5871  5891 D bt_hwcfg: Settlement delay -- 100 ms
08-29 05:08:10.142  5871  5891 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 05:08:10.276  5871  5891 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 05:08:10.276  5871  5891 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-29 05:08:10.277  5871  5891 I bt_hwcfg: vendor lib fwcfg completed
08-29 05:08:10.277  5871  5891 I bt_vendor: firmware callback
08-29 05:08:10.278  5871  5891 I bt_hci  : firmware_config_callback
,08-29 05:08:10.286  5871  5894 I bt_btu  : btu_task pending for preload complete event
,08-29 05:08:10.286  5871  5894 I bt_btu_task: Bluetooth chip preload is complete
08-29 05:08:10.286  5871  5894 I bt_btu  : btu_task received preload complete event
,08-29 05:08:10.293  5871  5894 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 05:08:10.293  5871  5894 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 05:08:10.293  5871  5894 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 05:08:10.293  5871  5894 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 05:08:10.293  5871  5894 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 05:08:10.294  5871  5894 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 05:08:10.295  5871  5894 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 05:08:10.295  5871  5894 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 05:08:10.375  5871  5894 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bc4c99
,08-29 05:08:10.375  5871  5894 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bc4c99 
,08-29 05:08:10.387  5871  5887 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 05:08:10.388  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 05:08:10.389  5871  5887 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 05:08:10.393  5871  5887 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 05:08:10.396  5871  5887 D BluetoothAdapterProperties: Scan Mode:20
,08-29 05:08:10.396  5871  5887 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 05:08:10.396  5871  5887 D bt_hci  : do_postload posting postload work item
08-29 05:08:10.397  5871  5891 I bt_hci  : event_postload
08-29 05:08:10.397  5871  5891 I bt_vendor: sco_config_cb
,08-29 05:08:10.397  5871  5891 I bt_hci  : sco_config_callback postload finished.
08-29 05:08:10.398  5871  5887 D bt_bte_conf: Device ID record 1 : primary
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   vendorId            = 000f
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   vendorIdSource      = 0001
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   product             = 1200
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   version             = 1436
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   clientExecutableURL = 
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   serviceDescription  = 
08-29 05:08:10.399  5871  5887 D bt_bte_conf:   documentationURL    = 
08-29 05:08:10.399  5871  5887 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 05:08:10.399  5871  5884 D bt_stack_manager: event_start_up_stack finished
08-29 05:08:10.400  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 05:08:10.400  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:10.401  5871  5883 D BluetoothAdapterProperties: Setting state to 15
08-29 05:08:10.401  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 05:08:10.402  5871  5883 I BluetoothAdapterState: Entering BleOnState
,08-29 05:08:10.407  5871  5891 I bt_vendor: low_power_mode_cb
08-29 05:08:10.407  5871  5883 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 05:08:10.407  5871  5883 D BluetoothAdapterProperties: Setting state to 11
08-29 05:08:10.407  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 05:08:10.411  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:10.413  5871  5871 D HeadsetService: Received start request. Starting profile...
08-29 05:08:10.417  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:10.420  5871  5871 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 05:08:10.420  5871  5871 D HeadsetStateMachine: make
,08-29 05:08:10.426  5871  5883 I BluetoothAdapterState: Entering PendingCommandState
,08-29 05:08:10.428  5871  5871 D HeadsetStateMachine: max_hf_connections = 1
,08-29 05:08:10.428  5871  5871 I bt_bluedroid: get_profile_interface handsfree
08-29 05:08:10.429  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 05:08:10.429  5871  5887 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 05:08:10.433  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:10.433  5871  5871 D A2dpService: Received start request. Starting profile...
,08-29 05:08:10.434  5871  5871 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 05:08:10.434  5871  5871 I bt_bluedroid: get_profile_interface avrcp
,08-29 05:08:10.439  5871  5871 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 05:08:10.439  5871  5871 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 05:08:10.439  5871  5871 D A2dpStateMachine: make
08-29 05:08:10.440  5871  5871 I bt_bluedroid: get_profile_interface a2dp
,08-29 05:08:10.441  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 05:08:10.442  5871  5902 D A2dpStateMachine: Enter Disconnected: -2
,08-29 05:08:10.442  5871  5871 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 05:08:10.443  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:10.444  5871  5871 D HidService: Received start request. Starting profile...
08-29 05:08:10.444  5871  5871 I bt_bluedroid: get_profile_interface hidhost
,08-29 05:08:10.444  5871  5871 D HidService: setHidService(): set to: null
08-29 05:08:10.444  5871  5887 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ba62d9
08-29 05:08:10.444  5871  5887 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 05:08:10.445  5871  5871 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 05:08:10.446  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:10.446  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 05:08:10.447  5871  5871 D HealthService: Received start request. Starting profile...
,08-29 05:08:10.448  5871  5871 I bt_bluedroid: get_profile_interface health
,08-29 05:08:10.449  5871  5871 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 05:08:10.450  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:10.450  5871  5871 D PanService: Received start request. Starting profile...
08-29 05:08:10.450  5871  5871 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 05:08:10.450  5871  5871 I bt_bluedroid: get_profile_interface pan
08-29 05:08:10.451  5871  5887 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 05:08:10.453  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
,08-29 05:08:10.453  5871  5871 D BluetoothMapService: Received start request. Starting profile...
08-29 05:08:10.453  5871  5871 D BluetoothMapService: start()
08-29 05:08:10.455  5871  5871 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 05:08:10.456  5871  5871 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 05:08:10.456  5871  5871 D BluetoothMapAppObserver: createReceiver()
,08-29 05:08:10.457  5871  5871 D BluetoothMapAppObserver: initObservers()
,08-29 05:08:10.457  5871  5871 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 05:08:10.463  5871  5871 V SapService: SapBinder()
,08-29 05:08:10.463  5871  5871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:10.464  5871  5871 D SapService: Received start request. Starting profile...
,08-29 05:08:10.464  5871  5871 V SapService: start()
,08-29 05:08:10.466  5871  5871 V BluetoothAdapterState: isTurningOff()=false
,08-29 05:08:10.466  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.466  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:10.466  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:10.466  5871  5871 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:10.467  5871  5900 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOff()=false
,08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:10.467  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.468  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:10.468  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:10.468  5871  5871 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:10.468  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.468  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:10.468  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:10.469  5871  5871 V BluetoothAdapterState: isTurningOff()=false
08-29 05:08:10.469  5871  5871 V BluetoothAdapterState: isTurningOn()=true
08-29 05:08:10.469  5871  5871 V BluetoothAdapterState: isBleTurningOn()=false
08-29 05:08:10.469  5871  5871 V BluetoothAdapterState: isBleTurningOff()=false
08-29 05:08:10.469  5871  5883 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 05:08:10.469  5871  5883 D BluetoothAdapterProperties: ScanMode =  20
08-29 05:08:10.469  5871  5883 D BluetoothAdapterProperties: State =  11
08-29 05:08:10.469  5871  5883 D BluetoothAdapterProperties: Setting state to 12
08-29 05:08:10.470  5871  5883 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 05:08:10.470  5871  5883 I BluetoothAdapterState: Entering OnState
,08-29 05:08:10.470   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:10.470  3205  3216 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 05:08:10.473   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 05:08:10.474  3205  5661 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:10.474  5871  5887 D BluetoothAdapterProperties: Scan Mode:21
08-29 05:08:10.474  5871  5887 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 05:08:10.474   929   929 D BluetoothA2dp: Proxy object connected
,08-29 05:08:10.476  3205  3813 D BluetoothMap: onBluetoothStateChange: up=true
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:10.477  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:08:10.479  3205  3205 D BluetoothMap: Proxy object connected
08-29 05:08:10.479  3205  3216 D BluetoothPan: onBluetoothStateChange on: true
08-29 05:08:10.479  3205  3205 D MapProfile: Bluetooth service connected
08-29 05:08:10.479  3205  3205 D BluetoothMap: getConnectedDevices()
08-29 05:08:10.479  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:08:10.481   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 05:08:10.482  5871  5871 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 05:08:10.482  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 05:08:10.483  5871  5871 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 05:08:10.484  3624  3856 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:10.484  5871  5871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:10.484  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:10.484  5738  5748 D BluetoothPan: onBluetoothStateChange on: true
08-29 05:08:10.486  3205  5661 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 05:08:10.486  5871  5871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 05:08:10.486  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:10.487  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 05:08:10.487  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57b58bd added. We now have 8 listener(s)
08-29 05:08:10.487  5871  5871 D ObexServerSockets: Succeed to create listening sockets 
08-29 05:08:10.487  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:10.487  5871  5871 D ObexServerSockets0: startAccept()
08-29 05:08:10.487  5871  5871 D ObexServerSockets0: prepareForNewConnect()
08-29 05:08:10.487  3205  3813 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 05:08:10.488   929  5075 D WifiService: setWifiEnabled: false pid=5662, uid=10077
08-29 05:08:10.488   929  5075 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 05:08:10.489  5871  5871 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 05:08:10.489  5871  5871 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 05:08:10.489  5738  5749 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 05:08:10.489  3205  3205 D BluetoothA2dp: Proxy object connected
08-29 05:08:10.489  5871  5908 D ObexServerSockets0: Accepting socket connection...
08-29 05:08:10.490  5871  5909 D ObexServerSockets0: Accepting socket connection...
,08-29 05:08:10.491  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 05:08:10.491  5738  5738 D PanProfile: Bluetooth service connected
08-29 05:08:10.491  5738  5738 D BluetoothInputDevice: Proxy object connected
08-29 05:08:10.491  5738  5738 D HidProfile: Bluetooth service connected
08-29 05:08:10.492  3205  3205 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 05:08:10.492  3205  3205 D PanProfile: Bluetooth service connected
08-29 05:08:10.492  3205  3205 D BluetoothInputDevice: Proxy object connected
08-29 05:08:10.492  3205  3205 D HidProfile: Bluetooth service connected
08-29 05:08:10.493   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:10.493  5738  5748 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 05:08:10.493  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:10.494   929  3480 D WifiService: setWifiEnabled: true pid=5662, uid=10077
,08-29 05:08:10.494   929  3480 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 05:08:10.494  5738  5749 D BluetoothMap: onBluetoothStateChange: up=true
08-29 05:08:10.496  5738  5748 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 05:08:10.497   508   922 D SoftapController: Softap fwReload - Ok
08-29 05:08:10.498  5738  5738 D BluetoothA2dp: Proxy object connected
08-29 05:08:10.498   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 05:08:10.499  5871  5871 D BluetoothMapService: onReceive
08-29 05:08:10.499  5871  5871 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 05:08:10.499  5871  5871 D BluetoothMapService: STATE_ON
08-29 05:08:10.500  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:10.500  5738  5738 D BluetoothMap: Proxy object connected
08-29 05:08:10.500  5738  5738 D MapProfile: Bluetooth service connected
08-29 05:08:10.500  5738  5738 D BluetoothMap: getConnectedDevices()
,08-29 05:08:10.500   508   922 D CommandListener: Setting iface cfg
08-29 05:08:10.500   508   922 D CommandListener: Trying to bring down wlan0
08-29 05:08:10.501   508   922 D CommandListener: Clearing all IP addresses on wlan0
08-29 05:08:10.502  5871  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 05:08:10.503  5871  5914 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 05:08:10.503  5871  5914 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 05:08:10.504   929  3049 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 05:08:10.507  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 05:08:10.513  3692  3692 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 05:08:10.514  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,08-29 05:08:10.520  5738  5738 D BluetoothPbap: Proxy object connected
,08-29 05:08:10.520  5738  5738 D PbapServerProfile: Bluetooth service connected
,08-29 05:08:10.525  5871  5871 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 05:08:10.525  5871  5871 D ObexServerSockets0: prepareForNewConnect()
,08-29 05:08:10.529  5871  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 05:08:10.532  3205  3205 D BluetoothPbap: Proxy object connected
08-29 05:08:10.532  3205  3205 D PbapServerProfile: Bluetooth service connected
,08-29 05:08:10.541  5871  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 05:08:10.543  5871  5922 I BtOppRfcommListener: Accept thread started.
,08-29 05:08:10.571   929   929 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.572  3624  3660 D BluetoothHeadset: Proxy object connected
08-29 05:08:10.572   929   929 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.572  3205  3813 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.573  3205  3205 D HeadsetProfile: Bluetooth service connected
08-29 05:08:10.573  5738  5749 D BluetoothHeadset: Proxy object connected
08-29 05:08:10.573   929   929 D BluetoothHeadset: Proxy object connected
08-29 05:08:10.574  5738  5738 D HeadsetProfile: Bluetooth service connected
,08-29 05:08:10.576  3205  3217 D BluetoothHeadset: Proxy object connected
08-29 05:08:10.576  3205  3205 D HeadsetProfile: Bluetooth service connected
,08-29 05:08:10.581   929   946 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.585  3624  3658 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.592   929   946 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.597  5738  5748 D BluetoothHeadset: Proxy object connected
,08-29 05:08:10.597  5738  5738 D HeadsetProfile: Bluetooth service connected
,08-29 05:08:10.934   599   599 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 05:08:11.120   929  3049 D wifi    : set interface wlan0 flags (UP)
,08-29 05:08:11.120   929  3049 I WifiHAL : Initializing wifi
08-29 05:08:11.120   929  3049 I WifiHAL : Creating socket
,08-29 05:08:11.127   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 05:08:11.131   929  3049 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 05:08:11.132   929  3049 D wifi    : Did set static halHandle = 0x7f68274900
,08-29 05:08:11.132   929  3049 D wifi    : halHandle = 0x7f68274900, mVM = 0x7f8468d140, mCls = 0x101292
,08-29 05:08:11.132   929  3049 D wifi    : array field set
,08-29 05:08:11.133   929  3049 I WifiNative-HAL: interface[0] = wlan0
,08-29 05:08:11.135   929  5923 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547208251648
,08-29 05:08:11.135   929  5923 D wifi    : waitForHalEvents called, vm = 0x7f8468d140, obj = 0x101292, env = 0x7f69f7ab40
,08-29 05:08:11.202  5924  5924 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 05:08:11.223  5924  5924 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 05:08:11.235  5924  5924 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 05:08:11.235  5924  5924 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
08-29 05:08:11.236   929  3049 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 05:08:11.245  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 05:08:11.258   929  3049 D WifiConfigStore: Loading config and enabling all networks 
,08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:11.259  5662  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:11.261  5662  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:08:11.265   929  3049 D WifiConfigStore: loaded 0 passpoint configs
,08-29 05:08:11.265   929  3049 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 05:08:11.265   929  3049 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 05:08:11.266   929  3049 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 05:08:11.266   929  3049 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,08-29 05:08:11.266   929  3049 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 05:08:11.269  4317  4317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 05:08:11.269   929  3049 D WifiNative-HAL: Setting external_sim to 1
08-29 05:08:11.269   929  3049 D wifi    : setting dfs flag to true, 0x7f6c7a5140
08-29 05:08:11.270   929  3049 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 05:08:11.270   929  3049 D wifi    : setting scan oui 0x7f6c7a5140
08-29 05:08:11.270   929  3049 D WifiHAL : Sending mac address OUI
,08-29 05:08:11.284   929  3049 E native  : do suspend true
,08-29 05:08:11.290   929  3049 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-29 05:08:11.290   929   929 D RttService: SCAN_AVAILABLE : 3
08-29 05:08:11.290   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 05:08:11.290   929  3158 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 05:08:11.291   508   922 D CommandListener: Setting iface cfg
,08-29 05:08:11.295   929  3048 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '77 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 77 Failed to set address (No such device)'
08-29 05:08:11.295   929  3048 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 05:08:11.302   929  3048 D WifiNative-HAL: p2pGetDeviceAddress
08-29 05:08:11.303   929  3048 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 05:08:11.308   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=193866 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:11.507  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:11.511  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:08:11.519  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 05:08:11.520  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 05:08:11.523  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a52c39a Bundle[{}]
,08-29 05:08:11.524  5662  5708 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 05:08:11.525  5662  5708 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 05:08:11.526  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 05:08:11.527  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 05:08:11.528  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 05:08:11.529  5662  5708 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 05:08:11.535  5662  5708 I System.out: Running OutgoingSocketThread
,08-29 05:08:11.537  5662  5926 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,08-29 05:08:11.538  5662  5926 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37532
,08-29 05:08:11.538  5662  5926 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 05:08:11.939   599   599 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 05:08:12.538  5662  5708 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
08-29 05:08:12.539  5662  5708 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,08-29 05:08:12.545  5662  5708 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,08-29 05:08:12.547  5662  5708 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 05:08:12.547  5662  5708 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,08-29 05:08:12.554  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 05:08:12.554  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc8eb2 added. We now have 2 listener(s)
08-29 05:08:12.556  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.556  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.556  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 05:08:12.556  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.556  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86f2e03 added. We now have 9 listener(s)
08-29 05:08:12.556  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.558  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 05:08:12.563  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:12.568  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:08:12.571  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:12.571  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 05:08:12.572  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.572  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09c3b9 added. We now have 3 listener(s)
08-29 05:08:12.573  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.574  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.574  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.574  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 05:08:12.574  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae0e3fe added. We now have 10 listener(s)
08-29 05:08:12.574  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.574  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:08:12.574  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.575  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.575  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 05:08:12.575  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.575  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.575  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.575  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.575  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bc8eb2 removed from the list
08-29 05:08:12.575  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.575  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86f2e03 removed from the list
,08-29 05:08:12.576  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.576  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:08:12.576  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.577  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.578  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.580  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.580  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 05:08:12.580  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.580  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86f2e03 not in the list
08-29 05:08:12.580  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.580  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:08:12.583  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 05:08:12.583  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.583  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.583  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae0e3fe removed from the list
08-29 05:08:12.583  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.583  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 05:08:12.583  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.583  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.583  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09c3b9 removed from the list
08-29 05:08:12.584  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 05:08:12.584  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@baca75f added. We now have 2 listener(s)
08-29 05:08:12.586  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.586  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.586  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.586  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.586  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc65ac added. We now have 9 listener(s)
08-29 05:08:12.586  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.587  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 05:08:12.591  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:12.595  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:08:12.597  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:12.597  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:08:12.597  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.597  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c63420a added. We now have 3 listener(s)
08-29 05:08:12.598  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.598  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.599  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.599  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 05:08:12.599  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.599  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e5a7b added. We now have 10 listener(s)
08-29 05:08:12.599  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.599  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:08:12.599  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 05:08:12.599  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 05:08:12.599  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:08:12.599  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 05:08:12.600  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.603  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 05:08:12.603  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 05:08:12.606  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 05:08:12.607  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 05:08:12.607  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 05:08:12.610  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 05:08:12.611  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 05:08:12.611  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 05:08:12.611  5662  5708 D BluetoothAdapter: STATE_ON
,08-29 05:08:12.615  5871  5899 D BtGatt.GattService: registerClient() - UUID=5a423a0c-b137-420a-950f-fb7af720b712
,08-29 05:08:12.615  5871  5887 D BtGatt.GattService: onClientRegistered() - UUID=5a423a0c-b137-420a-950f-fb7af720b712, clientIf=5
,08-29 05:08:12.616  5662  5804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 05:08:12.617  5871  5881 D BtGatt.GattService: start scan with filters
,08-29 05:08:12.620  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 05:08:12.620  5871  5890 D BtGatt.ScanManager: handling starting scan
,08-29 05:08:12.620  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 05:08:12.621  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 05:08:12.621  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 05:08:12.623  5871  5890 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3386c8e
08-29 05:08:12.624  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:08:12.624  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 05:08:12.624  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:08:12.625  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 05:08:12.628  5662  5708 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 05:08:12.628  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.628  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 05:08:12.628  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.628  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 05:08:12.628  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 05:08:12.628  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:08:12.628  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:08:12.628  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:08:12.628  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 05:08:12.628  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 05:08:12.629  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:08:12.630  5871  5887 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 05:08:12.630  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.630  5871  5881 D BtGatt.GattService: stopScan() - queue size =1
08-29 05:08:12.631  5871  5890 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 05:08:12.632  5871  5907 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 05:08:12.632  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 05:08:12.632  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 05:08:12.632  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 05:08:12.632  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 05:08:12.633  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 05:08:12.634  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:08:12.634  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 05:08:12.634  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 05:08:12.634  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 05:08:12.635  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.636  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:08:12.636  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:08:12.636  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:08:12.637  5871  5887 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 05:08:12.637  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.638  5871  5890 D BtGatt.ScanManager: Starting BLE batch scan
08-29 05:08:12.638  5871  5890 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 05:08:12.639  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 05:08:12.639  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.639  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:08:12.639  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.639  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.639  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.639  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.639  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@baca75f removed from the list
08-29 05:08:12.639  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.640  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc65ac removed from the list
08-29 05:08:12.640  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:08:12.640  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:08:12.640  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.640  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.641  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.641  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.641  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.642  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5fc65ac not in the list
08-29 05:08:12.642  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.642  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:08:12.644  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 05:08:12.644  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.644  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.644  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e5a7b removed from the list
08-29 05:08:12.644  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.644  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.644  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.644  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.644  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c63420a removed from the list
08-29 05:08:12.645  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.645  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22e2357 added. We now have 2 listener(s)
08-29 05:08:12.647  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 05:08:12.647  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.647  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.647  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.647  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b3be44 added. We now have 9 listener(s)
08-29 05:08:12.647  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:08:12.648  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 05:08:12.649  5871  5887 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 05:08:12.649  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.652  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:12.655  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:08:12.656  5871  5887 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 05:08:12.656  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.657  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 05:08:12.663  5871  5887 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 05:08:12.658  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:08:12.667  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.667  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5120862 added. We now have 3 listener(s)
08-29 05:08:12.667  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.668  5871  5890 D BtGatt.ScanManager: stopping BLe Batch
08-29 05:08:12.668  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.668  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.668  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.668  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.668  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.668  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5079df3 added. We now have 10 listener(s)
08-29 05:08:12.668  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.669  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:08:12.669  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:08:12.669  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 05:08:12.669  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 05:08:12.669  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:08:12.669  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.669  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 05:08:12.673  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 05:08:12.673  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 05:08:12.673  5871  5887 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 05:08:12.673  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.673  5871  5890 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 05:08:12.676  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 05:08:12.677  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 05:08:12.677  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 05:08:12.678  5871  5887 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 05:08:12.678  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.680  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 05:08:12.680  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 05:08:12.680  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 05:08:12.681  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:08:12.687  5871  5882 D BtGatt.GattService: registerClient() - UUID=1742c864-6667-4e60-8bda-ef104cffeb2d
08-29 05:08:12.688  5871  5887 D BtGatt.GattService: onClientRegistered() - UUID=1742c864-6667-4e60-8bda-ef104cffeb2d, clientIf=5
08-29 05:08:12.688  5662  5804 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 05:08:12.688  5871  5881 D BtGatt.GattService: start scan with filters
,08-29 05:08:12.690  5871  5890 D BtGatt.ScanManager: handling starting scan
08-29 05:08:12.691  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 05:08:12.691  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 05:08:12.691  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 05:08:12.691  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 05:08:12.693  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 05:08:12.694  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 05:08:12.694  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 05:08:12.695  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 05:08:12.696  5871  5887 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 05:08:12.696  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.696  5871  5890 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 05:08:12.697  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:08:12.697  5662  5708 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 05:08:12.697  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:08:12.697  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.697  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:08:12.697  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.697  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.697  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 05:08:12.697  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 05:08:12.697  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22e2357 removed from the list
08-29 05:08:12.697  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.697  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b3be44 removed from the list
08-29 05:08:12.697  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:08:12.697  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.698  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.698  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 05:08:12.698  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 05:08:12.698  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 05:08:12.700  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.700  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.700  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.700  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b3be44 not in the list
,08-29 05:08:12.700  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:08:12.700  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:08:12.700  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:08:12.700  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 05:08:12.700  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 05:08:12.701  5871  5887 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 05:08:12.701  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.701  5871  5890 D BtGatt.ScanManager: Starting BLE batch scan
08-29 05:08:12.701  5871  5890 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 05:08:12.701  5662  5708 D BluetoothAdapter: STATE_ON
,08-29 05:08:12.702  5871  5899 D BtGatt.GattService: stopScan() - queue size =1
08-29 05:08:12.703  5871  5907 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 05:08:12.703  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 05:08:12.703  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 05:08:12.703  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 05:08:12.703  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 05:08:12.703  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 05:08:12.704  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:08:12.704  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 05:08:12.704  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 05:08:12.704  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 05:08:12.705  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.705  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.705  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.706  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.706  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 05:08:12.706  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5079df3 removed from the list
08-29 05:08:12.706  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.706  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:08:12.706  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.706  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:08:12.706  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.706  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.706  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5120862 removed from the list
08-29 05:08:12.706  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.706  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4264f added. We now have 2 listener(s)
08-29 05:08:12.708  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.708  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 05:08:12.708  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.708  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.708  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bba91dc added. We now have 9 listener(s)
08-29 05:08:12.708  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.708  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 05:08:12.709  5871  5887 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 05:08:12.710  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.710  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:12.713  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 05:08:12.714  5871  5887 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 05:08:12.715  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.716  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:08:12.716  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:08:12.716  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.716  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45841ba added. We now have 3 listener(s)
08-29 05:08:12.717  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.717  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.717  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.717  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.717  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.718  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d76d86b added. We now have 10 listener(s)
08-29 05:08:12.718  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.718  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:08:12.718  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 05:08:12.718  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 05:08:12.718  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:08:12.718  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 05:08:12.719  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.720  5871  5887 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 05:08:12.720  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.720  5871  5890 D BtGatt.ScanManager: stopping BLe Batch
,08-29 05:08:12.721  5662  5708 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 05:08:12.722  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 05:08:12.725  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 05:08:12.725  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 05:08:12.726  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 05:08:12.726  5871  5887 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 05:08:12.726  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.726  5871  5890 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 05:08:12.730  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 05:08:12.730  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 05:08:12.730  5662  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 05:08:12.730  5871  5887 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 05:08:12.730  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.731  5662  5708 D BluetoothAdapter: STATE_ON
,08-29 05:08:12.733  5871  5882 D BtGatt.GattService: registerClient() - UUID=6a4eba6d-bf4a-4055-9f3f-382cf148f410
08-29 05:08:12.733  5871  5887 D BtGatt.GattService: onClientRegistered() - UUID=6a4eba6d-bf4a-4055-9f3f-382cf148f410, clientIf=5
,08-29 05:08:12.733  5662  5673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 05:08:12.734  5871  5881 D BtGatt.GattService: start scan with filters
08-29 05:08:12.736  5871  5890 D BtGatt.ScanManager: handling starting scan
,08-29 05:08:12.736  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 05:08:12.736  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 05:08:12.736  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 05:08:12.736  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 05:08:12.739  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 05:08:12.739  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 05:08:12.739  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 05:08:12.740  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 05:08:12.740  5871  5887 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 05:08:12.740  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.741  5871  5890 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 05:08:12.745  5871  5887 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 05:08:12.745  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.745  5871  5890 D BtGatt.ScanManager: Starting BLE batch scan
08-29 05:08:12.745  5871  5890 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 05:08:12.746  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:08:12.746  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.746  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:08:12.746  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 05:08:12.746  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.746  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 05:08:12.746  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.746  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4264f removed from the list
08-29 05:08:12.746  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.746  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bba91dc removed from the list
08-29 05:08:12.746  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 05:08:12.746  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.747  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 05:08:12.747  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 05:08:12.747  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.747  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.748  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.748  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.748  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.748  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bba91dc not in the list
08-29 05:08:12.748  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 05:08:12.748  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 05:08:12.748  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 05:08:12.748  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 05:08:12.748  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 05:08:12.749  5662  5708 D BluetoothAdapter: STATE_ON
08-29 05:08:12.750  5871  5881 D BtGatt.GattService: stopScan() - queue size =1
08-29 05:08:12.750  5871  5899 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 05:08:12.750  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 05:08:12.750  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 05:08:12.750  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 05:08:12.750  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 05:08:12.751  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 05:08:12.751  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:08:12.751  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 05:08:12.751  5662  5708 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 05:08:12.752  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 05:08:12.752  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.753  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.753  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.753  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 05:08:12.753  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:08:12.753  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d76d86b removed from the list
08-29 05:08:12.753  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.753  5662  5662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 05:08:12.753  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.753  5662  5662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 05:08:12.753  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.753  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.753  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45841ba removed from the list
08-29 05:08:12.754  5871  5887 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 05:08:12.754  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.754  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.754  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d289047 added. We now have 2 listener(s)
08-29 05:08:12.755  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.755  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.755  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.755  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.755  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4254074 added. We now have 9 listener(s)
08-29 05:08:12.755  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 05:08:12.756  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 05:08:12.758  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 05:08:12.759  5871  5887 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 05:08:12.759  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 05:08:12.760  5662  5708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 05:08:12.762  5662  5708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 05:08:12.763  5662  5708 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 05:08:12.763  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 05:08:12.763  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1514e12 added. We now have 3 listener(s)
08-29 05:08:12.764  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.764  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 05:08:12.764  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 05:08:12.764  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 05:08:12.764  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 05:08:12.764  5871  5887 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 05:08:12.764  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953e9e3 added. We now have 10 listener(s)
08-29 05:08:12.764  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.764  5662  5708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 05:08:12.764  5871  5890 D BtGatt.ScanManager: stopping BLe Batch
08-29 05:08:12.764  5662  5708 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 05:08:12.764  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.764  5662  5708 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 05:08:12.764  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.765  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.765  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 05:08:12.765  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.765  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d289047 removed from the list
08-29 05:08:12.765  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 05:08:12.765  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4254074 removed from the list
08-29 05:08:12.765  5662  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 05:08:12.765  5662  5708 D io.jxcore.node.ConnectivityMonitor: stop
08-29 05:08:12.765  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:08:12.766  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.766  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 05:08:12.767  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 05:08:12.767  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.767  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.767  5662  5708 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4254074 not in the list
08-29 05:08:12.767  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.767  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.768  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 05:08:12.768  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 05:08:12.768  5662  5708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 05:08:12.768  5662  5708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953e9e3 removed from the list
08-29 05:08:12.768  5662  5708 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 05:08:12.768  5662  5708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 05:08:12.768  5662  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 05:08:12.768  5662  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 05:08:12.768  5662  5708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1514e12 removed from the list
08-29 05:08:12.769  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 05:08:12.769  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 05:08:12.769  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 05:08:12.769  5871  5887 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 05:08:12.769  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 05:08:12.769  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 05:08:12.769  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 05:08:12.769  5662  5708 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 05:08:12.769  5871  5890 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 05:08:12.774  5871  5887 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 05:08:12.774  5871  5887 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 05:08:12.774  5662  5928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
08-29 05:08:12.774  5662  5928 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
08-29 05:08:12.774  5662  5928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 05:08:12.776  5662  5929 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
,08-29 05:08:12.776  5662  5929 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
08-29 05:08:12.776  5662  5929 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 05:08:12.778  5662  5708 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 05:08:12.778  5662  5708 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 05:08:12.778  5662  5708 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 05:08:12.778  5662  5708 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 05:08:12.778  5662  5708 D com.test.thalitest.ThaliTestRunner: Total duration: 21538 ms
08-29 05:08:12.780  5662  5708 I jxcore-log: *Native tests were executed*
08-29 05:08:12.780  5662  5708 I jxcore-log: 
08-29 05:08:12.780  5662  5708 I jxcore-log: Total number of executed tests:  80
08-29 05:08:12.780  5662  5708 I jxcore-log: 
08-29 05:08:12.780  5662  5708 I jxcore-log: Number of passed tests:  80
08-29 05:08:12.780  5662  5708 I jxcore-log: 
,08-29 05:08:12.780  5662  5708 I jxcore-log: Number of failed tests:  0
08-29 05:08:12.780  5662  5708 I jxcore-log: 
08-29 05:08:12.780  5662  5708 I jxcore-log: Number of ignored tests:  0
08-29 05:08:12.780  5662  5708 I jxcore-log: 
08-29 05:08:12.780  5662  5708 I jxcore-log: Total duration:  21538
08-29 05:08:12.780  5662  5708 I jxcore-log: 
08-29 05:08:12.781  5662  5708 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 05:08:12.781  5662  5708 I jxcore-log: 
,08-29 05:08:12.784  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 05:08:12.784  5662  5708 I jxcore-log: 
08-29 05:08:12.786  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.786  5662  5708 I jxcore-log: 
08-29 05:08:12.788  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.788  5662  5708 I jxcore-log: 
08-29 05:08:12.788  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.788  5662  5708 I jxcore-log: 
08-29 05:08:12.790  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.790  5662  5708 I jxcore-log: 
08-29 05:08:12.791  5662  5662 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 05:08:12.791  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.791  5662  5708 I jxcore-log: 
08-29 05:08:12.793  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.793  5662  5708 I jxcore-log: 
08-29 05:08:12.795  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.795  5662  5708 I jxcore-log: 
08-29 05:08:12.796  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.796  5662  5708 I jxcore-log: 
08-29 05:08:12.797  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.797  5662  5708 I jxcore-log: 
08-29 05:08:12.798  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 05:08:12.798  5662  5708 I jxcore-log: 
08-29 05:08:12.799  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.799  5662  5708 I jxcore-log: 
,08-29 05:08:12.800  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.800  5662  5708 I jxcore-log: 
08-29 05:08:12.800  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.800  5662  5708 I jxcore-log: 
08-29 05:08:12.801  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.801  5662  5708 I jxcore-log: 
,08-29 05:08:12.802  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.802  5662  5708 I jxcore-log: 
08-29 05:08:12.802  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.802  5662  5708 I jxcore-log: 
,08-29 05:08:12.803  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.803  5662  5708 I jxcore-log: 
08-29 05:08:12.804  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.804  5662  5708 I jxcore-log: 
,08-29 05:08:12.804  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.804  5662  5708 I jxcore-log: 
,08-29 05:08:12.805  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 05:08:12.805  5662  5708 I jxcore-log: 
,08-29 05:08:12.806  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.806  5662  5708 I jxcore-log: 
08-29 05:08:12.806  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.806  5662  5708 I jxcore-log: 
,08-29 05:08:12.807  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.807  5662  5708 I jxcore-log: 
,08-29 05:08:12.808  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.808  5662  5708 I jxcore-log: 
,08-29 05:08:12.808  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.808  5662  5708 I jxcore-log: 
,08-29 05:08:12.809  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.809  5662  5708 I jxcore-log: 
08-29 05:08:12.810  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 05:08:12.810  5662  5708 I jxcore-log: 
,08-29 05:08:13.137  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 05:08:13.141  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 05:08:13.141  5662  5708 I jxcore-log: 
,08-29 05:08:13.205  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 05:08:13.208  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 05:08:13.208  5662  5708 I jxcore-log: 
,08-29 05:08:13.213  5930  5930 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 05:08:13.220  5930  5930 D AndroidRuntime: CheckJNI is OFF
,08-29 05:08:13.248  5930  5930 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 05:08:13.253  5662  5662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 05:08:13.256  5662  5708 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 05:08:13.256  5662  5708 I jxcore-log: 
,08-29 05:08:13.278  5930  5930 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 05:08:13.293  5930  5930 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 05:08:13.299   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 05:08:13.300   929   942 I ActivityManager: Killing 5662:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 05:08:13.379   929  3050 D WifiService: Client connection lost with reason: 4
,08-29 05:08:13.379   929  3631 D GraphicsStats: Buffer count: 2
08-29 05:08:13.379   929  3224 I WindowState: WIN DEATH: Window{6b2a570 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 05:08:13.435   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 05:08:13.435   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 05:08:13.436   929   952 I art     : Starting a blocking GC Explicit
08-29 05:08:13.436   929   942 E ActivityManager: Failure starting process com.test.thalitest
08-29 05:08:13.436   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 05:08:13.436   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:08:13.436   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:08:13.436   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 05:08:13.436   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 05:08:13.437   929   942 I ActivityManager:   Force finishing activity ActivityRecord{8efbdc5 u0 com.test.thalitest/.MainActivity t4}
,08-29 05:08:13.445   929  5075 W ActivityManager: Spurious death for ProcessRecord{f4bdf40 0:com.test.thalitest/u0a77}, curProc for 5662: null
,08-29 05:08:13.510   929   952 I art     : Explicit concurrent mark sweep GC freed 16363(1037KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.508ms total 74.208ms
,08-29 05:08:13.530   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 05:08:13.533  5930  5930 I art     : System.exit called, status: 0
08-29 05:08:13.533  5930  5930 I AndroidRuntime: VM exiting with result code 0.
,08-29 05:08:13.554   929   952 I ActivityManager: Start proc 5940:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-29 05:08:13.554   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 05:08:13.563   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 05:08:13.566  3478  3478 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 05:08:13.568  5871  5871 D BluetoothMapAppObserver: onReceive
08-29 05:08:13.568  5871  5871 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 05:08:13.571   929  3038 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 05:08:13.574  3714  4005 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 05:08:13.595  5468  5953 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 05:08:13.596  3478  5952 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 05:08:13.612  3478  5952 I Decoder : createOrResetDecoder
,08-29 05:08:13.616  3624  3624 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 05:08:13.627   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 05:08:13.642  3692  3692 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-29 05:08:13.642  3692  3692 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 05:08:13.645    27    27 W kworker/1:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 05:08:13.658  3692  3692 I ConfigService: onCreate
,08-29 05:08:13.658  3938  5959 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 05:08:13.659  3938  5959 D AccountUtils: Clearing selected account for com.test.thalitest
,08-29 05:08:13.655    27    27 W kworker/1:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 05:08:13.681  3478  5952 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 05:08:13.685    27    27 W kworker/1:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 05:08:13.723  3938  5959 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 05:08:13.740  5468  5953 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-29 05:08:13.741  5468  5953 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 05:08:13.741  5468  5953 E AndroidRuntime: Process: android.process.acore, PID: 5468
08-29 05:08:13.741  5468  5953 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 05:08:13.741  5468  5953 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 05:08:13.746   929  5964 E DropBoxManagerService: Can't write: system_app_crash
08-29 05:08:13.746   929  5964 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 05:08:13.746   929  5964 E DropBoxManagerService: 	... 5 more
,08-29 05:08:13.747  5468  5953 I Process : Sending signal. PID: 5468 SIG: 9

```
