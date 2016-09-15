#### Test 8520251856d1c3c_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 03:35:42.131   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:35:42.641  5668  5668 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 03:35:42.646  5668  5668 D AndroidRuntime: CheckJNI is OFF
09-15 03:35:42.674  5668  5668 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 03:35:42.706  5668  5668 I Radio-JNI: register_android_hardware_Radio DONE
09-15 03:35:42.721  5668  5668 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 03:35:42.727   925  3605 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 03:35:42.765   925  3605 I ActivityManager: Start proc 5677:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 03:35:42.770  5668  5668 D AndroidRuntime: Shutting down VM
09-15 03:35:42.820  3556  3863 W OpenGLRenderer: Incorrectly called buildLayer on View: FrameLayout, destroying layer...
09-15 03:35:42.864  5677  5677 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 03:35:42.901  5677  5677 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 03:35:42.929  5677  5677 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 822-842)
09-15 03:35:42.930  5677  5677 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 03:35:42.951  5677  5677 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fd8cc6}
09-15 03:35:42.952  5677  5677 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 03:35:42.954  5677  5677 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 03:35:42.960  5677  5677 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 03:35:42.962  5677  5677 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-15 03:35:42.998  5677  5677 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-15 03:35:43.013  5677  5677 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 03:35:43.013  5677  5677 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 03:35:43.013  5677  5677 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 03:35:43.013  5677  5677 I Adreno  : Build Date                       : 12/06/15
09-15 03:35:43.013  5677  5677 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 03:35:43.013  5677  5677 I Adreno  : Local Branch                     : mybranch17112971
09-15 03:35:43.013  5677  5677 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 03:35:43.013  5677  5677 I Adreno  : Remote Branch                    : NONE
09-15 03:35:43.013  5677  5677 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 03:35:43.065   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f33c41:true
,09-15 03:35:43.111  2962  2962 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[34001]" dev="sockfs" ino=34001 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 03:35:43.111  2962  2962 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[34001]" dev="sockfs" ino=34001 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 03:35:43.127  5677  5677 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 03:35:43.132   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:35:43.138  5677  5677 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 03:35:43.174  2962  2962 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30554]" dev="sockfs" ino=30554 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 03:35:43.174  2962  2962 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30554]" dev="sockfs" ino=30554 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 03:35:43.179  5677  5714 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 03:35:43.181  3457  3457 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[14319]" dev="sockfs" ino=14319 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 03:35:43.181  3457  3457 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[14319]" dev="sockfs" ino=14319 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 03:35:43.188  5677  5701 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 03:35:43.222  5677  5714 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 03:35:43.312   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +501ms (total +573ms)
,09-15 03:35:43.325  5677  5677 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5677
,09-15 03:35:43.416  5677  5677 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 03:35:43.589  5677  5715 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -566232784
,09-15 03:35:43.594  5677  5715 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 03:35:43.594  5677  5715 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 03:35:43.594  5677  5715 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 03:35:43.594  5677  5715 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 03:35:43.594  5677  5715 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 03:35:43.594  5677  5715 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f5313f added. We now have 1 listener(s)
09-15 03:35:43.598  5677  5715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 03:35:43.599  5677  5715 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:35:43.599  5677  5715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:35:43.600  5677  5715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 03:35:43.604  5677  5715 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d3d6a added. We now have 1 listener(s)
09-15 03:35:43.604  5677  5715 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:35:43.609   925  3002 D WifiService: New client listening to asynchronous messages
,09-15 03:35:43.611  5677  5715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:35:43.611  5677  5715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 03:35:43.611  5677  5715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 03:35:43.611  5677  5715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 03:35:43.612  5677  5715 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 03:35:43.613  5677  5715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:35:43.613  5677  5715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 03:35:43.620  5677  5715 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:35:43.621  5677  5715 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:35:43.621  5677  5715 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 03:35:43.621  5677  5715 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:35:43.622  5677  5715 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 03:35:43.623  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:35:43.626  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:35:43.647  5677  5677 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 03:35:44.109  5677  5686 I art     : Background sticky concurrent mark sweep GC freed 76410(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.440ms total 230.503ms
,09-15 03:35:44.133   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:35:44.448  5677  5723 W jxcore-log: Initializing JXcore engine
09-15 03:35:44.448  5677  5723 W jxcore-log: JXcore engine is ready
,09-15 03:35:44.498  5723  5723 W Thread-57: type=1400 audit(0.0:120): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12545 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-15 03:35:44.498  5723  5723 W Thread-57: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[16395]" dev="sockfs" ino=16395 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 03:35:44.498  5723  5723 W Thread-57: type=1400 audit(0.0:122): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 03:35:44.498  5723  5723 W Thread-57: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[29490]" dev="sockfs" ino=29490 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 03:35:44.509  5677  5723 W jxcore-log: Starting JXcore engine
,09-15 03:35:44.564  5677  5723 W jxcore-log: Platform android
09-15 03:35:44.564  5677  5723 W jxcore-log: 
,09-15 03:35:44.564  5677  5723 W jxcore-log: Process ARCH arm
09-15 03:35:44.564  5677  5723 W jxcore-log: 
,09-15 03:35:44.660  5677  5723 I jxcore-log: JXcore Cordova bridge is ready!
09-15 03:35:44.660  5677  5723 I jxcore-log: 
,09-15 03:35:44.661  5677  5723 W jxcore-log: JXcore engine is started
,09-15 03:35:44.670  5677  5715 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 03:35:44.675  5677  5677 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 03:35:45.133   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:35:46.134   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:35:47.135   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:35:51.627   925  2966 I PowerManagerService: Waking up from dozing (uid 1000)...
09-15 03:35:51.628   925   925 V KeyguardServiceDelegate: onStartedWakingUp()
,09-15 03:35:51.631   925   945 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
09-15 03:35:51.631   925   945 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@9b8cd8c)
09-15 03:35:51.632   925   945 I sensors : batch
09-15 03:35:51.632   925   945 I sensors : activate
,09-15 03:35:51.634   925   925 I sensors : batch
09-15 03:35:51.634   925   925 I sensors : activate
09-15 03:35:51.631  5728  5728 W mdss_fb0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 03:35:51.635   382   382 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7fb52c3c00
09-15 03:35:51.635   511   511 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-15 03:35:51.635   925   943 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,09-15 03:35:51.635   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-15 03:35:51.638   925  3545 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,09-15 03:35:51.643   925  2707 I hubconnection: sensorhub said: 'batch 7 flags:0, sampling_rate_Hz:4.00, max_report_latency_us:0'
,09-15 03:35:51.646   925  2707 I hubconnection: sensorhub said: 'activate 7 enable:1'
,09-15 03:35:51.647   925  2707 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,09-15 03:35:51.650   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-15 03:35:51.650   925  3001 E native  : do suspend false
09-15 03:35:51.650   925  2707 I hubconnection: sensorhub said: 'activate 31 enable:1'
,09-15 03:35:51.664   925  3001 D WifiConfigStore: No blacklist allowed without epno enabled
,09-15 03:35:51.707   925   945 I DisplayPowerController: Unblocked screen on after 77 ms
,09-15 03:35:51.709   925   945 V KeyguardServiceDelegate: onScreenTurnedOn()
,09-15 03:35:51.709   925   945 I DreamManagerService: Gently waking up from dream.
09-15 03:35:51.710   925   935 I DreamManagerService: Leaving dreamland.
,09-15 03:35:51.710   925   940 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
09-15 03:35:51.712   925  3177 I sensors : activate
,09-15 03:35:51.715   925  2707 I hubconnection: sensorhub said: 'activate 21 enable:0'
,09-15 03:35:51.721  3532  4511 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,09-15 03:35:51.721  3532  4511 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-15 03:35:51.721  3532  4511 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-15 03:35:51.721   524  1219 D         : oem-qmi: Connection accepted
09-15 03:35:51.721   524  1219 D         : oem-qmi: Waiting to accept connection
,09-15 03:35:51.727  3532  4511 D         : oem_qmi_lib:output 0
09-15 03:35:51.727  3532  4511 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-15 03:35:51.732  3166  3166 W PathParser: Points are too far apart 4.030360828967057
,09-15 03:35:51.733  3166  3166 W PathParser: Points are too far apart 4.030360538880159
,09-15 03:35:51.793   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,09-15 03:35:51.791  5732  5732 W irq/504-synapti: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 03:35:51.795   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
09-15 03:35:51.796   925  3110 D SurfaceControl: Excessive delay in setPowerMode(): 161ms
,09-15 03:35:52.931  3166  3166 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME RECENT clock SEARCH quick_settings >
,09-15 03:35:52.939  5677  5677 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 03:35:52.940  5677  5677 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-15 03:35:52.944  5677  5677 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-15 03:35:52.944  5677  5677 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-15 03:35:52.949   511  3027 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-15 03:35:52.951  3166  3166 D PhoneStatusBar: disable: < expand icons* alerts system_info* back HOME RECENT clock SEARCH quick_settings >
,09-15 03:35:52.962   511  3027 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
,09-15 03:35:52.962   511  3027 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
09-15 03:35:52.963   511  3027 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-15 03:35:52.968  3659  3659 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,09-15 03:35:52.973   511  3027 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-15 03:35:52.977   511  3027 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-15 03:35:52.978   935   935 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[30571]" dev="sockfs" ino=30571 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 03:35:52.978   935   935 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[30571]" dev="sockfs" ino=30571 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 03:35:52.983  3166  3166 D PhoneStatusBar: disable: < expand icons alerts system_info back home* recent* clock search* quick_settings >
,09-15 03:35:52.978  3707  3707 W Binder_9: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[30570]" dev="sockfs" ino=30570 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 03:35:52.981  3707  3707 W Binder_9: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[30570]" dev="sockfs" ino=30570 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 03:35:52.984  3431  3431 I Keyboard.Facilitator: onFinishInput()
,09-15 03:35:53.711   511  3027 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-15 03:35:53.713   511  3027 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-15 03:35:53.725   511  3027 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-15 03:35:54.609  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 03:35:54.609  5677  5723 I jxcore-log: 
,09-15 03:35:54.612  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 03:35:54.612  5677  5723 I jxcore-log: 
,09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:35:54.616  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:35:54.617  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:35:54.618  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 03:35:54.618  5677  5723 I jxcore-log: 
,09-15 03:35:54.619  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 03:35:54.619  5677  5723 I jxcore-log: 
,09-15 03:35:54.670   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 03:35:54.857  5677  5723 I jxcore-log: Running unit tests
09-15 03:35:54.857  5677  5723 I jxcore-log: 
,09-15 03:35:54.858  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:35:54.858  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@336edd5 added. We now have 2 listener(s)
09-15 03:35:54.859  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:35:54.859  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:35:54.859  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:35:54.859  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:35:54.859  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29859ea added. We now have 2 listener(s)
09-15 03:35:54.859  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:35:54.859  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 03:35:54.862  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:35:54.865  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:35:54.865  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.866  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 03:35:54.866  5677  5723 D executeNativeTests: Running unit tests
,09-15 03:35:54.870  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:35:54.872  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:35:54.904  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:35:54.904  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 added. We now have 3 listener(s)
,09-15 03:35:54.905  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:35:54.905  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:35:54.905  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:35:54.905  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:35:54.905  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 added. We now have 3 listener(s)
09-15 03:35:54.905  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 03:35:54.905  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:35:54.907  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:35:54.910  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:35:54.911  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.912  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:35:54.913  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 03:35:54.913  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:35:54.913  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:35:54.913  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:35:54.914  5677  5723 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 03:35:54.914  5677  5723 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 03:35:54.914  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 03:35:54.914  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 03:35:54.914  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 03:35:54.914  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-15 03:35:54.914  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:35:54.915  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:35:54.915  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:35:54.915  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:35:54.915  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:35:54.915  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:35:54.915  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:35:54.915  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 03:35:54.915  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 removed from the list
09-15 03:35:54.915  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:35:54.915  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 removed from the list
,09-15 03:35:54.918  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:35:54.918  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:35:54.918  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:35:54.919  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:54.919  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.919  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:35:54.919  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:35:54.919  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:35:54.919  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:35:54.920  5677  5723 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 03:35:54.920  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:35:54.920  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:35:54.920  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:35:54.920  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:35:54.920  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:35:54.921  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.921  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:35:54.921  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:35:54.921  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:35:54.921  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:35:54.921  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:54.921  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.921  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:54.921  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.921  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:35:54.921  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 03:35:54.921  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:35:54.921  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 03:35:54.924  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 03:35:54.925  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 03:35:54.925  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 03:35:54.925  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 03:35:54.925  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:35:54.925  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:35:54.925  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:35:54.925  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:35:54.925  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:54.925  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.925  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:35:54.925  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:35:54.925  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:35:54.925  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:35:54.925  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:54.925  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.925  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:54.925  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:54.926  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:35:54.926  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:35:54.926  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:35:54.926  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:35:54.926  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 03:35:54.927  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:35:54.929  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:35:54.930  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:35:54.930  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 03:35:54.930  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:35:54.930  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 03:35:54.930  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 03:35:54.930  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:35:54.930  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 03:35:54.933  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:35:54.933  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 03:35:54.933  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:35:54.935  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:35:54.936  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 03:35:54.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:35:54.938  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 03:35:54.939  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-15 03:35:54.940  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 03:35:54.940  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 03:35:54.940  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:35:54.941  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 03:35:54.941  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:35:54.943  4423  4436 D BtGatt.GattService: registerClient() - UUID=7414dd2a-abd0-4384-85e6-6386c9e75781
09-15 03:35:54.944  4423  4485 D BtGatt.GattService: onClientRegistered() - UUID=7414dd2a-abd0-4384-85e6-6386c9e75781, clientIf=5
09-15 03:35:54.944  5677  5688 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 03:35:54.945  4423  4598 D BtGatt.GattService: start scan with filters
09-15 03:35:54.949  4423  4490 D BtGatt.ScanManager: handling starting scan
09-15 03:35:54.949  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 03:35:54.949  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:35:54.949  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:35:54.949  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 03:35:54.950  4423  4490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:35:54.950  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:35:54.951  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:35:54.951  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:35:54.951  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 03:35:54.952  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
09-15 03:35:54.958  4423  4485 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:35:54.958  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:35:54.959  4423  4490 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 03:35:54.963  4423  4485 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 03:35:54.964  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:35:54.964  4423  4490 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:35:54.964  4423  4490 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:35:54.973  4423  4485 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 03:35:54.973  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:35:54.978  4423  4485 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:35:54.978  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:35:55.452  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 03:35:55.453  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:35:55.453  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:35:57.696   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 03:35:59.957  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:35:59.957  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 03:35:59.957  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:35:59.958  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:59.958  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 03:35:59.960  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:35:59.960  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:35:59.960  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:35:59.960  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:35:59.961  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:35:59.961  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 03:35:59.962  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:35:59.963  4423  4436 D BtGatt.GattService: stopScan() - queue size =1
,09-15 03:35:59.964  4423  4598 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:35:59.965  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:35:59.966  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 03:35:59.966  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 03:35:59.966  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:35:59.966  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:35:59.969  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:35:59.970  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:35:59.970  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 03:35:59.971  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 03:35:59.973  4423  4423 D BtGatt.ScanManager: awakened up at time 387885
09-15 03:35:59.974  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 03:35:59.976  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:35:59.976  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:35:59.976  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:35:59.976  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:35:59.976  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:35:59.977  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:35:59.977  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:35:59.977  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:35:59.977  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:35:59.977  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:35:59.977  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:35:59.980  4423  4485 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 03:35:59.980  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:35:59.981  4423  4490 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:35:59.991  4423  4485 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 03:35:59.991  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:35:59.991  4423  4490 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:36:00.019  4423  4485 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-15 03:36:00.019  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:36:00.019  4423  4485 D BtGatt.GattService: current time is 387932617391
,09-15 03:36:00.020  4423  4485 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -74, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -71, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -74, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 03:36:00.022  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 03:36:00.024  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 03:36:00.024  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 03:36:00.024  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 03:36:00.024  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-15 03:36:00.479  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:36:00.723   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 03:36:02.136   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:03.138   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:03.753   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 03:36:04.139   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:04.979  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-15 03:36:04.987  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:04.997  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:36:05.002  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:05.003  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:36:05.003  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:36:05.003  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 03:36:05.003  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 03:36:05.003  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:36:05.003  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 03:36:05.007  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:05.009  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:36:05.009  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 03:36:05.012  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:05.016  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:36:05.017  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:36:05.017  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:36:05.023  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 03:36:05.023  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 03:36:05.023  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 03:36:05.024  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:36:05.028  4423  4436 D BtGatt.GattService: registerClient() - UUID=13c20860-cf65-40ae-855b-a17cc9fc5c53
,09-15 03:36:05.029  4423  4485 D BtGatt.GattService: onClientRegistered() - UUID=13c20860-cf65-40ae-855b-a17cc9fc5c53, clientIf=5
,09-15 03:36:05.029  5677  5688 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 03:36:05.030  4423  4598 D BtGatt.GattService: start scan with filters
09-15 03:36:05.033  4423  4490 D BtGatt.ScanManager: handling starting scan
09-15 03:36:05.033  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 03:36:05.033  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-15 03:36:05.033  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:36:05.033  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 03:36:05.037  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:36:05.037  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:36:05.037  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:36:05.039  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:36:05.043  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
09-15 03:36:05.043  4423  4485 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:36:05.043  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.044  4423  4490 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:36:05.046  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:36:05.046  5677  5723 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 03:36:05.046  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:05.046  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:36:05.046  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:05.046  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 03:36:05.046  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:36:05.046  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:36:05.046  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 03:36:05.047  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:36:05.047  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:36:05.047  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 03:36:05.048  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:36:05.049  4423  4436 D BtGatt.GattService: stopScan() - queue size =1
09-15 03:36:05.049  4423  4598 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 03:36:05.050  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:36:05.050  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 03:36:05.050  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 03:36:05.050  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:36:05.050  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:36:05.051  4423  4485 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:36:05.051  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.051  4423  4490 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:36:05.051  4423  4490 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 03:36:05.051  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:36:05.052  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:36:05.052  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 03:36:05.052  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:36:05.052  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:36:05.054  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:36:05.054  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:05.054  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:05.054  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:36:05.054  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:36:05.054  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:36:05.054  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:05.054  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:05.055  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:05.055  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:05.055  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:05.055  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:05.055  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:05.056  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 03:36:05.056  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:05.056  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:05.057  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:05.058  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 03:36:05.060  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:05.065  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:36:05.066  4423  4485 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 03:36:05.066  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:36:05.067  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:05.067  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:36:05.067  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:36:05.067  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 03:36:05.067  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 03:36:05.067  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:36:05.067  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 03:36:05.072  4423  4485 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:36:05.073  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:36:05.074  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:36:05.074  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 03:36:05.074  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:05.078  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:05.078  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:36:05.079  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:36:05.079  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 03:36:05.081  4423  4485 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 03:36:05.081  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.081  4423  4490 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:36:05.083  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 03:36:05.083  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:36:05.083  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 03:36:05.083  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:36:05.085  4423  4436 D BtGatt.GattService: registerClient() - UUID=0f4a43b0-8563-4c53-9119-bf4f15076075
09-15 03:36:05.086  4423  4485 D BtGatt.GattService: onClientRegistered() - UUID=0f4a43b0-8563-4c53-9119-bf4f15076075, clientIf=5
09-15 03:36:05.086  4423  4485 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 03:36:05.087  5677  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 03:36:05.087  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.087  4423  4490 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:36:05.087  4423  4632 D BtGatt.GattService: start scan with filters
09-15 03:36:05.089  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 03:36:05.089  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-15 03:36:05.090  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:36:05.090  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 03:36:05.093  4423  4485 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 03:36:05.093  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.093  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:36:05.093  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:36:05.093  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:36:05.094  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 03:36:05.094  4423  4490 D BtGatt.ScanManager: handling starting scan
,09-15 03:36:05.096  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 03:36:05.100  4423  4485 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:36:05.100  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.100  4423  4490 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:36:05.105  4423  4485 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:36:05.105  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:05.105  4423  4490 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:36:05.105  4423  4490 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:36:05.114  4423  4485 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 03:36:05.114  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:36:05.120  4423  4485 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:36:05.120  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:36:05.140   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:05.594  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 03:36:05.595  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:36:05.595  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:36:06.141   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:06.772   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 03:36:06.780   925  3003 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-15 03:36:07.142   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:36:09.802   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-15 03:36:09.806   925  3003 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-15 03:36:10.097  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:36:10.097  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:36:10.098  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:36:10.098  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:10.098  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 03:36:10.098  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:36:10.098  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:36:10.098  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 03:36:10.098  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:36:10.099  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:36:10.099  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 03:36:10.101  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:36:10.103  4423  4632 D BtGatt.GattService: stopScan() - queue size =1
,09-15 03:36:10.106  4423  4437 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 03:36:10.106  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:36:10.107  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 03:36:10.107  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 03:36:10.107  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:36:10.107  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:36:10.110  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:36:10.110  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:36:10.111  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 03:36:10.111  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:36:10.113  4423  4423 D BtGatt.ScanManager: awakened up at time 398025
09-15 03:36:10.115  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:36:10.118  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:36:10.118  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:36:10.118  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:36:10.119  4423  4485 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 03:36:10.120  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:10.120  4423  4490 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:36:10.130  4423  4485 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 03:36:10.130  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:10.130  4423  4490 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:36:10.150  4423  4485 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-15 03:36:10.151  4423  4485 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:36:10.151  4423  4485 D BtGatt.GattService: current time is 398063972521
09-15 03:36:10.151  4423  4485 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -67, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -76, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -75, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 03:36:10.151  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 03:36:10.152  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 03:36:10.152  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 03:36:10.152  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 03:36:10.152  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-15 03:36:10.153  4423  4485 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-15 03:36:10.619  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:36:10.620  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:10.620  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:36:15.119  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:36:15.120  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.120  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.120  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 03:36:15.120  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.120  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:36:15.121  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.121  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:15.121  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:15.121  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 03:36:15.121  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.123  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:15.124  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.127  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.127  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.127  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:15.127  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.129  5677  5723 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 03:36:15.131  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.131  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.131  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.131  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.131  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.131  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.132  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.132  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.132  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:15.132  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.132  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.132  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.132  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.133  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.135  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 03:36:15.135  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.135  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.135  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.138  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 03:36:15.138  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.138  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.138  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.138  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.138  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:15.139  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.139  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.139  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.139  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.139  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.139  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.139  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.139  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.139  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.140  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.140  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.141  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:15.141  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.141  5677  5723 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 03:36:15.142  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.142  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.142  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.142  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.142  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.142  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.142  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.142  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.142  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.142  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.142  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:15.142  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.142  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.143  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.144  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.144  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.144  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.144  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.145  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-15 03:36:15.145  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.145  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.146  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.146  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.146  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.146  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.146  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.146  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.146  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.146  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.146  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.146  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.146  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:15.146  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.148  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.148  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.148  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.148  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:15.149  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-15 03:36:15.149  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:36:15.149  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:36:15.149  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 03:36:15.149  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 03:36:15.149  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 03:36:15.149  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 03:36:15.149  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:36:15.150  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 03:36:15.150  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.150  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.150  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.150  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.150  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:15.150  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.150  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.150  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.150  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.150  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.150  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.151  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.151  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.151  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.153  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.153  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.153  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.153  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:15.154  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-15 03:36:15.154  5677  5723 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 03:36:15.154  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 03:36:15.158  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 03:36:15.158  5677  5723 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 03:36:15.158  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 03:36:15.159  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 03:36:15.160  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 03:36:15.160  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 03:36:15.160  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-15 03:36:15.160  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 03:36:15.160  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 03:36:15.160  5677  5723 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 03:36:15.160  5677  5723 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 03:36:15.161  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 03:36:15.161  5677  5723 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 03:36:15.161  5677  5723 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 03:36:15.161  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 03:36:15.161  5677  5723 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 03:36:15.161  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 03:36:15.164  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 03:36:15.165  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 03:36:15.165  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 03:36:15.166  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 03:36:15.166  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-15 03:36:15.166  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 03:36:15.166  5677  5723 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 03:36:15.166  5677  5723 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 03:36:15.167  5677  5743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 03:36:15.167  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.167  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.167  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.167  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.167  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.167  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.167  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 03:36:15.168  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.168  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.168  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.168  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.168  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.168  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.169  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:15.169  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.169  5677  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
,09-15 03:36:15.170  5677  5743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:36:15.171  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.168  4436  4436 W Binder_1: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[29598]" dev="sockfs" ino=29598 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:36:15.171  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.171  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.171  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.172  5677  5723 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 03:36:15.173  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.173  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.173  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.173  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.173  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.168  4436  4436 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[29598]" dev="sockfs" ino=29598 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:36:15.173  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.173  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.173  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.173  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:15.174  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.174  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.174  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.174  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.174  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:15.175  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.175  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.175  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.175  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.176  5677  5723 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 03:36:15.176  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.177  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:36:15.177  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:36:15.177  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.177  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.178  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.178  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.178  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.178  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.178  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.178  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.178  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.178  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.178  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.179  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.179  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.179  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.179  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.180  5677  5723 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-15 03:36:15.181  5677  5723 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 03:36:15.181  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 03:36:15.181  5677  5723 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 03:36:15.181  5677  5723 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-15 03:36:15.181  5677  5723 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 03:36:15.181  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 03:36:15.181  5677  5723 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 03:36:15.181  5677  5723 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 03:36:15.181  5677  5723 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 03:36:15.181  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 03:36:15.181  5677  5723 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 03:36:15.182  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:15.182  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:15.182  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:15.182  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.182  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.182  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.182  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.182  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.182  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.182  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.182  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.182  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.182  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.182  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:15.184  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:15.184  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:15.184  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.184  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.184  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:15.184  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.184  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:15.184  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:15.185  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:15.185  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:15.185  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:15.185  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:15.185  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:20.185  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.186  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:20.186  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:20.186  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.186  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.186  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:20.187  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:20.187  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:20.187  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:20.187  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 03:36:20.187  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.188  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.188  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:20.188  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.188  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.189  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:20.189  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:20.189  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.189  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.189  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.192  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:20.192  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:20.192  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:20.193  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:20.196  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 03:36:20.197  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:36:20.201  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 03:36:20.203  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 03:36:20.203  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-15 03:36:20.204  4598  4598 W Binder_3: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[30598]" dev="sockfs" ino=30598 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:36:20.204  4598  4598 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[30598]" dev="sockfs" ino=30598 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 03:36:20.205  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 03:36:20.205  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 03:36:20.205  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-15 03:36:20.205  5677  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:36:20.206  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:20.206  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 03:36:20.206  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 03:36:20.206  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 03:36:20.206  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.206  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 03:36:20.206  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
,09-15 03:36:20.207  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 03:36:20.207  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.207  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:36:20.207  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:36:20.207  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:36:20.207  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.207  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.209  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:36:20.209  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:20.209  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:36:20.209  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:20.209  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:36:20.209  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:20.209  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:36:20.209  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:20.209  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:20.209  5677  5745 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-15 03:36:20.209  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.210  5677  5745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 03:36:20.210  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.210  5677  5745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 03:36:20.210  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:20.210  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.210  5677  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-15 03:36:20.210  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.211  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:20.211  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.211  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.211  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.211  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.214  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 03:36:20.214  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:20.214  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.214  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.216  5677  5723 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 03:36:20.217  5677  5723 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 03:36:20.217  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 03:36:20.218  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-15 03:36:20.218  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 03:36:20.218  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:20.218  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:20.219  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:20.219  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 03:36:20.219  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.220  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.220  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:20.221  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.221  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.221  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:20.221  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:20.221  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.221  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.221  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.223  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:20.223  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:20.223  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.223  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
,09-15 03:36:20.228  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:36:20.229  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:36:20.229  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:20.229  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:20.229  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:36:20.229  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.229  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:20.229  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.229  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.229  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:20.229  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.229  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:20.229  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.230  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.231  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:20.231  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:36:20.231  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.232  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.233  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:36:20.233  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:36:20.233  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:36:20.233  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:36:20.233  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.233  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.233  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a18f2a8 not in the list
09-15 03:36:20.233  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:20.233  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.233  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:20.233  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.233  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:20.234  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:20.234  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:20.235  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:36:20.235  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 03:36:20.235  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:20.235  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7eb1c1 not in the list
09-15 03:36:20.236  5677  5723 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 03:36:20.236  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 03:36:20.237  5677  5723 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 03:36:20.237  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-15 03:36:20.237  5677  5723 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 03:36:20.237  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-15 03:36:20.239  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-15 03:36:20.239  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 03:36:20.240  5677  5723 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-15 03:36:20.240  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-15 03:36:20.240  5677  5723 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 03:36:20.241  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 03:36:20.241  5677  5723 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 03:36:20.241  5677  5723 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 03:36:20.241  5677  5723 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 03:36:20.242  5677  5723 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-15 03:36:20.243  5677  5723 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 03:36:20.243  5677  5723 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 03:36:20.243  5677  5723 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 03:36:20.243  5677  5723 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 03:36:20.245  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:36:20.245  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@308ccbb added. We now have 3 listener(s)
,09-15 03:36:20.245  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:36:20.247  5677  5723 D BluetoothAdapter: enable(): BT is already enabled..!
,09-15 03:36:20.247   925  3707 D WifiService: setWifiEnabled: true pid=5677, uid=10077
09-15 03:36:20.247   925  3707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 03:36:20.302  4423  4579 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-15 03:36:20.303  5677  5743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,09-15 03:36:20.304  4423  4594 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-15 03:36:20.710  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:36:21.204   925  5265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409116, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:36:25.253  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 03:36:25.254  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc255d8 added. We now have 4 listener(s)
09-15 03:36:25.254  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:36:25.266  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:25.266  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc255d8 removed from the list
09-15 03:36:25.266  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:25.267  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:25.267  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:25.268  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 03:36:25.269  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f68d31 added. We now have 4 listener(s)
,09-15 03:36:25.269  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:36:25.273  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:36:25.273  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f68d31 removed from the list
09-15 03:36:25.273  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:25.273  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:25.273  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:25.274  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:36:25.274  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9e53c16 added. We now have 4 listener(s)
09-15 03:36:25.274  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:36:25.277   925  3457 D WifiService: setWifiEnabled: false pid=5677, uid=10077
09-15 03:36:25.277   925  3457 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 03:36:25.284   925  3001 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 03:36:25.284   925  3001 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 03:36:25.284   925  3001 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 03:36:25.284   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:36:25.286  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:36:25.289  4423  4481 D BluetoothAdapterState: Current state: ON, message: 23
09-15 03:36:25.289  4423  4481 D BluetoothAdapterProperties: Setting state to 13
09-15 03:36:25.289  4423  4481 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 03:36:25.290  4423  4481 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 03:36:25.291  4423  4481 I BluetoothAdapterState: Entering PendingCommandState
09-15 03:36:25.293  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:25.293  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:36:25.294  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.294  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:25.295  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:36:25.298  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:25.298  4423  4423 D BluetoothMapService: onReceive
,09-15 03:36:25.298  4423  4423 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 03:36:25.299  4423  4423 D BluetoothMapService: STATE_TURNING_OFF
09-15 03:36:25.299  4423  4423 D BluetoothMapService: MAP Service closeService in
09-15 03:36:25.299  4423  4423 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 03:36:25.299  4423  4423 D ObexServerSockets0: shutdown(block = true)
09-15 03:36:25.300  4423  4423 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 03:36:25.300  4423  4636 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 03:36:25.300  4423  4423 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 03:36:25.300  4423  4594 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 03:36:25.300  4423  4637 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 03:36:25.302  4423  4423 I BtOppRfcommListener: stopping Accept Thread
09-15 03:36:25.302  4423  5174 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 03:36:25.302  4423  5174 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 03:36:25.302  4423  4485 D BluetoothAdapterProperties: Scan Mode:20
09-15 03:36:25.303  4423  4481 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 03:36:25.304  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.305   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 03:36:25.307   925  5266 D DhcpClient: Clearing IP address
,09-15 03:36:25.308  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:25.308  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:36:25.309  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 03:36:25.309  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:36:25.313   925   938 I ActivityManager: Start proc 5749:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-15 03:36:25.313   506   919 D CommandListener: Setting iface cfg
,09-15 03:36:25.316   925  5268 D DhcpClient: Receive thread stopped
09-15 03:36:25.316  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:25.316  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:36:25.316  4423  4423 D HeadsetService: Received stop request...Stopping profile...
09-15 03:36:25.317  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.317  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:25.321   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:25.321   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:25.322  3532  3544 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:25.322  4423  4423 D A2dpService: Received stop request...Stopping profile...
,09-15 03:36:25.322  4423  4614 D A2dpStateMachine: Exit Disconnected: -1
09-15 03:36:25.322  3166  3770 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:25.323  3166  3166 D HeadsetProfile: Bluetooth service disconnected
09-15 03:36:25.323  3614  5332 V NativeCrypto: Read error: ssl=0x7f678e5700: I/O error during system call, Connection timed out
09-15 03:36:25.323   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:25.323   925   925 D BluetoothA2dp: Proxy object disconnected
09-15 03:36:25.324  4423  4423 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:25.324  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.324  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.324  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.324  3166  3166 D BluetoothA2dp: Proxy object disconnected
09-15 03:36:25.325  3614  5332 V NativeCrypto: SSL shutdown failed: ssl=0x7f678e5700: I/O error during system call, Broken pipe
09-15 03:36:25.325  4423  4423 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 03:36:25.325  4423  4423 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 03:36:25.326  4423  4485 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 03:36:25.326  4423  4579 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:25.326  4423  4579 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:25.326  4423  4579 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:25.326  4423  4423 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:25.326  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.326  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.326  4423  4485 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 03:36:25.326  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.327  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:25.327  4423  4423 D HidService: Received stop request...Stopping profile...
09-15 03:36:25.327  4423  4423 D HidService: Stopping Bluetooth HidService
09-15 03:36:25.328  3166  3166 D BluetoothInputDevice: Proxy object disconnected
09-15 03:36:25.328  3166  3166 D HidProfile: Bluetooth service disconnected
,09-15 03:36:25.329   925  3178 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-15 03:36:25.329  4423  4485 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 03:36:25.329  4423  4579 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:25.329  4423  4579 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:25.329   925  5264 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-15 03:36:25.330  4423  4579 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 03:36:25.330  4423  4423 D HealthService: Received stop request...Stopping profile...
09-15 03:36:25.330  4423  4579 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 03:36:25.330  4423  4579 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-15 03:36:25.330  4423  4579 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 03:36:25.331  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.334  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.334   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 03:36:25.334   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-15 03:36:25.337   925  5264 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-15 03:36:25.338   532   532 E Parcel  : Reading a NULL string not supported here.
09-15 03:36:25.338  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.339  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:36:25.339   925   925 D RttService: SCAN_AVAILABLE : 1
09-15 03:36:25.339   925  3107 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 03:36:25.340  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.340   925  3003 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-15 03:36:25.340  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:25.341  4423  4423 D PanService: Received stop request...Stopping profile...
,09-15 03:36:25.342  3491  3653 W QCNEJ   : |CORE| network lost: 100
09-15 03:36:25.342  4423  4423 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:25.342  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.342  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.342  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.342  4423  4423 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 03:36:25.343  4423  4423 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-15 03:36:25.343  4423  4485 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 03:36:25.343  3491  3653 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 03:36:25.343  4423  4423 D BluetoothMapService: Received stop request...Stopping profile...
09-15 03:36:25.343  4423  4423 D BluetoothMapService: stop()
09-15 03:36:25.344  4423  4423 D BluetoothMapAppObserver: deinitObservers()
09-15 03:36:25.344  4423  4423 D BluetoothMapAppObserver: removeReceiver()
09-15 03:36:25.345  4423  4423 D SapService: Received stop request...Stopping profile...
09-15 03:36:25.345  4423  4423 V SapService: stop()
,09-15 03:36:25.346  4423  4423 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:25.346  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.346  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.346  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.346  4423  4423 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 03:36:25.346  4423  4485 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 03:36:25.347  4423  4423 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-15 03:36:25.347  4423  4423 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:25.347  4423  4423 V BluetoothAdapterState: isTurningOn()=false
,09-15 03:36:25.347  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.347  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.347  4423  4423 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 03:36:25.347  4423  4423 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 03:36:25.348  4423  4423 D BluetoothMapService: MAP Service closeService in
09-15 03:36:25.348  4423  4423 V BluetoothAdapterState: isTurningOff()=true
,09-15 03:36:25.348  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.348  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.348  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.349  4423  4423 D BluetoothMapService: cleanup()
09-15 03:36:25.349  4423  4423 D BluetoothMapService: MAP Service closeService in
09-15 03:36:25.349  4423  4423 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:25.349  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.349  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.349  4423  4423 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:25.349  4423  4481 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 03:36:25.350  4423  4481 D BluetoothAdapterProperties: Setting state to 15
09-15 03:36:25.350  4423  4481 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 03:36:25.350  4423  4481 I BluetoothAdapterState: Entering BleOnState
09-15 03:36:25.350  3166  3179 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 03:36:25.351   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:25.352  3166  3180 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:25.352  3166  3770 D BluetoothMap: onBluetoothStateChange: up=false
09-15 03:36:25.353  3166  3769 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 03:36:25.354  3532  3875 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:25.354  3166  3179 D BluetoothPan: onBluetoothStateChange on: false
09-15 03:36:25.355  3166  3180 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 03:36:25.356   925  3001 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-15 03:36:25.357   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:25.358   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:25.358   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 03:36:25.358  4423  4481 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 03:36:25.358  4423  4481 D BluetoothAdapterProperties: Setting state to 16
09-15 03:36:25.358  4423  4481 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 03:36:25.359  4423  4481 D BluetoothAdapterProperties: onBleDisable
09-15 03:36:25.359  4423  4481 I BluetoothAdapterState: Entering PendingCommandState
09-15 03:36:25.359  4423  4482 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 03:36:25.360  4423  4485 D BluetoothAdapterProperties: Scan Mode:20
09-15 03:36:25.360  4423  4579 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 03:36:25.360  4423  4579 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:25.361  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.361  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:25.362   925  3001 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 03:36:,25.362  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.362  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:25.364  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.364  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:25.364  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.364  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:25.366  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.366  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:25.367  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:25.368  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:25.369  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.376  5749  5749 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-15 03:36:25.377   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:36:25.387  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 03:36:25.392   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@137f7df:true
,09-15 03:36:25.394  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 03:36:25.397   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:36:25.397   506   919 D CommandListener: Clearing all IP addresses on wlan0
09-15 03:36:25.398   925  3003 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 03:36:25.398   925  3003 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:36:25.408   925  3545 I ActivityManager: Start proc 5767:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 03:36:25.410   925  3001 D DhcpClient: doQuit
,09-15 03:36:25.410   925  3001 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 03:36:25.410   925  5266 D DhcpClient: onQuitting
09-15 03:36:25.411  3632  3632 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 03:36:25.413   925   942 D Tethering: MasterInitialState.processMessage what=3
,09-15 03:36:25.415  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.415  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:25.416  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.416  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:25.417  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.417  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:25.418  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.418  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:25.419  5160  5160 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dd3fe12 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-15 03:36:25.419  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: fal,se
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:25.419  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:25.420  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:25.420  4753  4753 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-15 03:36:25.420  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:25.421  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:25.422  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:25.422  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.425  4819  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-15 03:36:25.427  4819  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 03:36:25.427  4819  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 03:36:25.427  4819  4848 E SarControlService: no key has been found,reset the power
09-15 03:36:25.428  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 03:36:25.428  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 03:36:25.428  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 03:36:25.429  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:36:25.429  4850  4850 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 03:36:25.430  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-15 03:36:25.430  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-15 03:36:25.431  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-15 03:36:25.432  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:36:25.432  4850  4850 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 03:36:25.432  3632  3632 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-15 03:36:25.439  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000ea03000000000000ffffffff]
09-15 03:36:25.439  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:36:25.439  4850  4887 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 03:36:25.439  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:36:25.439  4819  4830 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 03:36:25.439  3632  3632 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-15 03:36:25.441  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000eb03000000000000ffffffff]
,09-15 03:36:25.442  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:36:25.442  4850  4887 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 03:36:25.442  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:36:25.443  4819  4831 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 03:36:25.457  5749  5749 D LocalBluetoothProfileManager: Adding local MAP profile
,09-15 03:36:25.459  5749  5749 D BluetoothMap: Create BluetoothMap proxy object
,09-15 03:36:25.466   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 03:36:25.467  5767  5767 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 03:36:25.468  3632  3632 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-15 03:36:25.468   925  3003 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 03:36:25.475  5749  5749 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 03:36:25.481  3632  3632 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 03:36:25.494  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-15 03:36:25.502   925  3178 I ActivityManager: Killing 4795:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 03:36:25.565  4423  4485 I bt_hci  : shut_down
,09-15 03:36:25.569  4423  4491 D bt_hwcfg: hw_epilog_process
,09-15 03:36:25.569  4423  4491 I bt_vendor: low_power_mode_cb
,09-15 03:36:25.572  4423  4491 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 03:36:25.572  4423  4491 I bt_vendor: epilog_cb
09-15 03:36:25.572  4423  4491 I bt_hci  : epilog_finished_callback
,09-15 03:36:25.574  4423  4485 I bt_hci_h4: hal_close
,09-15 03:36:25.575  4423  4485 I bt_userial_vendor: device fd = 54 close
,09-15 03:36:25.583   925  3001 D wifi    : In wifi stop Hal
,09-15 03:36:25.583  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 03:36:25.584   925  3001 D wifi    : halHandle = 0x7f6602f0e0, mVM = 0x7f81f8d140, mCls = 0x100ae6
09-15 03:36:25.584   925  3629 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 03:36:25.584   925  3629 D WifiHAL : Got a signal to exit!!!
,09-15 03:36:25.584   925  3629 I WifiHAL : Exit wifi_event_loop
09-15 03:36:25.585   925  3001 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 03:36:25.585   925  3001 E WifiHAL : Event processing terminated
09-15 03:36:25.585   925  3001 D wifi    : In wifi cleaned up handler
09-15 03:36:25.585   925  3001 I WifiHAL : Internal cleanup completed
09-15 03:36:25.586  3659  4055 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 03:36:25.587  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.588  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.590  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:25.609   925  3629 D wifi    : set interface wlan0 flags (DOWN)
,09-15 03:36:25.610   925  3001 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 03:36:25.672   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 03:36:25.681  4423  4482 D bt_stack_manager: event_shut_down_stack finished.
,09-15 03:36:25.681  4423  4481 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 03:36:25.683  4423  4423 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 03:36:25.683  4423  4481 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 03:36:25.683  4423  4423 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 03:36:25.683  4423  4423 D BtGatt.GattService: stop()
09-15 03:36:25.684  4423  4423 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 03:36:25.685  4423  4423 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:25.685  4423  4423 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:25.685  4423  4423 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:25.685  4423  4423 V BluetoothAdapterState: isBleTurningOff()=true
09-15 03:36:25.685  4423  4481 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 03:36:25.685  4423  4481 D BluetoothAdapterProperties: Setting state to 10
09-15 03:36:25.685  4423  4481 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 03:36:25.686  4423  4481 I BluetoothAdapterState: Entering OffState
,09-15 03:36:25.686   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-15 03:36:25.692  4423  4423 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 03:36:25.692  4423  4423 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 03:36:25.692  4423  4423 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 03:36:25.693  4423  4482 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 03:36:25.698  4423  4423 I art     : System.exit called, status: 0
,09-15 03:36:25.698  4423  4423 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.729  5767  5767 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 03:36:25.729  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 03:36:25.734  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 03:36:25.736   925  3457 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-15 03:36:25.737   925  3457 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-15 03:36:25.737   925  3457 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-15 03:36:25.737   925  3457 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-15 03:36:25.737   925  3457 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-15 03:36:25.754   925  3457 I ActivityManager: Start proc 5809:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-15 03:36:25.755   925  3178 W ActivityManager: Spurious death for ProcessRecord{19d00d6 5809:com.android.bluetooth/1002}, curProc for 4423: null
09-15 03:36:25.756  5749  5749 D DockEventReceiver: finishStartingService: stopping service
09-15 03:36:25.758   925   936 I ActivityManager: Killing 5160:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-15 03:36:25.812   925   942 D Tethering: InitialState.processMessage what=4
09-15 03:36:25.814   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 03:36:25.845  5809  5809 D AdapterServiceConfig: Adding HeadsetService
09-15 03:36:25.845  5809  5809 D AdapterServiceConfig: Adding A2dpService
09-15 03:36:25.845  5809  5809 D AdapterServiceConfig: Adding HidService
09-15 03:36:25.845  5809  5809 D AdapterServiceConfig: Adding HealthService
09-15 03:36:25.845  5809  5809 D AdapterServiceConfig: Adding PanService
09-15 03:36:25.845  5809  5809 D AdapterServiceConfig: Adding GattService
09-15 03:36:25.846  5809  5809 D AdapterServiceConfig: Adding BluetoothMapService
09-15 03:36:25.846  5809  5809 D AdapterServiceConfig: Adding SapService
,09-15 03:36:25.848   925   936 I ActivityManager: Killing 5307:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-15 03:36:25.880  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 03:36:25.896  3946  3946 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 03:36:25.904  3946  3946 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 03:36:25.907  3946  3946 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-15 03:36:25.908  3946  5304 I iu.UploadsManager: num queued entries: 0
,09-15 03:36:25.908  3946  5304 I iu.UploadsManager: num updated entries: 0
,09-15 03:36:25.909  3946  5304 I iu.SyncManager: NEXT; no task
,09-15 03:36:25.921   925  3458 I ActivityManager: Start proc 5826:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 03:36:25.959  5826  5826 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 03:36:25.965  5826  5826 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:36:25.971  5826  5826 D SprintDMHelper: simOperator: 
09-15 03:36:25.971  5826  5826 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 03:36:25.984  4314  5838 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 03:36:25.997   925  3707 I ActivityManager: Start proc 5839:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 03:36:25.999   925  3545 I ActivityManager: Killing 4495:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 03:36:26.012  5767  5789 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 03:36:26.030  5839  5839 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 03:36:26.037   925  3178 I ActivityManager: Killing 5380:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-15 03:36:26.051   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f690c7:true
,09-15 03:36:27.142   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:28.143   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:29.144   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:30.145   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:30.297   925  3545 D WifiService: setWifiEnabled: true pid=5677, uid=10077
09-15 03:36:30.297   925  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 03:36:30.308   506   919 D SoftapController: Softap fwReload - Ok
09-15 03:36:30.314   506   919 D CommandListener: Setting iface cfg
09-15 03:36:30.314   506   919 D CommandListener: Trying to bring down wlan0
,09-15 03:36:30.316   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 03:36:30.320   925  3001 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 03:36:30.886   925  3001 D wifi    : set interface wlan0 flags (UP)
,09-15 03:36:30.890   925  3001 I WifiHAL : Initializing wifi
09-15 03:36:30.890   925  3001 I WifiHAL : Creating socket
09-15 03:36:30.891   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 03:36:30.895   925  3001 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 03:36:30.896   925  3001 D wifi    : Did set static halHandle = 0x7f6602f0e0
09-15 03:36:30.896   925  3001 D wifi    : halHandle = 0x7f6602f0e0, mVM = 0x7f81f8d140, mCls = 0x201906
09-15 03:36:30.896   925  3001 D wifi    : array field set
09-15 03:36:30.896   925  3001 I WifiNative-HAL: interface[0] = wlan0
09-15 03:36:30.898   925  5857 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547172315360
09-15 03:36:30.898   925  5857 D wifi    : waitForHalEvents called, vm = 0x7f81f8d140, obj = 0x201906, env = 0x7f68f87a80
,09-15 03:36:30.972  5858  5858 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 03:36:30.987  5858  5858 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 03:36:30.999   925  3001 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 03:36:31.002  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:31.002  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:31.003  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:31.032  5858  5858 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 03:36:31.032  5858  5858 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 03:36:31.048   925  3001 D WifiConfigStore: Loading config and enabling all networks 
,09-15 03:36:31.050  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:31.050  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:31.050  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:31.050  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:36:31.051  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:31.052  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:31.052  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:31.052  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:31.053  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:31.053  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:31.053  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:31.053  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:36:31.060   925  3001 D WifiConfigStore: loaded 0 passpoint configs
,09-15 03:36:31.060   925  3001 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 03:36:31.061   925  3001 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 03:36:31.062   925  3001 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 03:36:31.063   925  3001 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 03:36:31.063   925  3001 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 03:36:31.063   925  3001 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 03:36:31.063   925  3001 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 03:36:31.067  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 03:36:31.067   925  3001 D WifiNative-HAL: Setting external_sim to 1
09-15 03:36:31.068   925  3001 D wifi    : setting dfs flag to true, 0x7f6797ed60
09-15 03:36:31.068   925  3001 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 03:36:31.068   925  3001 D wifi    : setting scan oui 0x7f6797ed60
09-15 03:36:31.068   925  3001 D WifiHAL : Sending mac address OUI
,09-15 03:36:31.072   925  3001 E native  : do suspend false
,09-15 03:36:31.079   925  3001 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 03:36:31.079   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-15 03:36:31.080   925   925 D RttService: SCAN_AVAILABLE : 3
,09-15 03:36:31.080   925  3107 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 03:36:31.080   506   919 D CommandListener: Setting iface cfg
,09-15 03:36:31.084   925  3000 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-15 03:36:31.084   925  3000 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 03:36:31.092   925  3000 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 03:36:31.092   925  3000 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 03:36:31.111   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=419023 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=27 mControllerEnergyUsed=102 }
,09-15 03:36:31.146   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:36:32.146   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:36:34.252  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:36:34.274  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:36:34.282  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:36:34.288  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:36:34.322   925  3001 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-15 03:36:34.323   925  3001 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-15 03:36:34.324   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:36:34.335   925  3001 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-15 03:36:34.365   925  3001 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-15 03:36:34.367  5858  5858 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-15 03:36:34.787  5858  5858 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-15 03:36:34.815  5858  5858 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-15 03:36:34.816  5858  5858 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-15 03:36:34.825   925  3001 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-15 03:36:34.826   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:36:34.826   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-15 03:36:34.844   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:36:34.857   506   919 D CommandListener: Setting iface cfg
,09-15 03:36:34.864   925  3001 D WifiStateMachine: Start Dhcp Watchdog 2
,09-15 03:36:34.871   925  5875 D DhcpClient: Receive thread started
,09-15 03:36:34.874   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-15 03:36:34.874   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-15 03:36:34.874   925  3003 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-15 03:36:34.956   925  3001 E native  : do suspend false
,09-15 03:36:34.969   925  5874 D DhcpClient: Broadcasting DHCPDISCOVER
,09-15 03:36:35.002   925  5875 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172419, domain null
,09-15 03:36:35.003   925  5874 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172419 seconds
,09-15 03:36:35.005   925  5874 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-15 03:36:35.022   925  5875 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-15 03:36:35.023   925  5874 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-15 03:36:35.026   506   919 D CommandListener: Setting iface cfg
,09-15 03:36:35.030   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-15 03:36:35.036   925  5874 D DhcpClient: Scheduling renewal in 86399s
,09-15 03:36:35.045   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-15 03:36:35.046   925  3001 D WifiConfigStore: No blacklist allowed without epno enabled
09-15 03:36:35.048   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-15 03:36:35.049   925  3003 D ConnectivityService: Adding iface wlan0 to network 101
09-15 03:36:35.058   925  3001 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-15 03:36:35.096   925  3003 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-15 03:36:35.097   925  3003 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-15 03:36:35.099   925  3003 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-15 03:36:35.101   925  3003 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-15 03:36:35.103   925  3003 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-15 03:36:35.116   925  3003 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-15 03:36:35.121   925  3003 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-15 03:36:35.122   925  3003 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-15 03:36:35.122   925  3003 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-15 03:36:35.122   925  3001 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-15 03:36:35.122   925  3003 D ConnectivityService:    accepting network in place of null
09-15 03:36:35.122   925  3001 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 03:36:35.123   925  3003 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 03:36:35.137   925  5873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423049, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:36:35.151   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:36:35.175   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:36:35.178   925  3003 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-15 03:36:35.178   925  3003 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:36:35.178  3491  3653 W QCNEJ   : |CORE| network available: 101
,09-15 03:36:35.179   925  3003 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-15 03:36:35.180   925   942 D Tethering: MasterInitialState.processMessage what=3
09-15 03:36:35.181  3491  3653 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-15 03:36:35.183  3491  3653 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-15 03:36:35.183  3491  3653 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-15 03:36:35.184  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:35.184  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:36:35.184  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.184  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:36:35.187  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:35.187  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:36:35.187  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.187  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:36:35.189  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:36:35.189  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:36:35.189  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.189  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:36:35.198  4819  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 03:36:35.199  4819  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 03:36:35.199  4819  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-15 03:36:35.199  4819  4848 E SarControlService: no key has been found,reset the power
,09-15 03:36:35.199  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 03:36:35.199  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 03:36:35.199  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 03:36:35.200  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:36:35.200  4850  4850 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 03:36:35.202  4753  4753 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-15 03:36:35.202  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 03:36:35.202  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 03:36:35.203  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 03:36:35.203  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:36:35.203  4850  4850 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 03:36:35.207  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000ec03000000000000ffffffff]
09-15 03:36:35.207  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:36:35.207  4850  4887 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-15 03:36:35.208  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:36:35.208  4819  4830 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 03:36:35.212  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000ed03000000000000ffffffff]
,09-15 03:36:35.212  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:36:35.212  4850  4887 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-15 03:36:35.213  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-15 03:36:35.213  4819  4831 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 03:36:35.217  3946  3946 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-15 03:36:35.218  3946  5304 I iu.UploadsManager: num queued entries: 0
09-15 03:36:35.218  3946  5304 I iu.UploadsManager: num updated entries: 0
09-15 03:36:35.219  3946  5304 I iu.SyncManager: NEXT; no task
,09-15 03:36:35.228  3946  3946 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 03:36:35.229  3946  3946 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-15 03:36:35.231  5826  5826 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:36:35.235  5826  5826 D SprintDMHelper: simOperator: 
,09-15 03:36:35.235  5826  5826 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-15 03:36:35.236   925  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,09-15 03:36:35.282   925  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 15 Sep 2016 07:36:35 GMT], X-Android-Received-Millis=[1473924995282], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473924995259]}
,09-15 03:36:35.283   925  3003 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-15 03:36:35.283   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-15 03:36:35.283   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-15 03:36:35.284   925  3003 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-15 03:36:35.305   925  3545 D WifiService: setWifiEnabled: false pid=5677, uid=10077
,09-15 03:36:35.305   925  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 03:36:35.306   925  3001 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 03:36:35.306   925  3001 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 03:36:35.307   925  3001 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 03:36:35.307   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:36:35.316   925  5874 D DhcpClient: Clearing IP address
,09-15 03:36:35.316   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 03:36:35.318   506   919 D CommandListener: Setting iface cfg
09-15 03:36:35.319  3614  5885 V NativeCrypto: SSL handshake aborted: ssl=0x7f780c9380: I/O error during system call, Connection timed out
,09-15 03:36:35.324   925  3458 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-15 03:36:35.324   925  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-15 03:36:35.325   925  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
09-15 03:36:35.328   925  5875 D DhcpClient: Receive thread stopped
09-15 03:36:35.332   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 03:36:35.332   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-15 03:36:35.333  4314  5888 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-15 03:36:35.338   925  5872 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:800::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-15 03:36:35.338   532   532 E Parcel  : Reading a NULL string not supported here.
,09-15 03:36:35.340   925  3003 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-15 03:36:35.340   925   925 D RttService: SCAN_AVAILABLE : 1
09-15 03:36:35.341   925  3107 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-15 03:36:35.341  3491  3653 W QCNEJ   : |CORE| network lost: 101
09-15 03:36:35.342  3491  3653 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-15 03:36:35.344   925  3001 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
09-15 03:36:35.346  4314  5888 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-15 03:36:35.346  4314  5888 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-15 03:36:35.347   925  3001 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 03:36:35.362   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:36:35.384   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:36:35.384   925  3003 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-15 03:36:35.384   506   919 D CommandListener: Clearing all IP addresses on wlan0
09-15 03:36:35.385   925  3003 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:36:35.387   925   942 D Tethering: MasterInitialState.processMessage what=3
09-15 03:36:35.388   925  3001 D DhcpClient: doQuit
09-15 03:36:35.389   925  3001 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 03:36:35.389   925  5874 D DhcpClient: onQuitting
09-15 03:36:35.389  5858  5858 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 03:36:35.390  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:35.390  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:35.391  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.391  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:36:35.394  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:35.394  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:35.395  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.395  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:36:35.395  4753  4753 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-15 03:36:35.396  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:35.396  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:35.396  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:35.396  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:35.397  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:35.398  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:35.399  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:35.399  4819  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 03:36:35.399  4819  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 03:36:35.399  4819  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 03:36:35.400  4819  4848 E SarControlService: no key has been found,reset the power
,09-15 03:36:35.400  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-15 03:36:35.400  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 03:36:35.400  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 03:36:35.400  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:36:35.401  4850  4850 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-15 03:36:35.403  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 03:36:35.403  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 03:36:35.403  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 03:36:35.405  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:36:35.405  4850  4850 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 03:36:35.405  5858  5858 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 03:36:35.408  5858  5858 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-15 03:36:35.409  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000ee03000000000000ffffffff]
09-15 03:36:35.409  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:36:35.409  4850  4887 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-15 03:36:35.409  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:36:35.410  4819  4831 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 03:36:35.412  3946  3946 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 03:36:35.413  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000ef03000000000000ffffffff]
09-15 03:36:35.413  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:36:35.413  4850  4887 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-15 03:36:35.414  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:36:35.414  4819  4830 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 03:36:35.419  3946  5304 I iu.UploadsManager: num queued entries: 0
09-15 03:36:35.420  3946  5304 I iu.UploadsManager: num updated entries: 0
,09-15 03:36:35.421  3946  3946 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 03:36:35.423  3946  3946 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 03:36:35.426  5826  5826 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:36:35.431  5826  5826 D SprintDMHelper: simOperator: 
09-15 03:36:35.431  5826  5826 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 03:36:35.438   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 03:36:35.439  3946  5304 I iu.SyncManager: NEXT; no task
09-15 03:36:35.439   925  3003 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-15 03:36:35.439   925  3003 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 03:36:35.442  4314  5906 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 03:36:35.450  5858  5858 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 03:36:35.461  5858  5858 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 03:36:35.563   925  3001 D wifi    : In wifi stop Hal
,09-15 03:36:35.563  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 03:36:35.564   925  3001 D wifi    : halHandle = 0x7f6602f0e0, mVM = 0x7f81f8d140, mCls = 0x201906
09-15 03:36:35.564   925  5857 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 03:36:35.564   925  5857 D WifiHAL : Got a signal to exit!!!
09-15 03:36:35.564   925  5857 I WifiHAL : Exit wifi_event_loop
09-15 03:36:35.568   925  3001 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 03:36:35.569   925  3001 E WifiHAL : Event processing terminated
,09-15 03:36:35.569   925  3001 D wifi    : In wifi cleaned up handler
,09-15 03:36:35.569  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:35.569   925  3001 I WifiHAL : Internal cleanup completed
09-15 03:36:35.570  3659  4055 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 03:36:35.572  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:35.576  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:35.595   925  5857 D wifi    : set interface wlan0 flags (DOWN)
,09-15 03:36:35.595   925  3001 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 03:36:35.655   506   919 E Netd    : netlink response contains error (No such file or directory)
,09-15 03:36:35.801   925   942 D Tethering: InitialState.processMessage what=4
,09-15 03:36:35.808   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 03:36:36.179   925  3003 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-15 03:36:40.344   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@861ba23:true
,09-15 03:36:40.345  5809  5809 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 03:36:40.351  5809  5809 I bt_bluedroid: init
,09-15 03:36:40.351  5809  5914 I BluetoothAdapterState: Entering OffState
,09-15 03:36:40.354  5809  5915 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 03:36:40.354  5809  5915 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 03:36:40.354  5809  5915 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 03:36:40.355  5809  5915 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 03:36:40.355  5809  5809 I bt_bluedroid: get_profile_interface socket
,09-15 03:36:40.358  5809  5809 I bt_bluedroid: get_profile_interface sdp
,09-15 03:36:40.359  5809  5918 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 03:36:40.361  5809  5918 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 03:36:40.368  5809  5820 I bt_bluedroid: config_hci_snoop_log
,09-15 03:36:40.369   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-15 03:36:40.374  5809  5914 D BluetoothAdapterState: Current state: OFF, message: 0
09-15 03:36:40.374  5809  5914 D BluetoothAdapterProperties: Setting state to 14
,09-15 03:36:40.375  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 03:36:40.377  5809  5914 D BluetoothBondStateMachine: make
,09-15 03:36:40.379  5809  5919 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 03:36:40.383  5809  5914 I BluetoothAdapterState: Entering PendingCommandState
,09-15 03:36:40.384  5809  5809 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 03:36:40.387  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:40.387  5809  5809 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 03:36:40.388  5809  5809 D BtGatt.GattService: Received start request. Starting profile...
,09-15 03:36:40.388  5809  5809 D BtGatt.GattService: start()
09-15 03:36:40.388  5809  5809 I bt_bluedroid: get_profile_interface gatt
09-15 03:36:40.389  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:40.389  5809  5809 D BtGatt.AdvertiseManager: advertise manager created
,09-15 03:36:40.395  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:40.395  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:40.395  5809  5809 V BluetoothAdapterState: isBleTurningOn()=true
09-15 03:36:40.395  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:40.395  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 03:36:40.397  5809  5914 I bt_bluedroid: bt_bluedroid
09-15 03:36:40.397  5809  5915 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 03:36:40.397  5809  5915 I bt_hci  : start_up
,09-15 03:36:40.403  5809  5915 I bt_vendor: alloc value 0xf3c38871
,09-15 03:36:40.403  5809  5915 I bt_vendor: init
09-15 03:36:40.403  5809  5915 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 03:36:40.403  5809  5915 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 03:36:40.514  5809  5915 D bt_hci  : start_up starting async portion
09-15 03:36:40.515  5809  5922 I bt_hci  : event_finish_startup
,09-15 03:36:40.515  5809  5922 I bt_hci_h4: hal_open
,09-15 03:36:40.515  5809  5922 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 03:36:40.511  5923  5923 W irq/448-msm_hs_: type=1400 audit(0.0:134): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 03:36:40.517  5809  5922 I bt_userial_vendor: device fd = 54 open
,09-15 03:36:40.531  5809  5922 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 03:36:40.534  5809  5922 D bt_hwcfg: Chipset BCM4358A3
09-15 03:36:40.534  5809  5922 D bt_hwcfg: Target name = [BCM4358A3]
,09-15 03:36:40.534  5809  5922 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 03:36:40.895  5809  5922 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 03:36:40.895  5809  5922 D bt_hwcfg: Settlement delay -- 100 ms
09-15 03:36:40.895  5809  5922 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 03:36:41.030  5809  5922 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 03:36:41.031  5809  5922 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 03:36:41.032  5809  5922 I bt_hwcfg: vendor lib fwcfg completed
,09-15 03:36:41.032  5809  5922 I bt_vendor: firmware callback
,09-15 03:36:41.032  5809  5922 I bt_hci  : firmware_config_callback
,09-15 03:36:41.042  5809  5925 I bt_btu  : btu_task pending for preload complete event
,09-15 03:36:41.042  5809  5925 I bt_btu_task: Bluetooth chip preload is complete
09-15 03:36:41.043  5809  5925 I bt_btu  : btu_task received preload complete event
,09-15 03:36:41.049  5809  5925 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 03:36:41.049  5809  5925 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 03:36:41.049  5809  5925 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 03:36:41.049  5809  5925 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 03:36:41.050  5809  5925 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 03:36:41.050  5809  5925 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 03:36:41.050  5809  5925 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-15 03:36:41.050  5809  5925 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 03:36:41.050  5809  5925 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 03:36:41.051  5809  5925 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 03:36:41.051  5809  5925 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 03:36:41.051  5809  5925 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 03:36:41.051  5809  5925 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 03:36:41.052  5809  5925 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-15 03:36:41.052  5809  5925 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 03:36:41.134  5809  5925 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bb6549
,09-15 03:36:41.134  5809  5925 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bb6549 
,09-15 03:36:41.154  5809  5918 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 03:36:41.156  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 03:36:41.157  5809  5918 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 03:36:41.160  5809  5918 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 03:36:41.162  5809  5918 D BluetoothAdapterProperties: Scan Mode:20
,09-15 03:36:41.163  5809  5918 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 03:36:41.163  5809  5918 D bt_hci  : do_postload posting postload work item
09-15 03:36:41.163  5809  5922 I bt_hci  : event_postload
09-15 03:36:41.164  5809  5922 I bt_vendor: sco_config_cb
09-15 03:36:41.164  5809  5922 I bt_hci  : sco_config_callback postload finished.
09-15 03:36:41.166  5809  5918 D bt_bte_conf: Device ID record 1 : primary
,09-15 03:36:41.166  5809  5918 D bt_bte_conf:   vendorId            = 000f
09-15 03:36:41.166  5809  5918 D bt_bte_conf:   vendorIdSource      = 0001
09-15 03:36:41.166  5809  5918 D bt_bte_conf:   product             = 1200
09-15 03:36:41.167  5809  5918 D bt_bte_conf:   version             = 1436
09-15 03:36:41.168  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:41.167  5809  5918 D bt_bte_conf:   clientExecutableURL = 
09-15 03:36:41.168  5809  5918 D bt_bte_conf:   serviceDescription  = 
09-15 03:36:41.168  5809  5918 D bt_bte_conf:   documentationURL    = 
09-15 03:36:41.169  5809  5918 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 03:36:41.169  5809  5915 D bt_stack_manager: event_start_up_stack finished
09-15 03:36:41.170  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 03:36:41.171  5809  5914 D BluetoothAdapterProperties: Setting state to 15
09-15 03:36:41.171  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 03:36:41.172  5809  5922 I bt_vendor: low_power_mode_cb
09-15 03:36:41.173  5809  5914 I BluetoothAdapterState: Entering BleOnState
09-15 03:36:41.174  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:41.178  5809  5914 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 03:36:41.179  5809  5914 D BluetoothAdapterProperties: Setting state to 11
09-15 03:36:41.179  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-15 03:36:41.184  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:41.187  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:41.187  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:41.188  5809  5809 D HeadsetService: Received start request. Starting profile...
09-15 03:36:41.189  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:41.191  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:41.191  5809  5809 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 03:36:41.191  5809  5809 D HeadsetStateMachine: make
,09-15 03:36:41.196  5809  5914 I BluetoothAdapterState: Entering PendingCommandState
,09-15 03:36:41.201  5809  5809 D HeadsetStateMachine: max_hf_connections = 1
09-15 03:36:41.202  5809  5809 I bt_bluedroid: get_profile_interface handsfree
09-15 03:36:41.202  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 03:36:41.202  5809  5918 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 03:36:41.205  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:41.205  5809  5809 D A2dpService: Received start request. Starting profile...
,09-15 03:36:41.206  5809  5809 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-15 03:36:41.206  5809  5809 I bt_bluedroid: get_profile_interface avrcp
,09-15 03:36:41.213  5809  5809 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-15 03:36:41.213  5809  5809 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 03:36:41.213  5809  5809 D A2dpStateMachine: make
,09-15 03:36:41.214  5809  5809 I bt_bluedroid: get_profile_interface a2dp
09-15 03:36:41.214  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 03:36:41.216  5809  5934 D A2dpStateMachine: Enter Disconnected: -2
09-15 03:36:41.216  5809  5809 I BluetoothHidServiceJni: classInitNative: succeeds
09-15 03:36:41.217  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
,09-15 03:36:41.218  5809  5809 D HidService: Received start request. Starting profile...
,09-15 03:36:41.218  5809  5809 I bt_bluedroid: get_profile_interface hidhost
09-15 03:36:41.218  5809  5809 D HidService: setHidService(): set to: null
09-15 03:36:41.218  5809  5918 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9756d
09-15 03:36:41.218  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 03:36:41.219  5809  5809 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 03:36:41.219  5749  5749 D BluetoothInputDevice: Proxy object connected
09-15 03:36:41.219  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
,09-15 03:36:41.220  5749  5749 D HidProfile: Bluetooth service connected
09-15 03:36:41.220  5809  5809 D HealthService: Received start request. Starting profile...
09-15 03:36:41.222  5809  5809 I bt_bluedroid: get_profile_interface health
09-15 03:36:41.222  5809  5809 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 03:36:41.223  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
,09-15 03:36:41.225  5809  5809 D PanService: Received start request. Starting profile...
,09-15 03:36:41.225  5809  5809 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 03:36:41.225  5809  5809 I bt_bluedroid: get_profile_interface pan
09-15 03:36:41.225  5809  5918 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 03:36:41.227  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:41.227  5749  5749 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 03:36:41.228  5809  5809 D BluetoothMapService: Received start request. Starting profile...
09-15 03:36:41.228  5809  5809 D BluetoothMapService: start()
,09-15 03:36:41.233  5749  5749 D PanProfile: Bluetooth service connected
,09-15 03:36:41.233  5749  5749 D BluetoothMap: Proxy object connected
09-15 03:36:41.233  5749  5749 D MapProfile: Bluetooth service connected
09-15 03:36:41.233  5749  5749 D BluetoothMap: getConnectedDevices()
09-15 03:36:41.234  5809  5809 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 03:36:41.234  5749  5749 D BluetoothMap: Bluetooth is Not enabled
,09-15 03:36:41.235  5809  5809 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 03:36:41.235  5809  5809 D BluetoothMapAppObserver: createReceiver()
09-15 03:36:41.236  5809  5809 D BluetoothMapAppObserver: initObservers()
09-15 03:36:41.236  5809  5809 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 03:36:41.243  5809  5809 V SapService: SapBinder()
,09-15 03:36:41.243  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 03:36:41.243  5809  5809 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:41.244  5809  5809 D SapService: Received start request. Starting profile...
09-15 03:36:41.244  5809  5809 V SapService: start()
,09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.247  5809  5932 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.247  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:41.248  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.249  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:41.249  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.249  5809  5809 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:41.250  5809  5809 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:41.250  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:41.250  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:41.250  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 03:36:41.250  5809  5914 D BluetoothAdapterProperties: ScanMode =  20
09-15 03:36:41.250  5809  5914 D BluetoothAdapterProperties: State =  11
09-15 03:36:41.250  5809  5914 D BluetoothAdapterProperties: Setting state to 12
,09-15 03:36:41.250  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 03:36:41.251  5809  5914 I BluetoothAdapterState: Entering OnState
09-15 03:36:41.251  5809  5918 D BluetoothAdapterProperties: Scan Mode:21
09-15 03:36:41.251  5749  5762 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 03:36:41.252  5809  5918 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 03:36:41.252  3166  3770 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 03:36:41.255  5749  5760 D BluetoothMap: onBluetoothStateChange: up=true
09-15 03:36:41.255  5749  5762 D BluetoothPan: onBluetoothStateChange on: true
09-15 03:36:41.255   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:41.255  3166  3179 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:41.255  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:41.256  3166  3180 D BluetoothMap: onBluetoothStateChange: up=true
09-15 03:36:41.257  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:41.257  3166  3166 D BluetoothMap: Proxy object connected
09-15 03:36:41.257  3166  3770 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 03:36:41.257  3166  3166 D MapProfile: Bluetooth service connected
09-15 03:36:41.257  3166  3166 D BluetoothMap: getConnectedDevices()
,09-15 03:36:41.259  5749  5760 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 03:36:41.260  3166  3166 D BluetoothA2dp: Proxy object connected
,09-15 03:36:41.261  3532  3544 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:41.261  3166  3180 D BluetoothPan: onBluetoothStateChange on: true
09-15 03:36:41.262  5809  5809 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:41.262  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:41.262  5809  5809 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 03:36:41.263  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 03:36:41.263  3166  3770 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 03:36:41.263  3166  3166 D PanProfile: Bluetooth service connected
09-15 03:36:41.264  5809  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:41.264  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:41.265   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:41.265  3166  3166 D BluetoothInputDevice: Proxy object connected
09-15 03:36:41.265   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:41.265  3166  3166 D HidProfile: Bluetooth service connected
09-15 03:36:41.265   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 03:36:41.265   925   925 D BluetoothA2dp: Proxy object connected
,09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:41.268  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:41.269  5749  5749 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 03:36:41.270   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 03:36:41.270  5809  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:36:41.271  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:41.272  5809  5809 D ObexServerSockets: Succeed to create listening sockets 
09-15 03:36:41.272  5809  5809 D ObexServerSockets0: startAccept()
09-15 03:36:41.273  5809  5809 D ObexServerSockets0: prepareForNewConnect()
09-15 03:36:41.273  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:41.274  5749  5749 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-15 03:36:41.274  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:41.275  5809  5809 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 03:36:41.275  5809  5809 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 03:36:41.276  5809  5941 D ObexServerSockets0: Accepting socket connection...
09-15 03:36:41.276  5809  5809 D BluetoothMapService: onReceive
09-15 03:36:41.276  5809  5809 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 03:36:41.276  5809  5809 D BluetoothMapService: STATE_ON
09-15 03:36:41.277  5809  5942 D ObexServerSockets0: Accepting socket connection...
09-15 03:36:41.277  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:41.278  5809  5943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:41.281  5809  5943 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-15 03:36:41.281  5809  5943 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 03:36:41.282  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 03:36:41.285  5749  5749 D BluetoothA2dp: Proxy object connected
,09-15 03:36:41.289  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 03:36:41.292  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-15 03:36:41.295  3166  3166 D BluetoothPbap: Proxy object connected
09-15 03:36:41.295  3166  3166 D PbapServerProfile: Bluetooth service connected
09-15 03:36:41.295  5749  5749 D BluetoothPbap: Proxy object connected
,09-15 03:36:41.296  5749  5749 D PbapServerProfile: Bluetooth service connected
,09-15 03:36:41.302  5809  5809 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 03:36:41.302  5809  5809 D ObexServerSockets0: prepareForNewConnect()
09-15 03:36:41.302  5809  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:41.318  5809  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:41.319  5809  5951 I BtOppRfcommListener: Accept thread started.
,09-15 03:36:41.356   925   925 D BluetoothHeadset: Proxy object connected
09-15 03:36:41.356   925   925 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.357  3532  3875 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.357  3166  3180 D BluetoothHeadset: Proxy object connected
09-15 03:36:41.357  3166  3166 D HeadsetProfile: Bluetooth service connected
09-15 03:36:41.357   925   925 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.362  3532  3549 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.364   925   942 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.364   925   942 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.377  5749  5762 D BluetoothHeadset: Proxy object connected
,09-15 03:36:41.378  5749  5749 D HeadsetProfile: Bluetooth service connected
,09-15 03:36:43.129   925  3003 D ConnectivityService: handlePromptUnvalidated 101
,09-15 03:36:45.322  5809  5914 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 03:36:45.322  5809  5914 D BluetoothAdapterProperties: Setting state to 13
09-15 03:36:45.322  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-15 03:36:45.324  5809  5914 D BluetoothAdapterProperties: onBluetoothDisable()
,09-15 03:36:45.326  5809  5914 I BluetoothAdapterState: Entering PendingCommandState
09-15 03:36:45.331  5809  5809 D BluetoothMapService: onReceive
09-15 03:36:45.331  5809  5809 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-15 03:36:45.331  5809  5809 D BluetoothMapService: STATE_TURNING_OFF
09-15 03:36:45.332  5809  5809 D BluetoothMapService: MAP Service closeService in
,09-15 03:36:45.332  5809  5809 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 03:36:45.332  5809  5809 D ObexServerSockets0: shutdown(block = true)
09-15 03:36:45.334  5809  5809 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 03:36:45.334  5809  5941 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 03:36:45.334  5809  5809 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 03:36:45.334  5809  5927 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 03:36:45.335  5809  5942 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-15 03:36:45.336  5809  5809 I BtOppRfcommListener: stopping Accept Thread
09-15 03:36:45.338  5809  5951 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 03:36:45.339  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:45.340  5809  5951 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 03:36:45.341  5809  5918 D BluetoothAdapterProperties: Scan Mode:20
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:45.341  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:45.341  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-15 03:36:45.347  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:45.347  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:36:45.348  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 03:36:45.351  5809  5809 D HeadsetService: Received stop request...Stopping profile...
,09-15 03:36:45.353  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:45.353  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 03:36:45.354   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:45.354  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:45.354   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:45.354  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:45.355  3532  3876 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:45.356  3166  3180 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:45.356  3166  3166 D HeadsetProfile: Bluetooth service disconnected
09-15 03:36:45.356   925   925 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:45.357  5749  5760 D BluetoothHeadset: Proxy object disconnected
09-15 03:36:45.358  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:45.358  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:36:45.359  5677  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 03:36:45.359  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:45.359  5749  5749 D DockEventReceiver: finishStartingService: stopping service
09-15 03:36:45.360  5749  5749 D HeadsetProfile: Bluetooth service disconnected
09-15 03:36:45.361  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:45.363  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:45.364  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:45.364  5809  5809 D A2dpService: Received stop request...Stopping profile...
09-15 03:36:45.365  5809  5934 D A2dpStateMachine: Exit Disconnected: -1
09-15 03:36:45.366   925   925 D BluetoothA2dp: Proxy object disconnected
09-15 03:36:45.367  3166  3166 D BluetoothA2dp: Proxy object disconnected
09-15 03:36:45.367  5809  5809 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:45.367  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.367  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.367  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:45.368  5749  5749 D BluetoothA2dp: Proxy object disconnected
09-15 03:36:45.370  5809  5809 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 03:36:45.370  5809  5809 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 03:36:45.370  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 03:36:45.370  5809  5925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:45.370  5809  5925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:45.370  5809  5925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:45.370  5809  5918 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 03:36:45.372  5809  5809 D HidService: Received stop request...Stopping profile...
09-15 03:36:45.373  5809  5809 D HidService: Stopping Bluetooth HidService
,09-15 03:36:45.373  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 03:36:45.374  5809  5809 D HealthService: Received stop request...Stopping profile...
09-15 03:36:45.375  3166  3166 D BluetoothInputDevice: Proxy object disconnected
09-15 03:36:45.375  3166  3166 D HidProfile: Bluetooth service disconnected
09-15 03:36:45.375  5809  5809 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:45.375  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.375  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.375  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:45.376  5809  5809 D PanService: Received stop request...Stopping profile...
09-15 03:36:45.376  3166  3166 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 03:36:45.376  3166  3166 D PanProfile: Bluetooth service disconnected
09-15 03:36:45.378  5809  5925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:45.378  5809  5925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:45.379  5809  5925 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 03:36:45.379  5809  5925 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 03:36:45.379  5809  5925 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 03:36:45.379  5809  5925 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 03:36:45.379  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 03:36:45.379  5809  5809 D BluetoothMapService: Received stop request...Stopping profile...
09-15 03:36:45.379  5809  5809 D BluetoothMapService: stop()
,09-15 03:36:45.380  5749  5749 D BluetoothInputDevice: Proxy object disconnected
09-15 03:36:45.380  5749  5749 D HidProfile: Bluetooth service disconnected
09-15 03:36:45.381  5809  5809 D BluetoothMapAppObserver: deinitObservers()
09-15 03:36:45.381  5809  5809 D BluetoothMapAppObserver: removeReceiver()
09-15 03:36:45.382  5749  5749 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 03:36:45.382  3166  3166 D BluetoothMap: Proxy object disconnected
09-15 03:36:45.382  3166  3166 D MapProfile: Bluetooth service disconnected
09-15 03:36:45.382  5749  5749 D PanProfile: Bluetooth service disconnected
09-15 03:36:45.383  5749  5749 D BluetoothMap: Proxy object disconnected
09-15 03:36:45.383  5749  5749 D MapProfile: Bluetooth service disconnected
09-15 03:36:45.383  5809  5809 D SapService: Received stop request...Stopping profile...
09-15 03:36:45.383  5809  5809 V SapService: stop()
,09-15 03:36:45.387  5809  5809 V BluetoothAdapterState: isTurningOff()=true
,09-15 03:36:45.387  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.387  5749  5749 D BluetoothPbap: Proxy object disconnected
09-15 03:36:45.387  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.387  5749  5749 D PbapServerProfile: Bluetooth service disconnected
09-15 03:36:45.387  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:45.387  3166  3166 D BluetoothPbap: Proxy object disconnected
09-15 03:36:45.387  3166  3166 D PbapServerProfile: Bluetooth service disconnected
09-15 03:36:45.387  5809  5809 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 03:36:45.387  5809  5809 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 03:36:45.388  5809  5809 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:45.388  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.388  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.388  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 03:36:45.388  5809  5809 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 03:36:45.389  5809  5809 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 03:36:45.389  5809  5809 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:45.389  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.389  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.389  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:45.389  5809  5809 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 03:36:45.389  5809  5809 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 03:36:45.390  5809  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 03:36:45.390  5809  5918 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 03:36:45.390  5809  5809 D BluetoothMapService: MAP Service closeService in
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:45.391  5809  5809 D BluetoothMapService: cleanup()
,09-15 03:36:45.391  5809  5809 D BluetoothMapService: MAP Service closeService in
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isTurningOff()=true
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:45.391  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.392  5809  5809 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:45.392  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 03:36:45.392  5809  5914 D BluetoothAdapterProperties: Setting state to 15
09-15 03:36:45.392  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 03:36:45.392  5809  5914 I BluetoothAdapterState: Entering BleOnState
,09-15 03:36:45.393  5749  5762 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 03:36:45.395  3166  3180 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 03:36:45.396  5749  5957 D BluetoothMap: onBluetoothStateChange: up=false
09-15 03:36:45.396  5749  5760 D BluetoothPan: onBluetoothStateChange on: false
09-15 03:36:45.397   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 03:36:45.397  3166  3179 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:45.397  3166  3769 D BluetoothMap: onBluetoothStateChange: up=false
09-15 03:36:45.398  3166  3770 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 03:36:45.398  5749  5762 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 03:36:45.399  3532  3544 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:45.399  5749  5957 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 03:36:45.400  3166  3180 D BluetoothPan: onBluetoothStateChange on: false
09-15 03:36:45.400  3166  3179 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 03:36:45.401   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:45.401   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 03:36:45.401   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 03:36:45.401  5749  5760 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 03:36:45.401  5809  5914 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 03:36:45.401  5809  5914 D BluetoothAdapterProperties: Setting state to 16
09-15 03:36:45.401  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 03:36:45.402  5809  5914 D BluetoothAdapterProperties: onBleDisable
09-15 03:36:45.402  5809  5914 I BluetoothAdapterState: Entering PendingCommandState
09-15 03:36:45.402  5809  5915 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 03:36:45.403  5809  5925 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 03:36:45.403  5809  5925 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 03:36:45.404  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:45.406  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:45.406  5809  5918 D BluetoothAdapterProperties: Scan Mode:20
09-15 03:36:45.407  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:45.408  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 03:36:45.409  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:45.410  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:45.413  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:45.413  5749  5749 D DockEventReceiver: finishStartingService: stopping service
09-15 03:36:45.413  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 03:36:45.621  5809  5918 I bt_hci  : shut_down
,09-15 03:36:45.633  5809  5922 I bt_vendor: low_power_mode_cb
,09-15 03:36:45.636  5809  5922 D bt_hwcfg: hw_epilog_process
,09-15 03:36:45.639  5809  5922 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 03:36:45.639  5809  5922 I bt_vendor: epilog_cb
09-15 03:36:45.639  5809  5922 I bt_hci  : epilog_finished_callback
,09-15 03:36:45.645  5809  5918 I bt_hci_h4: hal_close
,09-15 03:36:45.646  5809  5918 I bt_userial_vendor: device fd = 54 close
,09-15 03:36:45.764  5809  5915 D bt_stack_manager: event_shut_down_stack finished.
,09-15 03:36:45.765  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 03:36:45.770  5809  5809 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 03:36:45.771  5809  5914 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 03:36:45.771  5809  5809 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 03:36:45.771  5809  5809 D BtGatt.GattService: stop()
,09-15 03:36:45.772  5809  5809 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 03:36:45.774  5809  5809 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:45.774  5809  5809 V BluetoothAdapterState: isTurningOn()=false
,09-15 03:36:45.775  5809  5809 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:45.775  5809  5809 V BluetoothAdapterState: isBleTurningOff()=true
09-15 03:36:45.775  5809  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-15 03:36:45.776  5809  5914 D BluetoothAdapterProperties: Setting state to 10
09-15 03:36:45.776  5809  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 03:36:45.777  5809  5914 I BluetoothAdapterState: Entering OffState
09-15 03:36:45.778   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 03:36:45.794  5809  5809 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 03:36:45.795  5809  5809 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 03:36:45.795  5809  5809 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 03:36:45.797  5809  5915 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 03:36:45.807  5809  5809 I art     : System.exit called, status: 0
,09-15 03:36:45.808  5809  5809 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 03:36:45.839   925  3457 I ActivityManager: Process com.android.bluetooth (pid 5809) has died
,09-15 03:36:50.320  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 03:36:50.320  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:36:50.326  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:50.328  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9e53c16 removed from the list
09-15 03:36:50.328  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:36:50.329  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:50.329  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:50.331  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:36:50.332  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af2f784 added. We now have 4 listener(s)
09-15 03:36:50.332  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:36:50.334  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:36:50.334  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af2f784 removed from the list
,09-15 03:36:50.334  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 03:36:50.335  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:36:50.335  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:36:50.337  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:36:50.337  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f5cb6d added. We now have 4 listener(s)
,09-15 03:36:50.337  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:36:52.985  3431  3596 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-15 03:36:52.986  3431  3596 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-15 03:36:53.024  3614  3614 I ConfigService: onCreate
,09-15 03:36:55.348  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:55.382   925   942 I ActivityManager: Start proc 5963:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 03:36:55.474  5963  5963 D AdapterServiceConfig: Adding HeadsetService
,09-15 03:36:55.474  5963  5963 D AdapterServiceConfig: Adding A2dpService
,09-15 03:36:55.475  5963  5963 D AdapterServiceConfig: Adding HidService
09-15 03:36:55.475  5963  5963 D AdapterServiceConfig: Adding HealthService
09-15 03:36:55.475  5963  5963 D AdapterServiceConfig: Adding PanService
,09-15 03:36:55.475  5963  5963 D AdapterServiceConfig: Adding GattService
09-15 03:36:55.475  5963  5963 D AdapterServiceConfig: Adding BluetoothMapService
09-15 03:36:55.476  5963  5963 D AdapterServiceConfig: Adding SapService
,09-15 03:36:55.486   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6c1f15e:true
,09-15 03:36:55.486  5963  5963 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 03:36:55.489  5963  5963 I bt_bluedroid: init
09-15 03:36:55.490  5963  5975 I BluetoothAdapterState: Entering OffState
,09-15 03:36:55.492  5963  5976 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 03:36:55.492  5963  5976 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 03:36:55.492  5963  5976 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 03:36:55.492  5963  5976 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 03:36:55.493  5963  5963 I bt_bluedroid: get_profile_interface socket
,09-15 03:36:55.496  5963  5979 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 03:36:55.496  5963  5963 I bt_bluedroid: get_profile_interface sdp
,09-15 03:36:55.499  5963  5979 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 03:36:55.502  5963  5974 I bt_bluedroid: config_hci_snoop_log
09-15 03:36:55.503   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 03:36:55.507  5963  5975 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 03:36:55.508  5963  5975 D BluetoothAdapterProperties: Setting state to 14
09-15 03:36:55.508  5963  5975 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 03:36:55.509  5963  5975 D BluetoothBondStateMachine: make
,09-15 03:36:55.511  5963  5980 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 03:36:55.514  5963  5975 I BluetoothAdapterState: Entering PendingCommandState
,09-15 03:36:55.515  5963  5963 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 03:36:55.518  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
,09-15 03:36:55.519  5963  5963 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 03:36:55.519  5963  5963 D BtGatt.GattService: Received start request. Starting profile...
09-15 03:36:55.519  5963  5963 D BtGatt.GattService: start()
09-15 03:36:55.519  5963  5963 I bt_bluedroid: get_profile_interface gatt
,09-15 03:36:55.521  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:55.521  5963  5963 D BtGatt.AdvertiseManager: advertise manager created
,09-15 03:36:55.527  5963  5963 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:55.527  5963  5963 V BluetoothAdapterState: isTurningOn()=false
09-15 03:36:55.527  5963  5963 V BluetoothAdapterState: isBleTurningOn()=true
,09-15 03:36:55.527  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 03:36:55.527  5963  5975 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 03:36:55.529  5963  5975 I bt_bluedroid: bt_bluedroid
09-15 03:36:55.530  5963  5976 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 03:36:55.530  5963  5976 I bt_hci  : start_up
,09-15 03:36:55.535  5963  5976 I bt_vendor: alloc value 0xf3cb5871
,09-15 03:36:55.535  5963  5976 I bt_vendor: init
09-15 03:36:55.535  5963  5976 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 03:36:55.535  5963  5976 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 03:36:55.646  5963  5976 D bt_hci  : start_up starting async portion
,09-15 03:36:55.646  5963  5983 I bt_hci  : event_finish_startup
09-15 03:36:55.646  5963  5983 I bt_hci_h4: hal_open
,09-15 03:36:55.646  5963  5983 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 03:36:55.650  5963  5983 I bt_userial_vendor: device fd = 54 open
,09-15 03:36:55.644  5984  5984 W irq/448-msm_hs_: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 03:36:55.666  5963  5983 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 03:36:55.669  5963  5983 D bt_hwcfg: Chipset BCM4358A3
,09-15 03:36:55.669  5963  5983 D bt_hwcfg: Target name = [BCM4358A3]
09-15 03:36:55.670  5963  5983 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 03:36:56.075  5963  5983 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-15 03:36:56.075  5963  5983 D bt_hwcfg: Settlement delay -- 100 ms
,09-15 03:36:56.075  5963  5983 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 03:36:56.210  5963  5983 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 03:36:56.210  5963  5983 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 03:36:56.212  5963  5983 I bt_hwcfg: vendor lib fwcfg completed
09-15 03:36:56.212  5963  5983 I bt_vendor: firmware callback
09-15 03:36:56.212  5963  5983 I bt_hci  : firmware_config_callback
,09-15 03:36:56.221  5963  5986 I bt_btu  : btu_task pending for preload complete event
,09-15 03:36:56.221  5963  5986 I bt_btu_task: Bluetooth chip preload is complete
09-15 03:36:56.221  5963  5986 I bt_btu  : btu_task received preload complete event
,09-15 03:36:56.229  5963  5986 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 03:36:56.229  5963  5986 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 03:36:56.229  5963  5986 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-15 03:36:56.229  5963  5986 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 03:36:56.229  5963  5986 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-15 03:36:56.230  5963  5986 I         : BTE_InitTraceLevels -- TRC_A2D
,09-15 03:36:56.230  5963  5986 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 03:36:56.230  5963  5986 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 03:36:56.230  5963  5986 I         : BTE_InitTraceLevels -- TRC_GAP
,09-15 03:36:56.231  5963  5986 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 03:36:56.231  5963  5986 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 03:36:56.231  5963  5986 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 03:36:56.231  5963  5986 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 03:36:56.232  5963  5986 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 03:36:56.232  5963  5986 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 03:36:56.317  5963  5986 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c33549
,09-15 03:36:56.317  5963  5986 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c33549 
,09-15 03:36:56.339  5963  5979 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,09-15 03:36:56.340  5963  5979 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 03:36:56.341  5963  5979 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 03:36:56.343  5963  5979 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 03:36:56.346  5963  5979 D BluetoothAdapterProperties: Scan Mode:20
,09-15 03:36:56.346  5963  5979 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 03:36:56.346  5963  5979 D bt_hci  : do_postload posting postload work item
09-15 03:36:56.346  5963  5983 I bt_hci  : event_postload
,09-15 03:36:56.346  5963  5983 I bt_vendor: sco_config_cb
09-15 03:36:56.346  5963  5983 I bt_hci  : sco_config_callback postload finished.
,09-15 03:36:56.349  5963  5979 D bt_bte_conf: Device ID record 1 : primary
09-15 03:36:56.349  5963  5979 D bt_bte_conf:   vendorId            = 000f
09-15 03:36:56.349  5963  5979 D bt_bte_conf:   vendorIdSource      = 0001
09-15 03:36:56.349  5963  5979 D bt_bte_conf:   product             = 1200
09-15 03:36:56.349  5963  5979 D bt_bte_conf:   version             = 1436
,09-15 03:36:56.349  5963  5979 D bt_bte_conf:   clientExecutableURL = 
09-15 03:36:56.350  5963  5979 D bt_bte_conf:   serviceDescription  = 
09-15 03:36:56.350  5963  5979 D bt_bte_conf:   documentationURL    = 
09-15 03:36:56.350  5963  5979 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 03:36:56.350  5963  5976 D bt_stack_manager: event_start_up_stack finished
09-15 03:36:56.351  5963  5975 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 03:36:56.351  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:56.351  5963  5975 D BluetoothAdapterProperties: Setting state to 15
09-15 03:36:56.351  5963  5975 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-15 03:36:56.352  5963  5975 I BluetoothAdapterState: Entering BleOnState
09-15 03:36:56.356  5963  5983 I bt_vendor: low_power_mode_cb
09-15 03:36:56.356  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:56.359  5963  5975 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 03:36:56.359  5963  5975 D BluetoothAdapterProperties: Setting state to 11
09-15 03:36:56.359  5963  5975 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 03:36:56.364  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:56.365  5963  5963 D HeadsetService: Received start request. Starting profile...
09-15 03:36:56.369  5963  5963 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 03:36:56.370  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:36:56.369  5963  5963 D HeadsetStateMachine: make
,09-15 03:36:56.372  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:56.379  5963  5975 I BluetoothAdapterState: Entering PendingCommandState
,09-15 03:36:56.382  5963  5963 D HeadsetStateMachine: max_hf_connections = 1
,09-15 03:36:56.382  5963  5963 I bt_bluedroid: get_profile_interface handsfree
09-15 03:36:56.382  5963  5979 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 03:36:56.382  5963  5979 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 03:36:56.385  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:56.385  5963  5963 D A2dpService: Received start request. Starting profile...
09-15 03:36:56.386  5963  5963 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 03:36:56.387  5963  5963 I bt_bluedroid: get_profile_interface avrcp
,09-15 03:36:56.392  5963  5963 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 03:36:56.392  5963  5963 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 03:36:56.392  5963  5963 D A2dpStateMachine: make
09-15 03:36:56.393  5963  5963 I bt_bluedroid: get_profile_interface a2dp
,09-15 03:36:56.394  5963  5979 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 03:36:56.395  5963  5994 D A2dpStateMachine: Enter Disconnected: -2
,09-15 03:36:56.396  5963  5963 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 03:36:56.397  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
,09-15 03:36:56.397  5963  5963 D HidService: Received start request. Starting profile...
09-15 03:36:56.398  5963  5963 I bt_bluedroid: get_profile_interface hidhost
09-15 03:36:56.398  5963  5963 D HidService: setHidService(): set to: null
09-15 03:36:56.398  5963  5979 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c1456d
09-15 03:36:56.398  5963  5979 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 03:36:56.399  5963  5963 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 03:36:56.400  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:56.400  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 03:36:56.400  5963  5963 D HealthService: Received start request. Starting profile...
,09-15 03:36:56.402  5963  5963 I bt_bluedroid: get_profile_interface health
,09-15 03:36:56.403  5963  5963 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 03:36:56.404  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:56.405  5963  5963 D PanService: Received start request. Starting profile...
09-15 03:36:56.405  5963  5963 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 03:36:56.406  5963  5963 I bt_bluedroid: get_profile_interface pan
09-15 03:36:56.406  5963  5979 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 03:36:56.409  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
,09-15 03:36:56.410  5963  5963 D BluetoothMapService: Received start request. Starting profile...
,09-15 03:36:56.410  5963  5963 D BluetoothMapService: start()
09-15 03:36:56.412  5963  5963 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 03:36:56.413  5963  5963 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 03:36:56.413  5963  5963 D BluetoothMapAppObserver: createReceiver()
,09-15 03:36:56.415  5963  5963 D BluetoothMapAppObserver: initObservers()
,09-15 03:36:56.415  5963  5963 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 03:36:56.422  5963  5963 V SapService: SapBinder()
,09-15 03:36:56.422  5963  5963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:36:56.422  5963  5963 D SapService: Received start request. Starting profile...
09-15 03:36:56.422  5963  5963 V SapService: start()
,09-15 03:36:56.424  5963  5963 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.425  5963  5992 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.425  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.426  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:56.426  5963  5963 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:56.426  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.426  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.426  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isTurningOff()=false
,09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.427  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 03:36:56.428  5963  5963 V BluetoothAdapterState: isTurningOff()=false
09-15 03:36:56.428  5963  5963 V BluetoothAdapterState: isTurningOn()=true
09-15 03:36:56.428  5963  5963 V BluetoothAdapterState: isBleTurningOn()=false
09-15 03:36:56.428  5963  5963 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 03:36:56.429  5963  5975 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 03:36:56.429  5963  5975 D BluetoothAdapterProperties: ScanMode =  20
,09-15 03:36:56.429  5963  5975 D BluetoothAdapterProperties: State =  11
09-15 03:36:56.429  5963  5975 D BluetoothAdapterProperties: Setting state to 12
09-15 03:36:56.429  5963  5975 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 03:36:56.430  5963  5975 I BluetoothAdapterState: Entering OnState
09-15 03:36:56.430  5749  5957 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 03:36:56.431  5963  5979 D BluetoothAdapterProperties: Scan Mode:21
09-15 03:36:56.432  5963  5979 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 03:36:56.435  3166  3180 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 03:36:56.436  5749  5749 D BluetoothInputDevice: Proxy object connected
09-15 03:36:56.437  5749  5749 D HidProfile: Bluetooth service connected
,09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:56.437  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:36:56.437  5749  5762 D BluetoothMap: onBluetoothStateChange: up=true
09-15 03:36:56.439  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:36:56.441  5749  5760 D BluetoothPan: onBluetoothStateChange on: true
,09-15 03:36:56.441  5963  5963 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 03:36:56.442  5963  5963 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 03:36:56.443   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:56.443  3166  3179 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:56.443  5963  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:36:56.443  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:36:56.444  3166  3769 D BluetoothMap: onBluetoothStateChange: up=true
09-15 03:36:56.446  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:36:56.446  3166  3770 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 03:36:56.447  5963  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:56.448  5749  5957 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 03:36:56.449  5963  5963 D ObexServerSockets: Succeed to create listening sockets 
09-15 03:36:56.449  5963  5963 D ObexServerSockets0: startAccept()
09-15 03:36:56.449  5963  5963 D ObexServerSockets0: prepareForNewConnect()
09-15 03:36:56.450  3532  3875 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:56.451  5749  5762 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 03:36:56.451  5963  5963 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 03:36:56.451  5963  5963 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 03:36:56.452  5963  6001 D ObexServerSockets0: Accepting socket connection...
09-15 03:36:56.452  5963  6002 D ObexServerSockets0: Accepting socket connection...
09-15 03:36:56.453  3166  3166 D BluetoothMap: Proxy object connected
09-15 03:36:56.453  3166  3166 D MapProfile: Bluetooth service connected
09-15 03:36:56.453  3166  3179 D BluetoothPan: onBluetoothStateChange on: true
09-15 03:36:56.453  3166  3166 D BluetoothMap: getConnectedDevices()
09-15 03:36:56.456  3166  3769 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 03:36:56.456  3166  3166 D BluetoothA2dp: Proxy object connected
,09-15 03:36:56.457   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 03:36:56.457   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 03:36:56.458   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 03:36:56.458  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 03:36:56.458  3166  3166 D PanProfile: Bluetooth service connected
09-15 03:36:56.458   925   925 D BluetoothA2dp: Proxy object connected
09-15 03:36:56.458  3166  3166 D BluetoothInputDevice: Proxy object connected
09-15 03:36:56.458  5749  5760 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 03:36:56.458  3166  3166 D HidProfile: Bluetooth service connected
,09-15 03:36:56.460  5749  5749 D BluetoothMap: Proxy object connected
09-15 03:36:56.460  5749  5749 D MapProfile: Bluetooth service connected
09-15 03:36:56.460  5749  5749 D BluetoothMap: getConnectedDevices()
09-15 03:36:56.460   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 03:36:56.461  5963  5963 D BluetoothMapService: onReceive
09-15 03:36:56.461  5963  5963 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 03:36:56.461  5963  5963 D BluetoothMapService: STATE_ON
09-15 03:36:56.462  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:56.464  5749  5749 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 03:36:56.465  5749  5749 D PanProfile: Bluetooth service connected
09-15 03:36:56.465  5749  5749 D BluetoothA2dp: Proxy object connected
09-15 03:36:56.465  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:36:56.466  5963  6004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:36:56.467  5963  6004 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 03:36:56.467  5963  6004 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 03:36:56.472  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 03:36:56.479  3614  3614 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 03:36:56.482  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-15 03:36:56.486  3166  3166 D BluetoothPbap: Proxy object connected
,09-15 03:36:56.486  3166  3166 D PbapServerProfile: Bluetooth service connected
09-15 03:36:56.486  5963  5963 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 03:36:56.486  5963  5963 D ObexServerSockets0: prepareForNewConnect()
,09-15 03:36:56.489  5749  5749 D BluetoothPbap: Proxy object connected
09-15 03:36:56.489  5749  5749 D PbapServerProfile: Bluetooth service connected
,09-15 03:36:56.494  5963  6008 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:56.508  5963  6012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:36:56.509  5963  6012 I BtOppRfcommListener: Accept thread started.
,09-15 03:36:56.545   925   925 D BluetoothHeadset: Proxy object connected
,09-15 03:36:56.545   925   925 D BluetoothHeadset: Proxy object connected
09-15 03:36:56.545  3532  3549 D BluetoothHeadset: Proxy object connected
09-15 03:36:56.545  3166  3179 D BluetoothHeadset: Proxy object connected
09-15 03:36:56.545  3166  3166 D HeadsetProfile: Bluetooth service connected
09-15 03:36:56.545   925   925 D BluetoothHeadset: Proxy object connected
09-15 03:36:56.546  5749  5762 D BluetoothHeadset: Proxy object connected
09-15 03:36:56.546  5749  5749 D HeadsetProfile: Bluetooth service connected
,09-15 03:36:56.550  3532  3876 D BluetoothHeadset: Proxy object connected
,09-15 03:36:56.557   925   942 D BluetoothHeadset: Proxy object connected
09-15 03:36:56.557   925   942 D BluetoothHeadset: Proxy object connected
,09-15 03:36:56.559  5749  5957 D BluetoothHeadset: Proxy object connected
,09-15 03:36:56.559  5749  5749 D HeadsetProfile: Bluetooth service connected
,09-15 03:36:57.147   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:36:57.147   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:36:58.060  3614  3614 I ConfigService: onDestroy
,09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:37:00.363  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:37:00.369  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:37:00.370  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:37:00.370  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f5cb6d removed from the list
09-15 03:37:00.370  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:00.370  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:37:00.370  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:00.372  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 03:37:00.373  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f103a2 added. We now have 4 listener(s)
09-15 03:37:00.373  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 03:37:00.376   925  3178 D WifiService: setWifiEnabled: false pid=5677, uid=10077
,09-15 03:37:00.376   925  3178 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 03:37:05.382  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:05.383   925  3178 D WifiService: setWifiEnabled: true pid=5677, uid=10077
09-15 03:37:05.384   925  3178 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 03:37:05.388   506   919 D SoftapController: Softap fwReload - Ok
09-15 03:37:05.390   506   919 D CommandListener: Setting iface cfg
09-15 03:37:05.390   506   919 D CommandListener: Trying to bring down wlan0
,09-15 03:37:05.391   506   919 D CommandListener: Clearing all IP addresses on wlan0
,09-15 03:37:05.393   925  3001 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 03:37:06.054   925  3001 D wifi    : set interface wlan0 flags (UP)
,09-15 03:37:06.059   925  3001 I WifiHAL : Initializing wifi
,09-15 03:37:06.059   925  3001 I WifiHAL : Creating socket
,09-15 03:37:06.064   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 03:37:06.066   925  3001 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-15 03:37:06.066   925  3001 D wifi    : Did set static halHandle = 0x7f6602f0e0
09-15 03:37:06.066   925  3001 D wifi    : halHandle = 0x7f6602f0e0, mVM = 0x7f81f8d140, mCls = 0x10181e
,09-15 03:37:06.066   925  3001 D wifi    : array field set
09-15 03:37:06.066   925  3001 I WifiNative-HAL: interface[0] = wlan0
,09-15 03:37:06.071   925  6022 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547172315360
09-15 03:37:06.071   925  6022 D wifi    : waitForHalEvents called, vm = 0x7f81f8d140, obj = 0x10181e, env = 0x7f68f89040
,09-15 03:37:06.073   925  3001 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-15 03:37:06.075   925  3001 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-15 03:37:06.079  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:06.081  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:06.118  6023  6023 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 03:37:06.140  6023  6023 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 03:37:06.168  6023  6023 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 03:37:06.168  6023  6023 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 03:37:07.089   925  3001 D WifiConfigStore: Loading config and enabling all networks 
,09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:37:07.098  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:37:07.102  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:37:07.108  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:37:07.111   925  3001 D WifiConfigStore: loaded 0 passpoint configs
09-15 03:37:07.111   925  3001 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 03:37:07.112   925  3001 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 03:37:07.113   925  3001 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-15 03:37:07.113  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 03:37:07.115   925  3001 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 03:37:07.115   925  3001 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-15 03:37:07.115   925  3001 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 03:37:07.115   925  3001 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 03:37:07.119   925  3001 D WifiNative-HAL: Setting external_sim to 1
09-15 03:37:07.119  4314  4314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 03:37:07.119   925  3001 D wifi    : setting dfs flag to true, 0x7f677a69a0
,09-15 03:37:07.120   925  3001 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 03:37:07.120   925  3001 D wifi    : setting scan oui 0x7f677a69a0
09-15 03:37:07.120   925  3001 D WifiHAL : Sending mac address OUI
,09-15 03:37:07.125   925  3001 E native  : do suspend false
,09-15 03:37:07.136   925  3001 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 03:37:07.136   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 03:37:07.137   925   925 D RttService: SCAN_AVAILABLE : 3
09-15 03:37:07.137   925  3107 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 03:37:07.138   506   919 D CommandListener: Setting iface cfg
,09-15 03:37:07.143   925  3000 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
09-15 03:37:07.143   925  3000 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 03:37:07.155   925  3000 D WifiNative-HAL: p2pGetDeviceAddress
09-15 03:37:07.155   925  3000 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 03:37:07.161   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=455074 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,09-15 03:37:10.303  6023  6023 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:37:10.309  6023  6023 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:37:10.315  6023  6023 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:37:10.358   925  3001 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-15 03:37:10.359   925  3001 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-15 03:37:10.359   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:37:10.370   925  3001 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 03:37:10.391  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 03:37:10.393  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 03:37:10.394  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:37:10.394  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f103a2 removed from the list
09-15 03:37:10.394  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:10.394  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:10.394  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:10.398  5677  6034 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-15 03:37:10.398  5677  6034 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 03:37:10.404   925  3001 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-15 03:37:10.406  6023  6023 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-15 03:37:10.844  6023  6023 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-15 03:37:10.875  6023  6023 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-15 03:37:10.876  6023  6023 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-15 03:37:10.887   925  3001 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 03:37:10.888   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 03:37:10.888   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-15 03:37:10.905   925  3001 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 03:37:10.917   506   919 D CommandListener: Setting iface cfg
,09-15 03:37:10.923   925  3001 D WifiStateMachine: Start Dhcp Watchdog 3
,09-15 03:37:10.933   925  6038 D DhcpClient: Receive thread started
,09-15 03:37:10.936   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-15 03:37:10.936   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-15 03:37:10.936   925  3003 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-15 03:37:11.018   925  3001 E native  : do suspend false
,09-15 03:37:11.030   925  6037 D DhcpClient: Broadcasting DHCPDISCOVER
,09-15 03:37:11.044   925  6038 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-15 03:37:11.044   925  6037 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-15 03:37:11.046   925  6037 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-15 03:37:11.058   925  6038 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-15 03:37:11.059   925  6037 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-15 03:37:11.061   506   919 D CommandListener: Setting iface cfg
09-15 03:37:11.065   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-15 03:37:11.068   925  6037 D DhcpClient: Scheduling renewal in 86399s
,09-15 03:37:11.079   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-15 03:37:11.080   925  3001 D WifiConfigStore: No blacklist allowed without epno enabled
,09-15 03:37:11.082   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-15 03:37:11.084   925  3003 D ConnectivityService: Adding iface wlan0 to network 102
,09-15 03:37:11.087   925  3001 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-15 03:37:11.144   925  3003 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-15 03:37:11.144   925  3003 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-15 03:37:11.147   925  3003 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-15 03:37:11.150   925  3003 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-15 03:37:11.151   925  3003 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-15 03:37:11.158   925  3003 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-15 03:37:11.163   925  3003 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-15 03:37:11.164   925  3003 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-15 03:37:11.164   925  3003 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-15 03:37:11.164   925  3001 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-15 03:37:11.164   925  3003 D ConnectivityService:    accepting network in place of null
09-15 03:37:11.164   925  3001 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 03:37:11.164   925  3003 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 03:37:11.179   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=459091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:37:11.189   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:37:11.209   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 03:37:11.212   925  3003 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-15 03:37:11.212  3491  3653 W QCNEJ   : |CORE| network available: 102
09-15 03:37:11.212   925  3003 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-15 03:37:11.213   925  3003 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-15 03:37:11.216   925   942 D Tethering: MasterInitialState.processMessage what=3
,09-15 03:37:11.219  3491  3653 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-15 03:37:11.220  3491  3653 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-15 03:37:11.221  3491  3653 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:11.222  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:37:11.225  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:11.228  4753  4753 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:11.229  5677  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 03:37:11.230  4819  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 03:37:11.230  4819  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 03:37:11.230  5677  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:11.230  4819  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-15 03:37:11.231  4819  4848 E SarControlService: no key has been found,reset the power
09-15 03:37:11.233  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-15 03:37:11.234  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 03:37:11.234  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 03:37:11.235  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:37:11.235  4850  4850 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 03:37:11.235  4819  4863 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 03:37:11.235  4819  4863 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 03:37:11.236  4819  4863 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 03:37:11.237  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 03:37:11.238  4850  4850 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-15 03:37:11.244  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000f003000000000000ffffffff]
,09-15 03:37:11.244  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 03:37:11.244  4850  4887 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,09-15 03:37:11.244  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:37:11.245  4819  4831 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 03:37:11.245  3946  3946 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-15 03:37:11.247  4850  4887 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c952b08 HexData = [00000000f103000000000000ffffffff]
,09-15 03:37:11.247  4850  4887 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-15 03:37:11.249  4850  4887 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-15 03:37:11.250  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 03:37:11.250  4819  4830 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 03:37:11.253   925  6035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-15 03:37:11.256  3946  5304 I iu.UploadsManager: num queued entries: 0
09-15 03:37:11.257  3946  5304 I iu.UploadsManager: num updated entries: 0
,09-15 03:37:11.260  3946  3946 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 03:37:11.262  3946  3946 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-15 03:37:11.263  5826  5826 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 03:37:11.267  5826  5826 D SprintDMHelper: simOperator: 
09-15 03:37:11.267  5826  5826 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 03:37:11.279  3946  5304 I iu.SyncManager: NEXT; no task
,09-15 03:37:11.300   925  6035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 15 Sep 2016 07:37:11 GMT], X-Android-Received-Millis=[1473925031299], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473925031276]}
,09-15 03:37:11.300   925  3003 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 03:37:11.301   925  3003 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-15 03:37:11.301   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-15 03:37:11.302   925  3003 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-15 03:37:11.379  4314  6051 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-15 03:37:12.362   925  3001 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-15 03:37:12.374   925  3003 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-15 03:37:12.381  3491  3653 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-15 03:37:12.382  3491  3653 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-15 03:37:13.409  5677  6034 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-15 03:37:13.409  5677  6059 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-15 03:37:13.410  5677  6059 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-15 03:37:13.410  5677  6034 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 03:37:13.412  5677  6059 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 03:37:13.412  5677  6034 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 03:37:13.414  5677  6059 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 03:37:13.414  5677  6034 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 03:37:13.417  5677  6061 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: IncomingSocketThread/Sender)
,09-15 03:37:13.418  5677  6059 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-15 03:37:13.418  5677  6034 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 03:37:13.419  5677  6062 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender)
,09-15 03:37:13.423  5677  6064 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Receiver)
,09-15 03:37:13.423  5677  6063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
09-15 03:37:13.424  5677  6063 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
,09-15 03:37:13.425  5677  6063 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 03:37:13.425  5677  6063 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-15 03:37:13.425  5677  6064 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: IncomingSocketThread/Receiver)
,09-15 03:37:13.426  5677  6064 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-15 03:37:13.426  5677  6064 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-15 03:37:16.407  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-15 03:37:16.409  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-15 03:37:16.416  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ce3814c Bundle[{}]
,09-15 03:37:16.417  5677  5723 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 03:37:16.418  5677  5723 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-15 03:37:16.418  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-15 03:37:16.419  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 03:37:16.419  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-15 03:37:16.420  5677  5723 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-15 03:37:16.425  5677  5723 I System.out: Running OutgoingSocketThread
,09-15 03:37:16.426  5677  6065 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-15 03:37:16.426  5677  6065 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 03:37:17.148   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:18.149   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:19.150   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:19.169   925  3003 D ConnectivityService: handlePromptUnvalidated 102
,09-15 03:37:19.438  5677  6066 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-15 03:37:19.438  5677  6065 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-15 03:37:19.438  5677  6065 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 03:37:19.438  5677  6066 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-15 03:37:19.438  5677  6066 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 03:37:19.438  5677  6065 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 03:37:19.441  5677  6065 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 03:37:19.441  5677  6066 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 03:37:19.443  5677  6069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
09-15 03:37:19.445  5677  6065 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 03:37:19.449  5677  6066 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-15 03:37:19.449  5677  6068 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender)
,09-15 03:37:19.452  5677  6070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Receiver)
,09-15 03:37:19.453  5677  6071 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Receiver)
09-15 03:37:19.454  5677  6070 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: OutgoingSocketThread/Receiver)
09-15 03:37:19.454  5677  6070 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 03:37:19.454  5677  6070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-15 03:37:19.455  5677  6071 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: IncomingSocketThread/Receiver)
09-15 03:37:19.455  5677  6071 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-15 03:37:19.456  5677  6071 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-15 03:37:20.151   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:21.153   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:22.154   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:37:22.154   925  3001 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-15 03:37:22.436  5677  5723 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-15 03:37:22.437  5677  5723 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-15 03:37:22.437  5677  5723 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-15 03:37:22.443  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:37:22.443  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e061833 added. We now have 3 listener(s)
,09-15 03:37:22.448  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:37:22.448  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:22.448  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:37:22.449  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 03:37:22.449  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6a07f0 added. We now have 4 listener(s)
09-15 03:37:22.449  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 03:37:22.451  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:37:22.458  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:22.463  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:22.466  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:22.466  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:37:22.467  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:22.467  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:22.467  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:37:22.467  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:22.467  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:22.468  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:22.468  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 03:37:22.468  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e061833 removed from the list
09-15 03:37:22.468  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:22.468  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6a07f0 removed from the list
,09-15 03:37:22.470  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:37:22.471  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:22.471  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:22.472  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:37:22.472  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:22.474  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:22.474  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:22.474  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:22.474  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6a07f0 not in the list
09-15 03:37:22.474  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:22.474  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:22.475  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:22.476  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:22.476  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:22.476  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6a07f0 not in the list
09-15 03:37:22.476  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:22.476  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:22.476  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:22.476  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:22.476  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e061833 not in the list
09-15 03:37:22.477  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:37:22.477  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bffb7ee added. We now have 3 listener(s)
09-15 03:37:22.479  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:37:22.480  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:22.480  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:37:22.480  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:37:22.480  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600048f added. We now have 4 listener(s)
09-15 03:37:22.480  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:37:22.481  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:37:22.484  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:22.489  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:22.491  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:22.492  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:37:22.492  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 03:37:22.492  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 03:37:22.492  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 03:37:22.492  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:22.492  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 03:37:22.496  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:37:22.497  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:37:22.498  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 03:37:22.499  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:22.501  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:37:22.502  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:22.502  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:37:22.506  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 03:37:22.506  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:37:22.506  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 03:37:22.507  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:22.510  5963  5973 D BtGatt.GattService: registerClient() - UUID=2c4df7dd-2a80-48f1-8858-5a3b89c60fb6
09-15 03:37:22.511  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=2c4df7dd-2a80-48f1-8858-5a3b89c60fb6, clientIf=5
09-15 03:37:22.512  5677  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 03:37:22.513  5963  5974 D BtGatt.GattService: start scan with filters
,09-15 03:37:22.517  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 03:37:22.517  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:37:22.517  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-15 03:37:22.517  5963  5982 D BtGatt.ScanManager: handling starting scan
09-15 03:37:22.517  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 03:37:22.519  5963  5982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e4354d9
09-15 03:37:22.520  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:37:22.520  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:37:22.520  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:37:22.521  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 03:37:22.524  5677  5723 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 03:37:22.524  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:22.524  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:37:22.525  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:22.525  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-15 03:37:22.525  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:37:22.525  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:37:22.525  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:37:22.525  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:37:22.525  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:37:22.525  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 03:37:22.526  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:22.527  5963  5974 D BtGatt.GattService: stopScan() - queue size =1
09-15 03:37:22.527  5963  5979 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:37:22.527  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:22.527  5963  6003 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:37:22.528  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:37:22.528  5963  5982 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 03:37:22.528  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 03:37:22.528  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 03:37:22.528  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:37:22.528  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:37:22.529  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:22.529  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:37:22.529  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 03:37:22.529  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:37:22.530  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:22.531  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 03:37:22.531  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:22.531  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:37:22.534  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 03:37:22.534  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:22.535  5963  5982 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:37:22.535  5963  5982 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:37:22.545  5963  5979 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 03:37:22.545  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:22.551  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:37:22.551  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:22.558  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 03:37:22.558  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:22.559  5963  5982 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:37:22.563  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 03:37:22.564  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:22.564  5963  5982 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:37:22.569  5963  5979 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 03:37:22.569  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:23.032  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-15 03:37:23.033  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:37:23.033  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:37:25.531  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:25.532  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:37:25.532  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:37:25.532  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:25.532  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:37:25.533  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:25.533  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 03:37:25.533  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bffb7ee removed from the list
09-15 03:37:25.533  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:37:25.533  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600048f removed from the list
09-15 03:37:25.534  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:25.534  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:25.535  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:25.535  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:25.538  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:25.538  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:25.539  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:25.539  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600048f not in the list
09-15 03:37:25.539  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:25.539  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:25.541  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 03:37:25.542  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:25.542  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:25.542  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@600048f not in the list
09-15 03:37:25.542  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:25.542  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:37:25.542  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:25.543  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bffb7ee not in the list
09-15 03:37:25.544  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:37:25.544  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2e508 added. We now have 3 listener(s)
09-15 03:37:25.548  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:37:25.549  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:25.549  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:37:25.549  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:37:25.549  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19424a1 added. We now have 4 listener(s)
09-15 03:37:25.549  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:37:25.551  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:37:25.554  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:25.558  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:25.560  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:25.561  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 03:37:25.561  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 03:37:25.562  5677  5723 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-15 03:37:25.562  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-15 03:37:25.562  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 03:37:25.562  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 03:37:25.562  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 03:37:25.562  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:25.564  5973  5973 W Binder_1: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[37007]" dev="sockfs" ino=37007 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 03:37:25.563  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 03:37:25.564  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 03:37:25.564  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:37:25.564  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 03:37:25.565  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 03:37:25.565  5677  6072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:37:25.565  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 03:37:25.566  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:25.564  5973  5973 W Binder_1: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[37007]" dev="sockfs" ino=37007 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:37:25.566  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 03:37:25.567  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:37:25.568  5677  6072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-15 03:37:25.568  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-15 03:37:25.573  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 03:37:25.581  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 03:37:25.585  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:37:25.586  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:25.586  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:37:25.588  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-15 03:37:25.589  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:37:25.589  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-15 03:37:25.590  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:37:25.590  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:37:25.590  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 03:37:25.591  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:37:25.595  5963  5973 D BtGatt.GattService: registerClient() - UUID=ab4da21c-8bbb-4bcf-9063-81d0e90363fe
,09-15 03:37:25.595  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=ab4da21c-8bbb-4bcf-9063-81d0e90363fe, clientIf=5
,09-15 03:37:25.595  5677  5688 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-15 03:37:25.597  5963  5981 D BtGatt.AdvertiseManager: message : 0
,09-15 03:37:25.599  5963  5981 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 03:37:25.608  5963  5979 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 03:37:25.613  5963  5979 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 03:37:25.614  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-15 03:37:25.615  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:37:25.616  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:37:25.617  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 03:37:25.617  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 03:37:25.617  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 03:37:25.617  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 03:37:25.617  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 03:37:25.617  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-15 03:37:25.620  5677  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 03:37:25.620  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 03:37:25.620  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 03:37:25.621  5677  5723 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:37:26.058   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-15 03:37:26.121  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 03:37:27.155   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:28.156   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:28.622  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:37:28.622  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-15 03:37:28.623  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:37:28.623  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 03:37:28.623  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-15 03:37:28.623  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 03:37:28.624  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 03:37:28.624  5677  6072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 03:37:28.624  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 03:37:28.624  5677  6072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 03:37:28.624  5677  6072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 03:37:28.624  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:37:28.624  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 03:37:28.624  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 03:37:28.624  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:37:28.624  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:37:28.625  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 03:37:28.628  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:28.628  5677  5723 D BluetoothLeScanner: could not find callback wrapper
09-15 03:37:28.628  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:37:28.629  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-15 03:37:28.631  5963  5981 D BtGatt.AdvertiseManager: message : 1
,09-15 03:37:28.632  5963  5981 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 03:37:28.645  5963  5979 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 03:37:28.645  5963  5979 D BtGatt.GattService: Client app is not null!
09-15 03:37:28.647  5963  5974 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 03:37:28.648  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:37:28.648  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 03:37:28.648  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 03:37:28.648  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 03:37:28.649  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 03:37:28.651  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:28.651  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 03:37:28.651  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:37:28.652  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:28.654  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:28.654  5677  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 03:37:28.654  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:28.654  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:28.655  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 03:37:28.655  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:28.655  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2e508 removed from the list
09-15 03:37:28.655  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:37:28.655  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:28.655  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19424a1 removed from the list
09-15 03:37:28.655  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:28.655  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:28.655  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:28.656  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:28.656  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:28.659  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:28.659  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:28.659  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 03:37:28.660  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19424a1 not in the list
09-15 03:37:28.660  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:28.660  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:28.662  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 03:37:28.662  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:28.662  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:28.662  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19424a1 not in the list
09-15 03:37:28.662  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:28.662  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:37:28.662  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:28.663  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2e508 not in the list
09-15 03:37:28.664  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:37:28.664  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c859952 added. We now have 3 listener(s)
09-15 03:37:28.666  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:37:28.667  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:28.667  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 03:37:28.667  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:37:28.667  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1057423 added. We now have 4 listener(s)
09-15 03:37:28.667  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 03:37:28.668  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:37:28.672  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:28.679  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:28.683  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:28.683  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 03:37:28.684  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:37:28.684  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 03:37:28.684  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 03:37:28.684  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:28.684  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 03:37:28.688  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:28.690  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 03:37:28.690  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 03:37:28.692  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:28.696  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:37:28.697  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:28.697  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 03:37:28.702  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 03:37:28.702  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:37:28.702  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 03:37:28.703  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:37:28.706  5963  5990 D BtGatt.GattService: registerClient() - UUID=88bfe54f-87fa-42d4-8253-6c7ef3149e03
09-15 03:37:28.706  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=88bfe54f-87fa-42d4-8253-6c7ef3149e03, clientIf=5
,09-15 03:37:28.707  5677  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 03:37:28.707  5963  5974 D BtGatt.GattService: start scan with filters
09-15 03:37:28.710  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 03:37:28.710  5963  5982 D BtGatt.ScanManager: handling starting scan
09-15 03:37:28.710  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:37:28.710  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:37:28.710  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 03:37:28.717  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:37:28.717  5963  5979 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:37:28.717  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:28.717  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:37:28.717  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:37:28.718  5963  5982 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:37:28.719  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:37:28.725  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:37:28.725  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:28.725  5963  5982 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:37:28.725  5963  5982 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:37:28.737  5963  5979 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 03:37:28.737  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:28.743  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 03:37:28.743  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:29.156  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:37:29.157   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:29.218  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 03:37:29.218  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:37:29.218  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:37:30.158   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:31.159   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:31.729  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:37:31.730  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:37:31.730  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:37:31.730  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.730  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 03:37:31.730  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-15 03:37:31.730  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:37:31.731  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:37:31.731  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:37:31.731  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:37:31.731  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 03:37:31.733  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:31.734  5963  6003 D BtGatt.GattService: stopScan() - queue size =1
09-15 03:37:31.736  5963  5973 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 03:37:31.737  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:37:31.738  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 03:37:31.738  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 03:37:31.738  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:37:31.738  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:37:31.741  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:31.741  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:37:31.742  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 03:37:31.742  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:37:31.744  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 03:37:31.744  5963  5963 D BtGatt.ScanManager: awakened up at time 479657
09-15 03:37:31.748  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:31.748  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:31.748  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.748  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:31.748  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:31.748  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:31.748  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 03:37:31.748  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c859952 removed from the list
09-15 03:37:31.748  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:31.748  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1057423 removed from the list
09-15 03:37:31.749  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:31.749  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:31.752  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.753  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:31.755  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 03:37:31.755  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:31.755  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:31.755  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1057423 not in the list
09-15 03:37:31.755  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.755  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:31.756  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 03:37:31.756  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:31.757  5963  5982 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:37:31.757  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:31.757  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 03:37:31.757  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:31.757  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1057423 not in the list
09-15 03:37:31.758  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:31.758  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.758  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:31.758  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c859952 not in the list
09-15 03:37:31.759  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 03:37:31.759  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa41b4c added. We now have 3 listener(s)
09-15 03:37:31.762  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:37:31.762  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:31.762  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:37:31.762  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 03:37:31.762  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8f795 added. We now have 4 listener(s)
09-15 03:37:31.762  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 03:37:31.765  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:37:31.766  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 03:37:31.766  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:31.766  5963  5982 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:37:31.769  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:31.775  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:31.778  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:31.778  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 03:37:31.779  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:37:31.779  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:31.779  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:37:31.779  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:31.779  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.779  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 03:37:31.779  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 03:37:31.779  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa41b4c removed from the list
09-15 03:37:31.779  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:31.780  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8f795 removed from the list
,09-15 03:37:31.784  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:37:31.784  5677  5723 D io.jxcore.node.ConnectivityMonitor: stop
09-15 03:37:31.784  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:31.784  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 03:37:31.785  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 03:37:31.787  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 03:37:31.787  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:31.787  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:31.787  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:31.787  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8f795 not in the list
09-15 03:37:31.787  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.788  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:31.789  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:37:31.789  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:37:31.789  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 03:37:31.789  5677  5723 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8f795 not in the list
09-15 03:37:31.789  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 03:37:31.789  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:31.789  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 03:37:31.789  5677  5723 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa41b4c not in the list
09-15 03:37:31.790  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-15 03:37:31.791  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 03:37:31.791  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-15 03:37:31.791  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:37:31.791  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:37:31.791  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:31.792  5963  5979 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-15 03:37:31.792  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:31.792  5963  5979 D BtGatt.GattService: current time is 479705700904
09-15 03:37:31.793  5963  5979 D BtGatt.GattService: Batch record : [50, -35, 86, -77, -92, -11, 1, 0, -92, 58, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 35, 102, 3, 3, 2, -37, 21, 61, 125, -63, 61, 28, 6, 8, 116, 105, 115, 54, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 37, -47, 14, -113, 116, -46, 1, -128, -73, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -85, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -72, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -69, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -71, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 03:37:31.794  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 35, 102, 3, 3, 2, -37, 21, 61, 125, -63, 61, 6, 8, 116, 105, 115, 54, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-15 03:37:31.795  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-15 03:37:31.795  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 03:37:31.795  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-15 03:37:31.796  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 03:37:31.796  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-15 03:37:32.106   925  3003 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-15 03:37:32.159   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:37:32.249  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:37:33.804  5677  6074 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-15 03:37:34.926  6023  6023 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-15 03:37:35.804  5677  5723 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,09-15 03:37:35.804  5677  5723 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-15 03:37:35.809  5677  6075 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-15 03:37:35.809  5677  6075 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
09-15 03:37:35.809  5677  6075 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-15 03:37:35.816  5677  5723 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 03:37:35.822  5677  6076 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-15 03:37:35.822  5677  6076 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-15 03:37:35.822  5677  6076 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-15 03:37:35.826  5677  5723 I jxcore-log: Total number of executed tests:  82
09-15 03:37:35.826  5677  5723 I jxcore-log: 
,09-15 03:37:35.827  5677  5723 I jxcore-log: Number of passed tests:  82
09-15 03:37:35.827  5677  5723 I jxcore-log: 
09-15 03:37:35.827  5677  5723 I jxcore-log: Number of failed tests:  0
09-15 03:37:35.827  5677  5723 I jxcore-log: 
09-15 03:37:35.827  5677  5723 I jxcore-log: Number of ignored tests:  0
09-15 03:37:35.827  5677  5723 I jxcore-log: 
09-15 03:37:35.827  5677  5723 I jxcore-log: Total duration:  100920
09-15 03:37:35.827  5677  5723 I jxcore-log: 
,09-15 03:37:35.831  5677  5723 I jxcore-log: Unit Test app is loaded
09-15 03:37:35.831  5677  5723 I jxcore-log: 
,09-15 03:37:35.835  5677  6074 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-15 03:37:35.840  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.840  5677  5723 I jxcore-log: 
,09-15 03:37:35.846  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.846  5677  5723 I jxcore-log: 
,09-15 03:37:35.847  5677  5677 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 03:37:35.848  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.848  5677  5723 I jxcore-log: 
,09-15 03:37:35.849  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.849  5677  5723 I jxcore-log: 
09-15 03:37:35.851  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 03:37:35.851  5677  5723 I jxcore-log: 
09-15 03:37:35.852  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:35.852  5677  5723 I jxcore-log: 
,09-15 03:37:35.855  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.855  5677  5723 I jxcore-log: 
,09-15 03:37:35.858  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.858  5677  5723 I jxcore-log: 
,09-15 03:37:35.859  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 03:37:35.859  5677  5723 I jxcore-log: 
,09-15 03:37:35.861  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:35.861  5677  5723 I jxcore-log: 
,09-15 03:37:35.862  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:35.862  5677  5723 I jxcore-log: 
09-15 03:37:35.863  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.863  5677  5723 I jxcore-log: 
,09-15 03:37:35.864  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.864  5677  5723 I jxcore-log: 
,09-15 03:37:35.865  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.865  5677  5723 I jxcore-log: 
09-15 03:37:35.866  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.866  5677  5723 I jxcore-log: 
,09-15 03:37:35.867  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.867  5677  5723 I jxcore-log: 
,09-15 03:37:35.869  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.869  5677  5723 I jxcore-log: 
09-15 03:37:35.870  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.870  5677  5723 I jxcore-log: 
,09-15 03:37:35.871  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.871  5677  5723 I jxcore-log: 
09-15 03:37:35.872  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.872  5677  5723 I jxcore-log: 
,09-15 03:37:35.873  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.873  5677  5723 I jxcore-log: 
,09-15 03:37:35.874  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.874  5677  5723 I jxcore-log: 
09-15 03:37:35.875  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.875  5677  5723 I jxcore-log: 
,09-15 03:37:35.876  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.876  5677  5723 I jxcore-log: 
09-15 03:37:35.877  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.877  5677  5723 I jxcore-log: 
,09-15 03:37:35.878  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.878  5677  5723 I jxcore-log: 
,09-15 03:37:35.879  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.879  5677  5723 I jxcore-log: 
09-15 03:37:35.880  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.880  5677  5723 I jxcore-log: 
,09-15 03:37:35.881  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.881  5677  5723 I jxcore-log: 
09-15 03:37:35.882  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.882  5677  5723 I jxcore-log: 
,09-15 03:37:35.883  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.883  5677  5723 I jxcore-log: 
09-15 03:37:35.883  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.883  5677  5723 I jxcore-log: 
09-15 03:37:35.884  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.884  5677  5723 I jxcore-log: 
,09-15 03:37:35.885  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.885  5677  5723 I jxcore-log: 
09-15 03:37:35.886  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.886  5677  5723 I jxcore-log: 
,09-15 03:37:35.886  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.886  5677  5723 I jxcore-log: 
09-15 03:37:35.887  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.887  5677  5723 I jxcore-log: 
,09-15 03:37:35.888  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 03:37:35.888  5677  5723 I jxcore-log: 
09-15 03:37:35.888  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.888  5677  5723 I jxcore-log: 
,09-15 03:37:35.889  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.889  5677  5723 I jxcore-log: 
09-15 03:37:35.890  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 03:37:35.890  5677  5723 I jxcore-log: 
,09-15 03:37:35.891  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.891  5677  5723 I jxcore-log: 
09-15 03:37:35.891  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.891  5677  5723 I jxcore-log: 
,09-15 03:37:35.892  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.892  5677  5723 I jxcore-log: 
09-15 03:37:35.893  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.893  5677  5723 I jxcore-log: 
,09-15 03:37:35.894  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:35.894  5677  5723 I jxcore-log: 
09-15 03:37:35.894  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.894  5677  5723 I jxcore-log: 
,09-15 03:37:35.895  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 03:37:35.895  5677  5723 I jxcore-log: 
09-15 03:37:35.896  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.896  5677  5723 I jxcore-log: 
,09-15 03:37:35.897  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:35.897  5677  5723 I jxcore-log: 
09-15 03:37:35.898  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 03:37:35.898  5677  5723 I jxcore-log: 
,09-15 03:37:35.898  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:35.898  5677  5723 I jxcore-log: 
09-15 03:37:35.898  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:35.898  5677  5723 I jxcore-log: 
,09-15 03:37:35.902  5677  5723 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-15 03:37:35.902  5677  5723 I jxcore-log:   bluetooth: 'on',
09-15 03:37:35.902  5677  5723 I jxcore-log:   wifi: 'on',
09-15 03:37:35.902  5677  5723 I jxcore-log:   cellular: 'doNotCare',
09-15 03:37:35.902  5677  5723 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-15 03:37:35.902  5677  5723 I jxcore-log: 
,09-15 03:37:35.906  5677  5723 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-15 03:37:35.906  5677  5723 I jxcore-log:   bluetooth: 'on',
09-15 03:37:35.906  5677  5723 I jxcore-log:   wifi: 'on',
09-15 03:37:35.906  5677  5723 I jxcore-log:   cellular: 'doNotCare',
09-15 03:37:35.906  5677  5723 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-15 03:37:35.906  5677  5723 I jxcore-log: 
,09-15 03:37:35.906  5677  5723 I jxcore-log: My device name is: Huawei-Nexus 6P
09-15 03:37:35.906  5677  5723 I jxcore-log: 
09-15 03:37:35.907  5677  5723 I jxcore-log: Running for WIFI network type
09-15 03:37:35.907  5677  5723 I jxcore-log: 
,09-15 03:37:37.659  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-15 03:37:37.659  5677  5723 I jxcore-log: 
,09-15 03:37:37.966  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-15 03:37:37.966  5677  5723 I jxcore-log: 
,09-15 03:37:37.992  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-15 03:37:37.992  5677  5723 I jxcore-log: 
,09-15 03:37:37.996  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-15 03:37:37.996  5677  5723 I jxcore-log: 
,09-15 03:37:38.000  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-15 03:37:38.000  5677  5723 I jxcore-log: 
,09-15 03:37:38.039  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-15 03:37:38.039  5677  5723 I jxcore-log: 
,09-15 03:37:38.050  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-15 03:37:38.050  5677  5723 I jxcore-log: 
,09-15 03:37:38.053  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-15 03:37:38.053  5677  5723 I jxcore-log: 
,09-15 03:37:38.566  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-15 03:37:38.566  5677  5723 I jxcore-log: 
,09-15 03:37:38.574  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-15 03:37:38.574  5677  5723 I jxcore-log: 
,09-15 03:37:38.580  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-15 03:37:38.580  5677  5723 I jxcore-log: 
,09-15 03:37:38.730  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-15 03:37:38.730  5677  5723 I jxcore-log: 
,09-15 03:37:39.774  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-15 03:37:39.774  5677  5723 I jxcore-log: 
,09-15 03:37:39.807  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-15 03:37:39.807  5677  5723 I jxcore-log: 
,09-15 03:37:39.812  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-15 03:37:39.812  5677  5723 I jxcore-log: 
,09-15 03:37:39.902  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-15 03:37:39.902  5677  5723 I jxcore-log: 
,09-15 03:37:39.916  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-15 03:37:39.916  5677  5723 I jxcore-log: 
,09-15 03:37:39.920  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-15 03:37:39.920  5677  5723 I jxcore-log: 
,09-15 03:37:39.924  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-15 03:37:39.924  5677  5723 I jxcore-log: 
,09-15 03:37:39.934  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-15 03:37:39.934  5677  5723 I jxcore-log: 
,09-15 03:37:39.998   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=487910, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:37:40.039  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-15 03:37:40.039  5677  5723 I jxcore-log: 
,09-15 03:37:40.056  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-15 03:37:40.056  5677  5723 I jxcore-log: 
,09-15 03:37:40.066  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-15 03:37:40.066  5677  5723 I jxcore-log: 
,09-15 03:37:40.074  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-15 03:37:40.074  5677  5723 I jxcore-log: 
,09-15 03:37:40.084  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-15 03:37:40.084  5677  5723 I jxcore-log: 
,09-15 03:37:40.106  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-15 03:37:40.106  5677  5723 I jxcore-log: 
,09-15 03:37:40.109  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-15 03:37:40.109  5677  5723 I jxcore-log: 
,09-15 03:37:40.128  5677  5723 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-15 03:37:40.128  5677  5723 I jxcore-log: 
,09-15 03:37:40.135  5677  5723 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-15 03:37:40.136  5677  5723 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-15 03:37:40.136  5677  5723 I jxcore-log: 
,09-15 03:37:40.138  5677  5723 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-15 03:37:40.138  5677  5723 I jxcore-log: 
,09-15 03:37:40.138  5677  5723 I jxcore-log: ThaliTape :: Started ThaliTape
09-15 03:37:40.138  5677  5723 I jxcore-log: 
,09-15 03:37:40.142  5677  5723 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-15 03:37:40.142  5677  5723 I jxcore-log: 
,09-15 03:37:40.281  5677  5723 I jxcore-log: ThaliTape :: Connected to the test server
09-15 03:37:40.281  5677  5723 I jxcore-log: 
,09-15 03:37:40.677  5677  5723 I jxcore-log: TAP version 13
09-15 03:37:40.677  5677  5723 I jxcore-log: 
,09-15 03:37:40.681  5677  5723 I jxcore-log: # setup
09-15 03:37:40.681  5677  5723 I jxcore-log: 
,09-15 03:37:41.102  5677  5723 I jxcore-log: # 1. calling createNativeListener directly rejects
09-15 03:37:41.102  5677  5723 I jxcore-log: 
,09-15 03:37:41.148  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:41.148  5677  5723 I jxcore-log: 
,09-15 03:37:41.152  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 42420
09-15 03:37:41.152  5677  5723 I jxcore-log: 
,09-15 03:37:41.158  5677  5723 I jxcore-log: ok 1 Should throw
09-15 03:37:41.158  5677  5723 I jxcore-log: 
,09-15 03:37:41.161  5677  5723 I jxcore-log: # teardown
09-15 03:37:41.161  5677  5723 I jxcore-log: 
,09-15 03:37:41.276  5677  5723 I jxcore-log: # setup
09-15 03:37:41.276  5677  5723 I jxcore-log: 
,09-15 03:37:41.381  5677  5723 I jxcore-log: # 2. emits incomingConnectionState
09-15 03:37:41.381  5677  5723 I jxcore-log: 
,09-15 03:37:41.489  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:41.489  5677  5723 I jxcore-log: 
,09-15 03:37:41.495  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 45653
09-15 03:37:41.495  5677  5723 I jxcore-log: 
,09-15 03:37:41.508  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:41.508  5677  5723 I jxcore-log: 
,09-15 03:37:41.512  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:41.512  5677  5723 I jxcore-log: 
,09-15 03:37:41.525  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:41.525  5677  5723 I jxcore-log: 
,09-15 03:37:41.542  5677  5723 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-15 03:37:41.542  5677  5723 I jxcore-log: 
,09-15 03:37:41.562  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:41.562  5677  5723 I jxcore-log: 
,09-15 03:37:41.563  5677  5723 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-15 03:37:41.563  5677  5723 I jxcore-log: 
,09-15 03:37:41.570  5677  5723 I jxcore-log: # teardown
09-15 03:37:41.570  5677  5723 I jxcore-log: 
,09-15 03:37:41.629  5677  5723 I jxcore-log: # setup
09-15 03:37:41.629  5677  5723 I jxcore-log: 
,09-15 03:37:41.729  5677  5723 I jxcore-log: # 3. emits routerPortConnectionFailed
09-15 03:37:41.729  5677  5723 I jxcore-log: 
,09-15 03:37:41.838  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:41.838  5677  5723 I jxcore-log: 
,09-15 03:37:41.842  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 37479
09-15 03:37:41.842  5677  5723 I jxcore-log: 
,09-15 03:37:41.852  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:41.852  5677  5723 I jxcore-log: 
09-15 03:37:41.854  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:41.854  5677  5723 I jxcore-log: 
,09-15 03:37:41.856  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:41.856  5677  5723 I jxcore-log: 
,09-15 03:37:41.881  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:41.881  5677  5723 I jxcore-log: 
,09-15 03:37:41.884  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:41.884  5677  5723 I jxcore-log: 
,09-15 03:37:41.888  5677  5723 I jxcore-log: DEBUG createNativeListener: 
09-15 03:37:41.888  5677  5723 I jxcore-log: 
,09-15 03:37:41.889  5677  5723 I jxcore-log: ok 4 tried to connect to right port
09-15 03:37:41.889  5677  5723 I jxcore-log: 
09-15 03:37:41.890  5677  5723 I jxcore-log: ok 5 failed due to refused connection
09-15 03:37:41.890  5677  5723 I jxcore-log: 
09-15 03:37:41.890  5677  5723 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-15 03:37:41.890  5677  5723 I jxcore-log: 
,09-15 03:37:41.892  5677  5723 I jxcore-log: # teardown
09-15 03:37:41.892  5677  5723 I jxcore-log: 
,09-15 03:37:41.894  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:41.894  5677  5723 I jxcore-log: 
,09-15 03:37:41.946  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:41.946  5677  5723 I jxcore-log: 
,09-15 03:37:41.950  5677  5723 I jxcore-log: # setup
09-15 03:37:41.950  5677  5723 I jxcore-log: 
,09-15 03:37:41.951  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:41.951  5677  5723 I jxcore-log: 
,09-15 03:37:42.065  5677  5723 I jxcore-log: # 4. native server connections all up
09-15 03:37:42.065  5677  5723 I jxcore-log: 
,09-15 03:37:42.160   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:42.162  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:42.162  5677  5723 I jxcore-log: 
,09-15 03:37:42.169  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 39464
09-15 03:37:42.169  5677  5723 I jxcore-log: 
,09-15 03:37:42.181  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:42.181  5677  5723 I jxcore-log: 
,09-15 03:37:42.183  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:42.183  5677  5723 I jxcore-log: 
,09-15 03:37:42.186  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:42.186  5677  5723 I jxcore-log: 
,09-15 03:37:42.216  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:42.216  5677  5723 I jxcore-log: 
,09-15 03:37:42.220  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:42.220  5677  5723 I jxcore-log: 
,09-15 03:37:42.223  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:42.223  5677  5723 I jxcore-log: 
,09-15 03:37:42.225  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:42.225  5677  5723 I jxcore-log: 
,09-15 03:37:42.247  5677  5723 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-15 03:37:42.247  5677  5723 I jxcore-log: 
09-15 03:37:42.247  5677  5723 I jxcore-log: ok 8 Send/recvd #1 should be same
09-15 03:37:42.247  5677  5723 I jxcore-log: 
09-15 03:37:42.250  5677  5723 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-15 03:37:42.250  5677  5723 I jxcore-log: 
,09-15 03:37:42.250  5677  5723 I jxcore-log: ok 10 Send/recvd #2 should be same
09-15 03:37:42.250  5677  5723 I jxcore-log: 
,09-15 03:37:42.253  5677  5723 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-15 03:37:42.253  5677  5723 I jxcore-log: 
,09-15 03:37:42.263  5677  5723 I jxcore-log: # teardown
09-15 03:37:42.263  5677  5723 I jxcore-log: 
,09-15 03:37:42.309  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:42.309  5677  5723 I jxcore-log: 
,09-15 03:37:42.311  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:42.311  5677  5723 I jxcore-log: 
,09-15 03:37:42.313  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:42.313  5677  5723 I jxcore-log: 
,09-15 03:37:42.317  5677  5723 I jxcore-log: # setup
09-15 03:37:42.317  5677  5723 I jxcore-log: 
,09-15 03:37:42.318  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:42.318  5677  5723 I jxcore-log: 
,09-15 03:37:42.421  5677  5723 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-15 03:37:42.421  5677  5723 I jxcore-log: 
,09-15 03:37:42.513  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:42.513  5677  5723 I jxcore-log: 
,09-15 03:37:42.520  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 39199
09-15 03:37:42.520  5677  5723 I jxcore-log: 
,09-15 03:37:42.529  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:42.529  5677  5723 I jxcore-log: 
,09-15 03:37:42.530  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:42.530  5677  5723 I jxcore-log: 
,09-15 03:37:42.532  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:42.532  5677  5723 I jxcore-log: 
,09-15 03:37:42.547  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:42.547  5677  5723 I jxcore-log: 
,09-15 03:37:42.551  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:42.551  5677  5723 I jxcore-log: 
,09-15 03:37:42.562  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:42.562  5677  5723 I jxcore-log: 
,09-15 03:37:42.574  5677  5723 I jxcore-log: ok 12 socket shouldn't close until after stream
09-15 03:37:42.574  5677  5723 I jxcore-log: 
,09-15 03:37:42.575  5677  5723 I jxcore-log: ok 13 incoming remains open
09-15 03:37:42.575  5677  5723 I jxcore-log: 
,09-15 03:37:42.577  5677  5723 I jxcore-log: # teardown
09-15 03:37:42.577  5677  5723 I jxcore-log: 
,09-15 03:37:42.660  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:42.660  5677  5723 I jxcore-log: 
,09-15 03:37:42.664  5677  5723 I jxcore-log: # setup
09-15 03:37:42.664  5677  5723 I jxcore-log: 
,09-15 03:37:42.665  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:42.665  5677  5723 I jxcore-log: 
,09-15 03:37:42.802  5677  5723 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-15 03:37:42.802  5677  5723 I jxcore-log: 
,09-15 03:37:42.873  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:42.873  5677  5723 I jxcore-log: 
,09-15 03:37:42.878  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 49577
09-15 03:37:42.878  5677  5723 I jxcore-log: 
,09-15 03:37:42.888  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:42.888  5677  5723 I jxcore-log: 
,09-15 03:37:42.890  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:42.890  5677  5723 I jxcore-log: 
,09-15 03:37:42.892  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:42.892  5677  5723 I jxcore-log: 
,09-15 03:37:42.911  5677  5723 I jxcore-log: ok 14 we should not have gotten an error
09-15 03:37:42.911  5677  5723 I jxcore-log: 
,09-15 03:37:42.917  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:42.917  5677  5723 I jxcore-log: 
,09-15 03:37:42.922  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:42.922  5677  5723 I jxcore-log: 
,09-15 03:37:42.931  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:42.931  5677  5723 I jxcore-log: 
,09-15 03:37:42.933  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:42.933  5677  5723 I jxcore-log: 
,09-15 03:37:42.940  5677  5723 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-15 03:37:42.940  5677  5723 I jxcore-log: 
,09-15 03:37:42.941  5677  5723 I jxcore-log: ok 16 incoming is cleaned up
09-15 03:37:42.941  5677  5723 I jxcore-log: 
,09-15 03:37:42.944  5677  5723 I jxcore-log: # teardown
09-15 03:37:42.944  5677  5723 I jxcore-log: 
,09-15 03:37:43.028  5677  5723 I jxcore-log: # setup
09-15 03:37:43.028  5677  5723 I jxcore-log: 
,09-15 03:37:43.104  5677  5723 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-15 03:37:43.104  5677  5723 I jxcore-log: 
,09-15 03:37:43.162   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:43.178  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:43.178  5677  5723 I jxcore-log: 
,09-15 03:37:43.183  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 49159
09-15 03:37:43.183  5677  5723 I jxcore-log: 
,09-15 03:37:43.194  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.194  5677  5723 I jxcore-log: 
,09-15 03:37:43.196  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.196  5677  5723 I jxcore-log: 
,09-15 03:37:43.203  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.203  5677  5723 I jxcore-log: 
,09-15 03:37:43.223  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.223  5677  5723 I jxcore-log: 
,09-15 03:37:43.227  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.227  5677  5723 I jxcore-log: 
,09-15 03:37:43.244  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:43.244  5677  5723 I jxcore-log: 
,09-15 03:37:43.265  5677  5723 I jxcore-log: ok 17 stream was closed
09-15 03:37:43.265  5677  5723 I jxcore-log: 
,09-15 03:37:43.265  5677  5723 I jxcore-log: ok 18 incoming should survive
09-15 03:37:43.265  5677  5723 I jxcore-log: 
09-15 03:37:43.266  5677  5723 I jxcore-log: ok 19 mux should have no streams
09-15 03:37:43.266  5677  5723 I jxcore-log: 
,09-15 03:37:43.271  5677  5723 I jxcore-log: # teardown
09-15 03:37:43.271  5677  5723 I jxcore-log: 
,09-15 03:37:43.321  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:43.321  5677  5723 I jxcore-log: 
,09-15 03:37:43.327  5677  5723 I jxcore-log: # setup
09-15 03:37:43.327  5677  5723 I jxcore-log: 
,09-15 03:37:43.328  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:43.328  5677  5723 I jxcore-log: 
,09-15 03:37:43.449  5677  5723 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-15 03:37:43.449  5677  5723 I jxcore-log: 
,09-15 03:37:43.516  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:43.516  5677  5723 I jxcore-log: 
,09-15 03:37:43.523  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 49988
09-15 03:37:43.523  5677  5723 I jxcore-log: 
,09-15 03:37:43.534  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.534  5677  5723 I jxcore-log: 
,09-15 03:37:43.537  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.537  5677  5723 I jxcore-log: 
,09-15 03:37:43.540  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.540  5677  5723 I jxcore-log: 
,09-15 03:37:43.556  5677  5723 I jxcore-log: ok 20 we should not have gotten an error
09-15 03:37:43.556  5677  5723 I jxcore-log: 
,09-15 03:37:43.567  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.567  5677  5723 I jxcore-log: 
,09-15 03:37:43.571  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.571  5677  5723 I jxcore-log: 
,09-15 03:37:43.581  5677  5723 I jxcore-log: ok 21 Buffers are identical
09-15 03:37:43.581  5677  5723 I jxcore-log: 
,09-15 03:37:43.590  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:43.590  5677  5723 I jxcore-log: 
,09-15 03:37:43.593  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:43.593  5677  5723 I jxcore-log: 
,09-15 03:37:43.597  5677  5723 I jxcore-log: ok 22 native server is nulled out
09-15 03:37:43.597  5677  5723 I jxcore-log: 
,09-15 03:37:43.598  5677  5723 I jxcore-log: ok 23 native server should be closed
09-15 03:37:43.598  5677  5723 I jxcore-log: 
09-15 03:37:43.598  5677  5723 I jxcore-log: ok 24 incoming has been removed
09-15 03:37:43.598  5677  5723 I jxcore-log: 
09-15 03:37:43.599  5677  5723 I jxcore-log: ok 25 Incoming should be done
09-15 03:37:43.599  5677  5723 I jxcore-log: 
,09-15 03:37:43.599  5677  5723 I jxcore-log: ok 26 The mux object should be closed
09-15 03:37:43.599  5677  5723 I jxcore-log: 
09-15 03:37:43.600  5677  5723 I jxcore-log: ok 27 The mux stream should be closed
09-15 03:37:43.600  5677  5723 I jxcore-log: 
,09-15 03:37:43.601  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:43.601  5677  5723 I jxcore-log: 
,09-15 03:37:43.614  5677  5723 I jxcore-log: # teardown
09-15 03:37:43.614  5677  5723 I jxcore-log: 
,09-15 03:37:43.664  5677  5723 I jxcore-log: # setup
09-15 03:37:43.664  5677  5723 I jxcore-log: 
,09-15 03:37:43.742  5677  5723 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-15 03:37:43.742  5677  5723 I jxcore-log: 
,09-15 03:37:43.813  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:43.813  5677  5723 I jxcore-log: 
,09-15 03:37:43.819  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 47229
09-15 03:37:43.819  5677  5723 I jxcore-log: 
,09-15 03:37:43.852  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.852  5677  5723 I jxcore-log: 
,09-15 03:37:43.853  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.853  5677  5723 I jxcore-log: 
,09-15 03:37:43.854  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.854  5677  5723 I jxcore-log: 
,09-15 03:37:43.858  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.858  5677  5723 I jxcore-log: 
,09-15 03:37:43.858  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.858  5677  5723 I jxcore-log: 
09-15 03:37:43.860  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.860  5677  5723 I jxcore-log: 
,09-15 03:37:43.863  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.863  5677  5723 I jxcore-log: 
,09-15 03:37:43.864  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.864  5677  5723 I jxcore-log: 
,09-15 03:37:43.865  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.865  5677  5723 I jxcore-log: 
,09-15 03:37:43.868  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.868  5677  5723 I jxcore-log: 
,09-15 03:37:43.868  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.868  5677  5723 I jxcore-log: 
09-15 03:37:43.869  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.869  5677  5723 I jxcore-log: 
,09-15 03:37:43.872  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.872  5677  5723 I jxcore-log: 
,09-15 03:37:43.873  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.873  5677  5723 I jxcore-log: 
,09-15 03:37:43.874  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.874  5677  5723 I jxcore-log: 
,09-15 03:37:43.876  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.876  5677  5723 I jxcore-log: 
09-15 03:37:43.876  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.876  5677  5723 I jxcore-log: 
,09-15 03:37:43.878  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.878  5677  5723 I jxcore-log: 
,09-15 03:37:43.887  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.887  5677  5723 I jxcore-log: 
,09-15 03:37:43.889  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.889  5677  5723 I jxcore-log: 
,09-15 03:37:43.891  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.891  5677  5723 I jxcore-log: 
,09-15 03:37:43.896  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.896  5677  5723 I jxcore-log: 
,09-15 03:37:43.897  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.897  5677  5723 I jxcore-log: 
,09-15 03:37:43.898  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.898  5677  5723 I jxcore-log: 
09-15 03:37:43.899  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.899  5677  5723 I jxcore-log: 
09-15 03:37:43.899  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.899  5677  5723 I jxcore-log: 
09-15 03:37:43.900  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.900  5677  5723 I jxcore-log: 
09-15 03:37:43.901  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:43.901  5677  5723 I jxcore-log: 
,09-15 03:37:43.901  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:43.901  5677  5723 I jxcore-log: 
09-15 03:37:43.902  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:43.902  5677  5723 I jxcore-log: 
,09-15 03:37:43.962  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.962  5677  5723 I jxcore-log: 
,09-15 03:37:43.964  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.964  5677  5723 I jxcore-log: 
,09-15 03:37:43.965  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.965  5677  5723 I jxcore-log: 
,09-15 03:37:43.966  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.966  5677  5723 I jxcore-log: 
,09-15 03:37:43.967  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.967  5677  5723 I jxcore-log: 
,09-15 03:37:43.969  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.969  5677  5723 I jxcore-log: 
,09-15 03:37:43.971  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.971  5677  5723 I jxcore-log: 
,09-15 03:37:43.972  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.972  5677  5723 I jxcore-log: 
,09-15 03:37:43.974  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.974  5677  5723 I jxcore-log: 
,09-15 03:37:43.975  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.975  5677  5723 I jxcore-log: 
,09-15 03:37:43.976  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.976  5677  5723 I jxcore-log: 
09-15 03:37:43.977  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.977  5677  5723 I jxcore-log: 
09-15 03:37:43.978  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.978  5677  5723 I jxcore-log: 
,09-15 03:37:43.978  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.978  5677  5723 I jxcore-log: 
,09-15 03:37:43.979  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.979  5677  5723 I jxcore-log: 
,09-15 03:37:43.980  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.980  5677  5723 I jxcore-log: 
,09-15 03:37:43.982  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.982  5677  5723 I jxcore-log: 
,09-15 03:37:43.983  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.983  5677  5723 I jxcore-log: 
,09-15 03:37:43.983  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.983  5677  5723 I jxcore-log: 
,09-15 03:37:43.984  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.984  5677  5723 I jxcore-log: 
,09-15 03:37:43.985  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.985  5677  5723 I jxcore-log: 
,09-15 03:37:43.986  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.986  5677  5723 I jxcore-log: 
,09-15 03:37:43.987  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.987  5677  5723 I jxcore-log: 
,09-15 03:37:43.990  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.990  5677  5723 I jxcore-log: 
,09-15 03:37:43.991  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.991  5677  5723 I jxcore-log: 
,09-15 03:37:43.993  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.993  5677  5723 I jxcore-log: 
,09-15 03:37:43.993  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.993  5677  5723 I jxcore-log: 
,09-15 03:37:43.994  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.994  5677  5723 I jxcore-log: 
,09-15 03:37:43.995  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.995  5677  5723 I jxcore-log: 
,09-15 03:37:43.995  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.995  5677  5723 I jxcore-log: 
,09-15 03:37:43.996  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.996  5677  5723 I jxcore-log: 
,09-15 03:37:43.997  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.997  5677  5723 I jxcore-log: 
,09-15 03:37:43.998  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.998  5677  5723 I jxcore-log: 
09-15 03:37:43.999  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:43.999  5677  5723 I jxcore-log: 
,09-15 03:37:43.999  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:43.999  5677  5723 I jxcore-log: 
09-15 03:37:44.000  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.000  5677  5723 I jxcore-log: 
,09-15 03:37:44.001  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.001  5677  5723 I jxcore-log: 
09-15 03:37:44.001  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.001  5677  5723 I jxcore-log: 
,09-15 03:37:44.006  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.006  5677  5723 I jxcore-log: 
,09-15 03:37:44.007  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.007  5677  5723 I jxcore-log: 
,09-15 03:37:44.009  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.009  5677  5723 I jxcore-log: 
,09-15 03:37:44.010  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.010  5677  5723 I jxcore-log: 
,09-15 03:37:44.011  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.011  5677  5723 I jxcore-log: 
,09-15 03:37:44.012  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.012  5677  5723 I jxcore-log: 
,09-15 03:37:44.012  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.012  5677  5723 I jxcore-log: 
09-15 03:37:44.013  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.013  5677  5723 I jxcore-log: 
,09-15 03:37:44.014  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.014  5677  5723 I jxcore-log: 
,09-15 03:37:44.014  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.014  5677  5723 I jxcore-log: 
,09-15 03:37:44.015  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.015  5677  5723 I jxcore-log: 
,09-15 03:37:44.016  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.016  5677  5723 I jxcore-log: 
,09-15 03:37:44.017  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.017  5677  5723 I jxcore-log: 
,09-15 03:37:44.017  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.017  5677  5723 I jxcore-log: 
09-15 03:37:44.018  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.018  5677  5723 I jxcore-log: 
,09-15 03:37:44.019  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.019  5677  5723 I jxcore-log: 
09-15 03:37:44.019  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.019  5677  5723 I jxcore-log: 
,09-15 03:37:44.020  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.020  5677  5723 I jxcore-log: 
,09-15 03:37:44.021  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.021  5677  5723 I jxcore-log: 
,09-15 03:37:44.022  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.022  5677  5723 I jxcore-log: 
,09-15 03:37:44.022  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.022  5677  5723 I jxcore-log: 
,09-15 03:37:44.023  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.023  5677  5723 I jxcore-log: 
,09-15 03:37:44.024  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.024  5677  5723 I jxcore-log: 
,09-15 03:37:44.024  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.024  5677  5723 I jxcore-log: 
09-15 03:37:44.025  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.025  5677  5723 I jxcore-log: 
,09-15 03:37:44.026  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.026  5677  5723 I jxcore-log: 
,09-15 03:37:44.027  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.027  5677  5723 I jxcore-log: 
,09-15 03:37:44.027  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.027  5677  5723 I jxcore-log: 
09-15 03:37:44.028  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.028  5677  5723 I jxcore-log: 
,09-15 03:37:44.029  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.029  5677  5723 I jxcore-log: 
,09-15 03:37:44.029  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.029  5677  5723 I jxcore-log: 
09-15 03:37:44.030  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.030  5677  5723 I jxcore-log: 
,09-15 03:37:44.031  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.031  5677  5723 I jxcore-log: 
,09-15 03:37:44.031  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.031  5677  5723 I jxcore-log: 
,09-15 03:37:44.032  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.032  5677  5723 I jxcore-log: 
,09-15 03:37:44.033  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.033  5677  5723 I jxcore-log: 
,09-15 03:37:44.034  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.034  5677  5723 I jxcore-log: 
09-15 03:37:44.034  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.034  5677  5723 I jxcore-log: 
,09-15 03:37:44.035  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.035  5677  5723 I jxcore-log: 
,09-15 03:37:44.036  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.036  5677  5723 I jxcore-log: 
09-15 03:37:44.036  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:44.036  5677  5723 I jxcore-log: 
,09-15 03:37:44.037  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:44.037  5677  5723 I jxcore-log: 
,09-15 03:37:44.082  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.082  5677  5723 I jxcore-log: 
,09-15 03:37:44.083  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.083  5677  5723 I jxcore-log: 
,09-15 03:37:44.084  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.084  5677  5723 I jxcore-log: 
,09-15 03:37:44.085  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.085  5677  5723 I jxcore-log: 
,09-15 03:37:44.085  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.085  5677  5723 I jxcore-log: 
09-15 03:37:44.086  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.086  5677  5723 I jxcore-log: 
,09-15 03:37:44.087  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.087  5677  5723 I jxcore-log: 
09-15 03:37:44.087  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.087  5677  5723 I jxcore-log: 
,09-15 03:37:44.088  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.088  5677  5723 I jxcore-log: 
09-15 03:37:44.088  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.088  5677  5723 I jxcore-log: 
,09-15 03:37:44.089  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.089  5677  5723 I jxcore-log: 
,09-15 03:37:44.090  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.090  5677  5723 I jxcore-log: 
,09-15 03:37:44.091  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.091  5677  5723 I jxcore-log: 
09-15 03:37:44.092  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.092  5677  5723 I jxcore-log: 
,09-15 03:37:44.092  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.092  5677  5723 I jxcore-log: 
,09-15 03:37:44.096  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.096  5677  5723 I jxcore-log: 
,09-15 03:37:44.098  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.098  5677  5723 I jxcore-log: 
,09-15 03:37:44.099  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.099  5677  5723 I jxcore-log: 
,09-15 03:37:44.099  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.099  5677  5723 I jxcore-log: 
09-15 03:37:44.100  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.100  5677  5723 I jxcore-log: 
,09-15 03:37:44.100  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.100  5677  5723 I jxcore-log: 
09-15 03:37:44.101  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.101  5677  5723 I jxcore-log: 
,09-15 03:37:44.101  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.101  5677  5723 I jxcore-log: 
09-15 03:37:44.101  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.101  5677  5723 I jxcore-log: 
09-15 03:37:44.102  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.102  5677  5723 I jxcore-log: 
,09-15 03:37:44.103  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.103  5677  5723 I jxcore-log: 
09-15 03:37:44.103  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.103  5677  5723 I jxcore-log: 
09-15 03:37:44.103  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.103  5677  5723 I jxcore-log: 
,09-15 03:37:44.104  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.104  5677  5723 I jxcore-log: 
09-15 03:37:44.104  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.104  5677  5723 I jxcore-log: 
,09-15 03:37:44.105  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.105  5677  5723 I jxcore-log: 
09-15 03:37:44.105  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.105  5677  5723 I jxcore-log: 
,09-15 03:37:44.106  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.106  5677  5723 I jxcore-log: 
09-15 03:37:44.106  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.106  5677  5723 I jxcore-log: 
09-15 03:37:44.106  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.106  5677  5723 I jxcore-log: 
,09-15 03:37:44.107  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.107  5677  5723 I jxcore-log: 
,09-15 03:37:44.107  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.107  5677  5723 I jxcore-log: 
09-15 03:37:44.108  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.108  5677  5723 I jxcore-log: 
09-15 03:37:44.108  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.108  5677  5723 I jxcore-log: 
09-15 03:37:44.108  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.108  5677  5723 I jxcore-log: 
,09-15 03:37:44.109  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.109  5677  5723 I jxcore-log: 
09-15 03:37:44.109  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.109  5677  5723 I jxcore-log: 
09-15 03:37:44.110  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.110  5677  5723 I jxcore-log: 
09-15 03:37:44.110  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.110  5677  5723 I jxcore-log: 
,09-15 03:37:44.110  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.110  5677  5723 I jxcore-log: 
09-15 03:37:44.111  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.111  5677  5723 I jxcore-log: 
09-15 03:37:44.111  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.111  5677  5723 I jxcore-log: 
,09-15 03:37:44.112  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.112  5677  5723 I jxcore-log: 
09-15 03:37:44.112  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:44.112  5677  5723 I jxcore-log: 
,09-15 03:37:44.112  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:44.112  5677  5723 I jxcore-log: 
,09-15 03:37:44.114  5677  5723 I jxcore-log: ok 28 native server is nulled out
09-15 03:37:44.114  5677  5723 I jxcore-log: 
,09-15 03:37:44.115  5677  5723 I jxcore-log: ok 29 native server should be closed
09-15 03:37:44.115  5677  5723 I jxcore-log: 
09-15 03:37:44.115  5677  5723 I jxcore-log: ok 30 incoming has been removed
09-15 03:37:44.115  5677  5723 I jxcore-log: 
,09-15 03:37:44.116  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.116  5677  5723 I jxcore-log: 
09-15 03:37:44.116  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.116  5677  5723 I jxcore-log: 
09-15 03:37:44.116  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.116  5677  5723 I jxcore-log: 
,09-15 03:37:44.117  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.117  5677  5723 I jxcore-log: 
09-15 03:37:44.117  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.117  5677  5723 I jxcore-log: 
09-15 03:37:44.117  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.117  5677  5723 I jxcore-log: 
,09-15 03:37:44.117  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.117  5677  5723 I jxcore-log: 
09-15 03:37:44.117  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.117  5677  5723 I jxcore-log: 
09-15 03:37:44.118  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.118  5677  5723 I jxcore-log: 
09-15 03:37:44.118  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:44.118  5677  5723 I jxcore-log: 
,09-15 03:37:44.164   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:44.197  5677  5723 I jxcore-log: # teardown
09-15 03:37:44.197  5677  5723 I jxcore-log: 
,09-15 03:37:44.394  5677  5723 I jxcore-log: # setup
09-15 03:37:44.394  5677  5723 I jxcore-log: 
,09-15 03:37:45.165   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:45.177   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=493090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:37:45.672  5677  5723 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-15 03:37:45.672  5677  5723 I jxcore-log: 
,09-15 03:37:45.769  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:45.769  5677  5723 I jxcore-log: 
,09-15 03:37:45.775  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 40821
09-15 03:37:45.775  5677  5723 I jxcore-log: 
,09-15 03:37:45.785  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:45.785  5677  5723 I jxcore-log: 
,09-15 03:37:45.787  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:45.787  5677  5723 I jxcore-log: 
,09-15 03:37:45.789  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:45.789  5677  5723 I jxcore-log: 
,09-15 03:37:45.799  5677  5723 I jxcore-log: ok 31 we should not have gotten an error
09-15 03:37:45.799  5677  5723 I jxcore-log: 
,09-15 03:37:45.812  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:45.812  5677  5723 I jxcore-log: 
,09-15 03:37:45.815  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:45.815  5677  5723 I jxcore-log: 
,09-15 03:37:45.822  5677  5723 I jxcore-log: ok 32 Buffers are identical
09-15 03:37:45.822  5677  5723 I jxcore-log: 
,09-15 03:37:45.823  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:45.823  5677  5723 I jxcore-log: 
,09-15 03:37:45.825  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:45.825  5677  5723 I jxcore-log: 
,09-15 03:37:45.835  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:45.835  5677  5723 I jxcore-log: 
,09-15 03:37:45.836  5677  5723 I jxcore-log: ok 33 server should be fine
09-15 03:37:45.836  5677  5723 I jxcore-log: 
09-15 03:37:45.837  5677  5723 I jxcore-log: ok 34 server should be open
09-15 03:37:45.837  5677  5723 I jxcore-log: 
,09-15 03:37:45.837  5677  5723 I jxcore-log: ok 35 incoming has been removed
09-15 03:37:45.837  5677  5723 I jxcore-log: 
,09-15 03:37:45.838  5677  5723 I jxcore-log: ok 36 The mux object should be closed
09-15 03:37:45.838  5677  5723 I jxcore-log: 
09-15 03:37:45.838  5677  5723 I jxcore-log: ok 37 The mux stream should be closed
09-15 03:37:45.838  5677  5723 I jxcore-log: 
,09-15 03:37:45.841  5677  5723 I jxcore-log: # teardown
09-15 03:37:45.841  5677  5723 I jxcore-log: 
,09-15 03:37:45.910  5677  5723 I jxcore-log: # setup
09-15 03:37:45.910  5677  5723 I jxcore-log: 
,09-15 03:37:45.991  5677  5723 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-15 03:37:45.991  5677  5723 I jxcore-log: 
,09-15 03:37:46.073  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:46.073  5677  5723 I jxcore-log: 
,09-15 03:37:46.080  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 41941
09-15 03:37:46.080  5677  5723 I jxcore-log: 
,09-15 03:37:46.089  5677  5723 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-15 03:37:46.089  5677  5723 I jxcore-log: 
,09-15 03:37:46.092  5677  5723 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-15 03:37:46.092  5677  5723 I jxcore-log: 
,09-15 03:37:46.093  5677  5723 I jxcore-log: DEBUG createNativeListener: new mux
09-15 03:37:46.093  5677  5723 I jxcore-log: 
,09-15 03:37:46.101  5677  5723 I jxcore-log: ok 38 we should not have gotten an error
09-15 03:37:46.101  5677  5723 I jxcore-log: 
,09-15 03:37:46.108  5677  5723 I jxcore-log: DEBUG createNativeListener: new stream: 
09-15 03:37:46.108  5677  5723 I jxcore-log: 
,09-15 03:37:46.113  5677  5723 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-15 03:37:46.113  5677  5723 I jxcore-log: 
,09-15 03:37:46.119  5677  5723 I jxcore-log: ok 39 Buffers are identical
09-15 03:37:46.119  5677  5723 I jxcore-log: 
,09-15 03:37:46.123  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-15 03:37:46.123  5677  5723 I jxcore-log: 
09-15 03:37:46.124  5677  5723 I jxcore-log: DEBUG createNativeListener: stream close:
09-15 03:37:46.124  5677  5723 I jxcore-log: 
09-15 03:37:46.126  5677  5723 I jxcore-log: DEBUG createNativeListener: mux close
09-15 03:37:46.126  5677  5723 I jxcore-log: 
,09-15 03:37:46.130  5677  5723 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-15 03:37:46.130  5677  5723 I jxcore-log: 
09-15 03:37:46.131  5677  5723 I jxcore-log: ok 40 server should be fine
09-15 03:37:46.131  5677  5723 I jxcore-log: 
,09-15 03:37:46.131  5677  5723 I jxcore-log: ok 41 server should be open
09-15 03:37:46.131  5677  5723 I jxcore-log: 
09-15 03:37:46.131  5677  5723 I jxcore-log: ok 42 incoming has been removed
09-15 03:37:46.131  5677  5723 I jxcore-log: 
09-15 03:37:46.131  5677  5723 I jxcore-log: ok 43 The mux object should be closed
09-15 03:37:46.131  5677  5723 I jxcore-log: 
09-15 03:37:46.132  5677  5723 I jxcore-log: ok 44 The mux stream should be closed
09-15 03:37:46.132  5677  5723 I jxcore-log: 
,09-15 03:37:46.137  5677  5723 I jxcore-log: # teardown
09-15 03:37:46.137  5677  5723 I jxcore-log: 
,09-15 03:37:46.166   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:37:46.228  5677  5723 I jxcore-log: # setup
09-15 03:37:46.228  5677  5723 I jxcore-log: 
,09-15 03:37:46.288  5677  5723 I jxcore-log: # 12. closeAll can close even when connections open
09-15 03:37:46.288  5677  5723 I jxcore-log: 
,09-15 03:37:46.485  5677  5723 I jxcore-log: ok 45 not possible to connect to the server anymore
09-15 03:37:46.485  5677  5723 I jxcore-log: 
,09-15 03:37:46.492  5677  5723 I jxcore-log: # teardown
09-15 03:37:46.492  5677  5723 I jxcore-log: 
,09-15 03:37:46.562  5677  5723 I jxcore-log: # setup
09-15 03:37:46.562  5677  5723 I jxcore-log: 
,09-15 03:37:46.638  5677  5723 I jxcore-log: # 13. closeAll with promise
09-15 03:37:46.638  5677  5723 I jxcore-log: 
,09-15 03:37:46.848  5677  5723 I jxcore-log: ok 46 not possible to connect to the server anymore
09-15 03:37:46.848  5677  5723 I jxcore-log: 
,09-15 03:37:46.854  5677  5723 I jxcore-log: # teardown
09-15 03:37:46.854  5677  5723 I jxcore-log: 
,09-15 03:37:46.918  5677  5723 I jxcore-log: # setup
09-15 03:37:46.918  5677  5723 I jxcore-log: 
,09-15 03:37:46.985  5677  5723 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
09-15 03:37:46.985  5677  5723 I jxcore-log: 
,09-15 03:37:47.166  5677  5723 I jxcore-log: ok 47 Got the right error
09-15 03:37:47.166  5677  5723 I jxcore-log: 
,09-15 03:37:47.166   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:37:47.175  5677  5723 I jxcore-log: # teardown
09-15 03:37:47.175  5677  5723 I jxcore-log: 
,09-15 03:37:47.251  5677  5723 I jxcore-log: # setup
09-15 03:37:47.251  5677  5723 I jxcore-log: 
,09-15 03:37:47.335  5677  5723 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-15 03:37:47.335  5677  5723 I jxcore-log: 
,09-15 03:37:47.516  5677  5723 I jxcore-log: # teardown
09-15 03:37:47.516  5677  5723 I jxcore-log: 
,09-15 03:37:47.561  5677  5723 I jxcore-log: # setup
09-15 03:37:47.561  5677  5723 I jxcore-log: 
,09-15 03:37:47.625  5677  5723 I jxcore-log: # 16. onPeerLost calls jxcore
09-15 03:37:47.625  5677  5723 I jxcore-log: 
,09-15 03:37:47.694  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 03:37:47.694  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e33449b added. We now have 3 listener(s)
,09-15 03:37:47.698  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:37:47.698  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:47.698  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:37:47.698  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 03:37:47.699  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59da038 added. We now have 4 listener(s)
09-15 03:37:47.699  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 03:37:47.700  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 03:37:47.707  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:47.715  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:47.718  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:47.718  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 03:37:47.719  5677  5723 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-15 03:37:47.719  5677  5723 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-15 03:37:47.723  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:47.728  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:49.722  5677  5723 I jxcore-log: onPeerLost
09-15 03:37:49.722  5677  5723 I jxcore-log: 
,09-15 03:37:49.725  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:49.725  5677  5723 I jxcore-log: 
,09-15 03:37:49.735  5677  5723 I jxcore-log: # teardown
09-15 03:37:49.735  5677  5723 I jxcore-log: 
,09-15 03:37:49.749  5677  5723 I jxcore-log: ok 48 check if callback was fired by onPeerLost
09-15 03:37:49.749  5677  5723 I jxcore-log: 
,09-15 03:37:49.750  5677  5723 I jxcore-log: ok 49 check if peerAvailable is false
09-15 03:37:49.750  5677  5723 I jxcore-log: 
,09-15 03:37:49.835  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 03:37:49.835  5677  5723 I jxcore-log: 
,09-15 03:37:49.840  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 03:37:49.840  5677  5723 I jxcore-log: 
,09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:49.850  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:49.853  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:49.856  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 03:37:49.856  5677  5723 I jxcore-log: 
,09-15 03:37:49.859  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 03:37:49.859  5677  5723 I jxcore-log: 
,09-15 03:37:49.862  5677  5723 I jxcore-log: # setup
09-15 03:37:49.862  5677  5723 I jxcore-log: 
,09-15 03:37:49.864  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:49.864  5677  5723 I jxcore-log: 
,09-15 03:37:49.947  5677  5723 I jxcore-log: # 17. onPeerDiscovered calls jxcore
09-15 03:37:49.947  5677  5723 I jxcore-log: 
,09-15 03:37:50.008  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 03:37:50.009  5677  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7547d76 added. We now have 4 listener(s)
,09-15 03:37:50.011  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:37:50.012  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 03:37:50.012  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 03:37:50.012  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 03:37:50.012  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c778f77 added. We now have 5 listener(s)
09-15 03:37:50.012  5677  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 03:37:50.014  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 03:37:50.020  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:50.029  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:50.034  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:50.035  5677  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 03:37:50.035  5677  5723 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-15 03:37:50.042  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:50.046  5677  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 03:37:51.144   925  3001 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-15 03:37:52.038  5677  5723 I jxcore-log: onPeerDiscovered
09-15 03:37:52.038  5677  5723 I jxcore-log: 
,09-15 03:37:52.041  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:52.041  5677  5723 I jxcore-log: 
,09-15 03:37:52.049  5677  5723 I jxcore-log: # teardown
09-15 03:37:52.049  5677  5723 I jxcore-log: 
,09-15 03:37:52.060  5677  5723 I jxcore-log: ok 50 check if callback was fired by onPeerDiscovered
09-15 03:37:52.060  5677  5723 I jxcore-log: 
,09-15 03:37:52.061  5677  5723 I jxcore-log: ok 51 check if peerAvailable is true
09-15 03:37:52.061  5677  5723 I jxcore-log: 
,09-15 03:37:52.527  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 03:37:52.527  5677  5723 I jxcore-log: 
,09-15 03:37:52.531  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 03:37:52.531  5677  5723 I jxcore-log: 
,09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 03:37:52.543  5677  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 03:37:52.547  5677  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 03:37:52.550  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 03:37:52.550  5677  5723 I jxcore-log: 
,09-15 03:37:52.553  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 03:37:52.553  5677  5723 I jxcore-log: 
09-15 03:37:52.556  5677  5723 I jxcore-log: # setup
09-15 03:37:52.556  5677  5723 I jxcore-log: 
,09-15 03:37:52.567  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 03:37:52.567  5677  5723 I jxcore-log: 
,09-15 03:37:52.655  5677  5723 I jxcore-log: # 18. test defaultDirectory
09-15 03:37:52.655  5677  5723 I jxcore-log: 
,09-15 03:37:52.763  5677  5723 I jxcore-log: ok 52 should be equal
09-15 03:37:52.763  5677  5723 I jxcore-log: 
,09-15 03:37:52.768  5677  5723 I jxcore-log: ok 53 should be equal
09-15 03:37:52.768  5677  5723 I jxcore-log: 
,09-15 03:37:52.786  5677  5723 I jxcore-log: ok 54 should be equal
09-15 03:37:52.786  5677  5723 I jxcore-log: 
,09-15 03:37:52.788  5677  5723 I jxcore-log: # teardown
09-15 03:37:52.788  5677  5723 I jxcore-log: 
,09-15 03:37:52.863  5677  5723 I jxcore-log: # setup
09-15 03:37:52.863  5677  5723 I jxcore-log: 
,09-15 03:37:52.913  5677  5723 I jxcore-log: # 19. test defaultAdapter
09-15 03:37:52.913  5677  5723 I jxcore-log: 
,09-15 03:37:52.970  3659  5559 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-15 03:37:52.987  5677  5723 I jxcore-log: ok 55 should be equal
09-15 03:37:52.987  5677  5723 I jxcore-log: 
,09-15 03:37:52.988  5677  5723 I jxcore-log: ok 56 should be equal
09-15 03:37:52.988  5677  5723 I jxcore-log: 
,09-15 03:37:52.991  5677  5723 I jxcore-log: ok 57 should be equal
09-15 03:37:52.991  5677  5723 I jxcore-log: 
09-15 03:37:52.991  5677  5723 I jxcore-log: ok 58 should be equal
09-15 03:37:52.991  5677  5723 I jxcore-log: 
,09-15 03:37:52.996  5677  5723 I jxcore-log: ok 59 should be equal
09-15 03:37:52.996  5677  5723 I jxcore-log: 
09-15 03:37:52.997  5677  5723 I jxcore-log: ok 60 should be equal
09-15 03:37:52.997  5677  5723 I jxcore-log: 
,09-15 03:37:53.142  5677  5723 I jxcore-log: ok 61 should be equal
09-15 03:37:53.142  5677  5723 I jxcore-log: 
,09-15 03:37:53.143  5677  5723 I jxcore-log: ok 62 should be equal
09-15 03:37:53.143  5677  5723 I jxcore-log: 
09-15 03:37:53.144  5677  5723 I jxcore-log: # teardown
09-15 03:37:53.144  5677  5723 I jxcore-log: 
,09-15 03:37:53.352  5677  5723 I jxcore-log: # setup
09-15 03:37:53.352  5677  5723 I jxcore-log: 
,09-15 03:37:53.466  5677  5723 I jxcore-log: # 20. enqueue and run in order
09-15 03:37:53.466  5677  5723 I jxcore-log: 
,09-15 03:37:53.604  5677  5723 I jxcore-log: ok 63 firstPromise setTimeout
09-15 03:37:53.604  5677  5723 I jxcore-log: 
,09-15 03:37:53.609  5677  5723 I jxcore-log: ok 64 firstPromise result
09-15 03:37:53.609  5677  5723 I jxcore-log: 
,09-15 03:37:53.613  5677  5723 I jxcore-log: ok 65 firstPromise testValue
09-15 03:37:53.613  5677  5723 I jxcore-log: 
,09-15 03:37:53.716  5677  5723 I jxcore-log: ok 66 secondPromise setTimeout
09-15 03:37:53.716  5677  5723 I jxcore-log: 
,09-15 03:37:53.719  5677  5723 I jxcore-log: ok 67 secondPromise result
09-15 03:37:53.719  5677  5723 I jxcore-log: 
,09-15 03:37:53.720  5677  5723 I jxcore-log: ok 68 secondPromise testValue
09-15 03:37:53.720  5677  5723 I jxcore-log: 
,09-15 03:37:53.722  5677  5723 I jxcore-log: ok 69 thirdPromise in promise
09-15 03:37:53.722  5677  5723 I jxcore-log: 
,09-15 03:37:53.725  5677  5723 I jxcore-log: ok 70 thirdPromise result
09-15 03:37:53.725  5677  5723 I jxcore-log: 
,09-15 03:37:53.726  5677  5723 I jxcore-log: ok 71 thirdPromise testValue
09-15 03:37:53.726  5677  5723 I jxcore-log: 
,09-15 03:37:53.733  5677  5723 I jxcore-log: # teardown
09-15 03:37:53.733  5677  5723 I jxcore-log: 
,09-15 03:37:53.798  5677  5723 I jxcore-log: # setup
09-15 03:37:53.798  5677  5723 I jxcore-log: 
,09-15 03:37:53.893  5677  5723 I jxcore-log: # 21. enqueueAtTop and run backwards
09-15 03:37:53.893  5677  5723 I jxcore-log: 
,09-15 03:37:53.986  5677  5723 I jxcore-log: ok 72 thirdPromise - first to run
09-15 03:37:53.986  5677  5723 I jxcore-log: 
,09-15 03:37:53.990  5677  5723 I jxcore-log: ok 73 thirdPromise - in resolve
09-15 03:37:53.990  5677  5723 I jxcore-log: 
,09-15 03:37:53.992  5677  5723 I jxcore-log: ok 74 secondPromise - second to run
09-15 03:37:53.992  5677  5723 I jxcore-log: 
09-15 03:37:53.994  5677  5723 I jxcore-log: ok 75 secondPromise - in catch
09-15 03:37:53.994  5677  5723 I jxcore-log: 
,09-15 03:37:53.996  5677  5723 I jxcore-log: ok 76 firstPromise - third to run
09-15 03:37:53.996  5677  5723 I jxcore-log: 
,09-15 03:37:53.999  5677  5723 I jxcore-log: ok 77 firstPromise - in then
09-15 03:37:53.999  5677  5723 I jxcore-log: 
,09-15 03:37:54.001  5677  5723 I jxcore-log: ok 78 testing promises
09-15 03:37:54.001  5677  5723 I jxcore-log: 
,09-15 03:37:54.005  5677  5723 I jxcore-log: # teardown
09-15 03:37:54.005  5677  5723 I jxcore-log: 
,09-15 03:37:54.055  5677  5723 I jxcore-log: # setup
09-15 03:37:54.055  5677  5723 I jxcore-log: 
,09-15 03:37:54.121  5677  5723 I jxcore-log: # 22. mix enqueue and enqueueAtTop
09-15 03:37:54.121  5677  5723 I jxcore-log: 
,09-15 03:37:54.194  5677  5723 I jxcore-log: ok 79 fourth
09-15 03:37:54.194  5677  5723 I jxcore-log: 
,09-15 03:37:54.197  5677  5723 I jxcore-log: ok 80 fourth
09-15 03:37:54.197  5677  5723 I jxcore-log: 
,09-15 03:37:54.200  5677  5723 I jxcore-log: ok 81 second
09-15 03:37:54.200  5677  5723 I jxcore-log: 
,09-15 03:37:54.202  5677  5723 I jxcore-log: ok 82 secondPromise - in then
09-15 03:37:54.202  5677  5723 I jxcore-log: 
,09-15 03:37:54.306  5677  5723 I jxcore-log: ok 83 first
09-15 03:37:54.306  5677  5723 I jxcore-log: 
,09-15 03:37:54.309  5677  5723 I jxcore-log: ok 84 firstPromise - in catch
09-15 03:37:54.309  5677  5723 I jxcore-log: 
09-15 03:37:54.311  5677  5723 I jxcore-log: ok 85 third
09-15 03:37:54.311  5677  5723 I jxcore-log: 
,09-15 03:37:54.314  5677  5723 I jxcore-log: ok 86 thirdPromise - in then
09-15 03:37:54.314  5677  5723 I jxcore-log: 
,09-15 03:37:54.317  5677  5723 I jxcore-log: ok 87 testingPromises
09-15 03:37:54.317  5677  5723 I jxcore-log: 
,09-15 03:37:54.326  5677  5723 I jxcore-log: # teardown
09-15 03:37:54.326  5677  5723 I jxcore-log: 
,09-15 03:37:54.396  5677  5723 I jxcore-log: # setup
09-15 03:37:54.396  5677  5723 I jxcore-log: 
,09-15 03:37:54.476  5677  5723 I jxcore-log: # 23. queues handled independently
09-15 03:37:54.476  5677  5723 I jxcore-log: 
,09-15 03:37:54.695  5677  5723 I jxcore-log: ok 88 all short operations completed before the long resolves
09-15 03:37:54.695  5677  5723 I jxcore-log: 
,09-15 03:37:54.705  5677  5723 I jxcore-log: # teardown
09-15 03:37:54.705  5677  5723 I jxcore-log: 
,09-15 03:37:54.786  5677  5723 I jxcore-log: # setup
09-15 03:37:54.786  5677  5723 I jxcore-log: 
,09-15 03:37:54.840  5677  5723 I jxcore-log: # 24. basic
09-15 03:37:54.840  5677  5723 I jxcore-log: 
,09-15 03:37:54.903  5677  5723 I jxcore-log: ok 89 sane
09-15 03:37:54.903  5677  5723 I jxcore-log: 
,09-15 03:37:54.907  5677  5723 I jxcore-log: # teardown
09-15 03:37:54.907  5677  5723 I jxcore-log: 
,09-15 03:37:54.972  5677  5723 I jxcore-log: # setup
09-15 03:37:54.972  5677  5723 I jxcore-log: 
,09-15 03:37:55.033  5677  5723 I jxcore-log: # 25. another
09-15 03:37:55.033  5677  5723 I jxcore-log: 
,09-15 03:37:55.091  5677  5723 I jxcore-log: ok 90 sane
09-15 03:37:55.091  5677  5723 I jxcore-log: 
,09-15 03:37:55.095  5677  5723 I jxcore-log: # teardown
09-15 03:37:55.095  5677  5723 I jxcore-log: 
,09-15 03:37:55.176  5677  5723 I jxcore-log: # setup
09-15 03:37:55.176  5677  5723 I jxcore-log: 
,09-15 03:37:55.240  5677  5723 I jxcore-log: # 26. can pass data in setup
09-15 03:37:55.240  5677  5723 I jxcore-log: 
,09-15 03:37:55.298  5677  5723 I jxcore-log: [{"uuid":"89e6618f-61a3-47e8-ac4f-5a6ad78ed99e","data":"custom data"},{"uuid":"d5ed4044-837a-4ed7-a18a-28c83c60012d","data":"custom data"},{"uuid":"f7a22ae9-a149-465d-82be-6ab4ef807a2e","data":"custom data"}]
09-15 03:37:55.298  5677  5723 I jxcore-log: 
,09-15 03:37:55.299  5677  5723 I jxcore-log: ok 91 test participant has uuid
09-15 03:37:55.299  5677  5723 I jxcore-log: 
09-15 03:37:55.301  5677  5723 I jxcore-log: ok 92 participant data matches
09-15 03:37:55.301  5677  5723 I jxcore-log: 
09-15 03:37:55.301  5677  5723 I jxcore-log: ok 93 test participant has uuid
09-15 03:37:55.301  5677  5723 I jxcore-log: 
,09-15 03:37:55.302  5677  5723 I jxcore-log: ok 94 participant data matches
09-15 03:37:55.302  5677  5723 I jxcore-log: 
09-15 03:37:55.302  5677  5723 I jxcore-log: ok 95 test participant has uuid
09-15 03:37:55.302  5677  5723 I jxcore-log: 
09-15 03:37:55.303  5677  5723 I jxcore-log: ok 96 participant data matches
09-15 03:37:55.303  5677  5723 I jxcore-log: 
09-15 03:37:55.305  5677  5723 I jxcore-log: ok 97 own UUID is found from the participants list
09-15 03:37:55.305  5677  5723 I jxcore-log: 
,09-15 03:37:55.311  5677  5723 I jxcore-log: # teardown
09-15 03:37:55.311  5677  5723 I jxcore-log: 
,09-15 03:37:55.365  5677  5723 I jxcore-log: # setup
09-15 03:37:55.365  5677  5723 I jxcore-log: 
,09-15 03:37:55.429  5677  5723 I jxcore-log: # 27. #startListeningForAdvertisements should fail if start not called
09-15 03:37:55.429  5677  5723 I jxcore-log: 
,09-15 03:37:55.518  5677  5723 I jxcore-log: ok 98 specific error should be returned
09-15 03:37:55.518  5677  5723 I jxcore-log: 
,09-15 03:37:55.522  5677  5723 I jxcore-log: # teardown
09-15 03:37:55.522  5677  5723 I jxcore-log: 
,09-15 03:37:55.585  5677  5723 I jxcore-log: ok 99 error should be null
09-15 03:37:55.585  5677  5723 I jxcore-log: 
,09-15 03:37:55.586  5677  5723 I jxcore-log: ok 100 error should be null
09-15 03:37:55.586  5677  5723 I jxcore-log: 
,09-15 03:37:55.590  5677  5723 I jxcore-log: # setup
09-15 03:37:55.590  5677  5723 I jxcore-log: 
,09-15 03:37:55.639  5677  5723 I jxcore-log: # 28. #startUpdateAdvertisingAndListening should fail if start not called
09-15 03:37:55.639  5677  5723 I jxcore-log: 
,09-15 03:37:55.732  5677  5723 I jxcore-log: ok 101 specific error should be returned
09-15 03:37:55.732  5677  5723 I jxcore-log: 
,09-15 03:37:55.736  5677  5723 I jxcore-log: # teardown
09-15 03:37:55.736  5677  5723 I jxcore-log: 
,09-15 03:37:55.776  5677  5723 I jxcore-log: ok 102 error should be null
09-15 03:37:55.776  5677  5723 I jxcore-log: 
,09-15 03:37:55.777  5677  5723 I jxcore-log: ok 103 error should be null
09-15 03:37:55.777  5677  5723 I jxcore-log: 
,09-15 03:37:55.780  5677  5723 I jxcore-log: # setup
09-15 03:37:55.780  5677  5723 I jxcore-log: 
,09-15 03:37:55.857  5677  5723 I jxcore-log: # 29. should be able to call #stopListeningForAdvertisements many times
09-15 03:37:55.857  5677  5723 I jxcore-log: 
,09-15 03:37:56.024  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 43991
09-15 03:37:56.024  5677  5723 I jxcore-log: 
,09-15 03:37:56.025  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:56.025  5677  5723 I jxcore-log: 
,09-15 03:37:56.026  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 42427
09-15 03:37:56.026  5677  5723 I jxcore-log: 
,09-15 03:37:56.030  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-15 03:37:56.030  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:37:56.030  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:37:56.030  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:56.032  5677  5723 I jxcore-log: ok 104 error should be null
09-15 03:37:56.032  5677  5723 I jxcore-log: 
09-15 03:37:56.032  5677  5723 I jxcore-log: ok 105 error should be null
09-15 03:37:56.032  5677  5723 I jxcore-log: 
,09-15 03:37:56.033  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-15 03:37:56.033  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:37:56.033  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:37:56.033  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:56.035  5677  5723 I jxcore-log: ok 106 error should be null
09-15 03:37:56.035  5677  5723 I jxcore-log: 
09-15 03:37:56.035  5677  5723 I jxcore-log: ok 107 error should be null
09-15 03:37:56.035  5677  5723 I jxcore-log: 
,09-15 03:37:56.046  5677  5723 I jxcore-log: # teardown
09-15 03:37:56.046  5677  5723 I jxcore-log: 
,09-15 03:37:56.096  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
09-15 03:37:56.096  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:37:56.096  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:56.096  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:56.098  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-15 03:37:56.098  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-15 03:37:56.098  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:37:56.098  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:56.102  5677  5723 I jxcore-log: ok 108 error should be null
09-15 03:37:56.102  5677  5723 I jxcore-log: 
09-15 03:37:56.103  5677  5723 I jxcore-log: ok 109 error should be null
09-15 03:37:56.103  5677  5723 I jxcore-log: 
,09-15 03:37:56.106  5677  5723 I jxcore-log: # setup
09-15 03:37:56.106  5677  5723 I jxcore-log: 
,09-15 03:37:56.174  5677  5723 I jxcore-log: # 30. should be able to call #startListeningForAdvertisements many times
09-15 03:37:56.174  5677  5723 I jxcore-log: 
,09-15 03:37:56.266  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 37848
09-15 03:37:56.266  5677  5723 I jxcore-log: 
,09-15 03:37:56.268  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:56.268  5677  5723 I jxcore-log: 
,09-15 03:37:56.273  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 40288
09-15 03:37:56.273  5677  5723 I jxcore-log: 
,09-15 03:37:56.282  5677  5723 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-15 03:37:56.286  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-15 03:37:56.286  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 03:37:56.286  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:37:56.286  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 03:37:56.286  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 03:37:56.286  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:56.287  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 03:37:56.291  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 03:37:56.291  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 03:37:56.296  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 03:37:56.296  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:56.297  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:37:56.301  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 03:37:56.301  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:37:56.301  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 03:37:56.302  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:56.304  5963  6003 D BtGatt.GattService: registerClient() - UUID=4195fadc-fb3f-4378-96ba-78d05351a1be
09-15 03:37:56.304  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=4195fadc-fb3f-4378-96ba-78d05351a1be, clientIf=5
09-15 03:37:56.305  5677  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 03:37:56.305  5963  5974 D BtGatt.GattService: start scan with filters
,09-15 03:37:56.308  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 03:37:56.309  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:37:56.309  5963  5982 D BtGatt.ScanManager: handling starting scan
09-15 03:37:56.309  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:37:56.309  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 03:37:56.313  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:37:56.313  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:37:56.313  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:37:56.314  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:37:56.317  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 03:37:56.317  5963  5979 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:37:56.318  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:56.318  5963  5982 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:37:56.325  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:37:56.325  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:56.325  5963  5982 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:37:56.325  5963  5982 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:37:56.336  5963  5979 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 03:37:56.336  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:56.342  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:37:56.342  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:56.814  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 03:37:56.814  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:37:56.814  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:37:56.823  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 03:37:56.823  5677  5723 I jxcore-log: 
,09-15 03:37:56.826  5677  5723 I jxcore-log: ok 110 error should be null
09-15 03:37:56.826  5677  5723 I jxcore-log: 
,09-15 03:37:56.829  5677  5723 I jxcore-log: ok 111 error should be null
09-15 03:37:56.829  5677  5723 I jxcore-log: 
,09-15 03:37:56.835  5677  5723 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-15 03:37:56.841  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-15 03:37:56.841  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-15 03:37:56.841  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 03:37:56.842  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:37:56.842  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
09-15 03:37:56.845  5677  5723 I jxcore-log: ok 112 error should be null
09-15 03:37:56.845  5677  5723 I jxcore-log: 
,09-15 03:37:56.846  5677  5723 I jxcore-log: ok 113 error should be null
09-15 03:37:56.846  5677  5723 I jxcore-log: 
,09-15 03:37:56.853  5677  5723 I jxcore-log: # teardown
09-15 03:37:56.853  5677  5723 I jxcore-log: 
,09-15 03:37:57.030  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:37:57.030  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:57.031  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:37:57.031  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 03:37:57.031  5677  5723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 03:37:57.031  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-15 03:37:57.031  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:37:57.031  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:37:57.031  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:37:57.031  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 03:37:57.032  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:37:57.032  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 03:37:57.037  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:37:57.040  5963  5999 D BtGatt.GattService: stopScan() - queue size =1
,09-15 03:37:57.042  5963  5973 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:37:57.043  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 03:37:57.044  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 03:37:57.044  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 03:37:57.045  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:37:57.045  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:37:57.049  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:57.049  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:37:57.049  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 03:37:57.049  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:37:57.050  5963  5963 D BtGatt.ScanManager: awakened up at time 504963
09-15 03:37:57.053  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-15 03:37:57.057  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 03:37:57.057  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:57.057  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:57.058  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 03:37:57.058  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:57.058  5963  5982 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:37:57.062  5677  5723 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-15 03:37:57.062  5677  5723 I jxcore-log: 
,09-15 03:37:57.068  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 03:37:57.068  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:57.068  5963  5982 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:37:57.078  5963  5979 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-15 03:37:57.078  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:57.078  5963  5979 D BtGatt.GattService: current time is 504991178891
09-15 03:37:57.078  5963  5979 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -72, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -72, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,09-15 03:37:57.078  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 03:37:57.079  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 03:37:57.079  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-15 03:37:57.079  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-15 03:37:57.558  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:37:57.559  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:57.559  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:37:57.562  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-15 03:37:57.563  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:37:57.563  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:37:57.563  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:37:57.566  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:57.566  5677  5723 I jxcore-log: 
,09-15 03:37:57.576  5677  5723 I jxcore-log: ok 114 error should be null
09-15 03:37:57.576  5677  5723 I jxcore-log: 
,09-15 03:37:57.577  5677  5723 I jxcore-log: ok 115 error should be null
09-15 03:37:57.577  5677  5723 I jxcore-log: 
,09-15 03:37:57.584  5677  5723 I jxcore-log: # setup
09-15 03:37:57.584  5677  5723 I jxcore-log: 
,09-15 03:37:57.660  5677  5723 I jxcore-log: # 31. should be able to call #startUpdateAdvertisingAndListening many times
09-15 03:37:57.660  5677  5723 I jxcore-log: 
,09-15 03:37:57.762  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 39390
09-15 03:37:57.762  5677  5723 I jxcore-log: 
,09-15 03:37:57.764  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:57.764  5677  5723 I jxcore-log: 
,09-15 03:37:57.769  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 43939
09-15 03:37:57.769  5677  5723 I jxcore-log: 
,09-15 03:37:57.785  5677  5723 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-15 03:37:57.788  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 43939, start advertisements: true
,09-15 03:37:57.788  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-15 03:37:57.788  5677  5723 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-15 03:37:57.788  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-15 03:37:57.788  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 03:37:57.788  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 03:37:57.788  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 03:37:57.788  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:57.790  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 03:37:57.791  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 03:37:57.791  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 03:37:57.791  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 03:37:57.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 03:37:57.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 03:37:57.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:57.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 03:37:57.792  5677  6085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:37:57.791  6003  6003 W Binder_6: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[37048]" dev="sockfs" ino=37048 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:37:57.791  6003  6003 W Binder_6: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[37048]" dev="sockfs" ino=37048 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:37:57.798  5677  6085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 03:37:57.798  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:37:57.798  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 03:37:57.804  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:37:57.805  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:57.805  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 03:37:57.807  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 03:37:57.807  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:37:57.807  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-15 03:37:57.808  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:37:57.808  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:37:57.808  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 03:37:57.808  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:57.810  5963  5974 D BtGatt.GattService: registerClient() - UUID=9ca65274-79f6-41d8-a8e8-c9e82a1aaf1e
09-15 03:37:57.810  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=9ca65274-79f6-41d8-a8e8-c9e82a1aaf1e, clientIf=5
,09-15 03:37:57.811  5677  5687 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-15 03:37:57.812  5963  5981 D BtGatt.AdvertiseManager: message : 0
09-15 03:37:57.813  5963  5981 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 03:37:57.822  5963  5979 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 03:37:57.827  5963  5979 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 03:37:57.828  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 03:37:57.828  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 03:37:57.829  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 03:37:57.830  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
09-15 03:37:57.830  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-15 03:37:57.830  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-15 03:37:57.830  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 03:37:57.830  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 03:37:57.830  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 03:37:57.830  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-15 03:37:57.832  5677  5723 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 46346
09-15 03:37:57.832  5677  5723 I jxcore-log: 
09-15 03:37:57.833  5677  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 03:37:57.833  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 03:37:58.334  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 03:37:58.335  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 03:37:58.335  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:37:58.345  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 03:37:58.345  5677  5723 I jxcore-log: 
,09-15 03:37:58.348  5677  5723 I jxcore-log: ok 116 error should be null
09-15 03:37:58.348  5677  5723 I jxcore-log: 
,09-15 03:37:58.350  5677  5723 I jxcore-log: ok 117 error should be null
09-15 03:37:58.350  5677  5723 I jxcore-log: 
,09-15 03:37:58.360  5677  5723 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-15 03:37:58.365  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 43939, start advertisements: true
,09-15 03:37:58.365  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 03:37:58.366  5677  5723 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-15 03:37:58.366  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-15 03:37:58.368  5963  5981 D BtGatt.AdvertiseManager: message : 1
09-15 03:37:58.369  5963  5981 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 03:37:58.382  5963  5979 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 03:37:58.382  5963  5979 D BtGatt.GattService: Client app is not null!
,09-15 03:37:58.384  5963  6000 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:37:58.385  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 03:37:58.386  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 03:37:58.386  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:37:58.386  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-15 03:37:58.386  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 03:37:58.386  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-15 03:37:58.387  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-15 03:37:58.387  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:37:58.387  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 03:37:58.389  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:58.393  5963  6003 D BtGatt.GattService: registerClient() - UUID=ad1e95a0-9fdf-437a-82ea-ed50898d0a86
,09-15 03:37:58.393  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=ad1e95a0-9fdf-437a-82ea-ed50898d0a86, clientIf=5
09-15 03:37:58.394  5677  5688 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 03:37:58.396  5963  5981 D BtGatt.AdvertiseManager: message : 0
,09-15 03:37:58.398  5963  5981 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 03:37:58.410  5963  5979 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 03:37:58.418  5963  5979 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 03:37:58.418  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 03:37:58.418  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 03:37:58.419  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:58.419  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 03:37:58.419  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 03:37:58.419  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 03:37:58.419  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-15 03:37:58.419  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 03:37:58.419  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 03:37:58.428  5677  5723 I jxcore-log: ok 118 error should be null
09-15 03:37:58.428  5677  5723 I jxcore-log: 
,09-15 03:37:58.430  5677  5723 I jxcore-log: ok 119 error should be null
09-15 03:37:58.430  5677  5723 I jxcore-log: 
,09-15 03:37:58.434  5677  5723 I jxcore-log: # teardown
09-15 03:37:58.434  5677  5723 I jxcore-log: 
,09-15 03:37:58.789  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:37:58.789  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:58.789  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-15 03:37:58.789  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:37:58.789  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 03:37:58.790  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-15 03:37:58.790  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 03:37:58.790  5677  6085 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 03:37:58.790  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-15 03:37:58.791  5677  6085 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 03:37:58.791  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 03:37:58.791  5677  6085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 03:37:58.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:37:58.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:37:58.791  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:37:58.791  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 03:37:58.791  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 03:37:58.791  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:37:58.793  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:37:58.794  5677  5723 D BluetoothLeScanner: could not find callback wrapper
09-15 03:37:58.794  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:37:58.794  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 03:37:58.796  5963  5981 D BtGatt.AdvertiseManager: message : 1
,09-15 03:37:58.797  5963  5981 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 03:37:58.809  5963  5979 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-15 03:37:58.809  5963  5979 D BtGatt.GattService: Client app is not null!
,09-15 03:37:58.811  5963  5999 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:37:58.812  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 03:37:58.812  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 03:37:58.812  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 03:37:58.812  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-15 03:37:58.812  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 03:37:58.814  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:37:58.815  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 03:37:58.815  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 03:37:58.816  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-15 03:37:58.819  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:58.819  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 03:37:58.820  5677  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 03:37:58.820  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:58.820  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:37:58.820  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:37:58.823  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-15 03:37:58.823  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-15 03:37:58.824  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-15 03:37:58.824  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:58.829  5677  5723 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-15 03:37:58.829  5677  5723 I jxcore-log: 
,09-15 03:37:58.835  5677  5723 I jxcore-log: ok 120 error should be null
09-15 03:37:58.835  5677  5723 I jxcore-log: 
,09-15 03:37:58.836  5677  5723 I jxcore-log: ok 121 error should be null
09-15 03:37:58.836  5677  5723 I jxcore-log: 
,09-15 03:37:58.842  5677  5723 I jxcore-log: # setup
09-15 03:37:58.842  5677  5723 I jxcore-log: 
,09-15 03:37:58.885  5677  5723 I jxcore-log: # 32. should be able to call #stopAdvertisingAndListening many times
09-15 03:37:58.885  5677  5723 I jxcore-log: 
,09-15 03:37:58.963  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 48512
09-15 03:37:58.963  5677  5723 I jxcore-log: 
,09-15 03:37:58.965  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:58.965  5677  5723 I jxcore-log: 
,09-15 03:37:58.970  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 48878
09-15 03:37:58.970  5677  5723 I jxcore-log: 
,09-15 03:37:58.975  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:37:58.975  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:58.975  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:58.975  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:58.979  5677  5723 I jxcore-log: ok 122 error should be null
09-15 03:37:58.979  5677  5723 I jxcore-log: 
,09-15 03:37:58.979  5677  5723 I jxcore-log: ok 123 error should be null
09-15 03:37:58.979  5677  5723 I jxcore-log: 
,09-15 03:37:58.982  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:37:58.982  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:58.982  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:58.982  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:58.986  5677  5723 I jxcore-log: ok 124 error should be null
09-15 03:37:58.986  5677  5723 I jxcore-log: 
,09-15 03:37:58.986  5677  5723 I jxcore-log: ok 125 error should be null
09-15 03:37:58.986  5677  5723 I jxcore-log: 
,09-15 03:37:58.992  5677  5723 I jxcore-log: # teardown
09-15 03:37:58.992  5677  5723 I jxcore-log: 
,09-15 03:37:59.060  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:37:59.060  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:59.060  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:37:59.060  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:59.063  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-15 03:37:59.064  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:37:59.064  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:37:59.064  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:59.069  5677  5723 I jxcore-log: ok 126 error should be null
09-15 03:37:59.069  5677  5723 I jxcore-log: 
,09-15 03:37:59.070  5677  5723 I jxcore-log: ok 127 error should be null
09-15 03:37:59.070  5677  5723 I jxcore-log: 
,09-15 03:37:59.075  5677  5723 I jxcore-log: # setup
09-15 03:37:59.075  5677  5723 I jxcore-log: 
,09-15 03:37:59.145  5677  5723 I jxcore-log: # 33. #start should fail if called twice in a row
09-15 03:37:59.145  5677  5723 I jxcore-log: 
,09-15 03:37:59.246  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 44768
09-15 03:37:59.246  5677  5723 I jxcore-log: 
,09-15 03:37:59.248  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:59.248  5677  5723 I jxcore-log: 
,09-15 03:37:59.251  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 47114
09-15 03:37:59.251  5677  5723 I jxcore-log: 
,09-15 03:37:59.255  5677  5723 I jxcore-log: ok 128 first call should succeed
09-15 03:37:59.255  5677  5723 I jxcore-log: 
,09-15 03:37:59.256  5677  5723 I jxcore-log: ok 129 first call should succeed
09-15 03:37:59.256  5677  5723 I jxcore-log: 
,09-15 03:37:59.260  5677  5723 I jxcore-log: ok 130 specific error should be returned
09-15 03:37:59.260  5677  5723 I jxcore-log: 
,09-15 03:37:59.263  5677  5723 I jxcore-log: # teardown
09-15 03:37:59.263  5677  5723 I jxcore-log: 
,09-15 03:37:59.320  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:37:59.325  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:37:59.325  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:37:59.325  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:37:59.326  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:59.329  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:37:59.329  5677  5723 I jxcore-log: 
,09-15 03:37:59.331  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-15 03:37:59.332  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:37:59.332  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-15 03:37:59.332  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:37:59.340  5677  5723 I jxcore-log: ok 131 error should be null
09-15 03:37:59.340  5677  5723 I jxcore-log: 
,09-15 03:37:59.341  5677  5723 I jxcore-log: ok 132 error should be null
09-15 03:37:59.341  5677  5723 I jxcore-log: 
,09-15 03:37:59.351  5677  5723 I jxcore-log: # setup
09-15 03:37:59.351  5677  5723 I jxcore-log: 
,09-15 03:37:59.422  5677  5723 I jxcore-log: # 34. does not emit duplicate discoveryAdvertisingStateUpdate
09-15 03:37:59.422  5677  5723 I jxcore-log: 
,09-15 03:37:59.511  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 38439
09-15 03:37:59.511  5677  5723 I jxcore-log: 
,09-15 03:37:59.514  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:37:59.514  5677  5723 I jxcore-log: 
,09-15 03:37:59.518  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 37859
09-15 03:37:59.518  5677  5723 I jxcore-log: 
,09-15 03:37:59.527  5677  5723 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-15 03:37:59.532  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 43939, start advertisements: false
09-15 03:37:59.532  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 03:37:59.532  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 03:37:59.532  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 03:37:59.532  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 03:37:59.532  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:37:59.532  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 03:37:59.537  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:37:59.538  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 03:37:59.542  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:37:59.542  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:37:59.543  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:37:59.546  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 03:37:59.547  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:37:59.547  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 03:37:59.548  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:37:59.551  5963  5973 D BtGatt.GattService: registerClient() - UUID=a81f9053-62a1-47e5-8d7b-9eafb46f6b67
09-15 03:37:59.552  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=a81f9053-62a1-47e5-8d7b-9eafb46f6b67, clientIf=5
,09-15 03:37:59.552  5677  5688 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 03:37:59.552  5963  5990 D BtGatt.GattService: start scan with filters
,09-15 03:37:59.557  5963  5982 D BtGatt.ScanManager: handling starting scan
,09-15 03:37:59.557  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 03:37:59.557  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:37:59.557  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:37:59.557  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 03:37:59.560  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:37:59.560  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 03:37:59.560  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 03:37:59.562  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 03:37:59.565  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
09-15 03:37:59.567  5963  5979 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:37:59.567  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:59.567  5963  5982 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:37:59.573  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:37:59.573  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:37:59.573  5963  5982 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:37:59.573  5963  5982 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:37:59.583  5963  5979 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 03:37:59.583  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:37:59.588  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:37:59.588  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:38:00.061  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 03:38:00.062  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 03:38:00.062  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:38:00.068  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 03:38:00.068  5677  5723 I jxcore-log: 
,09-15 03:38:00.087  5677  5723 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-15 03:38:00.091  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 37859, start advertisements: true
,09-15 03:38:00.091  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 03:38:00.091  5677  5723 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-15 03:38:00.092  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 03:38:00.092  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 03:38:00.094  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:38:00.096  5963  5974 D BtGatt.GattService: stopScan() - queue size =1
,09-15 03:38:00.097  5963  5999 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:38:00.098  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:38:00.098  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 03:38:00.098  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:38:00.098  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 03:38:00.098  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:38:00.098  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 03:38:00.099  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:38:00.103  5963  5963 D BtGatt.ScanManager: awakened up at time 508015
09-15 03:38:00.106  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 03:38:00.106  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.106  5963  6000 D BtGatt.GattService: registerClient() - UUID=79a36461-9fbd-4fcc-acce-9c856225183f
09-15 03:38:00.107  5963  5982 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:38:00.110  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=79a36461-9fbd-4fcc-acce-9c856225183f, clientIf=5
,09-15 03:38:00.111  5677  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 03:38:00.111  5963  5990 D BtGatt.GattService: start scan with filters
,09-15 03:38:00.114  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 03:38:00.114  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.114  5963  5982 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:38:00.115  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 03:38:00.116  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:38:00.116  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 03:38:00.116  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 03:38:00.116  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 03:38:00.116  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:38:00.117  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 03:38:00.117  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 03:38:00.117  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 03:38:00.118  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 03:38:00.118  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 03:38:00.118  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 03:38:00.118  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:38:00.118  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 03:38:00.119  5677  6086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 03:38:00.119  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:38:00.121  6003  6003 W Binder_6: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[37923]" dev="sockfs" ino=37923 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:38:00.121  6003  6003 W Binder_6: type=1400 audit(0.0:141): avc: denied { ioctl } for path="socket:[37923]" dev="sockfs" ino=37923 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 03:38:00.121  5963  5999 D BtGatt.GattService: stopScan() - queue size =0
09-15 03:38:00.122  5963  6000 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 03:38:00.122  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:38:00.122  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 03:38:00.122  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 03:38:00.122  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:38:00.122  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 03:38:00.125  5677  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 03:38:00.127  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:38:00.128  5963  5979 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
09-15 03:38:00.128  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.128  5963  5979 D BtGatt.GattService: current time is 508040934300
09-15 03:38:00.128  5963  5979 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -72, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -104, 11, -30, 21, 88, -39, 1, 0, -94, 3, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -102, -63, 5, 75, -127, -125, 45, -98, -50, 102, 3, 3, 3, -29, 16, 62, 86, -9, -102, 28, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 50, -35, 86, -77, -92, -11, 1, 0, -97, 2, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 66, 102, 3, 3, 2, -37, 21, 61, 92, 58, 70, 28, 6, 8, 116, 105, 115, 54, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-15 03:38:00.128  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:38:00.128  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-15 03:38:00.128  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -102, -63, 5, 75, -127, -125, 45, -98, -50, 102, 3, 3, 3, -29, 16, 62, 86, -9, -102, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-15 03:38:00.129  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 66, 102, 3, 3, 2, -37, 21, 61, 92, 58, 70, 6, 8, 116, 105, 115, 54, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-15 03:38:00.130  5963  5982 D BtGatt.ScanManager: handling starting scan
,09-15 03:38:00.130  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-15 03:38:00.130  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:38:00.130  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-15 03:38:00.131  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:38:00.131  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:38:00.131  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 03:38:00.131  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:38:00.134  5963  5973 D BtGatt.GattService: registerClient() - UUID=7c50fba5-dc24-49e0-a2cb-1890a35178f0
09-15 03:38:00.135  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=7c50fba5-dc24-49e0-a2cb-1890a35178f0, clientIf=5
09-15 03:38:00.135  5677  5688 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-15 03:38:00.136  5963  5979 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 03:38:00.136  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.136  5963  5981 D BtGatt.AdvertiseManager: message : 0
09-15 03:38:00.136  5963  5982 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:38:00.139  5963  5981 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 03:38:00.142  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:38:00.142  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.142  5963  5982 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:38:00.142  5963  5982 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:38:00.150  5963  5979 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 03:38:00.159  5963  5979 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 03:38:00.159  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:38:00.163  5963  5979 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 03:38:00.164  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 03:38:00.164  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 03:38:00.165  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:38:00.166  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 03:38:00.166  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 03:38:00.166  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:38:00.166  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 03:38:00.167  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 03:38:00.167  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 03:38:00.167  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 03:38:00.167  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-15 03:38:00.168  5677  5723 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 43859
09-15 03:38:00.168  5677  5723 I jxcore-log: 
09-15 03:38:00.169  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:38:00.169  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.170  5677  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 03:38:00.170  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 03:38:00.176  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 03:38:00.176  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.176  5963  5982 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:38:00.181  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 03:38:00.181  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:00.181  5963  5982 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:38:00.186  5963  5979 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 03:38:00.187  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:38:00.671  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 03:38:00.671  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 03:38:00.671  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:38:00.680  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 03:38:00.680  5677  5723 I jxcore-log: 
,09-15 03:38:00.691  5677  5723 I jxcore-log: ok 133 called only once
09-15 03:38:00.691  5677  5723 I jxcore-log: 
,09-15 03:38:00.692  5677  5723 I jxcore-log: ok 134 discovery state matches
09-15 03:38:00.692  5677  5723 I jxcore-log: 
09-15 03:38:00.693  5677  5723 I jxcore-log: ok 135 advertising state matches
09-15 03:38:00.693  5677  5723 I jxcore-log: 
,09-15 03:38:00.702  5677  5723 I jxcore-log: # teardown
09-15 03:38:00.702  5677  5723 I jxcore-log: 
,09-15 03:38:00.936  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:38:00.936  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:38:00.937  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-15 03:38:00.937  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:38:00.937  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 03:38:00.937  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 03:38:00.937  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 03:38:00.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-15 03:38:00.938  5677  6086 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 03:38:00.938  5677  6086 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 03:38:00.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 03:38:00.938  5677  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 03:38:00.938  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:38:00.938  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 03:38:00.938  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 03:38:00.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 03:38:00.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 03:38:00.939  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 03:38:00.941  5677  5723 D BluetoothAdapter: STATE_ON
09-15 03:38:00.942  5677  5723 D BluetoothLeScanner: could not find callback wrapper
09-15 03:38:00.942  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 03:38:00.942  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 03:38:00.944  5963  5981 D BtGatt.AdvertiseManager: message : 1
,09-15 03:38:00.945  5963  5981 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 03:38:00.959  5963  5979 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 03:38:00.960  5963  5979 D BtGatt.GattService: Client app is not null!
,09-15 03:38:00.961  5963  5973 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 03:38:00.962  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:38:00.962  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 03:38:00.962  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-15 03:38:00.963  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 03:38:00.963  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 03:38:00.965  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:38:00.966  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 03:38:00.966  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 03:38:00.967  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-15 03:38:00.970  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 03:38:00.970  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 03:38:00.970  5677  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 03:38:00.970  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:38:00.970  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 03:38:00.970  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:38:00.975  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-15 03:38:00.975  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:38:00.975  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-15 03:38:00.975  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:38:00.980  5677  5723 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
09-15 03:38:00.980  5677  5723 I jxcore-log: 
,09-15 03:38:00.984  5677  5723 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-15 03:38:00.984  5677  5723 I jxcore-log: 
,09-15 03:38:00.986  5677  5723 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-15 03:38:00.986  5677  5723 I jxcore-log: 
,09-15 03:38:00.991  5677  5723 I jxcore-log: ok 136 error should be null
09-15 03:38:00.991  5677  5723 I jxcore-log: 
,09-15 03:38:00.991  5677  5723 I jxcore-log: ok 137 error should be null
09-15 03:38:00.991  5677  5723 I jxcore-log: 
,09-15 03:38:00.996  5677  5723 I jxcore-log: # setup
09-15 03:38:00.996  5677  5723 I jxcore-log: 
,09-15 03:38:01.050  5677  5723 I jxcore-log: # 35. does not send duplicate availability changes
09-15 03:38:01.050  5677  5723 I jxcore-log: 
,09-15 03:38:01.137  5677  5723 I jxcore-log: ok 138 should be called once
09-15 03:38:01.137  5677  5723 I jxcore-log: 
,09-15 03:38:01.139  5677  5723 I jxcore-log: ok 139 should not have been called more than once
09-15 03:38:01.139  5677  5723 I jxcore-log: 
,09-15 03:38:01.142  5677  5723 I jxcore-log: # teardown
09-15 03:38:01.142  5677  5723 I jxcore-log: 
,09-15 03:38:01.190  5677  5723 I jxcore-log: ok 140 error should be null
09-15 03:38:01.190  5677  5723 I jxcore-log: 
09-15 03:38:01.191  5677  5723 I jxcore-log: ok 141 error should be null
09-15 03:38:01.191  5677  5723 I jxcore-log: 
09-15 03:38:01.193  5677  5723 I jxcore-log: # setup
09-15 03:38:01.193  5677  5723 I jxcore-log: 
,09-15 03:38:01.346  5677  5723 I jxcore-log: # 36. can get the network status
09-15 03:38:01.346  5677  5723 I jxcore-log: 
,09-15 03:38:01.391  5677  5723 I jxcore-log: ok 142 network status should have certain non-empty properties
09-15 03:38:01.391  5677  5723 I jxcore-log: 
,09-15 03:38:01.393  5677  5723 I jxcore-log: # teardown
09-15 03:38:01.393  5677  5723 I jxcore-log: 
,09-15 03:38:01.471  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:38:01.477  5677  5723 I jxcore-log: ok 143 error should be null
09-15 03:38:01.477  5677  5723 I jxcore-log: 
,09-15 03:38:01.478  5677  5723 I jxcore-log: ok 144 error should be null
09-15 03:38:01.478  5677  5723 I jxcore-log: 
,09-15 03:38:01.482  5677  5723 I jxcore-log: # setup
09-15 03:38:01.482  5677  5723 I jxcore-log: 
,09-15 03:38:01.485  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:38:01.485  5677  5723 I jxcore-log: 
,09-15 03:38:01.558  5677  5723 I jxcore-log: # 37. wifi peer is marked unavailable if announcements stop
09-15 03:38:01.558  5677  5723 I jxcore-log: 
,09-15 03:38:01.655  5677  5723 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
09-15 03:38:01.655  5677  5723 I jxcore-log: 
,09-15 03:38:01.689  5677  5723 I jxcore-log: ok 145 host address should match
09-15 03:38:01.689  5677  5723 I jxcore-log: 
09-15 03:38:01.689  5677  5723 I jxcore-log: ok 146 port should match
09-15 03:38:01.689  5677  5723 I jxcore-log: 
,09-15 03:38:02.167   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:03.168   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:03.655  5677  5723 I jxcore-log: ok 147 host address should be null
09-15 03:38:03.655  5677  5723 I jxcore-log: 
,09-15 03:38:03.657  5677  5723 I jxcore-log: ok 148 port should should be null
09-15 03:38:03.657  5677  5723 I jxcore-log: 
,09-15 03:38:03.673  5677  5723 I jxcore-log: # teardown
09-15 03:38:03.673  5677  5723 I jxcore-log: 
,09-15 03:38:03.723  5677  5723 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-15 03:38:03.723  5677  5723 I jxcore-log: 
,09-15 03:38:03.726  5677  5723 I jxcore-log: ok 149 error should be null
09-15 03:38:03.726  5677  5723 I jxcore-log: 
,09-15 03:38:03.726  5677  5723 I jxcore-log: ok 150 error should be null
09-15 03:38:03.726  5677  5723 I jxcore-log: 
,09-15 03:38:03.729  5677  5723 I jxcore-log: # setup
09-15 03:38:03.729  5677  5723 I jxcore-log: 
,09-15 03:38:03.866  5677  5723 I jxcore-log: # 38. Client to server request coordinated
09-15 03:38:03.866  5677  5723 I jxcore-log: 
,09-15 03:38:03.923  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 39983
09-15 03:38:03.923  5677  5723 I jxcore-log: 
,09-15 03:38:03.924  5677  5723 I jxcore-log: DEBUG createNativeListener: creating native server
09-15 03:38:03.924  5677  5723 I jxcore-log: 
,09-15 03:38:03.927  5677  5723 I jxcore-log: DEBUG createNativeListener: listening 43061
09-15 03:38:03.927  5677  5723 I jxcore-log: 
,09-15 03:38:03.929  5677  5723 I jxcore-log: ok 151 error should be null
09-15 03:38:03.929  5677  5723 I jxcore-log: 
,09-15 03:38:03.930  5677  5723 I jxcore-log: ok 152 error should be null
09-15 03:38:03.930  5677  5723 I jxcore-log: 
,09-15 03:38:03.998  5677  5723 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-15 03:38:04.001  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 43061, start advertisements: true
,09-15 03:38:04.001  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 03:38:04.001  5677  5723 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-15 03:38:04.001  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-15 03:38:04.002  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 03:38:04.002  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 03:38:04.002  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 03:38:04.002  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:38:04.002  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 03:38:04.003  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 03:38:04.003  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 03:38:04.003  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 03:38:04.004  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 03:38:04.004  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 03:38:04.004  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 03:38:04.004  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-15 03:38:04.009  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 03:38:04.009  5677  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 03:38:04.010  5677  6087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 03:38:04.012  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 03:38:04.014  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 03:38:04.014  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 03:38:04.016  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 03:38:04.016  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 03:38:04.016  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-15 03:38:04.017  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:38:04.017  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 03:38:04.017  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 03:38:04.018  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:38:04.014  5973  5973 W Binder_1: type=1400 audit(0.0:142): avc: denied { ioctl } for path="socket:[37934]" dev="sockfs" ino=37934 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 03:38:04.019  5677  6087 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 03:38:04.019  5963  5999 D BtGatt.GattService: registerClient() - UUID=ca50a131-2b4b-4c3e-bc9c-64ed0289fa1f
09-15 03:38:04.020  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=ca50a131-2b4b-4c3e-bc9c-64ed0289fa1f, clientIf=5
09-15 03:38:04.014  5973  5973 W Binder_1: type=1400 audit(0.0:143): avc: denied { ioctl } for path="socket:[37934]" dev="sockfs" ino=37934 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 03:38:04.021  5677  5688 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 03:38:04.021  5963  5981 D BtGatt.AdvertiseManager: message : 0
,09-15 03:38:04.025  5963  5981 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 03:38:04.033  5963  5979 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 03:38:04.038  5963  5979 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 03:38:04.038  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 03:38:04.038  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:38:04.039  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:38:04.039  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 03:38:04.039  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-15 03:38:04.040  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 03:38:04.040  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 03:38:04.040  5677  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 03:38:04.040  5677  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 03:38:04.040  5677  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-15 03:38:04.041  5677  5723 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 41547
09-15 03:38:04.041  5677  5723 I jxcore-log: 
09-15 03:38:04.042  5677  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 03:38:04.042  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 03:38:04.169   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:04.543  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 03:38:04.544  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 03:38:04.544  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:38:04.551  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 03:38:04.551  5677  5723 I jxcore-log: 
,09-15 03:38:04.560  5677  5723 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-15 03:38:04.567  5677  5723 I io.jxcore.node.ConnectionHelper: start: Port number: 43061, start advertisements: false
,09-15 03:38:04.567  5677  5723 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 03:38:04.567  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
09-15 03:38:04.568  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 03:38:04.568  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 03:38:04.568  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 03:38:04.568  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 03:38:04.569  5963  5981 D BtGatt.AdvertiseManager: message : 1
09-15 03:38:04.571  5963  5981 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 03:38:04.580  5963  5979 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-15 03:38:04.581  5963  5979 D BtGatt.GattService: Client app is not null!
,09-15 03:38:04.582  5963  5990 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:38:04.583  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 03:38:04.583  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 03:38:04.583  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 03:38:04.583  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 03:38:04.583  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 03:38:04.586  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:38:04.586  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:38:04.590  5677  5723 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 03:38:04.595  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 03:38:04.595  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 03:38:04.595  5677  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 03:38:04.596  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:38:04.599  5963  6003 D BtGatt.GattService: registerClient() - UUID=ac2ca1f8-dd3f-44a4-952e-7c1206d9df98
,09-15 03:38:04.600  5963  5979 D BtGatt.GattService: onClientRegistered() - UUID=ac2ca1f8-dd3f-44a4-952e-7c1206d9df98, clientIf=5
09-15 03:38:04.600  5677  5688 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 03:38:04.600  5963  5973 D BtGatt.GattService: start scan with filters
,09-15 03:38:04.603  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 03:38:04.603  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 03:38:04.604  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 03:38:04.604  5963  5982 D BtGatt.ScanManager: handling starting scan
09-15 03:38:04.604  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 03:38:04.606  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:38:04.606  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 03:38:04.606  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 03:38:04.608  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 03:38:04.610  5677  5723 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 03:38:04.612  5963  5979 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 03:38:04.612  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:04.612  5963  5982 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 03:38:04.619  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 03:38:04.619  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:04.620  5963  5982 D BtGatt.ScanManager: Starting BLE batch scan
09-15 03:38:04.620  5963  5982 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 03:38:04.629  5963  5979 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 03:38:04.630  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:38:04.635  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 03:38:04.635  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 03:38:05.107  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 03:38:05.108  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 03:38:05.108  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:38:05.112  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 03:38:05.112  5677  5723 I jxcore-log: 
,09-15 03:38:05.115  5677  5723 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
09-15 03:38:05.115  5677  5723 I jxcore-log: 
,09-15 03:38:05.170   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:05.594  5677  5723 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.118, 192.168.1.118, 46298
09-15 03:38:05.594  5677  5723 I jxcore-log: 
,09-15 03:38:05.660  5677  5723 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:tcp, 192.168.1.137, 192.168.1.137, 40767
09-15 03:38:05.660  5677  5723 I jxcore-log: 
,09-15 03:38:06.171   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:07.171   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:38:08.926  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-15 03:38:08.927  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:38:08.927  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-15 03:38:08.927  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
09-15 03:38:08.928  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 03:38:08.928  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 03:38:08.931  5677  5723 D BluetoothAdapter: STATE_ON
,09-15 03:38:08.934  5963  5990 D BtGatt.GattService: stopScan() - queue size =1
,09-15 03:38:08.937  5963  6003 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 03:38:08.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 03:38:08.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 03:38:08.938  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 03:38:08.938  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 03:38:08.939  5677  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 03:38:08.942  5677  5723 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 03:38:08.943  5677  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 03:38:08.947  5963  5963 D BtGatt.ScanManager: awakened up at time 516860
,09-15 03:38:08.953  5963  5979 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 03:38:08.953  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:08.953  5963  5982 D BtGatt.ScanManager: stopping BLe Batch
,09-15 03:38:08.963  5963  5979 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 03:38:08.963  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:08.963  5963  5982 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 03:38:08.988  5963  5979 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-15 03:38:08.988  5963  5979 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 03:38:08.988  5963  5979 D BtGatt.GattService: current time is 516901217995
09-15 03:38:08.988  5963  5979 D BtGatt.GattService: Batch record : [-116, 54, 105, 7, 40, 90, 1, -128, -56, 86, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 96, -29, -84, 57, 124, 41, 0, 18, 8, 95, 93, 22, 124, 1, -128, -54, 85, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 37, -47, 14, -113, 116, -46, 1, -128, -73, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 50, -35, 86, -77, -92, -11, 1, 0, -93, 75, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 72, 102, 3, 3, 2, -37, 21, 61, 96, 22, -80, 28, 6, 8, 116, 105, 115, 54, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -74, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -73, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 03:38:08.989  5963  5979 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 96, -29, -84, 57, 124, 41]
09-15 03:38:08.989  5963  5979 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
,09-15 03:38:08.989  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-15 03:38:08.990  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 03:38:08.990  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 72, 102, 3, 3, 2, -37, 21, 61, 96, 22, -80, 6, 8, 116, 105, 115, 54, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-15 03:38:08.991  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 03:38:08.991  5963  5979 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-15 03:38:09.444  5677  5677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 03:38:09.444  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:38:09.444  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 03:38:09.461  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:38:09.461  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 03:38:09.462  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:38:09.462  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 03:38:09.462  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 03:38:09.462  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-15 03:38:09.462  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-15 03:38:09.463  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-15 03:38:09.463  5677  6087 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 03:38:09.463  5677  5723 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 03:38:09.463  5677  6087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 03:38:09.463  5677  5723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 03:38:09.463  5677  6087 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 03:38:09.463  5677  5723 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 03:38:09.463  5677  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-15 03:38:09.466  5677  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 03:38:09.470  5677  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:38:09.471  5677  5677 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 03:38:09.471  5677  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-15 03:38:09.482  5677  5723 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 03:38:09.482  5677  5723 I jxcore-log: 
,09-15 03:38:09.486  5677  5723 I jxcore-log: ok 153 Peer made successful https requests to all peers
09-15 03:38:09.486  5677  5723 I jxcore-log: 
09-15 03:38:09.488  5677  5723 I jxcore-log: ok 154 Peer received right amount of https requests
09-15 03:38:09.488  5677  5723 I jxcore-log: 
,09-15 03:38:09.489  5677  5723 I jxcore-log: ok 155 HTTPS server received zero PSK Identities. Count:0
09-15 03:38:09.489  5677  5723 I jxcore-log: 
,09-15 03:38:09.499  5677  5723 I jxcore-log: # teardown
09-15 03:38:09.499  5677  5723 I jxcore-log: 
,09-15 03:38:09.589  5677  5723 I jxcore-log: INFO testThaliNotification: Participants:3 Peers Replied to us:2 Peers requested to:2
09-15 03:38:09.589  5677  5723 I jxcore-log: 
,09-15 03:38:09.601  5677  5723 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-15 03:38:09.602  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 03:38:09.602  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 03:38:09.602  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:38:09.606  5677  5723 I jxcore-log: # setup
09-15 03:38:09.606  5677  5723 I jxcore-log: 
,09-15 03:38:09.609  5677  5723 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-15 03:38:09.610  5677  5723 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-15 03:38:09.610  5677  5723 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 03:38:09.610  5677  5723 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 03:38:09.794  5677  5723 I jxcore-log: # 39. Test BEACONS_RETRIEVED_AND_PARSED locally
09-15 03:38:09.794  5677  5723 I jxcore-log: 
,09-15 03:38:09.960  5677  5723 I jxcore-log: ok 156 peerIdentifier should be identifier
09-15 03:38:09.960  5677  5723 I jxcore-log: 
,09-15 03:38:09.961  5677  5723 I jxcore-log: ok 157 Response should be BEACONS_RETRIEVED_AND_PARSED
09-15 03:38:09.961  5677  5723 I jxcore-log: 
,09-15 03:38:09.963  5677  5723 I jxcore-log: ok 158 good beacon
09-15 03:38:09.963  5677  5723 I jxcore-log: 
09-15 03:38:09.965  5677  5723 I jxcore-log: ok 159 good preAmble
09-15 03:38:09.965  5677  5723 I jxcore-log: 
09-15 03:38:09.965  5677  5723 I jxcore-log: ok 160 public keys match!
09-15 03:38:09.965  5677  5723 I jxcore-log: 
,09-15 03:38:09.970  5677  5723 I jxcore-log: ok 161 must return null after successful call
09-15 03:38:09.970  5677  5723 I jxcore-log: 
,09-15 03:38:09.971  5677  5723 I jxcore-log: ok 162 Once start returns the action should be in KILLED state
09-15 03:38:09.971  5677  5723 I jxcore-log: 
,09-15 03:38:09.985  5677  5723 I jxcore-log: # teardown
09-15 03:38:09.985  5677  5723 I jxcore-log: 
,09-15 03:38:10.131  5677  5723 I jxcore-log: # setup
09-15 03:38:10.131  5677  5723 I jxcore-log: 
,09-15 03:38:10.315  5677  5723 I jxcore-log: # 40. Test HTTP_BAD_RESPONSE locally
09-15 03:38:10.315  5677  5723 I jxcore-log: 
,09-15 03:38:10.408  5677  5723 I jxcore-log: ok 163 Response should be HTTP_BAD_RESPONSE
09-15 03:38:10.408  5677  5723 I jxcore-log: 
,09-15 03:38:10.412  5677  5723 I jxcore-log: ok 164 must return null after successful call
09-15 03:38:10.412  5677  5723 I jxcore-log: 
,09-15 03:38:10.427  5677  5723 I jxcore-log: # teardown
09-15 03:38:10.427  5677  5723 I jxcore-log: 
,09-15 03:38:10.565  5677  5723 I jxcore-log: # setup
09-15 03:38:10.565  5677  5723 I jxcore-log: 
,09-15 03:38:10.749  5677  5723 I jxcore-log: # 41. Test NETWORK_PROBLEM locally
09-15 03:38:10.749  5677  5723 I jxcore-log: 
,09-15 03:38:10.911  5677  5723 I jxcore-log: ok 165 Response should be NETWORK_PROBLEM
09-15 03:38:10.911  5677  5723 I jxcore-log: 
,09-15 03:38:10.916  5677  5723 I jxcore-log: ok 166 reject reason should be: Could not establish TCP connection
09-15 03:38:10.916  5677  5723 I jxcore-log: 
,09-15 03:38:10.926  5677  5723 I jxcore-log: # teardown
09-15 03:38:10.926  5677  5723 I jxcore-log: 
,09-15 03:38:11.053  5677  5723 I jxcore-log: # setup
09-15 03:38:11.053  5677  5723 I jxcore-log: 
,09-15 03:38:11.216  5677  5723 I jxcore-log: # 42. Call the start two times
09-15 03:38:11.216  5677  5723 I jxcore-log: 
,09-15 03:38:11.296  5677  5723 I jxcore-log: ok 167 Call start once
09-15 03:38:11.296  5677  5723 I jxcore-log: 
,09-15 03:38:11.436  5677  5723 I jxcore-log: ok 168 Response should be BEACONS_RETRIEVED_AND_PARSED
09-15 03:38:11.436  5677  5723 I jxcore-log: 
,09-15 03:38:11.439  5677  5723 I jxcore-log: ok 169 must return null after successful call.
09-15 03:38:11.439  5677  5723 I jxcore-log: 
,09-15 03:38:11.452  5677  5723 I jxcore-log: # teardown
09-15 03:38:11.452  5677  5723 I jxcore-log: 
,09-15 03:38:11.498  5677  5723 I jxcore-log: # setup
09-15 03:38:11.498  5677  5723 I jxcore-log: 
,09-15 03:38:11.658  5677  5723 I jxcore-log: # 43. Call the kill before calling the start
09-15 03:38:11.658  5677  5723 I jxcore-log: 
,09-15 03:38:11.691  5677  5723 I jxcore-log: ok 170 Should be Killed
09-15 03:38:11.691  5677  5723 I jxcore-log: 
,09-15 03:38:11.697  5677  5723 I jxcore-log: ok 171 Start after killed
09-15 03:38:11.697  5677  5723 I jxcore-log: 
,09-15 03:38:11.702  5677  5723 I jxcore-log: # teardown
09-15 03:38:11.702  5677  5723 I jxcore-log: 
,09-15 03:38:11.801  5677  5723 I jxcore-log: # setup
09-15 03:38:11.801  5677  5723 I jxcore-log: 
,09-15 03:38:11.983  5677  5723 I jxcore-log: # 44. Call the kill immediately after the start
09-15 03:38:11.983  5677  5723 I jxcore-log: 
,09-15 03:38:12.087  5677  5723 I jxcore-log: ok 172 Should be KILLED
09-15 03:38:12.087  5677  5723 I jxcore-log: 
,09-15 03:38:12.090  5677  5723 I jxcore-log: ok 173 must return null after successful kill
09-15 03:38:12.090  5677  5723 I jxcore-log: 
,09-15 03:38:12.098  5677  5723 I jxcore-log: # teardown
09-15 03:38:12.098  5677  5723 I jxcore-log: 
,09-15 03:38:12.175  5677  5723 I jxcore-log: # setup
09-15 03:38:12.175  5677  5723 I jxcore-log: 
,09-15 03:38:12.324  5677  5723 I jxcore-log: # 45. Call the kill while waiting a response from the server
09-15 03:38:12.324  5677  5723 I jxcore-log: 
,09-15 03:38:14.414  5677  5723 I jxcore-log: ok 174 Should be KILLED
09-15 03:38:14.414  5677  5723 I jxcore-log: 
,09-15 03:38:14.423  5677  5723 I jxcore-log: ok 175 must return null after successful kill
09-15 03:38:14.423  5677  5723 I jxcore-log: 
,09-15 03:38:14.445  5677  5723 I jxcore-log: # teardown
09-15 03:38:14.445  5677  5723 I jxcore-log: 
,09-15 03:38:15.177  5677  5723 I jxcore-log: # setup
09-15 03:38:15.177  5677  5723 I jxcore-log: 
,09-15 03:38:15.974  5677  5723 I jxcore-log: # 46. Test to exceed the max content size locally
09-15 03:38:15.974  5677  5723 I jxcore-log: 
,09-15 03:38:16.091  5677  5723 I jxcore-log: ok 176 HTTP_BAD_RESPONSE should be response when content size is exceeded
09-15 03:38:16.091  5677  5723 I jxcore-log: 
,09-15 03:38:16.107  5677  5723 I jxcore-log: ok 177 must return null after successful call
09-15 03:38:16.107  5677  5723 I jxcore-log: 
,09-15 03:38:16.128  5677  5723 I jxcore-log: # teardown
09-15 03:38:16.128  5677  5723 I jxcore-log: 
,09-15 03:38:16.228  5677  5723 I jxcore-log: # setup
09-15 03:38:16.228  5677  5723 I jxcore-log: 
,09-15 03:38:16.436  5677  5723 I jxcore-log: # 47. Close the server socket while the client is waiting a response from the server. Local test.
09-15 03:38:16.436  5677  5723 I jxcore-log: 
,09-15 03:38:18.489  5677  5723 I jxcore-log: ok 178 Should be NETWORK_PROBLEM caused closing server socket
09-15 03:38:18.489  5677  5723 I jxcore-log: 
,09-15 03:38:18.495  5677  5723 I jxcore-log: ok 179 Should be Could not establish TCP connection
09-15 03:38:18.495  5677  5723 I jxcore-log: 
,09-15 03:38:18.505  5677  5723 I jxcore-log: # teardown
09-15 03:38:18.505  5677  5723 I jxcore-log: 
,09-15 03:38:18.653  5677  5723 I jxcore-log: # setup
09-15 03:38:18.653  5677  5723 I jxcore-log: 
,09-15 03:38:18.826  5677  5723 I jxcore-log: # 48. Close the client socket while the client is waiting a response from the server. Local test.
09-15 03:38:18.826  5677  5723 I jxcore-log: 
,09-15 03:38:20.892  5677  5723 I jxcore-log: ok 180 Should be NETWORK_PROBLEM caused closing client socket
09-15 03:38:20.892  5677  5723 I jxcore-log: 
,09-15 03:38:20.903  5677  5723 I jxcore-log: ok 181 Should be Could not establish TCP connection
09-15 03:38:20.903  5677  5723 I jxcore-log: 
,09-15 03:38:20.919  5677  5723 I jxcore-log: # teardown
09-15 03:38:20.919  5677  5723 I jxcore-log: 
,09-15 03:38:20.994  5677  5723 I jxcore-log: # setup
09-15 03:38:20.994  5677  5723 I jxcore-log: 
,09-15 03:38:21.075  5677  5723 I jxcore-log: # 49. #generatePreambleAndBeacons bad args
09-15 03:38:21.075  5677  5723 I jxcore-log: 
,09-15 03:38:21.182  5677  5723 I jxcore-log: ok 182 publicKeysToNotify cannot be null
09-15 03:38:21.182  5677  5723 I jxcore-log: 
,09-15 03:38:21.185  5677  5723 I jxcore-log: ok 183 ecdh for local device cannot be null
09-15 03:38:21.185  5677  5723 I jxcore-log: 
09-15 03:38:21.188  5677  5723 I jxcore-log: ok 184 milliseconds cannot be less than 0
09-15 03:38:21.188  5677  5723 I jxcore-log: 
,09-15 03:38:21.191  5677  5723 I jxcore-log: ok 185 milliseconds cannot be 0
09-15 03:38:21.191  5677  5723 I jxcore-log: 
,09-15 03:38:21.195  5677  5723 I jxcore-log: ok 186 milliseconds cannot be greater than one_day
09-15 03:38:21.195  5677  5723 I jxcore-log: 
,09-15 03:38:21.197  5677  5723 I jxcore-log: # teardown
09-15 03:38:21.197  5677  5723 I jxcore-log: 
,09-15 03:38:21.262  5677  5723 I jxcore-log: # setup
09-15 03:38:21.262  5677  5723 I jxcore-log: 
,09-15 03:38:21.339  5677  5723 I jxcore-log: # 50. #generatePreambleAndBeacons empty keys to notify
09-15 03:38:21.339  5677  5723 I jxcore-log: 
,09-15 03:38:21.435  5677  5723 I jxcore-log: ok 187 should be equal
09-15 03:38:21.435  5677  5723 I jxcore-log: 
,09-15 03:38:21.439  5677  5723 I jxcore-log: # teardown
09-15 03:38:21.439  5677  5723 I jxcore-log: 
,09-15 03:38:21.484  5677  5723 I jxcore-log: # setup
09-15 03:38:21.484  5677  5723 I jxcore-log: 
,09-15 03:38:21.557  5677  5723 I jxcore-log: # 51. #generatePreambleAndBeacons multiple keys to notify
09-15 03:38:21.557  5677  5723 I jxcore-log: 
,09-15 03:38:21.741  5677  5723 I jxcore-log: ok 188 should be equal
09-15 03:38:21.741  5677  5723 I jxcore-log: 
,09-15 03:38:21.742  5677  5723 I jxcore-log: ok 189 should be equal
09-15 03:38:21.742  5677  5723 I jxcore-log: 
09-15 03:38:21.743  5677  5723 I jxcore-log: ok 190 (unnamed assert)
09-15 03:38:21.743  5677  5723 I jxcore-log: 
09-15 03:38:21.743  5677  5723 I jxcore-log: ok 191 should be equal
09-15 03:38:21.743  5677  5723 I jxcore-log: 
,09-15 03:38:21.745  5677  5723 I jxcore-log: # teardown
09-15 03:38:21.745  5677  5723 I jxcore-log: 
,09-15 03:38:21.787  5677  5723 I jxcore-log: # setup
09-15 03:38:21.787  5677  5723 I jxcore-log: 
,09-15 03:38:21.864  5677  5723 I jxcore-log: # 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
09-15 03:38:21.864  5677  5723 I jxcore-log: 
,09-15 03:38:21.964  5677  5723 I jxcore-log: ok 192 should throw
09-15 03:38:21.964  5677  5723 I jxcore-log: 
,09-15 03:38:21.966  5677  5723 I jxcore-log: # teardown
09-15 03:38:21.966  5677  5723 I jxcore-log: 
,09-15 03:38:22.036  5677  5723 I jxcore-log: # setup
09-15 03:38:22.036  5677  5723 I jxcore-log: 
,09-15 03:38:22.123  5677  5723 I jxcore-log: # 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble
09-15 03:38:22.123  5677  5723 I jxcore-log: 
,09-15 03:38:22.209  5677  5723 I jxcore-log: ok 193 Preamble expiration must be a 64 bit integer
09-15 03:38:22.209  5677  5723 I jxcore-log: 
,09-15 03:38:22.212  5677  5723 I jxcore-log: # teardown
09-15 03:38:22.212  5677  5723 I jxcore-log: 
,09-15 03:38:22.267  5677  5723 I jxcore-log: # setup
09-15 03:38:22.267  5677  5723 I jxcore-log: 
,09-15 03:38:22.333  5677  5723 I jxcore-log: # 54. #parseBeacons expiration out of range lower
09-15 03:38:22.333  5677  5723 I jxcore-log: 
,09-15 03:38:22.443  5677  5723 I jxcore-log: ok 194 Expiration out of range
09-15 03:38:22.443  5677  5723 I jxcore-log: 
,09-15 03:38:22.445  5677  5723 I jxcore-log: # teardown
09-15 03:38:22.445  5677  5723 I jxcore-log: 
,09-15 03:38:22.498  5677  5723 I jxcore-log: # setup
09-15 03:38:22.498  5677  5723 I jxcore-log: 
,09-15 03:38:22.552  5677  5723 I jxcore-log: # 55. #parseBeacons expiration out of range lower
09-15 03:38:22.552  5677  5723 I jxcore-log: 
,09-15 03:38:22.651  5677  5723 I jxcore-log: ok 195 Expiration out of range
09-15 03:38:22.651  5677  5723 I jxcore-log: 
,09-15 03:38:22.653  5677  5723 I jxcore-log: # teardown
09-15 03:38:22.653  5677  5723 I jxcore-log: 
,09-15 03:38:22.716  5677  5723 I jxcore-log: # setup
09-15 03:38:22.716  5677  5723 I jxcore-log: 
,09-15 03:38:22.810  5677  5723 I jxcore-log: # 56. #parseBeacons no beacons returns null
09-15 03:38:22.810  5677  5723 I jxcore-log: 
,09-15 03:38:22.885  5677  5723 I jxcore-log: ok 196 should be equal
09-15 03:38:22.885  5677  5723 I jxcore-log: 
,09-15 03:38:22.887  5677  5723 I jxcore-log: # teardown
09-15 03:38:22.887  5677  5723 I jxcore-log: 
,09-15 03:38:22.958  5677  5723 I jxcore-log: # setup
09-15 03:38:22.958  5677  5723 I jxcore-log: 
,09-15 03:38:23.010  5677  5723 I jxcore-log: # 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
09-15 03:38:23.010  5677  5723 I jxcore-log: 
,09-15 03:38:23.103  5677  5723 I jxcore-log: ok 197 Malformed encrypted beacon key ID
09-15 03:38:23.103  5677  5723 I jxcore-log: 
,09-15 03:38:23.109  5677  5723 I jxcore-log: # teardown
09-15 03:38:23.109  5677  5723 I jxcore-log: 
,09-15 03:38:23.156  5677  5723 I jxcore-log: # setup
09-15 03:38:23.156  5677  5723 I jxcore-log: 
,09-15 03:38:23.222  5677  5723 I jxcore-log: # 58. #parseBeacons addressBookCallback fails decrypt
09-15 03:38:23.222  5677  5723 I jxcore-log: 
,09-15 03:38:23.418  5677  5723 I jxcore-log: ok 198 should be equal
09-15 03:38:23.418  5677  5723 I jxcore-log: 
,09-15 03:38:23.420  5677  5723 I jxcore-log: # teardown
09-15 03:38:23.420  5677  5723 I jxcore-log: 
,09-15 03:38:23.456  5677  5723 I jxcore-log: # setup,
09-15 03:38:23.456  5677  5723 I jxcore-log: 
,09-15 03:38:23.534  5677  5723 I jxcore-log: # 59. #parseBeacons addressBookCallback returns no matches
09-15 03:38:23.534  5677  5723 I jxcore-log: 
,09-15 03:38:23.768  5677  5723 I jxcore-log: ok 199 should be equal
09-15 03:38:23.768  5677  5723 I jxcore-log: 
,09-15 03:38:23.768  5677  5723 I jxcore-log: ok 200 should be equal
09-15 03:38:23.768  5677  5723 I jxcore-log: 
,09-15 03:38:23.770  5677  5723 I jxcore-log: # teardown
09-15 03:38:23.770  5677  5723 I jxcore-log: 
,09-15 03:38:23.797  5677  5723 I jxcore-log: # setup
09-15 03:38:23.797  5677  5723 I jxcore-log: 
,09-15 03:38:23.857  5677  5723 I jxcore-log: # 60. #parseBeacons addressBookCallback returns spurious match
09-15 03:38:23.857  5677  5723 I jxcore-log: 
,09-15 03:38:24.059  5677  5723 I jxcore-log: ok 201 should be equal
09-15 03:38:24.059  5677  5723 I jxcore-log: 
,09-15 03:38:24.060  5677  5723 I jxcore-log: ok 202 should be equal
09-15 03:38:24.060  5677  5723 I jxcore-log: 
09-15 03:38:24.061  5677  5723 I jxcore-log: # teardown
09-15 03:38:24.061  5677  5723 I jxcore-log: 
,09-15 03:38:24.089  5677  5723 I jxcore-log: # setup
09-15 03:38:24.089  5677  5723 I jxcore-log: 
,09-15 03:38:24.157  5677  5723 I jxcore-log: # 61. #parseBeacons addressBookCallback returns public key
09-15 03:38:24.157  5677  5723 I jxcore-log: 
,09-15 03:38:24.354  5677  5723 I jxcore-log: ok 203 right number of calls to address book
09-15 03:38:24.354  5677  5723 I jxcore-log: 
09-15 03:38:24.355  5677  5723 I jxcore-log: ok 204 good preAmble
09-15 03:38:24.355  5677  5723 I jxcore-log: 
,09-15 03:38:24.355  5677  5723 I jxcore-log: ok 205 good unencryptedKeyId
09-15 03:38:24.355  5677  5723 I jxcore-log: 
09-15 03:38:24.355  5677  5723 I jxcore-log: ok 206 good beacon
09-15 03:38:24.355  5677  5723 I jxcore-log: 
,09-15 03:38:24.356  5677  5723 I jxcore-log: # teardown
09-15 03:38:24.356  5677  5723 I jxcore-log: 
,09-15 03:38:24.388  5677  5723 I jxcore-log: # setup
09-15 03:38:24.388  5677  5723 I jxcore-log: 
,09-15 03:38:24.457  5677  5723 I jxcore-log: # 62. validate generatePskIdentityField
09-15 03:38:24.457  5677  5723 I jxcore-log: 
,09-15 03:38:24.534  5677  5723 I jxcore-log: ok 207 decoded buffers match
09-15 03:38:24.534  5677  5723 I jxcore-log: 
,09-15 03:38:24.539  5677  5723 I jxcore-log: # teardown
09-15 03:38:24.539  5677  5723 I jxcore-log: 
,09-15 03:38:24.610  5677  5723 I jxcore-log: # setup
09-15 03:38:24.610  5677  5723 I jxcore-log: 
,09-15 03:38:24.682  5677  5723 I jxcore-log: # 63. validate generatePskSecret
09-15 03:38:24.682  5677  5723 I jxcore-log: 
,09-15 03:38:24.792  5677  5723 I jxcore-log: ok 208 secrets match
09-15 03:38:24.792  5677  5723 I jxcore-log: 
,09-15 03:38:24.795  5677  5723 I jxcore-log: # teardown
09-15 03:38:24.795  5677  5723 I jxcore-log: 
,09-15 03:38:24.832  5677  5723 I jxcore-log: # setup
09-15 03:38:24.832  5677  5723 I jxcore-log: 
,09-15 03:38:24.912  5677  5723 I jxcore-log: # 64. validate generatePskSecrets
09-15 03:38:24.912  5677  5723 I jxcore-log: 
,09-15 03:38:25.112  5677  5723 I jxcore-log: ok 209 Matching numbers
09-15 03:38:25.112  5677  5723 I jxcore-log: 
,09-15 03:38:25.118  5677  5723 I jxcore-log: ok 210 We have an entry!
09-15 03:38:25.118  5677  5723 I jxcore-log: 
09-15 03:38:25.118  5677  5723 I jxcore-log: ok 211 keys match
09-15 03:38:25.118  5677  5723 I jxcore-log: 
09-15 03:38:25.118  5677  5723 I jxcore-log: ok 212 secrets match
09-15 03:38:25.118  5677  5723 I jxcore-log: 
,09-15 03:38:25.124  5677  5723 I jxcore-log: ok 213 We have an entry!
09-15 03:38:25.124  5677  5723 I jxcore-log: 
,09-15 03:38:25.124  5677  5723 I jxcore-log: ok 214 keys match
09-15 03:38:25.124  5677  5723 I jxcore-log: 
09-15 03:38:25.124  5677  5723 I jxcore-log: ok 215 secrets match
09-15 03:38:25.124  5677  5723 I jxcore-log: 
,09-15 03:38:25.130  5677  5723 I jxcore-log: ok 216 We have an entry!
09-15 03:38:25.130  5677  5723 I jxcore-log: 
,09-15 03:38:25.130  5677  5723 I jxcore-log: ok 217 keys match
09-15 03:38:25.130  5677  5723 I jxcore-log: 
09-15 03:38:25.130  5677  5723 I jxcore-log: ok 218 secrets match
09-15 03:38:25.130  5677  5723 I jxcore-log: 
,09-15 03:38:25.131  5677  5723 I jxcore-log: # teardown
09-15 03:38:25.131  5677  5723 I jxcore-log: 
,09-15 03:38:25.210  5677  5723 I jxcore-log: # setup
09-15 03:38:25.210  5677  5723 I jxcore-log: 
,09-15 03:38:25.266  5677  5723 I jxcore-log: # 65. validate generateBeaconStreamAndSecrets
09-15 03:38:25.266  5677  5723 I jxcore-log: 
,09-15 03:38:25.460  5677  5723 I jxcore-log: ok 219 Streams have same length
09-15 03:38:25.460  5677  5723 I jxcore-log: 
,09-15 03:38:25.468  5677  5723 I jxcore-log: ok 220 matching size
09-15 03:38:25.468  5677  5723 I jxcore-log: 
,09-15 03:38:25.468  5677  5723 I jxcore-log: ok 221 keys match
09-15 03:38:25.468  5677  5723 I jxcore-log: 
09-15 03:38:25.468  5677  5723 I jxcore-log: ok 222 secrets match
09-15 03:38:25.468  5677  5723 I jxcore-log: 
,09-15 03:38:25.470  5677  5723 I jxcore-log: # teardown
09-15 03:38:25.470  5677  5723 I jxcore-log: 
,09-15 03:38:25.498  5677  5723 I jxcore-log: # setup
09-15 03:38:25.498  5677  5723 I jxcore-log: 
,09-15 03:38:25.687  5677  5723 I jxcore-log: # 66. Add two Peers.
09-15 03:38:25.687  5677  5723 I jxcore-log: 
,09-15 03:38:25.736  5677  5723 I jxcore-log: ok 223 should be equal
09-15 03:38:25.736  5677  5723 I jxcore-log: 
,09-15 03:38:25.739  5677  5723 I jxcore-log: ok 224 should be equal
09-15 03:38:25.739  5677  5723 I jxcore-log: 
09-15 03:38:25.740  5677  5723 I jxcore-log: ok 225 should be equal
09-15 03:38:25.740  5677  5723 I jxcore-log: 
09-15 03:38:25.741  5677  5723 I jxcore-log: ok 226 should be equal
09-15 03:38:25.741  5677  5723 I jxcore-log: 
09-15 03:38:25.743  5677  5723 I jxcore-log: ok 227 should be equal
09-15 03:38:25.743  5677  5723 I jxcore-log: 
,09-15 03:38:25.750  5677  5723 I jxcore-log: # teardown
09-15 03:38:25.750  5677  5723 I jxcore-log: 
,09-15 03:38:25.812  5677  5723 I jxcore-log: # setup
09-15 03:38:25.812  5677  5723 I jxcore-log: 
,09-15 03:38:26.001  5677  5723 I jxcore-log: # 67. TCP_NATIVE peer loses DNS
09-15 03:38:26.001  5677  5723 I jxcore-log: 
,09-15 03:38:26.077  5677  5723 I jxcore-log: ok 228 should be equal
09-15 03:38:26.077  5677  5723 I jxcore-log: 
,09-15 03:38:26.079  5677  5723 I jxcore-log: ok 229 should be equal
09-15 03:38:26.079  5677  5723 I jxcore-log: 
,09-15 03:38:26.084  5677  5723 I jxcore-log: # teardown
09-15 03:38:26.084  5677  5723 I jxcore-log: 
,09-15 03:38:26.144  5677  5723 I jxcore-log: # setup
09-15 03:38:26.144  5677  5723 I jxcore-log: 
,09-15 03:38:26.317  5677  5723 I jxcore-log: # 68. Received beacons with no values for us
09-15 03:38:26.317  5677  5723 I jxcore-log: 
,09-15 03:38:26.470  5677  5723 I jxcore-log: ok 230 entry exists
09-15 03:38:26.470  5677  5723 I jxcore-log: 
,09-15 03:38:26.471  5677  5723 I jxcore-log: ok 231 entry is resolved
09-15 03:38:26.471  5677  5723 I jxcore-log: 
,09-15 03:38:26.478  5677  5723 I jxcore-log: # teardown
09-15 03:38:26.478  5677  5723 I jxcore-log: 
,09-15 03:38:26.624  5677  5723 I jxcore-log: # setup
09-15 03:38:26.624  5677  5723 I jxcore-log: 
,09-15 03:38:26.787  5677  5723 I jxcore-log: # 69. Resolves an action locally
09-15 03:38:26.787  5677  5723 I jxcore-log: 
,09-15 03:38:27.013  5677  5723 I jxcore-log: ok 232 Host address must match
09-15 03:38:27.013  5677  5723 I jxcore-log: 
,09-15 03:38:27.014  5677  5723 I jxcore-log: ok 233 suggestedTCPTimeout must match
09-15 03:38:27.014  5677  5723 I jxcore-log: 
,09-15 03:38:27.015  5677  5723 I jxcore-log: ok 234 connectionType must match
09-15 03:38:27.015  5677  5723 I jxcore-log: 
09-15 03:38:27.015  5677  5723 I jxcore-log: ok 235 portNumber must match
09-15 03:38:27.015  5677  5723 I jxcore-log: 
,09-15 03:38:27.024  5677  5723 I jxcore-log: # teardown
09-15 03:38:27.024  5677  5723 I jxcore-log: 
,09-15 03:38:27.120  5677  5723 I jxcore-log: # setup
09-15 03:38:27.120  5677  5723 I jxcore-log: 
,09-15 03:38:27.172   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:27.299  5677  5723 I jxcore-log: # 70. Resolves an action locally using ThaliPeerPoolDefault
09-15 03:38:27.299  5677  5723 I jxcore-log: 
,09-15 03:38:27.502  5677  5723 I jxcore-log: ok 236 Host address must match
09-15 03:38:27.502  5677  5723 I jxcore-log: 
,09-15 03:38:27.502  5677  5723 I jxcore-log: ok 237 suggestedTCPTimeout must match
09-15 03:38:27.502  5677  5723 I jxcore-log: 
09-15 03:38:27.502  5677  5723 I jxcore-log: ok 238 connectionType must match
09-15 03:38:27.502  5677  5723 I jxcore-log: 
,09-15 03:38:27.503  5677  5723 I jxcore-log: ok 239 portNumber must match
09-15 03:38:27.503  5677  5723 I jxcore-log: 
,09-15 03:38:27.511  5677  5723 I jxcore-log: # teardown
09-15 03:38:27.511  5677  5723 I jxcore-log: 
,09-15 03:38:27.605  5677  5723 I jxcore-log: # setup
09-15 03:38:27.605  5677  5723 I jxcore-log: 
,09-15 03:38:27.758  5677  5723 I jxcore-log: # 71. Action fails because of a bad hostname.
09-15 03:38:27.758  5677  5723 I jxcore-log: 
,09-15 03:38:28.173   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:29.174   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:30.176   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:31.177   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:38:32.177   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:38:32.842  5677  5723 I jxcore-log: ok 240 should be equal
09-15 03:38:32.842  5677  5723 I jxcore-log: 
,09-15 03:38:32.844  5677  5723 I jxcore-log: ok 241 should be equal
09-15 03:38:32.844  5677  5723 I jxcore-log: 
,09-15 03:38:32.845  5677  5723 I jxcore-log: ok 242 should be equal
09-15 03:38:32.845  5677  5723 I jxcore-log: 
,09-15 03:38:32.853  5677  5723 I jxcore-log: # teardown
09-15 03:38:32.853  5677  5723 I jxcore-log: 
,09-15 03:38:33.498  5677  5723 I jxcore-log: # setup
09-15 03:38:33.498  5677  5723 I jxcore-log: 
,09-15 03:38:34.518  5677  5723 I jxcore-log: # 72. hostaddress is removed when the action is running. 
09-15 03:38:34.518  5677  5723 I jxcore-log: 
,09-15 03:38:36.569  5677  5723 I jxcore-log: ok 243 should be equal
09-15 03:38:36.569  5677  5723 I jxcore-log: 
,09-15 03:38:36.596  5677  5723 I jxcore-log: # teardown
09-15 03:38:36.596  5677  5723 I jxcore-log: 
,09-15 03:38:36.688  5677  5723 I jxcore-log: # setup
09-15 03:38:36.688  5677  5723 I jxcore-log: 
,09-15 03:38:36.823  5677  5723 I jxcore-log: # 73. Client to server request locally
09-15 03:38:36.823  5677  5723 I jxcore-log: 
,09-15 03:38:37.004  5677  5723 I jxcore-log: ok 244 secrets are equal
09-15 03:38:37.004  5677  5723 I jxcore-log: 
,09-15 03:38:37.005  5677  5723 I jxcore-log: ok 245 Public key matches with the server key
09-15 03:38:37.005  5677  5723 I jxcore-log: 
09-15 03:38:37.005  5677  5723 I jxcore-log: ok 246 Host address must match
09-15 03:38:37.005  5677  5723 I jxcore-log: 
09-15 03:38:37.005  5677  5723 I jxcore-log: ok 247 suggestedTCPTimeout must match
09-15 03:38:37.005  5677  5723 I jxcore-log: 
09-15 03:38:37.006  5677  5723 I jxcore-log: ok 248 connectionType must match
09-15 03:38:37.006  5677  5723 I jxcore-log: 
09-15 03:38:37.006  5677  5723 I jxcore-log: ok 249 portNumber must match
09-15 03:38:37.006  5677  5723 I jxcore-log: 
,09-15 03:38:37.011  5677  5723 I jxcore-log: # teardown
09-15 03:38:37.011  5677  5723 I jxcore-log: 
,09-15 03:38:37.145  5677  5723 I jxcore-log: # setup
09-15 03:38:37.145  5677  5723 I jxcore-log: 
,09-15 03:38:37.251  5677  5723 I jxcore-log: # 74. Test ThaliPskMapCache clean and expiration
09-15 03:38:37.251  5677  5723 I jxcore-log: 
,09-15 03:38:37.285  5677  5723 I jxcore-log: ok 250 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
09-15 03:38:37.285  5677  5723 I jxcore-log: 
09-15 03:38:37.286  5677  5723 I jxcore-log: ok 251 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
09-15 03:38:37.286  5677  5723 I jxcore-log: 
,09-15 03:38:38.289  5677  5723 I jxcore-log: ok 252 All entries should be expired after 1 second
09-15 03:38:38.289  5677  5723 I jxcore-log: 
,09-15 03:38:38.297  5677  5723 I jxcore-log: # teardown
09-15 03:38:38.297  5677  5723 I jxcore-log: 
,09-15 03:38:38.439  5677  5723 I jxcore-log: # setup
09-15 03:38:38.439  5677  5723 I jxcore-log: 
,09-15 03:38:38.545  5677  5723 I jxcore-log: # 75. Test ThaliPskMapCache getSecret and getPublic
09-15 03:38:38.545  5677  5723 I jxcore-log: 
,09-15 03:38:38.737  5677  5723 I jxcore-log: ok 253 All keys need to be available in the cache
09-15 03:38:38.737  5677  5723 I jxcore-log: 
,09-15 03:38:39.739  5677  5723 I jxcore-log: ok 254 All entries should be expired after 1 second
09-15 03:38:39.739  5677  5723 I jxcore-log: 
,09-15 03:38:39.750  5677  5723 I jxcore-log: # teardown
09-15 03:38:39.750  5677  5723 I jxcore-log: 
,09-15 03:38:39.798  5677  5723 I jxcore-log: # setup
09-15 03:38:39.798  5677  5723 I jxcore-log: 
,09-15 03:38:39.932  5677  5723 I jxcore-log: # 76. Test ThaliPskMapCache multiple entries
09-15 03:38:39.932  5677  5723 I jxcore-log: 
,09-15 03:38:41.322  5677  5723 I jxcore-log: ok 255 Size of the cache should be 2
09-15 03:38:41.322  5677  5723 I jxcore-log: 
09-15 03:38:41.325  5677  5723 I jxcore-log: ok 256 Cache doesn't contain dictionary1
09-15 03:38:41.325  5677  5723 I jxcore-log: 
,09-15 03:38:42.538  5677  5723 I jxcore-log: ok 257 Size of the cache should be 1
09-15 03:38:42.538  5677  5723 I jxcore-log: 
,09-15 03:38:42.542  5677  5723 I jxcore-log: ok 258 Cache doesn't contain beaconStreamAndSecretDictionary2
09-15 03:38:42.542  5677  5723 I jxcore-log: 
,09-15 03:38:42.551  5677  5723 I jxcore-log: # teardown
09-15 03:38:42.551  5677  5723 I jxcore-log: 
,09-15 03:38:43.144  5677  5723 I jxcore-log: # setup
09-15 03:38:43.144  5677  5723 I jxcore-log: 
,09-15 03:38:43.344  5677  5723 I jxcore-log: # 77. Start and stop ThaliNotificationServer
09-15 03:38:43.344  5677  5723 I jxcore-log: 
,09-15 03:38:43.458  5677  5723 I jxcore-log: ok 259 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
09-15 03:38:43.458  5677  5723 I jxcore-log: 
,09-15 03:38:43.458  5677  5723 I jxcore-log: ok 260 ThaliMobile.StopAdvertisingAndListeningshould be called once
09-15 03:38:43.458  5677  5723 I jxcore-log: 
09-15 03:38:43.459  5677  5723 I jxcore-log: # teardown
09-15 03:38:43.459  5677  5723 I jxcore-log: 
,09-15 03:38:43.526  5677  5723 I jxcore-log: # setup
09-15 03:38:43.526  5677  5723 I jxcore-log: 
,09-15 03:38:43.643  5677  5723 I jxcore-log: # 78. Pass an empty array to ThaliNotificationServer.start
09-15 03:38:43.643  5677  5723 I jxcore-log: 
,09-15 03:38:43.692  5677  5723 I jxcore-log: ok 261 StartUpdateAdvertisingAndListening should not be called
09-15 03:38:43.692  5677  5723 I jxcore-log: 
,09-15 03:38:43.708  5677  5723 I jxcore-log: ok 262 ThaliMobile.StopAdvertisingAndListening should be called once
09-15 03:38:43.708  5677  5723 I jxcore-log: 
,09-15 03:38:43.755  5677  5723 I jxcore-log: ok 263 no error,
09-15 03:38:43.755  5677  5723 I jxcore-log: 
09-15 03:38:43.756  5677  5723 I jxcore-log: ok 264 should be 204
09-15 03:38:43.756  5677  5723 I jxcore-log: 
,09-15 03:38:43.761  5677  5723 I jxcore-log: # teardown
09-15 03:38:43.761  5677  5723 I jxcore-log: 
,09-15 03:38:43.853  5677  5723 I jxcore-log: # setup
09-15 03:38:43.853  5677  5723 I jxcore-log: 
,09-15 03:38:43.945  5677  5723 I jxcore-log: # 79. Pass a string to ThaliNotificationServer.start
09-15 03:38:43.945  5677  5723 I jxcore-log: 
,09-15 03:38:44.022  5677  5723 I jxcore-log: ok 265 StartUpdateAdvertisingAndListening should not be called
09-15 03:38:44.022  5677  5723 I jxcore-log: 
,09-15 03:38:44.026  5677  5723 I jxcore-log: # teardown
09-15 03:38:44.026  5677  5723 I jxcore-log: 
,09-15 03:38:44.124  5677  5723 I jxcore-log: # setup
09-15 03:38:44.124  5677  5723 I jxcore-log: 
,09-15 03:38:44.222  5677  5723 I jxcore-log: # 80. Pass an empty parameter to ThaliNotificationServer.start
09-15 03:38:44.222  5677  5723 I jxcore-log: 
,09-15 03:38:44.325  5677  5723 I jxcore-log: ok 266 StartUpdateAdvertisingAndListening should not be called
09-15 03:38:44.325  5677  5723 I jxcore-log: 
,09-15 03:38:44.330  5677  5723 I jxcore-log: # teardown
09-15 03:38:44.330  5677  5723 I jxcore-log: 
,09-15 03:38:44.424  5677  5723 I jxcore-log: # setup
09-15 03:38:44.424  5677  5723 I jxcore-log: 
,09-15 03:38:44.550  5677  5723 I jxcore-log: # 81. Make an HTTP request to /NotificationBeacons
09-15 03:38:44.550  5677  5723 I jxcore-log: 
,09-15 03:38:44.709  5677  5723 I jxcore-log: ok 267 no error
09-15 03:38:44.709  5677  5723 I jxcore-log: 
09-15 03:38:44.710  5677  5723 I jxcore-log: ok 268 should be 200
09-15 03:38:44.710  5677  5723 I jxcore-log: 
,09-15 03:38:44.710  5677  5723 I jxcore-log: ok 269 should be equal
09-15 03:38:44.710  5677  5723 I jxcore-log: 
09-15 03:38:44.710  5677  5723 I jxcore-log: ok 270 should be equal
09-15 03:38:44.710  5677  5723 I jxcore-log: 
,09-15 03:38:44.730  5677  5723 I jxcore-log: ok 271 (unnamed assert)
09-15 03:38:44.730  5677  5723 I jxcore-log: 
,09-15 03:38:44.758  5677  5723 I jxcore-log: ok 272 no error
09-15 03:38:44.758  5677  5723 I jxcore-log: 
,09-15 03:38:44.759  5677  5723 I jxcore-log: ok 273 should be 204
09-15 03:38:44.759  5677  5723 I jxcore-log: 
,09-15 03:38:44.761  5677  5723 I jxcore-log: # teardown
09-15 03:38:44.761  5677  5723 I jxcore-log: 
,09-15 03:38:44.866  5677  5723 I jxcore-log: # setup
09-15 03:38:44.866  5677  5723 I jxcore-log: 
,09-15 03:38:44.979  5677  5723 I jxcore-log: # 82. Make an HTTP request to /NotificationBeacons (no keys)
09-15 03:38:44.979  5677  5723 I jxcore-log: 
,09-15 03:38:45.063  5677  5723 I jxcore-log: ok 274 error should be null
09-15 03:38:45.063  5677  5723 I jxcore-log: 
09-15 03:38:45.064  5677  5723 I jxcore-log: ok 275 should be 204
09-15 03:38:45.064  5677  5723 I jxcore-log: 
,09-15 03:38:45.068  5677  5723 I jxcore-log: # teardown
09-15 03:38:45.068  5677  5723 I jxcore-log: 
,09-15 03:38:45.146  5677  5723 I jxcore-log: # setup
09-15 03:38:45.146  5677  5723 I jxcore-log: 
,09-15 03:38:45.242  5677  5723 I jxcore-log: # 83. Make an HTTP request to /NotificationBeaconsbefore calling start
09-15 03:38:45.242  5677  5723 I jxcore-log: 
,09-15 03:38:45.314  5677  5723 I jxcore-log: ok 276 should be 404
09-15 03:38:45.314  5677  5723 I jxcore-log: 
,09-15 03:38:45.319  5677  5723 I jxcore-log: # teardown
09-15 03:38:45.319  5677  5723 I jxcore-log: 
,09-15 03:38:45.403  5677  5723 I jxcore-log: # setup
09-15 03:38:45.403  5677  5723 I jxcore-log: 
,09-15 03:38:45.470  5677  5723 I jxcore-log: # 84. #testThaliPeerAction - test getters
09-15 03:38:45.470  5677  5723 I jxcore-log: 
,09-15 03:38:45.537  5677  5723 I jxcore-log: ok 277 getPeerIdentifier
09-15 03:38:45.537  5677  5723 I jxcore-log: 
,09-15 03:38:45.539  5677  5723 I jxcore-log: ok 278 getConnectionType
09-15 03:38:45.539  5677  5723 I jxcore-log: 
,09-15 03:38:45.540  5677  5723 I jxcore-log: ok 279 getActionType
09-15 03:38:45.540  5677  5723 I jxcore-log: 
09-15 03:38:45.541  5677  5723 I jxcore-log: ok 280 getActionState
09-15 03:38:45.541  5677  5723 I jxcore-log: 
09-15 03:38:45.542  5677  5723 I jxcore-log: ok 281 getPskIdentity
09-15 03:38:45.542  5677  5723 I jxcore-log: 
09-15 03:38:45.543  5677  5723 I jxcore-log: ok 282 getPskKey
09-15 03:38:45.543  5677  5723 I jxcore-log: 
,09-15 03:38:45.548  5677  5723 I jxcore-log: # teardown
09-15 03:38:45.548  5677  5723 I jxcore-log: 
,09-15 03:38:45.610  5677  5723 I jxcore-log: # setup
09-15 03:38:45.610  5677  5723 I jxcore-log: 
,09-15 03:38:45.680  5677  5723 I jxcore-log: # 85. #testThaliPeerAction - start and kill
09-15 03:38:45.680  5677  5723 I jxcore-log: 
,09-15 03:38:45.747  5677  5723 I jxcore-log: ok 283 initial state
09-15 03:38:45.747  5677  5723 I jxcore-log: 
,09-15 03:38:45.751  5677  5723 I jxcore-log: ok 284 after start
09-15 03:38:45.751  5677  5723 I jxcore-log: 
,09-15 03:38:45.753  5677  5723 I jxcore-log: ok 285 after kill
09-15 03:38:45.753  5677  5723 I jxcore-log: 
,09-15 03:38:45.757  5677  5723 I jxcore-log: # teardown
09-15 03:38:45.757  5677  5723 I jxcore-log: 
,09-15 03:38:45.813  5677  5723 I jxcore-log: # setup
09-15 03:38:45.813  5677  5723 I jxcore-log: 
,09-15 03:38:45.867  5677  5723 I jxcore-log: # 86. #testThaliPeerAction - double start
09-15 03:38:45.867  5677  5723 I jxcore-log: 
,09-15 03:38:45.932  5677  5723 I jxcore-log: ok 286 should be equal
09-15 03:38:45.932  5677  5723 I jxcore-log: 
,09-15 03:38:45.937  5677  5723 I jxcore-log: # teardown
09-15 03:38:45.937  5677  5723 I jxcore-log: 
,09-15 03:38:45.994  5677  5723 I jxcore-log: # setup
09-15 03:38:45.994  5677  5723 I jxcore-log: 
,09-15 03:38:46.057  5677  5723 I jxcore-log: # 87. #testThaliPeerAction - start after kill
09-15 03:38:46.057  5677  5723 I jxcore-log: 
,09-15 03:38:46.123  5677  5723 I jxcore-log: ok 287 clean kill
09-15 03:38:46.123  5677  5723 I jxcore-log: 
,09-15 03:38:46.128  5677  5723 I jxcore-log: ok 288 should be equal
09-15 03:38:46.128  5677  5723 I jxcore-log: 
,09-15 03:38:46.132  5677  5723 I jxcore-log: # teardown
09-15 03:38:46.132  5677  5723 I jxcore-log: 
,09-15 03:38:46.187  5677  5723 I jxcore-log: # setup
09-15 03:38:46.187  5677  5723 I jxcore-log: 
,09-15 03:38:46.277  5677  5723 I jxcore-log: # 88. #testThaliPeerAction - make sure ids are unique
09-15 03:38:46.277  5677  5723 I jxcore-log: 
,09-15 03:38:46.356  5677  5723 I jxcore-log: ok 289 should not be equal
09-15 03:38:46.356  5677  5723 I jxcore-log: 
,09-15 03:38:46.359  5677  5723 I jxcore-log: # teardown
09-15 03:38:46.359  5677  5723 I jxcore-log: 
,09-15 03:38:46.415  5677  5723 I jxcore-log: # setup
09-15 03:38:46.415  5677  5723 I jxcore-log: 
,09-15 03:38:46.480  5677  5723 I jxcore-log: # 89. Test PeerConnectionInformation basics
09-15 03:38:46.480  5677  5723 I jxcore-log: 
,09-15 03:38:46.552  5677  5723 I jxcore-log: ok 290 connection type works
09-15 03:38:46.552  5677  5723 I jxcore-log: 
,09-15 03:38:46.554  5677  5723 I jxcore-log: ok 291 getHostAddress works
09-15 03:38:46.554  5677  5723 I jxcore-log: 
,09-15 03:38:46.555  5677  5723 I jxcore-log: ok 292 getPortNumber works
09-15 03:38:46.555  5677  5723 I jxcore-log: 
,09-15 03:38:46.556  5677  5723 I jxcore-log: ok 293 getSuggestedTCPTimeout works
09-15 03:38:46.556  5677  5723 I jxcore-log: 
,09-15 03:38:46.561  5677  5723 I jxcore-log: # teardown
09-15 03:38:46.561  5677  5723 I jxcore-log: 
,09-15 03:38:46.611  5677  5723 I jxcore-log: # setup
09-15 03:38:46.611  5677  5723 I jxcore-log: 
,09-15 03:38:46.677  5677  5723 I jxcore-log: # 90. Test PeerDictionary basic functionality
09-15 03:38:46.677  5677  5723 I jxcore-log: 
,09-15 03:38:46.766  5677  5723 I jxcore-log: ok 294 Entry counter must be 1
09-15 03:38:46.766  5677  5723 I jxcore-log: 
,09-15 03:38:46.767  5677  5723 I jxcore-log: ok 295 Size must be 1
09-15 03:38:46.767  5677  5723 I jxcore-log: 
,09-15 03:38:46.768  5677  5723 I jxcore-log: ok 296 Entry counter must be 2
09-15 03:38:46.768  5677  5723 I jxcore-log: 
,09-15 03:38:46.769  5677  5723 I jxcore-log: ok 297 Size must be 2
09-15 03:38:46.769  5677  5723 I jxcore-log: 
,09-15 03:38:46.771  5677  5723 I jxcore-log: ok 298 Entry2 should not be found
09-15 03:38:46.771  5677  5723 I jxcore-log: 
,09-15 03:38:46.772  5677  5723 I jxcore-log: ok 299 Size must be 1
09-15 03:38:46.772  5677  5723 I jxcore-log: 
,09-15 03:38:46.779  5677  5723 I jxcore-log: ok 300 Size must be 0
09-15 03:38:46.779  5677  5723 I jxcore-log: 
,09-15 03:38:46.783  5677  5723 I jxcore-log: # teardown
09-15 03:38:46.783  5677  5723 I jxcore-log: 
,09-15 03:38:46.817  5677  5723 I jxcore-log: # setup
09-15 03:38:46.817  5677  5723 I jxcore-log: 
,09-15 03:38:46.887  5677  5723 I jxcore-log: # 91. Test PeerDictionary with multiple entries.
09-15 03:38:46.887  5677  5723 I jxcore-log: 
,09-15 03:38:47.547  5677  5723 I jxcore-log: ok 301 Size must be100
09-15 03:38:47.547  5677  5723 I jxcore-log: 
,09-15 03:38:47.550  5677  5723 I jxcore-log: ok 302 Entries between 20 and MAXSIZE + 20 should exist
09-15 03:38:47.550  5677  5723 I jxcore-log: 
,09-15 03:38:48.063  5677  5723 I jxcore-log: ok 303 WAITING state entry should not be removed
09-15 03:38:48.063  5677  5723 I jxcore-log: 
,09-15 03:38:48.065  5677  5723 I jxcore-log: # teardown
09-15 03:38:48.065  5677  5723 I jxcore-log: 
,09-15 03:38:48.539  5677  5723 I jxcore-log: # setup
09-15 03:38:48.539  5677  5723 I jxcore-log: 
,09-15 03:38:49.155  5677  5723 I jxcore-log: # 92. RESOLVED entries are removed before WAITING state entry.
09-15 03:38:49.155  5677  5723 I jxcore-log: 
,09-15 03:38:49.779  5677  5723 I jxcore-log: ok 304 Entries between 6 and MAXSIZE + 4 should exist
09-15 03:38:49.779  5677  5723 I jxcore-log: 
,09-15 03:38:49.780  5677  5723 I jxcore-log: ok 305 Size should be MAXSIZE
09-15 03:38:49.780  5677  5723 I jxcore-log: 
09-15 03:38:49.780  5677  5723 I jxcore-log: ok 306 Size should be MAXSIZE+6
09-15 03:38:49.780  5677  5723 I jxcore-log: 
09-15 03:38:49.781  5677  5723 I jxcore-log: # teardown
09-15 03:38:49.781  5677  5723 I jxcore-log: 
,09-15 03:38:49.819  5677  5723 I jxcore-log: # setup
09-15 03:38:49.819  5677  5723 I jxcore-log: 
,09-15 03:38:49.895  5677  5723 I jxcore-log: # 93. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
09-15 03:38:49.895  5677  5723 I jxcore-log: 
,09-15 03:38:50.523  5677  5723 I jxcore-log: ok 307 WAITING state entry should not be removed
09-15 03:38:50.523  5677  5723 I jxcore-log: 
,09-15 03:38:50.524  5677  5723 I jxcore-log: ok 308 Waiting entries between 6 and MAXSIZE + 4 should exist
09-15 03:38:50.524  5677  5723 I jxcore-log: 
09-15 03:38:50.524  5677  5723 I jxcore-log: ok 309 Size should be MAXSIZE
09-15 03:38:50.524  5677  5723 I jxcore-log: 
09-15 03:38:50.525  5677  5723 I jxcore-log: ok 310 entryCounter should be MAXSIZE+6
09-15 03:38:50.525  5677  5723 I jxcore-log: 
,09-15 03:38:50.526  5677  5723 I jxcore-log: # teardown
09-15 03:38:50.526  5677  5723 I jxcore-log: 
,09-15 03:38:51.151   925  3001 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-15 03:38:51.427  5677  5723 I jxcore-log: # setup
09-15 03:38:51.427  5677  5723 I jxcore-log: 
,09-15 03:38:52.534  5677  5723 I jxcore-log: # 94. When CONTROLLED_BY_POOL entry is removed and kill is called.
09-15 03:38:52.534  5677  5723 I jxcore-log: 
,09-15 03:38:53.111  5677  5723 I jxcore-log: ok 311 Kill should be called once
09-15 03:38:53.111  5677  5723 I jxcore-log: 
,09-15 03:38:53.111  5677  5723 I jxcore-log: ok 312 Size should be 100
09-15 03:38:53.111  5677  5723 I jxcore-log: 
09-15 03:38:53.112  5677  5723 I jxcore-log: # teardown
09-15 03:38:53.112  5677  5723 I jxcore-log: 
,09-15 03:38:53.460  5677  5723 I jxcore-log: # setup
09-15 03:38:53.460  5677  5723 I jxcore-log: 
,09-15 03:38:53.771  5677  5723 I jxcore-log: # 95. #ThaliPeerPoolInterface - make sure that start verifies queue length
09-15 03:38:53.771  5677  5723 I jxcore-log: 
,09-15 03:38:53.816  5677  5723 I jxcore-log: ok 313 good start
09-15 03:38:53.816  5677  5723 I jxcore-log: 
,09-15 03:38:53.817  5677  5723 I jxcore-log: ok 314 good enqueue
09-15 03:38:53.817  5677  5723 I jxcore-log: 
,09-15 03:38:53.828  5677  5723 I jxcore-log: ok 315 queue is not empty
09-15 03:38:53.828  5677  5723 I jxcore-log: 
,09-15 03:38:53.834  5677  5723 I jxcore-log: # teardown
09-15 03:38:53.834  5677  5723 I jxcore-log: 
,09-15 03:38:53.896  5677  5723 I jxcore-log: # setup
09-15 03:38:53.896  5677  5723 I jxcore-log: 
,09-15 03:38:53.951  5677  5723 I jxcore-log: # 96. #ThaliPeerPoolInterface - bad enqueues
09-15 03:38:53.951  5677  5723 I jxcore-log: 
,09-15 03:38:54.007  5677  5723 I jxcore-log: ok 316 null arg
09-15 03:38:54.007  5677  5723 I jxcore-log: 
,09-15 03:38:54.012  5677  5723 I jxcore-log: ok 317 wrong arg type
09-15 03:38:54.012  5677  5723 I jxcore-log: 
,09-15 03:38:54.017  5677  5723 I jxcore-log: ok 318 wrong arg type
09-15 03:38:54.017  5677  5723 I jxcore-log: 
,09-15 03:38:54.021  5677  5723 I jxcore-log: # teardown
09-15 03:38:54.021  5677  5723 I jxcore-log: 
,09-15 03:38:54.072  5677  5723 I jxcore-log: # setup
09-15 03:38:54.072  5677  5723 I jxcore-log: 
,09-15 03:38:54.139  5677  5723 I jxcore-log: # 97. #ThaliPeerPoolInterface - do not allow same object type
09-15 03:38:54.139  5677  5723 I jxcore-log: 
,09-15 03:38:54.218  5677  5723 I jxcore-log: ok 319 good enqueue
09-15 03:38:54.218  5677  5723 I jxcore-log: 
,09-15 03:38:54.223  5677  5723 I jxcore-log: ok 320 already enqueued
09-15 03:38:54.223  5677  5723 I jxcore-log: 
,09-15 03:38:54.227  5677  5723 I jxcore-log: # teardown
09-15 03:38:54.227  5677  5723 I jxcore-log: 
,09-15 03:38:54.293  5677  5723 I jxcore-log: # setup
09-15 03:38:54.293  5677  5723 I jxcore-log: 
,09-15 03:38:54.374  5677  5723 I jxcore-log: # 98. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
09-15 03:38:54.374  5677  5723 I jxcore-log: 
,09-15 03:38:54.481  5677  5723 I jxcore-log: ok 321 good enqueue
09-15 03:38:54.481  5677  5723 I jxcore-log: 
,09-15 03:38:54.482  5677  5723 I jxcore-log: ok 322 2nd good enqueue
09-15 03:38:54.482  5677  5723 I jxcore-log: 
09-15 03:38:54.483  5677  5723 I jxcore-log: ok 323 we are in the pool
09-15 03:38:54.483  5677  5723 I jxcore-log: 
,09-15 03:38:54.487  5677  5723 I jxcore-log: ok 324 We are out of the pool
09-15 03:38:54.487  5677  5723 I jxcore-log: 
,09-15 03:38:54.488  5677  5723 I jxcore-log: ok 325 Action was killed
09-15 03:38:54.488  5677  5723 I jxcore-log: 
,09-15 03:38:54.489  5677  5723 I jxcore-log: ok 326 The original kill was called too
09-15 03:38:54.489  5677  5723 I jxcore-log: 
09-15 03:38:54.491  5677  5723 I jxcore-log: ok 327 second item is still in queue
09-15 03:38:54.491  5677  5723 I jxcore-log: 
,09-15 03:38:54.495  5677  5723 I jxcore-log: # teardown
09-15 03:38:54.495  5677  5723 I jxcore-log: 
,09-15 03:38:54.548  5677  5723 I jxcore-log: # setup
09-15 03:38:54.548  5677  5723 I jxcore-log: 
,09-15 03:38:54.628  5677  5723 I jxcore-log: # 99. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
09-15 03:38:54.628  5677  5723 I jxcore-log: 
,09-15 03:38:54.698  5677  5723 I jxcore-log: ok 328 good enqueue
09-15 03:38:54.698  5677  5723 I jxcore-log: 
,09-15 03:38:54.699  5677  5723 I jxcore-log: ok 329 first kill
09-15 03:38:54.699  5677  5723 I jxcore-log: 
,09-15 03:38:54.700  5677  5723 I jxcore-log: ok 330 second NOOP kill
09-15 03:38:54.700  5677  5723 I jxcore-log: 
,09-15 03:38:54.703  5677  5723 I jxcore-log: # teardown
09-15 03:38:54.703  5677  5723 I jxcore-log: 
,09-15 03:38:54.777  5677  5723 I jxcore-log: # setup
09-15 03:38:54.777  5677  5723 I jxcore-log: 
,09-15 03:38:54.839  5677  5723 I jxcore-log: # 100. #ThaliPeerPoolInterface - make sure that stop removes all actions
09-15 03:38:54.839  5677  5723 I jxcore-log: 
,09-15 03:38:54.908  5677  5723 I jxcore-log: ok 331 1st good enqueue
09-15 03:38:54.908  5677  5723 I jxcore-log: 
,09-15 03:38:54.910  5677  5723 I jxcore-log: ok 332 2nd good enqueue
09-15 03:38:54.910  5677  5723 I jxcore-log: 
,09-15 03:38:54.912  5677  5723 I jxcore-log: ok 333 1st action is in the pool
09-15 03:38:54.912  5677  5723 I jxcore-log: 
,09-15 03:38:54.914  5677  5723 I jxcore-log: ok 334 2nd action is in the pool
09-15 03:38:54.914  5677  5723 I jxcore-log: 
,09-15 03:38:54.921  5677  5723 I jxcore-log: ok 335 1st action is out of the pool
09-15 03:38:54.921  5677  5723 I jxcore-log: 
,09-15 03:38:54.922  5677  5723 I jxcore-log: ok 336 2st action is out of the pool
09-15 03:38:54.922  5677  5723 I jxcore-log: 
09-15 03:38:54.923  5677  5723 I jxcore-log: ok 337 pool is empty
09-15 03:38:54.923  5677  5723 I jxcore-log: 
09-15 03:38:54.925  5677  5723 I jxcore-log: # teardown
09-15 03:38:54.925  5677  5723 I jxcore-log: 
,09-15 03:38:54.967  5677  5723 I jxcore-log: # setup
09-15 03:38:54.967  5677  5723 I jxcore-log: 
,09-15 03:38:55.031  5677  5723 I jxcore-log: # 101. Make sure peerDictionaryKey is reasonable
09-15 03:38:55.031  5677  5723 I jxcore-log: 
,09-15 03:38:55.094  5677  5723 I jxcore-log: ok 338 equal keys
09-15 03:38:55.094  5677  5723 I jxcore-log: 
,09-15 03:38:55.095  5677  5723 I jxcore-log: ok 339 not equal connection type
09-15 03:38:55.095  5677  5723 I jxcore-log: 
,09-15 03:38:55.096  5677  5723 I jxcore-log: ok 340 same connection type, different buffer
09-15 03:38:55.096  5677  5723 I jxcore-log: 
,09-15 03:38:55.101  5677  5723 I jxcore-log: # teardown
09-15 03:38:55.101  5677  5723 I jxcore-log: 
,09-15 03:38:55.151  5677  5723 I jxcore-log: # setup
09-15 03:38:55.151  5677  5723 I jxcore-log: 
,09-15 03:38:55.202  5677  5723 I jxcore-log: # 102. Make sure start works
09-15 03:38:55.202  5677  5723 I jxcore-log: 
,09-15 03:38:55.285  5677  5723 I jxcore-log: DEBUG thaliPullReplicationFromNotification: starting thaliPeerPoolInterface
09-15 03:38:55.285  5677  5723 I jxcore-log: 
,09-15 03:38:55.293  5677  5723 I jxcore-log: ok 341 First start and on called correctly
09-15 03:38:55.293  5677  5723 I jxcore-log: 
,09-15 03:38:55.295  5677  5723 I jxcore-log: # teardown
09-15 03:38:55.295  5677  5723 I jxcore-log: 
,09-15 03:38:55.356  5677  5723 I jxcore-log: # setup
09-15 03:38:55.356  5677  5723 I jxcore-log: 
,09-15 03:38:55.417  5677  5723 I jxcore-log: # 103. Make sure stop works
09-15 03:38:55.417  5677  5723 I jxcore-log: 
,09-15 03:38:55.465  5677  5723 I jxcore-log: ok 342 second cleared dictionary
09-15 03:38:55.465  5677  5723 I jxcore-log: 
,09-15 03:38:55.492  5677  5723 I jxcore-log: DEBUG thaliPullReplicationFromNotification: starting thaliPeerPoolInterface
09-15 03:38:55.492  5677  5723 I jxcore-log: 
,09-15 03:38:55.498  5677  5723 I jxcore-log: ok 343 First start and on called correctly
09-15 03:38:55.498  5677  5723 I jxcore-log: 
,09-15 03:38:55.522  5677  5723 I jxcore-log: ok 344 First stop and removeListener called correctly
09-15 03:38:55.522  5677  5723 I jxcore-log: 
,09-15 03:38:55.522  5677  5723 I jxcore-log: ok 345 first action kill called
09-15 03:38:55.522  5677  5723 I jxcore-log: 
09-15 03:38:55.523  5677  5723 I jxcore-log: ok 346 second action kill called
09-15 03:38:55.523  5677  5723 I jxcore-log: 
09-15 03:38:55.523  5677  5723 I jxcore-log: ok 347 first cleared dictionary
09-15 03:38:55.523  5677  5723 I jxcore-log: 
09-15 03:38:55.523  5677  5723 I jxcore-log: ok 348 first cleared pool
09-15 03:38:55.523  5677  5723 I jxcore-log: 
09-15 03:38:55.523  5677  5723 I jxcore-log: ok 349 second cleared dictionary
09-15 03:38:55.523  5677  5723 I jxcore-log: 
,09-15 03:38:55.525  5677  5723 I jxcore-log: ok 350 second cleared pool
09-15 03:38:55.525  5677  5723 I jxcore-log: 
,09-15 03:38:55.528  5677  5723 I jxcore-log: # teardown
09-15 03:38:55.528  5677  5723 I jxcore-log: 
,09-15 03:38:55.608  5677  5723 I jxcore-log: # setup
09-15 03:38:55.608  5677  5723 I jxcore-log: 
,09-15 03:38:55.671  5677  5723 I jxcore-log: # 104. Simple peer event
09-15 03:38:55.671  5677  5723 I jxcore-log: 
,09-15 03:38:55.752  5677  5723 I jxcore-log: DEBUG thaliPullReplicationFromNotification: starting thaliPeerPoolInterface
09-15 03:38:55.752  5677  5723 I jxcore-log: 
,09-15 03:38:55.755  5677  5723 I jxcore-log: ok 351 listener has been set
09-15 03:38:55.755  5677  5723 I jxcore-log: 
,09-15 03:38:55.765  5677  5723 I jxcore-log: ok 352 peer dictionary has expected number of entries
09-15 03:38:55.765  5677  5723 I jxcore-log: 
,09-15 03:38:55.766  5677  5723 I jxcore-log: ok 353 Dictionary and pool have same action
09-15 03:38:55.766  5677  5723 I jxcore-log: 
09-15 03:38:55.767  5677  5723 I jxcore-log: ok 354 ads match
09-15 03:38:55.767  5677  5723 I jxcore-log: 
,09-15 03:38:55.767  5677  5723 I jxcore-log: ok 355 PouchDB matches
09-15 03:38:55.767  5677  5723 I jxcore-log: 
09-15 03:38:55.768  5677  5723 I jxcore-log: ok 356 DB Names match
09-15 03:38:55.768  5677  5723 I jxcore-log: 
09-15 03:38:55.768  5677  5723 I jxcore-log: ok 357 public keys match
09-15 03:38:55.768  5677  5723 I jxcore-log: 
,09-15 03:38:55.775  5677  5723 I jxcore-log: ok 358 peer dictionary has expected number of entries
09-15 03:38:55.775  5677  5723 I jxcore-log: 
09-15 03:38:55.776  5677  5723 I jxcore-log: ok 359 Dictionary and pool have same action
09-15 03:38:55.776  5677  5723 I jxcore-log: 
,09-15 03:38:55.776  5677  5723 I jxcore-log: ok 360 ads match
09-15 03:38:55.776  5677  5723 I jxcore-log: 
09-15 03:38:55.777  5677  5723 I jxcore-log: ok 361 PouchDB matches
09-15 03:38:55.777  5677  5723 I jxcore-log: 
09-15 03:38:55.778  5677  5723 I jxcore-log: ok 362 DB Names match
09-15 03:38:55.778  5677  5723 I jxcore-log: 
,09-15 03:38:55.779  5677  5723 I jxcore-log: ok 363 public keys match
09-15 03:38:55.779  5677  5723 I jxcore-log: 
,09-15 03:38:55.790  5677  5723 I jxcore-log: ok 364 start called once
09-15 03:38:55.790  5677  5723 I jxcore-log: 
,09-15 03:38:55.791  5677  5723 I jxcore-log: ok 365 One entry left
09-15 03:38:55.791  5677  5723 I jxcore-log: 
,09-15 03:38:55.792  5677  5723 I jxcore-log: ok 366 Dictionary and pool have same action
09-15 03:38:55.792  5677  5723 I jxcore-log: 
,09-15 03:38:55.793  5677  5723 I jxcore-log: ok 367 Start never called
09-15 03:38:55.793  5677  5723 I jxcore-log: 
,09-15 03:38:55.794  5677  5723 I jxcore-log: ok 368 Kill called once
09-15 03:38:55.794  5677  5723 I jxcore-log: 
,09-15 03:38:55.794  5677  5723 I jxcore-log: ok 369 no entries left
09-15 03:38:55.794  5677  5723 I jxcore-log: 
,09-15 03:38:55.803  5677  5723 I jxcore-log: ok 370 Third action is dead
09-15 03:38:55.803  5677  5723 I jxcore-log: 
,09-15 03:38:55.803  5677  5723 I jxcore-log: ok 371 peer dictionary has expected number of entries
09-15 03:38:55.803  5677  5723 I jxcore-log: 
09-15 03:38:55.803  5677  5723 I jxcore-log: ok 372 Dictionary and pool have same action
09-15 03:38:55.803  5677  5723 I jxcore-log: 
09-15 03:38:55.804  5677  5723 I jxcore-log: ok 373 ads match
09-15 03:38:55.804  5677  5723 I jxcore-log: 
,09-15 03:38:55.804  5677  5723 I jxcore-log: ok 374 PouchDB matches
09-15 03:38:55.804  5677  5723 I jxcore-log: 
,09-15 03:38:55.805  5677  5723 I jxcore-log: ok 375 DB Names match
09-15 03:38:55.805  5677  5723 I jxcore-log: 
09-15 03:38:55.805  5677  5723 I jxcore-log: ok 376 public keys match
09-15 03:38:55.805  5677  5723 I jxcore-log: 
,09-15 03:38:55.808  5677  5723 I jxcore-log: # teardown
09-15 03:38:55.808  5677  5723 I jxcore-log: 
,09-15 03:38:55.907  5677  5723 I jxcore-log: # setup
09-15 03:38:55.907  5677  5723 I jxcore-log: 
,09-15 03:38:57.102  5677  5723 I jxcore-log: # 105. Coordinated pull replication from notification test
09-15 03:38:57.102  5677  5723 I jxcore-log: 
,09-15 03:38:57.178   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 03:38:57.178   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:39:05.231   925   945 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-15 03:39:05.231   936   936 W Binder_2: type=1400 audit(0.0:144): avc: denied { ioctl } for path="socket:[30570]" dev="sockfs" ino=30570 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 03:39:05.234   936   936 W Binder_2: type=1400 audit(0.0:145): avc: denied { ioctl } for path="socket:[30570]" dev="sockfs" ino=30570 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 03:39:05.248  3431  3431 I Keyboard.Facilitator: onFinishInput()
,09-15 03:39:05.793  5677  5677 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 03:39:05.793  5677  5677 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-15 03:39:05.836   925   945 I sensors : batch
,09-15 03:39:05.836   925   945 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-15 03:39:05.841   925   945 I sensors : activate
,09-15 03:39:05.839  5677  5677 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ce3814c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@29c8781, 16908290=android.view.AbsSavedState$1@29c8781}, android:focusedViewId=100}]}]
09-15 03:39:05.841  5677  5677 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-15 03:39:05.841  5677  5677 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 03:39:05.841  5677  5677 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-15 03:39:05.842   925   943 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-15 03:39:05.842   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fb52c3c00
09-15 03:39:05.842   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-15 03:39:05.846   925  2707 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,09-15 03:39:05.849   925  2707 I hubconnection: sensorhub said: 'activate 7 enable:0'
,09-15 03:39:06.151   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-15 03:39:06.153   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-15 03:39:06.154   925  3110 D SurfaceControl: Excessive delay in setPowerMode(): 312ms
,09-15 03:39:06.170   925   945 I DreamManagerService: Entering dreamland.
,09-15 03:39:06.177   925   945 I PowerManagerService: Dozing...
09-15 03:39:06.178   925   940 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-15 03:39:06.198  3545  3545 W Binder_7: type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[37079]" dev="sockfs" ino=37079 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 03:39:06.198  3545  3545 W Binder_7: type=1400 audit(0.0:147): avc: denied { ioctl } for path="socket:[37079]" dev="sockfs" ino=37079 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-15 03:39:06.203   925  3178 I sensors : batch
09-15 03:39:06.203   925  3178 I sensors : activate
,09-15 03:39:06.206   925  2707 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,09-15 03:39:06.208   925  2707 I hubconnection: sensorhub said: 'activate 21 enable:1'
09-15 03:39:06.212   925   925 I sensors : activate
09-15 03:39:06.213   511  3063 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-15 03:39:06.215   925  2707 I hubconnection: sensorhub said: 'activate 31 enable:0'
,09-15 03:39:06.222   925  3001 E native  : do suspend true
,09-15 03:39:06.250  3532  4511 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,09-15 03:39:06.250  3532  4511 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-15 03:39:06.250  3532  4511 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-15 03:39:06.251   524  1219 D         : oem-qmi: Connection accepted
09-15 03:39:06.251   524  1219 D         : oem-qmi: Waiting to accept connection
,09-15 03:39:06.258  3532  4511 D         : oem_qmi_lib:output 0
,09-15 03:39:06.258  3532  4511 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-15 03:39:10.288  3166  3166 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-15 03:39:10.366  3166  3166 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,09-15 03:39:10.383  3166  3166 W PathParser: Points are too far apart 4.030360828967057
,09-15 03:39:10.383  3166  3166 W PathParser: Points are too far apart 4.030360538880159
,09-15 03:39:11.151   925  3001 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-15 03:39:22.205   534  1674 E QC-QMI  : qmi_client [534] 9: failed to locate client data
,09-15 03:39:22.208   518   518 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
,09-15 03:39:22.209   518   518 E QC-QMI  : QMUX qmux_client_id=9 not found in qmux client list, unable to remove
09-15 03:39:22.210   534   534 I Atfwd_Daemon: Stop the daemon....
,09-15 03:39:22.264  6102  6102 I libmdmdetect: ESOC framework not supported
,09-15 03:39:22.265  6102  6102 I libmdmdetect: Found internal modem: modem
09-15 03:39:22.261  6102  6102 W ATFWD-daemon: type=1400 audit(0.0:148): avc: denied { read write } for name="diag" dev="tmpfs" ino=12485 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-15 03:39:22.266  6102  6102 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 03:39:22.272  6102  6102 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-15 03:39:22.272  6102  6102 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-15 03:39:22.273  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:23.274  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:24.276  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:25.277  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:26.278  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:27.279  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:39:32.280  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:33.281  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:34.282  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:35.284  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:36.285  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:37.286  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:39:47.287  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:48.289  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:49.290  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:50.291  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:51.292  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:39:52.293  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:40:05.250  3431  3596 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-15 03:40:05.250  3431  3596 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-15 03:40:05.283  3614  3614 I ConfigService: onCreate
,09-15 03:40:07.294  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:08.295  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:09.296  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:10.297  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:10.316  3614  3614 I ConfigService: onDestroy
,09-15 03:40:11.298  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:12.299  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:40:32.301  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:33.302  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:34.303  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:35.305  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:36.306  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:40:37.307  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:41:02.307  6102  6102 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:41:02.308  6102  6102 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:41:07.309  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:08.310  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:09.311  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:10.312  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:11.313  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:12.314  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:41:17.315  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:18.317  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:19.318  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:20.320  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:21.321  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:22.322  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:41:32.324  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:33.325  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:34.326  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:35.327  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:36.328  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:37.329  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:41:52.331  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:53.332  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:54.334  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:55.335  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:56.336  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:41:57.337  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:42:17.339  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:18.340  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:19.341  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:20.342  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:21.343  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:22.344  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:42:47.344  6102  6102 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:42:47.345  6102  6102 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:42:57.346  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:58.347  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:42:59.348  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:00.350  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:01.351  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:02.351  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:43:07.353  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:08.354  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:09.356  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:10.357  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:11.359  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:12.359  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:43:22.361  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:23.362  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:24.364  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:25.365  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:26.367  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:27.368  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:43:42.369  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:43.370  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:44.371  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:45.372  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:46.374  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:43:47.374  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:44:07.376  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:08.377  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:09.378  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:10.379  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:11.380  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:12.381  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:44:37.382  6102  6102 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:44:37.382  6102  6102 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:44:52.383  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:53.384  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:54.385  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:55.386  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:56.387  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:44:57.388  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:45:02.390  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:03.391  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:04.392  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:05.393  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:06.395  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:07.395  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:45:17.397  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:18.398  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:19.399  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:20.400  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:21.401  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:22.402  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:45:37.403  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:38.405  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:39.406  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:40.407  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:41.408  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:45:42.409  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:46:02.410  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:03.412  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:04.413  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:05.415  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:06.416  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:07.417  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:46:32.418  6102  6102 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:46:32.418  6102  6102 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:46:52.419  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:53.421  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:54.422  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:55.424  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:56.425  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:46:57.426  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:47:02.427  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:03.429  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:04.430  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:05.431  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:06.433  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:07.434  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:47:17.435  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:18.437  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:19.438  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:20.440  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:21.441  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:22.442  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:47:37.444  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:38.446  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:39.447  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:40.448  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:41.450  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:47:42.451  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:48:02.452  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:03.454  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:04.455  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:05.456  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:06.457  6102  6102 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:07.458  6102  6102 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:48:32.459  6102  6102 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:48:32.459  6102  6102 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:48:57.469  6102  6104 E QC-QMI  : qmi_client [6102] 1d: failed to locate client data
,09-15 03:48:57.472   518   518 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
,09-15 03:48:57.472   518   518 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-15 03:48:57.479  6102  6102 I Atfwd_Daemon: Stop the daemon....
,09-15 03:48:57.524  6118  6118 I libmdmdetect: ESOC framework not supported
,09-15 03:48:57.525  6118  6118 I libmdmdetect: Found internal modem: modem
,09-15 03:48:57.525  6118  6118 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 03:48:57.521  6118  6118 W ATFWD-daemon: type=1400 audit(0.0:149): avc: denied { read write } for name="diag" dev="tmpfs" ino=12485 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-15 03:48:57.531  6118  6118 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-15 03:48:57.531  6118  6118 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
09-15 03:48:57.532  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:58.534  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:48:59.535  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:00.537  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:01.538  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:02.539  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:49:05.017   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:49:07.540  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:08.541  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:09.543  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:10.544  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:11.545  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:12.546  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:49:22.547  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:23.549  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:24.550  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:25.551  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:26.552  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:27.217   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1195130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:49:27.553  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:49:30.057   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1197970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:49:42.554  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:43.555  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:44.556  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:45.557  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:46.558  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:49:47.559  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:49:51.596   925   937 I UsageStatsService: User[0] Flushing usage stats to disk
,09-15 03:49:52.271   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1220184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:49:55.105   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1223017, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:50:07.560  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:08.562  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:09.563  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:10.564  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:11.566  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:12.567  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:50:17.312   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:50:20.139   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1248051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:50:37.568  6118  6118 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:50:37.568  6118  6118 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:50:42.351   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-15 03:50:42.569  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:43.571  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:44.572  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:45.574  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:46.575  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:47.576  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:50:50.191   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1278104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:50:52.577  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:53.578  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:54.579  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:55.581  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:56.582  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:50:57.583  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:51:07.391   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:51:07.584  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:08.585  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:09.587  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:10.225   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1298137, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:51:10.588  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:11.590  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:12.590  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:51:27.592  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:28.593  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:29.595  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:30.596  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:31.597  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:32.431   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:51:32.598  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:51:35.271   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1323183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:51:52.599  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:53.601  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:54.602  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:55.604  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:56.604  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:51:57.471   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:51:57.605  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:52:00.311   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1348223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:52:22.511   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:52:22.606  6118  6118 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:52:22.606  6118  6118 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:52:25.351   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1373263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:52:32.607  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:33.608  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:34.610  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:35.611  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:36.612  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:37.614  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:52:42.615  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:43.616  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:44.617  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:45.618  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:46.620  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:47.551   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:52:47.621  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:52:50.398   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1398310, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:52:57.622  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:58.623  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:52:59.625  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:00.626  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:01.627  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:02.628  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:53:12.605   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:53:15.458   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1423370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:53:17.629  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:18.631  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:19.632  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:20.633  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:21.634  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:22.635  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:53:37.658   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:53:40.491   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1448403, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:53:42.636  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:43.637  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:44.638  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:45.639  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:46.641  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:53:47.641  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:54:02.698   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1470610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:54:05.698   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1473610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:54:12.642  6118  6118 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:54:12.643  6118  6118 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:54:27.644  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:27.765   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1495677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:54:28.645  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:29.647  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:30.648  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:30.745   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1498657, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:54:31.649  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:32.650  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:54:37.651  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:38.653  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:39.654  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:40.656  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:41.657  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:42.658  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:54:52.659  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:52.818   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1520730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:54:53.661  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:54.662  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:55.664  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:55.791   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1523704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:54:56.666  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:54:57.666  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:55:12.668  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:13.669  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:14.671  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:15.672  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:16.674  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:17.674  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:55:17.871   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1545783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:55:20.838   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1548750, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:55:37.676  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:38.677  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:39.679  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:40.680  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:41.681  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:55:42.681  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:55:42.911   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1570823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:55:45.912   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1573824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:56:07.682  6118  6118 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:56:07.683  6118  6118 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:56:07.978   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1595890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:56:10.952   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1598864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:56:27.684  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:28.685  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:29.686  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:30.688  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:31.689  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:32.689  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:56:33.018   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1620930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:56:35.991   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1623904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:56:37.691  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:38.692  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:39.694  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:40.695  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:41.697  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:42.698  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:56:52.699  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:53.701  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:54.702  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:55.703  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:56.705  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:56:57.705  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:56:58.058   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1645970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:57:01.031   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1648943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:57:12.706  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:13.708  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:14.709  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:15.711  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:16.712  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:17.712  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 03:57:23.098   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1671010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:57:26.072   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1673984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:57:37.713  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:38.715  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:39.716  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:40.717  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:41.718  6118  6118 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:57:42.718  6118  6118 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 03:57:48.138   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1696050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:57:51.111   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1699023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:58:07.719  6118  6118 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 03:58:07.720  6118  6118 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 03:58:13.178   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1721091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:58:16.151   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1724064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:58:32.731  6118  6120 E QC-QMI  : qmi_client [6118] 1e: failed to locate client data
,09-15 03:58:32.735   518   518 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
,09-15 03:58:32.735   518   518 E QC-QMI  : QMUX qmux_client_id=1e not found in qmux client list, unable to remove
09-15 03:58:32.737  6118  6118 I Atfwd_Daemon: Stop the daemon....
,09-15 03:58:32.788  6131  6131 W ATFWD-daemon: type=1400 audit(0.0:150): avc: denied { read write } for name="diag" dev="tmpfs" ino=12485 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-15 03:58:32.789  6131  6131 I libmdmdetect: ESOC framework not supported
09-15 03:58:32.790  6131  6131 I libmdmdetect: Found internal modem: modem
09-15 03:58:32.791  6131  6131 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 03:58:32.801  6131  6131 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-15 03:58:32.801  6131  6131 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
09-15 03:58:32.802  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:33.804  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:34.806  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:35.807  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:36.808  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:37.809  6131  6131 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 03:58:38.218   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1746130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 03:58:41.204   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1749116, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 03:58:42.811  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:43.812  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:44.814  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:45.815  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:46.816  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:47.817  6131  6131 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 03:58:57.818  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:58.819  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:58:59.821  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:59:00.822  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:59:01.824  6131  6131 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 03:59:02.825  6131  6131 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 03:59:03.271   925  6036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1771184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms)
```
