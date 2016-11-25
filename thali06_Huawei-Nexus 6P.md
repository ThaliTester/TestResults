#### Test 89975734180bfa4_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-25 08:32:31.871  3529  5585 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 08:32:32.120  3529  5583 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-25 08:32:32.177  3529  5581 W Uploader:  no longer exists, so no auth token.
11-25 08:32:32.187  3529  5585 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-25 08:32:32.266  3529  5583 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-25 08:32:32.283  5594  5594 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 08:32:32.286  5594  5594 D AndroidRuntime: CheckJNI is OFF
11-25 08:32:32.310  5594  5594 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 08:32:32.337  5594  5594 I Radio-JNI: register_android_hardware_Radio DONE
11-25 08:32:32.352  5594  5594 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-25 08:32:32.355   931  3368 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 08:32:32.384   931  3368 I ActivityManager: Start proc 5603:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 08:32:32.387  5594  5594 D AndroidRuntime: Shutting down VM
,11-25 08:32:32.726   931  3805 I WindowManager: Screenshot max retries 4 of Token{9ba683a ActivityRecord{e9a0365 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{11e3a1d u0 Starting com.test.thalitest} drawState=2
,11-25 08:32:32.803  5603  5603 I CordovaLog: Changing log level to DEBUG(3)
,11-25 08:32:32.803  5603  5603 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 08:32:32.803  5603  5603 D CordovaActivity: CordovaActivity.onCreate()
,11-25 08:32:32.810  5603  5603 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-25 08:32:32.837  5603  5603 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-25 08:32:32.905  5603  5603 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 294-357)
,11-25 08:32:32.905  5603  5603 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 08:32:32.942  5603  5603 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6b9e8ba}
,11-25 08:32:32.943  5603  5603 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-25 08:32:32.943  5603  5603 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 08:32:32.949  5603  5603 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-25 08:32:32.951  5603  5603 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 08:32:32.996  5603  5603 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 08:32:33.008  5603  5603 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
11-25 08:32:33.008  5603  5603 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 08:32:33.008  5603  5603 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 08:32:33.008  5603  5603 I Adreno  : Build Date                       : 12/06/15
11-25 08:32:33.008  5603  5603 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 08:32:33.008  5603  5603 I Adreno  : Local Branch                     : mybranch17112971
11-25 08:32:33.008  5603  5603 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 08:32:33.008  5603  5603 I Adreno  : Remote Branch                    : NONE
11-25 08:32:33.008  5603  5603 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 08:32:33.041   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cf24578:true
,11-25 08:32:33.061   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34377]" dev="sockfs" ino=34377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 08:32:33.061   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34377]" dev="sockfs" ino=34377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 08:32:33.074  5603  5603 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 08:32:33.082  5603  5603 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 08:32:33.085  5603  5603 D PluginManager: init()
,11-25 08:32:33.088  5603  5603 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 08:32:33.101  5603  5603 D CordovaActivity: Started the activity.
,11-25 08:32:33.102  5603  5603 D CordovaActivity: Resumed the activity.
,11-25 08:32:33.101   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30669]" dev="sockfs" ino=30669 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 08:32:33.105  5603  5640 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-25 08:32:33.101   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30669]" dev="sockfs" ino=30669 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 08:32:33.104  3767  3767 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34382]" dev="sockfs" ino=34382 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 08:32:33.104  3767  3767 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34382]" dev="sockfs" ino=34382 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 08:32:33.109  5603  5603 D CordovaActivity: Paused the activity.
,11-25 08:32:33.111  5603  5627 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 08:32:33.136  5603  5640 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 08:32:33.161  5603  5603 D CordovaActivity: Stopped the activity.
,11-25 08:32:33.217   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +489ms (total +848ms)
,11-25 08:32:33.223  5603  5603 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 08:32:33.239  5603  5603 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5603
,11-25 08:32:33.315  5603  5603 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 08:32:33.454  5603  5643 D jxcore_app_log: JniHelper::setJavaVM(0xf51fc000), pthread_self() = -584316624
,11-25 08:32:33.459  5603  5643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 08:32:33.459  5603  5643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 08:32:33.459  5603  5643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 08:32:33.459  5603  5643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 08:32:33.459  5603  5643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 08:32:33.459  5603  5643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da92ca3 added. We now have 1 listener(s)
,11-25 08:32:33.461  5603  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-25 08:32:33.462  5603  5643 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:32:33.462  5603  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 08:32:33.462  5603  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-25 08:32:33.464  5603  5643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ff6b1e added. We now have 1 listener(s)
11-25 08:32:33.464  5603  5643 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:32:33.468   931  2927 D WifiService: New client listening to asynchronous messages
,11-25 08:32:33.469  5603  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 08:32:33.469  5603  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 08:32:33.469  5603  5643 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-25 08:32:33.469  5603  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-25 08:32:33.469  5603  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 08:32:33.469  5603  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 08:32:33.469  5603  5643 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-25 08:32:33.471  5603  5643 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 08:32:33.480  5603  5603 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 08:32:33.487  5603  5603 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-25 08:32:33.487  5603  5603 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 08:32:33.964  5603  5612 I art     : Background partial concurrent mark sweep GC freed 61026(7MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 2.351ms total 139.234ms
,11-25 08:32:34.044  5603  5649 W jxcore-log: Initializing JXcore engine
,11-25 08:32:34.044  5603  5649 W jxcore-log: JXcore engine is ready
,11-25 08:32:34.064  5649  5649 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11745 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-25 08:32:34.064  5649  5649 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14458]" dev="sockfs" ino=14458 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-25 08:32:34.064  5649  5649 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 08:32:34.064  5649  5649 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32003]" dev="sockfs" ino=32003 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
11-25 08:32:34.076  5603  5649 W jxcore-log: Starting JXcore engine
,11-25 08:32:34.127  5603  5649 W jxcore-log: Platform android
11-25 08:32:34.127  5603  5649 W jxcore-log: 
,11-25 08:32:34.127  5603  5649 W jxcore-log: Process ARCH arm
11-25 08:32:34.127  5603  5649 W jxcore-log: 
,11-25 08:32:34.311  5603  5649 I jxcore-log: JXcore Cordova bridge is ready!
11-25 08:32:34.311  5603  5649 I jxcore-log: 
,11-25 08:32:34.312  5603  5649 W jxcore-log: JXcore engine is started
,11-25 08:32:34.321  5603  5643 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 08:32:34.327  5603  5603 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-25 08:32:34.328  5603  5603 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 08:32:36.468   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:32:36.611   931  5344 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 08:32:37.469   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:32:38.470   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:32:39.471   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:32:40.472   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:32:41.472   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 08:32:44.021  5603  5649 I jxcore-log: 2016-11-25 13:32:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 08:32:44.021  5603  5649 I jxcore-log: 
,11-25 08:32:44.024  5603  5649 I jxcore-log: 2016-11-25 13:32:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 08:32:44.024  5603  5649 I jxcore-log: 
,11-25 08:32:44.030  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 08:32:44.031  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 08:32:44.032  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 08:32:44.033  5603  5649 I jxcore-log: 2016-11-25 13:32:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 08:32:44.033  5603  5649 I jxcore-log: 
11-25 08:32:44.034  5603  5649 I jxcore-log: 2016-11-25 13:32:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 08:32:44.034  5603  5649 I jxcore-log: 
,11-25 08:32:44.277  5603  5649 I jxcore-log: 2016-11-25 13:32:44 - DEBUG UnitTest_app: 'Running unit tests'
11-25 08:32:44.277  5603  5649 I jxcore-log: 
,11-25 08:32:44.278  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 08:32:44.278  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8de8b added. We now have 2 listener(s)
,11-25 08:32:44.279  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:32:44.279  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:32:44.279  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 08:32:44.279  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:32:44.279  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da74b68 added. We now have 2 listener(s)
11-25 08:32:44.279  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:32:44.280  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 08:32:44.281  5603  5649 D executeNativeTests: Running unit tests
,11-25 08:32:44.325  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 08:32:44.325  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 added. We now have 3 listener(s)
11-25 08:32:44.326  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 08:32:44.326  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:32:44.326  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:32:44.326  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:32:44.326  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 added. We now have 3 listener(s)
11-25 08:32:44.326  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:32:44.327  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 08:32:44.329  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 08:32:44.329  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:32:44.329  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:32:44.329  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:32:44.330  5603  5649 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-25 08:32:44.330  5603  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-25 08:32:44.330  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 08:32:44.330  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:32:44.330  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:32:44.331  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:32:44.331  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:32:44.331  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:32:44.331  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:32:44.331  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:32:44.332  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:32:44.332  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:32:44.332  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 removed from the list
,11-25 08:32:44.332  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:44.332  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 removed from the list
11-25 08:32:44.332  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:32:44.332  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.332  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.333  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.333  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:44.333  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.333  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:32:44.333  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:32:44.333  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:44.333  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:44.334  5603  5649 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-25 08:32:44.335  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:32:44.335  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:32:44.335  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:32:44.335  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 08:32:44.335  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:32:44.335  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:32:44.335  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:44.335  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:44.335  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:32:44.335  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.335  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.336  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.336  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.336  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.336  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 08:32:44.336  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:32:44.336  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:44.336  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 08:32:44.339  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 08:32:44.340  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:32:44.340  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:32:44.340  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:32:44.340  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:32:44.340  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 08:32:44.340  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:32:44.340  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:44.340  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:44.340  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:32:44.340  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.340  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.341  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:44.341  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.341  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.341  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:32:44.341  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:32:44.341  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:44.341  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:44.342  5603  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 08:32:44.343  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:32:44.343  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 08:32:44.356  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 08:32:44.359  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 08:32:44.359  5603  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-25 08:32:44.360  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:32:44.360  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 08:32:44.360  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 08:32:44.360  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 08:32:44.361  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 08:32:44.362  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 08:32:44.362  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 08:32:44.362  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 08:32:44.363  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:32:44.365  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:44.365  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 08:32:44.366  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 08:32:44.366  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 08:32:44.366  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 08:32:44.367  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:32:44.367  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-25 08:32:44.369  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 08:32:44.369  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.369  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 08:32:44.369  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 08:32:44.369  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 08:32:44.369  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 08:32:44.369  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.370  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:44.372  4549  4796 D BtGatt.GattService: registerClient() - UUID=285d16b9-5376-4748-a584-9c3f24387d6b
,11-25 08:32:44.372  4549  4637 D BtGatt.GattService: onClientRegistered() - UUID=285d16b9-5376-4748-a584-9c3f24387d6b, clientIf=5
,11-25 08:32:44.373  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 08:32:44.374  4549  4564 D BtGatt.GattService: start scan with filters
11-25 08:32:44.380  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 08:32:44.380  4549  4641 D BtGatt.ScanManager: handling starting scan
11-25 08:32:44.380  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.380  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 08:32:44.381  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.381  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 08:32:44.381  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 08:32:44.381  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.381  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 08:32:44.381  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.381  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 08:32:44.382  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 08:32:44.382  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.382  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.382  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.382  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 08:32:44.383  4549  4641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:32:44.383  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:44.383  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.383  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:44.383  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.384  5603  5649 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 08:32:44.387  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 08:32:44.387  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:32:44.388  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.388  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:44.388  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 08:32:44.392  4549  4637 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 08:32:44.393  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:44.393  4549  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 08:32:44.400  4549  4637 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 08:32:44.400  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:44.400  4549  4641 D BtGatt.ScanManager: Starting BLE batch scan
11-25 08:32:44.401  4549  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 08:32:44.414  4549  4637 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 08:32:44.414  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:44.420  4549  4637 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 08:32:44.420  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:44.890  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 08:32:44.890  5603  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:32:44.891  5603  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 08:32:49.389  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 08:32:49.389  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:32:49.389  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 08:32:49.389  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:32:49.389  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 08:32:49.389  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:32:49.389  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 08:32:49.390  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 08:32:49.390  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.390  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 08:32:49.390  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:32:49.391  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:49.391  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.391  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.391  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 08:32:49.391  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:49.392  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:49.394  4549  4794 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 08:32:49.395  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 08:32:49.397  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:49.397  4549  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 08:32:49.399  4549  4796 D BtGatt.GattService: stopScan() - queue size =1
,11-25 08:32:49.401  4549  4564 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 08:32:49.402  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 08:32:49.402  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.402  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-25 08:32:49.402  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.403  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.403  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:49.403  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:49.404  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 08:32:49.404  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.404  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.405  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.405  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 08:32:49.405  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 08:32:49.406  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:32:49.407  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.407  4549  4549 D BtGatt.ScanManager: awakened up at time 176860
,11-25 08:32:49.409  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:49.409  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:32:49.409  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.410  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:49.410  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:32:49.410  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:32:49.410  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:32:49.410  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:32:49.411  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:32:49.410  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 08:32:49.412  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 08:32:49.412  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.412  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:32:49.412  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 08:32:49.412  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:49.412  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 08:32:49.412  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:49.412  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:32:49.412  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.412  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 08:32:49.412  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.413  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.413  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:32:49.413  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 08:32:49.413  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.416  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.417  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:49.417  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 08:32:49.433  4549  4637 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,11-25 08:32:49.433  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:49.433  4549  4637 D BtGatt.GattService: current time is 176886151002
11-25 08:32:49.434  4549  4637 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -65, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -70, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -67, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -68, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -24, -5, 124, 62, -54, -40, 1, 0, -94, 68, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 122, 81, 97, 3, 0, -25, 27, -109, 28, 108, 27, 28, 6, 8, 116, 105, 110, 53, 52, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 116, -43, -111, -91, -20, -29, 1, -128, -67, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 105, -60, -61, 76, 49, -48, 1, -128, -101, 57, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -74, -74, 121, -71, 29, -72, -103, -116, 36, 80, 97, 3, 3, -25, 23, -109, 57, -93, 4, 0]
11-25 08:32:49.435  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 08:32:49.436  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 08:32:49.436  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 08:32:49.436  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 08:32:49.436  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 08:32:49.437  4549  4637 D BtGatt.GattService: ScanR,ecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 122, 81, 97, 3, 0, -25, 27, -109, 28, 108, 27, 6, 8, 116, 105, 110, 53, 52, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-25 08:32:49.437  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 08:32:49.437  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -74, -74, 121, -71, 29, -72, -103, -116, 36, 80, 97, 3, 3, -25, 23, -109, 57, -93, 4]
11-25 08:32:49.437  4549  4637 E BtGatt.ContextMap: Context not found for ID 5
11-25 08:32:49.445  4549  4637 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 08:32:49.446  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:49.446  4549  4641 D BtGatt.ScanManager: stopping BLe Batch
11-25 08:32:49.452  4549  4637 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 08:32:49.452  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:49.452  4549  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:32:49.458  4549  4637 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:32:49.458  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:49.914  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 08:32:49.936   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 08:32:52.976   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 08:32:53.748   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:32:54.415  5603  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 08:32:54.421  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:32:54.421  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 08:32:54.434  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 08:32:54.439  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 08:32:54.439  5603  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 08:32:54.439  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:32:54.440  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-25 08:32:54.440  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 08:32:54.440  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:32:54.440  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 08:32:54.445  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:32:54.447  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 08:32:54.447  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 08:32:54.447  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 08:32:54.451  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:32:54.455  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:54.455  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 08:32:54.457  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 08:32:54.457  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-25 08:32:54.457  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 08:32:54.463  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:54.463  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-25 08:32:54.463  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 08:32:54.463  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-25 08:32:54.464  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 08:32:54.464  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.465  5603  5649 D BluetoothAdapter: STATE_ON
,11-25 08:32:54.469  4549  4562 D BtGatt.GattService: registerClient() - UUID=99937beb-bbe5-4ace-a5ce-ac4f8746d810
,11-25 08:32:54.469  4549  4637 D BtGatt.GattService: onClientRegistered() - UUID=99937beb-bbe5-4ace-a5ce-ac4f8746d810, clientIf=5
11-25 08:32:54.470  5603  5614 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 08:32:54.470  4549  4773 D BtGatt.GattService: start scan with filters
,11-25 08:32:54.476  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 08:32:54.476  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.476  4549  4641 D BtGatt.ScanManager: handling starting scan
11-25 08:32:54.476  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 08:32:54.476  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.476  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 08:32:54.477  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 08:32:54.477  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.477  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 08:32:54.477  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 08:32:54.477  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.477  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-25 08:32:54.477  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.478  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 08:32:54.481  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-25 08:32:54.481  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.485  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.485  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:32:54.486  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.486  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.486  5603  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-25 08:32:54.486  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.486  4549  4637 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 08:32:54.487  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.487  4549  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 08:32:54.490  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.490  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:32:54.490  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.490  5603  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 08:32:54.490  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.490  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 08:32:54.490  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:32:54.490  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 08:32:54.490  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:32:54.490  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:32:54.491  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 08:32:54.491  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.491  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.491  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 08:32:54.492  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.493  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:54.493  4549  4562 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 08:32:54.494  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 08:32:54.494  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:54.495  4549  4637 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 08:32:54.495  4549  4564 D BtGatt.GattService: stopScan() - queue size =1
11-25 08:32:54.495  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.495  4549  4641 D BtGatt.ScanManager: Starting BLE batch scan
,11-25 08:32:54.495  4549  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 08:32:54.496  4549  4794 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 08:32:54.496  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 08:32:54.497  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.497  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 08:32:54.497  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.497  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.497  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.498  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.498  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 08:32:54.498  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.498  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.498  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.498  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-25 08:32:54.498  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-25 08:32:54.499  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:32:54.499  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:54.503  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.503  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:32:54.503  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.503  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:54.503  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:32:54.503  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:32:54.503  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:32:54.503  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:32:54.503  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 08:32:54.504  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:32:54.504  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.504  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.505  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:32:54.505  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:32:54.505  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:32:54.505  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:54.505  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:32:54.505  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:32:54.505  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 08:32:54.506  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 08:32:54.506  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.507  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.508  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:54.508  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.509  4549  4637 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 08:32:54.509  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.510  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.510  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.510  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.510  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:32:54.510  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:32:54.510  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:32:54.510  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
,11-25 08:32:54.511  5603  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 08:32:54.513  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:32:54.513  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 08:32:54.516  4549  4637 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 08:32:54.516  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:54.517  4549  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 08:32:54.520  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 08:32:54.523  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 08:32:54.523  4549  4637 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:32:54.523  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.523  5603  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 08:32:54.523  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:32:54.523  4549  4637 E BtGatt.ContextMap: Context not found for ID 5
,11-25 08:32:54.523  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 08:32:54.523  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 08:32:54.523  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:32:54.523  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 08:32:54.526  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 08:32:54.526  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 08:32:54.526  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 08:32:54.526  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:32:54.530  4549  4637 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 08:32:54.530  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.530  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.530  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 08:32:54.530  4549  4641 D BtGatt.ScanManager: stopping BLe Batch
11-25 08:32:54.531  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 08:32:54.531  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 08:32:54.531  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 08:32:54.533  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:32:54.535  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.535  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 08:32:54.535  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 08:32:54.535  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 08:32:54.535  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 08:32:54.535  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.538  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:54.537  4549  4637 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 08:32:54.538  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.538  4549  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 08:32:54.540  4549  4562 D BtGatt.GattService: registerClient() - UUID=33892a62-cb99-436f-84e2-08e5aaf100f3
11-25 08:32:54.540  4549  4637 D BtGatt.GattService: onClientRegistered() - UUID=33892a62-cb99-436f-84e2-08e5aaf100f3, clientIf=5
11-25 08:32:54.540  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 08:32:54.541  4549  4773 D BtGatt.GattService: start scan with filters
,11-25 08:32:54.543  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 08:32:54.543  4549  4637 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:32:54.543  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.543  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.543  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 08:32:54.543  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.543  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 08:32:54.544  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 08:32:54.544  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.544  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 08:32:54.544  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 08:32:54.544  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.544  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.544  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.544  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.545  4549  4641 D BtGatt.ScanManager: handling starting scan
11-25 08:32:54.545  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 08:32:54.545  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:54.547  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.548  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:32:54.548  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.548  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:54.548  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.548  5603  5649 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 08:32:54.550  4549  4637 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 08:32:54.550  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:54.551  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.551  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 08:32:54.551  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:54.551  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:32:54.551  4549  4641 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 08:32:54.556  4549  4637 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 08:32:54.556  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:54.556  4549  4641 D BtGatt.ScanManager: Starting BLE batch scan
11-25 08:32:54.556  4549  4641 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 08:32:54.564  4549  4637 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 08:32:54.564  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:54.569  4549  4637 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 08:32:54.569  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:32:55.052  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-25 08:32:55.053  5603  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 08:32:55.053  5603  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 08:32:55.994   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 08:32:55.999   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-25 08:32:59.019   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 08:32:59.024   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-25 08:32:59.548  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 08:32:59.549  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:32:59.549  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 08:32:59.549  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 08:32:59.549  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-25 08:32:59.549  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 08:32:59.550  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 08:32:59.550  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-25 08:32:59.550  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:59.550  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 08:32:59.550  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:32:59.551  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:59.551  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.551  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.551  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 08:32:59.552  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.554  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:59.554  4549  4562 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 08:32:59.555  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 08:32:59.556  4549  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:32:59.557  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:32:59.558  4549  4794 D BtGatt.GattService: stopScan() - queue size =1
11-25 08:32:59.560  4549  4564 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 08:32:59.561  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 08:32:59.561  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.562  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 08:32:59.562  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.562  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.562  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.562  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.563  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 08:32:59.563  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-25 08:32:59.563  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.563  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.563  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 08:32:59.564  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 08:32:59.564  4549  4549 D BtGatt.ScanManager: awakened up at time 187017
11-25 08:32:59.565  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 08:32:59.565  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.567  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.568  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:32:59.568  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.568  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:32:59.569  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:32:59.569  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:32:59.569  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 08:32:59.569  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.570  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 08:32:59.570  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 08:32:59.570  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.570  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-25 08:32:59.570  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.570  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:32:59.571  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.571  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.572  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.572  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:32:59.573  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 08:32:59.586  4549  4637 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-25 08:32:59.586  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:59.586  4549  4637 D BtGatt.GattService: current time is 187039610717
11-25 08:32:59.587  4549  4637 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -75, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 50, -35, 86, -77, -92, -11, 1, 0, -93, 84, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 94, 85, 97, 3, 2, -33, 21, -106, -8, -85, 51, 28, 6, 8, 116, 105, 110, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -68, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -67, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 08:32:59.588  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 08:32:59.588  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 08:32:59.588  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-25 08:32:59.589  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 94, 85, 97, 3, 2, -33, 21, -106, -8, -85, 51, 6, 8, 116, 105, 110, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-25 08:32:59.589  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 08:32:59.589  4549  4637 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 08:32:59.590  4549  4637 E BtGatt.ContextMap: Context not found for ID 5
,11-25 08:32:59.595  4549  4637 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 08:32:59.596  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:59.596  4549  4641 D BtGatt.ScanManager: stopping BLe Batch
,11-25 08:32:59.602  4549  4637 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 08:32:59.602  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:32:59.602  4549  4641 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 08:32:59.608  4549  4637 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 08:32:59.608  4549  4637 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:33:00.071  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 08:33:00.071  5603  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:00.071  5603  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 08:33:01.474   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:02.475   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:03.476   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:04.478   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:04.569  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 08:33:04.570  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:33:04.570  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 08:33:04.570  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 08:33:04.570  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:33:04.571  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:33:04.571  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 08:33:04.571  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.571  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:04.571  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.571  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:04.572  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 08:33:04.575  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.576  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.580  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.582  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.582  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.582  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.582  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.582  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:04.583  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.584  5603  5649 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-25 08:33:04.586  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.586  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:33:04.586  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.586  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.587  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.587  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
,11-25 08:33:04.587  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.587  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.587  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.587  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.588  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.591  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.592  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.592  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.592  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 08:33:04.592  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.592  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.592  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
,11-25 08:33:04.593  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-25 08:33:04.593  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.594  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:04.594  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.594  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.594  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.594  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.594  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.594  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
,11-25 08:33:04.594  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.594  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.594  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.596  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.596  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.596  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.596  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.596  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.596  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.596  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.597  5603  5649 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 08:33:04.597  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.598  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:33:04.598  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.598  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.598  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.598  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.598  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.598  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.598  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:04.598  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.598  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.600  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.600  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.600  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.600  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.600  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 08:33:04.600  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.600  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.601  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 08:33:04.601  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 08:33:04.601  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:33:04.601  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.601  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.601  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.601  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
,11-25 08:33:04.601  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.602  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.602  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.602  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.602  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.603  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.603  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.603  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.603  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.603  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 08:33:04.603  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.604  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.604  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 08:33:04.605  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:33:04.605  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:33:04.605  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-25 08:33:04.605  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:33:04.605  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:33:04.605  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 08:33:04.605  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:33:04.605  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 08:33:04.605  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 08:33:04.605  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:04.605  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.605  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.606  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.606  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.606  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.606  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.606  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.606  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.606  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.608  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.608  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.608  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.608  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.608  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.608  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:04.608  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.609  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 08:33:04.609  5603  5649 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 08:33:04.609  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 08:33:04.612  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-25 08:33:04.612  5603  5649 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 08:33:04.612  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 08:33:04.612  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 08:33:04.612  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 08:33:04.613  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 08:33:04.614  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 08:33:04.614  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 08:33:04.614  5603  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 08:33:04.614  5603  5649 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 08:33:04.615  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-25 08:33:04.615  5603  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 08:33:04.615  5603  5649 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-25 08:33:04.615  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 08:33:04.615  5603  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 08:33:04.615  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-25 08:33:04.619  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-25 08:33:04.620  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 08:33:04.620  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 08:33:04.621  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-25 08:33:04.621  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 08:33:04.621  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 08:33:04.621  5603  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 08:33:04.621  5603  5649 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 08:33:04.621  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-25 08:33:04.622  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-25 08:33:04.622  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-25 08:33:04.622  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 08:33:04.622  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.622  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:04.622  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.622  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 08:33:04.622  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.622  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-25 08:33:04.623  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.623  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.623  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.624  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:04.625  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.625  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.625  5603  5650 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-25 08:33:04.625  5603  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-25 08:33:04.625  5603  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 08:33:04.625  5603  5650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 08:33:04.625  5603  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-25 08:33:04.625  5603  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
,11-25 08:33:04.624  4773  4773 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32061]" dev="sockfs" ino=32061 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 08:33:04.624  4773  4773 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32061]" dev="sockfs" ino=32061 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 08:33:04.628  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.628  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.628  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.628  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.628  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.628  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.628  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.629  5603  5649 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 08:33:04.630  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.630  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:04.630  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.630  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.630  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 08:33:04.630  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.631  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.631  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.631  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.631  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.631  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.631  5603  5650 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-25 08:33:04.632  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 08:33:04.632  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-25 08:33:04.632  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:04.632  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.632  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.632  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:04.632  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.632  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.632  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.633  5603  5649 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-25 08:33:04.633  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.633  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:04.633  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 08:33:04.633  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.633  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.634  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.634  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.634  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.634  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.634  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.634  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.635  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.635  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.635  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.635  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 08:33:04.635  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.635  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.635  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.636  5603  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 08:33:04.636  5603  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 08:33:04.636  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 08:33:04.636  5603  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 08:33:04.636  5603  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 08:33:04.636  5603  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 08:33:04.636  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-25 08:33:04.636  5603  5649 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 08:33:04.636  5603  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 08:33:04.636  5603  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 08:33:04.636  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 08:33:04.636  5603  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 08:33:04.636  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:04.637  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:04.637  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:04.637  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.637  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 08:33:04.637  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.637  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.637  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.637  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:04.637  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.637  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.638  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.638  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.638  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:04.638  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 08:33:04.638  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:04.638  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.638  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.639  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:04.639  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:04.639  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:04.639  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:04.639  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:04.639  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:05.479   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:06.480   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 08:33:08.104   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 08:33:08.651   931  5344 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 08:33:09.640  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:09.640  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.641  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:09.641  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:09.641  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
,11-25 08:33:09.641  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:09.641  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:09.642  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:09.642  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 08:33:09.642  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:09.642  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:09.642  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.642  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
,11-25 08:33:09.643  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:09.643  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.643  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.646  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.646  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.646  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.647  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 08:33:09.647  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 08:33:09.647  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:09.647  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.651  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-25 08:33:09.652  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:33:09.652  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 08:33:09.659  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-25 08:33:09.660  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-25 08:33:09.660  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-25 08:33:09.660  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 08:33:09.660  5603  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-25 08:33:09.661  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-25 08:33:09.661  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 08:33:09.661  5603  5603 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-25 08:33:09.661  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 08:33:09.661  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-25 08:33:09.661  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 08:33:09.661  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 08:33:09.661  5603  5652 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:09.662  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 08:33:09.662  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 08:33:09.662  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-25 08:33:09.663  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:09.663  5603  5603 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 08:33:09.663  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.663  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 08:33:09.663  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.663  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 08:33:09.663  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:33:09.663  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.664  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.664  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:33:09.664  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.665  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.665  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
,11-25 08:33:09.665  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:33:09.665  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:09.665  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:33:09.665  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 08:33:09.665  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:33:09.665  5603  5652 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 08:33:09.665  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:09.665  5603  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-25 08:33:09.665  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 08:33:09.665  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 08:33:09.665  5603  5652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 08:33:09.665  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:09.665  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.665  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.665  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:09.666  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.666  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.666  5603  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-25 08:33:09.666  5603  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:09.661  4794  4794 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32063]" dev="sockfs" ino=32063 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 08:33:09.667  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.667  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.661  4794  4794 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32063]" dev="sockfs" ino=32063 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 08:33:09.667  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.667  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:09.667  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:09.667  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.668  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.669  5603  5649 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-25 08:33:09.669  5603  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 08:33:09.669  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-25 08:33:09.669  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:33:09.670  5603  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 08:33:09.671  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:09.671  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:09.671  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:09.671  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:09.671  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:09.672  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
,11-25 08:33:09.672  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.672  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.672  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:09.672  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.672  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.674  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.674  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.674  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.674  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:09.674  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:09.674  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:09.674  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
,11-25 08:33:09.679  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 08:33:09.679  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:09.679  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:09.679  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:09.679  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:09.679  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:09.680  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.680  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.680  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:09.680  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.680  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.681  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.681  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.681  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.681  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 08:33:09.681  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 08:33:09.681  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.681  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.682  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:09.682  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:09.682  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 08:33:09.682  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:09.682  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:09.682  5603  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c6f1 not in the list
11-25 08:33:09.682  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.683  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.683  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:09.683  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.683  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.684  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:09.684  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.684  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:09.684  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:09.684  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:09.684  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:09.684  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d252d6 not in the list
11-25 08:33:09.685  5603  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-25 08:33:09.685  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-25 08:33:09.685  5603  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-25 08:33:09.685  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 08:33:09.685  5603  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 08:33:09.686  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 08:33:09.688  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 08:33:09.688  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-25 08:33:09.689  5603  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-25 08:33:09.689  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 08:33:09.689  5603  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 08:33:09.689  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 08:33:09.689  5603  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-25 08:33:09.689  5603  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-25 08:33:09.689  5603  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-25 08:33:09.689  5603  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 08:33:09.690  5603  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-25 08:33:09.690  5603  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 08:33:09.690  5603  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 08:33:09.690  5603  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-25 08:33:09.691  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:09.691  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a769647 added. We now have 3 listener(s)
11-25 08:33:09.691  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:33:09.693  5603  5649 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 08:33:09.693   931  3767 D WifiService: setWifiEnabled: true pid=5603, uid=10077
11-25 08:33:09.693   931  3767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 08:33:09.755  4549  4753 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-25 08:33:09.755  4549  4766 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-25 08:33:10.166  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 08:33:11.132   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 08:33:13.752   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:33:14.698  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:14.698  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@831ce74 added. We now have 4 listener(s)
11-25 08:33:14.699  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:14.710  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:14.710  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@831ce74 removed from the list
11-25 08:33:14.711  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:14.712  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:33:14.712  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd46f9d added. We now have 4 listener(s)
11-25 08:33:14.713  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:14.716  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:14.717  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd46f9d removed from the list
11-25 08:33:14.717  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:14.719  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:33:14.719  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e38c12 added. We now have 4 listener(s)
,11-25 08:33:14.720  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:14.727   931  5156 D WifiService: setWifiEnabled: false pid=5603, uid=10077
11-25 08:33:14.727   931  5156 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 08:33:14.732   931  2926 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 08:33:14.732   931  2926 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 08:33:14.732   931  2926 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 08:33:14.733   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:14.738  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:33:14.738  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 08:33:14.742  4549  4633 D BluetoothAdapterState: Current state: ON, message: 23
11-25 08:33:14.743  4549  4633 D BluetoothAdapterProperties: Setting state to 13
11-25 08:33:14.743  4549  4633 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 08:33:14.744  4549  4633 D BluetoothAdapterProperties: onBluetoothDisable()
,11-25 08:33:14.744  4549  4633 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:14.745  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 08:33:14.745  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 08:33:14.746  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:14.746  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 08:33:14.746  4549  4637 D BluetoothAdapterProperties: Scan Mode:20
,11-25 08:33:14.746  5603  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 08:33:14.747  4549  4633 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 08:33:14.748   931  5345 D DhcpClient: Clearing IP address
11-25 08:33:14.749   509   928 D CommandListener: Clearing all IP addresses on wlan0
11-25 08:33:14.750  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:14.752  4549  4549 D HeadsetService: Received stop request...Stopping profile...
11-25 08:33:14.754   931   931 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:14.754  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:14.754   931   931 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:14.754   931   931 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:14.755  3753  3776 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:14.755  3083  3096 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:14.755  4549  4549 D A2dpService: Received stop request...Stopping profile...
11-25 08:33:14.755  3083  3083 D HeadsetProfile: Bluetooth service disconnected
11-25 08:33:14.756  4549  4776 D A2dpStateMachine: Exit Disconnected: -1
11-25 08:33:14.757   509   928 D CommandListener: Setting iface cfg
11-25 08:33:14.758   931   931 D BluetoothA2dp: Proxy object disconnected
11-25 08:33:14.758  3083  3083 D BluetoothA2dp: Proxy object disconnected
11-25 08:33:14.758  4549  4549 V BluetoothAdapterState: isTurningOff()=true
,11-25 08:33:14.758  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.758  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.759  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.760   931  5346 D DhcpClient: Receive thread stopped
11-25 08:33:14.761  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:14.762  3529  5399 V NativeCrypto: Read error: ssl=0x7f75285700: I/O error during system call, Connection timed out
,11-25 08:33:14.764  3529  5399 V NativeCrypto: SSL shutdown failed: ssl=0x7f75285700: I/O error during system call, Broken pipe
11-25 08:33:14.766   931  3369 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 08:33:14.766  4549  4549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 08:33:14.766   931  5343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-25 08:33:14.766  4549  4549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 08:33:14.767  4549  4753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:14.767  4549  4753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:14.767  4549  4753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:14.767  4549  4637 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 08:33:14.767  4549  4637 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 08:33:14.770   931  5343 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-25 08:33:14.770   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-25 08:33:14.770   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 08:33:14.772   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 08:33:14.773  4549  4549 D HidService: Received stop request...Stopping profile...
,11-25 08:33:14.773  4549  4549 D HidService: Stopping Bluetooth HidService
11-25 08:33:14.774  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:14.774  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.774  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.774  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.774  3083  3083 D BluetoothInputDevice: Proxy object disconnected
11-25 08:33:14.774  3083  3083 D HidProfile: Bluetooth service disconnected
,11-25 08:33:14.777  4549  4753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:14.777  4549  4753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 08:33:14.777  4549  4637 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 08:33:14.777   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 08:33:14.777  4549  4753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 08:33:14.777  4549  4753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 08:33:14.777  4549  4753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 08:33:14.777  4549  4753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 08:33:14.778  4549  4549 D HealthService: Received stop request...Stopping profile...
11-25 08:33:14.778   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-25 08:33:14.779   535   535 E Parcel  : Reading a NULL string not supported here.
11-25 08:33:14.779  4549  4549 D PanService: Received stop request...Stopping profile...
,11-25 08:33:14.783   931   931 D RttService: SCAN_AVAILABLE : 1
11-25 08:33:14.783  4549  4549 D BluetoothMapService: Received stop request...Stopping profile...
11-25 08:33:14.783  4549  4549 D BluetoothMapService: stop()
11-25 08:33:14.783   931  3036 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 08:33:14.783  4549  4549 D BluetoothMapAppObserver: deinitObservers()
11-25 08:33:14.783  4549  4549 D BluetoothMapAppObserver: removeReceiver()
11-25 08:33:14.785  4549  4549 D SapService: Received stop request...Stopping profile...
11-25 08:33:14.785  4549  4549 V SapService: stop()
,11-25 08:33:14.786  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:14.786  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.786  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.786  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.786   931  2928 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 08:33:14.786  4549  4549 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 08:33:14.786  4549  4549 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 08:33:14.787  4549  4637 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 08:33:14.787  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:14.787  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.787  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.787  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.787  4549  4549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 08:33:14.787  3728  3867 W QCNEJ   : |CORE| network lost: 100
11-25 08:33:14.788  4549  4549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 08:33:14.788  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:14.788  3728  3867 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 08:33:14.788  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.788  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.788  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.788  4549  4549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 08:33:14.788  4549  4549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 08:33:14.788  4549  4637 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 08:33:14.789  4549  4549 D BluetoothMapService: MAP Service closeService in
11-25 08:33:14.789  4549  4549 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 08:33:14.789  4549  4549 D ObexServerSockets0: shutdown(block = true)
11-25 08:33:14.790  4549  4549 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 08:33:14.790  4549  4808 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-25 08:33:14.790  4549  4766 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 08:33:14.791  4549  4809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-25 08:33:14.790  4549  4549 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 08:33:14.791  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:14.791  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.791  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.791  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.792  4549  4549 D BluetoothMapService: cleanup()
11-25 08:33:14.792  4549  4549 D BluetoothMapService: MAP Service closeService in
11-25 08:33:14.793  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:14.793  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:14.793  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:14.793  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:14.793  4549  4633 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 08:33:14.793  4549  4633 D BluetoothAdapterProperties: Setting state to 15
11-25 08:33:14.793  4549  4633 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-25 08:33:14.794  4549  4633 I BluetoothAdapterState: Entering BleOnState
11-25 08:33:14.794  3083  3083 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 08:33:14.794  3083  3083 D PanProfile: Bluetooth service disconnected
11-25 08:33:14.794  3083  3083 D BluetoothMap: Proxy object disconnected
11-25 08:33:14.794  3083  3083 D MapProfile: Bluetooth service disconnected
11-25 08:33:14.796  4549  4549 I BtOppRfcommListener: stopping Accept Thread
11-25 08:33:14.796  4549  5259 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 08:33:14.796  4549  5259 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-25 08:33:14.805  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:14.805  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 08:33:14.805  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 08:33:14.805  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 08:33:14.812   931   944 I ActivityManager: Start proc 5661:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-25 08:33:14.813  3083  3095 D BluetoothPan: onBluetoothStateChange on: false
,11-25 08:33:14.814  3083  3930 D BluetoothPbap: onBluetoothStateChange: up=false
,11-25 08:33:14.815   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:14.815   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 08:33:14.815  3083  3095 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 08:33:14.816  3083  3930 D BluetoothMap: onBluetoothStateChange: up=false
,11-25 08:33:14.816  3083  3096 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 08:33:14.818   931  2926 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 08:33:14.818  3083  3095 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:14.819  3753  3776 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:14.819   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 08:33:14.819   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:14.819   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:14.819  4549  4633 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 08:33:14.820  4549  4633 D BluetoothAdapterProperties: Setting state to 16
11-25 08:33:14.820  4549  4633 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 08:33:14.822  4549  4633 D BluetoothAdapterProperties: onBleDisable
11-25 08:33:14.822  4549  4633 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:14.822  4549  4634 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 08:33:14.824  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:14.824  4549  4637 D BluetoothAdapterProperties: Scan Mode:20
11-25 08:33:14.825   931  2926 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 08:33:14.831  4549  4753 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 08:33:14.831  4549  4753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 08:33:14.833  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:14.847   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 08:33:14.847   509   928 D CommandListener: Clearing all IP addresses on wlan0
11-25 08:33:14.847   509   928 D TetherController: Setting IP forward enable = 0
,11-25 08:33:14.849   931  2928 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 08:33:14.850   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 08:33:14.851   931  2926 D DhcpClient: doQuit
11-25 08:33:14.851   931  2926 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 08:33:14.851   931  5345 D DhcpClient: onQuitting
11-25 08:33:14.852  3410  3410 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 08:33:14.854   931   948 D Tethering: MasterInitialState.processMessage what=3
11-25 08:33:14.858  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:14.858  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 08:33:14.858  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:14.858  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 08:33:14.859  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:14.862  5247  5247 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dc07946 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-25 08:33:14.868  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 08:33:14.868  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 08:33:14.868  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 08:33:14.868  5010  5033 E SarControlService: no key has been found,reset the power
11-25 08:33:14.868  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 08:33:14.868  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 08:33:14.869  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 08:33:14.869  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:33:14.870  5035  5035 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 08:33:14.871  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 08:33:14.871  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 08:33:14.871  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 08:33:14.872  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:33:14.872  5035  5035 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 08:33:14.877  3410  3410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-25 08:33:14.877  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000ea03000000000000ffffffff]
11-25 08:33:14.877  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:33:14.877  5035  5049 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 08:33:14.877  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:33:14.878  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 08:33:14.882  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000eb03000000000000ffffffff]
11-25 08:33:14.883  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:33:14.883  5035  5049 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-25 08:33:14.883  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 08:33:14.884  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 08:33:14.886  3410  3410 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 08:33:14.894  5661  5661 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-25 08:33:14.905  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 08:33:14.906   509   928 E Netd    : netlink response contains error (No such file or directory)
,11-25 08:33:14.907   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 08:33:14.908   509   928 D TetherController: Setting IP forward enable = 0
,11-25 08:33:14.910   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fa817f:true
,11-25 08:33:14.911  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 08:33:14.923   931   942 I ActivityManager: Start proc 5688:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-25 08:33:14.928  3410  3410 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 08:33:14.935  3410  3410 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-25 08:33:14.939  5661  5661 D LocalBluetoothProfileManager: Adding local MAP profile
11-25 08:33:14.941  5661  5661 D BluetoothMap: Create BluetoothMap proxy object
,11-25 08:33:14.950  5661  5661 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 08:33:14.962  5688  5688 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-25 08:33:14.965  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 08:33:14.973   931  3369 I ActivityManager: Killing 4950:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-25 08:33:15.038  4985  4985 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 08:33:15.038   931  2926 D wifi    : In wifi stop Hal
11-25 08:33:15.038   931  2926 D wifi    : halHandle = 0x7f5ef2d300, mVM = 0x7f7b54d140, mCls = 0x100a02
,11-25 08:33:15.038   931  3408 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 08:33:15.039   931  3408 D WifiHAL : Got a signal to exit!!!
,11-25 08:33:15.039   931  3408 I WifiHAL : Exit wifi_event_loop
11-25 08:33:15.040   931  2926 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-25 08:33:15.040   931  2926 E WifiHAL : Event processing terminated
11-25 08:33:15.040   931  2926 D wifi    : In wifi cleaned up handler
11-25 08:33:15.040   931  2926 I WifiHAL : Internal cleanup completed
11-25 08:33:15.040  4549  4637 I bt_hci  : shut_down
11-25 08:33:15.042  4062  4184 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 08:33:15.045  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:15.046  4549  4643 D bt_hwcfg: hw_epilog_process
11-25 08:33:15.046  4549  4643 I bt_vendor: low_power_mode_cb
,11-25 08:33:15.049  4549  4643 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-25 08:33:15.050  4549  4643 I bt_vendor: epilog_cb
11-25 08:33:15.050  4549  4643 I bt_hci  : epilog_finished_callback
,11-25 08:33:15.052  4549  4637 I bt_hci_h4: hal_close
,11-25 08:33:15.053  4549  4637 I bt_userial_vendor: device fd = 54 close
,11-25 08:33:15.062   931  3408 D wifi    : set interface wlan0 flags (DOWN)
,11-25 08:33:15.062   931  2926 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 08:33:15.161  4549  4634 D bt_stack_manager: event_shut_down_stack finished.
,11-25 08:33:15.161  4549  4633 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 08:33:15.163  4549  4549 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 08:33:15.163  4549  4633 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 08:33:15.163  4549  4549 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 08:33:15.163  4549  4549 D BtGatt.GattService: stop()
11-25 08:33:15.163  4549  4549 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 08:33:15.164  5688  5688 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.164  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  4549  4549 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:15.165  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:15.165  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 08:33:15.165  5688  ,5688 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  4549  4549 V BluetoothAdapterState: isBleTurningOff()=true
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  4549  4633 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.k.d(PG:583)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  4549  4633 D BluetoothAdapterProperties: Setting state to 10
11-25 08:33:15.165  4549  4633 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.165  5688  5688 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:33:15.165  5688  5688 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:33:15.166  4549  4633 I BluetoothAdapterState: Entering OffState
11-25 08:33:15.166   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-25 08:33:15.175  4549  4549 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-25 08:33:15.175  4549  4549 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 08:33:15.175  4549  4549 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 08:33:15.176  4549  4634 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 08:33:15.178  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 08:33:15.184  4549  4549 I art     : System.exit called, status: 0
11-25 08:33:15.185  4549  4549 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-25 08:33:15.188  5661  5661 D DockEventReceiver: finishStartingService: stopping service
11-25 08:33:15.190   931  3767 I ActivityManager: Killing 5373:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-25 08:33:15.228   931   942 I ActivityManager: Process com.android.bluetooth (pid 4549) has died
11-25 08:33:15.231  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 08:33:15.243   931  3733 I ActivityManager: Start proc 5720:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,11-25 08:33:15.264   931   948 D Tethering: InitialState.processMessage what=4
,11-25 08:33:15.266   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 08:33:15.299  5720  5720 D AdapterServiceConfig: Adding HeadsetService
,11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding A2dpService
11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding HidService
11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding HealthService
11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding PanService
,11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding GattService
11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding BluetoothMapService
11-25 08:33:15.300  5720  5720 D AdapterServiceConfig: Adding SapService
11-25 08:33:15.304   931  3767 I ActivityManager: Killing 5386:com.android.chrome/u0a39 (adj 15): empty #17
,11-25 08:33:15.340  3677  3677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 08:33:15.343  3677  3677 D SystemUpdateService: onCreate
,11-25 08:33:15.346  3677  3677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 08:33:15.352  3677  3677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 08:33:15.359  3677  5370 I iu.UploadsManager: num queued entries: 0
,11-25 08:33:15.359  3677  5370 I iu.UploadsManager: num updated entries: 0
11-25 08:33:15.360  3677  5370 I iu.SyncManager: NEXT; no task
,11-25 08:33:15.361  3677  5732 I SystemUpdateService: active receiver: enabled
,11-25 08:33:15.368  3677  3677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 08:33:15.369  3677  3677 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 08:33:15.375  3677  5732 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 08:33:15.380  3677  5732 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 08:33:15.380  3677  5732 I SystemUpdateService: now status is 0 (complete)
11-25 08:33:15.380  3677  5732 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 08:33:15.380  3677  5732 I SystemUpdateService: file has been verified
11-25 08:33:15.380  3677  5732 I SystemUpdateService: OTA package size = 21989297
11-25 08:33:15.382   931  3368 I ActivityManager: Start proc 5734:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-25 08:33:15.400  3677  5732 I SystemUpdateService: showing system update notification
,11-25 08:33:15.416  5734  5734 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-25 08:33:15.420  5734  5734 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 08:33:15.429  5734  5734 D SprintDMHelper: simOperator: 
11-25 08:33:15.429  5734  5734 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 08:33:15.440   931  3369 I ActivityManager: Start proc 5746:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-25 08:33:15.456  3677  3677 D SystemUpdateService: onDestroy
,11-25 08:33:15.458   931  3369 I ActivityManager: Killing 5403:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-25 08:33:15.558  4985  5760 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 08:33:15.563   931   942 I ActivityManager: Start proc 5761:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-25 08:33:15.566   931  3733 I ActivityManager: Killing 5247:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 08:33:15.591  5688  5714 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-25 08:33:15.618  5761  5761 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-25 08:33:15.636   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9819ac:true
,11-25 08:33:15.811   931  3800 I ActivityManager: Killing 5455:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-25 08:33:15.847   931   941 I ActivityManager: Start proc 5775:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 08:33:15.877  5775  5775 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 08:33:15.885   931  3368 I ActivityManager: Killing 4647:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 08:33:19.749   931  3733 D WifiService: setWifiEnabled: true pid=5603, uid=10077
,11-25 08:33:19.749   931  3733 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 08:33:19.757   509   928 D SoftapController: Softap fwReload - Ok
,11-25 08:33:19.764   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:19.764   509   928 D CommandListener: Trying to bring down wlan0
11-25 08:33:19.766   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 08:33:19.771   931  2926 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 08:33:20.345   931  2926 D wifi    : set interface wlan0 flags (UP)
,11-25 08:33:20.348   931  2926 I WifiHAL : Initializing wifi
,11-25 08:33:20.348   931  2926 I WifiHAL : Creating socket
,11-25 08:33:20.350   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 08:33:20.352   931  2926 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-25 08:33:20.353   931  2926 D wifi    : Did set static halHandle = 0x7f5ef2d300
11-25 08:33:20.353   931  2926 D wifi    : halHandle = 0x7f5ef2d300, mVM = 0x7f7b54d140, mCls = 0x1946
11-25 08:33:20.353   931  2926 D wifi    : array field set
11-25 08:33:20.353   931  2926 I WifiNative-HAL: interface[0] = wlan0
11-25 08:33:20.355   931  5793 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547053818624
11-25 08:33:20.356   931  5793 D wifi    : waitForHalEvents called, vm = 0x7f7b54d140, obj = 0x1946, env = 0x7f5cd3c480
,11-25 08:33:20.428  5794  5794 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 08:33:20.440  5794  5794 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 08:33:20.449  5794  5794 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 08:33:20.449  5794  5794 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 08:33:20.457   931  2926 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 08:33:20.459  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:20.464   931  2926 D WifiConfigStore: Loading config and enabling all networks 
,11-25 08:33:20.465  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:20.465  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 08:33:20.465  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:20.465  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 08:33:20.472   931  2926 D WifiConfigStore: loaded 0 passpoint configs
11-25 08:33:20.472   931  2926 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 08:33:20.472   931  2926 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 08:33:20.473   931  2926 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 08:33:20.474   931  2926 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 08:33:20.474   931  2926 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-25 08:33:20.474   931  2926 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-25 08:33:20.474   931  2926 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 08:33:20.476   931  2926 D WifiNative-HAL: Setting external_sim to 1
,11-25 08:33:20.476   931  2926 D wifi    : setting dfs flag to true, 0x7f60c3e600
,11-25 08:33:20.476  4985  4985 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 08:33:20.477   931  2926 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 08:33:20.477   931  2926 D wifi    : setting scan oui 0x7f60c3e600
11-25 08:33:20.477   931  2926 D WifiHAL : Sending mac address OUI
,11-25 08:33:20.480   931  2926 E native  : do suspend false
,11-25 08:33:20.486   931  2926 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-25 08:33:20.487   931   931 D RttService: SCAN_AVAILABLE : 3
11-25 08:33:20.487   931  3036 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 08:33:20.491   509   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 08:33:20.492   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:20.492   931  2925 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-25 08:33:20.492   931  2925 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 08:33:20.501   931  2925 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 08:33:20.506   931  2925 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-25 08:33:20.506   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=207959 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-25 08:33:23.558  5794  5794 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 08:33:23.564  5794  5794 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 08:33:23.569  5794  5794 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 08:33:23.616   931  2926 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 08:33:23.618   931  2926 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-25 08:33:23.618   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:23.630   931  2926 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 08:33:23.664   931  2926 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 08:33:23.665  5794  5794 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 08:33:24.100  5794  5794 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 08:33:24.146  5794  5794 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 08:33:24.147  5794  5794 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 08:33:24.156   931  2926 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 08:33:24.156   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 08:33:24.156   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 08:33:24.171   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:24.182   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:24.188   931  2926 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 08:33:24.194   931  5802 D DhcpClient: Receive thread started
,11-25 08:33:24.198   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 08:33:24.198   931  2926 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 08:33:24.198   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 08:33:24.278   931  2926 E native  : do suspend false
,11-25 08:33:24.286   931  5801 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 08:33:24.303   931  5802 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172630, domain null
,11-25 08:33:24.304   931  5801 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172630 seconds
11-25 08:33:24.305   931  5801 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-25 08:33:24.329   931  5802 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 08:33:24.330   931  5801 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 08:33:24.334   509   928 D CommandListener: Setting iface cfg
11-25 08:33:24.339   931  2926 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 08:33:24.345   931  5801 D DhcpClient: Scheduling renewal in 86399s
,11-25 08:33:24.354   931  2926 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 08:33:24.355   931  2926 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 08:33:24.356   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 08:33:24.359   931  2926 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 08:33:24.363   931  2928 D ConnectivityService: Adding iface wlan0 to network 101
,11-25 08:33:24.398   931  2928 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 08:33:24.399   931  2928 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 08:33:24.400   931  2928 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 08:33:24.402   931  2928 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 08:33:24.403   931  2928 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 08:33:24.409   931  2928 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 08:33:24.413   931  2928 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-25 08:33:24.413   931  2928 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-25 08:33:24.413   931  2928 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 08:33:24.413   931  2926 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-25 08:33:24.413   931  2928 D ConnectivityService:    accepting network in place of null
,11-25 08:33:24.413   931  2926 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 08:33:24.414   931  2928 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 08:33:24.429   931  5800 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211882, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 08:33:24.436   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 08:33:24.458   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 08:33:24.462   931  2928 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 08:33:24.462  3728  3867 W QCNEJ   : |CORE| network available: 101
11-25 08:33:24.462   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 08:33:24.463   931  2928 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-25 08:33:24.466  3728  3867 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-25 08:33:24.467   931   948 D Tethering: MasterInitialState.processMessage what=3
11-25 08:33:24.467  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 08:33:24.467  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 08:33:24.467  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:24.467  3728  3867 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-25 08:33:24.467  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 08:33:24.468  3728  3867 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 08:33:24.476  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 08:33:24.476  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 08:33:24.476  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 08:33:24.476  5010  5033 E SarControlService: no key has been found,reset the power
11-25 08:33:24.476  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 08:33:24.477  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 08:33:24.477  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 08:33:24.477  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:33:24.477  5035  5035 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 08:33:24.478  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 08:33:24.478  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 08:33:24.479  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 08:33:24.479  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:33:24.479  5035  5035 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 08:33:24.481  3677  3677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 08:33:24.484  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000ec03000000000000ffffffff]
11-25 08:33:24.484  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:33:24.484  5035  5049 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 08:33:24.484  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:33:24.484  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 08:33:24.485  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000ed03000000000000ffffffff]
11-25 08:33:24.485  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-25 08:33:24.485  5035  5049 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-25 08:33:24.486  3677  3677 D SystemUpdateService: onCreate
11-25 08:33:24.486  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:33:24.487  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 08:33:24.490  3677  3677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 08:33:24.492   931  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 08:33:24.501  3677  3677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 08:33:24.507  3677  5370 I iu.UploadsManager: num queued entries: 0
,11-25 08:33:24.509  3677  5812 I SystemUpdateService: active receiver: enabled
,11-25 08:33:24.511  3677  3677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 08:33:24.512  3677  3677 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 08:33:24.514  5734  5734 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 08:33:24.519  5734  5734 D SprintDMHelper: simOperator: 
11-25 08:33:24.519  5734  5734 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 08:33:24.539  3677  5370 I iu.UploadsManager: num updated entries: 0
,11-25 08:33:24.544  3677  5812 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 08:33:24.548   931  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 13:33:24 GMT], X-Android-Received-Millis=[1480080804547], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480080804517]}
,11-25 08:33:24.548   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 08:33:24.548   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-25 08:33:24.548   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-25 08:33:24.549   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 08:33:24.540  3677  5370 I iu.SyncManager: NEXT; no task
11-25 08:33:24.558  3677  5812 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-25 08:33:24.558  3677  5812 I SystemUpdateService: now status is 0 (complete)
11-25 08:33:24.558  3677  5812 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 08:33:24.558  3677  5812 I SystemUpdateService: file has been verified
11-25 08:33:24.558  3677  5812 I SystemUpdateService: OTA package size = 21989297
,11-25 08:33:24.563  3677  5812 I SystemUpdateService: showing system update notification
,11-25 08:33:24.575  3677  3677 D SystemUpdateService: onDestroy
,11-25 08:33:24.628  4985  5817 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 08:33:24.756   931  3800 D WifiService: setWifiEnabled: false pid=5603, uid=10077
,11-25 08:33:24.757   931  3800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 08:33:24.763   931  2926 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-25 08:33:24.764   931  2926 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 08:33:24.764   931  2926 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 08:33:24.764   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:24.779   931  5801 D DhcpClient: Clearing IP address
11-25 08:33:24.779   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 08:33:24.781   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:24.791  3529  5822 V NativeCrypto: Read error: ssl=0x7f5fc02a80: I/O error during system call, Connection timed out
,11-25 08:33:24.793  3529  5822 V NativeCrypto: SSL shutdown failed: ssl=0x7f5fc02a80: I/O error during system call, Broken pipe
,11-25 08:33:24.795   931  3147 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-25 08:33:24.796   931  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-25 08:33:24.796   931  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 08:33:24.800   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 08:33:24.800   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-25 08:33:24.803   535   535 E Parcel  : Reading a NULL string not supported here.
11-25 08:33:24.808   931   931 D RttService: SCAN_AVAILABLE : 1
11-25 08:33:24.808   931  3036 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 08:33:24.809   931  2928 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-25 08:33:24.810   931  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-25 08:33:24.810  3728  3867 W QCNEJ   : |CORE| network lost: 101
11-25 08:33:24.811  3728  3867 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 08:33:24.813   931  5802 D DhcpClient: Receive thread stopped
11-25 08:33:24.814   931  2926 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 08:33:24.817   931  2926 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 08:33:24.835   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 08:33:24.855   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 08:33:24.855   931  2928 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 08:33:24.855   509   928 D CommandListener: Clearing all IP addresses on wlan0
11-25 08:33:24.855   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 08:33:24.858   931   948 D Tethering: MasterInitialState.processMessage what=3
,11-25 08:33:24.860  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:24.860   931  2926 D DhcpClient: doQuit
11-25 08:33:24.860   931  2926 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 08:33:24.860   931  5801 D DhcpClient: onQuitting
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:24.860  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 08:33:24.860  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:24.861  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 08:33:24.861  5794  5794 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 08:33:24.864  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:24.864  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 08:33:24.864  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:24.865  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 08:33:24.868  3677  3677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 08:33:24.872  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 08:33:24.872  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-25 08:33:24.872  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 08:33:24.872  5010  5033 E SarControlService: no key has been found,reset the power
11-25 08:33:24.872  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 08:33:24.872  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-25 08:33:24.872  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 08:33:24.873  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 08:33:24.873  5035  5035 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 08:33:24.874  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 08:33:24.874  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 08:33:24.874  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 08:33:24.875  5794  5794 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-25 08:33:24.875  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:33:24.875  5035  5035 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 08:33:24.878  3677  3677 D SystemUpdateService: onCreate
11-25 08:33:24.879  5794  5794 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-25 08:33:24.879  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000ee03000000000000ffffffff]
11-25 08:33:24.879  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:33:24.879  5035  5049 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 08:33:24.879  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:33:24.880  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 08:33:24.880  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000ef03000000000000ffffffff]
11-25 08:33:24.880  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:33:24.880  5035  5049 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 08:33:24.881  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:33:24.881  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 08:33:24.884  3677  3677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 08:33:24.890  3677  5831 I SystemUpdateService: active receiver: enabled
,11-25 08:33:24.892  3677  3677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 08:33:24.896  3677  5370 I iu.UploadsManager: num queued entries: 0
,11-25 08:33:24.896  3677  5370 I iu.UploadsManager: num updated entries: 0
,11-25 08:33:24.899  3677  5831 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 08:33:24.901  3677  3677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 08:33:24.903  3677  3677 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 08:33:24.905  5734  5734 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 08:33:24.910  5734  5734 D SprintDMHelper: simOperator: 
11-25 08:33:24.910  5734  5734 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 08:33:24.917   509   928 E Netd    : netlink response contains error (No such file or directory)
,11-25 08:33:24.918  3677  5831 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-25 08:33:24.918  3677  5831 I SystemUpdateService: now status is 0 (complete)
11-25 08:33:24.919  3677  5370 I iu.SyncManager: NEXT; no task
11-25 08:33:24.918  3677  5831 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 08:33:24.919  3677  5831 I SystemUpdateService: file has been verified
11-25 08:33:24.919  3677  5831 I SystemUpdateService: OTA package size = 21989297
11-25 08:33:24.919   931  2928 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-25 08:33:24.919   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 08:33:24.919  5794  5794 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 08:33:24.921  4985  5835 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 08:33:24.931  5794  5794 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 08:33:24.936   931  2926 D wifi    : In wifi stop Hal
,11-25 08:33:24.936  4985  4985 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 08:33:24.936   931  2926 D wifi    : halHandle = 0x7f5ef2d300, mVM = 0x7f7b54d140, mCls = 0x1946
11-25 08:33:24.936   931  5793 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 08:33:24.936   931  5793 D WifiHAL : Got a signal to exit!!!
11-25 08:33:24.936   931  5793 I WifiHAL : Exit wifi_event_loop
11-25 08:33:24.936   931  2926 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 08:33:24.937   931  2926 E WifiHAL : Event processing terminated
11-25 08:33:24.937   931  2926 D wifi    : In wifi cleaned up handler
11-25 08:33:24.937   931  2926 I WifiHAL : Internal cleanup completed
11-25 08:33:24.938  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:24.939  4062  4184 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 08:33:24.943  3677  5831 I SystemUpdateService: showing system update notification
,11-25 08:33:24.951  3677  3677 D SystemUpdateService: onDestroy
,11-25 08:33:24.970   931  5793 D wifi    : set interface wlan0 flags (DOWN)
,11-25 08:33:24.970   931  2926 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 08:33:25.175   931   948 D Tethering: InitialState.processMessage what=4
,11-25 08:33:25.182   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 08:33:25.463   931  2928 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 08:33:29.797   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f9cb70:true
,11-25 08:33:29.798  5720  5720 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 08:33:29.804  5720  5720 I bt_bluedroid: init
,11-25 08:33:29.804  5720  5837 I BluetoothAdapterState: Entering OffState
,11-25 08:33:29.809  5720  5838 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 08:33:29.809  5720  5838 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-25 08:33:29.810  5720  5838 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 08:33:29.810  5720  5838 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-25 08:33:29.811  5720  5720 I bt_bluedroid: get_profile_interface socket
,11-25 08:33:29.817  5720  5841 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 08:33:29.817  5720  5720 I bt_bluedroid: get_profile_interface sdp
,11-25 08:33:29.820  5720  5841 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 08:33:29.828  5720  5730 I bt_bluedroid: config_hci_snoop_log
,11-25 08:33:29.831   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 08:33:29.841  5720  5837 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 08:33:29.841  5720  5837 D BluetoothAdapterProperties: Setting state to 14
,11-25 08:33:29.841  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 08:33:29.845  5720  5837 D BluetoothBondStateMachine: make
,11-25 08:33:29.849  5720  5842 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 08:33:29.855  5720  5837 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:29.857  5720  5720 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 08:33:29.863  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:29.864  5720  5720 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 08:33:29.866  5720  5720 D BtGatt.GattService: Received start request. Starting profile...
,11-25 08:33:29.866  5720  5720 D BtGatt.GattService: start()
,11-25 08:33:29.866  5720  5720 I bt_bluedroid: get_profile_interface gatt
,11-25 08:33:29.868  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:29.869  5720  5720 D BtGatt.AdvertiseManager: advertise manager created
,11-25 08:33:29.878  5720  5720 V BluetoothAdapterState: isTurningOff()=false
,11-25 08:33:29.878  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:29.878  5720  5720 V BluetoothAdapterState: isBleTurningOn()=true
11-25 08:33:29.878  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:29.879  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 08:33:29.882  5720  5837 I bt_bluedroid: bt_bluedroid
,11-25 08:33:29.882  5720  5838 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 08:33:29.882  5720  5838 I bt_hci  : start_up
,11-25 08:33:29.892  5720  5838 I bt_vendor: alloc value 0xf3e78871
,11-25 08:33:29.892  5720  5838 I bt_vendor: init
11-25 08:33:29.892  5720  5838 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 08:33:29.892  5720  5838 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 08:33:30.004  5720  5838 D bt_hci  : start_up starting async portion
,11-25 08:33:30.004  5720  5845 I bt_hci  : event_finish_startup
,11-25 08:33:30.005  5720  5845 I bt_hci_h4: hal_open
,11-25 08:33:30.005  5720  5845 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-25 08:33:30.001  5846  5846 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 08:33:30.008  5720  5845 I bt_userial_vendor: device fd = 54 open
,11-25 08:33:30.021  5720  5845 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 08:33:30.024  5720  5845 D bt_hwcfg: Chipset BCM4358A3
11-25 08:33:30.024  5720  5845 D bt_hwcfg: Target name = [BCM4358A3]
,11-25 08:33:30.025  5720  5845 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 08:33:30.419  5720  5845 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 08:33:30.419  5720  5845 D bt_hwcfg: Settlement delay -- 100 ms
,11-25 08:33:30.419  5720  5845 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 08:33:30.555  5720  5845 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 08:33:30.555  5720  5845 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-25 08:33:30.556  5720  5845 I bt_hwcfg: vendor lib fwcfg completed
11-25 08:33:30.557  5720  5845 I bt_vendor: firmware callback
11-25 08:33:30.557  5720  5845 I bt_hci  : firmware_config_callback
,11-25 08:33:30.566  5720  5850 I bt_btu  : btu_task pending for preload complete event
,11-25 08:33:30.566  5720  5850 I bt_btu_task: Bluetooth chip preload is complete
11-25 08:33:30.566  5720  5850 I bt_btu  : btu_task received preload complete event
,11-25 08:33:30.574  5720  5850 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 08:33:30.575  5720  5850 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_GAP
,11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-25 08:33:30.576  5720  5850 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 08:33:30.663  5720  5850 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3df6549
11-25 08:33:30.663  5720  5850 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3df6549 
,11-25 08:33:30.675  5720  5841 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 08:33:30.676  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 08:33:30.677  5720  5841 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 08:33:30.679  5720  5841 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 08:33:30.682  5720  5841 D BluetoothAdapterProperties: Scan Mode:20
11-25 08:33:30.682  5720  5841 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 08:33:30.683  5720  5841 D bt_hci  : do_postload posting postload work item
11-25 08:33:30.683  5720  5845 I bt_hci  : event_postload
11-25 08:33:30.683  5720  5845 I bt_vendor: sco_config_cb
11-25 08:33:30.683  5720  5845 I bt_hci  : sco_config_callback postload finished.
11-25 08:33:30.687  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:30.688  5720  5841 D bt_bte_conf: Device ID record 1 : primary
11-25 08:33:30.688  5720  5841 D bt_bte_conf:   vendorId            = 000f
11-25 08:33:30.688  5720  5841 D bt_bte_conf:   vendorIdSource      = 0001
11-25 08:33:30.688  5720  5841 D bt_bte_conf:   product             = 1200
11-25 08:33:30.688  5720  5841 D bt_bte_conf:   version             = 1436
11-25 08:33:30.688  5720  5841 D bt_bte_conf:   clientExecutableURL = 
11-25 08:33:30.688  5720  5841 D bt_bte_conf:   serviceDescription  = 
11-25 08:33:30.689  5720  5841 D bt_bte_conf:   documentationURL    = 
11-25 08:33:30.689  5720  5841 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-25 08:33:30.689  5720  5838 D bt_stack_manager: event_start_up_stack finished
,11-25 08:33:30.690  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-25 08:33:30.690  5720  5837 D BluetoothAdapterProperties: Setting state to 15
11-25 08:33:30.690  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 08:33:30.692  5720  5837 I BluetoothAdapterState: Entering BleOnState
,11-25 08:33:30.696  5720  5845 I bt_vendor: low_power_mode_cb
11-25 08:33:30.697  5720  5837 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 08:33:30.697  5720  5837 D BluetoothAdapterProperties: Setting state to 11
11-25 08:33:30.697  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 08:33:30.706  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:30.706  5720  5720 D HeadsetService: Received start request. Starting profile...
,11-25 08:33:30.706  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:30.709  5720  5720 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 08:33:30.710  5720  5720 D HeadsetStateMachine: make
,11-25 08:33:30.719  5720  5837 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:30.721  5720  5720 D HeadsetStateMachine: max_hf_connections = 1
,11-25 08:33:30.721  5720  5720 I bt_bluedroid: get_profile_interface handsfree
11-25 08:33:30.721  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 08:33:30.722  5720  5841 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 08:33:30.725  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:30.726  5720  5720 D A2dpService: Received start request. Starting profile...
,11-25 08:33:30.727  5720  5720 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-25 08:33:30.727  5720  5720 I bt_bluedroid: get_profile_interface avrcp
,11-25 08:33:30.733  5720  5720 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 08:33:30.734  5720  5720 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 08:33:30.734  5720  5720 D A2dpStateMachine: make
,11-25 08:33:30.735  5720  5720 I bt_bluedroid: get_profile_interface a2dp
,11-25 08:33:30.737  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-25 08:33:30.737  5720  5858 D A2dpStateMachine: Enter Disconnected: -2
,11-25 08:33:30.739  5720  5720 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 08:33:30.740  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:30.740  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 08:33:30.742  5661  5661 D BluetoothInputDevice: Proxy object connected
,11-25 08:33:30.742  5720  5720 D HidService: Received start request. Starting profile...
11-25 08:33:30.742  5720  5720 I bt_bluedroid: get_profile_interface hidhost
11-25 08:33:30.742  5720  5720 D HidService: setHidService(): set to: null
11-25 08:33:30.742  5720  5841 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dd756d
11-25 08:33:30.742  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 08:33:30.743  5661  5661 D HidProfile: Bluetooth service connected
11-25 08:33:30.743  5720  5720 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 08:33:30.744  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:30.744  5720  5720 D HealthService: Received start request. Starting profile...
,11-25 08:33:30.746  5720  5720 I bt_bluedroid: get_profile_interface health
,11-25 08:33:30.746  5720  5720 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 08:33:30.747  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:30.748  5661  5661 D BluetoothPan: BluetoothPAN Proxy object connected
,11-25 08:33:30.748  5720  5720 D PanService: Received start request. Starting profile...
11-25 08:33:30.749  5720  5720 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 08:33:30.749  5720  5720 I bt_bluedroid: get_profile_interface pan
11-25 08:33:30.749  5661  5661 D PanProfile: Bluetooth service connected
11-25 08:33:30.749  5720  5841 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 08:33:30.751  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:30.752  5661  5661 D BluetoothMap: Proxy object connected
,11-25 08:33:30.753  5720  5720 D BluetoothMapService: Received start request. Starting profile...
11-25 08:33:30.753  5720  5720 D BluetoothMapService: start()
11-25 08:33:30.753  5661  5661 D MapProfile: Bluetooth service connected
11-25 08:33:30.753  5661  5661 D BluetoothMap: getConnectedDevices()
11-25 08:33:30.754  5661  5661 D BluetoothMap: Bluetooth is Not enabled
,11-25 08:33:30.756  5720  5720 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 08:33:30.757  5720  5720 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 08:33:30.757  5720  5720 D BluetoothMapAppObserver: createReceiver()
,11-25 08:33:30.759  5720  5720 D BluetoothMapAppObserver: initObservers()
11-25 08:33:30.759  5720  5720 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 08:33:30.766  5720  5720 V SapService: SapBinder()
,11-25 08:33:30.767  5720  5720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:30.767  5720  5720 D SapService: Received start request. Starting profile...
,11-25 08:33:30.767  5720  5720 V SapService: start()
,11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:30.769  5720  5856 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.769  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.770  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:30.771  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 08:33:30.772  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 08:33:30.772  5720  5837 D BluetoothAdapterProperties: ScanMode =  20
11-25 08:33:30.772  5720  5837 D BluetoothAdapterProperties: State =  11
11-25 08:33:30.772  5720  5837 D BluetoothAdapterProperties: Setting state to 12
11-25 08:33:30.772  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 08:33:30.773  5720  5837 I BluetoothAdapterState: Entering OnState
11-25 08:33:30.773  5661  5675 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 08:33:30.773  3083  3096 D BluetoothPan: onBluetoothStateChange on: true
,11-25 08:33:30.775  5720  5841 D BluetoothAdapterProperties: Scan Mode:21
11-25 08:33:30.775  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 08:33:30.775  3083  3095 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 08:33:30.775  3083  3083 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 08:33:30.775  3083  3083 D PanProfile: Bluetooth service connected
,11-25 08:33:30.777   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:30.777   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 08:33:30.777  5720  5841 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 08:33:30.779   931   931 D BluetoothA2dp: Proxy object connected
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:30.779  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 08:33:30.781  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 08:33:30.781  5661  5678 D BluetoothPan: onBluetoothStateChange on: true
,11-25 08:33:30.782  3083  3096 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 08:33:30.783  3083  3083 D BluetoothA2dp: Proxy object connected
11-25 08:33:30.783  3083  3095 D BluetoothMap: onBluetoothStateChange: up=true
11-25 08:33:30.784  5720  5720 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 08:33:30.785  5720  5720 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 08:33:30.785  3083  3930 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 08:33:30.786  5720  5720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:30.787  3083  3083 D BluetoothMap: Proxy object connected
11-25 08:33:30.787  3083  3083 D MapProfile: Bluetooth service connected
11-25 08:33:30.787  3083  3083 D BluetoothMap: getConnectedDevices()
,11-25 08:33:30.787  5661  5675 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 08:33:30.789  3083  3930 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 08:33:30.789  5720  5720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:30.789  3083  3083 D BluetoothInputDevice: Proxy object connected
11-25 08:33:30.789  3083  3083 D HidProfile: Bluetooth service connected
11-25 08:33:30.789  5661  5678 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-25 08:33:30.790  3753  3781 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:30.790   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:30.790   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:30.791  5720  5720 D ObexServerSockets: Succeed to create listening sockets 
11-25 08:33:30.791  5720  5720 D ObexServerSockets0: startAccept()
11-25 08:33:30.791  5720  5720 D ObexServerSockets0: prepareForNewConnect()
11-25 08:33:30.791   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 08:33:30.792  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 08:33:30.793  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:30.793  5661  5661 D LocalBluetoothProfileManager: Adding local A2DP profile
11-25 08:33:30.794  5720  5720 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 08:33:30.794  5720  5720 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-25 08:33:30.796  5720  5864 D ObexServerSockets0: Accepting socket connection...
,11-25 08:33:30.796  5720  5865 D ObexServerSockets0: Accepting socket connection...
11-25 08:33:30.796  5720  5720 D BluetoothMapService: onReceive
11-25 08:33:30.796  5720  5720 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 08:33:30.796  5720  5720 D BluetoothMapService: STATE_ON
,11-25 08:33:30.797  5661  5661 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 08:33:30.798  5720  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:30.800  5720  5866 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 08:33:30.800  5720  5866 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 08:33:30.804  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 08:33:30.807  5661  5661 D BluetoothA2dp: Proxy object connected
,11-25 08:33:30.811  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 08:33:30.811  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 08:33:30.819  5661  5661 D BluetoothPbap: Proxy object connected
,11-25 08:33:30.820  5661  5661 D PbapServerProfile: Bluetooth service connected
,11-25 08:33:30.822  3083  3083 D BluetoothPbap: Proxy object connected
11-25 08:33:30.822  3083  3083 D PbapServerProfile: Bluetooth service connected
,11-25 08:33:30.822  5720  5720 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 08:33:30.822  5720  5720 D ObexServerSockets0: prepareForNewConnect()
11-25 08:33:30.825  5720  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 08:33:30.841  5720  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 08:33:30.842  5720  5874 I BtOppRfcommListener: Accept thread started.
,11-25 08:33:30.878   931   931 D BluetoothHeadset: Proxy object connected
,11-25 08:33:30.879   931   931 D BluetoothHeadset: Proxy object connected
11-25 08:33:30.879   931   931 D BluetoothHeadset: Proxy object connected
11-25 08:33:30.879  3753  3985 D BluetoothHeadset: Proxy object connected
11-25 08:33:30.879  3083  3096 D BluetoothHeadset: Proxy object connected
,11-25 08:33:30.879  3083  3083 D HeadsetProfile: Bluetooth service connected
,11-25 08:33:30.890  3083  3930 D BluetoothHeadset: Proxy object connected
11-25 08:33:30.890  3083  3083 D HeadsetProfile: Bluetooth service connected
,11-25 08:33:30.891  3753  3776 D BluetoothHeadset: Proxy object connected
11-25 08:33:30.891   931   948 D BluetoothHeadset: Proxy object connected
11-25 08:33:30.891   931   948 D BluetoothHeadset: Proxy object connected
,11-25 08:33:30.900  5661  5675 D BluetoothHeadset: Proxy object connected
,11-25 08:33:30.901  5661  5661 D HeadsetProfile: Bluetooth service connected
,11-25 08:33:31.481   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 08:33:31.481   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 08:33:32.421   931  2928 D ConnectivityService: handlePromptUnvalidated 101
,11-25 08:33:34.775  5720  5837 D BluetoothAdapterState: Current state: ON, message: 23
11-25 08:33:34.776  5720  5837 D BluetoothAdapterProperties: Setting state to 13
11-25 08:33:34.776  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 08:33:34.777  5720  5837 D BluetoothAdapterProperties: onBluetoothDisable()
,11-25 08:33:34.780  5720  5837 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:34.786  5720  5720 D BluetoothMapService: onReceive
,11-25 08:33:34.786  5720  5720 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-25 08:33:34.786  5720  5720 D BluetoothMapService: STATE_TURNING_OFF
,11-25 08:33:34.787  5720  5720 D BluetoothMapService: MAP Service closeService in
11-25 08:33:34.787  5720  5720 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 08:33:34.787  5720  5720 D ObexServerSockets0: shutdown(block = true)
11-25 08:33:34.788  5720  5720 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 08:33:34.789  5720  5852 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 08:33:34.789  5720  5720 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 08:33:34.789  5720  5865 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 08:33:34.790  5720  5864 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 08:33:34.792  5720  5841 D BluetoothAdapterProperties: Scan Mode:20
,11-25 08:33:34.794  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:34.794  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 08:33:34.795  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 08:33:34.797  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 08:33:34.797  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 08:33:34.799  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 08:33:34.800  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:34.802  5720  5720 I BtOppRfcommListener: stopping Accept Thread
11-25 08:33:34.802  5720  5874 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 08:33:34.803  5720  5874 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 08:33:34.806  5720  5720 D HeadsetService: Received stop request...Stopping profile...
,11-25 08:33:34.807  5661  5661 D DockEventReceiver: finishStartingService: stopping service
11-25 08:33:34.811   931   931 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:34.812  5720  5720 D A2dpService: Received stop request...Stopping profile...
11-25 08:33:34.812  5720  5858 D A2dpStateMachine: Exit Disconnected: -1
11-25 08:33:34.813  5661  5675 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:34.814   931   931 D BluetoothHeadset: Proxy object disconnected
,11-25 08:33:34.814   931   931 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:34.815  3753  3781 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:34.815  3083  3096 D BluetoothHeadset: Proxy object disconnected
11-25 08:33:34.816  5661  5661 D HeadsetProfile: Bluetooth service disconnected
11-25 08:33:34.816  3083  3083 D HeadsetProfile: Bluetooth service disconnected
,11-25 08:33:34.821   931   931 D BluetoothA2dp: Proxy object disconnected
,11-25 08:33:34.821  3083  3083 D BluetoothA2dp: Proxy object disconnected
,11-25 08:33:34.826  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 08:33:34.826  5720  5720 D HidService: Received stop request...Stopping profile...
11-25 08:33:34.826  5720  5720 D HidService: Stopping Bluetooth HidService
11-25 08:33:34.827  5661  5661 D BluetoothA2dp: Proxy object disconnected
11-25 08:33:34.828  3083  3083 D BluetoothInputDevice: Proxy object disconnected
,11-25 08:33:34.828  3083  3083 D HidProfile: Bluetooth service disconnected
11-25 08:33:34.828  5661  5661 D BluetoothInputDevice: Proxy object disconnected
11-25 08:33:34.828  5661  5661 D HidProfile: Bluetooth service disconnected
11-25 08:33:34.829  5720  5720 D HealthService: Received stop request...Stopping profile...
,11-25 08:33:34.830  5720  5720 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:34.830  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:34.830  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:34.830  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 08:33:34.831  5720  5720 D PanService: Received stop request...Stopping profile...
,11-25 08:33:34.831  3083  3083 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 08:33:34.831  3083  3083 D PanProfile: Bluetooth service disconnected
11-25 08:33:34.832  5661  5661 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-25 08:33:34.832  5661  5661 D PanProfile: Bluetooth service disconnected
,11-25 08:33:34.833  5720  5720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 08:33:34.833  5720  5720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-25 08:33:34.833  5720  5850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:34.834  5720  5850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 08:33:34.834  5720  5850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:34.834  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 08:33:34.834  5720  5720 D BluetoothMapService: Received stop request...Stopping profile...
11-25 08:33:34.834  5720  5720 D BluetoothMapService: stop()
11-25 08:33:34.834  5720  5841 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-25 08:33:34.835  5720  5720 D BluetoothMapAppObserver: deinitObservers()
,11-25 08:33:34.835  5720  5720 D BluetoothMapAppObserver: removeReceiver()
11-25 08:33:34.836  3083  3083 D BluetoothMap: Proxy object disconnected
11-25 08:33:34.836  3083  3083 D MapProfile: Bluetooth service disconnected
11-25 08:33:34.837  5661  5661 D BluetoothMap: Proxy object disconnected
11-25 08:33:34.837  5661  5661 D MapProfile: Bluetooth service disconnected
11-25 08:33:34.837  5720  5720 D SapService: Received stop request...Stopping profile...
11-25 08:33:34.837  5720  5720 V SapService: stop()
,11-25 08:33:34.840  5720  5720 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:34.840  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:34.840  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:34.840  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 08:33:34.842  5720  5850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:34.842  5720  5850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:34.842  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 08:33:34.842  5720  5850 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 08:33:34.842  5720  5850 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 08:33:34.842  5720  5850 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 08:33:34.842  5720  5850 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 08:33:34.851  5720  5720 V BluetoothAdapterState: isTurningOff()=true
,11-25 08:33:34.851  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:34.851  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:34.851  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:34.851  3083  3083 D BluetoothPbap: Proxy object disconnected
11-25 08:33:34.851  3083  3083 D PbapServerProfile: Bluetooth service disconnected
11-25 08:33:34.852  5661  5661 D BluetoothPbap: Proxy object disconnected
,11-25 08:33:34.852  5661  5661 D PbapServerProfile: Bluetooth service disconnected
11-25 08:33:34.852  5720  5720 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 08:33:34.852  5720  5720 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 08:33:34.852  5720  5720 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:34.852  5720  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 08:33:34.852  5720  5720 V BluetoothAdapterState: isTurningOn()=false
,11-25 08:33:34.853  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:34.853  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:34.853  5720  5720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 08:33:34.853  5720  5841 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 08:33:34.854  5720  5720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 08:33:34.854  5720  5720 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:34.854  5720  5720 V BluetoothAdapterState: isTurningOn()=false
,11-25 08:33:34.854  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:34.854  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:34.854  5720  5720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 08:33:34.854  5720  5720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 08:33:34.855  5720  5720 D BluetoothMapService: MAP Service closeService in
11-25 08:33:34.855  5720  5720 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:34.855  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:34.855  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:34.855  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:34.856  5720  5720 D BluetoothMapService: cleanup()
11-25 08:33:34.856  5720  5720 D BluetoothMapService: MAP Service closeService in
11-25 08:33:34.856  5720  5720 V BluetoothAdapterState: isTurningOff()=true
11-25 08:33:34.856  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:34.856  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 08:33:34.856  5720  5720 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:34.856  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 08:33:34.856  5720  5837 D BluetoothAdapterProperties: Setting state to 15
11-25 08:33:34.856  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 08:33:34.857  5720  5837 I BluetoothAdapterState: Entering BleOnState
11-25 08:33:34.857  5661  5678 D BluetoothMap: onBluetoothStateChange: up=false
11-25 08:33:34.859  3083  3095 D BluetoothPan: onBluetoothStateChange on: false
11-25 08:33:34.859  3083  3930 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 08:33:34.860  5661  5675 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:34.860   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:34.860   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 08:33:34.860  5661  5678 D BluetoothPan: onBluetoothStateChange on: false
11-25 08:33:34.861  3083  3096 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 08:33:34.861  3083  3095 D BluetoothMap: onBluetoothStateChange: up=false
11-25 08:33:34.862  3083  3930 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 08:33:34.862  5661  5675 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 08:33:34.863  5661  5678 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 08:33:34.864  3083  3096 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:34.864  5661  5675 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 08:33:34.865  3753  3985 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:34.865   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:34.865   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 08:33:34.865  5720  5837 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 08:33:34.865  5720  5837 D BluetoothAdapterProperties: Setting state to 16
11-25 08:33:34.865  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 08:33:34.866  5720  5837 D BluetoothAdapterProperties: onBleDisable
11-25 08:33:34.866  5720  5837 I BluetoothAdapterState: Entering PendingCommandState
11-25 08:33:34.866  5720  5838 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 08:33:34.868  5720  5850 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 08:33:34.868  5720  5850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 08:33:34.868  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:34.868  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 08:33:34.872  5720  5841 D BluetoothAdapterProperties: Scan Mode:20
11-25 08:33:34.874  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 08:33:34.876  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 08:33:34.876  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 08:33:35.085  5720  5841 I bt_hci  : shut_down
,11-25 08:33:35.094  5720  5845 D bt_hwcfg: hw_epilog_process
,11-25 08:33:35.094  5720  5845 I bt_vendor: low_power_mode_cb
,11-25 08:33:35.097  5720  5845 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 08:33:35.098  5720  5845 I bt_vendor: epilog_cb
11-25 08:33:35.098  5720  5845 I bt_hci  : epilog_finished_callback
,11-25 08:33:35.103  5720  5841 I bt_hci_h4: hal_close
,11-25 08:33:35.104  5720  5841 I bt_userial_vendor: device fd = 54 close
,11-25 08:33:35.218  5720  5838 D bt_stack_manager: event_shut_down_stack finished.
,11-25 08:33:35.219  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 08:33:35.223  5720  5837 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-25 08:33:35.223  5720  5720 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 08:33:35.225  5720  5720 D BtGatt.GattService: Received stop request...Stopping profile...
,11-25 08:33:35.225  5720  5720 D BtGatt.GattService: stop()
,11-25 08:33:35.225  5720  5720 D BtGatt.AdvertiseManager: advertise clients cleared
,11-25 08:33:35.230  5720  5720 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:35.230  5720  5720 V BluetoothAdapterState: isTurningOn()=false
11-25 08:33:35.230  5720  5720 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:35.230  5720  5720 V BluetoothAdapterState: isBleTurningOff()=true
,11-25 08:33:35.231  5720  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 08:33:35.231  5720  5837 D BluetoothAdapterProperties: Setting state to 10
11-25 08:33:35.232  5720  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 08:33:35.233  5720  5837 I BluetoothAdapterState: Entering OffState
,11-25 08:33:35.235   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 08:33:35.256  5720  5720 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 08:33:35.257  5720  5720 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-25 08:33:35.257  5720  5838 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 08:33:35.260  5720  5720 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-25 08:33:35.264  5720  5720 I art     : System.exit called, status: 0
,11-25 08:33:35.265  5720  5720 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 08:33:35.294   931  3147 I ActivityManager: Process com.android.bluetooth (pid 5720) has died
,11-25 08:33:39.773  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:39.773  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 08:33:39.780  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:39.781  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e38c12 removed from the list
,11-25 08:33:39.781  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:39.786  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:39.786  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68d6899 added. We now have 4 listener(s)
,11-25 08:33:39.786  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:39.788  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:39.789  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68d6899 removed from the list
,11-25 08:33:39.789  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:39.792  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:39.792  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6a575e added. We now have 4 listener(s)
11-25 08:33:39.792  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:41.482   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:42.484   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:43.485   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:44.486   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:44.803  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:44.838   931   948 I ActivityManager: Start proc 5883:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 08:33:44.925  5883  5883 D AdapterServiceConfig: Adding HeadsetService
,11-25 08:33:44.926  5883  5883 D AdapterServiceConfig: Adding A2dpService
11-25 08:33:44.926  5883  5883 D AdapterServiceConfig: Adding HidService
11-25 08:33:44.926  5883  5883 D AdapterServiceConfig: Adding HealthService
11-25 08:33:44.926  5883  5883 D AdapterServiceConfig: Adding PanService
11-25 08:33:44.926  5883  5883 D AdapterServiceConfig: Adding GattService
11-25 08:33:44.926  5883  5883 D AdapterServiceConfig: Adding BluetoothMapService
11-25 08:33:44.927  5883  5883 D AdapterServiceConfig: Adding SapService
,11-25 08:33:44.938   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2b2ca9:true
,11-25 08:33:44.938  5883  5883 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 08:33:44.941  5883  5883 I bt_bluedroid: init
,11-25 08:33:44.942  5883  5895 I BluetoothAdapterState: Entering OffState
,11-25 08:33:44.944  5883  5896 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 08:33:44.944  5883  5896 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 08:33:44.944  5883  5896 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 08:33:44.944  5883  5896 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 08:33:44.945  5883  5883 I bt_bluedroid: get_profile_interface socket
,11-25 08:33:44.947  5883  5899 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-25 08:33:44.947  5883  5883 I bt_bluedroid: get_profile_interface sdp
,11-25 08:33:44.948  5883  5899 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 08:33:44.952  5883  5894 I bt_bluedroid: config_hci_snoop_log
,11-25 08:33:44.953   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 08:33:44.958  5883  5895 D BluetoothAdapterState: Current state: OFF, message: 0
11-25 08:33:44.958  5883  5895 D BluetoothAdapterProperties: Setting state to 14
11-25 08:33:44.958  5883  5895 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-25 08:33:44.959  5883  5895 D BluetoothBondStateMachine: make
,11-25 08:33:44.961  5883  5900 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 08:33:44.964  5883  5895 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:44.965  5883  5883 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 08:33:44.967  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:44.968  5883  5883 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 08:33:44.968  5883  5883 D BtGatt.GattService: Received start request. Starting profile...
11-25 08:33:44.969  5883  5883 D BtGatt.GattService: start()
11-25 08:33:44.969  5883  5883 I bt_bluedroid: get_profile_interface gatt
,11-25 08:33:44.970  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:44.970  5883  5883 D BtGatt.AdvertiseManager: advertise manager created
,11-25 08:33:44.975  5883  5883 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:44.975  5883  5883 V BluetoothAdapterState: isTurningOn()=false
,11-25 08:33:44.975  5883  5883 V BluetoothAdapterState: isBleTurningOn()=true
11-25 08:33:44.975  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:44.975  5883  5895 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-25 08:33:44.977  5883  5895 I bt_bluedroid: bt_bluedroid
,11-25 08:33:44.977  5883  5896 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 08:33:44.978  5883  5896 I bt_hci  : start_up
,11-25 08:33:44.982  5883  5896 I bt_vendor: alloc value 0xf3ec9871
,11-25 08:33:44.982  5883  5896 I bt_vendor: init
11-25 08:33:44.982  5883  5896 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 08:33:44.983  5883  5896 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 08:33:45.094  5883  5896 D bt_hci  : start_up starting async portion
11-25 08:33:45.095  5883  5903 I bt_hci  : event_finish_startup
11-25 08:33:45.095  5883  5903 I bt_hci_h4: hal_open
11-25 08:33:45.095  5883  5903 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 08:33:45.091  5904  5904 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 08:33:45.097  5883  5903 I bt_userial_vendor: device fd = 54 open
,11-25 08:33:45.114  5883  5903 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 08:33:45.118  5883  5903 D bt_hwcfg: Chipset BCM4358A3
,11-25 08:33:45.118  5883  5903 D bt_hwcfg: Target name = [BCM4358A3]
11-25 08:33:45.118  5883  5903 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 08:33:45.488   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:45.517  5883  5903 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 08:33:45.517  5883  5903 D bt_hwcfg: Settlement delay -- 100 ms
11-25 08:33:45.517  5883  5903 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 08:33:45.651  5883  5903 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-25 08:33:45.652  5883  5903 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-25 08:33:45.653  5883  5903 I bt_hwcfg: vendor lib fwcfg completed
,11-25 08:33:45.654  5883  5903 I bt_vendor: firmware callback
,11-25 08:33:45.654  5883  5903 I bt_hci  : firmware_config_callback
11-25 08:33:45.662  5883  5906 I bt_btu  : btu_task pending for preload complete event
,11-25 08:33:45.662  5883  5906 I bt_btu_task: Bluetooth chip preload is complete
,11-25 08:33:45.662  5883  5906 I bt_btu  : btu_task received preload complete event
,11-25 08:33:45.669  5883  5906 I         : BTE_InitTraceLevels -- TRC_HCI
11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 08:33:45.670  5883  5906 I         : BTE_InitTraceLevels -- TRC_BTM
,11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_SDP
,11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 08:33:45.671  5883  5906 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 08:33:45.752  5883  5906 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e47549
,11-25 08:33:45.752  5883  5906 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e47549 
,11-25 08:33:45.776  5883  5899 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 08:33:45.777  5883  5899 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 08:33:45.778  5883  5899 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 08:33:45.780  5883  5899 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 08:33:45.783  5883  5899 D BluetoothAdapterProperties: Scan Mode:20
,11-25 08:33:45.783  5883  5899 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 08:33:45.783  5883  5899 D bt_hci  : do_postload posting postload work item
11-25 08:33:45.783  5883  5903 I bt_hci  : event_postload
,11-25 08:33:45.783  5883  5903 I bt_vendor: sco_config_cb
11-25 08:33:45.783  5883  5903 I bt_hci  : sco_config_callback postload finished.
11-25 08:33:45.785  5883  5899 D bt_bte_conf: Device ID record 1 : primary
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   vendorId            = 000f
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   vendorIdSource      = 0001
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   product             = 1200
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   version             = 1436
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   clientExecutableURL = 
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   serviceDescription  = 
11-25 08:33:45.786  5883  5899 D bt_bte_conf:   documentationURL    = 
11-25 08:33:45.786  5883  5899 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 08:33:45.786  5883  5896 D bt_stack_manager: event_start_up_stack finished
,11-25 08:33:45.788  5883  5895 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-25 08:33:45.788  5883  5895 D BluetoothAdapterProperties: Setting state to 15
,11-25 08:33:45.789  5883  5895 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 08:33:45.790  5883  5895 I BluetoothAdapterState: Entering BleOnState
,11-25 08:33:45.791  5883  5903 I bt_vendor: low_power_mode_cb
,11-25 08:33:45.795  5883  5895 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-25 08:33:45.795  5883  5895 D BluetoothAdapterProperties: Setting state to 11
11-25 08:33:45.795  5883  5895 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 08:33:45.800  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:45.801  5883  5883 D HeadsetService: Received start request. Starting profile...
11-25 08:33:45.803  5883  5883 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 08:33:45.804  5883  5883 D HeadsetStateMachine: make
,11-25 08:33:45.814  5883  5895 I BluetoothAdapterState: Entering PendingCommandState
,11-25 08:33:45.816  5883  5883 D HeadsetStateMachine: max_hf_connections = 1
,11-25 08:33:45.816  5883  5883 I bt_bluedroid: get_profile_interface handsfree
11-25 08:33:45.816  5883  5899 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 08:33:45.816  5883  5899 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-25 08:33:45.819  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:45.819  5883  5883 D A2dpService: Received start request. Starting profile...
11-25 08:33:45.820  5883  5883 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 08:33:45.820  5883  5883 I bt_bluedroid: get_profile_interface avrcp
,11-25 08:33:45.825  5883  5883 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 08:33:45.825  5883  5883 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 08:33:45.825  5883  5883 D A2dpStateMachine: make
11-25 08:33:45.826  5883  5883 I bt_bluedroid: get_profile_interface a2dp
,11-25 08:33:45.827  5883  5899 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 08:33:45.828  5883  5914 D A2dpStateMachine: Enter Disconnected: -2
11-25 08:33:45.829  5883  5883 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 08:33:45.829  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:45.830  5883  5883 D HidService: Received start request. Starting profile...
11-25 08:33:45.830  5883  5883 I bt_bluedroid: get_profile_interface hidhost
,11-25 08:33:45.831  5883  5883 D HidService: setHidService(): set to: null
11-25 08:33:45.831  5883  5899 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e2856d
11-25 08:33:45.831  5883  5899 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-25 08:33:45.832  5883  5883 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 08:33:45.833  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:45.833  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 08:33:45.833  5883  5883 D HealthService: Received start request. Starting profile...
11-25 08:33:45.835  5883  5883 I bt_bluedroid: get_profile_interface health
11-25 08:33:45.835  5883  5883 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 08:33:45.836  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
,11-25 08:33:45.837  5883  5883 D PanService: Received start request. Starting profile...
,11-25 08:33:45.837  5883  5883 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-25 08:33:45.837  5883  5883 I bt_bluedroid: get_profile_interface pan
,11-25 08:33:45.838  5883  5899 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 08:33:45.839  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:45.840  5883  5883 D BluetoothMapService: Received start request. Starting profile...
11-25 08:33:45.840  5883  5883 D BluetoothMapService: start()
11-25 08:33:45.843  5883  5883 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 08:33:45.843  5883  5883 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 08:33:45.844  5883  5883 D BluetoothMapAppObserver: createReceiver()
,11-25 08:33:45.845  5883  5883 D BluetoothMapAppObserver: initObservers()
,11-25 08:33:45.845  5883  5883 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 08:33:45.854  5883  5883 V SapService: SapBinder()
,11-25 08:33:45.854  5883  5883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:45.855  5883  5883 D SapService: Received start request. Starting profile...
,11-25 08:33:45.855  5883  5883 V SapService: start()
,11-25 08:33:45.857  5883  5883 V BluetoothAdapterState: isTurningOff()=false
,11-25 08:33:45.857  5883  5883 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:45.857  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.857  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:45.857  5883  5883 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.858  5883  5912 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isTurningOff()=false
,11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.858  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isTurningOff()=false
,11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:45.859  5883  5883 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:45.860  5883  5883 V BluetoothAdapterState: isTurningOn()=true
,11-25 08:33:45.860  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.860  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 08:33:45.861  5883  5883 V BluetoothAdapterState: isTurningOff()=false
11-25 08:33:45.861  5883  5883 V BluetoothAdapterState: isTurningOn()=true
11-25 08:33:45.861  5883  5883 V BluetoothAdapterState: isBleTurningOn()=false
11-25 08:33:45.861  5883  5883 V BluetoothAdapterState: isBleTurningOff()=false
11-25 08:33:45.861  5883  5895 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 08:33:45.861  5883  5895 D BluetoothAdapterProperties: ScanMode =  20
11-25 08:33:45.861  5883  5895 D BluetoothAdapterProperties: State =  11
11-25 08:33:45.861  5883  5895 D BluetoothAdapterProperties: Setting state to 12
11-25 08:33:45.861  5883  5895 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 08:33:45.862  5883  5895 I BluetoothAdapterState: Entering OnState
,11-25 08:33:45.862  5661  5675 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 08:33:45.865  5883  5899 D BluetoothAdapterProperties: Scan Mode:21
11-25 08:33:45.865  3083  3096 D BluetoothPan: onBluetoothStateChange on: true
,11-25 08:33:45.865  5883  5899 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 08:33:45.866  3083  3095 D BluetoothPbap: onBluetoothStateChange: up=true
,11-25 08:33:45.867  3083  3083 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 08:33:45.867  3083  3083 D PanProfile: Bluetooth service connected
11-25 08:33:45.868  5661  5675 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:45.868   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:45.868   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 08:33:45.869  5661  5678 D BluetoothPan: onBluetoothStateChange on: true
,11-25 08:33:45.870   931   931 D BluetoothA2dp: Proxy object connected
11-25 08:33:45.871  3083  3096 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 08:33:45.871  5883  5883 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 08:33:45.872  5883  5883 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 08:33:45.872  3083  3083 D BluetoothA2dp: Proxy object connected
11-25 08:33:45.872  3083  3095 D BluetoothMap: onBluetoothStateChange: up=true
11-25 08:33:45.873  5661  5661 D BluetoothMap: Proxy object connected
11-25 08:33:45.873  5661  5661 D MapProfile: Bluetooth service connected
,11-25 08:33:45.873  5661  5661 D BluetoothMap: getConnectedDevices()
11-25 08:33:45.873  5883  5883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:45.874  3083  3930 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 08:33:45.875  5661  5661 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 08:33:45.875  5661  5661 D PanProfile: Bluetooth service connected
11-25 08:33:45.875  3083  3083 D BluetoothMap: Proxy object connected
11-25 08:33:45.875  3083  3083 D MapProfile: Bluetooth service connected
11-25 08:33:45.875  3083  3083 D BluetoothMap: getConnectedDevices()
11-25 08:33:45.876  5661  5675 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 08:33:45.876  5883  5883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:45.877  5883  5883 D ObexServerSockets: Succeed to create listening sockets 
11-25 08:33:45.877  5883  5883 D ObexServerSockets0: startAccept()
11-25 08:33:45.877  5883  5883 D ObexServerSockets0: prepareForNewConnect()
11-25 08:33:45.878  5661  5919 D BluetoothPbap: onBluetoothStateChange: up=true
,11-25 08:33:45.879  5883  5883 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 08:33:45.879  5883  5883 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 08:33:45.879  5883  5920 D ObexServerSockets0: Accepting socket connection...
11-25 08:33:45.880  5883  5921 D ObexServerSockets0: Accepting socket connection...
,11-25 08:33:45.880  3083  3095 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 08:33:45.881  3083  3083 D BluetoothInputDevice: Proxy object connected
11-25 08:33:45.881  5661  5678 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 08:33:45.881  3083  3083 D HidProfile: Bluetooth service connected
11-25 08:33:45.883  3753  3781 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:45.883   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:45.883   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 08:33:45.884  5661  5661 D BluetoothA2dp: Proxy object connected
11-25 08:33:45.884   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 08:33:45.885  5883  5883 D BluetoothMapService: onReceive
11-25 08:33:45.885  5883  5883 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 08:33:45.885  5883  5883 D BluetoothMapService: STATE_ON
11-25 08:33:45.886  5661  5661 D BluetoothInputDevice: Proxy object connected
,11-25 08:33:45.886  5661  5661 D HidProfile: Bluetooth service connected
11-25 08:33:45.888  5883  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 08:33:45.889  5883  5923 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 08:33:45.890  5883  5923 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 08:33:45.892  5661  5661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 08:33:45.900  3529  3529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 08:33:45.901  5661  5661 D DockEventReceiver: finishStartingService: stopping service
,11-25 08:33:45.907  5661  5661 D BluetoothPbap: Proxy object connected
,11-25 08:33:45.908  5661  5661 D PbapServerProfile: Bluetooth service connected
11-25 08:33:45.908  5883  5883 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 08:33:45.908  5883  5883 D ObexServerSockets0: prepareForNewConnect()
,11-25 08:33:45.909  3083  3083 D BluetoothPbap: Proxy object connected
11-25 08:33:45.909  3083  3083 D PbapServerProfile: Bluetooth service connected
11-25 08:33:45.910  5883  5926 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 08:33:45.934  5883  5932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 08:33:45.935  5883  5932 I BtOppRfcommListener: Accept thread started.
,11-25 08:33:45.971   931   931 D BluetoothHeadset: Proxy object connected
,11-25 08:33:45.971  5661  5675 D BluetoothHeadset: Proxy object connected
,11-25 08:33:45.971   931   931 D BluetoothHeadset: Proxy object connected
11-25 08:33:45.971   931   931 D BluetoothHeadset: Proxy object connected
11-25 08:33:45.972  5661  5661 D HeadsetProfile: Bluetooth service connected
11-25 08:33:45.972  3753  3985 D BluetoothHeadset: Proxy object connected
11-25 08:33:45.972  3083  3095 D BluetoothHeadset: Proxy object connected
11-25 08:33:45.972  3083  3083 D HeadsetProfile: Bluetooth service connected
,11-25 08:33:45.982  3083  3096 D BluetoothHeadset: Proxy object connected
,11-25 08:33:45.982  3083  3083 D HeadsetProfile: Bluetooth service connected
,11-25 08:33:45.984  3753  3776 D BluetoothHeadset: Proxy object connected
11-25 08:33:45.984   931   948 D BluetoothHeadset: Proxy object connected
,11-25 08:33:45.984   931   948 D BluetoothHeadset: Proxy object connected
,11-25 08:33:46.488   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:49.821  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 08:33:49.828  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 08:33:49.829  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:49.829  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6a575e removed from the list
11-25 08:33:49.829  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:49.834  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:49.834  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79a073f added. We now have 4 listener(s)
11-25 08:33:49.835  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:49.840   931  3767 D WifiService: setWifiEnabled: false pid=5603, uid=10077
,11-25 08:33:49.840   931  3767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 08:33:51.489   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:52.490   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:53.491   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:54.492   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:54.851  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 08:33:54.852   931  3147 D WifiService: setWifiEnabled: true pid=5603, uid=10077
,11-25 08:33:54.852   931  3147 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 08:33:54.860   509   928 D SoftapController: Softap fwReload - Ok
,11-25 08:33:54.867   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:54.867   509   928 D CommandListener: Trying to bring down wlan0
,11-25 08:33:54.870   509   928 D CommandListener: Clearing all IP addresses on wlan0
,11-25 08:33:54.874   931  2926 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 08:33:55.494   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:33:55.544   931  2926 D wifi    : set interface wlan0 flags (UP)
,11-25 08:33:55.545   931  2926 I WifiHAL : Initializing wifi
11-25 08:33:55.545   931  2926 I WifiHAL : Creating socket
,11-25 08:33:55.552   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 08:33:55.554   931  2926 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-25 08:33:55.554   931  2926 D wifi    : Did set static halHandle = 0x7f5ef2d300
11-25 08:33:55.554   931  2926 D wifi    : halHandle = 0x7f5ef2d300, mVM = 0x7f7b54d140, mCls = 0x2013e6
11-25 08:33:55.555   931  2926 D wifi    : array field set
,11-25 08:33:55.555   931  2926 I WifiNative-HAL: interface[0] = wlan0
,11-25 08:33:55.559   931  5937 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547053818624
11-25 08:33:55.559   931  5937 D wifi    : waitForHalEvents called, vm = 0x7f7b54d140, obj = 0x2013e6, env = 0x7f5cd3db00
,11-25 08:33:55.617  5938  5938 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 08:33:55.639  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 08:33:55.650  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 08:33:55.651  5938  5938 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 08:33:55.659   931  2926 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 08:33:55.675   931  2926 D WifiConfigStore: Loading config and enabling all networks 
,11-25 08:33:55.687   931  2926 D WifiConfigStore: loaded 0 passpoint configs
,11-25 08:33:55.687   931  2926 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-25 08:33:55.687   931  2926 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 08:33:55.688   931  2926 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 08:33:55.689   931  2926 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 08:33:55.689   931  2926 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-25 08:33:55.689   931  2926 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-25 08:33:55.689   931  2926 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 08:33:55.692  4985  4985 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 08:33:55.692   931  2926 D WifiNative-HAL: Setting external_sim to 1
11-25 08:33:55.693   931  2926 D wifi    : setting dfs flag to true, 0x7f5fd9cf40
11-25 08:33:55.693   931  2926 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 08:33:55.694   931  2926 D wifi    : setting scan oui 0x7f5fd9cf40
11-25 08:33:55.694   931  2926 D WifiHAL : Sending mac address OUI
,11-25 08:33:55.698   931  2926 E native  : do suspend false
,11-25 08:33:55.705   931  2926 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 08:33:55.706   931   931 D RttService: SCAN_AVAILABLE : 3
11-25 08:33:55.706   509   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-25 08:33:55.706   931  3036 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-25 08:33:55.707   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:55.712   931  2925 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
11-25 08:33:55.712   931  2925 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 08:33:55.726   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=243179 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-25 08:33:55.728   931  2925 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 08:33:55.728   931  2925 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-25 08:33:56.497   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 08:33:58.773  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 08:33:58.802  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 08:33:58.814  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 08:33:58.857   931  2926 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 08:33:58.858   931  2926 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 08:33:58.859   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:58.871   931  2926 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 08:33:58.905   931  2926 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 08:33:58.907  5938  5938 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 08:33:59.677  5938  5938 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 08:33:59.713  5938  5938 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 08:33:59.715  5938  5938 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 08:33:59.723   931  2926 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 08:33:59.724   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
11-25 08:33:59.724   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:59.742   931  2926 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 08:33:59.755   509   928 D CommandListener: Setting iface cfg
,11-25 08:33:59.759   931  2926 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 08:33:59.764   931  5943 D DhcpClient: Receive thread started
,11-25 08:33:59.768   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:33:59.768   931  2926 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 08:33:59.768   931  2928 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 08:33:59.848   931  2926 E native  : do suspend false
,11-25 08:33:59.861   931  5942 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 08:33:59.871  5603  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 08:33:59.874   931  5943 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
11-25 08:33:59.875   931  5942 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
11-25 08:33:59.876  5603  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 08:33:59.877   931  5942 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
11-25 08:33:59.877  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:59.877  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79a073f removed from the list
,11-25 08:33:59.877  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:33:59.886  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-25 08:33:59.888  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-25 08:33:59.893  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8244ee0 Bundle[{}]
11-25 08:33:59.893  5603  5649 I io.jxcore.node.LifeCycleMonitor: start: OK
11-25 08:33:59.894   931  5943 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-25 08:33:59.894  5603  5649 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-25 08:33:59.894   931  5942 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 08:33:59.895  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-25 08:33:59.896  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-25 08:33:59.896   509   928 D CommandListener: Setting iface cfg
11-25 08:33:59.897  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-25 08:33:59.898  5603  5649 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-25 08:33:59.899   931  2926 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
11-25 08:33:59.901   931  5942 D DhcpClient: Scheduling renewal in 86399s
,11-25 08:33:59.906  5603  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-25 08:33:59.907  5603  5649 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 08:33:59.907  5603  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-25 08:33:59.910  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 08:33:59.910  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@484780c added. We now have 3 listener(s)
,11-25 08:33:59.911   931  2926 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 08:33:59.911   931  2926 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 08:33:59.911  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:33:59.912  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:33:59.912   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 08:33:59.912  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 08:33:59.912  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:59.912  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e42f555 added. We now have 4 listener(s)
11-25 08:33:59.912  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:33:59.912  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 08:33:59.913   931  2926 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-25 08:33:59.914  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:33:59.914  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e008b6a added. We now have 4 listener(s)
11-25 08:33:59.916  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:33:59.916  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:33:59.916  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:33:59.916  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:59.917  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb1d85b added. We now have 5 listener(s)
11-25 08:33:59.917  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:33:59.917  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:59.917  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:59.917  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:59.917  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:59.917  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:59.917  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:33:59.917   931  2928 D ConnectivityService: Adding iface wlan0 to network 102
11-25 08:33:59.917  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@484780c removed from the list
11-25 08:33:59.917  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:59.917  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e42f555 removed from the list
11-25 08:33:59.917  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:59.918  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.918  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.919  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.920  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.920  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.920  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:59.920  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:59.920  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:59.920  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e42f555 not in the list
11-25 08:33:59.920  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.920  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.923  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.923  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.923  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.923  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:59.923  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:59.923  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 08:33:59.923  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb1d85b removed from the list
11-25 08:33:59.923  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:59.924  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:59.924  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:33:59.924  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e008b6a removed from the list
11-25 08:33:59.925  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:33:59.925  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30708f8 added. We now have 3 listener(s)
11-25 08:33:59.926  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:33:59.927  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:33:59.927  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 08:33:59.927  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:33:59.927  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a91d1 added. We now have 4 listener(s)
11-25 08:33:59.927  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:33:59.927  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 08:33:59.929  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:33:59.929  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a13f436 added. We now have 4 listener(s)
,11-25 08:33:59.931  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:33:59.931  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:33:59.931  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 08:33:59.931  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 08:33:59.931  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab9f37 added. We now have 5 listener(s)
11-25 08:33:59.931  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:33:59.931  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:33:59.931  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 08:33:59.932  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 08:33:59.932  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:33:59.932  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 08:33:59.933  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 08:33:59.936  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 08:33:59.936  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 08:33:59.936  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 08:33:59.939  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.940  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 08:33:59.940  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 08:33:59.940  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 08:33:59.940  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 08:33:59.944  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.944  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 08:33:59.944  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 08:33:59.944  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-25 08:33:59.944  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 08:33:59.944  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.945  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:33:59.947   931  2928 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-25 08:33:59.947   931  2928 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-25 08:33:59.948  5883  5911 D BtGatt.GattService: registerClient() - UUID=c603f200-f702-463b-be2f-954fc8427ca1
11-25 08:33:59.948   931  2928 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-25 08:33:59.949  5883  5899 D BtGatt.GattService: onClientRegistered() - UUID=c603f200-f702-463b-be2f-954fc8427ca1, clientIf=5
,11-25 08:33:59.950   931  2928 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 08:33:59.950  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 08:33:59.951  5883  5922 D BtGatt.GattService: start scan with filters
11-25 08:33:59.953   931  2928 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-25 08:33:59.955  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 08:33:59.955  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.955  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 08:33:59.955  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.955  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 08:33:59.955  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 08:33:59.956  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.956  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 08:33:59.956  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 08:33:59.956  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.956  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.956  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.956  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.957  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 08:33:59.957  5883  5902 D BtGatt.ScanManager: handling starting scan
11-25 08:33:59.957  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.959   931  2928 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 08:33:59.959  5883  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3453c9d
11-25 08:33:59.960  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.960  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:33:59.960  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.960  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.960  5603  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 08:33:59.960  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.960  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:59.961  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 08:33:59.961  5603  5649 W org.thaliproject.p2p.btconnect,orlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:33:59.961  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:33:59.961  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:59.961  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 08:33:59.963  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.963  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.963  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.963  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 08:33:59.963  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.963  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 08:33:59.963  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.964   931  2928 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-25 08:33:59.964   931  2928 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-25 08:33:59.964   931  2928 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-25 08:33:59.964   931  2928 D ConnectivityService:    accepting network in place of null
11-25 08:33:59.964   931  2926 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 08:33:59.964   931  2926 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 08:33:59.964  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:33:59.964   931  2928 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-25 08:33:59.965  5883  5922 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 08:33:59.965  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 08:33:59.966  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:33:59.966  5883  5899 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 08:33:59.966  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:33:59.967  5883  5894 D BtGatt.GattService: stopScan() - queue size =1
,11-25 08:33:59.967  5883  5902 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 08:33:59.967  5883  5893 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.968  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 08:33:59.968  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 08:33:59.969  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 08:33:59.970  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.973  5883  5899 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 08:33:59.973  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:33:59.973  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.973  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 08:33:59.973  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.973  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.973  5883  5902 D BtGatt.ScanManager: Starting BLE batch scan
11-25 08:33:59.973  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:33:59.973  5883  5902 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 08:33:59.975  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 08:33:59.975  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.975  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:33:59.975  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.975  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.977  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.977  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.977  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:33:59.977  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:33:59.977  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:33:59.977  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:33:59.977  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:59.977  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:59.977  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:33:59.978  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30708f8 removed from the list
11-25 08:33:59.978  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:59.978  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a91d1 removed from the list
11-25 08:33:59.978  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:33:59.978  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.978  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.979  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.979  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.979  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.979  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:59.979  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:59.979  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11,-25 08:33:59.979   931  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=247432, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-25 08:33:59.980  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68a91d1 not in the list
11-25 08:33:59.980  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.980  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.981  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.981  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.981  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:33:59.981  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:33:59.981  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:33:59.981  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:33:59.981  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab9f37 removed from the list
11-25 08:33:59.981  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:33:59.981  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:33:59.981  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:33:59.982  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a13f436 removed from the list
11-25 08:33:59.982  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:33:59.982  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7edff10 added. We now have 3 listener(s)
11-25 08:33:59.983  5883  5899 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 08:33:59.983  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:33:59.983  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:33:59.984  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:33:59.984  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:33:59.984  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:33:59.984  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6caa09 added. We now have 4 listener(s)
11-25 08:33:59.984  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:33:59.984  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 08:33:59.987  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 08:33:59.987  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@809540e added. We now have 4 listener(s)
,11-25 08:33:59.988  5883  5899 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 08:33:59.988  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:33:59.989   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 08:33:59.989  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:33:59.989  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:33:59.989  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:33:59.989  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:33:59.989  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4693e2f added. We now have 5 listener(s)
11-25 08:33:59.989  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 08:33:59.989  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 08:33:59.990  5883  5902 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:33:59.990  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:33:59.990  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 08:33:59.990  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 08:33:59.990  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:33:59.990  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 08:33:59.992  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 08:33:59.994  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 08:33:59.994  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 08:33:59.994  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 08:33:59.995  5883  5899 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 08:33:59.996  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:33:59.996  5883  5899 E BtGatt.ContextMap: Context not found for ID 5
,11-25 08:33:59.999  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:33:59.999  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 08:34:00.000  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 08:34:00.000  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 08:34:00.000  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 08:34:00.002  5883  5899 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 08:34:00.002  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 08:34:00.003  5883  5902 D BtGatt.ScanManager: stopping BLe Batch
,11-25 08:34:00.005  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:34:00.005  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 08:34:00.005  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 08:34:00.005  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 08:34:00.005  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 08:34:00.005  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.007  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:34:00.008  5883  5899 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 08:34:00.008  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.008  5883  5902 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 08:34:00.009  5883  5924 D BtGatt.GattService: registerClient() - UUID=8e1a20fa-fb51-48a6-9445-a5d20f6ac107
,11-25 08:34:00.010  5883  5899 D BtGatt.GattService: onClientRegistered() - UUID=8e1a20fa-fb51-48a6-9445-a5d20f6ac107, clientIf=5
,11-25 08:34:00.011  5603  5614 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 08:34:00.011  5883  5922 D BtGatt.GattService: start scan with filters
11-25 08:34:00.014  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 08:34:00.014  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:34:00.014  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 08:34:00.014  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.014  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 08:34:00.015  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 08:34:00.015  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.015  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 08:34:00.015  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 08:34:00.015  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 08:34:00.015  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.015  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.015  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.015   509   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 08:34:00.016  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 08:34:00.016  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:34:00.016  5883  5899 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-25 08:34:00.016  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.016  5883  5899 D BtGatt.GattService: current time is 247469426311
,11-25 08:34:00.016  5883  5899 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -65, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 08:34:00.017  5883  5899 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 08:34:00.018  5883  5902 D BtGatt.ScanManager: handling starting scan
11-25 08:34:00.021   931  2928 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-25 08:34:00.021   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 08:34:00.021  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.021  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:34:00.021  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.021  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.021  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.022   931  2928 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-25 08:34:00.023   931   948 D Tethering: MasterInitialState.processMessage what=3
11-25 08:34:00.023  3728  3867 W QCNEJ   : |CORE| network available: 102
11-25 08:34:00.025  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:34:00.025  5603  5649 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 08:34:00.025  3728  3867 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-25 08:34:00.025  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:34:00.025  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:34:00.025  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:34:00.025  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:34:00.025  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.025  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:34:00.025  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:34:00.025  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:34:00.025  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7edff10 removed from the list
11-25 08:34:00.025  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.025  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6caa09 removed from the list
11-25 08:34:00.025  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:34:00.025  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.025  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:34:00.026  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.026  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-25 08:34:00.026  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 08:34:00.026  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.026  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:34:00.026  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.026  3728  3867 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 08:34:00.026  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.026  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.026  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.027  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:34:00.027  3728  3867 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 08:34:00.027  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.027  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.028  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.028  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:34:00.028  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:34:00.028  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.028  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6caa09 not in the list
11-25 08:34:00.028  5883  5899 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 08:34:00.028  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 08:34:00.028  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.028  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.028  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 08:34:00.028  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:34:00.028  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.028  5883  5902 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 08:34:00.028  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.029  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.029  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 08:34:00.029  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.029  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:34:00.030  5883  5922 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 08:34:00.030  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 08:34:00.031  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:34:00.032  5883  5893 D BtGatt.GattService: stopScan() - queue size =1
11-25 08:34:00.032  5883  5924 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.034  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.035  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.035  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 08:34:00.035  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 08:34:00.035  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 08:34:00.035  5883  5899 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 08:34:00.035  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.036  5883  5902 D BtGatt.ScanManager: Starting BLE batch scan
11-25 08:34:00.036  5883  5902 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 08:34:00.036  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 08:34:00.037  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.037  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:34:00.037  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.037  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.038  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:34:00.038  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:34:00.038  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.038  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4693e2f removed from the list
11-25 08:34:00.038  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:34:00.038  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:34:00.038  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:34:00.038  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@809540e removed from the list
11-25 08:34:00.038  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 08:34:00.038  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 08:34:00.038  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 08:34:00.038  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.038  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 08:34:00.038  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 08:34:00.039  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.039  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.039  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 08:34:00.039  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:34:00.039  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:34:00.039  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4caa028 added. We now have 3 listener(s)
,11-25 08:34:00.039  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 08:34:00.039  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.040  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:34:00.040  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 08:34:00.040  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 08:34:00.041  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:34:00.041  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e029141 added. We now have 4 listener(s)
11-25 08:34:00.041  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:34:00.041  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 08:34:00.041  5010  5033 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 08:34:00.042  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.042  5010  5033 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 08:34:00.042  5010  5033 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 08:34:00.042  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.042  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 08:34:00.042  5010  5033 E SarControlService: no key has been found,reset the power
11-25 08:34:00.042  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 08:34:00.042  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:34:00.042  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 08:34:00.042  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89fd6e6 added. We now have 4 listener(s)
11-25 08:34:00.042  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 08:34:00.043  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:34:00.043  5035  5035 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 08:34:00.043  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:34:00.043  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:34:00.043  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:34:00.043  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:34:00.043  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cc427 added. We now have 5 listener(s)
11-25 08:34:00.044  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:34:00.044  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:34:00.044  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 08:34:00.044  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 08:34:00.044  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 08:34:00.044  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 08:34:00.044  5010  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 08:34:00.044  5010  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 08:34:00.044  5010  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 08:34:00.045  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 08:34:00.045  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 08:34:00.045  5035  5035 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 08:34:00.046  5883  5899 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 08:34:00.046  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.047  3677  3677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 08:34:00.050  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManage,r: startBlePeerDiscoverer
11-25 08:34:00.050  5603  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 08:34:00.050  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 08:34:00.050  3677  3677 D SystemUpdateService: onCreate
11-25 08:34:00.051  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000f003000000000000ffffffff]
11-25 08:34:00.051  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:34:00.051  5035  5049 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-25 08:34:00.052  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:34:00.052  5010  5021 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 08:34:00.053  5883  5899 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 08:34:00.053  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.054  5883  5902 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:34:00.055  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.055  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 08:34:00.055  3677  3677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 08:34:00.055  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 08:34:00.055  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 08:34:00.055  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 08:34:00.056  5035  5049 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ab420dc HexData = [00000000f103000000000000ffffffff]
11-25 08:34:00.056  5035  5049 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 08:34:00.056  5035  5049 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-25 08:34:00.057  5035  5035 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 08:34:00.057  5010  5020 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 08:34:00.059  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.059  5883  5899 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:34:00.059  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 08:34:00.059  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.059  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 08:34:00.059  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 08:34:00.059  5883  5899 E BtGatt.ContextMap: Context not found for ID 5
11-25 08:34:00.059  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 08:34:00.059  5603  5649 D org.thaliproject.p2p.bt,connectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.060  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:34:00.062  5883  5893 D BtGatt.GattService: registerClient() - UUID=88a53fc3-dfdc-499e-90ea-bc6257e2a1a9
11-25 08:34:00.062  5883  5899 D BtGatt.GattService: onClientRegistered() - UUID=88a53fc3-dfdc-499e-90ea-bc6257e2a1a9, clientIf=5
11-25 08:34:00.062  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 08:34:00.063  5883  5924 D BtGatt.GattService: start scan with filters
11-25 08:34:00.065  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 08:34:00.065  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.065  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 08:34:00.065  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.065  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 08:34:00.065  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 08:34:00.065  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.066  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 08:34:00.066  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 08:34:00.066  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.066  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.066  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.066  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.066  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 08:34:00.066  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.068  5883  5899 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 08:34:00.068  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.068  5883  5902 D BtGatt.ScanManager: stopping BLe Batch
11-25 08:34:00.069  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.069  3677  3677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-25 08:34:00.069  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:34:00.069  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.069  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.069  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.074  5883  5899 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 08:34:00.074  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.074  5883  5902 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:34:00.076  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:34:00.076  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:34:00.076  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:34:00.076  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:34:00.076  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.076  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:34:00.076  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:34:00.076  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:34:00.076  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4caa028 removed from the list
11-25 08:34:00.076  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.077  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e029141 removed from the list
11-25 08:34:00.077  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-25 08:34:00.077  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.077  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:34:00.077  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.077  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.077  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 08:34:00.077  5603  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 08:34:00.077  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 08:34:00.077  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.077  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.077  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.078  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.078  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 08:34:00.079   931  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.079  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:34:00.079  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:34:00.079  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.079  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e029141 not in the list
11-25 08:34:00.079  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.079  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.080  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.080  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 08:34:00.080  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.080  3677  5370 I iu.UploadsManager: num queued entries: 0
11-25 08:34:00.080  5883  5899 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:34:00.080  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.080  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:34:00.080  3677  5954 I SystemUpdateService: active receiver: enabled
11-25 08:34:00.080  5883  5924 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 08:34:00.081  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 08:34:00.082  5883  5902 D BtGatt.ScanManager: handling starting scan
11-25 08:34:00.082  5603  5649 D BluetoothAdapter: STATE_ON
11-25 08:34:00.083  5883  5893 D BtGatt.GattService: stopScan() - queue size =1
11-25 08:34:00.083  3677  3677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 08:34:00.083  5883  5922 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.084  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 08:34:00.084  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 08:34:00.084  3677  3677 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-25 08:34:00.085  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 08:34:00.086  5734  5734 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 08:34:00.087  5883  5899 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 08:34:00.087  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.087  5883  5902 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 08:34:00.087  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.088  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.088  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:34:00.089  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.089  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.089  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:34:00.089  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:34:00.089  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.089  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:34:00.089  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6cc427 removed from the list
11-25 08:34:00.089  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:34:00.089  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 08:34:00.089  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:34:00.089  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:34:00.089  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 08:34:00.089  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89fd6e6 removed from the list
11-25 08:34:00.089  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.089  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 08:34:00.089  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 08:34:00.089  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.089  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.089  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.089  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 08:34:00.090  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.090  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:34:00.090  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.090  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7474c40 added. We now have 3 listener(s)
11-25 08:34:00.091  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.091  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.091  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 08:34:00.093  5883  5899 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 08:34:00.093  5734  5734 D SprintDMHelper: simOperator: 
11-25 08:34:00.093  5734  5734 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 08:34:00.093  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.093  5883  5902 D BtGatt.ScanManager: Starting BLE batch scan
11-25 08:34:00.093  5883  5902 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 08:34:00.094  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:34:00.094  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-,0800200c9a66
11-25 08:34:00.094  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:34:00.094  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:34:00.094  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c172779 added. We now have 4 listener(s)
11-25 08:34:00.094  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:34:00.095  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 08:34:00.096  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 08:34:00.096  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478dcbe added. We now have 4 listener(s)
11-25 08:34:00.097  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 08:34:00.097  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 08:34:00.097  5603  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 08:34:00.097  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 08:34:00.097  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac111f added. We now have 5 listener(s)
11-25 08:34:00.097  5603  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 08:34:00.097  5603  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 08:34:00.098  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:34:00.098  5603  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 08:34:00.098  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:34:00.098  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:34:00.098  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:34:00.098  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7474c40 removed from the list
11-25 08:34:00.098  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.098  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c172779 removed from the list
11-25 08:34:00.098  5603  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 08:34:00.098  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.098  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.099  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.099  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.099  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.099  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:34:00.099  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:34:00.099  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.099  5603  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c172779 not in the list
11-25 08:34:00.099  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.099  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.100  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.100  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.100  5603  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 08:34:00.101  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 08:34:00.101  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 08:34:00.101  5603  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 08:34:00.101  5603  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac111f removed from the list
11-25 08:34:00.101  5603  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 08:34:00.101  5603  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 08:34:00.101  5603  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 08:34:00.101  5603  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@478dcbe removed from the list
11-25 08:34:00.102  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 08:34:00.102  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 08:34:00.102  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 08:34:00.103  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:34:00.103  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 08:34:00.103  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 08:34:00.105  3677  5370 I iu.UploadsManager: num updated entries: 0
11-25 08:34:00.106  3677  5370 I iu.SyncManager: NEXT; no task
11-25 08:34:00.106  5883  5899 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 08:34:00.106  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.113  5883  5899 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 08:34:00.113  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.114  5883  5902 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:34:00.120  5883  5899 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:34:00.120  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.120  5883  5899 E BtGatt.ContextMap: Context not found for ID 5
11-25 08:34:00.121  3677  5954 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-25 08:34:00.128  5883  5899 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 08:34:00.128  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.128  5883  5902 D BtGatt.ScanManager: stopping BLe Batch
11-25 08:34:00.134  5883  5899 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 08:34:00.134  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.134  5883  5902 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 08:34:00.134  3677  5954 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-25 08:34:00.134  3677  5954 I SystemUpdateService: now status is 0 (complete)
11-25 08:34:00.135  3677  5954 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 08:34:00.135  3677  5954 I SystemUpdateService: file has been verified
11-25 08:34:00.135  3677  5954 I SystemUpdateService: OTA package size = 21989297
11-25 08:34:00.140  5883  5899 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 08:34:00.140  5883  5899 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 08:34:00.141  3677  5954 I SystemUpdateService: showing system update notification
11-25 08:34:00.142   931  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 13:34:00 GMT], X-Android-Received-Millis=[1480080840141], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480080840104]}
11-25 08:34:00.142   931  2928 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 08:34:00.142   931  2928 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-25 08:34:00.142   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 08:34:00.143   931  2928 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 08:34:00.152  3677  3677 D SystemUpdateService: onDestroy
,11-25 08:34:00.241  4985  5959 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 08:34:00.476  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 08:34:00.539  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 08:34:00.590  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 08:34:02.254  5603  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 08:34:02.254  5603  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:02.791   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:34:03.048  5603  5966 W !!      : call onHalfStreamCopied
,11-25 08:34:03.048  5603  5966 I testCopyDataAndClose: closing input stream
,11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 08:34:03.823  5603  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 08:34:06.498   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:07.499   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:07.631  5603  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:07.631  5603  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:07.969   931  2928 D ConnectivityService: handlePromptUnvalidated 102
,11-25 08:34:08.501   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:09.502   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:09.630  5603  5649 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-25 08:34:09.630  5603  5649 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:09.631  5603  5649 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-25 08:34:09.728  5603  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 08:34:09.728  5603  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:09.728  5603  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-25 08:34:09.769  5603  5968 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 08:34:09.769  5603  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:10.503   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:10.729   931  2926 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 08:34:11.395  5603  5968 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 08:34:11.504   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 08:34:11.853   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:34:14.882   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:34:15.123  5603  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:15.123  5603  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:15.123  5603  5969 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:15.123  5603  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 08:34:15.124  5603  5969 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 08:34:15.125  5603  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:15.125  5603  5969 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-25 08:34:15.126  5603  5649 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-25 08:34:15.130  5603  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:15.130  5603  5970 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 08:34:15.131  5603  5970 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,11-25 08:34:15.131  5603  5970 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:15.131  5603  5970 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-25 08:34:15.131  5603  5970 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-25 08:34:15.131  5603  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-25 08:34:15.131  5603  5970 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 08:34:15.135  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 08:34:15.135  5603  5649 I jxcore-log: 
11-25 08:34:15.135  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 08:34:15.135  5603  5649 I jxcore-log: 
11-25 08:34:15.135  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 08:34:15.135  5603  5649 I jxcore-log: 
11-25 08:34:15.135  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 08:34:15.135  5603  5649 I jxcore-log: 
,11-25 08:34:15.136  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'Total duration:  90810'
11-25 08:34:15.136  5603  5649 I jxcore-log: 
11-25 08:34:15.138  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 08:34:15.138  5603  5649 I jxcore-log: 
,11-25 08:34:15.141  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 08:34:15.141  5603  5649 I jxcore-log: 
,11-25 08:34:15.142  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 08:34:15.142  5603  5649 I jxcore-log: 
11-25 08:34:15.142  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 08:34:15.142  5603  5649 I jxcore-log: 
11-25 08:34:15.142  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 08:34:15.142  5603  5649 I jxcore-log: 
11-25 08:34:15.143  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.143  5603  5649 I jxcore-log: 
11-25 08:34:15.143  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 08:34:15.143  5603  5649 I jxcore-log: 
11-25 08:34:15.143  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.143  5603  5649 I jxcore-log: 
11-25 08:34:15.144  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 08:34:15.144  5603  5649 I jxcore-log: 
,11-25 08:34:15.144  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 08:34:15.144  5603  5649 I jxcore-log: 
11-25 08:34:15.144  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 08:34:15.144  5603  5649 I jxcore-log: 
11-25 08:34:15.145  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 08:34:15.145  5603  5649 I jxcore-log: 
11-25 08:34:15.145  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.145  5603  5649 I jxcore-log: 
11-25 08:34:15.145  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 08:34:15.145  5603  5649 I jxcore-log: 
11-25 08:34:15.145  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.145  5603  5649 I jxcore-log: 
11-25 08:34:15.145  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 08:34:15.145  5603  5649 I jxcore-log: 
,11-25 08:34:15.146  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.146  5603  5649 I jxcore-log: 
11-25 08:34:15.146  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 08:34:15.146  5603  5649 I jxcore-log: 
11-25 08:34:15.146  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 08:34:15.146  5603  5649 I jxcore-log: 
11-25 08:34:15.146  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 08:34:15.146  5603  5649 I jxcore-log: 
11-25 08:34:15.147  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 08:34:15.147  5603  5649 I jxcore-log: 
11-25 08:34:15.147  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 08:34:15.147  5603  5649 I jxcore-log: 
11-25 08:34:15.147  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 08:34:15.147  5603  5649 I jxcore-log: 
,11-25 08:34:15.147  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 08:34:15.147  5603  5649 I jxcore-log: 
11-25 08:34:15.148  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 08:34:15.148  5603  5649 I jxcore-log: 
11-25 08:34:15.149  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 08:34:15.149  5603  5649 I jxcore-log: 
11-25 08:34:15.149  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 08:34:15.149  5603  5649 I jxcore-log: 
,11-25 08:34:15.150  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-25 08:34:15.150  5603  5649 I jxcore-log: 
11-25 08:34:15.150  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 08:34:15.150  5603  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-25 08:34:15.150  5603  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 08:34:15.150  5603  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-25 08:34:15.150  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 08:34:15.150  5603  5649 I jxcore-log: 
11-25 08:34:15.151  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.151  5603  5649 I jxcore-log: 
11-25 08:34:15.151  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 08:34:15.151  5603  5649 I jxcore-log: 
11-25 08:34:15.151  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.151  5603  5649 I jxcore-log: 
11-25 08:34:15.151  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 08:34:15.151  5603  5649 I jxcore-log: 
11-25 08:34:15.151  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 08:34:15.151  5603  5649 I jxcore-log: 
,11-25 08:34:15.155  5603  5603 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 08:34:15.155  5603  5603 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-25 08:34:15.156  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 08:34:15.156  5603  5649 I jxcore-log: 
11-25 08:34:15.156  5603  5649 I jxcore-log: 2016-11-25 13:34:15 - WARN testUtils: 'myNameCallback not set!'
11-25 08:34:15.156  5603  5649 I jxcore-log: 
,11-25 08:34:17.230  5603  5649 I jxcore-log: 2016-11-25 13:34:17 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 08:34:17.230  5603  5649 I jxcore-log: 
,11-25 08:34:17.232  5603  5649 I jxcore-log: 2016-11-25 13:34:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 08:34:17.232  5603  5649 I jxcore-log: 
,11-25 08:34:17.582  5603  5649 I jxcore-log: 2016-11-25 13:34:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 08:34:17.582  5603  5649 I jxcore-log: 
,11-25 08:34:17.594  5603  5649 I jxcore-log: 2016-11-25 13:34:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 08:34:17.594  5603  5649 I jxcore-log: 
,11-25 08:34:18.711  5603  5649 I jxcore-log: 2016-11-25 13:34:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 08:34:18.711  5603  5649 I jxcore-log: 
,11-25 08:34:18.902  5603  5649 I jxcore-log: 2016-11-25 13:34:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 08:34:18.902  5603  5649 I jxcore-log: 
,11-25 08:34:18.908  5603  5649 I jxcore-log: 2016-11-25 13:34:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 08:34:18.908  5603  5649 I jxcore-log: 
,11-25 08:34:18.912  5603  5649 I jxcore-log: 2016-11-25 13:34:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 08:34:18.912  5603  5649 I jxcore-log: 
,11-25 08:34:19.392  5603  5649 I jxcore-log: 2016-11-25 13:34:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 08:34:19.392  5603  5649 I jxcore-log: 
,11-25 08:34:19.438  5603  5649 I jxcore-log: 2016-11-25 13:34:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 08:34:19.438  5603  5649 I jxcore-log: 
,11-25 08:34:19.451  5603  5649 I jxcore-log: 2016-11-25 13:34:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 08:34:19.451  5603  5649 I jxcore-log: 
,11-25 08:34:19.455  5603  5649 I jxcore-log: 2016-11-25 13:34:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 08:34:19.455  5603  5649 I jxcore-log: 
,11-25 08:34:19.731  5603  5649 I jxcore-log: 2016-11-25 13:34:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 08:34:19.731  5603  5649 I jxcore-log: 
,11-25 08:34:19.860  5603  5649 I jxcore-log: 2016-11-25 13:34:19 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 08:34:19.860  5603  5649 I jxcore-log: 
,11-25 08:34:20.232  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 08:34:20.232  5603  5649 I jxcore-log: 
,11-25 08:34:20.242  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 08:34:20.242  5603  5649 I jxcore-log: 
,11-25 08:34:20.246  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 08:34:20.246  5603  5649 I jxcore-log: 
,11-25 08:34:20.251  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 08:34:20.251  5603  5649 I jxcore-log: 
,11-25 08:34:20.257  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 08:34:20.257  5603  5649 I jxcore-log: 
,11-25 08:34:20.286  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 08:34:20.286  5603  5649 I jxcore-log: 
,11-25 08:34:20.324  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 08:34:20.324  5603  5649 I jxcore-log: 
,11-25 08:34:20.332  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 08:34:20.332  5603  5649 I jxcore-log: 
,11-25 08:34:20.338  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 08:34:20.338  5603  5649 I jxcore-log: 
,11-25 08:34:20.353  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 08:34:20.353  5603  5649 I jxcore-log: 
,11-25 08:34:20.369  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 08:34:20.369  5603  5649 I jxcore-log: 
,11-25 08:34:20.375  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 08:34:20.375  5603  5649 I jxcore-log: 
,11-25 08:34:20.380  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 08:34:20.380  5603  5649 I jxcore-log: 
,11-25 08:34:20.394  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 08:34:20.394  5603  5649 I jxcore-log: 
,11-25 08:34:20.411  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 08:34:20.411  5603  5649 I jxcore-log: 
,11-25 08:34:20.425  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 08:34:20.425  5603  5649 I jxcore-log: 
,11-25 08:34:20.436  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 08:34:20.436  5603  5649 I jxcore-log: 
,11-25 08:34:20.449  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 08:34:20.449  5603  5649 I jxcore-log: 
,11-25 08:34:20.459  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 08:34:20.459  5603  5649 I jxcore-log: 
,11-25 08:34:20.472  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 08:34:20.472  5603  5649 I jxcore-log: 
,11-25 08:34:20.482  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 08:34:20.482  5603  5649 I jxcore-log: 
,11-25 08:34:20.488  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 08:34:20.488  5603  5649 I jxcore-log: 
,11-25 08:34:20.511  5603  5649 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 08:34:20.512  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 08:34:20.512  5603  5649 I jxcore-log: 
,11-25 08:34:20.545  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 08:34:20.545  5603  5649 I jxcore-log: 
,11-25 08:34:20.747  5603  5649 I jxcore-log: 2016-11-25 13:34:20 - DEBUG CoordinatedClient: 'connected to the test server'
11-25 08:34:20.747  5603  5649 I jxcore-log: 
,11-25 08:34:26.504   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:27.506   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:28.507   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:29.509   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:30.510   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:31.511   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 08:34:39.073   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:34:39.918   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:34:42.110   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:34:51.513   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:52.514   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:53.515   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:54.517   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:55.518   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:34:56.519   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 08:35:03.274   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:35:06.309   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:35:19.923   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:35:21.520   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 08:35:21.521   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 08:35:36.522   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:37.523   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:38.524   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:39.526   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:39.925   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:35:40.527   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:41.528   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 08:35:46.529   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:47.531   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:48.532   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:49.534   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:50.535   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:35:51.536   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 08:36:01.537   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:02.539   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:03.540   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:04.541   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:05.543   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:06.543   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 08:36:19.930   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:36:21.544   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:22.545   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:23.547   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:24.548   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:25.549   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:26.550   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 08:36:28.054   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:36:31.087   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:36:39.933   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:36:46.551   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:47.552   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:48.554   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:49.245   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:36:49.555   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:50.557   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:36:51.558   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 08:36:52.276   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:36:59.934   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:37:01.353   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:37:07.417   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:37:16.558   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 08:37:16.559   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 08:37:19.530   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:37:25.581   931  2928 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 08:37:36.560   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:37:37.562   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:37:38.563   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:37:39.366  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-25 08:37:39.366  5603  5649 I jxcore-log: 
,11-25 08:37:39.564   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:37:39.625  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 08:37:39.625  5603  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 08:37:39.625  5603  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 08:37:39.625  5603  5649 I jxcore-log: emit@events.js:82:1
11-25 08:37:39.625  5603  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 08:37:39.625  5603  5649 I jxcore-log: emit@events.js:82:1''
11-25 08:37:39.625  5603  5649 I jxcore-log: 
,11-25 08:37:39.626  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedClient: 'test client failed'
11-25 08:37:39.626  5603  5649 I jxcore-log: 
,11-25 08:37:39.637  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 08:37:39.637  5603  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 08:37:39.637  5603  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 08:37:39.637  5603  5649 I jxcore-log: emit@events.js:82:1
11-25 08:37:39.637  5603  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 08:37:39.637  5603  5649 I jxcore-log: emit@events.js:82:1''
11-25 08:37:39.637  5603  5649 I jxcore-log: 
,11-25 08:37:39.638  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedClient: 'test client failed'
11-25 08:37:39.638  5603  5649 I jxcore-log: 
,11-25 08:37:39.643  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 08:37:39.643  5603  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 08:37:39.643  5603  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 08:37:39.643  5603  5649 I jxcore-log: emit@events.js:82:1
11-25 08:37:39.643  5603  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 08:37:39.643  5603  5649 I jxcore-log: emit@events.js:82:1''
11-25 08:37:39.643  5603  5649 I jxcore-log: 
,11-25 08:37:39.644  5603  5649 I jxcore-log: 2016-11-25 13:37:39 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 08:37:39.644  5603  5649 I jxcore-log: 
,11-25 08:37:39.937   931  2926 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 08:37:40.262  5982  5982 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 08:37:40.286  5982  5982 D AndroidRuntime: CheckJNI is OFF
,11-25 08:37:40.315  5982  5982 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 08:37:40.347  5982  5982 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 08:37:40.363  5982  5982 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 08:37:40.371   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 08:37:40.372   931   944 I ActivityManager: Killing 5603:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 08:37:40.467   931  2927 D WifiService: Client connection lost with reason: 4
,11-25 08:37:40.467   931   941 D GraphicsStats: Buffer count: 2
11-25 08:37:40.468   931   941 I WindowState: WIN DEATH: Window{83dfca8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-25 08:37:40.497   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-25 08:37:40.502   931   954 I art     : Starting a blocking GC Explicit
,11-25 08:37:40.499   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-25 08:37:40.506   931   944 E ActivityManager: Failure starting process com.test.thalitest
11-25 08:37:40.506   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-25 08:37:40.506   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:40.506   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.506   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 08:37:40.506   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-25 08:37:40.507   931   944 I ActivityManager:   Force finishing activity ActivityRecord{e9a0365 u0 com.test.thalitest/.MainActivity t10}
,11-25 08:37:40.515   931  3369 W ActivityManager: Spurious death for ProcessRecord{6bdc347 0:com.test.thalitest/u0a77}, curProc for 5603: null
,11-25 08:37:40.519   931   949 W WindowManager: Attempted to add application window with unknown token Token{9ba683a ActivityRecord{e9a0365 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-25 08:37:40.520   931   949 W WindowManager: Token{9ba683a ActivityRecord{e9a0365 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{9ba683a ActivityRecord{e9a0365 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-25 08:37:40.520   931   949 W WindowManager: view not successfully added to wm, removing view
11-25 08:37:40.520   931   949 W WindowManager: Exception when adding starting window
11-25 08:37:40.520   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{165385e V.E...... R.....ID 0,0-0,0} not attached to window manager
11-25 08:37:40.520   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-25 08:37:40.520   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-25 08:37:40.520   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-25 08:37:40.520   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-25 08:37:40.520   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-25 08:37:40.520   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:40.520   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.520   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 08:37:40.520   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-25 08:37:40.565   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 08:37:40.600   931   954 I art     : Explicit concurrent mark sweep GC freed 113802(7MB) AllocSpace objects, 65(1928KB) LOS objects, 33% free, 29MB/44MB, paused 1.480ms total 94.675ms
,11-25 08:37:40.621   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 08:37:40.624  5982  5982 I art     : System.exit called, status: 0
,11-25 08:37:40.624  5982  5982 I AndroidRuntime: VM exiting with result code 0.
,11-25 08:37:40.638   931   954 I ActivityManager: Start proc 5994:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-25 08:37:40.638   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 08:37:40.645   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-25 08:37:40.649  5883  5883 D BluetoothMapAppObserver: onReceive
11-25 08:37:40.649  5883  5883 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-25 08:37:40.651  4062  4155 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-25 08:37:40.654   931  2892 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-25 08:37:40.654  3638  3638 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-25 08:37:40.688  3638  6006 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 08:37:40.693  3753  3753 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 08:37:40.707   314   314 W kworker/1:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 08:37:40.702  3351  6009 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 08:37:40.714   314   314 W kworker/1:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 08:37:40.720  3529  3529 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-25 08:37:40.720  3529  3529 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-25 08:37:40.724   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 08:37:40.725  3638  6006 I Decoder : createOrResetDecoder
,11-25 08:37:40.727   314   314 W kworker/1:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 08:37:40.738  3677  6013 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-25 08:37:40.738  3677  6013 D AccountUtils: Clearing selected account for com.test.thalitest
,11-25 08:37:40.753  3791  3919 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-25 08:37:40.766   931  3805 I ActivityManager: Start proc 6014:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-25 08:37:40.767  3791  3919 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-25 08:37:40.767  3791  3919 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3791
11-25 08:37:40.767  3791  3919 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.767  3791  3919 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 08:37:40.773   931  5156 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-25 08:37:40.774   931  6023 E DropBoxManagerService: Can't write: system_app_crash
11-25 08:37:40.774   931  6023 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 08:37:40.774   931  6023 E DropBoxManagerService: 	... 5 more
,11-25 08:37:40.777  3791  3919 I Process : Sending signal. PID: 3791 SIG: 9
,11-25 08:37:40.795  3529  3529 I ConfigService: onCreate
,11-25 08:37:40.799  3529  6030 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-25 08:37:40.799  3529  6030 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-25 08:37:40.799  3529  6030 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-25 08:37:40.801  3529  6030 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-25 08:37:40.819  3677  6013 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-25 08:37:40.823  3638  6006 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-25 08:37:40.830  3351  3378 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj8D0190993) - 
,11-25 08:37:40.851  3677  6013 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.851  3677  6013 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.852  3677  6013 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 08:37:40.853  3677  6013 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-25 08:37:40.881  3351  3378 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-25 08:37:40.881  3351  3378 E AndroidRuntime: Process: android.process.acore, PID: 3351
11-25 08:37:40.881  3351  3378 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.881  3351  3378 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 08:37:40.883   931  6034 E DropBoxManagerService: Can't write: system_app_crash
11-25 08:37:40.883   931  6034 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 08:37:40.883   931  6034 E DropBoxManagerService: 	... 5 more
,11-25 08:37:40.917  3351  3378 I Process : Sending signal. PID: 3351 SIG: 9
,11-25 08:37:40.921   931  2891 W InputDispatcher: channel '2314e43 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-25 08:37:40.921   931  3769 D GraphicsStats: Buffer count: 1
,11-25 08:37:40.921   931  3147 I WindowState: WIN DEATH: Window{2314e43 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-25 08:37:40.921   931  2891 E InputDispatcher: channel '2314e43 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-25 08:37:40.922   931  3147 W InputDispatcher: Attempted to unregister already unregistered input channel '2314e43 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-25 08:37:40.927   931  5156 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3791) has died
,11-25 08:37:40.928   931  5156 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
11-25 08:37:40.929   931  5156 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-25 08:37:40.933  3677  6036 I GMPM-SVC: App measurement is starting up
,11-25 08:37:40.939  3677  6036 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-25 08:37:40.945  3677  6036 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-25 08:37:40.950   931   944 I ActivityManager: Start proc 6038:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 08:37:40.999  6038  6038 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:37:40.999  6038  6038 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 08:37:41.000  6038  6038 D AndroidRuntime: Shutting down VM
,11-25 08:37:41.006  6038  6038 E AndroidRuntime: FATAL EXCEPTION: main
11-25 08:37:41.006  6038  6038 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6038
11-25 08:37:41.006  6038  6038 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 08:37:41.006  6038  6038 E AndroidRuntime: 	... 10 more
11-25 08:37:41.009   931  5156 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-25 08:37:41.009   931  6052 E DropBoxManagerService: Can't write: system_app_crash
11-25 08:37:41.009   931  6052 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 08:37:41.009   931  6052 E DropBoxManagerService: 	... 5 more
11-25 08:37:41.009  6038  6038 I Process : Sending signal. PID: 6038 SIG: 9
,11-25 08:37:41.024   931  3769 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6038) has died
,11-25 08:37:41.025   931  3769 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-25 08:37:41.039   931   944 I ActivityManager: Start proc 6053:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 08:37:41.088  6053  6053 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:37:41.088  6053  6053 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 08:37:41.088  6053  6053 D AndroidRuntime: Shutting down VM
,11-25 08:37:41.096  6053  6053 E AndroidRuntime: FATAL EXCEPTION: main
11-25 08:37:41.096  6053  6053 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6053
11-25 08:37:41.096  6053  6053 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-25 08:37:41.096  6053  6053 E AndroidRuntime: 	... 10 more
11-25 08:37:41.099   931  3805 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-25 08:37:41.100   931  6065 E DropBoxManagerService: Can't write: system_app_crash
11-25 08:37:41.100   931  6065 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 08:37:41.100   931  6065 E DropBoxManagerService: 	... 5 more
11-25 08:37:41.100  6053  6053 I Process : Sending signal. PID: 6053 SIG: 9

```
