#### Test 83070177977a8d1_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 07:45:34.566   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:45:35.039  5537  5537 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 07:45:35.047  5537  5537 D AndroidRuntime: CheckJNI is OFF
08-29 07:45:35.071  5537  5537 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 07:45:35.115  5537  5537 I Radio-JNI: register_android_hardware_Radio DONE
08-29 07:45:35.129  5537  5537 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 07:45:35.135   927  3357 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 07:45:35.181   927  3357 I ActivityManager: Start proc 5546:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 07:45:35.186  5537  5537 D AndroidRuntime: Shutting down VM
08-29 07:45:35.286  5546  5546 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 07:45:35.316  5546  5546 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 07:45:35.344  5546  5546 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 6073-6093)
08-29 07:45:35.344  5546  5546 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 07:45:35.367  5546  5546 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c8001e3}
08-29 07:45:35.368  5546  5546 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 07:45:35.368  5546  5546 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 07:45:35.374  5546  5546 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 07:45:35.375  5546  5546 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 07:45:35.413  5546  5546 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 07:45:35.427  5546  5546 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 07:45:35.427  5546  5546 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 07:45:35.427  5546  5546 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 07:45:35.427  5546  5546 I Adreno  : Build Date                       : 10/21/15
08-29 07:45:35.427  5546  5546 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 07:45:35.427  5546  5546 I Adreno  : Local Branch                     : 
08-29 07:45:35.427  5546  5546 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 07:45:35.427  5546  5546 I Adreno  : Remote Branch                    : NONE
08-29 07:45:35.427  5546  5546 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 07:45:35.486   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f52866:true
,08-29 07:45:35.535  5546  5546 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 07:45:35.545  5546  5546 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 07:45:35.566   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:45:35.576  5546  5583 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 07:45:35.587  5546  5570 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 07:45:35.618  5546  5583 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 07:45:35.712   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +484ms (total +557ms)
,08-29 07:45:35.744  5546  5546 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5546
,08-29 07:45:35.837  5546  5546 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 07:45:36.001  5546  5586 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -577763024
,08-29 07:45:36.007  5546  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 07:45:36.007  5546  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 07:45:36.007  5546  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 07:45:36.007  5546  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 07:45:36.007  5546  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 07:45:36.007  5546  5586 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f73991 added. We now have 1 listener(s)
,08-29 07:45:36.011  5546  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 07:45:36.011  5546  5586 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:45:36.012  5546  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:45:36.013  5546  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 07:45:36.017  5546  5586 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce35764 added. We now have 1 listener(s)
08-29 07:45:36.017  5546  5586 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:45:36.021   927  2960 D WifiService: New client listening to asynchronous messages
,08-29 07:45:36.022  5546  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:45:36.022  5546  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 07:45:36.022  5546  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 07:45:36.022  5546  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 07:45:36.022  5546  5586 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 07:45:36.026  5546  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:45:36.026  5546  5586 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 07:45:36.033  5546  5586 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 07:45:36.034  5546  5586 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 07:45:36.034  5546  5586 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 07:45:36.034  5546  5586 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:45:36.035  5546  5586 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 07:45:36.037  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:36.041  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:36.059  5546  5546 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 07:45:36.316  5546  5592 W jxcore-log: Initializing JXcore engine
08-29 07:45:36.317  5546  5592 W jxcore-log: JXcore engine is ready
,08-29 07:45:36.335  5592  5592 W Thread-61: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11998 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 07:45:36.335  5592  5592 W Thread-61: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[6317]" dev="sockfs" ino=6317 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 07:45:36.335  5592  5592 W Thread-61: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1082 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 07:45:36.335  5592  5592 W Thread-61: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[33854]" dev="sockfs" ino=33854 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 07:45:36.351  5546  5592 W jxcore-log: Starting JXcore engine
,08-29 07:45:36.401  5546  5592 W jxcore-log: Platform android,
08-29 07:45:36.401  5546  5592 W jxcore-log: 
08-29 07:45:36.401  5546  5592 W jxcore-log: Process ARCH arm
08-29 07:45:36.401  5546  5592 W jxcore-log: 
,08-29 07:45:36.497  5546  5592 I jxcore-log: JXcore Cordova bridge is ready!
08-29 07:45:36.497  5546  5592 I jxcore-log: 
,08-29 07:45:36.497  5546  5592 W jxcore-log: JXcore engine is started
,08-29 07:45:36.504  5546  5586 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 07:45:36.506  5546  5546 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 07:45:36.567   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:45:37.568   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:45:37.791   927  5213 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168540, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 07:45:38.569   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:45:39.569   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 07:45:40.791   927  5213 D NetlinkSocketObserver: NeighborEvent{elapsedMs=171540, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,08-29 07:45:40.791   927  5213 W NetlinkSocketObserver: ALERT: NeighborEvent{elapsedMs=171540, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,08-29 07:45:40.792   927  5213 W IpReachabilityMonitor: FAILURE: LOST_PROVISIONING, NeighborEvent{elapsedMs=171540, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
08-29 07:45:40.795   927  2957 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 07:45:40.803  3590  3590 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 07:45:40.811   927  2957 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 07:45:40.811   927  2957 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{5}, ntable=[]
,08-29 07:45:40.812   927  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:45:40.812   927  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 07:45:40.826   927  2957 E native  : do suspend true
,08-29 07:45:40.836  3590  3590 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,08-29 07:45:40.843   927  5214 D DhcpClient: Clearing IP address
08-29 07:45:40.843   505   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:45:40.847   505   920 D CommandListener: Setting iface cfg
,08-29 07:45:40.862  3563  5275 V NativeCrypto: Read error: ssl=0x7f7c849280: I/O error during system call, Connection timed out
,08-29 07:45:40.865  3563  5275 V NativeCrypto: SSL shutdown failed: ssl=0x7f7c849280: I/O error during system call, Broken pipe
,08-29 07:45:40.866   927  5215 D DhcpClient: Receive thread stopped
,08-29 07:45:40.867   927  4495 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 07:45:40.868   927  5212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 07:45:40.870   927  5212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 07:45:40.876   927  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 07:45:40.876   927  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 07:45:40.877   927  2957 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 07:45:40.877   927  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:45:40.878   531   531 E Parcel  : Reading a NULL string not supported here.
08-29 07:45:40.878   927  2957 E native  : do suspend true
,08-29 07:45:40.884   927  2961 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 07:45:40.886  3452  3593 W QCNEJ   : |CORE| network lost: 100
,08-29 07:45:40.887  3452  3593 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 07:45:40.908   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 07:45:40.927   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 07:45:40.928   927  2961 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 07:45:40.928   505   920 D CommandListener: Clearing all IP addresses on wlan0
08-29 07:45:40.928   927  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 07:45:40.930   505   920 D TetherController: Setting IP forward enable = 0
,08-29 07:45:40.930   927   944 D Tethering: MasterInitialState.processMessage what=3
08-29 07:45:40.934  5116  5116 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4627acc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:40.939  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:40.939  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 07:45:40.939  3843  3843 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 07:45:40.941  4795  4813 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 07:45:40.941   927  2957 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 07:45:40.942  4795  4813 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 07:45:40.942  4795  4813 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 07:45:40.942  4795  4813 E SarControlService: no key has been found,reset the power
08-29 07:45:40.942  4795  4831 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 07:45:40.942  4795  4831 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,08-29 07:45:40.942  4795  4831 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,08-29 07:45:40.943  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,08-29 07:45:40.943  4820  4820 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 07:45:40.944  4795  4831 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 07:45:40.944  4795  4831 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 07:45:40.944  4795  4831 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 07:45:40.946  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 07:45:40.946  4820  4820 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 07:45:40.949  4820  4834 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3bec612 HexData = [00000000ea03000000000000ffffffff]
08-29 07:45:40.949  4820  4834 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 07:45:40.949  4820  4834 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 07:45:40.951  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 07:45:40.951  4795  4806 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 07:45:40.952  3843  3843 D SystemUpdateService: onCreate
08-29 07:45:40.955  4820  4834 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@3bec612 HexData = [00000000eb03000000000000ffffffff]
08-29 07:45:40.955  4820  4834 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 07:45:40.956  4820  4834 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,08-29 07:45:40.956  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 07:45:40.957  4795  4805 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 07:45:40.959  3843  3843 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 07:45:40.966  3843  5609 I SystemUpdateService: active receiver: enabled
08-29 07:45:40.968  3843  3843 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 07:45:40.974  3843  5244 I iu.UploadsManager: num queued entries: 0
08-29 07:45:40.975  3843  5244 I iu.UploadsManager: num updated entries: 0
08-29 07:45:40.976  3843  5244 I iu.SyncManager: NEXT; no task
,08-29 07:45:40.978  3843  3843 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 07:45:40.980  3843  3843 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 07:45:40.984  3843  5609 I SystemUpdateService: showing system update notification
,08-29 07:45:40.985   505   920 E Netd    : netlink response contains error (No such file or directory)
08-29 07:45:40.986   927  2961 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 07:45:40.986   927  2961 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 07:45:40.986   505   920 D TetherController: Setting IP forward enable = 0
,08-29 07:45:40.991   927  3503 I ActivityManager: Start proc 5614:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 07:45:41.026  3843  5609 V SystemUpdateService: retry (wakeup: false) in 3599961 ms
,08-29 07:45:41.029  5614  5614 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 07:45:41.032  3843  3843 D SystemUpdateService: onDestroy
,08-29 07:45:41.035  5614  5614 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 07:45:41.040  5614  5614 D SprintDMHelper: simOperator: 
,08-29 07:45:41.040  5614  5614 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 07:45:41.052   927   938 I ActivityManager: Start proc 5627:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 07:45:41.053   927   938 I ActivityManager: Killing 4896:com.google.android.deskclock/u0a66 (adj 15): empty #17
,08-29 07:45:41.196  4757  5641 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 07:45:41.210   927  3532 I ActivityManager: Killing 5297:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-29 07:45:42.963  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 07:45:42.963  5546  5592 I jxcore-log: 
,08-29 07:45:42.965  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 07:45:42.965  5546  5592 I jxcore-log: 
,08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:42.968  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:45:42.969  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:42.971  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 07:45:42.971  5546  5592 I jxcore-log: 
,08-29 07:45:42.972  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 07:45:42.972  5546  5592 I jxcore-log: 
,08-29 07:45:43.329  5546  5592 D executeNativeTests: Running unit tests
,08-29 07:45:43.368  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:45:43.368  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 added. We now have 2 listener(s)
,08-29 07:45:43.369  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:45:43.369  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:45:43.369  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:45:43.369  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:45:43.369  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 added. We now have 2 listener(s)
,08-29 07:45:43.369  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:45:43.370  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:45:43.372  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.374  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.375  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:43.375  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:45:43.377  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 07:45:43.377  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:45:43.377  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:45:43.378  5546  5592 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 07:45:43.378  5546  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 07:45:43.379  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 07:45:43.379  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:45:43.379  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:45:43.379  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:45:43.379  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.379  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:45:43.379  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.380  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.380  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.380  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:45:43.380  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:45:43.380  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 removed from the list
08-29 07:45:43.380  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:45:43.380  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 removed from the list
08-29 07:45:43.383  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.383  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.383  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.383  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.384  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.384  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 07:45:43.384  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.384  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.384  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
,08-29 07:45:43.385  5546  5592 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 07:45:43.386  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.386  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.386  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 07:45:43.386  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.386  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.386  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.386  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.386  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.386  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
,08-29 07:45:43.386  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.386  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.386  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.386  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.386  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.387  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.387  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.387  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.387  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
,08-29 07:45:43.389  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 07:45:43.390  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 07:45:43.391  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.391  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.391  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.391  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.391  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.391  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.391  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.391  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.391  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.391  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.391  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.391  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.391  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.391  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.392  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.392  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.392  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.392  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.393  5546  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:45:43.394  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.396  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.398  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:43.398  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:45:43.399  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:45:43.399  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:45:43.399  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:45:43.399  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.399  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:45:43.401  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.401  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.402  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:45:43.402  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:45:43.405  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:45:43.405  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:45:43.406  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:45:43.407  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 07:45:43.408  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 07:45:43.408  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:45:43.408  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:45:43.408  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:45:43.409  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:45:43.411  4316  4333 D BtGatt.GattService: registerClient() - UUID=1beebf4f-6aea-4092-a7fc-28e63f44f4a7
08-29 07:45:43.411  4316  4395 D BtGatt.GattService: onClientRegistered() - UUID=1beebf4f-6aea-4092-a7fc-28e63f44f4a7, clientIf=5
08-29 07:45:43.412  5546  5556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:45:43.413  4316  4334 D BtGatt.GattService: start scan with filters
08-29 07:45:43.416  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:45:43.416  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:45:43.416  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:45:43.416  4316  4398 D BtGatt.ScanManager: handling starting scan
08-29 07:45:43.417  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:45:43.418  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:45:43.418  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:45:43.418  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:45:43.418  4316  4398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:45:43.418  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:45:43.419  5546  5592 I io.jxcore.node.ConnectionHelper: start: OK
08-29 07:45:43.421  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.421  5546  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:45:43.421  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.421  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:45:43.421  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.421  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:45:43.421  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:45:43.421  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:45:43.421  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:45:43.421  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:45:43.421  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:45:43.421  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:45:43.422  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:45:43.422  4316  4333 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:45:43.422  4316  4334 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:45:43.422  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:45:43.423  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:45:43.423  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:45:43.423  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:45:43.423  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:45:43.423  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.423  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:45:43.423  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:45:43.423  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:45:43.424  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:45:43.425  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.425  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.425  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:45:43.425  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.425  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.425  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.425  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.425  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.425  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.425  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.425  4316  4395 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:45:43.425  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.425  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.425  5546  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:45:43.426  4316  4398 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:45:43.426  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.429  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.430  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:43.430  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:45:43.430  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:45:43.430  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:45:43.430  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:45:43.430  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.430  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:45:43.430  4316  4395 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:45:43.431  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.431  4316  4398 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:45:43.431  4316  4398 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:45:43.432  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.436  4316  4395 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:45:43.436  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.436  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:45:43.436  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:45:43.436  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.437  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:45:43.438  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:45:43.438  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 07:45:43.439  4316  4395 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:45:43.439  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.441  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:45:43.441  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:45:43.441  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:45:43.441  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:45:43.443  4316  4333 D BtGatt.GattService: registerClient() - UUID=0aa35aa9-d452-470d-97b0-bd85fb5469a4
08-29 07:45:43.444  4316  4395 D BtGatt.GattService: onClientRegistered() - UUID=0aa35aa9-d452-470d-97b0-bd85fb5469a4, clientIf=5
08-29 07:45:43.444  5546  5556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:45:43.444  4316  4334 D BtGatt.GattService: start scan with filters
08-29 07:45:43.445  4316  4395 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:45:43.445  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.445  4316  4398 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:45:43.447  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:45:43.447  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:45:43.447  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:45:43.447  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:45:43.448  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:45:43.448  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:45:43.448  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:45:43.448  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:45:43.449  4316  4395 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:45:43.449  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.450  4316  4398 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:45:43.450  5546  5592 I io.jxcore.node.ConnectionHelper: start: OK
08-29 07:45:43.452  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.452  5546  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:45:43.452  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.452  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:45:43.452  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.452  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:45:43.452  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:45:43.452  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:45:43.452  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:45:43.452  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:45:43.452  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:45:43.452  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:45:43.453  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:45:43.453  4316  4538 D BtGatt.GattService: stopScan() - queue size =0
08-29 07:45:43.453  4316  4333 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:45:43.453  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:45:43.453  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:45:43.454  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:45:43.454  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:45:43.454  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:45:43.454  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.454  4316  4395 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:45:43.454  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:45:43.454  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:45:43.454  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.454  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:45:43.455  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:45:43.455  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.455  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.455  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.455  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:45:43.455  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.455  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.455  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.455  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.455  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.455  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.455  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.456  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.456  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.456  4316  4398 D BtGatt.ScanManager: handling starting scan
08-29 07:45:43.456  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.456  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.456  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.456  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.457  5546  5592 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 07:45:43.457  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.459  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.460  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:43.460  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:45:43.460  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:45:43.460  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:45:43.460  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:45:43.461  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.461  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:45:43.461  4316  4395 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:45:43.461  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.461  4316  4398 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:45:43.462  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.463  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.464  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:45:43.465  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:45:43.465  4316  4395 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:45:43.465  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.465  4316  4398 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:45:43.465  4316  4398 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:45:43.467  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:45:43.468  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:45:43.468  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:45:43.470  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:45:43.470  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:45:43.470  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:45:43.471  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:45:43.472  4316  4538 D BtGatt.GattService: registerClient() - UUID=eac10f2c-3310-43ce-9003-610a42260d43
08-29 07:45:43.473  4316  4395 D BtGatt.GattService: onClientRegistered() - UUID=eac10f2c-3310-43ce-9003-610a42260d43, clientIf=5
08-29 07:45:43.473  5546  5557 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:45:43.473  4316  4333 D BtGatt.GattService: start scan with filters
08-29 07:45:43.474  4316  4395 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:45:43.474  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.476  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:45:43.476  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:45:43.476  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:45:43.476  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:45:43.477  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:45:43.477  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:45:43.478  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:45:43.478  4316  4395 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:45:43.478  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.478  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:45:43.480  5546  5592 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 07:45:43.480  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.480  5546  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:45:43.480  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.480  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:45:43.480  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.480  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:45:43.481  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:45:43.481  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:45:43.481  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 07:45:43.481  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:45:43.481  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:45:43.481  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:45:43.481  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:45:43.481  4316  4333 D BtGatt.GattService: stopScan() - queue size =0
08-29 07:45:43.482  4316  4527 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:45:43.482  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:45:43.482  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:45:43.482  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 07:45:43.482  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:45:43.482  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:45:43.483  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.483  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:45:43.483  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:45:43.483  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:45:43.483  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:45:43.484  4316  4395 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 07:45:43.484  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.484  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.484  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.484  4316  4398 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:45:43.484  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.484  5546  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:45:43.484  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.484  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.484  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 07:45:43.484  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.484  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.484  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:45:43.484  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.484  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.484  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.484  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.484  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.486  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.486  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.486  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.487  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.487  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.487  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.487  5546  5592 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 07:45:43.487  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.487  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.487  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.487  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.487  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.487  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.488  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.488  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.488  4316  4395 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:45:43.488  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.488  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.488  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.488  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.488  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.488  4316  4398 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:45:43.488  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:45:43.488  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.488  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.488  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.488  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.488  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.489  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 07:45:43.489  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.489  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.489  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.489  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 07:45:43.489  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.489  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.489  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.489  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.489  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.489  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.489  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.489  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.489  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.490  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.490  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.490  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.490  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.490  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.490  5546  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 07:45:43.490  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.491  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.491  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.491  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.491  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.491  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.491  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.491  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.491  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.491  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.491  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.491  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.491  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.491  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.492  4316  4395 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 07:45:43.492  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.492  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.492  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.492  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.492  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.493  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 07:45:43.493  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.493  4316  4398 D BtGatt.ScanManager: handling starting scan
,08-29 07:45:43.493  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.493  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.493  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.493  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.493  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.493  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.493  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:45:43.493  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.493  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.493  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.494  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.494  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.494  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.497  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 07:45:43.497  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.497  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.497  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.497  4316  4395 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:45:43.497  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.497  4316  4398 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 07:45:43.497  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:45:43.498  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:45:43.498  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:45:43.498  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:45:43.498  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 07:45:43.498  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 07:45:43.498  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.498  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.498  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.498  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.498  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.498  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.498  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
,08-29 07:45:43.498  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.499  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.499  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.499  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.499  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.499  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:45:43.499  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.500  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.500  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.500  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.500  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.500  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:45:43.500  5546  5592 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 07:45:43.500  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 07:45:43.501  4316  4395 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:45:43.501  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.501  4316  4398 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:45:43.501  4316  4398 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:45:43.502  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 07:45:43.502  5546  5592 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 07:45:43.503  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 07:45:43.504  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 07:45:43.504  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 07:45:43.505  5546  5592 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:45:43.505  5546  5592 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 07:45:43.505  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 07:45:43.505  5546  5592 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:45:43.505  5546  5592 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 07:45:43.505  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 07:45:43.505  5546  5592 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 07:45:43.505  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 07:45:43.508  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 07:45:43.508  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 07:45:43.508  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 07:45:43.509  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 07:45:43.509  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 07:45:43.509  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 07:45:43.509  5546  5592 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 07:45:43.509  5546  5592 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 07:45:43.509  5546  5643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,08-29 07:45:43.510  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:45:43.510  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.510  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.510  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.510  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.510  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.510  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 07:45:43.511  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
,08-29 07:45:43.511  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.511  5546  5643 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:45:43.511  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.511  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.511  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.511  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.511  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.511  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.512  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.512  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.512  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:45:43.512  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.512  5546  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
08-29 07:45:43.512  5546  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
08-29 07:45:43.512  5546  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
08-29 07:45:43.512  5546  5592 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 07:45:43.512  5546  5643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
08-29 07:45:43.513  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.513  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.513  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.513  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 07:45:43.513  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.513  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.513  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.513  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.513  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.513  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.513  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.513  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.513  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.513  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.514  4316  4395 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:45:43.514  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.514  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.514  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.514  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.514  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.514  5546  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 07:45:43.514  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.515  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.515  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.515  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 07:45:43.515  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.515  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.515  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.515  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.515  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.515  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.515  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.515  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.515  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.515  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.516  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.516  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.516  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.516  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.516  5546  5592 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 07:45:43.516  5546  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 07:45:43.516  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:45:43.516  5546  5592 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 07:45:43.516  5546  5592 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 07:45:43.516  5546  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 07:45:43.516  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:45:43.517  5546  5592 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-29 07:45:43.517  5546  5592 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 07:45:43.517  5546  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 07:45:43.517  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 07:45:43.517  5546  5592 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 07:45:43.517  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.517  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.517  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.517  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.517  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.517  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.517  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
,08-29 07:45:43.517  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.517  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.517  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.517  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.517  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.517  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.517  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.518  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.518  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 07:45:43.518  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.518  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.518  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.519  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.519  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.519  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.519  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.519  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.519  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.519  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.519  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.519  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.519  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.519  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 07:45:43.519  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.519  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.519  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.519  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.519  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.519  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.519  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.520  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.520  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.520  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.520  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.520  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.520  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.520  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.520  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.520  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.520  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.521  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.521  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.521  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.521  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.521  5546  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 07:45:43.522  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.522  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 07:45:43.523  4316  4395 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:45:43.523  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:45:43.523  5546  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 07:45:43.523  5546  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 07:45:43.523  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-29 07:45:43.523  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 07:45:43.523  5546  5546 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 07:45:43.523  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.524  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 07:45:43.524  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 07:45:43.524  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 07:45:43.524  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.524  5546  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 07:45:43.524  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.524  5546  5546 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 07:45:43.524  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.524  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:45:43.524  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:45:43.524  5546  5645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:45:43.524  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:45:43.524  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.524  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:43.526  5546  5645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 07:45:43.526  5546  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 07:45:43.526  5546  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 07:45:43.528  4316  4395 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:45:43.528  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.528  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.528  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
,08-29 07:45:43.528  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.528  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.528  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:45:43.528  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.528  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.528  5546  5546 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 07:45:43.528  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.528  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:45:43.528  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.528  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.528  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.528  4316  4398 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:45:43.528  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.528  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.528  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.528  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:45:43.528  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.528  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.529  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.529  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.529  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.529  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.529  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.530  5546  5592 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 07:45:43.530  5546  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 07:45:43.530  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 07:45:43.531  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 07:45:43.531  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.531  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:45:43.531  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.531  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.531  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.531  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.531  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.531  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.531  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.531  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.531  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.531  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.531  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.531  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.532  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.532  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.532  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.532  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.532  4316  4395 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:45:43.532  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.532  4316  4398 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:45:43.534  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.534  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.534  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.534  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.534  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.534  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.534  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.535  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.535  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.535  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.535  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.535  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.535  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.535  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.535  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.535  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.535  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.536  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.536  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:45:43.536  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:45:43.536  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:45:43.536  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:45:43.536  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.536  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.536  5546  5592 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c70a21 not in the list
08-29 07:45:43.536  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.536  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@,e5b8e46 not in the list
08-29 07:45:43.536  4316  4395 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:45:43.536  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:45:43.536  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.536  4316  4395 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:45:43.536  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.536  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:45:43.537  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:45:43.537  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:45:43.537  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:45:43.537  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:45:43.537  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5b8e46 not in the list
08-29 07:45:43.538  5546  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 07:45:43.538  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:45:43.538  5546  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 07:45:43.538  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 07:45:43.538  5546  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 07:45:43.538  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 07:45:43.539  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 07:45:43.539  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 07:45:43.539  5546  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 07:45:43.539  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 07:45:43.539  5546  5592 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 07:45:43.539  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 07:45:43.539  5546  5592 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 07:45:43.540  5546  5592 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 07:45:43.541  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:45:43.541  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f88bb8 added. We now have 2 listener(s)
08-29 07:45:43.541  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:45:43.542  5546  5592 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 07:45:43.542   927  3357 D WifiService: setWifiEnabled: true pid=5546, uid=10077
08-29 07:45:43.542   927  3357 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:45:43.543  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:45:43.543  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b5bd91 added. We now have 3 listener(s)
08-29 07:45:43.543  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:45:43.546  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:45:43.546  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a4a14f6 added. We now have 4 listener(s)
08-29 07:45:43.546  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:45:43.547  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:45:43.547  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3210f7 added. We now have 5 listener(s)
08-29 07:45:43.547  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:45:43.548   927  4495 D WifiService: setWifiEnabled: false pid=5546, uid=10077
08-29 07:45:43.548   927  4495 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:45:43.552  4316  4391 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 07:45:43.552  4316  4391 D BluetoothAdapterProperties: Setting state to 13
08-29 07:45:43.552  4316  4391 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 07:45:43.552  4316  4391 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 07:45:43.553  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:45:43.553  4316  4391 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:45:43.554  4316  4316 D BluetoothMapService: onReceive
08-29 07:45:43.554  4316  4316 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:45:43.554  4316  4316 D BluetoothMapService: STATE_TURNING_OFF
08-29 07:45:43.554  4316  4316 D BluetoothMapService: MAP Service closeService in
08-29 07:45:43.554  4316  4316 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 07:45:43.554  4316  4316 D ObexServerSockets0: shutdown(block = true)
08-29 07:45:43.554  4316  4316 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:45:43.555  4316  4316 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:45:43.555  4316  4553 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 07:45:43.555  4316  4520 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 07:45:43.555  4316  4552 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,08-29 07:45:43.556  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.556  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.557  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:45:43.557  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:43.557  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 07:45:43.558  4316  4316 I BtOppRfcommListener: stopping Accept Thread
,08-29 07:45:43.558  4316  5129 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 07:45:43.558  4316  5129 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 07:45:43.559  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.559  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.560  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.560  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:43.561  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.563  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.564  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.566   927   940 I ActivityManager: Start proc 5648:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 07:45:43.567  4316  4395 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:45:43.567  4316  4391 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 07:45:43.568  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.569   927   927 D RttService: SCAN_AVAILABLE : 1
08-29 07:45:43.570  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.570   927  3011 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:45:43.571  4316  4316 D HeadsetService: Received stop request...Stopping profile...
,08-29 07:45:43.574  4316  4316 D A2dpService: Received stop request...Stopping profile...
08-29 07:45:43.575  4316  4533 D A2dpStateMachine: Exit Disconnected: -1
,08-29 07:45:43.576   927  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 07:45:43.576   927  2957 E native  : do suspend true
08-29 07:45:43.576  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.576  4316  4316 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:43.576  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.576  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:43.577  3109  3109 D BluetoothA2dp: Proxy object disconnected
08-29 07:45:43.577  4316  4316 D HidService: Received stop request...Stopping profile...
08-29 07:45:43.578  4316  4316 D HidService: Stopping Bluetooth HidService
08-29 07:45:43.578  3481  3504 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:43.578   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:43.578   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:43.578   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:43.579  3109  3552 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:43.579   927   927 D BluetoothA2dp: Proxy object disconnected
,08-29 07:45:43.579  3109  3109 D BluetoothInputDevice: Proxy object disconnected
08-29 07:45:43.579  3109  3109 D HidProfile: Bluetooth service disconnected
08-29 07:45:43.579  3109  3109 D HeadsetProfile: Bluetooth service disconnected
08-29 07:45:43.579  4316  4316 D HealthService: Received stop request...Stopping profile...
08-29 07:45:43.582  4316  4316 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 07:45:43.582  4316  4316 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 07:45:43.582  4316  4496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:43.582  4316  4496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:43.582  4316  4496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:43.582  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.582  4316  4316 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:43.582  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.582  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:43.584  4316  4316 D PanService: Received stop request...Stopping profile...
,08-29 07:45:43.585  3109  3109 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:45:43.585  3109  3109 D PanProfile: Bluetooth service disconnected
,08-29 07:45:43.586  4316  4316 D BluetoothMapService: Received stop request...Stopping profile...
08-29 07:45:43.586  4316  4316 D BluetoothMapService: stop()
08-29 07:45:43.587  4316  4395 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 07:45:43.587  4316  4395 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 07:45:43.587  4316  4496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:43.587  4316  4395 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 07:45:43.587  4316  4496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:43.587  4316  4496 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:45:43.587  4316  4496 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:45:43.587  4316  4496 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:45:43.587  4316  4496 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:45:43.588   505   920 D CommandListener: Clearing all IP addresses on wlan0
08-29 07:45:43.588  4316  4316 D BluetoothMapAppObserver: deinitObservers()
08-29 07:45:43.588  4316  4316 D BluetoothMapAppObserver: removeReceiver()
,08-29 07:45:43.589  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.589  3109  3109 D BluetoothMap: Proxy object disconnected
08-29 07:45:43.589  4316  4316 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:43.589  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.589  3109  3109 D MapProfile: Bluetooth service disconnected
08-29 07:45:43.589  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:45:43.589  4316  4316 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 07:45:43.590  4316  4316 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 07:45:43.590  4316  4395 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:45:43.590   927  2957 D DhcpClient: doQuit
,08-29 07:45:43.590   927  2957 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 07:45:43.590  4316  4316 D SapService: Received stop request...Stopping profile...
08-29 07:45:43.590  4316  4316 V SapService: stop()
08-29 07:45:43.590   927  5214 D DhcpClient: onQuitting
08-29 07:45:43.591  3590  3590 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 07:45:43.594  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.594  4316  4316 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:43.594  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.594  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:43.594  4316  4316 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 07:45:43.595  4316  4395 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 07:45:43.595  4316  4316 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 07:45:43.595  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.595  4316  4316 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:43.595  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.595  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:43.595  4316  4316 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 07:45:43.595  4316  4316 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 07:45:43.598  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.598  4316  4316 D BluetoothMapService: MAP Service closeService in
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.598  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.598  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.598  4316  4316 V BluetoothAdapterState: isTurningOn()=false
,08-29 07:45:43.598  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.598  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:43.598  4316  4316 D BluetoothMapService: cleanup()
08-29 07:45:43.598  4316  4316 D BluetoothMapService: MAP Service closeService in
08-29 07:45:43.598  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.599  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:43.599  4316  4316 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:43.599  4316  4316 V BluetoothAdapterState: isTurningOn()=false
,08-29 07:45:43.599  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.599  4316  4316 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:43.599  4316  4391 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 07:45:43.599  4316  4391 D BluetoothAdapterProperties: Setting state to 15
08-29 07:45:43.599  4316  4391 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 07:45:43.600  4316  4391 I BluetoothAdapterState: Entering BleOnState
,08-29 07:45:43.601   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 07:45:43.602  3109  3552 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 07:45:43.602  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:43.602  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:43.603  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:43.603  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:43.605  3481  3511 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:43.605   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:45:43.605   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:43.605  3109  3121 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 07:45:43.606  3109  3677 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:45:43.606   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 07:45:43.606  3109  3122 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:43.607  3109  3552 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:45:43.607  3109  3121 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:45:43.608  4316  4391 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 07:45:43.608  4316  4391 D BluetoothAdapterProperties: Setting state to 16
08-29 07:45:43.608  4316  4391 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 07:45:43.610  4316  4391 D BluetoothAdapterProperties: onBleDisable
08-29 07:45:43.611  4316  4391 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:45:43.611  4316  4392 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 07:45:43.611  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.612  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.612  4316  4496 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 07:45:43.612  4316  4496 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:43.613  4316  4395 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:45:43.614  5648  5648 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 07:45:43.615  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.616  3590  3590 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
08-29 07:45:43.616  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.626  5648  5648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:45:43.632  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:45:43.632   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec3ca68:true
,08-29 07:45:43.644   927  3500 I ActivityManager: Start proc 5660:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 07:45:43.654  3590  3590 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 07:45:43.655  5648  5648 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 07:45:43.657  5648  5648 D BluetoothMap: Create BluetoothMap proxy object
,08-29 07:45:43.666  5648  5648 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 07:45:43.678  5660  5660 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 07:45:43.681  3590  3590 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:45:43.681  5648  5648 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:45:43.684   927  3120 I ActivityManager: Killing 5116:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 07:45:43.783   927  2957 D wifi    : In wifi stop Hal
08-29 07:45:43.783  4757  4757 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:45:43.783   927  2957 D wifi    : halHandle = 0x7f6a26e1a0, mVM = 0x7f8670d140, mCls = 0x100b0e
08-29 07:45:43.783   927  3585 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 07:45:43.783   927  3585 D WifiHAL : Got a signal to exit!!!
08-29 07:45:43.783   927  3585 I WifiHAL : Exit wifi_event_loop
08-29 07:45:43.784   927  2957 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 07:45:43.784   927  2957 E WifiHAL : Event processing terminated
08-29 07:45:43.784   927  2957 D wifi    : In wifi cleaned up handler
08-29 07:45:43.784   927  2957 I WifiHAL : Internal cleanup completed
,08-29 07:45:43.786  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:43.786  3609  3931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:45:43.787  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:43.807   927  3585 D wifi    : set interface wlan0 flags (DOWN)
,08-29 07:45:43.807   927  2957 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 07:45:43.816  4316  4395 I bt_hci  : shut_down
,08-29 07:45:43.818  4316  4399 D bt_hwcfg: hw_epilog_process
,08-29 07:45:43.818  4316  4399 I bt_vendor: low_power_mode_cb
,08-29 07:45:43.821  4316  4399 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 07:45:43.821  4316  4399 I bt_vendor: epilog_cb
08-29 07:45:43.821  4316  4399 I bt_hci  : epilog_finished_callback
,08-29 07:45:43.823  4316  4395 I bt_hci_h4: hal_close
08-29 07:45:43.823  4316  4395 I bt_userial_vendor: device fd = 51 close
,08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.910  5660  5660 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.910  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.911  5660  5660 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 07:45:43.911  5660  5660 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 07:45:43.926   927  3162 I ActivityManager: Start proc 5689:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-29 07:45:43.927   927  3162 I ActivityManager: Killing 4405:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 07:45:43.994  4316  4392 D bt_stack_manager: event_shut_down_stack finished.
08-29 07:45:43.995  4316  4391 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 07:45:43.996  4316  4391 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 07:45:43.996  4316  4316 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 07:45:43.997  4316  4316 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 07:45:43.997  4316  4316 D BtGatt.GattService: stop()
08-29 07:45:43.997  4316  4316 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 07:45:43.998  4316  4316 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:45:43.998  4316  4316 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:43.998  4316  4316 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:43.998  4316  4316 V BluetoothAdapterState: isBleTurningOff()=true
08-29 07:45:43.999  4316  4391 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 07:45:43.999  4316  4391 D BluetoothAdapterProperties: Setting state to 10
08-29 07:45:43.999  4316  4391 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 07:45:43.999  4316  4391 I BluetoothAdapterState: Entering OffState
,08-29 07:45:44.000   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 07:45:44.005  4316  4316 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 07:45:44.005  4316  4316 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 07:45:44.005  4316  4316 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 07:45:44.007  4316  4392 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 07:45:44.008  4316  4392 D bt_stack_manager: event_clean_up_stack finished.
08-29 07:45:44.010   927   944 D Tethering: InitialState.processMessage what=4
,08-29 07:45:44.011  5689  5689 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
08-29 07:45:44.013   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 07:45:44.018  4316  4316 I art     : System.exit called, status: 0
,08-29 07:45:44.019  4316  4316 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 07:45:44.028  5546  5546 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:45:44.065  5689  5689 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 07:45:44.068   927  3507 I ActivityManager: Killing 5408:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 07:45:44.085   927  3160 I ActivityManager: Process com.android.bluetooth (pid 4316) has died
,08-29 07:45:44.089  5648  5648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:45:44.103   927  3532 I ActivityManager: Start proc 5715:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 07:45:44.104  5648  5648 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:45:44.157  5715  5715 D AdapterServiceConfig: Adding HeadsetService
,08-29 07:45:44.157  5715  5715 D AdapterServiceConfig: Adding A2dpService
08-29 07:45:44.157  5715  5715 D AdapterServiceConfig: Adding HidService
08-29 07:45:44.157  5715  5715 D AdapterServiceConfig: Adding HealthService
08-29 07:45:44.157  5715  5715 D AdapterServiceConfig: Adding PanService
08-29 07:45:44.157  5715  5715 D AdapterServiceConfig: Adding GattService
08-29 07:45:44.158  5715  5715 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 07:45:44.158  5715  5715 D AdapterServiceConfig: Adding SapService
08-29 07:45:44.160   927  4495 I ActivityManager: Killing 5321:android.process.acore/u0a2 (adj 15): empty #17
,08-29 07:45:44.244  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:45:44.254  5660  5678 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 07:45:44.266   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a090d62:true
,08-29 07:45:46.558   927   937 D WifiService: setWifiEnabled: true pid=5546, uid=10077
,08-29 07:45:46.559   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:45:46.569   505   920 D SoftapController: Softap fwReload - Ok
,08-29 07:45:46.574   505   920 D CommandListener: Setting iface cfg
,08-29 07:45:46.575   505   920 D CommandListener: Trying to bring down wlan0
,08-29 07:45:46.576   505   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:45:46.581   927  2957 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:45:47.203   927  2957 D wifi    : set interface wlan0 flags (UP)
,08-29 07:45:47.207   927  2957 I WifiHAL : Initializing wifi
08-29 07:45:47.207   927  2957 I WifiHAL : Creating socket
08-29 07:45:47.209   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 07:45:47.217   927  2957 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 07:45:47.217   927  2957 D wifi    : Did set static halHandle = 0x7f6a26e1a0
08-29 07:45:47.217   927  2957 D wifi    : halHandle = 0x7f6a26e1a0, mVM = 0x7f8670d140, mCls = 0x1015da
08-29 07:45:47.217   927  2957 D wifi    : array field set
08-29 07:45:47.218   927  2957 I WifiNative-HAL: interface[0] = wlan0
08-29 07:45:47.219   927  5730 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547241779616
08-29 07:45:47.219   927  5730 D wifi    : waitForHalEvents called, vm = 0x7f8670d140, obj = 0x1015da, env = 0x7f6bb90480
,08-29 07:45:47.282  5731  5731 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 07:45:47.303  5731  5731 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:45:47.314  5731  5731 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:45:47.314  5731  5731 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 07:45:47.320   927  2957 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 07:45:47.328  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:47.332  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:47.339   927  2957 D WifiConfigStore: Loading config and enabling all networks 
,08-29 07:45:47.340  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:47.340  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:47.340  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:45:47.340  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:47.341  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:47.342  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:47.342  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:47.342  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:47.345   927  2957 D WifiConfigStore: loaded 0 passpoint configs
,08-29 07:45:47.345   927  2957 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:45:47.346   927  2957 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 07:45:47.347   927  2957 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 07:45:47.347   927  2957 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,08-29 07:45:47.347   927  2957 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 07:45:47.350  4757  4757 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:45:47.350   927  2957 D WifiNative-HAL: Setting external_sim to 1
08-29 07:45:47.351   927  2957 D wifi    : setting dfs flag to true, 0x7f6f521a40
08-29 07:45:47.352   927  2957 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 07:45:47.352   927  2957 D wifi    : setting scan oui 0x7f6f521a40
08-29 07:45:47.352   927  2957 D WifiHAL : Sending mac address OUI
,08-29 07:45:47.366   927  2957 E native  : do suspend true
,08-29 07:45:47.371   927  2957 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 07:45:47.371   505   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 07:45:47.372   927   927 D RttService: SCAN_AVAILABLE : 3
,08-29 07:45:47.372   927  3011 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:45:47.372   505   920 D CommandListener: Setting iface cfg
,08-29 07:45:47.378   927  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '65 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 65 Failed to set address (No such device)'
,08-29 07:45:47.378   927  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 07:45:47.384   927  2956 D WifiNative-HAL: p2pGetDeviceAddress
08-29 07:45:47.384   927  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 07:45:47.401   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178150 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,08-29 07:45:49.566   927  3357 D WifiService: setWifiEnabled: false pid=5546, uid=10077
,08-29 07:45:49.567   927  3357 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:45:49.587   927   927 D RttService: SCAN_AVAILABLE : 1
,08-29 07:45:49.587   927  3011 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 07:45:49.604   927  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 07:45:49.605   505   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:45:49.609   927  2957 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:45:49.611  5731  5731 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 07:45:49.617  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:49.617  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:49.617  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 07:45:49.617  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:49.622  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:49.622  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:45:49.622  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:49.622  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:49.625  5731  5731 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:45:49.641  5731  5731 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 07:45:49.651  5731  5731 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 07:45:49.755  4757  4757 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:45:49.756   927  2957 D wifi    : In wifi stop Hal
08-29 07:45:49.756   927  2957 D wifi    : halHandle = 0x7f6a26e1a0, mVM = 0x7f8670d140, mCls = 0x1015da
,08-29 07:45:49.756   927  5730 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,08-29 07:45:49.757   927  5730 D WifiHAL : Got a signal to exit!!!
08-29 07:45:49.757   927  5730 I WifiHAL : Exit wifi_event_loop
08-29 07:45:49.759   927  2957 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 07:45:49.759   927  2957 E WifiHAL : Event processing terminated
08-29 07:45:49.760   927  2957 D wifi    : In wifi cleaned up handler
08-29 07:45:49.764  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:49.764   927  2957 I WifiHAL : Internal cleanup completed
08-29 07:45:49.766  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:49.767  3609  3931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:45:49.795   927  5730 D wifi    : set interface wlan0 flags (DOWN)
,08-29 07:45:49.795   927  2957 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 07:45:50.003   927   944 D Tethering: InitialState.processMessage what=4
,08-29 07:45:50.011   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 07:45:50.430   927  3500 I ActivityManager: Start proc 5737:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-29 07:45:50.469  5737  5737 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,08-29 07:45:50.486  5737  5737 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 07:45:50.486  5737  5737 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 07:45:50.486  5737  5737 I GAv4    :   adb logcat -s GAv4
,08-29 07:45:50.500  5737  5737 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 07:45:50.505  5737  5737 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 07:45:50.517  5737  5752 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 07:45:50.530   927  3162 I ActivityManager: Killing 5428:com.google.android.partnersetup/u0a18 (adj 15): empty #17
,08-29 07:45:52.601   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c93ce5e:true
,08-29 07:45:52.602  5715  5715 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 07:45:52.607  5715  5715 I bt_bluedroid: init
,08-29 07:45:52.608  5715  5753 I BluetoothAdapterState: Entering OffState
,08-29 07:45:52.612  5715  5754 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 07:45:52.612  5715  5754 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 07:45:52.612  5715  5754 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 07:45:52.612  5715  5754 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 07:45:52.613  5715  5715 I bt_bluedroid: get_profile_interface socket
,08-29 07:45:52.617  5715  5757 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:45:52.617  5715  5715 I bt_bluedroid: get_profile_interface sdp
,08-29 07:45:52.619  5715  5757 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:45:52.623  5715  5725 I bt_bluedroid: config_hci_snoop_log
08-29 07:45:52.625   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 07:45:52.630  5715  5753 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 07:45:52.631  5715  5753 D BluetoothAdapterProperties: Setting state to 14
,08-29 07:45:52.631  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 07:45:52.633  5715  5753 D BluetoothBondStateMachine: make
,08-29 07:45:52.635  5715  5758 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 07:45:52.639  5715  5753 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:45:52.639  5715  5715 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 07:45:52.643  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:45:52.643  5715  5715 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:45:52.644  5715  5715 D BtGatt.GattService: Received start request. Starting profile...
08-29 07:45:52.644  5715  5715 D BtGatt.GattService: start()
08-29 07:45:52.644  5715  5715 I bt_bluedroid: get_profile_interface gatt
,08-29 07:45:52.645  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:45:52.646  5715  5715 D BtGatt.AdvertiseManager: advertise manager created
,08-29 07:45:52.652  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:45:52.652  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:52.652  5715  5715 V BluetoothAdapterState: isBleTurningOn()=true
08-29 07:45:52.652  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:45:52.653  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 07:45:52.653  5715  5753 I bt_bluedroid: enable
08-29 07:45:52.653  5715  5754 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 07:45:52.654  5715  5754 I bt_hci  : start_up
,08-29 07:45:52.660  5715  5754 I bt_vendor: alloc value 0xf403904d
,08-29 07:45:52.660  5715  5754 I bt_vendor: init
08-29 07:45:52.661  5715  5754 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 07:45:52.661  5715  5754 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 07:45:52.786  5715  5754 D bt_hci  : start_up starting async portion
,08-29 07:45:52.786  5715  5761 I bt_hci  : event_finish_startup
08-29 07:45:52.786  5715  5761 I bt_hci_h4: hal_open
08-29 07:45:52.787  5715  5761 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 07:45:52.789  5715  5761 I bt_userial_vendor: device fd = 51 open
,08-29 07:45:52.775  5762  5762 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:45:52.805  5715  5761 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:45:52.808  5715  5761 D bt_hwcfg: Chipset BCM4358A3
,08-29 07:45:52.808  5715  5761 D bt_hwcfg: Target name = [BCM4358A3]
08-29 07:45:52.808  5715  5761 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 07:45:53.181  5715  5761 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 07:45:53.181  5715  5761 D bt_hwcfg: Settlement delay -- 100 ms
08-29 07:45:53.181  5715  5761 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 07:45:53.314  5715  5761 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:45:53.315  5715  5761 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 07:45:53.316  5715  5761 I bt_hwcfg: vendor lib fwcfg completed
,08-29 07:45:53.316  5715  5761 I bt_vendor: firmware callback
,08-29 07:45:53.316  5715  5761 I bt_hci  : firmware_config_callback
,08-29 07:45:53.326  5715  5764 I bt_btu  : btu_task pending for preload complete event
,08-29 07:45:53.326  5715  5764 I bt_btu_task: Bluetooth chip preload is complete
08-29 07:45:53.326  5715  5764 I bt_btu  : btu_task received preload complete event
,08-29 07:45:53.334  5715  5764 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 07:45:53.335  5715  5764 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 07:45:53.336  5715  5764 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 07:45:53.417  5715  5764 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fb6c99
,08-29 07:45:53.418  5715  5764 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fb6c99 
,08-29 07:45:53.446  5715  5757 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 07:45:53.448  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:45:53.449  5715  5757 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 07:45:53.451  5715  5757 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 07:45:53.453  5715  5757 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:45:53.454  5715  5757 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:45:53.454  5715  5757 D bt_hci  : do_postload posting postload work item
08-29 07:45:53.454  5715  5761 I bt_hci  : event_postload
,08-29 07:45:53.454  5715  5761 I bt_vendor: sco_config_cb
08-29 07:45:53.454  5715  5761 I bt_hci  : sco_config_callback postload finished.
,08-29 07:45:53.459  5715  5757 D bt_bte_conf: Device ID record 1 : primary
08-29 07:45:53.459  5715  5757 D bt_bte_conf:   vendorId            = 000f
,08-29 07:45:53.460  5715  5757 D bt_bte_conf:   vendorIdSource      = 0001
08-29 07:45:53.460  5715  5757 D bt_bte_conf:   product             = 1200
08-29 07:45:53.460  5715  5757 D bt_bte_conf:   version             = 1436
08-29 07:45:53.460  5715  5757 D bt_bte_conf:   clientExecutableURL = 
08-29 07:45:53.460  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:53.460  5715  5757 D bt_bte_conf:   serviceDescription  = 
08-29 07:45:53.460  5715  5757 D bt_bte_conf:   documentationURL    = 
08-29 07:45:53.460  5715  5757 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 07:45:53.461  5715  5754 D bt_stack_manager: event_start_up_stack finished
08-29 07:45:53.463  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 07:45:53.463  5715  5753 D BluetoothAdapterProperties: Setting state to 15
08-29 07:45:53.463  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 07:45:53.463  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:53.465  5715  5753 I BluetoothAdapterState: Entering BleOnState
,08-29 07:45:53.465  5715  5761 I bt_vendor: low_power_mode_cb
,08-29 07:45:53.471  5715  5753 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 07:45:53.471  5715  5753 D BluetoothAdapterProperties: Setting state to 11
08-29 07:45:53.471  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 07:45:53.476  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:45:53.477  5715  5715 D HeadsetService: Received start request. Starting profile...
,08-29 07:45:53.478  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:53.479  5715  5715 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 07:45:53.480  5715  5715 D HeadsetStateMachine: make
08-29 07:45:53.480  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:45:53.488  5715  5753 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:45:53.489  5715  5715 D HeadsetStateMachine: max_hf_connections = 1
,08-29 07:45:53.489  5715  5715 I bt_bluedroid: get_profile_interface handsfree
08-29 07:45:53.489  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 07:45:53.489  5715  5757 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 07:45:53.493  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:45:53.493  5715  5715 D A2dpService: Received start request. Starting profile...
,08-29 07:45:53.494  5715  5715 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 07:45:53.494  5715  5715 I bt_bluedroid: get_profile_interface avrcp
,08-29 07:45:53.500  5715  5715 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 07:45:53.500  5715  5715 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 07:45:53.500  5715  5715 D A2dpStateMachine: make
08-29 07:45:53.501  5715  5715 I bt_bluedroid: get_profile_interface a2dp
,08-29 07:45:53.502  5715  5772 D A2dpStateMachine: Enter Disconnected: -2
,08-29 07:45:53.503  5715  5715 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 07:45:53.503  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:45:53.505  5648  5648 D BluetoothInputDevice: Proxy object connected
,08-29 07:45:53.505  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 07:45:53.505  5648  5648 D HidProfile: Bluetooth service connected
08-29 07:45:53.506  5715  5715 D HidService: Received start request. Starting profile...
08-29 07:45:53.506  5715  5715 I bt_bluedroid: get_profile_interface hidhost
08-29 07:45:53.506  5715  5715 D HidService: setHidService(): set to: null
08-29 07:45:53.506  5715  5757 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f982d9
08-29 07:45:53.507  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 07:45:53.507  5715  5715 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 07:45:53.507  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:45:53.508  5715  5715 D HealthService: Received start request. Starting profile...
08-29 07:45:53.509  5715  5715 I bt_bluedroid: get_profile_interface health
,08-29 07:45:53.510  5715  5715 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 07:45:53.510  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:45:53.512  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:45:53.513  5648  5648 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 07:45:53.513  5648  5648 D PanProfile: Bluetooth service connected
08-29 07:45:53.513  5715  5715 D PanService: Received start request. Starting profile...
08-29 07:45:53.514  5715  5715 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 07:45:53.514  5715  5715 I bt_bluedroid: get_profile_interface pan
,08-29 07:45:53.514  5715  5757 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 07:45:53.516  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:45:53.517  5648  5648 D BluetoothMap: Proxy object connected
08-29 07:45:53.517  5715  5715 D BluetoothMapService: Received start request. Starting profile...
08-29 07:45:53.517  5715  5715 D BluetoothMapService: start()
08-29 07:45:53.517  5648  5648 D MapProfile: Bluetooth service connected
08-29 07:45:53.517  5648  5648 D BluetoothMap: getConnectedDevices()
08-29 07:45:53.518  5648  5648 D BluetoothMap: Bluetooth is Not enabled
,08-29 07:45:53.519  5715  5715 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 07:45:53.520  5715  5715 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 07:45:53.520  5715  5715 D BluetoothMapAppObserver: createReceiver()
,08-29 07:45:53.521  5715  5715 D BluetoothMapAppObserver: initObservers()
08-29 07:45:53.521  5715  5715 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 07:45:53.527  5715  5715 V SapService: SapBinder()
08-29 07:45:53.528  5715  5715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:45:53.528  5715  5715 D SapService: Received start request. Starting profile...
,08-29 07:45:53.528  5715  5715 V SapService: start()
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOn()=true
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOn()=true
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:53.530  5715  5770 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOn()=true
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:53.530  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isTurningOn()=true
,08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isTurningOn()=true
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isTurningOn()=true
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.531  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:53.532  5715  5715 V BluetoothAdapterState: isTurningOff()=false
08-29 07:45:53.532  5715  5715 V BluetoothAdapterState: isTurningOn()=true
08-29 07:45:53.532  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:53.532  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:45:53.532  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 07:45:53.533  5715  5753 D BluetoothAdapterProperties: ScanMode =  20
,08-29 07:45:53.533  5715  5753 D BluetoothAdapterProperties: State =  11
08-29 07:45:53.536  5715  5757 D BluetoothAdapterProperties: Scan Mode:21
08-29 07:45:53.536  5715  5753 D BluetoothAdapterProperties: Setting state to 12
08-29 07:45:53.536  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 07:45:53.536  5715  5757 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:45:53.536  5715  5753 I BluetoothAdapterState: Entering OnState
08-29 07:45:53.536  5648  5658 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:45:53.537   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:45:53.537  3109  3677 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:45:53.538  3481  3702 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:45:53.539  5648  5659 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:53.539  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:53.540  5648  5658 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:45:53.540   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:45:53.541  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:53.541   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:45:53.541  5648  5659 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:45:53.542  3109  3122 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:45:53.542   927   927 D BluetoothA2dp: Proxy object connected
08-29 07:45:53.543  3109  3109 D BluetoothMap: Proxy object connected
08-29 07:45:53.543  3109  3677 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:45:53.543  3109  3109 D MapProfile: Bluetooth service connected
,08-29 07:45:53.543  3109  3109 D BluetoothMap: getConnectedDevices()
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:53.544  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:53.545  5715  5715 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:45:53.546  5715  5715 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 07:45:53.546  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:53.546  3109  3109 D BluetoothA2dp: Proxy object connected
08-29 07:45:53.548   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:45:53.548  3109  3122 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 07:45:53.548  3109  3552 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:45:53.549  5715  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:45:53.550  3109  3109 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:45:53.550  3109  3677 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:45:53.550  3109  3109 D PanProfile: Bluetooth service connected
08-29 07:45:53.551  5715  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:45:53.552  3109  3109 D BluetoothInputDevice: Proxy object connected
08-29 07:45:53.552  3109  3109 D HidProfile: Bluetooth service connected
08-29 07:45:53.552   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 07:45:53.553  5715  5715 D ObexServerSockets: Succeed to create listening sockets 
08-29 07:45:53.553  5715  5715 D ObexServerSockets0: startAccept()
,08-29 07:45:53.553  5715  5715 D ObexServerSockets0: prepareForNewConnect()
08-29 07:45:53.554  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:53.556  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:53.556  5715  5715 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 07:45:53.556  5715  5715 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 07:45:53.556  5715  5778 D ObexServerSockets0: Accepting socket connection...
08-29 07:45:53.556  5715  5715 D BluetoothMapService: onReceive
08-29 07:45:53.556  5715  5715 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:45:53.556  5715  5715 D BluetoothMapService: STATE_ON
,08-29 07:45:53.557  5715  5779 D ObexServerSockets0: Accepting socket connection...
,08-29 07:45:53.559  5715  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:45:53.559  5648  5648 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 07:45:53.560  5715  5780 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 07:45:53.560  5715  5780 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 07:45:53.563  5648  5648 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 07:45:53.568  5648  5648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:45:53.571  5648  5648 D BluetoothA2dp: Proxy object connected
,08-29 07:45:53.575  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:45:53.576  5648  5648 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:45:53.583  5648  5648 D BluetoothPbap: Proxy object connected
,08-29 07:45:53.583  5715  5715 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:45:53.583  3109  3109 D BluetoothPbap: Proxy object connected
08-29 07:45:53.583  5715  5715 D ObexServerSockets0: prepareForNewConnect()
08-29 07:45:53.583  3109  3109 D PbapServerProfile: Bluetooth service connected
08-29 07:45:53.583  5648  5648 D PbapServerProfile: Bluetooth service connected
,08-29 07:45:53.590  5715  5784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:45:53.602  5715  5788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:45:53.604  5715  5788 I BtOppRfcommListener: Accept thread started.
,08-29 07:45:53.638  3481  3767 D BluetoothHeadset: Proxy object connected
,08-29 07:45:53.638   927   927 D BluetoothHeadset: Proxy object connected
08-29 07:45:53.638   927   927 D BluetoothHeadset: Proxy object connected
08-29 07:45:53.639   927   927 D BluetoothHeadset: Proxy object connected
08-29 07:45:53.639  3481  3511 D BluetoothHeadset: Proxy object connected
08-29 07:45:53.639  3109  3122 D BluetoothHeadset: Proxy object connected
08-29 07:45:53.639  3109  3109 D HeadsetProfile: Bluetooth service connected
,08-29 07:45:53.641   927   944 D BluetoothHeadset: Proxy object connected
,08-29 07:45:53.648   927   944 D BluetoothHeadset: Proxy object connected
,08-29 07:45:53.648  3109  3552 D BluetoothHeadset: Proxy object connected
08-29 07:45:53.648  3109  3109 D HeadsetProfile: Bluetooth service connected
,08-29 07:45:53.665  5648  5658 D BluetoothHeadset: Proxy object connected
,08-29 07:45:53.666  5648  5648 D HeadsetProfile: Bluetooth service connected
,08-29 07:45:55.576  5715  5753 D BluetoothAdapterState: Current state: ON, message: 23
08-29 07:45:55.576  5715  5753 D BluetoothAdapterProperties: Setting state to 13
08-29 07:45:55.576  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 07:45:55.577  5715  5753 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 07:45:55.579  5715  5753 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:45:55.580  5715  5715 D BluetoothMapService: onReceive
08-29 07:45:55.587  5715  5715 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 07:45:55.587  5715  5715 D BluetoothMapService: STATE_TURNING_OFF
08-29 07:45:55.588  5715  5715 D BluetoothMapService: MAP Service closeService in
08-29 07:45:55.588  5715  5715 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 07:45:55.588  5715  5715 D ObexServerSockets0: shutdown(block = true)
08-29 07:45:55.588  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:55.589  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:45:55.589  5715  5715 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:45:55.589  5715  5778 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 07:45:55.589  5715  5715 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 07:45:55.589  5715  5766 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 07:45:55.590  5715  5779 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 07:45:55.590  5715  5757 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:45:55.590  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 07:45:55.590  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:55.591  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:45:55.591  5648  5648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:45:55.592  5715  5715 I BtOppRfcommListener: stopping Accept Thread
,08-29 07:45:55.594  5715  5788 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 07:45:55.594  5715  5788 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 07:45:55.594  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:45:55.594  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:45:55.595  5546  5546 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 07:45:55.595  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:45:55.596  5715  5715 D HeadsetService: Received stop request...Stopping profile...
08-29 07:45:55.597  5648  5648 D DockEventReceiver: finishStartingService: stopping service
08-29 07:45:55.598  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:55.599  5648  5659 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:55.600  3481  3504 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:55.600   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:55.600   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:55.600  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:55.600   927   927 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:55.600  5715  5715 D A2dpService: Received stop request...Stopping profile...
08-29 07:45:55.601  5715  5772 D A2dpStateMachine: Exit Disconnected: -1
08-29 07:45:55.601  3109  3552 D BluetoothHeadset: Proxy object disconnected
08-29 07:45:55.603   927   927 D BluetoothA2dp: Proxy object disconnected
,08-29 07:45:55.607  5715  5715 D HidService: Received stop request...Stopping profile...
,08-29 07:45:55.607  5715  5715 D HidService: Stopping Bluetooth HidService
08-29 07:45:55.607  5648  5648 D HeadsetProfile: Bluetooth service disconnected
08-29 07:45:55.608  5648  5648 D BluetoothA2dp: Proxy object disconnected
08-29 07:45:55.608  5648  5648 D BluetoothInputDevice: Proxy object disconnected
08-29 07:45:55.608  5715  5715 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:55.608  5648  5648 D HidProfile: Bluetooth service disconnected
08-29 07:45:55.608  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.608  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.608  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:45:55.609  5715  5715 D HealthService: Received stop request...Stopping profile...
08-29 07:45:55.610  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:45:55.611  5715  5715 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 07:45:55.611  5715  5715 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 07:45:55.611  5715  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:55.611  5715  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:55.611  5715  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:55.611  5715  5715 D PanService: Received stop request...Stopping profile...
,08-29 07:45:55.612  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 07:45:55.613  5715  5757 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 07:45:55.613  5715  5715 D BluetoothMapService: Received stop request...Stopping profile...
08-29 07:45:55.613  5715  5715 D BluetoothMapService: stop()
08-29 07:45:55.613  5715  5715 D BluetoothMapAppObserver: deinitObservers()
08-29 07:45:55.613  5715  5715 D BluetoothMapAppObserver: removeReceiver()
08-29 07:45:55.615  5648  5648 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:45:55.615  5715  5715 D SapService: Received stop request...Stopping profile...
08-29 07:45:55.615  5648  5648 D PanProfile: Bluetooth service disconnected
08-29 07:45:55.615  5715  5715 V SapService: stop()
08-29 07:45:55.615  5648  5648 D BluetoothMap: Proxy object disconnected
,08-29 07:45:55.615  5648  5648 D MapProfile: Bluetooth service disconnected
08-29 07:45:55.615  3109  3109 D HeadsetProfile: Bluetooth service disconnected
08-29 07:45:55.615  3109  3109 D BluetoothA2dp: Proxy object disconnected
08-29 07:45:55.616  3109  3109 D BluetoothInputDevice: Proxy object disconnected
08-29 07:45:55.616  3109  3109 D HidProfile: Bluetooth service disconnected
08-29 07:45:55.616  3109  3109 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 07:45:55.616  3109  3109 D PanProfile: Bluetooth service disconnected
08-29 07:45:55.616  3109  3109 D BluetoothMap: Proxy object disconnected
,08-29 07:45:55.616  3109  3109 D MapProfile: Bluetooth service disconnected
08-29 07:45:55.616  5715  5715 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:55.616  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.616  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.616  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:55.618  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 07:45:55.618  5715  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:55.618  5715  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 07:45:55.618  5715  5764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:45:55.618  5715  5764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:45:55.618  5715  5764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 07:45:55.618  5715  5764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 07:45:55.619  3109  3109 D BluetoothPbap: Proxy object disconnected
08-29 07:45:55.619  3109  3109 D PbapServerProfile: Bluetooth service disconnected
08-29 07:45:55.619  5715  5715 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:55.619  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.619  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.619  5648  5648 D BluetoothPbap: Proxy object disconnected
08-29 07:45:55.619  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:55.619  5648  5648 D PbapServerProfile: Bluetooth service disconnected
08-29 07:45:55.620  5715  5715 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 07:45:55.620  5715  5715 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 07:45:55.620  5715  5757 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:45:55.620  5715  5715 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:55.620  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.620  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.620  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:55.620  5715  5715 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 07:45:55.621  5715  5757 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 07:45:55.621  5715  5715 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 07:45:55.621  5715  5715 V BluetoothAdapterState: isTurningOff()=true
,08-29 07:45:55.621  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.621  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.621  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:55.622  5715  5715 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 07:45:55.622  5715  5715 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 07:45:55.622  5715  5715 D BluetoothMapService: MAP Service closeService in
08-29 07:45:55.622  5715  5715 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:55.622  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.622  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.622  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:55.623  5715  5715 D BluetoothMapService: cleanup()
08-29 07:45:55.623  5715  5715 D BluetoothMapService: MAP Service closeService in
08-29 07:45:55.623  5715  5715 V BluetoothAdapterState: isTurningOff()=true
08-29 07:45:55.623  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.623  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:45:55.623  5715  5715 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:45:55.623  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 07:45:55.623  5715  5753 D BluetoothAdapterProperties: Setting state to 15
08-29 07:45:55.623  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 07:45:55.624  5715  5753 I BluetoothAdapterState: Entering BleOnState
08-29 07:45:55.625  5648  5658 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:45:55.626   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:55.626  3109  3552 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:45:55.626  3481  3702 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:55.627  5648  5659 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 07:45:55.627  5648  5658 D BluetoothPan: onBluetoothStateChange on: false
,08-29 07:45:55.628   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 07:45:55.628   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:55.628  5648  5659 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:45:55.628  3109  3122 D BluetoothMap: onBluetoothStateChange: up=false
08-29 07:45:55.629  3109  3121 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:45:55.629   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:55.629  5648  5658 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 07:45:55.630  5648  5659 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 07:45:55.630  3109  3677 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 07:45:55.631  3109  3552 D BluetoothPan: onBluetoothStateChange on: false
08-29 07:45:55.631  3109  3122 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 07:45:55.632  5715  5753 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 07:45:55.632  5715  5753 D BluetoothAdapterProperties: Setting state to 16
08-29 07:45:55.632  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 07:45:55.633  5715  5753 D BluetoothAdapterProperties: onBleDisable
08-29 07:45:55.633  5715  5753 I BluetoothAdapterState: Entering PendingCommandState
08-29 07:45:55.633  5715  5754 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 07:45:55.634  5715  5764 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 07:45:55.634  5715  5764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 07:45:55.635  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:55.635  5715  5757 D BluetoothAdapterProperties: Scan Mode:20
08-29 07:45:55.636  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:55.637  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:55.638  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:45:55.639  5648  5648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 07:45:55.643  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:45:55.646  5648  5648 D DockEventReceiver: finishStartingService: stopping service
,08-29 07:45:55.840  5715  5757 I bt_hci  : shut_down
,08-29 07:45:55.849  5715  5761 D bt_hwcfg: hw_epilog_process
08-29 07:45:55.849  5715  5761 I bt_vendor: low_power_mode_cb
,08-29 07:45:55.852  5715  5761 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 07:45:55.852  5715  5761 I bt_vendor: epilog_cb
08-29 07:45:55.852  5715  5761 I bt_hci  : epilog_finished_callback
,08-29 07:45:55.855  5715  5757 I bt_hci_h4: hal_close
,08-29 07:45:55.855  5715  5757 I bt_userial_vendor: device fd = 51 close
,08-29 07:45:55.964  5715  5754 D bt_stack_manager: event_shut_down_stack finished.
,08-29 07:45:55.965  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 07:45:55.970  5715  5753 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 07:45:55.970  5715  5715 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 07:45:55.971  5715  5715 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 07:45:55.971  5715  5715 D BtGatt.GattService: stop()
,08-29 07:45:55.972  5715  5715 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 07:45:55.975  5715  5715 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:45:55.975  5715  5715 V BluetoothAdapterState: isTurningOn()=false
08-29 07:45:55.975  5715  5715 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 07:45:55.975  5715  5715 V BluetoothAdapterState: isBleTurningOff()=true
08-29 07:45:55.976  5715  5753 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 07:45:55.976  5715  5753 D BluetoothAdapterProperties: Setting state to 10
08-29 07:45:55.976  5715  5753 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 07:45:55.977  5715  5753 I BluetoothAdapterState: Entering OffState
08-29 07:45:55.979   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 07:45:55.995  5715  5715 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 07:45:55.995  5715  5715 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 07:45:55.995  5715  5715 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 07:45:55.997  5715  5754 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 07:45:55.998  5715  5754 D bt_stack_manager: event_clean_up_stack finished.
,08-29 07:45:56.000  5715  5715 I art     : System.exit called, status: 0
08-29 07:45:56.000  5715  5715 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 07:45:56.028   927  3503 I ActivityManager: Process com.android.bluetooth (pid 5715) has died
,08-29 07:45:58.577  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:45:58.577  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:45:59.570   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:46:00.571   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:46:01.573   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:46:01.584  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:01.584  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7a1cd added. We now have 6 listener(s)
08-29 07:46:01.584  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:01.588  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:01.588  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@77a8a82 added. We now have 7 listener(s)
08-29 07:46:01.589  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:46:01.590  5546  5592 I System.out: IsBluetoothEnabled
,08-29 07:46:01.597  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:46:01.623   927   944 I ActivityManager: Start proc 5796:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 07:46:01.692  5796  5796 D AdapterServiceConfig: Adding HeadsetService
08-29 07:46:01.693  5796  5796 D AdapterServiceConfig: Adding A2dpService
08-29 07:46:01.693  5796  5796 D AdapterServiceConfig: Adding HidService
08-29 07:46:01.693  5796  5796 D AdapterServiceConfig: Adding HealthService
08-29 07:46:01.693  5796  5796 D AdapterServiceConfig: Adding PanService
08-29 07:46:01.693  5796  5796 D AdapterServiceConfig: Adding GattService
08-29 07:46:01.693  5796  5796 D AdapterServiceConfig: Adding BluetoothMapService
08-29 07:46:01.694  5796  5796 D AdapterServiceConfig: Adding SapService
,08-29 07:46:01.704   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d535ff:true
,08-29 07:46:01.705  5796  5796 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 07:46:01.708  5796  5796 I bt_bluedroid: init
08-29 07:46:01.708  5796  5808 I BluetoothAdapterState: Entering OffState
,08-29 07:46:01.710  5796  5809 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 07:46:01.710  5796  5809 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 07:46:01.710  5796  5809 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 07:46:01.710  5796  5809 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 07:46:01.711  5796  5796 I bt_bluedroid: get_profile_interface socket
,08-29 07:46:01.713  5796  5812 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 07:46:01.714  5796  5796 I bt_bluedroid: get_profile_interface sdp
08-29 07:46:01.715  5796  5812 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 07:46:01.717  5796  5807 I bt_bluedroid: config_hci_snoop_log
08-29 07:46:01.719   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 07:46:01.723  5796  5808 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 07:46:01.723  5796  5808 D BluetoothAdapterProperties: Setting state to 14
08-29 07:46:01.723  5796  5808 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 07:46:01.725  5796  5808 D BluetoothBondStateMachine: make
,08-29 07:46:01.727  5796  5813 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 07:46:01.729  5796  5808 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:46:01.730  5796  5796 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-29 07:46:01.732  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:46:01.733  5796  5796 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 07:46:01.733  5796  5796 D BtGatt.GattService: Received start request. Starting profile...
,08-29 07:46:01.734  5796  5796 D BtGatt.GattService: start()
08-29 07:46:01.734  5796  5796 I bt_bluedroid: get_profile_interface gatt
08-29 07:46:01.735  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:46:01.735  5796  5796 D BtGatt.AdvertiseManager: advertise manager created
,08-29 07:46:01.741  5796  5796 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:46:01.741  5796  5796 V BluetoothAdapterState: isTurningOn()=false
08-29 07:46:01.741  5796  5796 V BluetoothAdapterState: isBleTurningOn()=true
08-29 07:46:01.741  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:46:01.741  5796  5808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 07:46:01.742  5796  5808 I bt_bluedroid: enable
,08-29 07:46:01.742  5796  5809 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 07:46:01.742  5796  5809 I bt_hci  : start_up
,08-29 07:46:01.748  5796  5809 I bt_vendor: alloc value 0xf40a904d
,08-29 07:46:01.748  5796  5809 I bt_vendor: init
08-29 07:46:01.748  5796  5809 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 07:46:01.748  5796  5809 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 07:46:01.875  5796  5809 D bt_hci  : start_up starting async portion
,08-29 07:46:01.876  5796  5816 I bt_hci  : event_finish_startup
,08-29 07:46:01.876  5796  5816 I bt_hci_h4: hal_open
08-29 07:46:01.876  5796  5816 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 07:46:01.865  5817  5817 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:46:01.880  5796  5816 I bt_userial_vendor: device fd = 51 open
,08-29 07:46:01.896  5796  5816 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:46:01.899  5796  5816 D bt_hwcfg: Chipset BCM4358A3
08-29 07:46:01.900  5796  5816 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 07:46:01.900  5796  5816 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 07:46:02.396  5796  5816 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 07:46:02.396  5796  5816 D bt_hwcfg: Settlement delay -- 100 ms
08-29 07:46:02.396  5796  5816 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 07:46:02.530  5796  5816 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 07:46:02.531  5796  5816 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 07:46:02.532  5796  5816 I bt_hwcfg: vendor lib fwcfg completed
,08-29 07:46:02.533  5796  5816 I bt_vendor: firmware callback
,08-29 07:46:02.533  5796  5816 I bt_hci  : firmware_config_callback
,08-29 07:46:02.541  5796  5819 I bt_btu  : btu_task pending for preload complete event
,08-29 07:46:02.542  5796  5819 I bt_btu_task: Bluetooth chip preload is complete
08-29 07:46:02.542  5796  5819 I bt_btu  : btu_task received preload complete event
,08-29 07:46:02.547  5796  5819 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 07:46:02.548  5796  5819 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 07:46:02.549  5796  5819 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 07:46:02.549  5796  5819 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 07:46:02.549  5796  5819 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 07:46:02.549  5796  5819 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 07:46:02.549  5796  5819 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 07:46:02.549  5796  5819 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 07:46:02.574   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:46:02.642  5796  5819 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4026c99
08-29 07:46:02.643  5796  5819 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4026c99 
,08-29 07:46:02.713  5796  5812 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 07:46:02.715  5796  5812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 07:46:02.716  5796  5812 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 07:46:02.718  5796  5812 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 07:46:02.720  5796  5812 D BluetoothAdapterProperties: Scan Mode:20
,08-29 07:46:02.721  5796  5812 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:46:02.721  5796  5812 D bt_hci  : do_postload posting postload work item
08-29 07:46:02.721  5796  5816 I bt_hci  : event_postload
08-29 07:46:02.721  5796  5816 I bt_vendor: sco_config_cb
08-29 07:46:02.721  5796  5816 I bt_hci  : sco_config_callback postload finished.
08-29 07:46:02.723  5796  5812 D bt_bte_conf: Device ID record 1 : primary
,08-29 07:46:02.723  5796  5812 D bt_bte_conf:   vendorId            = 000f
08-29 07:46:02.723  5796  5812 D bt_bte_conf:   vendorIdSource      = 0001
08-29 07:46:02.723  5796  5812 D bt_bte_conf:   product             = 1200
08-29 07:46:02.723  5796  5812 D bt_bte_conf:   version             = 1436
08-29 07:46:02.724  5796  5812 D bt_bte_conf:   clientExecutableURL = 
08-29 07:46:02.724  5796  5812 D bt_bte_conf:   serviceDescription  = 
08-29 07:46:02.724  5796  5812 D bt_bte_conf:   documentationURL    = 
08-29 07:46:02.724  5796  5812 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 07:46:02.724  5796  5809 D bt_stack_manager: event_start_up_stack finished
,08-29 07:46:02.726  5796  5808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 07:46:02.727  5796  5808 D BluetoothAdapterProperties: Setting state to 15
08-29 07:46:02.727  5796  5808 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 07:46:02.729  5796  5808 I BluetoothAdapterState: Entering BleOnState
,08-29 07:46:02.731  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:46:02.732  5796  5816 I bt_vendor: low_power_mode_cb
08-29 07:46:02.732  5796  5808 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 07:46:02.732  5796  5808 D BluetoothAdapterProperties: Setting state to 11
08-29 07:46:02.732  5796  5808 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 07:46:02.736  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:46:02.741  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:46:02.742  5796  5796 D HeadsetService: Received start request. Starting profile...
08-29 07:46:02.744  5796  5796 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 07:46:02.744  5796  5796 D HeadsetStateMachine: make
,08-29 07:46:02.750  5796  5808 I BluetoothAdapterState: Entering PendingCommandState
,08-29 07:46:02.754  5796  5796 D HeadsetStateMachine: max_hf_connections = 1
08-29 07:46:02.754  5796  5796 I bt_bluedroid: get_profile_interface handsfree
08-29 07:46:02.754  5796  5812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 07:46:02.754  5796  5812 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 07:46:02.757  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:46:02.758  5796  5796 D A2dpService: Received start request. Starting profile...
,08-29 07:46:02.758  5796  5796 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 07:46:02.758  5796  5796 I bt_bluedroid: get_profile_interface avrcp
,08-29 07:46:02.765  5796  5796 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 07:46:02.765  5796  5796 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 07:46:02.765  5796  5796 D A2dpStateMachine: make
,08-29 07:46:02.767  5796  5796 I bt_bluedroid: get_profile_interface a2dp
,08-29 07:46:02.768  5796  5812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 07:46:02.769  5796  5826 D A2dpStateMachine: Enter Disconnected: -2
08-29 07:46:02.770  5796  5796 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 07:46:02.771  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:46:02.772  5796  5796 D HidService: Received start request. Starting profile...
08-29 07:46:02.772  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 07:46:02.772  5796  5796 I bt_bluedroid: get_profile_interface hidhost
08-29 07:46:02.772  5796  5796 D HidService: setHidService(): set to: null
08-29 07:46:02.773  5796  5812 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40082d9
08-29 07:46:02.773  5796  5812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 07:46:02.773  5796  5796 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 07:46:02.774  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:46:02.774  5796  5796 D HealthService: Received start request. Starting profile...
,08-29 07:46:02.776  5796  5796 I bt_bluedroid: get_profile_interface health
08-29 07:46:02.776  5796  5796 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 07:46:02.777  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:46:02.777  5796  5796 D PanService: Received start request. Starting profile...
08-29 07:46:02.777  5796  5796 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 07:46:02.777  5796  5796 I bt_bluedroid: get_profile_interface pan
08-29 07:46:02.778  5796  5812 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 07:46:02.779  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:46:02.780  5796  5796 D BluetoothMapService: Received start request. Starting profile...
08-29 07:46:02.780  5796  5796 D BluetoothMapService: start()
,08-29 07:46:02.782  5796  5796 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 07:46:02.783  5796  5796 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 07:46:02.783  5796  5796 D BluetoothMapAppObserver: createReceiver()
08-29 07:46:02.784  5796  5796 D BluetoothMapAppObserver: initObservers()
,08-29 07:46:02.784  5796  5796 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 07:46:02.789  5796  5796 V SapService: SapBinder()
08-29 07:46:02.789  5796  5796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
08-29 07:46:02.790  5796  5796 D SapService: Received start request. Starting profile...
08-29 07:46:02.790  5796  5796 V SapService: start()
,08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isTurningOff()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isTurningOff()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isTurningOff()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.796  5796  5824 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.796  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isTurningOff()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isTurningOff()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isTurningOff()=false
,08-29 07:46:02.797  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.798  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.798  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
08-29 07:46:02.798  5796  5796 V BluetoothAdapterState: isTurningOff()=false
08-29 07:46:02.798  5796  5796 V BluetoothAdapterState: isTurningOn()=true
08-29 07:46:02.798  5796  5796 V BluetoothAdapterState: isBleTurningOn()=false
08-29 07:46:02.799  5796  5796 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 07:46:02.799  5796  5808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 07:46:02.799  5796  5808 D BluetoothAdapterProperties: ScanMode =  20
08-29 07:46:02.799  5796  5808 D BluetoothAdapterProperties: State =  11
08-29 07:46:02.799  5796  5808 D BluetoothAdapterProperties: Setting state to 12
08-29 07:46:02.799  5796  5808 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 07:46:02.800  5796  5808 I BluetoothAdapterState: Entering OnState
08-29 07:46:02.800  5796  5812 D BluetoothAdapterProperties: Scan Mode:21
08-29 07:46:02.800  5796  5812 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 07:46:02.801  5648  5658 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:46:02.803   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:46:02.803  3109  3677 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:46:02.805  3481  3767 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:02.805  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:46:02.805  5648  5658 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 07:46:02.807  5648  5659 D BluetoothPan: onBluetoothStateChange on: true
,08-29 07:46:02.808  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:46:02.808  5648  5648 D BluetoothInputDevice: Proxy object connected
08-29 07:46:02.808  5648  5648 D HidProfile: Bluetooth service connected
08-29 07:46:02.808  5796  5796 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:46:02.809  5796  5796 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 07:46:02.809   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:46:02.810   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:46:02.810  5796  5796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:46:02.811  5648  5658 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 07:46:02.813  5796  5796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:46:02.814  3109  3552 D BluetoothMap: onBluetoothStateChange: up=true
08-29 07:46:02.814  5796  5796 D ObexServerSockets: Succeed to create listening sockets 
,08-29 07:46:02.814  5796  5796 D ObexServerSockets0: startAccept()
,08-29 07:46:02.814  5796  5796 D ObexServerSockets0: prepareForNewConnect()
08-29 07:46:02.816  3109  3122 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:46:02.816  5796  5796 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 07:46:02.816  5796  5796 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 07:46:02.817  5796  5834 D ObexServerSockets0: Accepting socket connection...
08-29 07:46:02.817  5796  5835 D ObexServerSockets0: Accepting socket connection...
,08-29 07:46:02.818   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:46:02.818  5648  5659 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 07:46:02.819   927   927 D BluetoothA2dp: Proxy object connected
08-29 07:46:02.819  3109  3109 D BluetoothA2dp: Proxy object connected
08-29 07:46:02.824  3109  3109 D BluetoothMap: Proxy object connected
08-29 07:46:02.824  3109  3109 D MapProfile: Bluetooth service connected
08-29 07:46:02.824  3109  3109 D BluetoothMap: getConnectedDevices()
08-29 07:46:02.825  5648  5648 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:46:02.825  5648  5648 D PanProfile: Bluetooth service connected
,08-29 07:46:02.825  5648  5648 D BluetoothA2dp: Proxy object connected
08-29 07:46:02.826  5648  5659 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:46:02.826  5648  5648 D BluetoothMap: Proxy object connected
08-29 07:46:02.826  5648  5648 D MapProfile: Bluetooth service connected
08-29 07:46:02.826  5648  5648 D BluetoothMap: getConnectedDevices()
08-29 07:46:02.827  3109  3552 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 07:46:02.828  3109  3122 D BluetoothPan: onBluetoothStateChange on: true
08-29 07:46:02.829  3109  3109 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 07:46:02.829  3109  3121 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 07:46:02.829  3109  3109 D PanProfile: Bluetooth service connected
,08-29 07:46:02.831  3109  3109 D BluetoothInputDevice: Proxy object connected
08-29 07:46:02.831  3109  3109 D HidProfile: Bluetooth service connected
08-29 07:46:02.832   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 07:46:02.833  5796  5796 D BluetoothMapService: onReceive
08-29 07:46:02.833  5796  5796 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 07:46:02.833  5796  5796 D BluetoothMapService: STATE_ON
08-29 07:46:02.834  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:02.837  5796  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 07:46:02.839  5796  5837 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 07:46:02.839  5796  5837 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 07:46:02.841  5648  5648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 07:46:02.849  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 07:46:02.856  5648  5648 D DockEventReceiver: finishStartingService: stopping service
08-29 07:46:02.860  3109  3109 D BluetoothPbap: Proxy object connected
08-29 07:46:02.860  3109  3109 D PbapServerProfile: Bluetooth service connected
08-29 07:46:02.861  5648  5648 D BluetoothPbap: Proxy object connected
08-29 07:46:02.861  5648  5648 D PbapServerProfile: Bluetooth service connected
,08-29 07:46:02.863  5796  5796 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 07:46:02.863  5796  5796 D ObexServerSockets0: prepareForNewConnect()
,08-29 07:46:02.866  5796  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:46:02.877  5796  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 07:46:02.878  5796  5845 I BtOppRfcommListener: Accept thread started.
,08-29 07:46:02.905  5648  5659 D BluetoothHeadset: Proxy object connected
08-29 07:46:02.905  3481  3504 D BluetoothHeadset: Proxy object connected
08-29 07:46:02.905  3481  3702 D BluetoothHeadset: Proxy object connected
,08-29 07:46:02.905   927   927 D BluetoothHeadset: Proxy object connected
08-29 07:46:02.905   927   927 D BluetoothHeadset: Proxy object connected
08-29 07:46:02.905   927   927 D BluetoothHeadset: Proxy object connected
,08-29 07:46:02.906  3109  3677 D BluetoothHeadset: Proxy object connected
,08-29 07:46:02.906  3109  3109 D HeadsetProfile: Bluetooth service connected
08-29 07:46:02.907  5648  5648 D HeadsetProfile: Bluetooth service connected
,08-29 07:46:02.910   927   944 D BluetoothHeadset: Proxy object connected
,08-29 07:46:02.918   927   944 D BluetoothHeadset: Proxy object connected
,08-29 07:46:02.928  5648  5658 D BluetoothHeadset: Proxy object connected
,08-29 07:46:02.928  3109  3552 D BluetoothHeadset: Proxy object connected
08-29 07:46:02.929  5648  5648 D HeadsetProfile: Bluetooth service connected
,08-29 07:46:02.929  3109  3109 D HeadsetProfile: Bluetooth service connected
,08-29 07:46:03.575   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:03.615  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:03.619  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:03.622  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:46:03.622  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ecc593 added. We now have 8 listener(s)
,08-29 07:46:03.623  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:46:03.626   927  4495 D WifiService: setWifiEnabled: false pid=5546, uid=10077
08-29 07:46:03.626   927  4495 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:46:03.632  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:03.633   927  3500 D WifiService: setWifiEnabled: true pid=5546, uid=10077
08-29 07:46:03.633   927  3500 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 07:46:03.638   505   920 D SoftapController: Softap fwReload - Ok
,08-29 07:46:03.642   505   920 D CommandListener: Setting iface cfg
,08-29 07:46:03.642   505   920 D CommandListener: Trying to bring down wlan0
08-29 07:46:03.643   505   920 D CommandListener: Clearing all IP addresses on wlan0
,08-29 07:46:03.648   927  2957 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 07:46:04.258   927  2957 D wifi    : set interface wlan0 flags (UP)
,08-29 07:46:04.264   927  2957 I WifiHAL : Initializing wifi
08-29 07:46:04.264   927  2957 I WifiHAL : Creating socket
,08-29 07:46:04.268   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 07:46:04.272   927  2957 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 07:46:04.272   927  2957 D wifi    : Did set static halHandle = 0x7f6a26e1a0
08-29 07:46:04.272   927  2957 D wifi    : halHandle = 0x7f6a26e1a0, mVM = 0x7f8670d140, mCls = 0x2017d2
08-29 07:46:04.273   927  2957 D wifi    : array field set
08-29 07:46:04.273   927  2957 I WifiNative-HAL: interface[0] = wlan0
08-29 07:46:04.274   927  5850 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547241779616
08-29 07:46:04.274   927  5850 D wifi    : waitForHalEvents called, vm = 0x7f8670d140, obj = 0x2017d2, env = 0x7f6bb90840
,08-29 07:46:04.320  5851  5851 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 07:46:04.339  5851  5851 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:46:04.349  5851  5851 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 07:46:04.349  5851  5851 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 07:46:04.374   927  2957 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 07:46:04.381  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:46:04.386   927  2957 D WifiConfigStore: Loading config and enabling all networks 
,08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:04.391  5546  5546 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:04.393  5546  5546 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:04.394   927  2957 D WifiConfigStore: loaded 0 passpoint configs
,08-29 07:46:04.394   927  2957 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:46:04.395   927  2957 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 07:46:04.396   927  2957 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 07:46:04.396   927  2957 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 07:46:04.396   927  2957 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 07:46:04.400  4757  4757 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 07:46:04.401   927  2957 D WifiNative-HAL: Setting external_sim to 1
08-29 07:46:04.401   927  2957 D wifi    : setting dfs flag to true, 0x7f6b3bf440
,08-29 07:46:04.402   927  2957 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 07:46:04.402   927  2957 D wifi    : setting scan oui 0x7f6b3bf440
08-29 07:46:04.402   927  2957 D WifiHAL : Sending mac address OUI
,08-29 07:46:04.415   927  2957 E native  : do suspend true
,08-29 07:46:04.421   505   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 07:46:04.422   927  2957 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 07:46:04.422   927   927 D RttService: SCAN_AVAILABLE : 3
,08-29 07:46:04.422   927  3011 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 07:46:04.423   505   920 D CommandListener: Setting iface cfg
,08-29 07:46:04.427   927  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '77 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 77 Failed to set address (No such device)'
,08-29 07:46:04.427   927  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 07:46:04.429   927  2956 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 07:46:04.434   927  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 07:46:04.451   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=195200 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,08-29 07:46:04.576   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:04.640  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:04.647  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:04.653  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 07:46:04.654  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 07:46:04.656  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e0d3d1 Bundle[{}]
08-29 07:46:04.656  5546  5592 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 07:46:04.656  5546  5592 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 07:46:04.657  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 07:46:04.657  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 07:46:04.657  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 07:46:04.658  5546  5592 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 07:46:04.662  5546  5592 I System.out: Running OutgoingSocketThread
,08-29 07:46:04.663  5546  5853 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 155)
,08-29 07:46:04.665  5546  5853 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46497
08-29 07:46:04.665  5546  5853 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 07:46:05.665  5546  5592 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 156)
,08-29 07:46:05.665  5546  5592 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 156)
08-29 07:46:05.670  5546  5592 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 161)
,08-29 07:46:05.672  5546  5592 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 07:46:05.672  5546  5592 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 162)
,08-29 07:46:05.677  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:46:05.678  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b519d0 added. We now have 2 listener(s)
,08-29 07:46:05.682  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:46:05.682  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:46:05.682  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:46:05.683  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:46:05.683  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd98dc9 added. We now have 9 listener(s)
,08-29 07:46:05.683  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.684  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:46:05.691  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:05.696  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:05.698  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 07:46:05.699  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:46:05.699  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:46:05.699  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9427ef added. We now have 3 listener(s)
08-29 07:46:05.701  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.702  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:46:05.702  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 07:46:05.702  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 07:46:05.703  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 07:46:05.703  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1a02fc added. We now have 10 listener(s)
08-29 07:46:05.703  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.703  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.703  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:46:05.703  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:46:05.704  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:46:05.704  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.704  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.704  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.704  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.704  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b519d0 removed from the list
08-29 07:46:05.704  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:46:05.704  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd98dc9 removed from the list
08-29 07:46:05.705  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:46:05.705  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.705  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.705  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.707  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.707  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.707  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.707  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd98dc9 not in the list
08-29 07:46:05.707  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.707  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:46:05.708  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.708  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.708  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.708  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1a02fc removed from the list
08-29 07:46:05.708  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.708  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.709  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.709  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.709  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9427ef removed from the list
08-29 07:46:05.710  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:46:05.710  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e43d85 added. We now have 2 listener(s)
08-29 07:46:05.713  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.713  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.713  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.713  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.713  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cae7da added. We now have 9 listener(s)
08-29 07:46:05.713  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.714  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:46:05.717  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:05.722  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 07:46:05.725  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:05.725  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:46:05.725  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:46:05.725  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48252e8 added. We now have 3 listener(s)
08-29 07:46:05.726  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.727  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.727  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.727  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.727  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.727  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8302d01 added. We now have 10 listener(s)
,08-29 07:46:05.727  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.727  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:46:05.727  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:46:05.727  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:46:05.727  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:46:05.727  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:46:05.728  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:46:05.732  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 07:46:05.732  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 07:46:05.736  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 07:46:05.736  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 07:46:05.736  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:46:05.738  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:46:05.738  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:46:05.738  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:46:05.739  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:46:05.741  5796  5806 D BtGatt.GattService: registerClient() - UUID=6ce0a8c0-3335-46f9-8636-3d1f61827ab8
08-29 07:46:05.742  5796  5812 D BtGatt.GattService: onClientRegistered() - UUID=6ce0a8c0-3335-46f9-8636-3d1f61827ab8, clientIf=5
,08-29 07:46:05.742  5546  5556 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 07:46:05.743  5796  5832 D BtGatt.GattService: start scan with filters
,08-29 07:46:05.746  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 07:46:05.746  5796  5815 D BtGatt.ScanManager: handling starting scan
08-29 07:46:05.746  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:46:05.746  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:46:05.748  5796  5815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3591755
,08-29 07:46:05.746  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:46:05.755  5796  5812 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:46:05.757  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.757  5796  5815 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 07:46:05.759  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:46:05.759  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:46:05.759  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:46:05.760  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:46:05.762  5546  5592 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 07:46:05.762  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 07:46:05.763  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 07:46:05.763  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.763  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:46:05.763  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 07:46:05.763  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 07:46:05.763  5796  5812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:46:05.763  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:46:05.763  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.763  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:46:05.763  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:46:05.763  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:46:05.763  5796  5815 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:46:05.764  5796  5815 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:46:05.764  5546  5592 D BluetoothAdapter: STATE_ON
,08-29 07:46:05.769  5796  5806 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:46:05.770  5796  5832 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 07:46:05.770  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:46:05.770  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:46:05.770  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:46:05.770  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:46:05.770  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 07:46:05.771  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:46:05.771  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:46:05.771  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:46:05.771  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 07:46:05.772  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 07:46:05.773  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:46:05.773  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:46:05.773  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:46:05.774  5796  5812 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 07:46:05.774  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.775  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:46:05.775  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:46:05.775  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:46:05.775  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.775  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.775  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.775  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.775  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e43d85 removed from the list
08-29 07:46:05.775  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:46:05.775  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cae7da removed from the list
08-29 07:46:05.776  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:46:05.776  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:46:05.779  5796  5812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 07:46:05.779  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.779  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.779  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:46:05.780  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.780  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.780  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:46:05.780  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cae7da not in the list
08-29 07:46:05.780  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.780  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:46:05.781  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 07:46:05.781  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.781  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.782  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8302d01 removed from the list
08-29 07:46:05.782  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.782  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.782  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.782  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.782  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48252e8 removed from the list
08-29 07:46:05.782  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 07:46:05.782  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1983d added. We now have 2 listener(s)
08-29 07:46:05.784  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.784  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.784  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.784  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.784  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66e9832 added. We now have 9 listener(s)
08-29 07:46:05.784  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.785  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:46:05.787  5796  5812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 07:46:05.787  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.787  5796  5815 D BtGatt.ScanManager: stopping BLe Batch
,08-29 07:46:05.787  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:05.790  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:05.791  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:05.792  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:46:05.792  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:46:05.792  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a9700 added. We now have 3 listener(s)
08-29 07:46:05.792  5796  5812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:46:05.792  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.792  5796  5815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:46:05.793  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.793  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.793  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.793  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.793  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.793  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b647b39 added. We now have 10 listener(s)
08-29 07:46:05.793  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.793  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:46:05.794  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:46:05.794  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:46:05.794  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:46:05.794  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:46:05.794  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:46:05.794  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.797  5796  5812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:46:05.797  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.798  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 07:46:05.798  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:46:05.800  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 07:46:05.801  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 07:46:05.801  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:46:05.804  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:46:05.804  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:46:05.804  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:46:05.804  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:46:05.805  5796  5831 D BtGatt.GattService: registerClient() - UUID=17b166ac-5e0d-4e9d-93df-3849f7ceb090
08-29 07:46:05.806  5796  5812 D BtGatt.GattService: onClientRegistered() - UUID=17b166ac-5e0d-4e9d-93df-3849f7ceb090, clientIf=5
08-29 07:46:05.806  5546  5557 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:46:05.806  5796  5832 D BtGatt.GattService: start scan with filters
,08-29 07:46:05.808  5796  5815 D BtGatt.ScanManager: handling starting scan
,08-29 07:46:05.808  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 07:46:05.808  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:46:05.808  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:46:05.808  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 07:46:05.810  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:46:05.810  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 07:46:05.810  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:46:05.811  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 07:46:05.815  5796  5812 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 07:46:05.815  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.815  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:46:05.815  5796  5815 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 07:46:05.815  5546  5592 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 07:46:05.815  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:46:05.815  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:46:05.815  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:46:05.815  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.816  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.816  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:46:05.816  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.816  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f1983d removed from the list
08-29 07:46:05.816  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.816  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66e9832 removed from the list
08-29 07:46:05.816  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:46:05.816  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.816  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.816  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 07:46:05.816  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.816  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.817  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.818  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.818  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.818  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66e9832 not in the list
08-29 07:46:05.818  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 07:46:05.818  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:46:05.818  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:46:05.818  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:46:05.818  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 07:46:05.818  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:46:05.819  5796  5807 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:46:05.819  5796  5806 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:46:05.819  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:46:05.819  5796  5812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:46:05.820  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.820  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:46:05.820  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:46:05.820  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:46:05.820  5796  5815 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:46:05.820  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:46:05.820  5796  5815 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:46:05.821  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:46:05.821  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:46:05.821  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:46:05.821  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 07:46:05.822  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.823  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.823  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.823  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:46:05.823  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:46:05.823  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b647b39 removed from the list
08-29 07:46:05.823  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:46:05.824  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.824  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:46:05.824  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.824  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.824  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.824  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a9700 removed from the list
,08-29 07:46:05.825  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:46:05.825  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28891f5 added. We now have 2 listener(s)
,08-29 07:46:05.826  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 07:46:05.826  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.827  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.827  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.827  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91cfb8a added. We now have 9 listener(s)
08-29 07:46:05.827  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:46:05.827  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 07:46:05.828  5796  5812 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 07:46:05.829  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.830  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:05.833  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:05.833  5796  5812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 07:46:05.833  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.835  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:05.835  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:46:05.835  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:46:05.835  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644618 added. We now have 3 listener(s)
08-29 07:46:05.836  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.836  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.836  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.836  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.836  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.836  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d5871 added. We now have 10 listener(s)
,08-29 07:46:05.836  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.836  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:46:05.836  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 07:46:05.836  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 07:46:05.836  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 07:46:05.837  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 07:46:05.837  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.839  5546  5592 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 07:46:05.839  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 07:46:05.839  5796  5812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:46:05.839  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.839  5796  5815 D BtGatt.ScanManager: stopping BLe Batch
,08-29 07:46:05.844  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 07:46:05.844  5796  5812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:46:05.844  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.844  5796  5815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 07:46:05.844  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 07:46:05.844  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 07:46:05.848  5796  5812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 07:46:05.848  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.849  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 07:46:05.849  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 07:46:05.850  5546  5592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 07:46:05.850  5546  5592 D BluetoothAdapter: STATE_ON
,08-29 07:46:05.852  5796  5807 D BtGatt.GattService: registerClient() - UUID=c80acc20-f254-4c3d-b582-1b44c56f4889
08-29 07:46:05.852  5796  5812 D BtGatt.GattService: onClientRegistered() - UUID=c80acc20-f254-4c3d-b582-1b44c56f4889, clientIf=5
,08-29 07:46:05.853  5546  5557 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 07:46:05.853  5796  5806 D BtGatt.GattService: start scan with filters
,08-29 07:46:05.855  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 07:46:05.855  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 07:46:05.855  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 07:46:05.855  5796  5815 D BtGatt.ScanManager: handling starting scan
08-29 07:46:05.855  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 07:46:05.856  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 07:46:05.857  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 07:46:05.857  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 07:46:05.858  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 07:46:05.859  5796  5812 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 07:46:05.859  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.859  5796  5815 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 07:46:05.861  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 07:46:05.861  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:46:05.861  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 07:46:05.861  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.861  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.861  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 07:46:05.861  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.861  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28891f5 removed from the list
08-29 07:46:05.861  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.861  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91cfb8a removed from the list
08-29 07:46:05.861  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 07:46:05.861  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.862  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.862  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 07:46:05.862  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.862  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.863  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.863  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.863  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.863  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91cfb8a not in the list
08-29 07:46:05.863  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 07:46:05.863  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 07:46:05.863  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 07:46:05.863  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 07:46:05.863  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 07:46:05.864  5546  5592 D BluetoothAdapter: STATE_ON
08-29 07:46:05.864  5796  5812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 07:46:05.864  5796  5833 D BtGatt.GattService: stopScan() - queue size =1
08-29 07:46:05.864  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.864  5796  5815 D BtGatt.ScanManager: Starting BLE batch scan
08-29 07:46:05.864  5796  5815 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 07:46:05.865  5796  5807 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 07:46:05.865  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 07:46:05.865  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 07:46:05.865  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 07:46:05.865  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 07:46:05.865  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 07:46:05.866  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 07:46:05.866  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 07:46:05.866  5546  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 07:46:05.866  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 07:46:05.867  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.867  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.867  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.867  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.867  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:46:05.867  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39d5871 removed from the list
08-29 07:46:05.867  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.867  5546  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 07:46:05.867  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.868  5546  5546 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 07:46:05.868  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.868  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.868  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1644618 removed from the list
08-29 07:46:05.868  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:46:05.868  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e0aad added. We now have 2 listener(s)
08-29 07:46:05.869  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.869  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.869  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.869  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.870  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51971e2 added. We now have 9 listener(s)
,08-29 07:46:05.870  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 07:46:05.873  5796  5812 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 07:46:05.873  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 07:46:05.873  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.875  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 07:46:05.878  5796  5812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 07:46:05.878  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 07:46:05.879  5546  5592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 07:46:05.881  5546  5592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 07:46:05.881  5546  5592 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 07:46:05.881  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 07:46:05.881  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed1c030 added. We now have 3 listener(s)
08-29 07:46:05.882  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 07:46:05.882  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 07:46:05.882  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 07:46:05.882  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 07:46:05.882  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 07:46:05.882  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfda4a9 added. We now have 10 listener(s)
08-29 07:46:05.882  5546  5592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 07:46:05.883  5546  5592 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 07:46:05.883  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 07:46:05.883  5546  5592 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 07:46:05.883  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.883  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.883  5796  5812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 07:46:05.883  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 07:46:05.883  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.883  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.883  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e0aad removed from the list
08-29 07:46:05.883  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 07:46:05.883  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51971e2 removed from the list
08-29 07:46:05.883  5796  5815 D BtGatt.ScanManager: stopping BLe Batch
08-29 07:46:05.883  5546  5546 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 07:46:05.883  5546  5592 D io.jxcore.node.ConnectivityMonitor: stop
08-29 07:46:05.884  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 07:46:05.884  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 07:46:05.884  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.885  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.885  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.885  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.885  5546  5592 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51971e2 not in the list
08-29 07:46:05.885  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.885  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.886  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 07:46:05.886  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 07:46:05.886  5546  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 07:46:05.886  5546  5592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfda4a9 removed from the list
,08-29 07:46:05.886  5546  5592 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 07:46:05.886  5546  5592 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 07:46:05.886  5546  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 07:46:05.886  5546  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 07:46:05.886  5546  5592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed1c030 removed from the list
08-29 07:46:05.887  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 07:46:05.887  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 07:46:05.887  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 07:46:05.887  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 07:46:05.887  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 07:46:05.887  5546  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 07:46:05.888  5796  5812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 07:46:05.888  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 07:46:05.888  5796  5815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 07:46:05.891  5546  5854 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: My test thread name)
,08-29 07:46:05.892  5546  5854 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: My test thread name)
08-29 07:46:05.892  5546  5854 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 07:46:05.893  5546  5855 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: My test thread name)
08-29 07:46:05.893  5546  5855 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: My test thread name)
08-29 07:46:05.893  5796  5812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 07:46:05.893  5546  5855 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 07:46:05.893  5796  5812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 07:46:05.895  5546  5592 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 07:46:05.895  5546  5592 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 07:46:05.895  5546  5592 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 07:46:05.895  5546  5592 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 07:46:05.895  5546  5592 D com.test.thalitest.ThaliTestRunner: Total duration: 22528 ms
08-29 07:46:05.897  5546  5592 I jxcore-log: *Native tests were executed*
08-29 07:46:05.897  5546  5592 I jxcore-log: 
08-29 07:46:05.897  5546  5592 I jxcore-log: Total number of executed tests:  80
08-29 07:46:05.897  5546  5592 I jxcore-log: 
08-29 07:46:05.897  5546  5592 I jxcore-log: Number of passed tests:  80
08-29 07:46:05.897  5546  5592 I jxcore-log: 
08-29 07:46:05.897  5546  5592 I jxcore-log: Number of failed tests:  0
08-29 07:46:05.897  5546  5592 I jxcore-log: 
08-29 07:46:05.897  5546  5592 I jxcore-log: Number of ignored tests:  0
08-29 07:46:05.897  5546  5592 I jxcore-log: 
08-29 07:46:05.897  5546  5592 I jxcore-log: Total duration:  22528
08-29 07:46:05.897  5546  5592 I jxcore-log: 
08-29 07:46:05.898  5546  5592 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 07:46:05.898  5546  5592 I jxcore-log: 
08-29 07:46:05.900  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.900  5546  5592 I jxcore-log: 
,08-29 07:46:05.903  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.903  5546  5592 I jxcore-log: 
08-29 07:46:05.904  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.904  5546  5592 I jxcore-log: 
08-29 07:46:05.905  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.905  5546  5592 I jxcore-log: 
08-29 07:46:05.906  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.906  5546  5592 I jxcore-log: 
08-29 07:46:05.907  5546  5546 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 07:46:05.907  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.907  5546  5592 I jxcore-log: 
08-29 07:46:05.909  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.909  5546  5592 I jxcore-log: 
08-29 07:46:05.910  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.910  5546  5592 I jxcore-log: 
08-29 07:46:05.912  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.912  5546  5592 I jxcore-log: 
08-29 07:46:05.913  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:46:05.913  5546  5592 I jxcore-log: 
08-29 07:46:05.913  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.913  5546  5592 I jxcore-log: 
08-29 07:46:05.914  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.914  5546  5592 I jxcore-log: 
08-29 07:46:05.915  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.915  5546  5592 I jxcore-log: 
08-29 07:46:05.916  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.916  5546  5592 I jxcore-log: 
08-29 07:46:05.917  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.917  5546  5592 I jxcore-log: 
08-29 07:46:05.917  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.917  5546  5592 I jxcore-log: 
08-29 07:46:05.918  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.918  5546  5592 I jxcore-log: 
08-29 07:46:05.919  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.919  5546  5592 I jxcore-log: 
08-29 07:46:05.919  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.919  5546  5592 I jxcore-log: 
08-29 07:46:05.920  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 07:46:05.920  5546  5592 I jxcore-log: 
08-29 07:46:05.921  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.921  5546  5592 I jxcore-log: 
08-29 07:46:05.921  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.921  5546  5592 I jxcore-log: 
08-29 07:46:05.922  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.922  5546  5592 I jxcore-log: 
08-29 07:46:05.923  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.923  5546  5592 I jxcore-log: 
08-29 07:46:05.923  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.923  5546  5592 I jxcore-log: 
08-29 07:46:05.924  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.924  5546  5592 I jxcore-log: 
08-29 07:46:05.925  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 07:46:05.925  5546  5592 I jxcore-log: 
,08-29 07:46:06.275  5546  5546 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:46:06.278  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:46:06.278  5546  5592 I jxcore-log: 
,08-29 07:46:06.324  5546  5546 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:46:06.328  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:46:06.328  5546  5592 I jxcore-log: 
,08-29 07:46:06.356  5856  5856 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 07:46:06.361  5856  5856 D AndroidRuntime: CheckJNI is OFF
,08-29 07:46:06.368  5546  5546 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 07:46:06.371  5546  5592 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 07:46:06.371  5546  5592 I jxcore-log: 
,08-29 07:46:06.389  5856  5856 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 07:46:06.418  5856  5856 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 07:46:06.434  5856  5856 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 07:46:06.441   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 07:46:06.442   927   940 I ActivityManager: Killing 5546:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 07:46:06.525   927  4495 D GraphicsStats: Buffer count: 2
,08-29 07:46:06.525   927  3160 I WindowState: WIN DEATH: Window{c70826d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 07:46:06.525   927  2960 D WifiService: Client connection lost with reason: 4
,08-29 07:46:06.584   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 07:46:06.584   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 07:46:06.585   927   950 I art     : Starting a blocking GC Explicit
,08-29 07:46:06.586   927   940 E ActivityManager: Failure starting process com.test.thalitest
08-29 07:46:06.586   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 07:46:06.586   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 07:46:06.586   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:46:06.586   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:46:06.586   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 07:46:06.586   927   940 I ActivityManager:   Force finishing activity ActivityRecord{3dbf58e u0 com.test.thalitest/.MainActivity t4}
,08-29 07:46:06.594   927  3500 W ActivityManager: Spurious death for ProcessRecord{58c44c0 0:com.test.thalitest/u0a77}, curProc for 5546: null
,08-29 07:46:06.662   927   950 I art     : Explicit concurrent mark sweep GC freed 26692(1622KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.526ms total 77.048ms
,08-29 07:46:06.683   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 07:46:06.685  5856  5856 I art     : System.exit called, status: 0
,08-29 07:46:06.686  5856  5856 I AndroidRuntime: VM exiting with result code 0.
,08-29 07:46:06.701   927   950 I ActivityManager: Start proc 5866:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-29 07:46:06.702   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 07:46:06.708   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 07:46:06.711  5796  5796 D BluetoothMapAppObserver: onReceive
,08-29 07:46:06.712  5796  5796 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 07:46:06.714  3389  3389 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 07:46:06.717  3609  3876 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 07:46:06.733   927  2938 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 07:46:06.734  3481  3481 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 07:46:06.742   927   940 I ActivityManager: Start proc 5879:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 07:46:06.742  3389  5877 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 07:46:06.765  3389  5877 I Decoder : createOrResetDecoder
,08-29 07:46:06.774   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 07:46:06.785    28    28 W kworker/2:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:46:06.785    28    28 W kworker/2:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:46:06.796  3563  3563 I ConfigService: onCreate
,08-29 07:46:06.805    28    28 W kworker/2:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 07:46:06.812  3389  5877 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-29 07:46:06.819  5879  5879 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
08-29 07:46:06.822   927  4495 I ActivityManager: Start proc 5895:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 07:46:06.823  3524  3624 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 07:46:06.823  3524  3624 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3524
08-29 07:46:06.823  3524  3624 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 07:46:06.823  3524  3624 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: Can't write: system_app_crash
08-29 07:46:06.828   927  5900 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 07:46:06.828   927  5900 E DropBoxManagerService: 	... 5 more
08-29 07:46:06.828   927  3500 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 07:46:06.832  3524  3624 I Process : Sending signal. PID: 3524 SIG: 9
,08-29 07:46:06.883  3389  5877 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
08-29 07:46:06.885  3389  5877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 07:46:06.886  3389  5877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 07:46:06.888   379   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-29 07:46:06.888   379   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
