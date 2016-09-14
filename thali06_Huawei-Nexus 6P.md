#### Test 852025184f78031_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of system
,09-14 10:24:29.994   923  2953 I PowerManagerService: Waking up from dozing (uid 1000)...
--------- beginning of main
09-14 10:24:29.995   923   923 V KeyguardServiceDelegate: onStartedWakingUp()
09-14 10:24:30.004   923   943 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
09-14 10:24:30.004   923   943 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@b8b54c5)
09-14 10:24:30.005   923   923 I sensors : batch
09-14 10:24:30.005   923   923 I sensors : activate
09-14 10:24:30.007   511  3025 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-14 10:24:30.007   923   943 I sensors : batch
09-14 10:24:30.008   923   943 I sensors : activate
09-14 10:24:30.010   384   384 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7f8da83c00
09-14 10:24:30.011   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-14 10:24:30.006  5563  5563 W mdss_fb0: type=1400 audit(0.0:105): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-14 10:24:30.015   923   941 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
09-14 10:24:30.016   923  3467 V KeyguardServiceDelegate: **** SHOWN CALLED ****
09-14 10:24:30.021   923  2761 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
09-14 10:24:30.022   923  2761 I hubconnection: sensorhub said: 'activate 31 enable:1'
09-14 10:24:30.024   923  2761 I hubconnection: sensorhub said: 'batch 7 flags:0, sampling_rate_Hz:4.00, max_report_latency_us:0'
09-14 10:24:30.025   923  2761 I hubconnection: sensorhub said: 'activate 7 enable:1'
09-14 10:24:30.035   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-14 10:24:30.035   923  2961 E native  : do suspend false
09-14 10:24:30.041  3115  3115 W PathParser: Points are too far apart 4.030360828967057
09-14 10:24:30.041  3115  3115 W PathParser: Points are too far apart 4.030360538880159
09-14 10:24:30.054   923  2961 D WifiConfigStore: No blacklist allowed without epno enabled
09-14 10:24:30.064  3525  4558 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
09-14 10:24:30.064  3525  4558 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-14 10:24:30.065  3525  4558 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-14 10:24:30.065   524  1157 D         : oem-qmi: Connection accepted
09-14 10:24:30.065   524  1157 D         : oem-qmi: Waiting to accept connection
09-14 10:24:30.072  3525  4558 D         : oem_qmi_lib:output 0
09-14 10:24:30.072  3525  4558 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
09-14 10:24:30.078   923   943 I DisplayPowerController: Unblocked screen on after 75 ms
09-14 10:24:30.079   923   943 V KeyguardServiceDelegate: onScreenTurnedOn()
09-14 10:24:30.080   923   943 I DreamManagerService: Gently waking up from dream.
09-14 10:24:30.081   923   934 I DreamManagerService: Leaving dreamland.
09-14 10:24:30.081   923   938 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
09-14 10:24:30.083   923  3467 I sensors : activate
09-14 10:24:30.086   923  2761 I hubconnection: sensorhub said: 'activate 21 enable:0'
09-14 10:24:30.105  3115  3115 W PathParser: Points are too far apart 4.030360828967057
09-14 10:24:30.105  3115  3115 W PathParser: Points are too far apart 4.030360538880159
09-14 10:24:30.173   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
09-14 10:24:30.169  5585  5585 W irq/504-synapti: type=1400 audit(0.0:106): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-14 10:24:30.175   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
09-14 10:24:30.176   923  3072 D SurfaceControl: Excessive delay in setPowerMode(): 167ms
09-14 10:24:30.194   388   388 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x9 conn_h=0x7f7a27a010
09-14 10:24:30.194   388   388 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x6: req_h=0x9 msg_id=3: R/W request received
09-14 10:24:30.195   388   388 I rmt_storage: wakelock acquired: 1, error no: 42
09-14 10:24:30.195   388   489 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x6 Unblock worker thread (th_id: 547505570880)
09-14 10:24:30.221   388   489 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x6: req_h=0x9 msg_id=3: Bytes written = 1572864
09-14 10:24:30.221   388   489 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x6: req_h=0x9 msg_id=3: Send response: res=0 err=0
09-14 10:24:30.221   388   489 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x6 About to block rmt_storage client thread (th_id: 547505570880) wakelock released: 1, error no: 0
09-14 10:24:30.221   388   489 I rmt_storage: 
09-14 10:24:30.222   388   388 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x9 conn_h=0x7f7a27a010
09-14 10:24:30.237   506   917 D TetherController: Setting IP forward enable = 1
09-14 10:24:30.416  5565  5565 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 10:24:30.419  5565  5565 D AndroidRuntime: CheckJNI is OFF
09-14 10:24:30.442  5565  5565 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 10:24:30.469  5565  5565 I Radio-JNI: register_android_hardware_Radio DONE
09-14 10:24:30.484  5565  5565 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-14 10:24:30.487   923  3201 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-14 10:24:30.514   923  3201 I ActivityManager: Start proc 5615:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-14 10:24:30.526  5565  5565 D AndroidRuntime: Shutting down VM
,09-14 10:24:30.840   923   934 I WindowManager: Screenshot max retries 4 of Token{faa5d4b ActivityRecord{3854e1a u0 com.test.thalitest/.MainActivity t4}} appWin=Window{2c78672 u0 Starting com.test.thalitest} drawState=2
,09-14 10:24:30.887  5615  5615 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-14 10:24:30.910  5615  5615 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-14 10:24:30.934  5615  5615 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 5060-5080)
,09-14 10:24:30.934  5615  5615 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-14 10:24:30.953  5615  5615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a85dcb7}
,09-14 10:24:30.953  5615  5615 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 10:24:30.953  5615  5615 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-14 10:24:30.956  5615  5615 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-14 10:24:30.957  5615  5615 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-14 10:24:30.989  5615  5615 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-14 10:24:30.998  5615  5615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-14 10:24:30.998  5615  5615 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 10:24:30.998  5615  5615 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-14 10:24:30.998  5615  5615 I Adreno  : Build Date                       : 12/06/15
09-14 10:24:30.998  5615  5615 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 10:24:30.998  5615  5615 I Adreno  : Local Branch                     : mybranch17112971
09-14 10:24:30.998  5615  5615 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-14 10:24:30.998  5615  5615 I Adreno  : Remote Branch                    : NONE
09-14 10:24:30.998  5615  5615 I Adreno  : Reconstruct Branch               : NOTHING
,09-14 10:24:31.034   923   940 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@147f3b1:true
,09-14 10:24:31.062  3115  3115 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME RECENT clock SEARCH quick_settings >
,09-14 10:24:31.063   923  3422 D ActivityManager: awakeFromSleepingLocked: previously pausing activity didn't pause
,09-14 10:24:31.066  2352  2352 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[34935]" dev="sockfs" ino=34935 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.066  2352  2352 W Binder_3: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[34935]" dev="sockfs" ino=34935 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.086  5615  5615 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-14 10:24:31.091   511  2973 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-14 10:24:31.093  3115  3115 D PhoneStatusBar: disable: < expand icons* alerts system_info* back HOME RECENT clock SEARCH quick_settings >
,09-14 10:24:31.097  5615  5615 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-14 10:24:31.104   511  2973 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
09-14 10:24:31.104   511  2973 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
,09-14 10:24:31.106   511  2973 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-14 10:24:31.123  3115  3115 D PhoneStatusBar: disable: < expand icons alerts system_info back home* recent* clock search* quick_settings >
,09-14 10:24:31.124   511  2973 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-14 10:24:31.127   511  2973 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-14 10:24:31.132  3623  3623 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,09-14 10:24:31.139  5615  5661 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 10:24:31.133  5577  5577 W Binder_5: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[35842]" dev="sockfs" ino=35842 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-14 10:24:31.133  5577  5577 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[35842]" dev="sockfs" ino=35842 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.139  3467  3467 W Binder_7: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[15736]" dev="sockfs" ino=15736 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.139  3467  3467 W Binder_7: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[15736]" dev="sockfs" ino=15736 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.152  5615  5644 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-14 10:24:31.178  5615  5661 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 10:24:31.226   933   933 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[35847]" dev="sockfs" ino=35847 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 10:24:31.231   923   941 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +389ms (total +732ms)
09-14 10:24:31.226   933   933 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[35847]" dev="sockfs" ino=35847 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.226  3421  3421 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[35846]" dev="sockfs" ino=35846 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:24:31.229  3421  3421 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[35846]" dev="sockfs" ino=35846 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 10:24:31.234  3392  3392 I Keyboard.Facilitator: onFinishInput()
,09-14 10:24:31.260  5615  5615 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5615
,09-14 10:24:31.322  5615  5615 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 10:24:31.475  5615  5666 D jxcore_app_log: JniHelper::setJavaVM(0xf4e3c000), pthread_self() = -568063696
,09-14 10:24:31.482  5615  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 10:24:31.482  5615  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 10:24:31.482  5615  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 10:24:31.482  5615  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 10:24:31.482  5615  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-14 10:24:31.483  5615  5666 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7dc105 added. We now have 1 listener(s)
,09-14 10:24:31.485  5615  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-14 10:24:31.485  5615  5666 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 10:24:31.485  5615  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 10:24:31.486  5615  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-14 10:24:31.489  5615  5666 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e4c68 added. We now have 1 listener(s)
09-14 10:24:31.490  5615  5666 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:24:31.496   923  2965 D WifiService: New client listening to asynchronous messages
,09-14 10:24:31.497  5615  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 10:24:31.497  5615  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-14 10:24:31.497  5615  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-14 10:24:31.497  5615  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-14 10:24:31.497  5615  5666 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-14 10:24:31.500  5615  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:24:31.500  5615  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-14 10:24:31.507  5615  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:31.507  5615  5666 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:24:31.507  5615  5666 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 10:24:31.507  5615  5666 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 10:24:31.508  5615  5666 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 10:24:31.510  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:31.512  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:31.536  5615  5615 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 10:24:31.858   511  2973 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-14 10:24:31.859   511  2973 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-14 10:24:31.862  5615  5672 W jxcore-log: Initializing JXcore engine
,09-14 10:24:31.863  5615  5672 W jxcore-log: JXcore engine is ready
,09-14 10:24:31.867   511  2973 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-14 10:24:31.886  5672  5672 W Thread-57: type=1400 audit(0.0:117): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12471 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-14 10:24:31.886  5672  5672 W Thread-57: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[16401]" dev="sockfs" ino=16401 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-14 10:24:31.886  5672  5672 W Thread-57: type=1400 audit(0.0:119): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-14 10:24:31.886  5672  5672 W Thread-57: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[16795]" dev="sockfs" ino=16795 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-14 10:24:31.898  5615  5672 W jxcore-log: Starting JXcore engine
,09-14 10:24:31.952  5615  5672 W jxcore-log: Platform android
09-14 10:24:31.952  5615  5672 W jxcore-log: 
,09-14 10:24:31.952  5615  5672 W jxcore-log: Process ARCH arm
09-14 10:24:31.952  5615  5672 W jxcore-log: 
,09-14 10:24:32.058  5615  5672 I jxcore-log: JXcore Cordova bridge is ready!
09-14 10:24:32.058  5615  5672 I jxcore-log: 
,09-14 10:24:32.059  5615  5672 W jxcore-log: JXcore engine is started
,09-14 10:24:32.066  5615  5666 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-14 10:24:32.069  5615  5615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 10:24:33.054   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:35.855  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:36.080   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:36.116   923  5172 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2070263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 10:24:36.857  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:37.858  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:38.859  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:39.860  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:40.861  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 10:24:41.926  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 10:24:41.926  5615  5672 I jxcore-log: 
,09-14 10:24:41.928  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 10:24:41.928  5615  5672 I jxcore-log: 
,09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:41.932  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:24:41.933  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:24:41.935  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 10:24:41.935  5615  5672 I jxcore-log: 
,09-14 10:24:41.936  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 10:24:41.936  5615  5672 I jxcore-log: 
,09-14 10:24:42.134   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:42.179  5615  5672 I jxcore-log: Running unit tests
09-14 10:24:42.179  5615  5672 I jxcore-log: 
,09-14 10:24:42.180  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 10:24:42.180  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fda1da added. We now have 2 listener(s)
,09-14 10:24:42.180  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:24:42.180  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:24:42.180  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:24:42.181  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 10:24:42.181  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ea860b added. We now have 2 listener(s)
09-14 10:24:42.181  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:24:42.181  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 10:24:42.182  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:42.185  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:24:42.185  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:42.186  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:24:42.186  5615  5672 D executeNativeTests: Running unit tests
,09-14 10:24:42.191  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:42.197  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:42.222  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 10:24:42.222  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 added. We now have 3 listener(s)
,09-14 10:24:42.223  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:24:42.223  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:24:42.223  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:24:42.223  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:24:42.223  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 added. We now have 3 listener(s)
09-14 10:24:42.223  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:24:42.223  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 10:24:42.225  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:42.227  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:24:42.228  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:42.228  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 10:24:42.229  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 10:24:42.229  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 10:24:42.229  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 10:24:42.229  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 10:24:42.230  5615  5672 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-14 10:24:42.230  5615  5672 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 10:24:42.230  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 10:24:42.230  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 10:24:42.230  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 10:24:42.230  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-14 10:24:42.230  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:24:42.231  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:42.231  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:24:42.231  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:24:42.231  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.231  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:24:42.231  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 10:24:42.232  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 removed from the list
09-14 10:24:42.232  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:42.232  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 removed from the list
09-14 10:24:42.232  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:24:42.233  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:24:42.233  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.233  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.233  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.234  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:24:42.234  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:24:42.234  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:24:42.234  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:42.235  5615  5672 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-14 10:24:42.235  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:24:42.235  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:42.235  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:24:42.235  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:24:42.235  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.235  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.235  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:24:42.235  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:42.235  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:42.237  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:24:42.238  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:24:42.238  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.238  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.238  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.238  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.238  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:24:42.239  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:24:42.239  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:42.239  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 10:24:42.241  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 10:24:42.242  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:24:42.242  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:42.242  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:24:42.242  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:24:42.242  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.242  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.242  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:24:42.242  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:42.242  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:42.242  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:24:42.242  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.242  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.242  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:42.242  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:42.243  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:24:42.243  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:24:42.243  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:42.243  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:42.243  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 10:24:42.244  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:42.246  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:24:42.247  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:42.247  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:24:42.247  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:24:42.247  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:24:42.247  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:24:42.247  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:24:42.247  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 10:24:42.250  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:24:42.250  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:24:42.250  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:24:42.251  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:24:42.253  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:24:42.254  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:24:42.254  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:24:42.255  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-14 10:24:42.256  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-14 10:24:42.256  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:24:42.256  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:24:42.256  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:24:42.257  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:24:42.258  4442  4688 D BtGatt.GattService: registerClient() - UUID=77d7f0f9-a024-450e-8779-73ada33f2c5f
09-14 10:24:42.259  4442  4528 D BtGatt.GattService: onClientRegistered() - UUID=77d7f0f9-a024-450e-8779-73ada33f2c5f, clientIf=5
09-14 10:24:42.260  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:24:42.261  4442  4457 D BtGatt.GattService: start scan with filters
09-14 10:24:42.266  4442  4536 D BtGatt.ScanManager: handling starting scan
09-14 10:24:42.266  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:24:42.267  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:24:42.267  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:24:42.267  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 10:24:42.268  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:24:42.268  4442  4536 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
09-14 10:24:42.268  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:24:42.268  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:24:42.268  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 10:24:42.270  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
09-14 10:24:42.275  4442  4528 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:24:42.275  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:24:42.276  4442  4536 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 10:24:42.283  4442  4528 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:24:42.283  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:42.284  4442  4536 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:24:42.284  4442  4536 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 10:24:42.295  4442  4528 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 10:24:42.295  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:42.301  4442  4528 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 10:24:42.301  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:24:42.770  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 10:24:42.771  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:24:42.771  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:24:45.152   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:45.158   923  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-14 10:24:45.862  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:46.864  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:47.274  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:24:47.274  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:47.274  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 10:24:47.274  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:47.274  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 10:24:47.274  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:24:47.275  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-14 10:24:47.275  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:24:47.275  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:24:47.275  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:24:47.276  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 10:24:47.277  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:24:47.278  4442  4688 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:24:47.279  4442  4457 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:24:47.280  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 10:24:47.281  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-14 10:24:47.281  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 10:24:47.281  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:24:47.281  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 10:24:47.283  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:24:47.284  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:24:47.284  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:24:47.284  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:24:47.286  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 10:24:47.287  4442  4442 D BtGatt.ScanManager: awakened up at time 2081434
09-14 10:24:47.290  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:24:47.290  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:24:47.290  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:47.290  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:24:47.290  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:24:47.291  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:24:47.291  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:24:47.291  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:24:47.291  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:47.291  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:24:47.291  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:47.294  4442  4528 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:24:47.294  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:47.294  4442  4536 D BtGatt.ScanManager: stopping BLe Batch
,09-14 10:24:47.305  4442  4528 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 10:24:47.305  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:47.306  4442  4536 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:24:47.331  4442  4528 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:24:47.331  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:47.332  4442  4528 D BtGatt.GattService: current time is 2081479096404
09-14 10:24:47.333  4442  4528 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -76, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:24:47.335  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:24:47.336  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:24:47.336  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:24:47.336  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:24:47.337  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-14 10:24:47.337  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-14 10:24:47.792  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:24:47.865  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:48.191   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:48.198   923  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-14 10:24:48.866  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:49.851   923  5172 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2083998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:24:49.867  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:24:50.868  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 10:24:52.293  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-14 10:24:52.298  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:52.310  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:24:52.315  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:24:52.315  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:24:52.315  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:24:52.315  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:24:52.315  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:24:52.315  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:24:52.316  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 10:24:52.319  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:52.320  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 10:24:52.321  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:24:52.322  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:52.325  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:24:52.325  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:24:52.325  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:24:52.329  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:24:52.329  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 10:24:52.329  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:24:52.330  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:24:52.332  4442  4688 D BtGatt.GattService: registerClient() - UUID=010eaa24-0dfe-4556-83b9-dc68362bf588
09-14 10:24:52.333  4442  4528 D BtGatt.GattService: onClientRegistered() - UUID=010eaa24-0dfe-4556-83b9-dc68362bf588, clientIf=5
09-14 10:24:52.334  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:24:52.334  4442  4667 D BtGatt.GattService: start scan with filters
,09-14 10:24:52.337  4442  4536 D BtGatt.ScanManager: handling starting scan
09-14 10:24:52.337  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:24:52.337  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:24:52.337  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:24:52.337  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 10:24:52.340  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 10:24:52.340  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:24:52.341  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 10:24:52.343  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
09-14 10:24:52.344  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:24:52.344  4442  4528 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:24:52.344  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.345  4442  4536 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 10:24:52.345  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:24:52.345  5615  5672 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 10:24:52.345  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:52.345  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:24:52.345  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:52.346  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 10:24:52.346  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:24:52.346  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:24:52.346  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:24:52.346  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-14 10:24:52.346  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 10:24:52.346  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 10:24:52.347  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:24:52.348  4442  4688 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:24:52.348  4442  4667 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:24:52.349  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:24:52.349  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:24:52.349  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 10:24:52.349  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-14 10:24:52.349  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 10:24:52.350  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:24:52.350  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:24:52.350  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:24:52.350  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:24:52.351  4442  4528 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:24:52.351  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.351  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:24:52.351  4442  4536 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:24:52.351  4442  4536 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 10:24:52.352  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:24:52.352  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:24:52.352  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:52.352  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:24:52.352  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:24:52.352  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:24:52.352  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:24:52.352  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:52.352  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:52.352  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:24:52.352  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:52.354  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:52.354  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:24:52.355  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:24:52.355  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:24:52.355  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:24:52.355  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:24:52.355  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 10:24:52.357  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:24:52.361  4442  4528 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 10:24:52.361  4442  4528 D BtGatt.ScanM,anager: callback done for clientIf - 5 status - 0
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:24:52.361  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:24:52.363  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:24:52.363  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:24:52.363  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:24:52.363  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:24:52.364  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:24:52.364  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:24:52.364  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 10:24:52.366  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:52.368  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:24:52.368  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 10:24:52.368  4442  4528 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 10:24:52.368  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.370  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:24:52.372  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:24:52.372  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:24:52.373  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:24:52.375  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 10:24:52.375  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:24:52.375  4442  4528 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:24:52.375  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:24:52.376  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.376  4442  4536 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:24:52.376  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:24:52.378  4442  4457 D BtGatt.GattService: registerClient() - UUID=4b67f4f9-54e7-4576-9b50-2e9af9889078
09-14 10:24:52.379  4442  4528 D BtGatt.GattService: onClientRegistered() - UUID=4b67f4f9-54e7-4576-9b50-2e9af9889078, clientIf=5
09-14 10:24:52.379  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:24:52.379  4442  4455 D BtGatt.GattService: start scan with filters
,09-14 10:24:52.380  4442  4528 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:24:52.380  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.380  4442  4536 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:24:52.381  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:24:52.381  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 10:24:52.382  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:24:52.382  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 10:24:52.384  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:24:52.384  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:24:52.384  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:24:52.385  4442  4528 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:24:52.385  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.385  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 10:24:52.386  4442  4536 D BtGatt.ScanManager: handling starting scan
09-14 10:24:52.387  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:24:52.392  4442  4528 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 10:24:52.392  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:52.392  4442  4536 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:24:52.397  4442  4528 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:24:52.397  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:24:52.397  4442  4536 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:24:52.397  4442  4536 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:24:52.405  4442  4528 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:24:52.405  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:24:52.410  4442  4528 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:24:52.410  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:24:52.885  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-14 10:24:52.886  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 10:24:52.886  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:24:54.241   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:54.244   923  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-14 10:24:57.271   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-14 10:24:57.278   923  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-14 10:24:57.387  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:24:57.388  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:57.388  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:24:57.388  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:24:57.388  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 10:24:57.388  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:24:57.388  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:24:57.389  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:24:57.389  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:24:57.389  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:24:57.389  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 10:24:57.391  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:24:57.392  4442  4455 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:24:57.394  4442  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:24:57.394  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 10:24:57.395  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:24:57.395  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 10:24:57.395  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:24:57.395  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 10:24:57.399  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:24:57.400  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:24:57.400  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 10:24:57.400  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:24:57.402  4442  4442 D BtGatt.ScanManager: awakened up at time 2091549
09-14 10:24:57.403  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:24:57.405  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:24:57.406  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 10:24:57.406  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:24:57.410  4442  4528 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 10:24:57.411  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:57.411  4442  4536 D BtGatt.ScanManager: stopping BLe Batch
,09-14 10:24:57.421  4442  4528 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 10:24:57.422  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:57.422  4442  4536 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:24:57.442  4442  4528 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:24:57.442  4442  4528 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:24:57.442  4442  4528 D BtGatt.GattService: current time is 2091589345061
09-14 10:24:57.442  4442  4528 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -81, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -72, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:24:57.443  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:24:57.443  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:24:57.443  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:24:57.444  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:24:57.444  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:24:57.444  4442  4528 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:24:57.907  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:24:57.907  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:24:57.907  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:25:00.870  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:01.872  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:02.407  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:25:02.407  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:25:02.407  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:25:02.407  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.408  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:02.408  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:25:02.408  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
,09-14 10:25:02.408  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.408  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.408  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.409  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:02.412  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.412  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.416  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.417  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.417  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:02.417  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.420  5615  5672 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-14 10:25:02.422  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:25:02.423  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.423  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.424  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.424  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.424  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.424  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.425  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.425  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.425  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.425  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.426  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.426  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.427  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.429  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.429  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.429  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.429  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.430  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 10:25:02.430  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.431  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.431  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.431  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.431  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.431  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.431  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.431  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.431  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Di,scoveryManager@7c62056 not in the list
09-14 10:25:02.431  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.431  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.431  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.431  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.431  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.433  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.433  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.434  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.434  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.435  5615  5672 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-14 10:25:02.435  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.435  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.435  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.435  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.435  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:02.435  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.435  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.435  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.435  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:02.436  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.436  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.436  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.436  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.436  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.438  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.438  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.438  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.438  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:02.440  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-14 10:25:02.440  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.440  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.441  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.441  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.441  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.441  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.441  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.441  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.441  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.441  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 10:25:02.441  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.441  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.442  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.442  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.443  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.444  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 10:25:02.444  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.444  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.445  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 10:25:02.445  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 10:25:02.445  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 10:25:02.445  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 10:25:02.445  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 10:25:02.445  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 10:25:02.445  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 10:25:02.446  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 10:25:02.446  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 10:25:02.446  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.446  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.447  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.447  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.447  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.447  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.447  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.447  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.447  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.447  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.447  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.447  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.447  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.447  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.450  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.450  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.450  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.450  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.451  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 10:25:02.452  5615  5672 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 10:25:02.452  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 10:25:02.456  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-14 10:25:02.456  5615  5672 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-14 10:25:02.456  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 10:25:02.456  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 10:25:02.456  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 10:25:02.456  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 10:25:02.456  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 10:25:02.457  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 10:25:02.458  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 10:25:02.458  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 10:25:02.458  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 10:25:02.458  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 10:25:02.458  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 10:25:02.458  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-14 10:25:02.458  5615  5672 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-14 10:25:02.458  5615  5672 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-14 10:25:02.458  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 10:25:02.458  5615  5672 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 10:25:02.459  5615  5672 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-14 10:25:02.459  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 10:25:02.459  5615  5672 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 10:25:02.459  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-14 10:25:02.462  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-14 10:25:02.463  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-14 10:25:02.463  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-14 10:25:02.464  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-14 10:25:02.464  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-14 10:25:02.464  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-14 10:25:02.464  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 10:25:02.464  5615  5672 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-14 10:25:02.464  5615  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-14 10:25:02.465  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.465  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.465  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.465  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.465  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.465  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.466  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-14 10:25:02.467  5615  5675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:02.467  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.467  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.467  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.467  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.467  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.467  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.467  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:02.467  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.468  5615  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-14 10:25:02.468  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.468  5615  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-14 10:25:02.468  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.468  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.468  5615  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-14 10:25:02.468  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.463  4688  4688 W Binder_4: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[30447]" dev="sockfs" ino=30447 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:25:02.466  4688  4688 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[30447]" dev="sockfs" ino=30447 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:25:02.469  5615  5672 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-14 10:25:02.470  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.470  5615  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-14 10:25:02.470  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.470  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.470  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.470  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.470  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.470  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.470  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.470  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.470  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.470  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.470  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.470  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.470  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:02.471  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:02.472  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.472  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:02.472  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.474  5615  5672 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-14 10:25:02.474  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.474  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.474  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.475  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.475  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.475  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:02.475  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.475  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.475  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.475  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.475  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.475  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.475  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.475  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.476  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 10:25:02.476  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.476  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.476  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:02.477  5615  5672 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-14 10:25:02.477  5615  5672 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-14 10:25:02.477  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 10:25:02.477  5615  5672 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-14 10:25:02.477  5615  5672 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 10:25:02.477  5615  5672 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-14 10:25:02.477  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 10:25:02.477  5615  5672 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-14 10:25:02.477  5615  5672 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 10:25:02.477  5615  5672 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-14 10:25:02.477  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 10:25:02.477  5615  5672 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-14 10:25:02.477  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:02.477  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:02.477  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:02.478  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.478  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.478  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:02.478  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.478  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.478  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.478  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.478  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.478  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.478  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.478  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.479  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 10:25:02.479  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:02.479  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.479  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:02.480  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:02.480  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.480  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:02.480  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:02.480  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:02.480  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:02.480  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:02.480  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:02.480  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:02.873  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:03.875  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:04.876  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:05.876  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 10:25:07.481  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:07.481  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:07.481  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 10:25:07.481  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.482  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:07.482  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
,09-14 10:25:07.482  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:07.482  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:25:07.482  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:07.483  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:07.483  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.483  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.483  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:07.483  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:07.484  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.484  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:07.484  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.484  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.484  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.484  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.487  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:07.488  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:07.488  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.488  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.493  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 10:25:07.495  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:25:07.497  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 10:25:07.498  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 10:25:07.499  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 10:25:07.500  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-14 10:25:07.500  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 10:25:07.500  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:25:07.501  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:07.501  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 10:25:07.501  5615  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:25:07.501  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 10:25:07.501  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 10:25:07.501  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.501  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 10:25:07.501  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:07.501  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 10:25:07.501  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:07.501  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:25:07.501  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:25:07.501  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:25:07.502  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.502  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.499  4455  4455 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[30449]" dev="sockfs" ino=30449 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:25:07.499  4455  4455 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[30449]" dev="sockfs" ino=30449 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:25:07.503  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:25:07.503  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.503  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:25:07.503  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:25:07.503  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:07.503  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:25:07.503  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:25:07.503  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:07.504  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:07.504  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.504  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.504  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:07.504  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:07.504  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:07.504  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:07.504  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.504  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.504  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.504  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.505  5615  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 10:25:07.505  5615  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 10:25:07.505  5615  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-14 10:25:07.505  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 10:25:07.506  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:07.506  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:07.506  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.506  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
,09-14 10:25:07.508  5615  5672 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-14 10:25:07.508  5615  5672 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 10:25:07.508  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 10:25:07.508  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 10:25:07.508  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 10:25:07.509  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:07.509  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:07.509  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:25:07.509  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:07.509  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.509  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.509  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:07.509  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:07.509  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.509  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:07.509  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.509  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.509  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.510  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.511  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:07.511  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:07.511  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.511  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.516  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:25:07.516  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:07.516  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:25:07.516  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:07.516  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.516  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.516  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
,09-14 10:25:07.516  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.516  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.516  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:07.517  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.517  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.517  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.517  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.518  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:07.519  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:07.519  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.519  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.520  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:25:07.520  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:25:07.520  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:25:07.520  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:25:07.520  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.520  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.520  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f775a71 not in the list
09-14 10:25:07.520  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.521  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.521  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:07.521  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:07.521  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.521  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:07.521  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:07.522  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:25:07.522  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:25:07.522  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:07.522  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c62056 not in the list
09-14 10:25:07.523  5615  5672 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-14 10:25:07.524  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 10:25:07.524  5615  5672 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-14 10:25:07.524  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 10:25:07.524  5615  5672 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-14 10:25:07.524  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-14 10:25:07.526  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 10:25:07.526  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-14 10:25:07.527  5615  5672 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-14 10:25:07.527  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 10:25:07.527  5615  5672 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-14 10:25:07.527  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 10:25:07.527  5615  5672 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-14 10:25:07.527  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-14 10:25:07.528  5615  5672 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-14 10:25:07.528  5615  5672 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-14 10:25:07.528  5615  5672 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-14 10:25:07.528  5615  5672 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-14 10:25:07.529  5615  5672 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-14 10:25:07.529  5615  5672 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-14 10:25:07.530  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:25:07.530  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a0af48 added. We now have 3 listener(s)
09-14 10:25:07.530  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:25:07.532  5615  5672 D BluetoothAdapter: enable(): BT is already enabled..!
,09-14 10:25:07.532   923  3135 D WifiService: setWifiEnabled: true pid=5615, uid=10077
09-14 10:25:07.532   923  3135 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 10:25:07.595  4442  4651 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-14 10:25:07.596  4442  4665 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-14 10:25:08.004  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:25:12.538  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 10:25:12.538  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@882c1e1 added. We now have 4 listener(s)
,09-14 10:25:12.538  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:25:12.551  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:12.551  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@882c1e1 removed from the list
09-14 10:25:12.552  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 10:25:12.552  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:12.552  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:25:12.554  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:25:12.554  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc54b06 added. We now have 4 listener(s)
,09-14 10:25:12.554  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:25:12.557  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:12.558  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc54b06 removed from the list
09-14 10:25:12.558  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:12.558  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:12.558  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:12.559  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:25:12.560  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c80f5c7 added. We now have 4 listener(s)
,09-14 10:25:12.560  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:25:12.564   923  3467 D WifiService: setWifiEnabled: false pid=5615, uid=10077
,09-14 10:25:12.564   923  3467 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 10:25:12.569   923  2961 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-14 10:25:12.569   923  2961 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 10:25:12.569   923  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 10:25:12.569   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 10:25:12.574  4442  4520 D BluetoothAdapterState: Current state: ON, message: 23
09-14 10:25:12.574  4442  4520 D BluetoothAdapterProperties: Setting state to 13
09-14 10:25:12.574  4442  4520 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-14 10:25:12.577  4442  4520 D BluetoothAdapterProperties: onBluetoothDisable()
,09-14 10:25:12.577  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:25:12.580  4442  4520 I BluetoothAdapterState: Entering PendingCommandState
09-14 10:25:12.581  4442  4528 D BluetoothAdapterProperties: Scan Mode:20
09-14 10:25:12.581  4442  4520 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 10:25:12.582  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:12.583  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:25:12.584  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.584  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:12.584   506   917 D CommandListener: Clearing all IP addresses on wlan0
09-14 10:25:12.585  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 10:25:12.585   923  5173 D DhcpClient: Clearing IP address
09-14 10:25:12.588  4442  4442 D HeadsetService: Received stop request...Stopping profile...
09-14 10:25:12.589  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.589   506   917 D CommandListener: Setting iface cfg
09-14 10:25:12.591   923  5174 D DhcpClient: Receive thread stopped
09-14 10:25:12.592  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.593   923   923 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:12.593   923   923 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:12.594  3115  3378 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:12.594  3115  3115 D HeadsetProfile: Bluetooth service disconnected
09-14 10:25:12.594  3600  5226 V NativeCrypto: Read error: ssl=0x7f706ec000: I/O error during system call, Connection timed out
,09-14 10:25:12.595   923   923 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:12.596  3525  3751 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:12.597  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:12.597  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:25:12.598  4442  4442 D A2dpService: Received stop request...Stopping profile...
09-14 10:25:12.598  4442  4680 D A2dpStateMachine: Exit Disconnected: -1
,09-14 10:25:12.599  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.599  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:12.600  3600  5226 V NativeCrypto: SSL shutdown failed: ssl=0x7f706ec000: I/O error during system call, Broken pipe
09-14 10:25:12.604   923   934 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-14 10:25:12.604   923   923 D BluetoothA2dp: Proxy object disconnected
09-14 10:25:12.605   923  5171 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-14 10:25:12.605  3115  3115 D BluetoothA2dp: Proxy object disconnected
09-14 10:25:12.605  4442  4442 V BluetoothAdapterState: isTurningOff()=true
,09-14 10:25:12.605  4442  4442 V BluetoothAdapterState: isTurningOn()=false
,09-14 10:25:12.605  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 10:25:12.605  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.606  4442  4442 D HidService: Received stop request...Stopping profile...
09-14 10:25:12.606  4442  4442 D HidService: Stopping Bluetooth HidService
09-14 10:25:12.607  3115  3115 D BluetoothInputDevice: Proxy object disconnected
09-14 10:25:12.607  3115  3115 D HidProfile: Bluetooth service disconnected
09-14 10:25:12.609  4442  4442 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 10:25:12.609  4442  4442 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 10:25:12.609  4442  4651 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:12.609  4442  4651 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 10:25:12.609  4442  4651 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:12.610  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.610  4442  4528 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:12.610  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:25:12.610  4442  4442 D HealthService: Received stop request...Stopping profile...
09-14 10:25:12.610  4442  4528 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 10:25:12.612  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.612  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:25:12.613  4442  4442 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:12.614  4442  4442 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:12.614  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:12.614  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.615   923  5171 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-14 10:25:12.615   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-14 10:25:12.616   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-14 10:25:12.617   923  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-14 10:25:12.619  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.619  4442  4651 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:12.619  4442  4651 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:12.620  4442  4651 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 10:25:12.620  4442  4651 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 10:25:12.620  4442  4651 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 10:25:12.620  4442  4651 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 10:25:12.620  4442  4528 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-14 10:25:12.620  4442  4442 V BluetoothAdapterState: isTurningOff()=true
,09-14 10:25:12.620  4442  4442 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:12.620  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:12.620  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.620  4442  4442 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 10:25:12.621  4442  4442 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 10:25:12.621  4442  4528 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 10:25:12.621  4442  4442 D PanService: Received stop request...Stopping profile...
,09-14 10:25:12.628   923   936 I ActivityManager: Start proc 5683:com.google.android.talk/u0a53 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-14 10:25:12.633  4442  4442 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:12.633  4442  4442 V BluetoothAdapterState: isTurningOn()=false
,09-14 10:25:12.633  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:12.633  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.633   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 10:25:12.634   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-14 10:25:12.634  4442  4442 D BluetoothMapService: Received stop request...Stopping profile...
09-14 10:25:12.634  4442  4442 D BluetoothMapService: stop()
09-14 10:25:12.635  3115  3115 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 10:25:12.635  3115  3115 D PanProfile: Bluetooth service disconnected
09-14 10:25:12.636  4442  4442 D BluetoothMapAppObserver: deinitObservers()
09-14 10:25:12.636  4442  4442 D BluetoothMapAppObserver: removeReceiver()
,09-14 10:25:12.638   536   536 E Parcel  : Reading a NULL string not supported here.
,09-14 10:25:12.639  4442  4442 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-14 10:25:12.640  4442  4442 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-14 10:25:12.640  4442  4528 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 10:25:12.640  4442  4442 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:12.640  4442  4442 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:12.640  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:12.640  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.640  4442  4442 D SapService: Received stop request...Stopping profile...
09-14 10:25:12.641  4442  4442 V SapService: stop()
09-14 10:25:12.642   923  2966 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-14 10:25:12.642   923   923 D RttService: SCAN_AVAILABLE : 1
09-14 10:25:12.643   923  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 10:25:12.644  4442  4442 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-14 10:25:12.644  4442  4442 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 10:25:12.644  3488  3635 W QCNEJ   : |CORE| network lost: 100
09-14 10:25:12.645  3488  3635 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-14 10:25:12.647  4442  4442 D BluetoothMapService: MAP Service closeService in
09-14 10:25:12.647  4442  4442 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 10:25:12.647  4442  4442 D ObexServerSockets0: shutdown(block = true)
09-14 10:25:12.646  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.647  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:25:12.648  4442  4442 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-14 10:25:12.648  4442  4690 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-14 10:25:12.648  4442  4442 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 10:25:12.648  4442  4691 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 10:25:12.648  4442  4665 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 10:25:12.649  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.649  4442  4442 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:12.649  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:12.649  4442  4442 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:12.649  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 10:25:12.649  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.649  4442  4442 D BluetoothMapService: cleanup()
09-14 10:25:12.650  4442  4442 D BluetoothMapService: MAP Service closeService in
09-14 10:25:12.650  4442  4442 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:12.650  4442  4442 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:12.650  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:12.650  4442  4442 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:12.651  4442  4520 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 10:25:12.651  4442  4520 D BluetoothAdapterProperties: Setting state to 15
09-14 10:25:12.651  4442  4520 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 10:25:12.651  4442  4442 I BtOppRfcommListener: stopping Accept Thread
09-14 10:25:12.651  4442  4520 I BluetoothAdapterState: Entering BleOnState
09-14 10:25:12.651  4442  5125 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 10:25:12.651  4442  5125 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 10:25:12.652  3115  3378 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 10:25:12.653  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.653  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 10:25:12.653  3115  3128 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 10:25:12.654  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.654  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:12.655  3115  3709 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:12.655   923   940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:12.655  3115  3127 D BluetoothMap: onBluetoothStateChange: up=false
09-14 10:25:12.656   923  2961 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 10:25:12.657  3525  3572 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:12.657   923   940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:12.658   923   940 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 10:25:12.658   923   940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:12.658  3115  3709 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 10:25:12.658  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.659  3115  3378 D BluetoothPan: onBluetoothStateChange on: false
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.659  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:12.660  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.660  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:12.663  4442  4520 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 10:25:12.663  4442  4520 D BluetoothAdapterProperties: Setting state to 16
09-14 10:25:12.663  4442  4520 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-14 10:25:12.664   923  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 10:25:12.664  4442  4520 D BluetoothAdapterProperties: onBleDisable
09-14 10:25:12.664  4442  4520 I BluetoothAdapterState: Entering PendingCommandState
09-14 10:25:12.664  4442  4523 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 10:25:12.666  4442  4528 D BluetoothAdapterProperties: Scan Mode:20
09-14 10:25:12.668  4442  4651 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 10:25:12.668  4442  4651 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 10:25:12.670  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.670  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:12.671  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.673  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.673   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 10:25:12.674  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.675  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.676  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.693  5683  5683 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-14 10:25:12.694   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 10:25:12.694   506   917 D CommandListener: Clearing all IP addresses on wlan0
,09-14 10:25:12.696   923  2966 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-14 10:25:12.696   923  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 10:25:12.696   923  2961 D DhcpClient: doQuit
09-14 10:25:12.696   923  2961 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-14 10:25:12.697   923  5173 D DhcpClient: onQuitting
09-14 10:25:12.697  3654  3654 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-14 10:25:12.698   923   940 D Tethering: MasterInitialState.processMessage what=3
,09-14 10:25:12.702  4795  4795 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-14 10:25:12.703  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.703  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:12.704  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.704  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:12.705  4872  4889 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-14 10:25:12.706  4872  4889 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 10:25:12.706  4872  4889 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-14 10:25:12.706  4872  4889 E SarControlService: no key has been found,reset the power
,09-14 10:25:12.706  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 10:25:12.706  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 10:25:12.706  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 10:25:12.707  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:12.707  4902  4902 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 10:25:12.707  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 10:25:12.707  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 10:25:12.707  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.707  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.707  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:12.708  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:12.708  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 10:25:12.708  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:12.708  4902  4902 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-14 10:25:12.709  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:12.709  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:12.710  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:12.710  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:12.711  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.711  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.712  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:12.714  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000ea03000000000000ffffffff]
09-14 10:25:12.714  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:12.714  4902  4916 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-14 10:25:12.714  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:12.715  4872  4883 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-14 10:25:12.720  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000eb03000000000000ffffffff]
,09-14 10:25:12.720  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:12.720  4902  4916 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-14 10:25:12.721  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:12.721  4872  4884 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-14 10:25:12.723  3654  3654 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-14 10:25:12.728  3654  3654 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 10:25:12.752   506   917 E Netd    : netlink response contains error (No such file or directory)
,09-14 10:25:12.753   923  2966 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-14 10:25:12.753   923  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 10:25:12.763  3654  3654 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-14 10:25:12.776  3654  3654 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-14 10:25:12.855  5683  5708 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-14 10:25:12.855  5683  5708 I Babel_SMS: MmsConfig.loadMmsSettings
,09-14 10:25:12.857  5683  5708 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://wap1.huawei.com/uaprof/HUAWEI_angler-Uaprofile.xml
,09-14 10:25:12.858  5683  5708 I Babel_SMS: MmsConfig.loadFromDatabase
,09-14 10:25:12.875  4442  4528 I bt_hci  : shut_down
,09-14 10:25:12.879   923  2961 D wifi    : In wifi stop Hal
,09-14 10:25:12.879   923  2961 D wifi    : halHandle = 0x7f6fa08c00, mVM = 0x7f8b7cd140, mCls = 0x100bc2
09-14 10:25:12.879   923  3652 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-14 10:25:12.879   923  3652 D WifiHAL : Got a signal to exit!!!
09-14 10:25:12.879   923  3652 I WifiHAL : Exit wifi_event_loop
09-14 10:25:12.880   923  2961 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-14 10:25:12.880   923  2961 E WifiHAL : Event processing terminated
09-14 10:25:12.880   923  2961 D wifi    : In wifi cleaned up handler
09-14 10:25:12.880   923  2961 I WifiHAL : Internal cleanup completed
,09-14 10:25:12.880  4442  4537 D bt_hwcfg: hw_epilog_process
09-14 10:25:12.881  4442  4537 I bt_vendor: low_power_mode_cb
09-14 10:25:12.881  3623  4028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 10:25:12.882  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.883  4442  4537 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-14 10:25:12.883  4442  4537 I bt_vendor: epilog_cb
09-14 10:25:12.883  4442  4537 I bt_hci  : epilog_finished_callback
09-14 10:25:12.884  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.885  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:12.885  4442  4528 I bt_hci_h4: hal_close
,09-14 10:25:12.886  4442  4528 I bt_userial_vendor: device fd = 54 close
,09-14 10:25:12.903   923  3652 D wifi    : set interface wlan0 flags (DOWN)
,09-14 10:25:12.903   923  2961 D WifiNative-HAL: HAL event thread stopped successfully
,09-14 10:25:12.912  5683  5708 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-14 10:25:12.912  5683  5708 I Babel_SMS: MmsConfig.loadFromResources
09-14 10:25:12.913  5683  5708 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-14 10:25:12.914  5683  5708 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://wap1.huawei.com/uaprof/HUAWEI_angler-Uaprofile.xml
,09-14 10:25:12.921  5683  5683 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 10:25:12.925  5683  5683 I Babel_Crash: startup - clean
,09-14 10:25:12.947  5683  5683 I Babel_telephony: TeleModule.launchCompleted
,09-14 10:25:12.952   923  3829 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-14 10:25:12.963   506   917 E Netd    : netlink response contains error (No such file or directory)
,09-14 10:25:12.964  5683  5683 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-14 10:25:12.973  5683  5683 W Babel   : BAM#gBA: invalid account id: -1
,09-14 10:25:12.974  5683  5683 W Babel   : BAM#gBA: invalid account id: -1
09-14 10:25:12.974  5683  5683 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-14 10:25:12.977   923   933 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-14 10:25:13.005   923  3135 I ActivityManager: Start proc 5720:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-14 10:25:13.010  4442  4523 D bt_stack_manager: event_shut_down_stack finished.
,09-14 10:25:13.010  4442  4520 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-14 10:25:13.011  4442  4520 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-14 10:25:13.011  4442  4442 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 10:25:13.013  4442  4442 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 10:25:13.013  4442  4442 D BtGatt.GattService: stop()
09-14 10:25:13.013  4442  4442 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 10:25:13.014  4442  4442 V BluetoothAdapterState: isTurningOff()=false
,09-14 10:25:13.016  4442  4442 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:13.016  4442  4442 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:13.017  4442  4442 V BluetoothAdapterState: isBleTurningOff()=true
09-14 10:25:13.017  4442  4520 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 10:25:13.017  4442  4520 D BluetoothAdapterProperties: Setting state to 10
09-14 10:25:13.017  4442  4520 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 10:25:13.018  4442  4520 I BluetoothAdapterState: Entering OffState
,09-14 10:25:13.018   923   940 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-14 10:25:13.024  4442  4442 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 10:25:13.024  4442  4442 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 10:25:13.024  4442  4442 I BluetoothServiceJni: cleanupNative: return from cleanup
09-14 10:25:13.025  4442  4523 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 10:25:13.038  4442  4523 D bt_stack_manager: event_clean_up_stack finished.
,09-14 10:25:13.042  4442  4442 I art     : System.exit called, status: 0
,09-14 10:25:13.042  4442  4442 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 10:25:13.074  5720  5720 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-14 10:25:13.087  5683  5683 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-14 10:25:13.105   923   940 D Tethering: InitialState.processMessage what=4
,09-14 10:25:13.108   923   940 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-14 10:25:13.111   923  3422 I ActivityManager: Process com.android.bluetooth (pid 4442) has died
,09-14 10:25:13.111   923  3422 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,09-14 10:25:13.118  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 10:25:13.132   923   940 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a73a60:true
,09-14 10:25:13.138   923  3421 I ActivityManager: Start proc 5733:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-14 10:25:13.190  5720  5720 D LocalBluetoothProfileManager: Adding local MAP profile
,09-14 10:25:13.192  5720  5720 D BluetoothMap: Create BluetoothMap proxy object
,09-14 10:25:13.220  5720  5720 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-14 10:25:13.234  5683  5683 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-14 10:25:13.253  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,09-14 10:25:13.263   923  3543 I ActivityManager: Killing 3405:android.process.acore/u0a2 (adj 15): empty for 2013s
,09-14 10:25:13.274  5683  5683 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-14 10:25:13.287  5683  5683 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-14 10:25:13.294  5683  5683 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-14 10:25:13.306  5683  5683 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-14 10:25:13.311   923  3829 I ActivityManager: Killing 5303:com.google.android.partnersetup/u0a18 (adj 15): empty for 2013s
,09-14 10:25:13.340  5683  5683 I vclib   : onServiceConnected
,09-14 10:25:13.344  5733  5733 D AdapterServiceConfig: Adding HeadsetService
09-14 10:25:13.344  5733  5733 D AdapterServiceConfig: Adding A2dpService
09-14 10:25:13.345  5733  5733 D AdapterServiceConfig: Adding HidService
09-14 10:25:13.345  5733  5733 D AdapterServiceConfig: Adding HealthService
09-14 10:25:13.345  5733  5733 D AdapterServiceConfig: Adding PanService
09-14 10:25:13.345  5733  5733 D AdapterServiceConfig: Adding GattService
09-14 10:25:13.345  5733  5733 D AdapterServiceConfig: Adding BluetoothMapService
09-14 10:25:13.345  5733  5733 D AdapterServiceConfig: Adding SapService
,09-14 10:25:13.358  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 10:25:13.373   923   940 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@214c4af:true
,09-14 10:25:13.375  5720  5720 D BluetoothPbap: Proxy object connected
,09-14 10:25:13.375  5720  5720 D PbapServerProfile: Bluetooth service connected
,09-14 10:25:13.378  5720  5720 D BluetoothPbap: Proxy object disconnected
,09-14 10:25:13.378  5720  5720 D PbapServerProfile: Bluetooth service disconnected
,09-14 10:25:13.391   923  3543 I ActivityManager: Start proc 5748:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-14 10:25:13.393   923  3543 I ActivityManager: Killing 5320:com.android.musicfx/u0a21 (adj 15): empty for 2013s
,09-14 10:25:13.431  5748  5748 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-14 10:25:13.590  5748  5748 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 10:25:13.590  5748  5748 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.590  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.591  5748  5748 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.591  5748  5748 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.591  5748  5748 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.k.d(PG:583)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.591  5748  5748 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.591  5748  5748 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.591  5748  5748 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 10:25:13.591  5748  5748 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 10:25:13.595  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 10:25:13.602  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 10:25:13.614  5720  5720 D DockEventReceiver: finishStartingService: stopping service
09-14 10:25:13.617   923  3829 I ActivityManager: Killing 5090:com.google.android.gms.wearable/u0a12 (adj 15): empty for 2013s
,09-14 10:25:13.665  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 10:25:13.671  3900  5196 I iu.UploadsManager: num queued entries: 0
,09-14 10:25:13.671  3900  5196 I iu.UploadsManager: num updated entries: 0
09-14 10:25:13.672  3900  5196 I iu.SyncManager: NEXT; no task
,09-14 10:25:13.673  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 10:25:13.675  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 10:25:13.686   923   934 I ActivityManager: Start proc 5776:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-14 10:25:13.724  5776  5776 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-14 10:25:13.726  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 10:25:13.732  5776  5776 D SprintDMHelper: simOperator: 
09-14 10:25:13.732  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 10:25:13.743   923  3543 I ActivityManager: Start proc 5789:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-14 10:25:13.744   923  3543 I ActivityManager: Killing 4795:com.google.android.googlequicksearchbox:search/u0a29 (adj 15): empty for 2013s
,09-14 10:25:13.788   923  2965 D WifiService: Client connection lost with reason: 4
,09-14 10:25:13.867   923  3201 I ActivityManager: Start proc 5804:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-14 10:25:13.871  5683  5803 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-14 10:25:13.874   923   934 I ActivityManager: Killing 5342:com.google.android.apps.docs/u0a43 (adj 15): empty for 2013s
,09-14 10:25:13.949  5804  5804 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-14 10:25:14.132  5748  5763 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-14 10:25:14.140   923  3829 I ActivityManager: Killing 4653:com.android.vending/u0a22 (adj 15): empty for 1999s
,09-14 10:25:14.171   923   940 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e923f2:true
,09-14 10:25:14.229   923  3829 I ActivityManager: Start proc 5818:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-14 10:25:14.263  5818  5818 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-14 10:25:17.588   923  3543 D WifiService: setWifiEnabled: true pid=5615, uid=10077
,09-14 10:25:17.588   923  3543 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 10:25:17.598   506   917 D SoftapController: Softap fwReload - Ok
,09-14 10:25:17.603   506   917 D CommandListener: Setting iface cfg
09-14 10:25:17.603   506   917 D CommandListener: Trying to bring down wlan0
,09-14 10:25:17.605   506   917 D CommandListener: Clearing all IP addresses on wlan0
,09-14 10:25:17.611   923  2961 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 10:25:18.189   923  2961 D wifi    : set interface wlan0 flags (UP)
,09-14 10:25:18.194   923  2961 I WifiHAL : Initializing wifi
,09-14 10:25:18.194   923  2961 I WifiHAL : Creating socket
,09-14 10:25:18.202   923  2961 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-14 10:25:18.202   923  2961 D wifi    : Did set static halHandle = 0x7f6fa08c00
09-14 10:25:18.202   923  2961 D wifi    : halHandle = 0x7f6fa08c00, mVM = 0x7f8b7cd140, mCls = 0x1976
09-14 10:25:18.202   923  2961 D wifi    : array field set
09-14 10:25:18.202   923   940 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-14 10:25:18.204   923  2961 I WifiNative-HAL: interface[0] = wlan0
09-14 10:25:18.213   923  5839 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547333639168
,09-14 10:25:18.213   923  5839 D wifi    : waitForHalEvents called, vm = 0x7f8b7cd140, obj = 0x1976, env = 0x7f6b778500
,09-14 10:25:18.272  5840  5840 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-14 10:25:18.284  5840  5840 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 10:25:18.307   923  2961 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 10:25:18.310  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:18.312  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:18.312  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:18.331  5840  5840 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 10:25:18.331  5840  5840 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-14 10:25:18.347  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:18.347  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:18.347  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 10:25:18.347  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:18.348   923  2961 D WifiConfigStore: Loading config and enabling all networks 
09-14 10:25:18.348  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:18.348  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:18.349  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:18.349  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:18.350  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:18.350  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 10:25:18.350  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:18.350  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:18.357   923  2961 D WifiConfigStore: loaded 0 passpoint configs
,09-14 10:25:18.357   923  2961 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 10:25:18.358   923  2961 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-14 10:25:18.359   923  2961 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-14 10:25:18.360   923  2961 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-14 10:25:18.360   923  2961 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-14 10:25:18.360   923  2961 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-14 10:25:18.360   923  2961 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 10:25:18.364   923  2961 D WifiNative-HAL: Setting external_sim to 1
09-14 10:25:18.365   923  2961 D wifi    : setting dfs flag to true, 0x7f70078c40
09-14 10:25:18.365   923  2961 D WifiStateMachine: Setting OUI to DA-A1-19
,09-14 10:25:18.365   923  2961 D wifi    : setting scan oui 0x7f70078c40
09-14 10:25:18.365   923  2961 D WifiHAL : Sending mac address OUI
,09-14 10:25:18.367  5683  5683 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 10:25:18.369   923  2961 E native  : do suspend false
,09-14 10:25:18.376   923  2961 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-14 10:25:18.376   506   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-14 10:25:18.377   923   923 D RttService: SCAN_AVAILABLE : 3
09-14 10:25:18.377   923  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-14 10:25:18.377   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:18.381   923  2960 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '66 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 66 Failed to set address (No such device)'
,09-14 10:25:18.381   923  2960 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 10:25:18.395   923   938 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=2112542 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
09-14 10:25:18.395   923  2960 D WifiNative-HAL: p2pGetDeviceAddress
09-14 10:25:18.396   923  2960 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-14 10:25:20.878  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:21.569  5840  5840 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:21.574  5840  5840 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:21.578  5840  5840 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:21.584  5840  5840 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:21.639   923  2961 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-14 10:25:21.641   923  2961 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-14 10:25:21.641   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 10:25:21.657   923  2961 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-14 10:25:21.697   923  2961 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
09-14 10:25:21.698  5840  5840 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 10:25:21.879  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:22.130  5840  5840 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 10:25:22.173  5840  5840 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 10:25:22.174  5840  5840 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-14 10:25:22.188   923  2961 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 10:25:22.188   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 10:25:22.188   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-14 10:25:22.208   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 10:25:22.222   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:22.229   923  2961 D WifiStateMachine: Start Dhcp Watchdog 2
,09-14 10:25:22.237   923  5855 D DhcpClient: Receive thread started
,09-14 10:25:22.243   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 10:25:22.244   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 10:25:22.244   923  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-14 10:25:22.333   923  2961 E native  : do suspend false
,09-14 10:25:22.355   923  5854 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 10:25:22.368   923  5855 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170724, domain null
,09-14 10:25:22.369   923  5854 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170724 seconds
,09-14 10:25:22.372   923  5854 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-14 10:25:22.387   923  5855 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-14 10:25:22.388   923  5854 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-14 10:25:22.391   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:22.398   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 10:25:22.401   923  5854 D DhcpClient: Scheduling renewal in 86399s
,09-14 10:25:22.415   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-14 10:25:22.421   923  2961 D WifiConfigStore: No blacklist allowed without epno enabled
09-14 10:25:22.423   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-14 10:25:22.431   923  2961 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 10:25:22.428   923  2966 D ConnectivityService: Adding iface wlan0 to network 101
,09-14 10:25:22.473   923  2966 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-14 10:25:22.473   923  2966 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-14 10:25:22.475   923  2966 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-14 10:25:22.477   923  2966 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-14 10:25:22.478   923  2966 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-14 10:25:22.485   923  2966 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 10:25:22.489   923  2966 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-14 10:25:22.489   923  2966 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-14 10:25:22.490   923  2966 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-14 10:25:22.490   923  2961 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-14 10:25:22.490   923  2966 D ConnectivityService:    accepting network in place of null
09-14 10:25:22.490   923  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 10:25:22.490   923  2966 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 10:25:22.499   923  5853 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2116645, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:25:22.516   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 10:25:22.537   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 10:25:22.540   923  2966 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 10:25:22.540   923  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 10:25:22.541  3488  3635 W QCNEJ   : |CORE| network available: 101
,09-14 10:25:22.542  3488  3635 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-14 10:25:22.543   923  2966 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-14 10:25:22.543  3488  3635 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-14 10:25:22.544  3488  3635 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-14 10:25:22.545   923   940 D Tethering: MasterInitialState.processMessage what=3
,09-14 10:25:22.548  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:22.548  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:25:22.548  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.548  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:25:22.551  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:22.552  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:25:22.552  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.552  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:22.554  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:22.554  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:25:22.554  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.555  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:25:22.558  4872  4889 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-14 10:25:22.558  4872  4889 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 10:25:22.558  4872  4889 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-14 10:25:22.558  4872  4889 E SarControlService: no key has been found,reset the power
09-14 10:25:22.558  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 10:25:22.558  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 10:25:22.558  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 10:25:22.559  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:22.559  4902  4902 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-14 10:25:22.561  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 10:25:22.561  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 10:25:22.561  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-14 10:25:22.562  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:22.562  4902  4902 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-14 10:25:22.566  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000ec03000000000000ffffffff]
09-14 10:25:22.566  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:22.566  4902  4916 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-14 10:25:22.569  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:22.570  4872  4883 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-14 10:25:22.574  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000ed03000000000000ffffffff]
09-14 10:25:22.574  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:22.574  4902  4916 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-14 10:25:22.574  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:22.574  4872  4884 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-14 10:25:22.580  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-14 10:25:22.588  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 10:25:22.589   923  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
09-14 10:25:22.591  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 10:25:22.593  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 10:25:22.595   923  3201 D WifiService: setWifiEnabled: false pid=5615, uid=10077
09-14 10:25:22.596   923  3201 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 10:25:22.597   923  2961 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-14 10:25:22.597   923  2961 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 10:25:22.598   923  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 10:25:22.598   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 10:25:22.599  5776  5776 D SprintDMHelper: simOperator: 
09-14 10:25:22.599  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-14 10:25:22.586  3900  5196 I iu.UploadsManager: num queued entries: 0
,09-14 10:25:22.606   506   917 D CommandListener: Clearing all IP addresses on wlan0
09-14 10:25:22.607   923  5854 D DhcpClient: Clearing IP address
09-14 10:25:22.607  3900  5196 I iu.UploadsManager: num updated entries: 0
,09-14 10:25:22.608  3900  5196 I iu.SyncManager: NEXT; no task
,09-14 10:25:22.609   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:22.616   923  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:800::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-14 10:25:22.616   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-14 10:25:22.618   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 10:25:22.618   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-14 10:25:22.622   923   923 D RttService: SCAN_AVAILABLE : 1
09-14 10:25:22.622   536   536 E Parcel  : Reading a NULL string not supported here.
09-14 10:25:22.622   923  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 10:25:22.622   923  2966 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-14 10:25:22.624  3488  3635 W QCNEJ   : |CORE| network lost: 101
09-14 10:25:22.624  3488  3635 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-14 10:25:22.629   923  2961 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-14 10:25:22.631   923  5855 D DhcpClient: Receive thread stopped
09-14 10:25:22.632   923  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 10:25:22.639  5683  5868 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-14 10:25:22.639  5683  5868 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-14 10:25:22.647   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 10:25:22.667   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 10:25:22.668   506   917 D CommandListener: Clearing all IP addresses on wlan0
,09-14 10:25:22.669   923  2966 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 10:25:22.669   923  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 10:25:22.671   923   940 D Tethering: MasterInitialState.processMessage what=3
09-14 10:25:22.672   923  2961 D DhcpClient: doQuit
,09-14 10:25:22.672   923  2961 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-14 10:25:22.672  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.672  5840  5840 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:22.672  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:22.672   923  5854 D DhcpClient: onQuitting
09-14 10:25:22.673  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.673  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:22.673  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:22.674  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:22.674  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.674  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:22.675  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:  ,   - is Bluetooth enabled: false
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:22.675  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:22.676  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.677  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:22.678  4872  4889 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-14 10:25:22.679  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:22.679  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:22.679  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.679  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:22.681  4872  4889 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 10:25:22.681  4872  4889 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-14 10:25:22.682  4872  4889 E SarControlService: no key has been found,reset the power
09-14 10:25:22.682  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:22.682  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 10:25:22.682  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.682  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:22.682  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 10:25:22.682  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 10:25:22.682  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 10:25:22.683  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:22.683  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:22.683  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:22.683  4902  4902 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 10:25:22.683  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:22.683  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:22.687  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-14 10:25:22.687  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 10:25:22.687  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 10:25:22.688  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:22.688  4902  4902 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-14 10:25:22.691  5840  5840 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-14 10:25:22.692  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 10:25:22.696  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000ee03000000000000ffffffff]
09-14 10:25:22.696  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:22.696  4902  4916 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,09-14 10:25:22.696  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:22.696  4872  4884 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-14 10:25:22.697  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000ef03000000000000ffffffff]
09-14 10:25:22.697  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:22.697  4902  4916 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-14 10:25:22.697  5840  5840 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 10:25:22.698  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-14 10:25:22.698  4872  4883 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-14 10:25:22.700  3900  5196 I iu.UploadsManager: num queued entries: 0
09-14 10:25:22.701  3900  5196 I iu.UploadsManager: num updated entries: 0
09-14 10:25:22.701  3900  5196 I iu.SyncManager: NEXT; no task
09-14 10:25:22.702  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-14 10:25:22.704  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 10:25:22.706  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 10:25:22.711  5776  5776 D SprintDMHelper: simOperator: 
09-14 10:25:22.711  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 10:25:22.723  5683  5881 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-14 10:25:22.728   506   917 E Netd    : netlink response contains error (No such file or directory)
09-14 10:25:22.729  5840  5840 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-14 10:25:22.729   923  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 10:25:22.732  5840  5840 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-14 10:25:22.834   923  2961 D wifi    : In wifi stop Hal
09-14 10:25:22.834   923  2961 D wifi    : halHandle = 0x7f6fa08c00, mVM = 0x7f8b7cd140, mCls = 0x1976
09-14 10:25:22.834   923  5839 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-14 10:25:22.834   923  5839 D WifiHAL : Got a signal to exit!!!
09-14 10:25:22.834   923  5839 I WifiHAL : Exit wifi_event_loop
09-14 10:25:22.834   923  2961 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-14 10:25:22.834   923  2961 E WifiHAL : Event processing terminated
09-14 10:25:22.835   923  2961 D wifi    : In wifi cleaned up handler
09-14 10:25:22.835   923  2961 I WifiHAL : Internal cleanup completed
09-14 10:25:22.835  5683  5683 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 10:25:22.837  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:22.837  3623  4028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 10:25:22.838  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:22.839  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:22.858   923  5839 D wifi    : set interface wlan0 flags (DOWN)
09-14 10:25:22.858   923  2961 D WifiNative-HAL: HAL event thread stopped successfully
,09-14 10:25:22.880  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:22.921   506   917 E Netd    : netlink response contains error (No such file or directory)
,09-14 10:25:23.065   923   940 D Tethering: InitialState.processMessage what=4
,09-14 10:25:23.072   923   940 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-14 10:25:23.541   923  2966 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-14 10:25:23.880  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:24.881  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:25.882  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 10:25:27.632  5733  5733 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 10:25:27.640  5733  5733 I bt_bluedroid: init
,09-14 10:25:27.640  5733  5889 I BluetoothAdapterState: Entering OffState
,09-14 10:25:27.645  5733  5890 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-14 10:25:27.645  5733  5890 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 10:25:27.646  5733  5890 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 10:25:27.646  5733  5890 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-14 10:25:27.647  5733  5733 I bt_bluedroid: get_profile_interface socket
,09-14 10:25:27.650  5733  5893 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 10:25:27.651  5733  5733 I bt_bluedroid: get_profile_interface sdp
09-14 10:25:27.653  5733  5893 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 10:25:27.660  5733  5743 I bt_bluedroid: config_hci_snoop_log
,09-14 10:25:27.663   923   940 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 10:25:27.671  5733  5889 D BluetoothAdapterState: Current state: OFF, message: 0
09-14 10:25:27.671  5733  5889 D BluetoothAdapterProperties: Setting state to 14
,09-14 10:25:27.671  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 10:25:27.674  5733  5889 D BluetoothBondStateMachine: make
,09-14 10:25:27.677  5733  5894 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 10:25:27.682  5733  5889 I BluetoothAdapterState: Entering PendingCommandState
,09-14 10:25:27.683  5733  5733 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 10:25:27.687  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
,09-14 10:25:27.688  5733  5733 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 10:25:27.689  5733  5733 D BtGatt.GattService: Received start request. Starting profile...
09-14 10:25:27.689  5733  5733 D BtGatt.GattService: start()
,09-14 10:25:27.689  5733  5733 I bt_bluedroid: get_profile_interface gatt
09-14 10:25:27.691  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
,09-14 10:25:27.691  5733  5733 D BtGatt.AdvertiseManager: advertise manager created
,09-14 10:25:27.699  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:27.700  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:27.700  5733  5733 V BluetoothAdapterState: isBleTurningOn()=true
09-14 10:25:27.700  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:27.700  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 10:25:27.703  5733  5889 I bt_bluedroid: bt_bluedroid
,09-14 10:25:27.703  5733  5890 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-14 10:25:27.704  5733  5890 I bt_hci  : start_up
,09-14 10:25:27.713  5733  5890 I bt_vendor: alloc value 0xf3ab8871
,09-14 10:25:27.713  5733  5890 I bt_vendor: init
09-14 10:25:27.713  5733  5890 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 10:25:27.714  5733  5890 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 10:25:27.828  5733  5890 D bt_hci  : start_up starting async portion
,09-14 10:25:27.828  5733  5897 I bt_hci  : event_finish_startup
09-14 10:25:27.828  5733  5897 I bt_hci_h4: hal_open
09-14 10:25:27.826  5898  5898 W irq/448-msm_hs_: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 10:25:27.829  5733  5897 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-14 10:25:27.830  5733  5897 I bt_userial_vendor: device fd = 54 open
,09-14 10:25:27.843  5733  5897 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 10:25:27.845  5733  5897 D bt_hwcfg: Chipset BCM4358A3
,09-14 10:25:27.845  5733  5897 D bt_hwcfg: Target name = [BCM4358A3]
,09-14 10:25:27.846  5733  5897 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-14 10:25:28.242  5733  5897 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-14 10:25:28.242  5733  5897 D bt_hwcfg: Settlement delay -- 100 ms
09-14 10:25:28.242  5733  5897 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 10:25:28.376  5733  5897 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 10:25:28.376  5733  5897 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-14 10:25:28.378  5733  5897 I bt_hwcfg: vendor lib fwcfg completed
,09-14 10:25:28.378  5733  5897 I bt_vendor: firmware callback
,09-14 10:25:28.378  5733  5897 I bt_hci  : firmware_config_callback
,09-14 10:25:28.387  5733  5900 I bt_btu  : btu_task pending for preload complete event
,09-14 10:25:28.387  5733  5900 I bt_btu_task: Bluetooth chip preload is complete
,09-14 10:25:28.387  5733  5900 I bt_btu  : btu_task received preload complete event
09-14 10:25:28.392  5733  5900 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 10:25:28.392  5733  5900 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_A2D
,09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 10:25:28.393  5733  5900 I         : BTE_InitTraceLevels -- TRC_PAN
,09-14 10:25:28.394  5733  5900 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 10:25:28.394  5733  5900 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 10:25:28.394  5733  5900 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 10:25:28.394  5733  5900 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 10:25:28.394  5733  5900 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 10:25:28.477  5733  5900 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a36549
,09-14 10:25:28.477  5733  5900 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a36549 
,09-14 10:25:28.495  5733  5893 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 10:25:28.497  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 10:25:28.497  5733  5893 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-14 10:25:28.499  5733  5893 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 10:25:28.501  5733  5893 D BluetoothAdapterProperties: Scan Mode:20
09-14 10:25:28.502  5733  5893 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 10:25:28.502  5733  5893 D bt_hci  : do_postload posting postload work item
09-14 10:25:28.502  5733  5897 I bt_hci  : event_postload
09-14 10:25:28.502  5733  5897 I bt_vendor: sco_config_cb
09-14 10:25:28.503  5733  5897 I bt_hci  : sco_config_callback postload finished.
09-14 10:25:28.506  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:28.510  5733  5893 D bt_bte_conf: Device ID record 1 : primary
,09-14 10:25:28.510  5733  5893 D bt_bte_conf:   vendorId            = 000f
09-14 10:25:28.510  5733  5893 D bt_bte_conf:   vendorIdSource      = 0001
09-14 10:25:28.510  5733  5893 D bt_bte_conf:   product             = 1200
09-14 10:25:28.510  5733  5893 D bt_bte_conf:   version             = 1436
09-14 10:25:28.510  5733  5893 D bt_bte_conf:   clientExecutableURL = 
09-14 10:25:28.510  5733  5893 D bt_bte_conf:   serviceDescription  = 
09-14 10:25:28.510  5733  5893 D bt_bte_conf:   documentationURL    = 
09-14 10:25:28.510  5733  5893 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 10:25:28.510  5733  5890 D bt_stack_manager: event_start_up_stack finished
,09-14 10:25:28.511  5733  5897 I bt_vendor: low_power_mode_cb
09-14 10:25:28.511  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:28.515  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:28.516  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 10:25:28.516  5733  5889 D BluetoothAdapterProperties: Setting state to 15
09-14 10:25:28.516  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-14 10:25:28.517  5733  5889 I BluetoothAdapterState: Entering BleOnState
,09-14 10:25:28.519  5733  5889 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-14 10:25:28.520  5733  5889 D BluetoothAdapterProperties: Setting state to 11
09-14 10:25:28.520  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 10:25:28.523  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
,09-14 10:25:28.524  5733  5733 D HeadsetService: Received start request. Starting profile...
09-14 10:25:28.527  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:28.527  5733  5733 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-14 10:25:28.527  5733  5733 D HeadsetStateMachine: make
09-14 10:25:28.529  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:28.533  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:28.537  5733  5889 I BluetoothAdapterState: Entering PendingCommandState
,09-14 10:25:28.538  5733  5733 D HeadsetStateMachine: max_hf_connections = 1
,09-14 10:25:28.538  5733  5733 I bt_bluedroid: get_profile_interface handsfree
09-14 10:25:28.539  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 10:25:28.539  5733  5893 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-14 10:25:28.542  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
09-14 10:25:28.543  5733  5733 D A2dpService: Received start request. Starting profile...
,09-14 10:25:28.544  5733  5733 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-14 10:25:28.544  5733  5733 I bt_bluedroid: get_profile_interface avrcp
,09-14 10:25:28.549  5733  5733 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 10:25:28.549  5733  5733 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 10:25:28.549  5733  5733 D A2dpStateMachine: make
09-14 10:25:28.550  5733  5733 I bt_bluedroid: get_profile_interface a2dp
09-14 10:25:28.551  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-14 10:25:28.552  5733  5908 D A2dpStateMachine: Enter Disconnected: -2
,09-14 10:25:28.553  5733  5733 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 10:25:28.554  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
09-14 10:25:28.555  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 10:25:28.555  5733  5733 D HidService: Received start request. Starting profile...
09-14 10:25:28.555  5733  5733 I bt_bluedroid: get_profile_interface hidhost
09-14 10:25:28.556  5733  5733 D HidService: setHidService(): set to: null
09-14 10:25:28.556  5733  5893 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a1756d
09-14 10:25:28.556  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 10:25:28.556  5733  5733 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 10:25:28.557  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
,09-14 10:25:28.557  5720  5720 D BluetoothInputDevice: Proxy object connected
,09-14 10:25:28.557  5733  5733 D HealthService: Received start request. Starting profile...
09-14 10:25:28.558  5720  5720 D HidProfile: Bluetooth service connected
09-14 10:25:28.558  5733  5733 I bt_bluedroid: get_profile_interface health
09-14 10:25:28.559  5733  5733 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-14 10:25:28.560  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
,09-14 10:25:28.561  5720  5720 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 10:25:28.562  5720  5720 D PanProfile: Bluetooth service connected
09-14 10:25:28.562  5733  5733 D PanService: Received start request. Starting profile...
09-14 10:25:28.565  5733  5733 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 10:25:28.565  5733  5733 I bt_bluedroid: get_profile_interface pan
09-14 10:25:28.565  5733  5893 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 10:25:28.567  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
09-14 10:25:28.568  5720  5720 D BluetoothMap: Proxy object connected
09-14 10:25:28.569  5720  5720 D MapProfile: Bluetooth service connected
09-14 10:25:28.569  5720  5720 D BluetoothMap: getConnectedDevices()
09-14 10:25:28.569  5720  5720 D BluetoothMap: Bluetooth is Not enabled
09-14 10:25:28.570  5733  5733 D BluetoothMapService: Received start request. Starting profile...
,09-14 10:25:28.570  5733  5733 D BluetoothMapService: start()
,09-14 10:25:28.572  5733  5733 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-14 10:25:28.573  5733  5733 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 10:25:28.573  5733  5733 D BluetoothMapAppObserver: createReceiver()
09-14 10:25:28.574  5733  5733 D BluetoothMapAppObserver: initObservers()
09-14 10:25:28.574  5733  5733 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 10:25:28.579  5733  5733 V SapService: SapBinder()
,09-14 10:25:28.579  5733  5733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cb9bbc
09-14 10:25:28.579  5733  5733 D SapService: Received start request. Starting profile...
,09-14 10:25:28.579  5733  5733 V SapService: start()
,09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isTurningOff()=false
,09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:28.581  5733  5906 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isTurningOff()=false
,09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.581  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.582  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:28.583  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:28.583  5733  5733 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:28.583  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:28.583  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:28.583  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 10:25:28.583  5733  5889 D BluetoothAdapterProperties: ScanMode =  20
09-14 10:25:28.583  5733  5889 D BluetoothAdapterProperties: State =  11
09-14 10:25:28.584  5733  5889 D BluetoothAdapterProperties: Setting state to 12
09-14 10:25:28.584  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 10:25:28.584  5733  5889 I BluetoothAdapterState: Entering OnState
09-14 10:25:28.584  5720  5730 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 10:25:28.587  5733  5893 D BluetoothAdapterProperties: Scan Mode:21
09-14 10:25:28.587  5733  5893 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 10:25:28.588  5720  5731 D BluetoothPan: onBluetoothStateChange on: true
,09-14 10:25:28.589  3115  3128 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:28.590  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:28.591  3115  3378 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 10:25:28.592  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:28.592  3115  3127 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:28.593  3115  3115 D BluetoothA2dp: Proxy object connected
09-14 10:25:28.593  5720  5730 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 10:25:28.593   923   940 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 10:25:28.593  3115  3378 D BluetoothMap: onBluetoothStateChange: up=true
,09-14 10:25:28.595  3115  3115 D BluetoothMap: Proxy object connected
09-14 10:25:28.595  3525  3572 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 10:25:28.595  3115  3115 D MapProfile: Bluetooth service connected
,09-14 10:25:28.595  3115  3115 D BluetoothMap: getConnectedDevices()
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:28.595  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:28.595  5720  5731 D BluetoothMap: onBluetoothStateChange: up=true
09-14 10:25:28.596   923   940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:28.596   923   940 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 10:25:28.596   923   940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:28.596   923   923 D BluetoothA2dp: Proxy object connected
09-14 10:25:28.596  3115  3709 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 10:25:28.597  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:28.598  3115  3115 D BluetoothInputDevice: Proxy object connected
09-14 10:25:28.598  3115  3115 D HidProfile: Bluetooth service connected
09-14 10:25:28.598  3115  3378 D BluetoothPan: onBluetoothStateChange on: true
09-14 10:25:28.598  5733  5733 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 10:25:28.599  5733  5733 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 10:25:28.600  3115  3115 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 10:25:28.600  3115  3115 D PanProfile: Bluetooth service connected
09-14 10:25:28.601   923   923 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:28.602  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:28.602  5733  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:28.603  5720  5720 D LocalBluetoothProfileManager: Adding local A2DP profile
09-14 10:25:28.604  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:28.604  5733  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:28.605  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:28.606  5733  5733 D ObexServerSockets: Succeed to create listening sockets 
09-14 10:25:28.606  5733  5733 D ObexServerSockets0: startAccept()
09-14 10:25:28.606  5733  5733 D ObexServerSockets0: prepareForNewConnect()
09-14 10:25:28.607  5720  5720 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-14 10:25:28.607  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:28.608  5733  5733 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 10:25:28.608  5733  5733 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 10:25:28.608  5733  5917 D ObexServerSockets0: Accepting socket connection...
09-14 10:25:28.608  5733  5733 D BluetoothMapService: onReceive
09-14 10:25:28.608  5733  5733 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-14 10:25:28.608  5733  5733 D BluetoothMapService: STATE_ON
09-14 10:25:28.608  5733  5918 D ObexServerSockets0: Accepting socket connection...
09-14 10:25:28.609  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:28.610  5733  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:28.612  5733  5919 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-14 10:25:28.612  5733  5919 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-14 10:25:28.615  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 10:25:28.618  5720  5720 D BluetoothA2dp: Proxy object connected
,09-14 10:25:28.621  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 10:25:28.625  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,09-14 10:25:28.626  5720  5720 D BluetoothPbap: Proxy object connected
09-14 10:25:28.626  5720  5720 D PbapServerProfile: Bluetooth service connected
09-14 10:25:28.626  5733  5921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:28.628  3115  3115 D BluetoothPbap: Proxy object connected
,09-14 10:25:28.628  3115  3115 D PbapServerProfile: Bluetooth service connected
,09-14 10:25:28.643  5733  5733 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 10:25:28.643  5733  5733 D ObexServerSockets0: prepareForNewConnect()
,09-14 10:25:28.647  5733  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:25:28.648  5733  5927 I BtOppRfcommListener: Accept thread started.
,09-14 10:25:28.694   923   923 D BluetoothHeadset: Proxy object connected
,09-14 10:25:28.694   923   923 D BluetoothHeadset: Proxy object connected
09-14 10:25:28.694  3115  3709 D BluetoothHeadset: Proxy object connected
09-14 10:25:28.694  3115  3115 D HeadsetProfile: Bluetooth service connected
09-14 10:25:28.694   923   923 D BluetoothHeadset: Proxy object connected
,09-14 10:25:28.695  3525  3564 D BluetoothHeadset: Proxy object connected
,09-14 10:25:28.695  3525  3751 D BluetoothHeadset: Proxy object connected
09-14 10:25:28.696   923   940 D BluetoothHeadset: Proxy object connected
09-14 10:25:28.696   923   940 D BluetoothHeadset: Proxy object connected
,09-14 10:25:28.711  5720  5730 D BluetoothHeadset: Proxy object connected
,09-14 10:25:28.712  5720  5720 D HeadsetProfile: Bluetooth service connected
,09-14 10:25:30.497   923  2966 D ConnectivityService: handlePromptUnvalidated 101
,09-14 10:25:31.235  3392  3597 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-14 10:25:31.235  3392  3597 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-14 10:25:31.264  3600  3600 I ConfigService: onCreate
,09-14 10:25:32.612  5733  5889 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 10:25:32.613  5733  5889 D BluetoothAdapterProperties: Setting state to 13
,09-14 10:25:32.613  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-14 10:25:32.614  5733  5889 D BluetoothAdapterProperties: onBluetoothDisable()
09-14 10:25:32.615  5733  5889 I BluetoothAdapterState: Entering PendingCommandState
,09-14 10:25:32.623  5733  5733 D BluetoothMapService: onReceive
09-14 10:25:32.623  5733  5733 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 10:25:32.624  5733  5733 D BluetoothMapService: STATE_TURNING_OFF
09-14 10:25:32.624  5733  5733 D BluetoothMapService: MAP Service closeService in
09-14 10:25:32.624  5733  5733 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 10:25:32.624  5733  5733 D ObexServerSockets0: shutdown(block = true)
09-14 10:25:32.626  5733  5917 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 10:25:32.627  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:32.627  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:32.627  5733  5733 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 10:25:32.628  5733  5918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 10:25:32.629  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 10:25:32.630  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:32.630  5733  5733 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 10:25:32.630  5733  5902 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 10:25:32.630  5733  5893 D BluetoothAdapterProperties: Scan Mode:20
,09-14 10:25:32.631  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-14 10:25:32.631  5733  5733 I BtOppRfcommListener: stopping Accept Thread
09-14 10:25:32.631  5733  5927 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 10:25:32.632  5733  5927 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 10:25:32.637  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:32.637  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:32.638  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 10:25:32.638  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:32.639  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:32.646  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:32.646  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:32.647  5720  5720 D DockEventReceiver: finishStartingService: stopping service
09-14 10:25:32.647  5733  5733 D HeadsetService: Received stop request...Stopping profile...
09-14 10:25:32.647  5615  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 10:25:32.647  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:32.650  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.651   923   923 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:32.651   923   923 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:32.651  3115  3709 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:32.652  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.652  5733  5733 D A2dpService: Received stop request...Stopping profile...
09-14 10:25:32.652  5720  5731 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:32.652  5733  5908 D A2dpStateMachine: Exit Disconnected: -1
09-14 10:25:32.653   923   923 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:32.653  5720  5720 D HeadsetProfile: Bluetooth service disconnected
,09-14 10:25:32.654  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.654  5733  5733 D HidService: Received stop request...Stopping profile...
09-14 10:25:32.654  5733  5733 D HidService: Stopping Bluetooth HidService
09-14 10:25:32.654  5720  5720 D BluetoothA2dp: Proxy object disconnected
09-14 10:25:32.655  3115  3115 D HeadsetProfile: Bluetooth service disconnected
09-14 10:25:32.655  3115  3115 D BluetoothA2dp: Proxy object disconnected
09-14 10:25:32.656  3115  3115 D BluetoothInputDevice: Proxy object disconnected
09-14 10:25:32.656  3525  3928 D BluetoothHeadset: Proxy object disconnected
09-14 10:25:32.656  3115  3115 D HidProfile: Bluetooth service disconnected
09-14 10:25:32.656   923   923 D BluetoothA2dp: Proxy object disconnected
09-14 10:25:32.656  5720  5720 D BluetoothInputDevice: Proxy object disconnected
09-14 10:25:32.656  5720  5720 D HidProfile: Bluetooth service disconnected
,09-14 10:25:32.659  5733  5733 D HealthService: Received stop request...Stopping profile...
09-14 10:25:32.662  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 10:25:32.662  5733  5733 D PanService: Received stop request...Stopping profile...
,09-14 10:25:32.665  3115  3115 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 10:25:32.665  3115  3115 D PanProfile: Bluetooth service disconnected
,09-14 10:25:32.666  5733  5733 D BluetoothMapService: Received stop request...Stopping profile...
,09-14 10:25:32.666  5733  5733 D BluetoothMapService: stop()
09-14 10:25:32.667  5733  5733 D BluetoothMapAppObserver: deinitObservers()
09-14 10:25:32.667  5733  5733 D BluetoothMapAppObserver: removeReceiver()
09-14 10:25:32.668  3115  3115 D BluetoothMap: Proxy object disconnected
09-14 10:25:32.668  3115  3115 D MapProfile: Bluetooth service disconnected
,09-14 10:25:32.671  5733  5733 D SapService: Received stop request...Stopping profile...
,09-14 10:25:32.671  5733  5733 V SapService: stop()
09-14 10:25:32.672  5733  5733 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:32.672  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:32.672  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.672  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 10:25:32.674  5720  5720 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 10:25:32.674  5720  5720 D PanProfile: Bluetooth service disconnected
09-14 10:25:32.674  5733  5733 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 10:25:32.674  5720  5720 D BluetoothMap: Proxy object disconnected
09-14 10:25:32.674  5720  5720 D MapProfile: Bluetooth service disconnected
09-14 10:25:32.674  5733  5733 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 10:25:32.674  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 10:25:32.674  5733  5733 V BluetoothAdapterState: isTurningOff()=true
,09-14 10:25:32.674  5733  5900 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:32.674  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:32.674  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.675  5733  5900 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:32.675  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:32.675  5733  5900 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:32.675  5733  5893 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 10:25:32.676  5733  5733 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:32.676  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:32.677  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.677  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:32.677  5733  5733 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 10:25:32.677  5733  5733 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 10:25:32.677  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 10:25:32.677  5733  5900 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:32.678  5733  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 10:25:32.678  5733  5900 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:32.678  5733  5900 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 10:25:32.678  5733  5900 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-14 10:25:32.678  5733  5900 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 10:25:32.678  5733  5900 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-14 10:25:32.680  3115  3115 D BluetoothPbap: Proxy object disconnected
09-14 10:25:32.681  5733  5733 V BluetoothAdapterState: isTurningOff()=true
,09-14 10:25:32.681  3115  3115 D PbapServerProfile: Bluetooth service disconnected
09-14 10:25:32.681  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:32.681  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.681  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:32.681  5733  5733 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 10:25:32.681  5720  5720 D BluetoothPbap: Proxy object disconnected
09-14 10:25:32.681  5720  5720 D PbapServerProfile: Bluetooth service disconnected
09-14 10:25:32.681  5733  5893 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-14 10:25:32.681  5733  5733 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 10:25:32.681  5733  5733 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:32.682  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:32.682  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.682  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:32.682  5733  5733 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 10:25:32.682  5733  5733 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 10:25:32.683  5733  5733 D BluetoothMapService: MAP Service closeService in
09-14 10:25:32.683  5733  5733 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:32.683  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:32.683  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.683  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:32.683  5733  5733 D BluetoothMapService: cleanup()
09-14 10:25:32.683  5733  5733 D BluetoothMapService: MAP Service closeService in
09-14 10:25:32.684  5733  5733 V BluetoothAdapterState: isTurningOff()=true
09-14 10:25:32.684  5733  5733 V BluetoothAdapterState: isTurningOn()=false
,09-14 10:25:32.684  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:32.684  5733  5733 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:32.684  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 10:25:32.684  5733  5889 D BluetoothAdapterProperties: Setting state to 15
09-14 10:25:32.684  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 10:25:32.684  5733  5889 I BluetoothAdapterState: Entering BleOnState
09-14 10:25:32.686  5720  5730 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 10:25:32.687  5720  5731 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:32.687  5720  5730 D BluetoothPan: onBluetoothStateChange on: false
09-14 10:25:32.688  3115  3128 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 10:25:32.688  3115  3127 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 10:25:32.689  3115  3709 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:32.689  5720  5731 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 10:25:32.689   923   940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:32.690  3115  3378 D BluetoothMap: onBluetoothStateChange: up=false
,09-14 10:25:32.690  3525  3572 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:32.691  5720  5730 D BluetoothMap: onBluetoothStateChange: up=false
09-14 10:25:32.692   923   940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:32.692   923   940 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-14 10:25:32.692   923   940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 10:25:32.692  3115  3128 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 10:25:32.693  5720  5731 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 10:25:32.694  3115  3127 D BluetoothPan: onBluetoothStateChange on: false
09-14 10:25:32.695  5733  5889 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 10:25:32.695  5733  5889 D BluetoothAdapterProperties: Setting state to 16
09-14 10:25:32.695  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-14 10:25:32.696  5733  5889 D BluetoothAdapterProperties: onBleDisable
,09-14 10:25:32.697  5733  5889 I BluetoothAdapterState: Entering PendingCommandState
09-14 10:25:32.697  5733  5890 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 10:25:32.698  5733  5893 D BluetoothAdapterProperties: Scan Mode:20
09-14 10:25:32.698  5733  5900 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 10:25:32.699  5733  5900 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 10:25:32.699  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.699  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 10:25:32.701  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.703  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:32.705  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 10:25:32.706  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:32.708  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.711  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:32.712  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,09-14 10:25:32.914  5733  5893 I bt_hci  : shut_down
,09-14 10:25:32.919  5733  5897 D bt_hwcfg: hw_epilog_process
,09-14 10:25:32.921  5733  5897 I bt_vendor: low_power_mode_cb
,09-14 10:25:32.923  5733  5897 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 10:25:32.924  5733  5897 I bt_vendor: epilog_cb
09-14 10:25:32.924  5733  5897 I bt_hci  : epilog_finished_callback
,09-14 10:25:32.927  5733  5893 I bt_hci_h4: hal_close
,09-14 10:25:32.927  5733  5893 I bt_userial_vendor: device fd = 54 close
,09-14 10:25:33.038  5733  5890 D bt_stack_manager: event_shut_down_stack finished.
,09-14 10:25:33.038  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 10:25:33.043  5733  5889 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 10:25:33.045  5733  5733 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 10:25:33.046  5733  5733 D BtGatt.GattService: Received stop request...Stopping profile...
09-14 10:25:33.046  5733  5733 D BtGatt.GattService: stop()
09-14 10:25:33.046  5733  5733 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 10:25:33.050  5733  5733 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:33.050  5733  5733 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:33.050  5733  5733 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 10:25:33.050  5733  5733 V BluetoothAdapterState: isBleTurningOff()=true
09-14 10:25:33.051  5733  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 10:25:33.051  5733  5889 D BluetoothAdapterProperties: Setting state to 10
09-14 10:25:33.051  5733  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 10:25:33.053  5733  5889 I BluetoothAdapterState: Entering OffState
,09-14 10:25:33.055   923   940 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-14 10:25:33.071  5733  5733 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 10:25:33.072  5733  5733 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 10:25:33.072  5733  5733 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-14 10:25:33.076  5733  5890 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 10:25:33.085  5733  5733 I art     : System.exit called, status: 0
,09-14 10:25:33.085  5733  5733 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 10:25:33.123   923  3135 I ActivityManager: Process com.android.bluetooth (pid 5733) has died
,09-14 10:25:36.296  3600  3600 I ConfigService: onDestroy
,09-14 10:25:37.609  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 10:25:37.610  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:37.614  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:37.615  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c80f5c7 removed from the list
,09-14 10:25:37.615  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 10:25:37.615  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:37.615  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:37.617  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:25:37.618  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e889b1d added. We now have 4 listener(s)
09-14 10:25:37.618  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:25:37.621  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:37.621  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e889b1d removed from the list
09-14 10:25:37.621  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:37.621  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:37.622  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:37.624  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:25:37.624  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4db1192 added. We now have 4 listener(s)
09-14 10:25:37.624  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:25:42.633  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:42.666   923   940 I ActivityManager: Start proc 5936:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 10:25:42.771  5936  5936 D AdapterServiceConfig: Adding HeadsetService
,09-14 10:25:42.771  5936  5936 D AdapterServiceConfig: Adding A2dpService
09-14 10:25:42.772  5936  5936 D AdapterServiceConfig: Adding HidService
09-14 10:25:42.772  5936  5936 D AdapterServiceConfig: Adding HealthService
09-14 10:25:42.772  5936  5936 D AdapterServiceConfig: Adding PanService
09-14 10:25:42.772  5936  5936 D AdapterServiceConfig: Adding GattService
09-14 10:25:42.772  5936  5936 D AdapterServiceConfig: Adding BluetoothMapService
09-14 10:25:42.772  5936  5936 D AdapterServiceConfig: Adding SapService
,09-14 10:25:42.784   923   940 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a282be:true
,09-14 10:25:42.785  5936  5936 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 10:25:42.788  5936  5936 I bt_bluedroid: init
,09-14 10:25:42.788  5936  5948 I BluetoothAdapterState: Entering OffState
,09-14 10:25:42.791  5936  5949 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-14 10:25:42.791  5936  5949 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 10:25:42.791  5936  5949 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 10:25:42.791  5936  5949 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-14 10:25:42.792  5936  5936 I bt_bluedroid: get_profile_interface socket
,09-14 10:25:42.793  5936  5952 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 10:25:42.794  5936  5936 I bt_bluedroid: get_profile_interface sdp
09-14 10:25:42.795  5936  5952 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 10:25:42.798  5936  5947 I bt_bluedroid: config_hci_snoop_log
,09-14 10:25:42.800   923   940 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 10:25:42.804  5936  5948 D BluetoothAdapterState: Current state: OFF, message: 0
09-14 10:25:42.804  5936  5948 D BluetoothAdapterProperties: Setting state to 14
09-14 10:25:42.804  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 10:25:42.805  5936  5948 D BluetoothBondStateMachine: make
,09-14 10:25:42.808  5936  5953 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 10:25:42.811  5936  5948 I BluetoothAdapterState: Entering PendingCommandState
,09-14 10:25:42.812  5936  5936 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 10:25:42.814  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
,09-14 10:25:42.815  5936  5936 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 10:25:42.815  5936  5936 D BtGatt.GattService: Received start request. Starting profile...
,09-14 10:25:42.815  5936  5936 D BtGatt.GattService: start()
09-14 10:25:42.815  5936  5936 I bt_bluedroid: get_profile_interface gatt
09-14 10:25:42.816  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
,09-14 10:25:42.816  5936  5936 D BtGatt.AdvertiseManager: advertise manager created
,09-14 10:25:42.834  5936  5936 V BluetoothAdapterState: isTurningOff()=false
,09-14 10:25:42.834  5936  5936 V BluetoothAdapterState: isTurningOn()=false
09-14 10:25:42.834  5936  5936 V BluetoothAdapterState: isBleTurningOn()=true
09-14 10:25:42.834  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:42.835  5936  5948 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 10:25:42.836  5936  5948 I bt_bluedroid: bt_bluedroid
,09-14 10:25:42.837  5936  5949 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-14 10:25:42.837  5936  5949 I bt_hci  : start_up
,09-14 10:25:42.842  5936  5949 I bt_vendor: alloc value 0xf3b19871
09-14 10:25:42.842  5936  5949 I bt_vendor: init
09-14 10:25:42.842  5936  5949 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-14 10:25:42.842  5936  5949 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 10:25:42.951  5936  5949 D bt_hci  : start_up starting async portion
,09-14 10:25:42.952  5936  5956 I bt_hci  : event_finish_startup
,09-14 10:25:42.952  5936  5956 I bt_hci_h4: hal_open
09-14 10:25:42.952  5936  5956 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-14 10:25:42.954  5936  5956 I bt_userial_vendor: device fd = 54 open
,09-14 10:25:42.949  5957  5957 W irq/448-msm_hs_: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 10:25:42.971  5936  5956 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 10:25:42.975  5936  5956 D bt_hwcfg: Chipset BCM4358A3
,09-14 10:25:42.975  5936  5956 D bt_hwcfg: Target name = [BCM4358A3]
09-14 10:25:42.976  5936  5956 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-14 10:25:43.480  5936  5956 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 10:25:43.481  5936  5956 D bt_hwcfg: Settlement delay -- 100 ms
09-14 10:25:43.481  5936  5956 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 10:25:43.614  5936  5956 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 10:25:43.614  5936  5956 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-14 10:25:43.616  5936  5956 I bt_hwcfg: vendor lib fwcfg completed
,09-14 10:25:43.616  5936  5956 I bt_vendor: firmware callback
09-14 10:25:43.616  5936  5956 I bt_hci  : firmware_config_callback
,09-14 10:25:43.625  5936  5959 I bt_btu  : btu_task pending for preload complete event
,09-14 10:25:43.626  5936  5959 I bt_btu_task: Bluetooth chip preload is complete
09-14 10:25:43.626  5936  5959 I bt_btu  : btu_task received preload complete event
,09-14 10:25:43.631  5936  5959 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 10:25:43.631  5936  5959 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 10:25:43.631  5936  5959 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 10:25:43.631  5936  5959 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_A2D
,09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 10:25:43.632  5936  5959 I         : BTE_InitTraceLevels -- TRC_SMP
,09-14 10:25:43.633  5936  5959 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 10:25:43.633  5936  5959 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 10:25:43.739  5936  5959 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a97549
09-14 10:25:43.739  5936  5959 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a97549 
,09-14 10:25:43.755  5936  5952 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 10:25:43.757  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 10:25:43.758  5936  5952 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 10:25:43.761  5936  5952 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 10:25:43.764  5936  5952 D BluetoothAdapterProperties: Scan Mode:20
,09-14 10:25:43.764  5936  5952 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 10:25:43.764  5936  5952 D bt_hci  : do_postload posting postload work item
09-14 10:25:43.765  5936  5956 I bt_hci  : event_postload
09-14 10:25:43.765  5936  5956 I bt_vendor: sco_config_cb
09-14 10:25:43.765  5936  5956 I bt_hci  : sco_config_callback postload finished.
09-14 10:25:43.769  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:43.770  5936  5952 D bt_bte_conf: Device ID record 1 : primary
09-14 10:25:43.770  5936  5952 D bt_bte_conf:   vendorId            = 000f
09-14 10:25:43.770  5936  5952 D bt_bte_conf:   vendorIdSource      = 0001
09-14 10:25:43.770  5936  5952 D bt_bte_conf:   product             = 1200
09-14 10:25:43.770  5936  5952 D bt_bte_conf:   version             = 1436
09-14 10:25:43.770  5936  5952 D bt_bte_conf:   clientExecutableURL = 
,09-14 10:25:43.770  5936  5952 D bt_bte_conf:   serviceDescription  = 
,09-14 10:25:43.770  5936  5952 D bt_bte_conf:   documentationURL    = 
09-14 10:25:43.770  5936  5952 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-14 10:25:43.771  5936  5949 D bt_stack_manager: event_start_up_stack finished
09-14 10:25:43.771  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:43.772  5936  5948 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-14 10:25:43.772  5936  5948 D BluetoothAdapterProperties: Setting state to 15
09-14 10:25:43.773  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-14 10:25:43.773  5936  5956 I bt_vendor: low_power_mode_cb
09-14 10:25:43.774  5936  5948 I BluetoothAdapterState: Entering BleOnState
09-14 10:25:43.777  5936  5948 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 10:25:43.778  5936  5948 D BluetoothAdapterProperties: Setting state to 11
09-14 10:25:43.778  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 10:25:43.785  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:43.789  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
,09-14 10:25:43.790  5936  5936 D HeadsetService: Received start request. Starting profile...
09-14 10:25:43.790  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:43.793  5936  5936 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-14 10:25:43.793  5936  5936 D HeadsetStateMachine: make
,09-14 10:25:43.805  5936  5948 I BluetoothAdapterState: Entering PendingCommandState
,09-14 10:25:43.805  5936  5936 D HeadsetStateMachine: max_hf_connections = 1
09-14 10:25:43.805  5936  5936 I bt_bluedroid: get_profile_interface handsfree
,09-14 10:25:43.806  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 10:25:43.806  5936  5952 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-14 10:25:43.811  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
09-14 10:25:43.811  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 10:25:43.811  5936  5936 D A2dpService: Received start request. Starting profile...
09-14 10:25:43.813  5936  5936 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-14 10:25:43.813  5936  5936 I bt_bluedroid: get_profile_interface avrcp
,09-14 10:25:43.820  5936  5936 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-14 10:25:43.820  5936  5936 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 10:25:43.820  5936  5936 D A2dpStateMachine: make
,09-14 10:25:43.821  5936  5936 I bt_bluedroid: get_profile_interface a2dp
09-14 10:25:43.822  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 10:25:43.824  5936  5967 D A2dpStateMachine: Enter Disconnected: -2
,09-14 10:25:43.824  5936  5936 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 10:25:43.825  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
,09-14 10:25:43.826  5936  5936 D HidService: Received start request. Starting profile...
,09-14 10:25:43.826  5936  5936 I bt_bluedroid: get_profile_interface hidhost
09-14 10:25:43.827  5936  5936 D HidService: setHidService(): set to: null
09-14 10:25:43.827  5936  5952 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a7856d
09-14 10:25:43.827  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 10:25:43.827  5936  5936 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 10:25:43.828  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
09-14 10:25:43.828  5936  5936 D HealthService: Received start request. Starting profile...
,09-14 10:25:43.830  5936  5936 I bt_bluedroid: get_profile_interface health
09-14 10:25:43.832  5936  5936 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-14 10:25:43.833  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
,09-14 10:25:43.833  5936  5936 D PanService: Received start request. Starting profile...
09-14 10:25:43.834  5936  5936 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 10:25:43.834  5936  5936 I bt_bluedroid: get_profile_interface pan
09-14 10:25:43.834  5936  5952 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 10:25:43.835  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
09-14 10:25:43.836  5936  5936 D BluetoothMapService: Received start request. Starting profile...
09-14 10:25:43.836  5936  5936 D BluetoothMapService: start()
09-14 10:25:43.838  5936  5936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-14 10:25:43.839  5936  5936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 10:25:43.839  5936  5936 D BluetoothMapAppObserver: createReceiver()
,09-14 10:25:43.840  5936  5936 D BluetoothMapAppObserver: initObservers()
09-14 10:25:43.840  5936  5936 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 10:25:43.847  5936  5936 V SapService: SapBinder()
09-14 10:25:43.847  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
09-14 10:25:43.847  5936  5936 D SapService: Received start request. Starting profile...
,09-14 10:25:43.847  5936  5936 V SapService: start()
,09-14 10:25:43.849  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.849  5936  5936 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:43.849  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.849  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 10:25:43.850  5936  5965 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
09-14 10:25:43.850  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.850  5936  5936 V BluetoothAdapterState: isTurningOn()=true
,09-14 10:25:43.850  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.850  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.851  5936  5936 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:43.852  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.852  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:43.852  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.852  5936  5936 V BluetoothAdapterState: isTurningOn()=true
09-14 10:25:43.852  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.852  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 10:25:43.853  5936  5936 V BluetoothAdapterState: isTurningOff()=false
09-14 10:25:43.853  5936  5936 V BluetoothAdapterState: isTurningOn()=true
,09-14 10:25:43.853  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
09-14 10:25:43.853  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
09-14 10:25:43.853  5936  5948 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 10:25:43.853  5936  5948 D BluetoothAdapterProperties: ScanMode =  20
09-14 10:25:43.853  5936  5948 D BluetoothAdapterProperties: State =  11
09-14 10:25:43.854  5936  5948 D BluetoothAdapterProperties: Setting state to 12
09-14 10:25:43.854  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 10:25:43.854  5936  5948 I BluetoothAdapterState: Entering OnState
09-14 10:25:43.854  5720  5730 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 10:25:43.856  5936  5952 D BluetoothAdapterProperties: Scan Mode:21
09-14 10:25:43.856  5936  5952 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 10:25:43.857  5720  5731 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:43.857  5720  5730 D BluetoothPan: onBluetoothStateChange on: true
09-14 10:25:43.859  3115  3378 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:43.859  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:43.861  5720  5720 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 10:25:43.861  5720  5720 D PanProfile: Bluetooth service connected
,09-14 10:25:43.861  3115  3128 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 10:25:43.861  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:43.863  3115  3127 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:43.863  3115  3115 D BluetoothA2dp: Proxy object connected
,09-14 10:25:43.864  5720  5730 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-14 10:25:43.866   923   940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:43.866  3115  3378 D BluetoothMap: onBluetoothStateChange: up=true
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:43.866  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:43.866  5936  5936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 10:25:43.867  5936  5936 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 10:25:43.868  5936  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:43.868  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:43.869  3525  3572 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:43.870  5936  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:43.870  5720  5731 D BluetoothMap: onBluetoothStateChange: up=true
09-14 10:25:43.871  5936  5936 D ObexServerSockets: Succeed to create listening sockets 
09-14 10:25:43.871  5936  5936 D ObexServerSockets0: startAccept()
09-14 10:25:43.871  5936  5936 D ObexServerSockets0: prepareForNewConnect()
09-14 10:25:43.871   923   940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:43.871   923   940 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 10:25:43.872   923   940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 10:25:43.872   923   923 D BluetoothA2dp: Proxy object connected
09-14 10:25:43.872  3115  3128 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 10:25:43.872  5936  5936 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 10:25:43.872  5936  5936 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 10:25:43.873  5936  5974 D ObexServerSockets0: Accepting socket connection...
09-14 10:25:43.874  5720  5730 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 10:25:43.874  5936  5975 D ObexServerSockets0: Accepting socket connection...
09-14 10:25:43.875  3115  3115 D BluetoothInputDevice: Proxy object connected
09-14 10:25:43.875  3115  3115 D HidProfile: Bluetooth service connected
09-14 10:25:43.876  3115  3115 D BluetoothMap: Proxy object connected
09-14 10:25:43.877  3115  3115 D MapProfile: Bluetooth service connected
,09-14 10:25:43.877  3115  3115 D BluetoothMap: getConnectedDevices()
,09-14 10:25:43.877  3115  3128 D BluetoothPan: onBluetoothStateChange on: true
09-14 10:25:43.877  5720  5720 D BluetoothInputDevice: Proxy object connected
,09-14 10:25:43.877  5720  5720 D HidProfile: Bluetooth service connected
09-14 10:25:43.878  5720  5720 D BluetoothA2dp: Proxy object connected
09-14 10:25:43.878  3115  3115 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 10:25:43.878  3115  3115 D PanProfile: Bluetooth service connected
09-14 10:25:43.879   923   923 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 10:25:43.882  5720  5720 D BluetoothMap: Proxy object connected
09-14 10:25:43.882  5936  5936 D BluetoothMapService: onReceive
09-14 10:25:43.882  5720  5720 D MapProfile: Bluetooth service connected
,09-14 10:25:43.882  5936  5936 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 10:25:43.882  5720  5720 D BluetoothMap: getConnectedDevices()
09-14 10:25:43.882  5936  5936 D BluetoothMapService: STATE_ON
09-14 10:25:43.882  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:43.884  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:43.885  5936  5977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:25:43.886  5936  5977 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-14 10:25:43.886  5936  5977 D BluetoothSdpJni: SDP Create record success - handle: 1
09-14 10:25:43.888  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 10:25:43.894  3600  3600 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 10:25:43.896  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,09-14 10:25:43.901  5720  5720 D BluetoothPbap: Proxy object connected
09-14 10:25:43.901  5720  5720 D PbapServerProfile: Bluetooth service connected
,09-14 10:25:43.903  3115  3115 D BluetoothPbap: Proxy object connected
09-14 10:25:43.903  3115  3115 D PbapServerProfile: Bluetooth service connected
,09-14 10:25:43.906  5936  5936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 10:25:43.906  5936  5936 D ObexServerSockets0: prepareForNewConnect()
09-14 10:25:43.908  5936  5981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:25:43.923  5936  5985 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:25:43.924  5936  5985 I BtOppRfcommListener: Accept thread started.
,09-14 10:25:43.958   923   923 D BluetoothHeadset: Proxy object connected
,09-14 10:25:43.959   923   923 D BluetoothHeadset: Proxy object connected
09-14 10:25:43.959  3115  3709 D BluetoothHeadset: Proxy object connected
09-14 10:25:43.959  3115  3115 D HeadsetProfile: Bluetooth service connected
09-14 10:25:43.959  5720  5731 D BluetoothHeadset: Proxy object connected
09-14 10:25:43.960   923   923 D BluetoothHeadset: Proxy object connected
09-14 10:25:43.960  3525  3751 D BluetoothHeadset: Proxy object connected
,09-14 10:25:43.962  5720  5720 D HeadsetProfile: Bluetooth service connected
,09-14 10:25:43.964  3115  3128 D BluetoothHeadset: Proxy object connected
09-14 10:25:43.964  3115  3115 D HeadsetProfile: Bluetooth service connected
,09-14 10:25:43.966   923   940 D BluetoothHeadset: Proxy object connected
,09-14 10:25:43.970  3525  3564 D BluetoothHeadset: Proxy object connected
,09-14 10:25:43.972   923   940 D BluetoothHeadset: Proxy object connected
09-14 10:25:43.972   923   940 D BluetoothHeadset: Proxy object connected
,09-14 10:25:45.883  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:46.884  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:47.651  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 10:25:47.657  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:47.658  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 10:25:47.658  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4db1192 removed from the list
,09-14 10:25:47.659  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:47.659  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:25:47.659  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:47.661  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 10:25:47.661  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98d2763 added. We now have 4 listener(s)
,09-14 10:25:47.661  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:25:47.666   923   934 D WifiService: setWifiEnabled: false pid=5615, uid=10077
,09-14 10:25:47.666   923   934 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 10:25:47.885  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:48.886  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:49.888  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:25:50.889  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 10:25:52.678  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:25:52.679   923  3135 D WifiService: setWifiEnabled: true pid=5615, uid=10077
09-14 10:25:52.679   923  3135 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 10:25:52.690   506   917 D SoftapController: Softap fwReload - Ok
,09-14 10:25:52.698   506   917 D CommandListener: Setting iface cfg
09-14 10:25:52.699   506   917 D CommandListener: Trying to bring down wlan0
,09-14 10:25:52.701   506   917 D CommandListener: Clearing all IP addresses on wlan0
,09-14 10:25:52.708   923  2961 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 10:25:53.360   923  2961 D wifi    : set interface wlan0 flags (UP)
,09-14 10:25:53.363   923  2961 I WifiHAL : Initializing wifi
,09-14 10:25:53.364   923  2961 I WifiHAL : Creating socket
,09-14 10:25:53.371   923   940 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-14 10:25:53.376   923  2961 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-14 10:25:53.376   923  2961 D wifi    : Did set static halHandle = 0x7f6fa08c00
09-14 10:25:53.377   923  2961 D wifi    : halHandle = 0x7f6fa08c00, mVM = 0x7f8b7cd140, mCls = 0x20192e
09-14 10:25:53.377   923  2961 D wifi    : array field set
09-14 10:25:53.377   923  2961 I WifiNative-HAL: interface[0] = wlan0
,09-14 10:25:53.381   923  5991 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547333639168
,09-14 10:25:53.381   923  5991 D wifi    : waitForHalEvents called, vm = 0x7f8b7cd140, obj = 0x20192e, env = 0x7f6b779040
,09-14 10:25:53.435  5992  5992 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-14 10:25:53.457  5992  5992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 10:25:53.479   923  2961 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 10:25:53.480   923  2961 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-14 10:25:53.484  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:53.486  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:25:53.496  5992  5992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-14 10:25:53.496  5992  5992 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-14 10:25:54.501   923  2961 D WifiConfigStore: Loading config and enabling all networks 
,09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:54.504  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 10:25:54.508  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:54.515  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 10:25:54.519  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:54.519   923  2961 D WifiConfigStore: loaded 0 passpoint configs
09-14 10:25:54.521   923  2961 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 10:25:54.521   923  2961 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-14 10:25:54.522   923  2961 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-14 10:25:54.524   923  2961 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-14 10:25:54.524   923  2961 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-14 10:25:54.524   923  2961 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-14 10:25:54.524   923  2961 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-14 10:25:54.528  5683  5683 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 10:25:54.529   923  2961 D WifiNative-HAL: Setting external_sim to 1
,09-14 10:25:54.530   923  2961 D wifi    : setting dfs flag to true, 0x7f700788e0
09-14 10:25:54.530   923  2961 D WifiStateMachine: Setting OUI to DA-A1-19
,09-14 10:25:54.531   923  2961 D wifi    : setting scan oui 0x7f700788e0
09-14 10:25:54.531   923  2961 D WifiHAL : Sending mac address OUI
,09-14 10:25:54.536   923  2961 E native  : do suspend false
,09-14 10:25:54.549   923  2961 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-14 10:25:54.550   506   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-14 10:25:54.550   923   923 D RttService: SCAN_AVAILABLE : 3
09-14 10:25:54.550   923  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 10:25:54.552   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:54.556   923  2960 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '99 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 99 Failed to set address (No such device)'
,09-14 10:25:54.556   923  2960 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 10:25:54.567   923  2960 D WifiNative-HAL: p2pGetDeviceAddress
09-14 10:25:54.567   923  2960 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-14 10:25:54.573   923   938 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=2148720 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 10:25:57.704  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 10:25:57.710  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 10:25:57.711  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:25:57.712  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98d2763 removed from the list
,09-14 10:25:57.712  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:25:57.712  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:25:57.712  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:25:57.722  5615  6003 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-14 10:25:57.722  5615  6003 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 10:25:57.726  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:57.751  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:57.759  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:57.765  5992  5992 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 10:25:57.793   923  2961 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-14 10:25:57.794   923  2961 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-14 10:25:57.795   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 10:25:57.806   923  2961 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-14 10:25:57.840   923  2961 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-14 10:25:57.841  5992  5992 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 10:25:58.262  5992  5992 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 10:25:58.295  5992  5992 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 10:25:58.297  5992  5992 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-14 10:25:58.308   923  2961 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 10:25:58.308   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 10:25:58.309   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-14 10:25:58.324   923  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 10:25:58.333   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:58.339   923  2961 D WifiStateMachine: Start Dhcp Watchdog 3
,09-14 10:25:58.345   923  6007 D DhcpClient: Receive thread started
,09-14 10:25:58.348   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 10:25:58.348   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-14 10:25:58.348   923  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-14 10:25:58.428   923  2961 E native  : do suspend false
,09-14 10:25:58.437   923  6006 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 10:25:58.452   923  6007 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-14 10:25:58.452   923  6006 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-14 10:25:58.454   923  6006 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-14 10:25:58.465   923  6007 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-14 10:25:58.466   923  6006 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-14 10:25:58.468   506   917 D CommandListener: Setting iface cfg
,09-14 10:25:58.471   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 10:25:58.473   923  6006 D DhcpClient: Scheduling renewal in 86399s
,09-14 10:25:58.480   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 10:25:58.481   923  2961 D WifiConfigStore: No blacklist allowed without epno enabled
09-14 10:25:58.482   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-14 10:25:58.484   923  2966 D ConnectivityService: Adding iface wlan0 to network 102
,09-14 10:25:58.494   923  2961 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 10:25:58.534   923  2966 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-14 10:25:58.535   923  2966 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-14 10:25:58.537   923  2966 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-14 10:25:58.539   923  2966 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-14 10:25:58.540   923  2966 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-14 10:25:58.548   923  2966 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 10:25:58.552   923  2966 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-14 10:25:58.552   923  2966 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-14 10:25:58.553   923  2966 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-14 10:25:58.553   923  2961 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-14 10:25:58.553   923  2966 D ConnectivityService:    accepting network in place of null
09-14 10:25:58.553   923  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 10:25:58.553   923  2966 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 10:25:58.573   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2152720, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:25:58.577   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 10:25:58.601   506   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 10:25:58.606   923  2966 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-14 10:25:58.606   923  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 10:25:58.606  3488  3635 W QCNEJ   : |CORE| network available: 102
,09-14 10:25:58.608   923   940 D Tethering: MasterInitialState.processMessage what=3
,09-14 10:25:58.608   923  2966 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-14 10:25:58.612  3488  3635 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-14 10:25:58.613  3488  3635 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-14 10:25:58.614  3488  3635 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:58.620  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:25:58.622  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:25:58.625  4872  4889 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:25:58.626  5615  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:25:58.627  4872  4889 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 10:25:58.627  4872  4889 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-14 10:25:58.628  4872  4889 E SarControlService: no key has been found,reset the power
09-14 10:25:58.628  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 10:25:58.629  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 10:25:58.629  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 10:25:58.629  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:58.629  4902  4902 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 10:25:58.630  5615  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:25:58.630  4872  4914 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 10:25:58.631  4872  4914 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 10:25:58.631  4872  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 10:25:58.632  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 10:25:58.632  4902  4902 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-14 10:25:58.637  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000f003000000000000ffffffff]
,09-14 10:25:58.637  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:58.637  4902  4916 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-14 10:25:58.637  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:58.638  4872  4884 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-14 10:25:58.638  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2543351 HexData = [00000000f103000000000000ffffffff]
09-14 10:25:58.638  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 10:25:58.639  4902  4916 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-14 10:25:58.639  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 10:25:58.639  4872  4883 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-14 10:25:58.640  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-14 10:25:58.641   923  6004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:815::200e
,09-14 10:25:58.648  3900  5196 I iu.UploadsManager: num queued entries: 0
,09-14 10:25:58.648  3900  5196 I iu.UploadsManager: num updated entries: 0
09-14 10:25:58.649  3900  5196 I iu.SyncManager: NEXT; no task
,09-14 10:25:58.650  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-14 10:25:58.652  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 10:25:58.653  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 10:25:58.657  5776  5776 D SprintDMHelper: simOperator: 
,09-14 10:25:58.657  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 10:25:58.690   923  6004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 14:25:58 GMT], X-Android-Received-Millis=[1473863158689], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473863158664]}
,09-14 10:25:58.691   923  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 10:25:58.691   923  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-14 10:25:58.691   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-14 10:25:58.692   923  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 10:25:58.762  5683  6019 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-14 10:25:59.664   923  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-14 10:25:59.675   923  2966 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 10:25:59.682  3488  3635 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-14 10:25:59.683  3488  3635 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-14 10:26:00.730  5615  6003 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-14 10:26:00.730  5615  6029 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-14 10:26:00.732  5615  6029 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:26:00.732  5615  6003 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:26:00.732  5615  6029 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:26:00.732  5615  6003 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:26:00.734  5615  6029 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:26:00.734  5615  6003 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:26:00.737  5615  6031 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: IncomingSocketThread/Sender)
,09-14 10:26:00.739  5615  6003 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-14 10:26:00.740  5615  6029 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-14 10:26:00.741  5615  6032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender)
,09-14 10:26:00.743  5615  6034 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Receiver)
,09-14 10:26:00.743  5615  6033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
,09-14 10:26:00.745  5615  6033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
,09-14 10:26:00.746  5615  6034 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: IncomingSocketThread/Receiver)
09-14 10:26:00.746  5615  6034 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 10:26:00.746  5615  6034 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-14 10:26:00.747  5615  6033 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-14 10:26:00.747  5615  6033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-14 10:26:01.370   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 10:26:03.728  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-14 10:26:03.729  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-14 10:26:03.735  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@68cc745 Bundle[{}]
,09-14 10:26:03.737  5615  5672 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 10:26:03.738  5615  5672 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-14 10:26:03.740  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-14 10:26:03.741  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-14 10:26:03.741  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-14 10:26:03.743  5615  5672 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-14 10:26:03.749  5615  5672 I System.out: Running OutgoingSocketThread
,09-14 10:26:03.752  5615  6035 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-14 10:26:03.752  5615  6035 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 10:26:06.558   923  2966 D ConnectivityService: handlePromptUnvalidated 102
,09-14 10:26:06.764  5615  6035 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-14 10:26:06.764  5615  6036 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-14 10:26:06.764  5615  6036 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:26:06.764  5615  6035 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:26:06.764  5615  6035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:26:06.764  5615  6036 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:26:06.767  5615  6035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:26:06.767  5615  6036 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:26:06.769  5615  6038 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
,09-14 10:26:06.771  5615  6035 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-14 10:26:06.771  5615  6036 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-14 10:26:06.780  5615  6039 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender)
,09-14 10:26:06.781  5615  6041 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,09-14 10:26:06.782  5615  6040 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
09-14 10:26:06.783  5615  6041 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
09-14 10:26:06.783  5615  6040 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
09-14 10:26:06.784  5615  6040 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-14 10:26:06.784  5615  6040 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-14 10:26:06.784  5615  6041 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-14 10:26:06.784  5615  6041 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-14 10:26:09.569   923  2961 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,09-14 10:26:09.762  5615  5672 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-14 10:26:09.763  5615  5672 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-14 10:26:09.764  5615  5672 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-14 10:26:09.771  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 10:26:09.771  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cac1f60 added. We now have 3 listener(s)
09-14 10:26:09.775  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:09.775  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:26:09.775  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 10:26:09.776  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:09.776  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b18cc19 added. We now have 4 listener(s)
09-14 10:26:09.776  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:26:09.777  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 10:26:09.782  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:09.789  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:09.794  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:09.794  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:26:09.795  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:09.795  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:09.795  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:26:09.795  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:09.795  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:26:09.795  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:26:09.795  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 10:26:09.795  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cac1f60 removed from the list
09-14 10:26:09.795  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:09.795  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b18cc19 removed from the list
09-14 10:26:09.797  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:09.800  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:09.800  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 10:26:09.800  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:09.801  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:09.801  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:09.802  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:09.802  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:09.802  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:09.802  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b18cc19 not in the list
09-14 10:26:09.802  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:09.802  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:09.803  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:09.803  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:09.804  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:09.804  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b18cc19 not in the list
,09-14 10:26:09.804  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:09.804  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:09.804  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:09.804  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cac1f60 not in the list
09-14 10:26:09.804  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 10:26:09.804  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a0d6bf added. We now have 3 listener(s)
09-14 10:26:09.806  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:09.806  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:26:09.806  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:26:09.806  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:09.806  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da3d18c added. We now have 4 listener(s)
09-14 10:26:09.806  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:26:09.807  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 10:26:09.810  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:09.814  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:09.816  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:09.817  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:26:09.817  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:09.817  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:26:09.817  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:26:09.817  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:09.817  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 10:26:09.820  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:09.821  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:26:09.822  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:26:09.823  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:09.825  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:26:09.826  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:26:09.826  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:26:09.828  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:26:09.828  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:26:09.829  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:26:09.829  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:09.832  5936  5972 D BtGatt.GattService: registerClient() - UUID=300b81c9-1a71-4335-b23b-7cdaf8aa1bac
09-14 10:26:09.832  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=300b81c9-1a71-4335-b23b-7cdaf8aa1bac, clientIf=5
09-14 10:26:09.833  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 10:26:09.834  5936  5947 D BtGatt.GattService: start scan with filters
,09-14 10:26:09.838  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:26:09.838  5936  5955 D BtGatt.ScanManager: handling starting scan
,09-14 10:26:09.839  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:26:09.839  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:26:09.839  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 10:26:09.841  5936  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8bd078e
09-14 10:26:09.841  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:26:09.841  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:26:09.841  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 10:26:09.843  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 10:26:09.846  5615  5672 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 10:26:09.846  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:09.846  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:26:09.846  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:09.846  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 10:26:09.846  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:26:09.846  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:26:09.846  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:26:09.846  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:26:09.846  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:26:09.846  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 10:26:09.847  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:09.847  5936  5972 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:26:09.848  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:26:09.848  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:09.848  5936  5947 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:26:09.849  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 10:26:09.849  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:26:09.849  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:09.849  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 10:26:09.849  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:26:09.849  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 10:26:09.851  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:09.851  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:26:09.851  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:26:09.851  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:26:09.851  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:26:09.852  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:09.852  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:09.852  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:09.855  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:26:09.855  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:09.855  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:26:09.855  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:26:09.865  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 10:26:09.865  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:09.871  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:26:09.871  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:09.878  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:26:09.878  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:09.878  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
,09-14 10:26:09.883  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:26:09.883  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:09.884  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:26:09.889  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:26:09.889  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:10.354  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-14 10:26:10.354  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:10.354  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:12.803   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2166950, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:26:12.853  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:26:12.853  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:12.853  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:12.854  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:12.854  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:26:12.854  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 10:26:12.854  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-14 10:26:12.854  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a0d6bf removed from the list
,09-14 10:26:12.855  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:12.855  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da3d18c removed from the list
,09-14 10:26:12.855  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 10:26:12.855  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:12.858  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:12.858  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:12.862  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 10:26:12.862  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:12.862  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:12.862  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da3d18c not in the list
,09-14 10:26:12.862  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:12.863  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:12.865  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:12.865  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 10:26:12.865  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:12.866  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da3d18c not in the list
09-14 10:26:12.866  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:12.866  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:12.866  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:26:12.867  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a0d6bf not in the list
09-14 10:26:12.868  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 10:26:12.869  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@daee551 added. We now have 3 listener(s)
09-14 10:26:12.871  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:12.872  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:26:12.872  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:26:12.872  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:12.872  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc81b6 added. We now have 4 listener(s)
,09-14 10:26:12.872  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:26:12.873  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 10:26:12.877  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:12.883  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 10:26:12.885  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:12.886  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:26:12.886  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:12.887  5615  5672 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-14 10:26:12.888  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-14 10:26:12.888  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:12.888  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 10:26:12.888  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 10:26:12.888  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:12.890  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 10:26:12.891  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-14 10:26:12.891  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-14 10:26:12.891  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 10:26:12.891  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 10:26:12.891  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:12.891  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 10:26:12.891  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:12.892  5615  6042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:26:12.895  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:26:12.895  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:26:12.895  5615  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 10:26:12.896  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:26:12.896  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 10:26:12.889  5947  5947 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[35032]" dev="sockfs" ino=35032 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:12.889  5947  5947 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[35032]" dev="sockfs" ino=35032 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:26:12.899  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:26:12.900  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 10:26:12.900  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:26:12.901  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 10:26:12.902  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:12.902  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-14 10:26:12.903  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:12.903  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:12.903  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-14 10:26:12.904  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:12.908  5936  5973 D BtGatt.GattService: registerClient() - UUID=db3d6328-633c-45d6-975b-8936fb453115
09-14 10:26:12.909  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=db3d6328-633c-45d6-975b-8936fb453115, clientIf=5
,09-14 10:26:12.910  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 10:26:12.912  5936  5954 D BtGatt.AdvertiseManager: message : 0
,09-14 10:26:12.914  5936  5954 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 10:26:12.923  5936  5952 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 10:26:12.929  5936  5952 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 10:26:12.930  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-14 10:26:12.930  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 10:26:12.931  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:12.933  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:12.933  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 10:26:12.933  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 10:26:12.933  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 10:26:12.933  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 10:26:12.933  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 10:26:12.935  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-14 10:26:12.936  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 10:26:12.936  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 10:26:13.437  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-14 10:26:13.438  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 10:26:13.438  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:15.889  5537  5537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-14 10:26:15.890  5537  5537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 10:26:15.937  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:26:15.937  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-14 10:26:15.937  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:26:15.937  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-14 10:26:15.937  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-14 10:26:15.938  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 10:26:15.938  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 10:26:15.938  5615  6042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 10:26:15.938  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 10:26:15.938  5615  6042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 10:26:15.939  5615  6042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 10:26:15.939  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:26:15.939  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:26:15.939  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 10:26:15.939  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:26:15.939  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:26:15.939  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:26:15.941  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:15.942  5615  5672 D BluetoothLeScanner: could not find callback wrapper
09-14 10:26:15.942  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:26:15.942  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-14 10:26:15.944  5936  5954 D BtGatt.AdvertiseManager: message : 1
,09-14 10:26:15.947  5936  5954 D BtGatt.AdvertiseManager: stop advertise for client 5,
,09-14 10:26:15.958  5936  5952 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-14 10:26:15.958  5936  5952 D BtGatt.GattService: Client app is not null!
09-14 10:26:15.960  5936  5972 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:26:15.960  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:26:15.960  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-14 10:26:15.961  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 10:26:15.961  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 10:26:15.961  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-14 10:26:15.963  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:15.963  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:26:15.963  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 10:26:15.964  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 10:26:15.966  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 10:26:15.966  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-14 10:26:15.966  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:15.966  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:26:15.966  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 10:26:15.966  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@daee551 removed from the list
,09-14 10:26:15.966  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:15.967  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc81b6 removed from the list
09-14 10:26:15.967  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:15.967  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:26:15.967  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:15.967  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 10:26:15.967  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:15.968  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:15.968  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:15.970  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 10:26:15.970  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:15.970  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:15.970  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc81b6 not in the list
09-14 10:26:15.970  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:26:15.970  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:26:15.973  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 10:26:15.973  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:15.973  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:15.973  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afc81b6 not in the list
09-14 10:26:15.973  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:15.973  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:26:15.973  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:15.973  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@daee551 not in the list
09-14 10:26:15.974  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 10:26:15.974  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c6af53 added. We now have 3 listener(s)
,09-14 10:26:15.977  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:15.977  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:26:15.977  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:26:15.977  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:15.977  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c362090 added. We now have 4 listener(s)
09-14 10:26:15.977  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:26:15.978  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 10:26:15.982  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:15.988  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:15.991  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:15.991  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:26:15.991  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:15.991  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:26:15.992  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:26:15.992  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:15.992  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 10:26:15.996  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:15.996  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:26:15.997  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:26:15.999  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:16.002  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:26:16.003  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:26:16.003  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:26:16.007  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 10:26:16.007  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:26:16.007  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:26:16.008  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:16.011  5936  5972 D BtGatt.GattService: registerClient() - UUID=8c6e50c7-32f6-4ec4-9510-f2dd5fea2aa9
09-14 10:26:16.012  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=8c6e50c7-32f6-4ec4-9510-f2dd5fea2aa9, clientIf=5
,09-14 10:26:16.012  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:26:16.013  5936  5947 D BtGatt.GattService: start scan with filters
,09-14 10:26:16.015  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 10:26:16.015  5936  5955 D BtGatt.ScanManager: handling starting scan
09-14 10:26:16.015  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:26:16.015  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:26:16.016  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 10:26:16.018  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 10:26:16.018  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:26:16.018  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:26:16.020  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 10:26:16.022  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:26:16.022  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:16.022  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:26:16.027  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:26:16.027  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:16.027  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:26:16.027  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:26:16.037  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:26:16.038  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:16.043  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:26:16.043  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:16.468  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:26:16.518  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 10:26:16.519  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:16.519  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:19.029  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:26:19.029  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:26:19.030  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 10:26:19.031  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.032  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 10:26:19.032  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:26:19.032  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-14 10:26:19.032  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-14 10:26:19.032  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:26:19.033  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:26:19.033  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 10:26:19.034  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:19.036  5936  5973 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:26:19.039  5936  5947 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:26:19.040  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 10:26:19.040  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:19.041  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 10:26:19.041  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:26:19.041  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 10:26:19.042  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:19.043  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:26:19.043  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:26:19.043  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:26:19.044  5936  5936 D BtGatt.ScanManager: awakened up at time 2173191
,09-14 10:26:19.047  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 10:26:19.049  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 10:26:19.050  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.050  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:19.050  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:26:19.050  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:19.050  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 10:26:19.050  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:19.050  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c6af53 removed from the list
09-14 10:26:19.050  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:19.050  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c362090 removed from the list
09-14 10:26:19.050  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:26:19.050  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:26:19.051  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.051  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:19.052  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:19.052  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:26:19.052  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:19.052  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:19.052  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:26:19.053  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:19.053  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c362090 not in the list
09-14 10:26:19.053  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.053  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:19.055  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 10:26:19.055  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:19.055  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:19.055  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c362090 not in the list
09-14 10:26:19.055  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:19.055  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.055  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:19.055  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c6af53 not in the list
09-14 10:26:19.056  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 10:26:19.056  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a48d945 added. We now have 3 listener(s)
09-14 10:26:19.058  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:19.058  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:26:19.058  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:26:19.058  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:19.058  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395b89a added. We now have 4 listener(s)
,09-14 10:26:19.058  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:26:19.059  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:26:19.059  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:19.060  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 10:26:19.060  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 10:26:19.065  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:19.070  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:19.072  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:19.072  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:26:19.073  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:19.073  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:19.073  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:26:19.073  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:19.073  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.073  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 10:26:19.073  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 10:26:19.073  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a48d945 removed from the list
09-14 10:26:19.073  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:19.074  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395b89a removed from the list
,09-14 10:26:19.077  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:26:19.077  5615  5672 D io.jxcore.node.ConnectivityMonitor: stop
09-14 10:26:19.077  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 10:26:19.078  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 10:26:19.078  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:19.078  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-14 10:26:19.078  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:19.078  5936  5952 D BtGatt.GattService: current time is 2173225803769
09-14 10:26:19.079  5936  5952 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -76, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:26:19.079  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:19.079  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:19.079  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:19.079  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395b89a not in the list
09-14 10:26:19.079  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.079  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:19.081  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 10:26:19.081  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:19.081  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 10:26:19.081  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 10:26:19.081  5615  5672 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395b89a not in the list
09-14 10:26:19.081  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 10:26:19.081  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:19.081  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 10:26:19.081  5615  5672 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a48d945 not in the list
09-14 10:26:19.081  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:26:19.082  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:19.082  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:26:19.082  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:26:19.082  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-14 10:26:19.082  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:26:19.082  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 10:26:19.082  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:19.082  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:26:19.082  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 10:26:19.082  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:19.082  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:26:19.509   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 10:26:19.551  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:26:21.094  5615  6043 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-14 10:26:23.093  5615  5672 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
09-14 10:26:23.093  5615  5672 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-14 10:26:23.098  5615  6044 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-14 10:26:23.098  5615  6044 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
09-14 10:26:23.098  5615  6044 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-14 10:26:23.102  5615  5672 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:26:23.108  5615  6045 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-14 10:26:23.109  5615  6045 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-14 10:26:23.109  5615  6045 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-14 10:26:23.115  5615  5672 I jxcore-log: Total number of executed tests:  82
09-14 10:26:23.115  5615  5672 I jxcore-log: 
,09-14 10:26:23.116  5615  5672 I jxcore-log: Number of passed tests:  82
09-14 10:26:23.116  5615  5672 I jxcore-log: 
,09-14 10:26:23.116  5615  5672 I jxcore-log: Number of failed tests:  0
09-14 10:26:23.116  5615  5672 I jxcore-log: 
,09-14 10:26:23.117  5615  5672 I jxcore-log: Number of ignored tests:  0
09-14 10:26:23.117  5615  5672 I jxcore-log: 
09-14 10:26:23.117  5615  5672 I jxcore-log: Total duration:  100890
09-14 10:26:23.117  5615  5672 I jxcore-log: 
,09-14 10:26:23.123  5615  5672 I jxcore-log: Unit Test app is loaded
09-14 10:26:23.123  5615  5672 I jxcore-log: 
,09-14 10:26:23.136  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.136  5615  5672 I jxcore-log: 
,09-14 10:26:23.142  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.142  5615  5672 I jxcore-log: 
,09-14 10:26:23.144  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.144  5615  5672 I jxcore-log: 
,09-14 10:26:23.145  5615  5615 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-14 10:26:23.145  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.145  5615  5672 I jxcore-log: 
,09-14 10:26:23.148  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 10:26:23.148  5615  5672 I jxcore-log: 
,09-14 10:26:23.150  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:23.150  5615  5672 I jxcore-log: 
,09-14 10:26:23.153  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.153  5615  5672 I jxcore-log: 
,09-14 10:26:23.156  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.156  5615  5672 I jxcore-log: 
09-14 10:26:23.157  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 10:26:23.157  5615  5672 I jxcore-log: 
09-14 10:26:23.158  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:23.158  5615  5672 I jxcore-log: 
,09-14 10:26:23.159  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:23.159  5615  5672 I jxcore-log: 
09-14 10:26:23.160  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.160  5615  5672 I jxcore-log: 
,09-14 10:26:23.162  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.162  5615  5672 I jxcore-log: 
,09-14 10:26:23.163  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.163  5615  5672 I jxcore-log: 
09-14 10:26:23.164  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.164  5615  5672 I jxcore-log: 
,09-14 10:26:23.165  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.165  5615  5672 I jxcore-log: 
,09-14 10:26:23.167  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.167  5615  5672 I jxcore-log: 
,09-14 10:26:23.168  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.168  5615  5672 I jxcore-log: 
09-14 10:26:23.169  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.169  5615  5672 I jxcore-log: 
,09-14 10:26:23.170  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.170  5615  5672 I jxcore-log: 
,09-14 10:26:23.172  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.172  5615  5672 I jxcore-log: 
,09-14 10:26:23.173  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.173  5615  5672 I jxcore-log: 
09-14 10:26:23.174  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.174  5615  5672 I jxcore-log: 
,09-14 10:26:23.175  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.175  5615  5672 I jxcore-log: 
,09-14 10:26:23.176  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.176  5615  5672 I jxcore-log: 
09-14 10:26:23.177  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.177  5615  5672 I jxcore-log: 
,09-14 10:26:23.178  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.178  5615  5672 I jxcore-log: 
09-14 10:26:23.179  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.179  5615  5672 I jxcore-log: 
,09-14 10:26:23.180  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.180  5615  5672 I jxcore-log: 
,09-14 10:26:23.181  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.181  5615  5672 I jxcore-log: 
09-14 10:26:23.182  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.182  5615  5672 I jxcore-log: 
,09-14 10:26:23.183  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.183  5615  5672 I jxcore-log: 
,09-14 10:26:23.185  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.185  5615  5672 I jxcore-log: 
09-14 10:26:23.186  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.186  5615  5672 I jxcore-log: 
,09-14 10:26:23.186  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.186  5615  5672 I jxcore-log: 
,09-14 10:26:23.187  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.187  5615  5672 I jxcore-log: 
09-14 10:26:23.188  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.188  5615  5672 I jxcore-log: 
,09-14 10:26:23.189  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.189  5615  5672 I jxcore-log: 
09-14 10:26:23.189  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.189  5615  5672 I jxcore-log: 
,09-14 10:26:23.190  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.190  5615  5672 I jxcore-log: 
09-14 10:26:23.191  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 10:26:23.191  5615  5672 I jxcore-log: 
,09-14 10:26:23.191  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.191  5615  5672 I jxcore-log: 
09-14 10:26:23.192  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.192  5615  5672 I jxcore-log: 
,09-14 10:26:23.193  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 10:26:23.193  5615  5672 I jxcore-log: 
09-14 10:26:23.194  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.194  5615  5672 I jxcore-log: 
,09-14 10:26:23.194  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.194  5615  5672 I jxcore-log: 
09-14 10:26:23.195  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.195  5615  5672 I jxcore-log: 
,09-14 10:26:23.196  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.196  5615  5672 I jxcore-log: 
,09-14 10:26:23.197  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:23.197  5615  5672 I jxcore-log: 
09-14 10:26:23.198  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.198  5615  5672 I jxcore-log: 
,09-14 10:26:23.198  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 10:26:23.198  5615  5672 I jxcore-log: 
09-14 10:26:23.199  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.199  5615  5672 I jxcore-log: 
,09-14 10:26:23.200  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:23.200  5615  5672 I jxcore-log: 
09-14 10:26:23.200  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 10:26:23.200  5615  5672 I jxcore-log: 
,09-14 10:26:23.201  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:23.201  5615  5672 I jxcore-log: 
09-14 10:26:23.202  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:23.202  5615  5672 I jxcore-log: 
,09-14 10:26:23.203  5615  6043 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-14 10:26:23.206  5615  5672 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-14 10:26:23.206  5615  5672 I jxcore-log:   bluetooth: 'on',
09-14 10:26:23.206  5615  5672 I jxcore-log:   wifi: 'on',
09-14 10:26:23.206  5615  5672 I jxcore-log:   cellular: 'doNotCare',
09-14 10:26:23.206  5615  5672 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-14 10:26:23.206  5615  5672 I jxcore-log: 
,09-14 10:26:23.210  5615  5672 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-14 10:26:23.210  5615  5672 I jxcore-log:   bluetooth: 'on',
09-14 10:26:23.210  5615  5672 I jxcore-log:   wifi: 'on',
09-14 10:26:23.210  5615  5672 I jxcore-log:   cellular: 'doNotCare',
09-14 10:26:23.210  5615  5672 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-14 10:26:23.210  5615  5672 I jxcore-log: 
,09-14 10:26:23.210  5615  5672 I jxcore-log: My device name is: Huawei-Nexus 6P
09-14 10:26:23.210  5615  5672 I jxcore-log: 
09-14 10:26:23.211  5615  5672 I jxcore-log: WARN testUtils: myNameCallback not set!
09-14 10:26:23.211  5615  5672 I jxcore-log: 
09-14 10:26:23.211  5615  5672 I jxcore-log: Running for WIFI network type
09-14 10:26:23.211  5615  5672 I jxcore-log: 
,09-14 10:26:24.983  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-14 10:26:24.983  5615  5672 I jxcore-log: 
,09-14 10:26:25.286  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-14 10:26:25.286  5615  5672 I jxcore-log: 
,09-14 10:26:25.310  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-14 10:26:25.310  5615  5672 I jxcore-log: 
,09-14 10:26:25.313  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-14 10:26:25.313  5615  5672 I jxcore-log: 
,09-14 10:26:25.317  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-14 10:26:25.317  5615  5672 I jxcore-log: 
,09-14 10:26:25.357  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-14 10:26:25.357  5615  5672 I jxcore-log: 
,09-14 10:26:25.368  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-14 10:26:25.368  5615  5672 I jxcore-log: 
,09-14 10:26:25.371  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-14 10:26:25.371  5615  5672 I jxcore-log: 
,09-14 10:26:25.567   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 10:26:25.878  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-14 10:26:25.878  5615  5672 I jxcore-log: 
,09-14 10:26:25.885  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-14 10:26:25.885  5615  5672 I jxcore-log: 
,09-14 10:26:25.891  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-14 10:26:25.891  5615  5672 I jxcore-log: 
,09-14 10:26:26.040  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-14 10:26:26.040  5615  5672 I jxcore-log: 
,09-14 10:26:27.095  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-14 10:26:27.095  5615  5672 I jxcore-log: 
,09-14 10:26:27.128  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-14 10:26:27.128  5615  5672 I jxcore-log: 
,09-14 10:26:27.133  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-14 10:26:27.133  5615  5672 I jxcore-log: 
,09-14 10:26:27.224  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-14 10:26:27.224  5615  5672 I jxcore-log: 
,09-14 10:26:27.238  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-14 10:26:27.238  5615  5672 I jxcore-log: 
,09-14 10:26:27.242  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-14 10:26:27.242  5615  5672 I jxcore-log: 
,09-14 10:26:27.246  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-14 10:26:27.246  5615  5672 I jxcore-log: 
,09-14 10:26:27.256  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-14 10:26:27.256  5615  5672 I jxcore-log: 
,09-14 10:26:27.362  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-14 10:26:27.362  5615  5672 I jxcore-log: 
,09-14 10:26:27.379  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-14 10:26:27.379  5615  5672 I jxcore-log: 
,09-14 10:26:27.389  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-14 10:26:27.389  5615  5672 I jxcore-log: 
,09-14 10:26:27.397  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-14 10:26:27.397  5615  5672 I jxcore-log: 
,09-14 10:26:27.407  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-14 10:26:27.407  5615  5672 I jxcore-log: 
,09-14 10:26:27.428  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-14 10:26:27.428  5615  5672 I jxcore-log: 
,09-14 10:26:27.432  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-14 10:26:27.432  5615  5672 I jxcore-log: 
,09-14 10:26:27.451  5615  5672 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-14 10:26:27.451  5615  5672 I jxcore-log: 
,09-14 10:26:27.458  5615  5672 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-14 10:26:27.459  5615  5672 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-14 10:26:27.459  5615  5672 I jxcore-log: 
,09-14 10:26:27.461  5615  5672 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-14 10:26:27.461  5615  5672 I jxcore-log: 
,09-14 10:26:27.461  5615  5672 I jxcore-log: ThaliTape :: Started ThaliTape
09-14 10:26:27.461  5615  5672 I jxcore-log: 
,09-14 10:26:27.465  5615  5672 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-14 10:26:27.465  5615  5672 I jxcore-log: 
,09-14 10:26:27.593  5615  5672 I jxcore-log: ThaliTape :: Connected to the test server
09-14 10:26:27.593  5615  5672 I jxcore-log: 
,09-14 10:26:27.984  5615  5672 I jxcore-log: TAP version 13
09-14 10:26:27.984  5615  5672 I jxcore-log: 
,09-14 10:26:27.988  5615  5672 I jxcore-log: # setup
09-14 10:26:27.988  5615  5672 I jxcore-log: 
,09-14 10:26:28.593   923  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 10:26:29.042  5615  5672 I jxcore-log: # 1. calling createNativeListener directly rejects
09-14 10:26:29.042  5615  5672 I jxcore-log: 
,09-14 10:26:29.095  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:29.095  5615  5672 I jxcore-log: 
,09-14 10:26:29.099  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 45470
09-14 10:26:29.099  5615  5672 I jxcore-log: 
,09-14 10:26:29.105  5615  5672 I jxcore-log: ok 1 Should throw
09-14 10:26:29.105  5615  5672 I jxcore-log: 
,09-14 10:26:29.108  5615  5672 I jxcore-log: # teardown
09-14 10:26:29.108  5615  5672 I jxcore-log: 
,09-14 10:26:29.211  5615  5672 I jxcore-log: # setup
09-14 10:26:29.211  5615  5672 I jxcore-log: 
,09-14 10:26:29.287  5615  5672 I jxcore-log: # 2. emits incomingConnectionState
09-14 10:26:29.287  5615  5672 I jxcore-log: 
,09-14 10:26:29.397  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:29.397  5615  5672 I jxcore-log: 
,09-14 10:26:29.404  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 45506
09-14 10:26:29.404  5615  5672 I jxcore-log: 
,09-14 10:26:29.431  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:29.431  5615  5672 I jxcore-log: 
,09-14 10:26:29.434  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:29.434  5615  5672 I jxcore-log: 
,09-14 10:26:29.444  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:29.444  5615  5672 I jxcore-log: 
,09-14 10:26:29.451  5615  5672 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-14 10:26:29.451  5615  5672 I jxcore-log: 
,09-14 10:26:29.474  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:29.474  5615  5672 I jxcore-log: 
,09-14 10:26:29.475  5615  5672 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-14 10:26:29.475  5615  5672 I jxcore-log: 
,09-14 10:26:29.481  5615  5672 I jxcore-log: # teardown
09-14 10:26:29.481  5615  5672 I jxcore-log: 
,09-14 10:26:29.538  5615  5672 I jxcore-log: # setup
09-14 10:26:29.538  5615  5672 I jxcore-log: 
,09-14 10:26:29.649  5615  5672 I jxcore-log: # 3. emits routerPortConnectionFailed
09-14 10:26:29.649  5615  5672 I jxcore-log: 
,09-14 10:26:29.766  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:29.766  5615  5672 I jxcore-log: 
,09-14 10:26:29.771  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 43501
09-14 10:26:29.771  5615  5672 I jxcore-log: 
,09-14 10:26:29.782  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:29.782  5615  5672 I jxcore-log: 
,09-14 10:26:29.784  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:29.784  5615  5672 I jxcore-log: 
,09-14 10:26:29.787  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:29.787  5615  5672 I jxcore-log: 
,09-14 10:26:29.821  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:29.821  5615  5672 I jxcore-log: 
,09-14 10:26:29.824  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:29.824  5615  5672 I jxcore-log: 
,09-14 10:26:29.829  5615  5672 I jxcore-log: DEBUG createNativeListener: 
09-14 10:26:29.829  5615  5672 I jxcore-log: 
,09-14 10:26:29.830  5615  5672 I jxcore-log: ok 4 tried to connect to right port
09-14 10:26:29.830  5615  5672 I jxcore-log: 
09-14 10:26:29.831  5615  5672 I jxcore-log: ok 5 failed due to refused connection
09-14 10:26:29.831  5615  5672 I jxcore-log: 
09-14 10:26:29.831  5615  5672 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-14 10:26:29.831  5615  5672 I jxcore-log: 
,09-14 10:26:29.834  5615  5672 I jxcore-log: # teardown
09-14 10:26:29.834  5615  5672 I jxcore-log: 
,09-14 10:26:29.835  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:29.835  5615  5672 I jxcore-log: 
,09-14 10:26:29.912  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:29.912  5615  5672 I jxcore-log: 
,09-14 10:26:29.919  5615  5672 I jxcore-log: # setup
09-14 10:26:29.919  5615  5672 I jxcore-log: 
,09-14 10:26:29.920  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:29.920  5615  5672 I jxcore-log: 
,09-14 10:26:30.037  5615  5672 I jxcore-log: # 4. native server connections all up
09-14 10:26:30.037  5615  5672 I jxcore-log: 
,09-14 10:26:30.126  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:30.126  5615  5672 I jxcore-log: 
,09-14 10:26:30.133  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 45034
09-14 10:26:30.133  5615  5672 I jxcore-log: 
,09-14 10:26:30.147  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:30.147  5615  5672 I jxcore-log: 
,09-14 10:26:30.150  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:30.150  5615  5672 I jxcore-log: 
,09-14 10:26:30.153  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:30.153  5615  5672 I jxcore-log: 
,09-14 10:26:30.195  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:30.195  5615  5672 I jxcore-log: 
,09-14 10:26:30.200  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:30.200  5615  5672 I jxcore-log: 
,09-14 10:26:30.204  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:30.204  5615  5672 I jxcore-log: 
,09-14 10:26:30.208  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:30.208  5615  5672 I jxcore-log: 
,09-14 10:26:30.229  5615  5672 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-14 10:26:30.229  5615  5672 I jxcore-log: 
,09-14 10:26:30.230  5615  5672 I jxcore-log: ok 8 Send/recvd #1 should be same
09-14 10:26:30.230  5615  5672 I jxcore-log: 
09-14 10:26:30.232  5615  5672 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-14 10:26:30.232  5615  5672 I jxcore-log: 
09-14 10:26:30.233  5615  5672 I jxcore-log: ok 10 Send/recvd #2 should be same
09-14 10:26:30.233  5615  5672 I jxcore-log: 
,09-14 10:26:30.235  5615  5672 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-14 10:26:30.235  5615  5672 I jxcore-log: 
,09-14 10:26:30.240  5615  5672 I jxcore-log: # teardown
09-14 10:26:30.240  5615  5672 I jxcore-log: 
,09-14 10:26:30.317  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:30.317  5615  5672 I jxcore-log: 
,09-14 10:26:30.318  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:30.318  5615  5672 I jxcore-log: 
,09-14 10:26:30.321  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:30.321  5615  5672 I jxcore-log: 
,09-14 10:26:30.324  5615  5672 I jxcore-log: # setup
09-14 10:26:30.324  5615  5672 I jxcore-log: 
,09-14 10:26:30.326  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:30.326  5615  5672 I jxcore-log: 
,09-14 10:26:30.430  5615  5672 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-14 10:26:30.430  5615  5672 I jxcore-log: 
,09-14 10:26:30.515  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:30.515  5615  5672 I jxcore-log: 
,09-14 10:26:30.522  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 43958
09-14 10:26:30.522  5615  5672 I jxcore-log: 
,09-14 10:26:30.533  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:30.533  5615  5672 I jxcore-log: 
,09-14 10:26:30.535  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:30.535  5615  5672 I jxcore-log: 
,09-14 10:26:30.538  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:30.538  5615  5672 I jxcore-log: 
,09-14 10:26:30.560  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:30.560  5615  5672 I jxcore-log: 
,09-14 10:26:30.564  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:30.564  5615  5672 I jxcore-log: 
,09-14 10:26:30.579  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:30.579  5615  5672 I jxcore-log: 
,09-14 10:26:30.596  5615  5672 I jxcore-log: ok 12 socket shouldn't close until after stream
09-14 10:26:30.596  5615  5672 I jxcore-log: 
,09-14 10:26:30.597  5615  5672 I jxcore-log: ok 13 incoming remains open
09-14 10:26:30.597  5615  5672 I jxcore-log: 
,09-14 10:26:30.600  5615  5672 I jxcore-log: # teardown
09-14 10:26:30.600  5615  5672 I jxcore-log: 
,09-14 10:26:30.668  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:30.668  5615  5672 I jxcore-log: 
,09-14 10:26:30.678  5615  5672 I jxcore-log: # setup
09-14 10:26:30.678  5615  5672 I jxcore-log: 
,09-14 10:26:30.680  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:30.680  5615  5672 I jxcore-log: 
,09-14 10:26:30.784  5615  5672 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-14 10:26:30.784  5615  5672 I jxcore-log: 
,09-14 10:26:30.860  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:30.860  5615  5672 I jxcore-log: 
,09-14 10:26:30.866  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 43531
09-14 10:26:30.866  5615  5672 I jxcore-log: 
,09-14 10:26:30.877  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:30.877  5615  5672 I jxcore-log: 
,09-14 10:26:30.880  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:30.880  5615  5672 I jxcore-log: 
,09-14 10:26:30.882  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:30.882  5615  5672 I jxcore-log: 
,09-14 10:26:30.906  5615  5672 I jxcore-log: ok 14 we should not have gotten an error
09-14 10:26:30.906  5615  5672 I jxcore-log: 
,09-14 10:26:30.915  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:30.915  5615  5672 I jxcore-log: 
,09-14 10:26:30.920  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:30.920  5615  5672 I jxcore-log: 
,09-14 10:26:30.931  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:30.931  5615  5672 I jxcore-log: 
,09-14 10:26:30.933  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:30.933  5615  5672 I jxcore-log: 
,09-14 10:26:30.943  5615  5672 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-14 10:26:30.943  5615  5672 I jxcore-log: 
,09-14 10:26:30.944  5615  5672 I jxcore-log: ok 16 incoming is cleaned up
09-14 10:26:30.944  5615  5672 I jxcore-log: 
09-14 10:26:30.947  5615  5672 I jxcore-log: # teardown
09-14 10:26:30.947  5615  5672 I jxcore-log: 
,09-14 10:26:31.012  5615  5672 I jxcore-log: # setup
09-14 10:26:31.012  5615  5672 I jxcore-log: 
,09-14 10:26:31.097  5615  5672 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-14 10:26:31.097  5615  5672 I jxcore-log: 
,09-14 10:26:31.141  3623  5662 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-14 10:26:31.179  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:31.179  5615  5672 I jxcore-log: 
,09-14 10:26:31.184  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 48868
09-14 10:26:31.184  5615  5672 I jxcore-log: 
,09-14 10:26:31.193  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.193  5615  5672 I jxcore-log: 
,09-14 10:26:31.195  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.195  5615  5672 I jxcore-log: 
,09-14 10:26:31.201  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.201  5615  5672 I jxcore-log: 
,09-14 10:26:31.218  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:31.218  5615  5672 I jxcore-log: 
,09-14 10:26:31.222  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:31.222  5615  5672 I jxcore-log: 
,09-14 10:26:31.236  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:31.236  5615  5672 I jxcore-log: 
,09-14 10:26:31.250  5615  5672 I jxcore-log: ok 17 stream was closed
09-14 10:26:31.250  5615  5672 I jxcore-log: 
,09-14 10:26:31.251  5615  5672 I jxcore-log: ok 18 incoming should survive
09-14 10:26:31.251  5615  5672 I jxcore-log: 
09-14 10:26:31.251  5615  5672 I jxcore-log: ok 19 mux should have no streams
09-14 10:26:31.251  5615  5672 I jxcore-log: 
,09-14 10:26:31.255  5615  5672 I jxcore-log: # teardown
09-14 10:26:31.255  5615  5672 I jxcore-log: 
,09-14 10:26:31.367  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:31.367  5615  5672 I jxcore-log: 
,09-14 10:26:31.378  5615  5672 I jxcore-log: # setup
09-14 10:26:31.378  5615  5672 I jxcore-log: 
,09-14 10:26:31.381  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:31.381  5615  5672 I jxcore-log: 
,09-14 10:26:31.492  5615  5672 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-14 10:26:31.492  5615  5672 I jxcore-log: 
,09-14 10:26:31.550  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:31.550  5615  5672 I jxcore-log: 
,09-14 10:26:31.554  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 45884
09-14 10:26:31.554  5615  5672 I jxcore-log: 
,09-14 10:26:31.564  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.564  5615  5672 I jxcore-log: 
,09-14 10:26:31.566  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.566  5615  5672 I jxcore-log: 
,09-14 10:26:31.575  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.575  5615  5672 I jxcore-log: 
,09-14 10:26:31.585  5615  5672 I jxcore-log: ok 20 we should not have gotten an error
09-14 10:26:31.585  5615  5672 I jxcore-log: 
,09-14 10:26:31.594  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:31.594  5615  5672 I jxcore-log: 
,09-14 10:26:31.597  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:31.597  5615  5672 I jxcore-log: 
,09-14 10:26:31.608  5615  5672 I jxcore-log: ok 21 Buffers are identical
09-14 10:26:31.608  5615  5672 I jxcore-log: 
,09-14 10:26:31.610  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:31.610  5615  5672 I jxcore-log: 
,09-14 10:26:31.613  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:31.613  5615  5672 I jxcore-log: 
,09-14 10:26:31.615  5615  5672 I jxcore-log: ok 22 native server is nulled out
09-14 10:26:31.615  5615  5672 I jxcore-log: 
,09-14 10:26:31.616  5615  5672 I jxcore-log: ok 23 native server should be closed
09-14 10:26:31.616  5615  5672 I jxcore-log: 
09-14 10:26:31.616  5615  5672 I jxcore-log: ok 24 incoming has been removed
09-14 10:26:31.616  5615  5672 I jxcore-log: 
,09-14 10:26:31.617  5615  5672 I jxcore-log: ok 25 Incoming should be done
09-14 10:26:31.617  5615  5672 I jxcore-log: 
09-14 10:26:31.617  5615  5672 I jxcore-log: ok 26 The mux object should be closed
09-14 10:26:31.617  5615  5672 I jxcore-log: 
,09-14 10:26:31.617  5615  5672 I jxcore-log: ok 27 The mux stream should be closed
09-14 10:26:31.617  5615  5672 I jxcore-log: 
09-14 10:26:31.618  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:31.618  5615  5672 I jxcore-log: 
,09-14 10:26:31.629  5615  5672 I jxcore-log: # teardown
09-14 10:26:31.629  5615  5672 I jxcore-log: 
,09-14 10:26:31.701  5615  5672 I jxcore-log: # setup
09-14 10:26:31.701  5615  5672 I jxcore-log: 
,09-14 10:26:31.781  5615  5672 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-14 10:26:31.781  5615  5672 I jxcore-log: 
,09-14 10:26:31.845   923   943 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-14 10:26:31.846  3422  3422 W Binder_6: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[35846]" dev="sockfs" ino=35846 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:26:31.849  3422  3422 W Binder_6: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[35846]" dev="sockfs" ino=35846 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:26:31.862  3392  3392 I Keyboard.Facilitator: onFinishInput()
,09-14 10:26:31.872  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:31.872  5615  5672 I jxcore-log: 
,09-14 10:26:31.875  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 49348
09-14 10:26:31.875  5615  5672 I jxcore-log: 
,09-14 10:26:31.908  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.908  5615  5672 I jxcore-log: 
,09-14 10:26:31.912  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.912  5615  5672 I jxcore-log: 
,09-14 10:26:31.918  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.918  5615  5672 I jxcore-log: 
,09-14 10:26:31.921  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.921  5615  5672 I jxcore-log: 
,09-14 10:26:31.922  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.922  5615  5672 I jxcore-log: 
09-14 10:26:31.923  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.923  5615  5672 I jxcore-log: 
,09-14 10:26:31.925  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.925  5615  5672 I jxcore-log: 
,09-14 10:26:31.926  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.926  5615  5672 I jxcore-log: 
,09-14 10:26:31.927  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.927  5615  5672 I jxcore-log: 
,09-14 10:26:31.930  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.930  5615  5672 I jxcore-log: 
,09-14 10:26:31.931  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.931  5615  5672 I jxcore-log: 
,09-14 10:26:31.932  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.932  5615  5672 I jxcore-log: 
,09-14 10:26:31.935  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.935  5615  5672 I jxcore-log: 
,09-14 10:26:31.936  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.936  5615  5672 I jxcore-log: 
,09-14 10:26:31.937  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.937  5615  5672 I jxcore-log: 
,09-14 10:26:31.940  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.940  5615  5672 I jxcore-log: 
,09-14 10:26:31.940  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.940  5615  5672 I jxcore-log: 
,09-14 10:26:31.941  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.941  5615  5672 I jxcore-log: 
,09-14 10:26:31.951  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.951  5615  5672 I jxcore-log: 
,09-14 10:26:31.953  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.953  5615  5672 I jxcore-log: 
,09-14 10:26:31.954  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.954  5615  5672 I jxcore-log: 
,09-14 10:26:31.957  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.957  5615  5672 I jxcore-log: 
,09-14 10:26:31.957  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.957  5615  5672 I jxcore-log: 
09-14 10:26:31.958  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.958  5615  5672 I jxcore-log: 
,09-14 10:26:31.959  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.959  5615  5672 I jxcore-log: 
,09-14 10:26:31.959  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.959  5615  5672 I jxcore-log: 
,09-14 10:26:31.960  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.960  5615  5672 I jxcore-log: 
,09-14 10:26:31.961  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:31.961  5615  5672 I jxcore-log: 
09-14 10:26:31.961  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:31.961  5615  5672 I jxcore-log: 
,09-14 10:26:31.962  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:31.962  5615  5672 I jxcore-log: 
,09-14 10:26:32.021  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.021  5615  5672 I jxcore-log: 
,09-14 10:26:32.023  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.023  5615  5672 I jxcore-log: 
,09-14 10:26:32.024  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.024  5615  5672 I jxcore-log: 
,09-14 10:26:32.025  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.025  5615  5672 I jxcore-log: 
,09-14 10:26:32.026  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.026  5615  5672 I jxcore-log: 
,09-14 10:26:32.027  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.027  5615  5672 I jxcore-log: 
,09-14 10:26:32.028  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.028  5615  5672 I jxcore-log: 
09-14 10:26:32.029  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.029  5615  5672 I jxcore-log: 
,09-14 10:26:32.030  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.030  5615  5672 I jxcore-log: 
,09-14 10:26:32.031  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.031  5615  5672 I jxcore-log: 
,09-14 10:26:32.032  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.032  5615  5672 I jxcore-log: 
09-14 10:26:32.033  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.033  5615  5672 I jxcore-log: 
,09-14 10:26:32.033  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.033  5615  5672 I jxcore-log: 
09-14 10:26:32.034  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.034  5615  5672 I jxcore-log: 
09-14 10:26:32.035  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.035  5615  5672 I jxcore-log: 
,09-14 10:26:32.036  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.036  5615  5672 I jxcore-log: 
09-14 10:26:32.038  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.038  5615  5672 I jxcore-log: 
,09-14 10:26:32.039  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.039  5615  5672 I jxcore-log: 
,09-14 10:26:32.039  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.039  5615  5672 I jxcore-log: 
,09-14 10:26:32.042  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.042  5615  5672 I jxcore-log: 
,09-14 10:26:32.043  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.043  5615  5672 I jxcore-log: 
,09-14 10:26:32.044  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.044  5615  5672 I jxcore-log: 
,09-14 10:26:32.045  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.045  5615  5672 I jxcore-log: 
09-14 10:26:32.046  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.046  5615  5672 I jxcore-log: 
,09-14 10:26:32.047  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.047  5615  5672 I jxcore-log: 
,09-14 10:26:32.048  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.048  5615  5672 I jxcore-log: 
09-14 10:26:32.048  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.048  5615  5672 I jxcore-log: 
,09-14 10:26:32.049  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.049  5615  5672 I jxcore-log: 
,09-14 10:26:32.050  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.050  5615  5672 I jxcore-log: 
09-14 10:26:32.051  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.051  5615  5672 I jxcore-log: 
09-14 10:26:32.051  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.051  5615  5672 I jxcore-log: 
09-14 10:26:32.052  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.052  5615  5672 I jxcore-log: 
09-14 10:26:32.053  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.053  5615  5672 I jxcore-log: 
,09-14 10:26:32.054  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.054  5615  5672 I jxcore-log: 
,09-14 10:26:32.054  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.054  5615  5672 I jxcore-log: 
09-14 10:26:32.055  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.055  5615  5672 I jxcore-log: 
09-14 10:26:32.055  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.055  5615  5672 I jxcore-log: 
09-14 10:26:32.056  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.056  5615  5672 I jxcore-log: 
,09-14 10:26:32.061  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.061  5615  5672 I jxcore-log: 
,09-14 10:26:32.062  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.062  5615  5672 I jxcore-log: 
,09-14 10:26:32.064  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.064  5615  5672 I jxcore-log: 
,09-14 10:26:32.065  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.065  5615  5672 I jxcore-log: 
,09-14 10:26:32.066  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.066  5615  5672 I jxcore-log: 
,09-14 10:26:32.066  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.066  5615  5672 I jxcore-log: 
,09-14 10:26:32.067  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.067  5615  5672 I jxcore-log: 
09-14 10:26:32.068  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.068  5615  5672 I jxcore-log: 
09-14 10:26:32.068  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.068  5615  5672 I jxcore-log: 
,09-14 10:26:32.069  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.069  5615  5672 I jxcore-log: 
09-14 10:26:32.070  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.070  5615  5672 I jxcore-log: 
,09-14 10:26:32.071  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.071  5615  5672 I jxcore-log: 
,09-14 10:26:32.071  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.071  5615  5672 I jxcore-log: 
09-14 10:26:32.072  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.072  5615  5672 I jxcore-log: 
,09-14 10:26:32.073  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.073  5615  5672 I jxcore-log: 
,09-14 10:26:32.073  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.073  5615  5672 I jxcore-log: 
09-14 10:26:32.074  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.074  5615  5672 I jxcore-log: 
,09-14 10:26:32.075  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.075  5615  5672 I jxcore-log: 
,09-14 10:26:32.075  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.075  5615  5672 I jxcore-log: 
09-14 10:26:32.076  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.076  5615  5672 I jxcore-log: 
,09-14 10:26:32.077  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.077  5615  5672 I jxcore-log: 
,09-14 10:26:32.078  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.078  5615  5672 I jxcore-log: 
09-14 10:26:32.078  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.078  5615  5672 I jxcore-log: 
09-14 10:26:32.079  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.079  5615  5672 I jxcore-log: 
,09-14 10:26:32.079  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.079  5615  5672 I jxcore-log: 
,09-14 10:26:32.080  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.080  5615  5672 I jxcore-log: 
,09-14 10:26:32.081  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.081  5615  5672 I jxcore-log: 
,09-14 10:26:32.082  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.082  5615  5672 I jxcore-log: 
09-14 10:26:32.082  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.082  5615  5672 I jxcore-log: 
,09-14 10:26:32.083  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.083  5615  5672 I jxcore-log: 
09-14 10:26:32.084  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.084  5615  5672 I jxcore-log: 
09-14 10:26:32.084  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.084  5615  5672 I jxcore-log: 
,09-14 10:26:32.085  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.085  5615  5672 I jxcore-log: 
09-14 10:26:32.086  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.086  5615  5672 I jxcore-log: 
09-14 10:26:32.087  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.087  5615  5672 I jxcore-log: 
09-14 10:26:32.087  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.087  5615  5672 I jxcore-log: 
,09-14 10:26:32.088  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.088  5615  5672 I jxcore-log: 
,09-14 10:26:32.089  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.089  5615  5672 I jxcore-log: 
09-14 10:26:32.089  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.089  5615  5672 I jxcore-log: 
,09-14 10:26:32.090  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.090  5615  5672 I jxcore-log: 
,09-14 10:26:32.090  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:32.090  5615  5672 I jxcore-log: 
09-14 10:26:32.091  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:32.091  5615  5672 I jxcore-log: 
,09-14 10:26:32.136  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.136  5615  5672 I jxcore-log: 
,09-14 10:26:32.137  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.137  5615  5672 I jxcore-log: 
,09-14 10:26:32.138  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.138  5615  5672 I jxcore-log: 
09-14 10:26:32.139  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.139  5615  5672 I jxcore-log: 
,09-14 10:26:32.140  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.140  5615  5672 I jxcore-log: 
09-14 10:26:32.140  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.140  5615  5672 I jxcore-log: 
,09-14 10:26:32.141  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.141  5615  5672 I jxcore-log: 
09-14 10:26:32.141  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.141  5615  5672 I jxcore-log: 
,09-14 10:26:32.142  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.142  5615  5672 I jxcore-log: 
09-14 10:26:32.142  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.142  5615  5672 I jxcore-log: 
,09-14 10:26:32.143  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.143  5615  5672 I jxcore-log: 
09-14 10:26:32.145  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.145  5615  5672 I jxcore-log: 
,09-14 10:26:32.145  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.145  5615  5672 I jxcore-log: 
09-14 10:26:32.146  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.146  5615  5672 I jxcore-log: 
09-14 10:26:32.147  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.147  5615  5672 I jxcore-log: 
,09-14 10:26:32.151  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.151  5615  5672 I jxcore-log: 
09-14 10:26:32.153  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.153  5615  5672 I jxcore-log: 
,09-14 10:26:32.154  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.154  5615  5672 I jxcore-log: 
09-14 10:26:32.154  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.154  5615  5672 I jxcore-log: 
,09-14 10:26:32.155  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.155  5615  5672 I jxcore-log: 
09-14 10:26:32.155  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.155  5615  5672 I jxcore-log: 
09-14 10:26:32.156  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.156  5615  5672 I jxcore-log: 
,09-14 10:26:32.156  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.156  5615  5672 I jxcore-log: 
09-14 10:26:32.156  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.156  5615  5672 I jxcore-log: 
,09-14 10:26:32.157  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.157  5615  5672 I jxcore-log: 
09-14 10:26:32.158  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.158  5615  5672 I jxcore-log: 
09-14 10:26:32.158  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.158  5615  5672 I jxcore-log: 
09-14 10:26:32.158  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.158  5615  5672 I jxcore-log: 
09-14 10:26:32.159  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.159  5615  5672 I jxcore-log: 
,09-14 10:26:32.159  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.159  5615  5672 I jxcore-log: 
,09-14 10:26:32.160  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.160  5615  5672 I jxcore-log: 
09-14 10:26:32.160  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.160  5615  5672 I jxcore-log: 
09-14 10:26:32.161  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.161  5615  5672 I jxcore-log: 
09-14 10:26:32.161  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.161  5615  5672 I jxcore-log: 
,09-14 10:26:32.161  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.161  5615  5672 I jxcore-log: 
09-14 10:26:32.162  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.162  5615  5672 I jxcore-log: 
09-14 10:26:32.162  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.162  5615  5672 I jxcore-log: 
09-14 10:26:32.163  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.163  5615  5672 I jxcore-log: 
,09-14 10:26:32.163  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.163  5615  5672 I jxcore-log: 
09-14 10:26:32.163  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.163  5615  5672 I jxcore-log: 
09-14 10:26:32.164  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.164  5615  5672 I jxcore-log: 
,09-14 10:26:32.164  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.164  5615  5672 I jxcore-log: 
09-14 10:26:32.165  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.165  5615  5672 I jxcore-log: 
09-14 10:26:32.165  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.165  5615  5672 I jxcore-log: 
,09-14 10:26:32.165  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.165  5615  5672 I jxcore-log: 
09-14 10:26:32.166  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.166  5615  5672 I jxcore-log: 
09-14 10:26:32.166  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.166  5615  5672 I jxcore-log: 
09-14 10:26:32.167  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.167  5615  5672 I jxcore-log: 
,09-14 10:26:32.167  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:32.167  5615  5672 I jxcore-log: 
09-14 10:26:32.168  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:32.168  5615  5672 I jxcore-log: 
09-14 10:26:32.170  5615  5672 I jxcore-log: ok 28 native server is nulled out
09-14 10:26:32.170  5615  5672 I jxcore-log: 
09-14 10:26:32.170  5615  5672 I jxcore-log: ok 29 native server should be closed
09-14 10:26:32.170  5615  5672 I jxcore-log: 
09-14 10:26:32.171  5615  5672 I jxcore-log: ok 30 incoming has been removed
09-14 10:26:32.171  5615  5672 I jxcore-log: 
09-14 10:26:32.171  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.171  5615  5672 I jxcore-log: 
09-14 10:26:32.172  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.172  5615  5672 I jxcore-log: 
,09-14 10:26:32.172  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.172  5615  5672 I jxcore-log: 
09-14 10:26:32.172  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.172  5615  5672 I jxcore-log: 
09-14 10:26:32.173  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.173  5615  5672 I jxcore-log: 
,09-14 10:26:32.173  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.173  5615  5672 I jxcore-log: 
09-14 10:26:32.173  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.173  5615  5672 I jxcore-log: 
09-14 10:26:32.173  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.173  5615  5672 I jxcore-log: 
09-14 10:26:32.173  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.173  5615  5672 I jxcore-log: 
09-14 10:26:32.173  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:32.173  5615  5672 I jxcore-log: 
,09-14 10:26:32.251  5615  5672 I jxcore-log: # teardown
09-14 10:26:32.251  5615  5672 I jxcore-log: 
,09-14 10:26:32.385  5615  5615 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-14 10:26:32.385  5615  5615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-14 10:26:32.415   923   943 I sensors : batch
,09-14 10:26:32.415   923   943 V KeyguardServiceDelegate: onScreenTurnedOff()
09-14 10:26:32.418   923   943 I sensors : activate
09-14 10:26:32.417  5615  5615 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@68cc745 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2c571a8, 16908290=android.view.AbsSavedState$1@2c571a8}, android:focusedViewId=100}]}]
09-14 10:26:32.419  5615  5615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-14 10:26:32.419  5615  5615 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-14 10:26:32.419  5615  5615 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-14 10:26:32.419   384   384 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8da83c00
09-14 10:26:32.420   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-14 10:26:32.420   923   941 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-14 10:26:32.426   923  2761 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
09-14 10:26:32.428   923  2761 I hubconnection: sensorhub said: 'activate 7 enable:0'
,09-14 10:26:32.503   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2186649, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:26:32.704  5615  5672 I jxcore-log: # setup
09-14 10:26:32.704  5615  5672 I jxcore-log: 
,09-14 10:26:32.714   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-14 10:26:32.715   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-14 10:26:32.724   923  3072 D SurfaceControl: Excessive delay in setPowerMode(): 304ms
,09-14 10:26:32.736   923   943 I DreamManagerService: Entering dreamland.
09-14 10:26:32.736   923   943 I PowerManagerService: Dozing...
09-14 10:26:32.736   923   938 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-14 10:26:32.743  3201  3201 W Binder_4: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[38635]" dev="sockfs" ino=38635 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 10:26:32.743  3201  3201 W Binder_4: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[38635]" dev="sockfs" ino=38635 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:32.747   923  3467 I sensors : batch
09-14 10:26:32.747   923  3467 I sensors : activate
,09-14 10:26:32.751   923   923 I sensors : activate
,09-14 10:26:32.752   511  2984 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-14 10:26:32.752   923  2761 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,09-14 10:26:32.753   923  2761 I hubconnection: sensorhub said: 'activate 21 enable:1'
09-14 10:26:32.754   923  2961 E native  : do suspend true
,09-14 10:26:32.755   923  2761 I hubconnection: sensorhub said: 'activate 31 enable:0'
,09-14 10:26:32.773  3525  4558 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,09-14 10:26:32.773  3525  4558 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-14 10:26:32.773  3525  4558 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-14 10:26:32.773   524  1157 D         : oem-qmi: Connection accepted
09-14 10:26:32.774   524  1157 D         : oem-qmi: Waiting to accept connection
,09-14 10:26:32.779  3525  4558 D         : oem_qmi_lib:output 0
,09-14 10:26:32.779  3525  4558 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-14 10:26:33.721  5615  5672 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-14 10:26:33.721  5615  5672 I jxcore-log: 
,09-14 10:26:34.535  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:34.535  5615  5672 I jxcore-log: 
,09-14 10:26:34.543  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 43938
09-14 10:26:34.543  5615  5672 I jxcore-log: 
,09-14 10:26:34.556  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:34.556  5615  5672 I jxcore-log: 
,09-14 10:26:34.559  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:34.559  5615  5672 I jxcore-log: 
09-14 10:26:34.561  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:34.561  5615  5672 I jxcore-log: 
,09-14 10:26:34.574  5615  5672 I jxcore-log: ok 31 we should not have gotten an error
09-14 10:26:34.574  5615  5672 I jxcore-log: 
,09-14 10:26:34.587  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:34.587  5615  5672 I jxcore-log: 
,09-14 10:26:34.590  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:34.590  5615  5672 I jxcore-log: 
,09-14 10:26:34.600  5615  5672 I jxcore-log: ok 32 Buffers are identical
09-14 10:26:34.600  5615  5672 I jxcore-log: 
,09-14 10:26:34.602  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:34.602  5615  5672 I jxcore-log: 
09-14 10:26:34.604  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:34.604  5615  5672 I jxcore-log: 
,09-14 10:26:34.620  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:34.620  5615  5672 I jxcore-log: 
,09-14 10:26:34.621  5615  5672 I jxcore-log: ok 33 server should be fine
09-14 10:26:34.621  5615  5672 I jxcore-log: 
09-14 10:26:34.621  5615  5672 I jxcore-log: ok 34 server should be open
09-14 10:26:34.621  5615  5672 I jxcore-log: 
09-14 10:26:34.622  5615  5672 I jxcore-log: ok 35 incoming has been removed
09-14 10:26:34.622  5615  5672 I jxcore-log: 
09-14 10:26:34.622  5615  5672 I jxcore-log: ok 36 The mux object should be closed
09-14 10:26:34.622  5615  5672 I jxcore-log: 
,09-14 10:26:34.623  5615  5672 I jxcore-log: ok 37 The mux stream should be closed
09-14 10:26:34.623  5615  5672 I jxcore-log: 
,09-14 10:26:34.630  5615  5672 I jxcore-log: # teardown
09-14 10:26:34.630  5615  5672 I jxcore-log: 
,09-14 10:26:34.662  5615  5672 I jxcore-log: # setup
09-14 10:26:34.662  5615  5672 I jxcore-log: 
,09-14 10:26:34.745  5615  5672 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-14 10:26:34.745  5615  5672 I jxcore-log: 
,09-14 10:26:34.806  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:34.806  5615  5672 I jxcore-log: 
,09-14 10:26:34.810  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 39987
09-14 10:26:34.810  5615  5672 I jxcore-log: 
,09-14 10:26:34.818  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:26:34.818  5615  5672 I jxcore-log: 
,09-14 10:26:34.820  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:26:34.820  5615  5672 I jxcore-log: 
,09-14 10:26:34.822  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:26:34.822  5615  5672 I jxcore-log: 
,09-14 10:26:34.829  5615  5672 I jxcore-log: ok 38 we should not have gotten an error
09-14 10:26:34.829  5615  5672 I jxcore-log: 
,09-14 10:26:34.835  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:26:34.835  5615  5672 I jxcore-log: 
,09-14 10:26:34.838  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:26:34.838  5615  5672 I jxcore-log: 
,09-14 10:26:34.845  5615  5672 I jxcore-log: ok 39 Buffers are identical
09-14 10:26:34.845  5615  5672 I jxcore-log: 
,09-14 10:26:34.850  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-14 10:26:34.850  5615  5672 I jxcore-log: 
,09-14 10:26:34.851  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:26:34.851  5615  5672 I jxcore-log: 
,09-14 10:26:34.853  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:26:34.853  5615  5672 I jxcore-log: 
,09-14 10:26:34.858  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:26:34.858  5615  5672 I jxcore-log: 
,09-14 10:26:34.858  5615  5672 I jxcore-log: ok 40 server should be fine
09-14 10:26:34.858  5615  5672 I jxcore-log: 
09-14 10:26:34.858  5615  5672 I jxcore-log: ok 41 server should be open
09-14 10:26:34.858  5615  5672 I jxcore-log: 
09-14 10:26:34.859  5615  5672 I jxcore-log: ok 42 incoming has been removed
09-14 10:26:34.859  5615  5672 I jxcore-log: 
09-14 10:26:34.859  5615  5672 I jxcore-log: ok 43 The mux object should be closed
09-14 10:26:34.859  5615  5672 I jxcore-log: 
,09-14 10:26:34.859  5615  5672 I jxcore-log: ok 44 The mux stream should be closed
09-14 10:26:34.859  5615  5672 I jxcore-log: 
,09-14 10:26:34.865  5615  5672 I jxcore-log: # teardown
09-14 10:26:34.865  5615  5672 I jxcore-log: 
,09-14 10:26:34.936  5615  5672 I jxcore-log: # setup
09-14 10:26:34.936  5615  5672 I jxcore-log: 
,09-14 10:26:35.045  5615  5672 I jxcore-log: # 12. closeAll can close even when connections open
09-14 10:26:35.045  5615  5672 I jxcore-log: 
,09-14 10:26:35.240  5615  5672 I jxcore-log: ok 45 not possible to connect to the server anymore
09-14 10:26:35.240  5615  5672 I jxcore-log: 
,09-14 10:26:35.247  5615  5672 I jxcore-log: # teardown
09-14 10:26:35.247  5615  5672 I jxcore-log: 
,09-14 10:26:35.348  5615  5672 I jxcore-log: # setup
09-14 10:26:35.348  5615  5672 I jxcore-log: 
,09-14 10:26:35.496  5615  5672 I jxcore-log: # 13. closeAll with promise
09-14 10:26:35.496  5615  5672 I jxcore-log: 
,09-14 10:26:35.681  5615  5672 I jxcore-log: ok 46 not possible to connect to the server anymore
09-14 10:26:35.681  5615  5672 I jxcore-log: 
,09-14 10:26:35.685  5615  5672 I jxcore-log: # teardown
09-14 10:26:35.685  5615  5672 I jxcore-log: 
,09-14 10:26:35.755  5615  5672 I jxcore-log: # setup
09-14 10:26:35.755  5615  5672 I jxcore-log: 
,09-14 10:26:35.838  5615  5672 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
09-14 10:26:35.838  5615  5672 I jxcore-log: 
,09-14 10:26:35.890  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:36.023  5615  5672 I jxcore-log: ok 47 Got the right error
09-14 10:26:36.023  5615  5672 I jxcore-log: 
,09-14 10:26:36.033  5615  5672 I jxcore-log: # teardown
09-14 10:26:36.033  5615  5672 I jxcore-log: 
,09-14 10:26:36.085  5615  5672 I jxcore-log: # setup
09-14 10:26:36.085  5615  5672 I jxcore-log: 
,09-14 10:26:36.184  5615  5672 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-14 10:26:36.184  5615  5672 I jxcore-log: 
,09-14 10:26:36.352  5615  5672 I jxcore-log: # teardown
09-14 10:26:36.352  5615  5672 I jxcore-log: 
,09-14 10:26:36.402  5615  5672 I jxcore-log: # setup
09-14 10:26:36.402  5615  5672 I jxcore-log: 
,09-14 10:26:36.476  5615  5672 I jxcore-log: # 16. onPeerLost calls jxcore
09-14 10:26:36.476  5615  5672 I jxcore-log: 
,09-14 10:26:36.544  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 10:26:36.544  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a2c4c1 added. We now have 3 listener(s)
,09-14 10:26:36.548  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 10:26:36.549  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 10:26:36.549  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 10:26:36.550  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:36.550  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@986c466 added. We now have 4 listener(s)
09-14 10:26:36.550  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 10:26:36.551  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 10:26:36.558  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:36.568  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:36.573  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:36.574  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 10:26:36.574  5615  5672 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-14 10:26:36.574  5615  5672 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-14 10:26:36.579  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:36.584  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:36.891  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:36.902  3115  3115 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-14 10:26:36.986  3115  3115 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,09-14 10:26:37.002  3115  3115 W PathParser: Points are too far apart 4.030360828967057
,09-14 10:26:37.002  3115  3115 W PathParser: Points are too far apart 4.030360538880159
,09-14 10:26:37.892  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:38.534   923  2961 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-14 10:26:38.577  5615  5672 I jxcore-log: onPeerLost
09-14 10:26:38.577  5615  5672 I jxcore-log: 
,09-14 10:26:38.580  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:38.580  5615  5672 I jxcore-log: 
,09-14 10:26:38.594  5615  5672 I jxcore-log: # teardown
09-14 10:26:38.594  5615  5672 I jxcore-log: 
,09-14 10:26:38.607  5615  5672 I jxcore-log: ok 48 check if callback was fired by onPeerLost
09-14 10:26:38.607  5615  5672 I jxcore-log: 
,09-14 10:26:38.607  5615  5672 I jxcore-log: ok 49 check if peerAvailable is false
09-14 10:26:38.607  5615  5672 I jxcore-log: 
,09-14 10:26:38.685  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 10:26:38.685  5615  5672 I jxcore-log: 
,09-14 10:26:38.689  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 10:26:38.689  5615  5672 I jxcore-log: 
,09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:38.700  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:38.704  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:38.706  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 10:26:38.706  5615  5672 I jxcore-log: 
,09-14 10:26:38.708  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 10:26:38.708  5615  5672 I jxcore-log: 
,09-14 10:26:38.711  5615  5672 I jxcore-log: # setup
09-14 10:26:38.711  5615  5672 I jxcore-log: 
,09-14 10:26:38.713  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:38.713  5615  5672 I jxcore-log: 
,09-14 10:26:38.787  5615  5672 I jxcore-log: # 17. onPeerDiscovered calls jxcore
09-14 10:26:38.787  5615  5672 I jxcore-log: 
,09-14 10:26:38.856  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 10:26:38.857  5615  5672 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d40054 added. We now have 4 listener(s)
,09-14 10:26:38.861  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 10:26:38.861  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 10:26:38.861  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 10:26:38.862  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 10:26:38.862  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155ebfd added. We now have 5 listener(s)
,09-14 10:26:38.862  5615  5672 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 10:26:38.863  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 10:26:38.869  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:38.879  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:38.882  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:38.883  5615  5672 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 10:26:38.883  5615  5672 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
09-14 10:26:38.887  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 10:26:38.890  5615  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 10:26:38.893  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:39.894  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:40.885  5615  5672 I jxcore-log: onPeerDiscovered
09-14 10:26:40.885  5615  5672 I jxcore-log: 
,09-14 10:26:40.888  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:40.888  5615  5672 I jxcore-log: 
,09-14 10:26:40.894  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 10:26:40.897  5615  5672 I jxcore-log: # teardown
09-14 10:26:40.897  5615  5672 I jxcore-log: 
,09-14 10:26:40.906  5615  5672 I jxcore-log: ok 50 check if callback was fired by onPeerDiscovered
09-14 10:26:40.906  5615  5672 I jxcore-log: 
,09-14 10:26:40.907  5615  5672 I jxcore-log: ok 51 check if peerAvailable is true
09-14 10:26:40.907  5615  5672 I jxcore-log: 
,09-14 10:26:41.013  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 10:26:41.013  5615  5672 I jxcore-log: 
,09-14 10:26:41.017  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 10:26:41.017  5615  5672 I jxcore-log: 
,09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 10:26:41.027  5615  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 10:26:41.030  5615  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 10:26:41.032  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 10:26:41.032  5615  5672 I jxcore-log: 
,09-14 10:26:41.035  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 10:26:41.035  5615  5672 I jxcore-log: 
,09-14 10:26:41.038  5615  5672 I jxcore-log: # setup
09-14 10:26:41.038  5615  5672 I jxcore-log: 
09-14 10:26:41.040  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 10:26:41.040  5615  5672 I jxcore-log: 
,09-14 10:26:41.115  5615  5672 I jxcore-log: # 18. test defaultDirectory
09-14 10:26:41.115  5615  5672 I jxcore-log: 
,09-14 10:26:41.205  5615  5672 I jxcore-log: ok 52 should be equal
09-14 10:26:41.205  5615  5672 I jxcore-log: 
,09-14 10:26:41.210  5615  5672 I jxcore-log: ok 53 should be equal
09-14 10:26:41.210  5615  5672 I jxcore-log: 
,09-14 10:26:41.224  5615  5672 I jxcore-log: ok 54 should be equal
09-14 10:26:41.224  5615  5672 I jxcore-log: 
,09-14 10:26:41.227  5615  5672 I jxcore-log: # teardown
09-14 10:26:41.227  5615  5672 I jxcore-log: 
,09-14 10:26:41.325  5615  5672 I jxcore-log: # setup
09-14 10:26:41.325  5615  5672 I jxcore-log: 
,09-14 10:26:41.444  5615  5672 I jxcore-log: # 19. test defaultAdapter
09-14 10:26:41.444  5615  5672 I jxcore-log: 
,09-14 10:26:41.528  5615  5672 I jxcore-log: ok 55 should be equal
09-14 10:26:41.528  5615  5672 I jxcore-log: 
,09-14 10:26:41.530  5615  5672 I jxcore-log: ok 56 should be equal
09-14 10:26:41.530  5615  5672 I jxcore-log: 
,09-14 10:26:41.534  5615  5672 I jxcore-log: ok 57 should be equal
09-14 10:26:41.534  5615  5672 I jxcore-log: 
,09-14 10:26:41.535  5615  5672 I jxcore-log: ok 58 should be equal
09-14 10:26:41.535  5615  5672 I jxcore-log: 
,09-14 10:26:41.543  5615  5672 I jxcore-log: ok 59 should be equal
09-14 10:26:41.543  5615  5672 I jxcore-log: 
,09-14 10:26:41.544  5615  5672 I jxcore-log: ok 60 should be equal
09-14 10:26:41.544  5615  5672 I jxcore-log: 
,09-14 10:26:41.718  5615  5672 I jxcore-log: ok 61 should be equal
09-14 10:26:41.718  5615  5672 I jxcore-log: 
,09-14 10:26:41.719  5615  5672 I jxcore-log: ok 62 should be equal
09-14 10:26:41.719  5615  5672 I jxcore-log: 
09-14 10:26:41.720  5615  5672 I jxcore-log: # teardown
09-14 10:26:41.720  5615  5672 I jxcore-log: 
,09-14 10:26:41.858  5615  5672 I jxcore-log: # setup
09-14 10:26:41.858  5615  5672 I jxcore-log: 
,09-14 10:26:41.972  5615  5672 I jxcore-log: # 20. enqueue and run in order
09-14 10:26:41.972  5615  5672 I jxcore-log: 
,09-14 10:26:42.144  5615  5672 I jxcore-log: ok 63 firstPromise setTimeout
09-14 10:26:42.144  5615  5672 I jxcore-log: 
,09-14 10:26:42.146  5615  5672 I jxcore-log: ok 64 firstPromise result
09-14 10:26:42.146  5615  5672 I jxcore-log: 
09-14 10:26:42.147  5615  5672 I jxcore-log: ok 65 firstPromise testValue
09-14 10:26:42.147  5615  5672 I jxcore-log: 
,09-14 10:26:42.250  5615  5672 I jxcore-log: ok 66 secondPromise setTimeout
09-14 10:26:42.250  5615  5672 I jxcore-log: 
,09-14 10:26:42.252  5615  5672 I jxcore-log: ok 67 secondPromise result
09-14 10:26:42.252  5615  5672 I jxcore-log: 
09-14 10:26:42.253  5615  5672 I jxcore-log: ok 68 secondPromise testValue
09-14 10:26:42.253  5615  5672 I jxcore-log: 
,09-14 10:26:42.256  5615  5672 I jxcore-log: ok 69 thirdPromise in promise
09-14 10:26:42.256  5615  5672 I jxcore-log: 
,09-14 10:26:42.259  5615  5672 I jxcore-log: ok 70 thirdPromise result
09-14 10:26:42.259  5615  5672 I jxcore-log: 
,09-14 10:26:42.261  5615  5672 I jxcore-log: ok 71 thirdPromise testValue
09-14 10:26:42.261  5615  5672 I jxcore-log: 
,09-14 10:26:42.268  5615  5672 I jxcore-log: # teardown
09-14 10:26:42.268  5615  5672 I jxcore-log: 
,09-14 10:26:42.325  5615  5672 I jxcore-log: # setup
09-14 10:26:42.325  5615  5672 I jxcore-log: 
,09-14 10:26:42.397  5615  5672 I jxcore-log: # 21. enqueueAtTop and run backwards
09-14 10:26:42.397  5615  5672 I jxcore-log: 
,09-14 10:26:42.474  5615  5672 I jxcore-log: ok 72 thirdPromise - first to run
09-14 10:26:42.474  5615  5672 I jxcore-log: 
,09-14 10:26:42.476  5615  5672 I jxcore-log: ok 73 thirdPromise - in resolve
09-14 10:26:42.476  5615  5672 I jxcore-log: 
,09-14 10:26:42.478  5615  5672 I jxcore-log: ok 74 secondPromise - second to run
09-14 10:26:42.478  5615  5672 I jxcore-log: 
,09-14 10:26:42.480  5615  5672 I jxcore-log: ok 75 secondPromise - in catch
09-14 10:26:42.480  5615  5672 I jxcore-log: 
,09-14 10:26:42.482  5615  5672 I jxcore-log: ok 76 firstPromise - third to run
09-14 10:26:42.482  5615  5672 I jxcore-log: 
,09-14 10:26:42.500  5615  5672 I jxcore-log: ok 77 firstPromise - in then
09-14 10:26:42.500  5615  5672 I jxcore-log: 
,09-14 10:26:42.502  5615  5672 I jxcore-log: ok 78 testing promises
09-14 10:26:42.502  5615  5672 I jxcore-log: 
,09-14 10:26:42.506  5615  5672 I jxcore-log: # teardown
09-14 10:26:42.506  5615  5672 I jxcore-log: 
,09-14 10:26:42.557  5615  5672 I jxcore-log: # setup
09-14 10:26:42.557  5615  5672 I jxcore-log: 
,09-14 10:26:42.647  5615  5672 I jxcore-log: # 22. mix enqueue and enqueueAtTop
09-14 10:26:42.647  5615  5672 I jxcore-log: 
,09-14 10:26:42.724  5615  5672 I jxcore-log: ok 79 fourth
09-14 10:26:42.724  5615  5672 I jxcore-log: 
,09-14 10:26:42.726  5615  5672 I jxcore-log: ok 80 fourth
09-14 10:26:42.726  5615  5672 I jxcore-log: 
09-14 10:26:42.727  5615  5672 I jxcore-log: ok 81 second
09-14 10:26:42.727  5615  5672 I jxcore-log: 
,09-14 10:26:42.730  5615  5672 I jxcore-log: ok 82 secondPromise - in then
09-14 10:26:42.730  5615  5672 I jxcore-log: 
,09-14 10:26:42.835  5615  5672 I jxcore-log: ok 83 first
09-14 10:26:42.835  5615  5672 I jxcore-log: 
,09-14 10:26:42.837  5615  5672 I jxcore-log: ok 84 firstPromise - in catch
09-14 10:26:42.837  5615  5672 I jxcore-log: 
,09-14 10:26:42.839  5615  5672 I jxcore-log: ok 85 third
09-14 10:26:42.839  5615  5672 I jxcore-log: 
,09-14 10:26:42.841  5615  5672 I jxcore-log: ok 86 thirdPromise - in then
09-14 10:26:42.841  5615  5672 I jxcore-log: 
,09-14 10:26:42.843  5615  5672 I jxcore-log: ok 87 testingPromises
09-14 10:26:42.843  5615  5672 I jxcore-log: 
,09-14 10:26:42.850  5615  5672 I jxcore-log: # teardown
09-14 10:26:42.850  5615  5672 I jxcore-log: 
,09-14 10:26:42.915  5615  5672 I jxcore-log: # setup
09-14 10:26:42.915  5615  5672 I jxcore-log: 
,09-14 10:26:42.974  5615  5672 I jxcore-log: # 23. queues handled independently
09-14 10:26:42.974  5615  5672 I jxcore-log: 
,09-14 10:26:43.225  5615  5672 I jxcore-log: ok 88 all short operations completed before the long resolves
09-14 10:26:43.225  5615  5672 I jxcore-log: 
,09-14 10:26:43.235  5615  5672 I jxcore-log: # teardown
09-14 10:26:43.235  5615  5672 I jxcore-log: 
,09-14 10:26:43.294  5615  5672 I jxcore-log: # setup
09-14 10:26:43.294  5615  5672 I jxcore-log: 
,09-14 10:26:43.370  5615  5672 I jxcore-log: # 24. basic
09-14 10:26:43.370  5615  5672 I jxcore-log: 
,09-14 10:26:43.430  5615  5672 I jxcore-log: ok 89 sane
09-14 10:26:43.430  5615  5672 I jxcore-log: 
,09-14 10:26:43.434  5615  5672 I jxcore-log: # teardown
09-14 10:26:43.434  5615  5672 I jxcore-log: 
,09-14 10:26:43.494  5615  5672 I jxcore-log: # setup
09-14 10:26:43.494  5615  5672 I jxcore-log: 
,09-14 10:26:43.558  5615  5672 I jxcore-log: # 25. another
09-14 10:26:43.558  5615  5672 I jxcore-log: 
,09-14 10:26:43.614  5615  5672 I jxcore-log: ok 90 sane
09-14 10:26:43.614  5615  5672 I jxcore-log: 
,09-14 10:26:43.616  5615  5672 I jxcore-log: # teardown
09-14 10:26:43.616  5615  5672 I jxcore-log: 
,09-14 10:26:43.676  5615  5672 I jxcore-log: # setup
09-14 10:26:43.676  5615  5672 I jxcore-log: 
,09-14 10:26:43.752  5615  5672 I jxcore-log: # 26. can pass data in setup
09-14 10:26:43.752  5615  5672 I jxcore-log: 
,09-14 10:26:43.813  5615  5672 I jxcore-log: [{"uuid":"27e9017f-0d32-4a90-9dde-43293e444e2c","data":"custom data"},{"uuid":"d731b19c-561e-459c-896e-9beccd4993d6","data":"custom data"},{"uuid":"6ab1e51c-449c-452f-a343-72a775a79c89","data":"custom data"}]
09-14 10:26:43.813  5615  5672 I jxcore-log: 
,09-14 10:26:43.815  5615  5672 I jxcore-log: ok 91 test participant has uuid
09-14 10:26:43.815  5615  5672 I jxcore-log: 
,09-14 10:26:43.815  5615  5672 I jxcore-log: ok 92 participant data matches
09-14 10:26:43.815  5615  5672 I jxcore-log: 
09-14 10:26:43.816  5615  5672 I jxcore-log: ok 93 test participant has uuid
09-14 10:26:43.816  5615  5672 I jxcore-log: 
09-14 10:26:43.817  5615  5672 I jxcore-log: ok 94 participant data matches
09-14 10:26:43.817  5615  5672 I jxcore-log: 
,09-14 10:26:43.817  5615  5672 I jxcore-log: ok 95 test participant has uuid
09-14 10:26:43.817  5615  5672 I jxcore-log: 
09-14 10:26:43.818  5615  5672 I jxcore-log: ok 96 participant data matches
09-14 10:26:43.818  5615  5672 I jxcore-log: 
09-14 10:26:43.819  5615  5672 I jxcore-log: ok 97 own UUID is found from the participants list
09-14 10:26:43.819  5615  5672 I jxcore-log: 
,09-14 10:26:43.823  5615  5672 I jxcore-log: # teardown
09-14 10:26:43.823  5615  5672 I jxcore-log: 
,09-14 10:26:43.896  5615  5672 I jxcore-log: # setup
09-14 10:26:43.896  5615  5672 I jxcore-log: 
,09-14 10:26:43.966  5615  5672 I jxcore-log: # 27. #startListeningForAdvertisements should fail if start not called
09-14 10:26:43.966  5615  5672 I jxcore-log: 
,09-14 10:26:44.034  5615  5672 I jxcore-log: ok 98 specific error should be returned
09-14 10:26:44.034  5615  5672 I jxcore-log: 
,09-14 10:26:44.038  5615  5672 I jxcore-log: # teardown
09-14 10:26:44.038  5615  5672 I jxcore-log: 
,09-14 10:26:44.103  5615  5672 I jxcore-log: ok 99 error should be null
09-14 10:26:44.103  5615  5672 I jxcore-log: 
,09-14 10:26:44.104  5615  5672 I jxcore-log: ok 100 error should be null
09-14 10:26:44.104  5615  5672 I jxcore-log: 
09-14 10:26:44.107  5615  5672 I jxcore-log: # setup
09-14 10:26:44.107  5615  5672 I jxcore-log: 
,09-14 10:26:44.188  5615  5672 I jxcore-log: # 28. #startUpdateAdvertisingAndListening should fail if start not called
09-14 10:26:44.188  5615  5672 I jxcore-log: 
,09-14 10:26:44.260  5615  5672 I jxcore-log: ok 101 specific error should be returned
09-14 10:26:44.260  5615  5672 I jxcore-log: 
,09-14 10:26:44.263  5615  5672 I jxcore-log: # teardown
09-14 10:26:44.263  5615  5672 I jxcore-log: 
,09-14 10:26:44.331  5615  5672 I jxcore-log: ok 102 error should be null
09-14 10:26:44.331  5615  5672 I jxcore-log: 
,09-14 10:26:44.332  5615  5672 I jxcore-log: ok 103 error should be null
09-14 10:26:44.332  5615  5672 I jxcore-log: 
09-14 10:26:44.335  5615  5672 I jxcore-log: # setup
09-14 10:26:44.335  5615  5672 I jxcore-log: 
,09-14 10:26:44.386  5615  5672 I jxcore-log: # 29. should be able to call #stopListeningForAdvertisements many times
09-14 10:26:44.386  5615  5672 I jxcore-log: 
,09-14 10:26:44.584  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 42170
09-14 10:26:44.584  5615  5672 I jxcore-log: 
,09-14 10:26:44.586  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:44.586  5615  5672 I jxcore-log: 
,09-14 10:26:44.588  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 46894
09-14 10:26:44.588  5615  5672 I jxcore-log: 
,09-14 10:26:44.594  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:44.594  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,09-14 10:26:44.594  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:44.594  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:44.596  5615  5672 I jxcore-log: ok 104 error should be null
09-14 10:26:44.596  5615  5672 I jxcore-log: 
09-14 10:26:44.596  5615  5672 I jxcore-log: ok 105 error should be null
09-14 10:26:44.596  5615  5672 I jxcore-log: 
,09-14 10:26:44.597  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:44.597  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:44.597  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:44.597  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:44.599  5615  5672 I jxcore-log: ok 106 error should be null
09-14 10:26:44.599  5615  5672 I jxcore-log: 
,09-14 10:26:44.599  5615  5672 I jxcore-log: ok 107 error should be null
09-14 10:26:44.599  5615  5672 I jxcore-log: 
,09-14 10:26:44.610  5615  5672 I jxcore-log: # teardown
09-14 10:26:44.610  5615  5672 I jxcore-log: 
,09-14 10:26:45.311  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:45.312  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:26:45.312  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:26:45.312  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:45.317  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:45.317  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:45.318  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-14 10:26:45.318  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:45.326  5615  5672 I jxcore-log: ok 108 error should be null
09-14 10:26:45.326  5615  5672 I jxcore-log: 
,09-14 10:26:45.327  5615  5672 I jxcore-log: ok 109 error should be null
09-14 10:26:45.327  5615  5672 I jxcore-log: 
,09-14 10:26:45.333  5615  5672 I jxcore-log: # setup
09-14 10:26:45.333  5615  5672 I jxcore-log: 
,09-14 10:26:45.895  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:45.903  5615  5672 I jxcore-log: # 30. should be able to call #startListeningForAdvertisements many times
09-14 10:26:45.903  5615  5672 I jxcore-log: 
,09-14 10:26:45.993  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 46102
09-14 10:26:45.993  5615  5672 I jxcore-log: 
,09-14 10:26:45.995  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:45.995  5615  5672 I jxcore-log: 
,09-14 10:26:46.000  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 41070
09-14 10:26:46.000  5615  5672 I jxcore-log: 
,09-14 10:26:46.009  5615  5672 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-14 10:26:46.014  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-14 10:26:46.014  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-14 10:26:46.015  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 10:26:46.015  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:26:46.015  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:26:46.015  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:46.015  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 10:26:46.021  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 10:26:46.021  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 10:26:46.025  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:26:46.026  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:26:46.026  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:26:46.030  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 10:26:46.030  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:26:46.030  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:26:46.031  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:46.034  5936  5946 D BtGatt.GattService: registerClient() - UUID=97721f39-a144-49ab-962f-96b9e938e63b
09-14 10:26:46.034  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=97721f39-a144-49ab-962f-96b9e938e63b, clientIf=5
,09-14 10:26:46.034  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:26:46.035  5936  5972 D BtGatt.GattService: start scan with filters
,09-14 10:26:46.038  5936  5955 D BtGatt.ScanManager: handling starting scan
09-14 10:26:46.039  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 10:26:46.039  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:26:46.039  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:26:46.039  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 10:26:46.041  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 10:26:46.042  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:26:46.042  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:26:46.043  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:46.046  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 10:26:46.046  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:46.047  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:26:46.047  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:46.054  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-14 10:26:46.054  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:46.054  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:26:46.054  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:26:46.065  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:26:46.065  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:46.071  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:26:46.071  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:46.543  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 10:26:46.543  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:46.543  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:46.548  5615  5672 I jxcore-log: ok 110 error should be null
09-14 10:26:46.548  5615  5672 I jxcore-log: 
,09-14 10:26:46.550  5615  5672 I jxcore-log: ok 111 error should be null
09-14 10:26:46.550  5615  5672 I jxcore-log: 
,09-14 10:26:46.558  5615  5672 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-14 10:26:46.564  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,09-14 10:26:46.565  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-14 10:26:46.565  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:46.565  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:26:46.565  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:46.570  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 10:26:46.570  5615  5672 I jxcore-log: 
,09-14 10:26:46.572  5615  5672 I jxcore-log: ok 112 error should be null
09-14 10:26:46.572  5615  5672 I jxcore-log: 
,09-14 10:26:46.573  5615  5672 I jxcore-log: ok 113 error should be null
09-14 10:26:46.573  5615  5672 I jxcore-log: 
09-14 10:26:46.578  5615  5672 I jxcore-log: # teardown
09-14 10:26:46.578  5615  5672 I jxcore-log: 
,09-14 10:26:46.748  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:46.749  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:46.749  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:46.749  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:26:46.750  5615  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 10:26:46.750  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-14 10:26:46.750  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 10:26:46.750  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:26:46.750  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:26:46.750  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:26:46.750  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:26:46.750  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-14 10:26:46.753  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:46.755  5936  5964 D BtGatt.GattService: stopScan() - queue size =1
,09-14 10:26:46.760  5936  5946 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:26:46.761  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:26:46.761  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:46.761  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-14 10:26:46.762  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:26:46.762  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 10:26:46.764  5936  5936 D BtGatt.ScanManager: awakened up at time 2200911
,09-14 10:26:46.772  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 10:26:46.772  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:46.772  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:26:46.773  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:46.773  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:26:46.773  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:26:46.773  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:26:46.774  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 10:26:46.777  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 10:26:46.777  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:46.777  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:46.780  5615  5672 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-14 10:26:46.780  5615  5672 I jxcore-log: 
,09-14 10:26:46.782  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:26:46.782  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:46.782  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:26:46.798  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-14 10:26:46.798  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:46.798  5936  5952 D BtGatt.GattService: current time is 2200945260017
09-14 10:26:46.798  5936  5952 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:26:46.798  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 10:26:46.896  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:47.278  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:26:47.278  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:47.278  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:47.282  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:47.282  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:47.283  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-14 10:26:47.283  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:47.286  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:47.286  5615  5672 I jxcore-log: 
,09-14 10:26:47.298  5615  5672 I jxcore-log: ok 114 error should be null
09-14 10:26:47.298  5615  5672 I jxcore-log: 
,09-14 10:26:47.298  5615  5672 I jxcore-log: ok 115 error should be null
09-14 10:26:47.298  5615  5672 I jxcore-log: 
,09-14 10:26:47.304  5615  5672 I jxcore-log: # setup
09-14 10:26:47.304  5615  5672 I jxcore-log: 
,09-14 10:26:47.373  5615  5672 I jxcore-log: # 31. should be able to call #startUpdateAdvertisingAndListening many times
09-14 10:26:47.373  5615  5672 I jxcore-log: 
,09-14 10:26:47.456  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 41352
09-14 10:26:47.456  5615  5672 I jxcore-log: 
,09-14 10:26:47.459  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:47.459  5615  5672 I jxcore-log: 
,09-14 10:26:47.463  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 37054
09-14 10:26:47.463  5615  5672 I jxcore-log: 
,09-14 10:26:47.480  5615  5672 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-14 10:26:47.484  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 37054, start advertisements: true
09-14 10:26:47.484  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-14 10:26:47.484  5615  5672 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-14 10:26:47.485  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-14 10:26:47.485  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:47.485  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 10:26:47.485  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 10:26:47.485  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:47.486  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-14 10:26:47.487  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-14 10:26:47.487  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 10:26:47.487  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-14 10:26:47.487  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 10:26:47.487  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:47.487  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 10:26:47.489  5615  6062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:26:47.489  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-14 10:26:47.492  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:26:47.486  5947  5947 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[39000]" dev="sockfs" ino=39000 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:47.486  5947  5947 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[39000]" dev="sockfs" ino=39000 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:26:47.492  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:26:47.493  5615  6062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-14 10:26:47.498  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:26:47.499  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:26:47.499  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:26:47.502  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-14 10:26:47.502  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:47.503  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-14 10:26:47.503  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:47.503  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:47.503  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-14 10:26:47.505  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:47.509  5936  5973 D BtGatt.GattService: registerClient() - UUID=c4c8bcd4-0a14-491d-b9e0-0c3f5c5b24ef
,09-14 10:26:47.509  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=c4c8bcd4-0a14-491d-b9e0-0c3f5c5b24ef, clientIf=5
,09-14 10:26:47.510  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-14 10:26:47.511  5936  5954 D BtGatt.AdvertiseManager: message : 0
,09-14 10:26:47.513  5936  5954 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 10:26:47.523  5936  5952 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 10:26:47.528  5936  5952 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 10:26:47.529  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-14 10:26:47.529  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 10:26:47.530  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:47.531  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:47.532  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:47.532  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 10:26:47.532  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 10:26:47.532  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 10:26:47.532  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 10:26:47.532  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-14 10:26:47.533  5615  5672 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 43755
09-14 10:26:47.533  5615  5672 I jxcore-log: 
09-14 10:26:47.535  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-14 10:26:47.535  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 10:26:47.897  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:48.036  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-14 10:26:48.036  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-14 10:26:48.036  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:48.048  5615  5672 I jxcore-log: ok 116 error should be null
09-14 10:26:48.048  5615  5672 I jxcore-log: 
,09-14 10:26:48.050  5615  5672 I jxcore-log: ok 117 error should be null
09-14 10:26:48.050  5615  5672 I jxcore-log: 
,09-14 10:26:48.061  5615  5672 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-14 10:26:48.068  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 37054, start advertisements: true
,09-14 10:26:48.068  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-14 10:26:48.068  5615  5672 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-14 10:26:48.068  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-14 10:26:48.069  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-14 10:26:48.071  5936  5954 D BtGatt.AdvertiseManager: message : 1
,09-14 10:26:48.073  5936  5954 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 10:26:48.087  5936  5952 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-14 10:26:48.087  5936  5952 D BtGatt.GattService: Client app is not null!
09-14 10:26:48.088  5936  5964 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:26:48.089  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:26:48.089  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-14 10:26:48.089  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:26:48.089  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 10:26:48.089  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 10:26:48.090  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-14 10:26:48.090  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:48.090  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:48.090  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-14 10:26:48.092  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:48.098  5936  5947 D BtGatt.GattService: registerClient() - UUID=d3a9d942-7cbc-45b3-ac8a-71b840e5310a
09-14 10:26:48.098  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=d3a9d942-7cbc-45b3-ac8a-71b840e5310a, clientIf=5
,09-14 10:26:48.099  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-14 10:26:48.101  5936  5954 D BtGatt.AdvertiseManager: message : 0
,09-14 10:26:48.107  5936  5954 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 10:26:48.123  5936  5952 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 10:26:48.132  5936  5952 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 10:26:48.132  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 10:26:48.133  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-14 10:26:48.133  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 10:26:48.133  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 10:26:48.133  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 10:26:48.133  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:26:48.133  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 10:26:48.133  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:26:48.133  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:48.145  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 10:26:48.145  5615  5672 I jxcore-log: 
,09-14 10:26:48.146  5615  5672 I jxcore-log: ok 118 error should be null
09-14 10:26:48.146  5615  5672 I jxcore-log: 
,09-14 10:26:48.148  5615  5672 I jxcore-log: ok 119 error should be null
09-14 10:26:48.148  5615  5672 I jxcore-log: 
,09-14 10:26:48.153  5615  5672 I jxcore-log: # teardown
09-14 10:26:48.153  5615  5672 I jxcore-log: 
,09-14 10:26:48.567  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
09-14 10:26:48.567  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:26:48.567  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-14 10:26:48.567  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:26:48.568  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 10:26:48.568  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 10:26:48.568  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 10:26:48.568  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-14 10:26:48.568  5615  6062 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-14 10:26:48.569  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 10:26:48.569  5615  6062 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 10:26:48.569  5615  6062 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 10:26:48.569  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:26:48.569  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:26:48.569  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-14 10:26:48.569  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 10:26:48.569  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:26:48.570  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:26:48.572  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:48.575  5615  5672 D BluetoothLeScanner: could not find callback wrapper
09-14 10:26:48.575  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:26:48.575  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-14 10:26:48.578  5936  5954 D BtGatt.AdvertiseManager: message : 1
,09-14 10:26:48.579  5936  5954 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 10:26:48.589  5936  5952 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-14 10:26:48.589  5936  5952 D BtGatt.GattService: Client app is not null!
,09-14 10:26:48.593  5936  5964 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:26:48.594  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 10:26:48.594  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:48.594  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-14 10:26:48.594  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 10:26:48.594  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-14 10:26:48.596  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:48.596  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:26:48.596  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:26:48.597  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 10:26:48.599  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 10:26:48.600  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 10:26:48.600  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 10:26:48.600  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:48.600  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:48.600  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:48.602  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:48.602  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:48.602  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:48.602  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:48.607  5615  5672 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-14 10:26:48.607  5615  5672 I jxcore-log: 
,09-14 10:26:48.612  5615  5672 I jxcore-log: ok 120 error should be null
09-14 10:26:48.612  5615  5672 I jxcore-log: 
,09-14 10:26:48.613  5615  5672 I jxcore-log: ok 121 error should be null
09-14 10:26:48.613  5615  5672 I jxcore-log: 
,09-14 10:26:48.617  5615  5672 I jxcore-log: # setup
09-14 10:26:48.617  5615  5672 I jxcore-log: 
,09-14 10:26:48.646  5615  5672 I jxcore-log: # 32. should be able to call #stopAdvertisingAndListening many times
09-14 10:26:48.646  5615  5672 I jxcore-log: 
,09-14 10:26:48.750  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 42615
09-14 10:26:48.750  5615  5672 I jxcore-log: 
,09-14 10:26:48.754  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:48.754  5615  5672 I jxcore-log: 
,09-14 10:26:48.758  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 39809
09-14 10:26:48.758  5615  5672 I jxcore-log: 
,09-14 10:26:48.764  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:48.764  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:48.765  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:48.765  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:48.768  5615  5672 I jxcore-log: ok 122 error should be null
09-14 10:26:48.768  5615  5672 I jxcore-log: 
,09-14 10:26:48.769  5615  5672 I jxcore-log: ok 123 error should be null
09-14 10:26:48.769  5615  5672 I jxcore-log: 
,09-14 10:26:48.773  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:48.773  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:48.773  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:48.773  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:48.776  5615  5672 I jxcore-log: ok 124 error should be null
09-14 10:26:48.776  5615  5672 I jxcore-log: 
,09-14 10:26:48.777  5615  5672 I jxcore-log: ok 125 error should be null
09-14 10:26:48.777  5615  5672 I jxcore-log: 
,09-14 10:26:48.782  5615  5672 I jxcore-log: # teardown
09-14 10:26:48.782  5615  5672 I jxcore-log: 
,09-14 10:26:48.827  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:48.827  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:48.827  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:48.827  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:48.828  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:48.829  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:48.829  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:48.829  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:48.834  5615  5672 I jxcore-log: ok 126 error should be null
09-14 10:26:48.834  5615  5672 I jxcore-log: 
,09-14 10:26:48.835  5615  5672 I jxcore-log: ok 127 error should be null
09-14 10:26:48.835  5615  5672 I jxcore-log: 
,09-14 10:26:48.841  5615  5672 I jxcore-log: # setup
09-14 10:26:48.841  5615  5672 I jxcore-log: 
,09-14 10:26:48.898  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:26:48.941  5615  5672 I jxcore-log: # 33. #start should fail if called twice in a row
09-14 10:26:48.941  5615  5672 I jxcore-log: 
,09-14 10:26:49.031  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 48056
09-14 10:26:49.031  5615  5672 I jxcore-log: 
,09-14 10:26:49.032  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:49.032  5615  5672 I jxcore-log: 
,09-14 10:26:49.037  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 42432
09-14 10:26:49.037  5615  5672 I jxcore-log: 
,09-14 10:26:49.041  5615  5672 I jxcore-log: ok 128 first call should succeed
09-14 10:26:49.041  5615  5672 I jxcore-log: 
,09-14 10:26:49.042  5615  5672 I jxcore-log: ok 129 first call should succeed
09-14 10:26:49.042  5615  5672 I jxcore-log: 
,09-14 10:26:49.046  5615  5672 I jxcore-log: ok 130 specific error should be returned
09-14 10:26:49.046  5615  5672 I jxcore-log: 
,09-14 10:26:49.049  5615  5672 I jxcore-log: # teardown
09-14 10:26:49.049  5615  5672 I jxcore-log: 
,09-14 10:26:49.100  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:26:49.102  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:49.102  5615  5672 I jxcore-log: 
,09-14 10:26:49.116  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:49.116  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:26:49.117  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:49.117  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:49.121  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:49.121  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:49.121  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:49.121  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:26:49.128  5615  5672 I jxcore-log: ok 131 error should be null
09-14 10:26:49.128  5615  5672 I jxcore-log: 
,09-14 10:26:49.128  5615  5672 I jxcore-log: ok 132 error should be null
09-14 10:26:49.128  5615  5672 I jxcore-log: 
,09-14 10:26:49.136  5615  5672 I jxcore-log: # setup
09-14 10:26:49.136  5615  5672 I jxcore-log: 
,09-14 10:26:49.194  5615  5672 I jxcore-log: # 34. does not emit duplicate discoveryAdvertisingStateUpdate
09-14 10:26:49.194  5615  5672 I jxcore-log: 
,09-14 10:26:49.302  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 46997
09-14 10:26:49.302  5615  5672 I jxcore-log: 
,09-14 10:26:49.305  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:49.305  5615  5672 I jxcore-log: 
,09-14 10:26:49.310  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 38468
09-14 10:26:49.310  5615  5672 I jxcore-log: 
,09-14 10:26:49.316  5615  5672 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-14 10:26:49.320  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 37054, start advertisements: false
09-14 10:26:49.320  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-14 10:26:49.320  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:49.320  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:26:49.320  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:26:49.320  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:49.321  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 10:26:49.325  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 10:26:49.325  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 10:26:49.330  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 10:26:49.331  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:26:49.331  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:26:49.335  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 10:26:49.335  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:26:49.335  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-14 10:26:49.336  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:49.340  5936  5964 D BtGatt.GattService: registerClient() - UUID=d8a0622c-71f8-445d-b082-3f825bdf8a2e
,09-14 10:26:49.340  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=d8a0622c-71f8-445d-b082-3f825bdf8a2e, clientIf=5
,09-14 10:26:49.341  5615  6055 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 10:26:49.341  5936  5947 D BtGatt.GattService: start scan with filters
,09-14 10:26:49.344  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:26:49.344  5936  5955 D BtGatt.ScanManager: handling starting scan
09-14 10:26:49.344  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:26:49.344  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:26:49.344  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 10:26:49.347  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 10:26:49.347  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:26:49.347  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:26:49.348  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:49.351  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:26:49.351  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.351  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:26:49.352  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:49.358  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:26:49.358  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.358  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:26:49.358  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:26:49.370  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:26:49.370  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.375  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 10:26:49.375  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.848  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 10:26:49.848  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:49.849  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:49.855  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 10:26:49.855  5615  5672 I jxcore-log: 
,09-14 10:26:49.875  5615  5672 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-14 10:26:49.881  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 38468, start advertisements: true
,09-14 10:26:49.881  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-14 10:26:49.881  5615  5672 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-14 10:26:49.882  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:26:49.882  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 10:26:49.888  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:49.896  5936  5972 D BtGatt.GattService: stopScan() - queue size =1
,09-14 10:26:49.898  5936  5946 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:26:49.899  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 10:26:49.899  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:49.899  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:26:49.899  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:26:49.899  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:26:49.899  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
09-14 10:26:49.899  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-14 10:26:49.901  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:49.903  5936  5936 D BtGatt.ScanManager: awakened up at time 2204050
09-14 10:26:49.906  5936  5964 D BtGatt.GattService: registerClient() - UUID=5b5f92f1-abd1-475e-9496-eb64f7d067ed
,09-14 10:26:49.906  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=5b5f92f1-abd1-475e-9496-eb64f7d067ed, clientIf=5
09-14 10:26:49.907  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 10:26:49.908  5936  5972 D BtGatt.GattService: start scan with filters
09-14 10:26:49.909  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:26:49.909  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.909  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
,09-14 10:26:49.914  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:26:49.914  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 10:26:49.914  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:49.914  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 10:26:49.914  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 10:26:49.914  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 10:26:49.916  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 10:26:49.917  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 10:26:49.917  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 10:26:49.917  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-14 10:26:49.917  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 10:26:49.917  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 10:26:49.917  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:26:49.917  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 10:26:49.918  5615  6063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:26:49.918  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:49.919  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:26:49.919  5936  5972 D BtGatt.GattService: stopScan() - queue size =0
09-14 10:26:49.919  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:49.920  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 10:26:49.921  5936  5973 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:26:49.921  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:26:49.921  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:49.921  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-14 10:26:49.921  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:26:49.922  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 10:26:49.916  5964  5964 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[32619]" dev="sockfs" ino=32619 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:49.916  5964  5964 W Binder_3: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[32619]" dev="sockfs" ino=32619 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:26:49.922  5615  6063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 10:26:49.924  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:49.926  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 10:26:49.930  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 10:26:49.931  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:49.931  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-14 10:26:49.931  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:49.932  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:49.932  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-14 10:26:49.933  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:49.937  5936  5947 D BtGatt.GattService: registerClient() - UUID=ead7076d-963e-4747-8c58-09fcc5a73118
,09-14 10:26:49.937  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
09-14 10:26:49.937  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:49.938  5936  5952 D BtGatt.GattService: current time is 2204084850590
,09-14 10:26:49.938  5936  5952 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
09-14 10:26:49.938  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-14 10:26:49.938  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-14 10:26:49.938  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=ead7076d-963e-4747-8c58-09fcc5a73118, clientIf=5
09-14 10:26:49.939  5615  5626 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 10:26:49.940  5936  5954 D BtGatt.AdvertiseManager: message : 0
,09-14 10:26:49.940  5936  5955 D BtGatt.ScanManager: handling starting scan
,09-14 10:26:49.946  5936  5954 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 10:26:49.947  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 10:26:49.948  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:49.948  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:26:49.960  5936  5952 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 10:26:49.966  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:26:49.966  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.967  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:26:49.967  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:26:49.974  5936  5952 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-14 10:26:49.975  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-14 10:26:49.975  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 10:26:49.977  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:49.978  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
09-14 10:26:49.978  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:49.978  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:49.978  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 10:26:49.978  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 10:26:49.978  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 10:26:49.978  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 10:26:49.978  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-14 10:26:49.980  5615  5672 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 37454
09-14 10:26:49.980  5615  5672 I jxcore-log: 
09-14 10:26:49.982  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-14 10:26:49.982  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 10:26:49.989  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:26:49.989  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:49.996  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 10:26:49.996  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:50.003  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 10:26:50.003  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:50.003  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
,09-14 10:26:50.009  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 10:26:50.009  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:50.009  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:26:50.015  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:26:50.015  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:50.483  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-14 10:26:50.483  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 10:26:50.483  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:50.492  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 10:26:50.492  5615  5672 I jxcore-log: 
,09-14 10:26:50.506  5615  5672 I jxcore-log: ok 133 called only once
09-14 10:26:50.506  5615  5672 I jxcore-log: 
,09-14 10:26:50.508  5615  5672 I jxcore-log: ok 134 discovery state matches
09-14 10:26:50.508  5615  5672 I jxcore-log: 
,09-14 10:26:50.508  5615  5672 I jxcore-log: ok 135 advertising state matches
09-14 10:26:50.508  5615  5672 I jxcore-log: 
,09-14 10:26:50.519  5615  5672 I jxcore-log: # teardown
09-14 10:26:50.519  5615  5672 I jxcore-log: 
,09-14 10:26:50.900  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 10:26:50.921  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:26:50.921  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 10:26:50.921  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-14 10:26:50.921  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:26:50.921  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-14 10:26:50.922  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 10:26:50.922  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-14 10:26:50.922  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-14 10:26:50.922  5615  6063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 10:26:50.922  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 10:26:50.922  5615  6063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-14 10:26:50.923  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:26:50.923  5615  6063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 10:26:50.923  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 10:26:50.923  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 10:26:50.923  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-14 10:26:50.923  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 10:26:50.923  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 10:26:50.925  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:50.926  5615  5672 D BluetoothLeScanner: could not find callback wrapper
09-14 10:26:50.926  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 10:26:50.926  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-14 10:26:50.928  5936  5954 D BtGatt.AdvertiseManager: message : 1
09-14 10:26:50.929  5936  5954 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 10:26:50.943  5936  5952 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-14 10:26:50.943  5936  5952 D BtGatt.GattService: Client app is not null!
09-14 10:26:50.945  5936  5964 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:26:50.945  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 10:26:50.946  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:50.946  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 10:26:50.946  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 10:26:50.946  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-14 10:26:50.949  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:26:50.949  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 10:26:50.949  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 10:26:50.951  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-14 10:26:50.954  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:26:50.954  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 10:26:50.954  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 10:26:50.955  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:50.955  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 10:26:50.955  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:50.956  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:26:50.956  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:26:50.956  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:26:50.956  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 10:26:50.961  5615  5672 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
09-14 10:26:50.961  5615  5672 I jxcore-log: 
09-14 10:26:50.962  5615  5672 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-14 10:26:50.962  5615  5672 I jxcore-log: 
,09-14 10:26:50.964  5615  5672 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-14 10:26:50.964  5615  5672 I jxcore-log: 
,09-14 10:26:50.969  5615  5672 I jxcore-log: ok 136 error should be null
09-14 10:26:50.969  5615  5672 I jxcore-log: 
,09-14 10:26:50.969  5615  5672 I jxcore-log: ok 137 error should be null
09-14 10:26:50.969  5615  5672 I jxcore-log: 
,09-14 10:26:50.975  5615  5672 I jxcore-log: # setup
09-14 10:26:50.975  5615  5672 I jxcore-log: 
,09-14 10:26:51.009  5615  5672 I jxcore-log: # 35. does not send duplicate availability changes
09-14 10:26:51.009  5615  5672 I jxcore-log: 
,09-14 10:26:51.100  5615  5672 I jxcore-log: ok 138 should be called once
09-14 10:26:51.100  5615  5672 I jxcore-log: 
,09-14 10:26:51.103  5615  5672 I jxcore-log: ok 139 should not have been called more than once
09-14 10:26:51.103  5615  5672 I jxcore-log: 
,09-14 10:26:51.107  5615  5672 I jxcore-log: # teardown
09-14 10:26:51.107  5615  5672 I jxcore-log: 
,09-14 10:26:51.182  5615  5672 I jxcore-log: ok 140 error should be null
09-14 10:26:51.182  5615  5672 I jxcore-log: 
,09-14 10:26:51.183  5615  5672 I jxcore-log: ok 141 error should be null
09-14 10:26:51.183  5615  5672 I jxcore-log: 
09-14 10:26:51.186  5615  5672 I jxcore-log: # setup
09-14 10:26:51.186  5615  5672 I jxcore-log: 
,09-14 10:26:51.264  5615  5672 I jxcore-log: # 36. can get the network status
09-14 10:26:51.264  5615  5672 I jxcore-log: 
,09-14 10:26:51.386  5615  5672 I jxcore-log: ok 142 network status should have certain non-empty properties
09-14 10:26:51.386  5615  5672 I jxcore-log: 
,09-14 10:26:51.389  5615  5672 I jxcore-log: # teardown
09-14 10:26:51.389  5615  5672 I jxcore-log: 
,09-14 10:26:51.422  5615  5672 I jxcore-log: ok 143 error should be null
09-14 10:26:51.422  5615  5672 I jxcore-log: 
,09-14 10:26:51.423  5615  5672 I jxcore-log: ok 144 error should be null
09-14 10:26:51.423  5615  5672 I jxcore-log: 
,09-14 10:26:51.425  5615  5672 I jxcore-log: # setup
09-14 10:26:51.425  5615  5672 I jxcore-log: 
,09-14 10:26:51.456  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:26:51.458  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:26:51.458  5615  5672 I jxcore-log: 
,09-14 10:26:51.507  5615  5672 I jxcore-log: # 37. wifi peer is marked unavailable if announcements stop
09-14 10:26:51.507  5615  5672 I jxcore-log: 
,09-14 10:26:51.597  5615  5672 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
09-14 10:26:51.597  5615  5672 I jxcore-log: 
,09-14 10:26:51.627  5615  5672 I jxcore-log: ok 145 host address should match
09-14 10:26:51.627  5615  5672 I jxcore-log: 
,09-14 10:26:51.628  5615  5672 I jxcore-log: ok 146 port should match
09-14 10:26:51.628  5615  5672 I jxcore-log: 
,09-14 10:26:53.596  5615  5672 I jxcore-log: ok 147 host address should be null
09-14 10:26:53.596  5615  5672 I jxcore-log: 
,09-14 10:26:53.598  5615  5672 I jxcore-log: ok 148 port should should be null
09-14 10:26:53.598  5615  5672 I jxcore-log: 
,09-14 10:26:53.612  5615  5672 I jxcore-log: # teardown
09-14 10:26:53.612  5615  5672 I jxcore-log: 
,09-14 10:26:53.661  5615  5672 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
09-14 10:26:53.661  5615  5672 I jxcore-log: 
,09-14 10:26:53.665  5615  5672 I jxcore-log: ok 149 error should be null
09-14 10:26:53.665  5615  5672 I jxcore-log: 
,09-14 10:26:53.666  5615  5672 I jxcore-log: ok 150 error should be null
09-14 10:26:53.666  5615  5672 I jxcore-log: 
,09-14 10:26:53.669  5615  5672 I jxcore-log: # setup
09-14 10:26:53.669  5615  5672 I jxcore-log: 
,09-14 10:26:53.802  5615  5672 I jxcore-log: # 38. Client to server request coordinated
09-14 10:26:53.802  5615  5672 I jxcore-log: 
,09-14 10:26:53.855  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: listening 39443
09-14 10:26:53.855  5615  5672 I jxcore-log: 
,09-14 10:26:53.856  5615  5672 I jxcore-log: DEBUG createNativeListener: creating native server
09-14 10:26:53.856  5615  5672 I jxcore-log: 
,09-14 10:26:53.859  5615  5672 I jxcore-log: DEBUG createNativeListener: listening 39885
09-14 10:26:53.859  5615  5672 I jxcore-log: 
,09-14 10:26:53.861  5615  5672 I jxcore-log: ok 151 error should be null
09-14 10:26:53.861  5615  5672 I jxcore-log: 
,09-14 10:26:53.862  5615  5672 I jxcore-log: ok 152 error should be null
09-14 10:26:53.862  5615  5672 I jxcore-log: 
,09-14 10:26:53.925  5615  5672 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,09-14 10:26:53.928  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 39885, start advertisements: true
,09-14 10:26:53.928  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-14 10:26:53.928  5615  5672 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-14 10:26:53.928  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-14 10:26:53.929  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:53.929  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-14 10:26:53.929  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-14 10:26:53.929  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:53.930  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 10:26:53.930  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-14 10:26:53.930  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 10:26:53.931  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 10:26:53.931  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-14 10:26:53.931  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 10:26:53.931  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 10:26:53.931  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 10:26:53.933  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 10:26:53.933  5615  5672 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 10:26:53.935  5615  6064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 10:26:53.936  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:26:53.936  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:26:53.936  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:26:53.938  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-14 10:26:53.933  5946  5946 W Binder_1: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[35213]" dev="sockfs" ino=35213 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:53.938  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 10:26:53.938  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
,09-14 10:26:53.938  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:53.939  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-14 10:26:53.939  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-14 10:26:53.939  5615  5672 D BluetoothAdapter: STATE_ON
09-14 10:26:53.940  5615  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-14 10:26:53.933  5946  5946 W Binder_1: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[35213]" dev="sockfs" ino=35213 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:53.941  5936  5947 D BtGatt.GattService: registerClient() - UUID=bdd100a4-1d50-446f-8530-bf4bcbda7b66
09-14 10:26:53.942  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=bdd100a4-1d50-446f-8530-bf4bcbda7b66, clientIf=5
09-14 10:26:53.944  5615  6055 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-14 10:26:53.946  5936  5954 D BtGatt.AdvertiseManager: message : 0
,09-14 10:26:53.952  5936  5954 D BtGatt.AdvertiseManager: starting multi advertising
,09-14 10:26:53.968  5936  5952 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-14 10:26:53.975  5936  5952 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-14 10:26:53.976  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-14 10:26:53.976  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 10:26:53.978  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:53.979  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:53.979  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-14 10:26:53.980  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-14 10:26:53.980  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-14 10:26:53.980  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-14 10:26:53.980  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-14 10:26:53.980  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-14 10:26:53.983  5615  5672 I jxcore-log: DEBUG thaliWifiInfrastructure: listening 47791
09-14 10:26:53.983  5615  5672 I jxcore-log: 
,09-14 10:26:53.984  5615  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-14 10:26:53.984  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-14 10:26:54.485  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-14 10:26:54.486  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-14 10:26:54.486  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:26:54.490  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-14 10:26:54.490  5615  5672 I jxcore-log: 
,09-14 10:26:54.501  5615  5672 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,09-14 10:26:54.508  5615  5672 I io.jxcore.node.ConnectionHelper: start: Port number: 39885, start advertisements: false
,09-14 10:26:54.509  5615  5672 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-14 10:26:54.509  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
09-14 10:26:54.509  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 10:26:54.509  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 10:26:54.510  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 10:26:54.510  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-14 10:26:54.511  5936  5954 D BtGatt.AdvertiseManager: message : 1
09-14 10:26:54.512  5936  5954 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-14 10:26:54.528  5936  5952 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-14 10:26:54.528  5936  5952 D BtGatt.GattService: Client app is not null!
,09-14 10:26:54.530  5936  5973 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:26:54.532  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 10:26:54.532  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-14 10:26:54.532  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-14 10:26:54.532  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-14 10:26:54.533  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-14 10:26:54.535  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:54.536  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:26:54.539  5615  5672 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 10:26:54.548  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:26:54.548  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:26:54.549  5615  5672 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-14 10:26:54.550  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:26:54.554  5936  5964 D BtGatt.GattService: registerClient() - UUID=5279ee8e-bafb-404f-942d-88e9f04707b2
,09-14 10:26:54.555  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=5279ee8e-bafb-404f-942d-88e9f04707b2, clientIf=5
,09-14 10:26:54.555  5615  6055 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:26:54.556  5936  5946 D BtGatt.GattService: start scan with filters
09-14 10:26:54.562  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:26:54.562  5936  5955 D BtGatt.ScanManager: handling starting scan
09-14 10:26:54.562  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 10:26:54.562  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 10:26:54.562  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 10:26:54.567  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 10:26:54.567  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 10:26:54.567  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 10:26:54.570  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 10:26:54.573  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 10:26:54.574  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:54.574  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 10:26:54.574  5615  5672 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 10:26:54.585  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-14 10:26:54.585  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:54.585  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:26:54.585  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:26:54.599  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:26:54.599  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:54.606  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 10:26:54.606  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:26:55.068  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-14 10:26:55.069  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 10:26:55.069  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 10:26:55.073  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-14 10:26:55.073  5615  5672 I jxcore-log: 
,09-14 10:26:55.077  5615  5672 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
09-14 10:26:55.077  5615  5672 I jxcore-log: 
,09-14 10:26:59.610  5936  5936 D BtGatt.ScanManager: awakened up at time 2213757
,09-14 10:26:59.612  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:26:59.646  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-14 10:26:59.646  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:26:59.646  5936  5952 D BtGatt.GattService: current time is 2213793765307
09-14 10:26:59.647  5936  5952 D BtGatt.GattService: Batch record : [-98, 63, -124, -112, -86, 69, 1, -128, -70, 99, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 116, -43, -111, -91, -20, -29, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -74, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -77, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -77, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -76, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-14 10:26:59.647  5936  5952 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
09-14 10:26:59.648  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:26:59.648  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-14 10:26:59.648  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-14 10:26:59.648  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-14 10:26:59.649  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-14 10:26:59.649  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-14 10:26:59.654  5615  5615 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 44:78:3E:94:4A:3E 5], added - the peer count is 1
09-14 10:26:59.655  5615  5615 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 5], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
,09-14 10:26:59.660  5615  5672 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-14 10:26:59.660  5615  5672 I jxcore-log: 
,09-14 10:26:59.664  5615  5672 I jxcore-log: DEBUG createPeerListener: listening 49130
09-14 10:26:59.664  5615  5672 I jxcore-log: 
,09-14 10:26:59.665  5615  5672 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-14 10:26:59.665  5615  5672 I jxcore-log: 
,09-14 10:26:59.690  5615  5672 I jxcore-log: DEBUG createPeerListener: first connection
09-14 10:26:59.690  5615  5672 I jxcore-log: 
,09-14 10:26:59.694  5615  5672 D io.jxcore.node.JXcoreExtension: connect: 44:78:3E:94:4A:3E
,09-14 10:26:59.694  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 44:78:3E:94:4A:3E
09-14 10:26:59.694  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 44:78:3E:94:4A:3E 5]
09-14 10:26:59.696  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 44:78:3E:94:4A:3E
09-14 10:26:59.696  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-14 10:26:59.696  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-14 10:26:59.697  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 44:78:3E:94:4A:3E
,09-14 10:26:59.697  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 44:78:3E:94:4A:3E
09-14 10:26:59.697  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 44:78:3E:94:4A:3E)
09-14 10:26:59.698  5615  6065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 44:78:3E:94:4A:3E (thread ID: 197)
,09-14 10:26:59.699  5615  6065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:26:59.696  5964  5964 W Binder_3: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[32645]" dev="sockfs" ino=32645 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:26:59.696  5964  5964 W Binder_3: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[32645]" dev="sockfs" ino=32645 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:27:00.123  5936  5959 W bt_btif : bta_dm_acl_change info: 0x10
,09-14 10:27:00.123  5936  5952 D bt_btif_dm: remote version info [44:78:3e:94:4a:3e]: 8, f, 6106
09-14 10:27:00.124  5936  5952 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,09-14 10:27:00.154  5936  5936 D BtGatt.ScanManager: awakened up at time 2214301
09-14 10:27:00.156  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:00.160  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:27:00.160  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:00.172  5936  5959 W bt_sdp  : process_service_search_attr_rsp
,09-14 10:27:00.535  5936  5952 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 1
09-14 10:27:00.536  5936  5952 I bt_btif_dm: check_cod remote_cod = 0x00001f00 cod = 0x00000580
,09-14 10:27:00.541  5936  5953 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 10 NewState: 11
09-14 10:27:00.542  5936  5953 I BluetoothBondStateMachine: Entering PendingCommandState State
09-14 10:27:00.543  3115  3361 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-14 10:27:00.545  5720  5720 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-14 10:27:00.546  3115  3361 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-14 10:27:00.549  5720  5720 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-14 10:27:00.664  5936  5936 D BtGatt.ScanManager: awakened up at time 2214811
,09-14 10:27:00.668  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:00.672  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:27:00.672  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:00.703  5936  5952 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 0
,09-14 10:27:00.703  5936  5953 D BluetoothAdapterProperties: Failed to remove device: 44:78:3E:94:4A:3E
,09-14 10:27:00.705  5936  5953 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 11 NewState: 10
,09-14 10:27:00.707  3115  3361 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
,09-14 10:27:00.709  5720  5720 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
,09-14 10:27:00.711  3115  3361 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-14 10:27:00.717  5720  5720 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-14 10:27:00.745  5936  5953 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@9416350
,09-14 10:27:00.750  5936  5953 D HidService: Saved priority 44:78:3E:94:4A:3E = -1
,09-14 10:27:00.753  5936  5959 W bt_smp  : for SMP over BR max_key_size: 0x10,                        local_i_key: 0x07, local_r_key: 0x07
,09-14 10:27:00.758  5936  5953 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 10:27:00.767  5936  5952 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 1
,09-14 10:27:00.769  5936  5959 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
09-14 10:27:00.769  5936  5959 W bt_smp  : flag = 0 round = 1
09-14 10:27:00.769  5936  5959 W bt_smp  : AES128_CMAC started, allocate buffer size = 16
,09-14 10:27:00.769  5936  5959 W bt_smp  : flag = 0 round = 1
,09-14 10:27:00.771  3115  3361 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-14 10:27:00.772  5936  5953 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 10 NewState: 11
,09-14 10:27:00.772  5720  5720 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-14 10:27:00.772  5936  5953 I BluetoothBondStateMachine: Entering PendingCommandState State
,09-14 10:27:00.774  3115  3361 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-14 10:27:00.775  5720  5720 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-14 10:27:00.780  5936  5959 W bt_smp  : smp_send_id_info
,09-14 10:27:00.820  5936  5952 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: 44:78:3E:94:4A:3E newState: 0
,09-14 10:27:00.820  5936  5953 D BluetoothAdapterProperties: Failed to remove device: 44:78:3E:94:4A:3E
09-14 10:27:00.823  3115  3361 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-14 10:27:00.823  5936  5953 I BluetoothBondStateMachine: Bond State Change Intent:44:78:3E:94:4A:3E OldState: 11 NewState: 10
09-14 10:27:00.825  5720  5720 W BluetoothEventManager: CachedBluetoothDevice for device 44:78:3E:94:4A:3E not found, calling readPairedDevices().
09-14 10:27:00.825  5936  5953 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@9416350
09-14 10:27:00.827  5936  5953 D HidService: Saved priority 44:78:3E:94:4A:3E = -1
09-14 10:27:00.828  5936  5953 I BluetoothBondStateMachine: StableState(): Entering Off State
09-14 10:27:00.829  3115  3361 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
09-14 10:27:00.829  5720  5720 E BluetoothEventManager: Got bonding state changed for 44:78:3E:94:4A:3E, but we have no record of that device.
,09-14 10:27:00.900  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:01.025  5936  5959 W bt_btif : new conn_srvc id:26, app_id:1
,09-14 10:27:01.025  5936  5959 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,09-14 10:27:01.025  5936  5959 W bt_btif : bta_dm_pm_ssr:2, lat:1200
09-14 10:27:01.027  5615  6065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> 44:78:3E:94:4A:3E 5] (thread ID: 197)
09-14 10:27:01.028  5615  6065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 197)
,09-14 10:27:01.031  5615  6065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 198)
09-14 10:27:01.032  5615  6073 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 198)
,09-14 10:27:01.032  5615  6065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 198)
,09-14 10:27:01.032  5615  6065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 197)
,09-14 10:27:01.177  5936  5936 D BtGatt.ScanManager: awakened up at time 2215324
09-14 10:27:01.179  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:01.194  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:01.196  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:01.322  5615  6073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 198)
,09-14 10:27:01.325  5615  6073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> 44:78:3E:94:4A:3E]
,09-14 10:27:01.325  5615  6073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 197)
09-14 10:27:01.325  5615  6073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 197)
,09-14 10:27:01.327  5615  6073 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 198)
,09-14 10:27:01.328  5615  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:27:01.329  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:27:01.331  5615  5615 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
09-14 10:27:01.331  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 2 -> 0
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 3 -> 1
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 2 -> 0
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-14 10:27:01.335  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
09-14 10:27:01.335  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 10:27:01.337  5615  5615 D BluetoothAdapter: STATE_ON
09-14 10:27:01.338  5936  5964 D BtGatt.GattService: stopScan() - queue size =1
,09-14 10:27:01.340  5936  5973 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:27:01.341  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:27:01.341  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:27:01.341  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
09-14 10:27:01.341  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:27:01.341  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 10:27:01.342  5615  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:27:01.343  5615  5615 D BluetoothAdapter: STATE_ON
09-14 10:27:01.346  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:27:01.347  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:01.347  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:27:01.349  5936  5972 D BtGatt.GattService: registerClient() - UUID=d5e7db29-cf09-411d-8fe4-eb57468539e1
09-14 10:27:01.352  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:27:01.352  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:01.352  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 10:27:01.352  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=d5e7db29-cf09-411d-8fe4-eb57468539e1, clientIf=5
,09-14 10:27:01.353  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:27:01.353  5936  5947 D BtGatt.GattService: start scan with filters
09-14 10:27:01.354  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:01.354  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:01.360  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 10:27:01.360  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:27:01.361  5936  5955 D BtGatt.ScanManager: handling starting scan
09-14 10:27:01.362  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
09-14 10:27:01.362  5615  5615 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
09-14 10:27:01.362  5615  6074 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 199)
09-14 10:27:01.363  5615  6074 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48804
,09-14 10:27:01.363  5615  6074 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-14 10:27:01.363  5615  6074 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 48804 (peer ID: 44:78:3E:94:4A:3E)
09-14 10:27:01.363  5615  6074 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "44:78:3E:94:4A:3E" removed
09-14 10:27:01.363  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:27:01.363  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:01.364  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:27:01.366  5615  5672 I jxcore-log: DEBUG createPeerListener: forward connection
09-14 10:27:01.366  5615  5672 I jxcore-log: 
,09-14 10:27:01.367  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:27:01.367  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:01.368  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:27:01.368  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 10:27:01.370  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 10:27:01.370  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:01.372  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:27:01.372  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:01.377  5615  6074 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 48804
09-14 10:27:01.377  5615  6074 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:27:01.377  5615  6074 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:27:01.377  5615  6074 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:27:01.378  5615  6075 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: OutgoingSocketThread/Sender)
09-14 10:27:01.378  5615  6074 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 199)
09-14 10:27:01.378  5615  6074 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 199)
,09-14 10:27:01.380  5615  6076 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: OutgoingSocketThread/Receiver)
,09-14 10:27:01.874  5936  5936 D BtGatt.ScanManager: awakened up at time 2216021
,09-14 10:27:01.876  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:01.885  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:27:01.885  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:01.901  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:02.294  5615  5672 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:AndroidBluetooth, 127.0.0.1, 127.0.0.1, 49130
09-14 10:27:02.294  5615  5672 I jxcore-log: 
,09-14 10:27:02.389  5936  5936 D BtGatt.ScanManager: awakened up at time 2216535
,09-14 10:27:02.391  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:02.394  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:02.394  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:02.443  5615  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,09-14 10:27:02.444  5615  6064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 202)
09-14 10:27:02.445  5615  6064 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 10:27:02.446  5615  6077 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 202)
09-14 10:27:02.448  5615  6064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:27:02.450  5936  5959 W bt_btif : new conn_srvc id:26, app_id:255
,09-14 10:27:02.450  5936  5959 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
09-14 10:27:02.450  5936  5959 W bt_btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,09-14 10:27:02.451  5936  5959 W bt_btif : bta_dm_pm_ssr:2, lat:1200
,09-14 10:27:02.449  5946  5946 W Binder_1: type=1400 audit(0.0:141): avc: denied { ioctl } for path="socket:[38711]" dev="sockfs" ino=38711 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:27:02.449  5946  5946 W Binder_1: type=1400 audit(0.0:142): avc: denied { ioctl } for path="socket:[38711]" dev="sockfs" ino=38711 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:27:02.454  5615  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-14 10:27:02.757  5615  6077 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 202)
,09-14 10:27:02.760  5615  6077 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> 44:78:3E:94:4A:3E]
,09-14 10:27:02.761  5615  6077 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 202)
09-14 10:27:02.761  5615  6077 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 202
09-14 10:27:02.761  5615  6077 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 202)
,09-14 10:27:02.762  5615  6077 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:27:02.763  5615  6077 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 202)
09-14 10:27:02.763  5615  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:27:02.763  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> 44:78:3E:94:4A:3E]
,09-14 10:27:02.766  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
,09-14 10:27:02.766  5615  5615 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
09-14 10:27:02.767  5615  6078 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 203)
,09-14 10:27:02.774  5615  6078 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 39885
,09-14 10:27:02.775  5615  6078 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:27:02.775  5615  6078 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:27:02.777  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:27:02.777  5615  5672 I jxcore-log: 
,09-14 10:27:02.778  5615  6078 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:27:02.779  5615  6080 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: IncomingSocketThread/Sender)
,09-14 10:27:02.780  5615  6078 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 203)
,09-14 10:27:02.780  5615  6078 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 203)
,09-14 10:27:02.782  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:27:02.782  5615  5672 I jxcore-log: 
,09-14 10:27:02.783  5615  6081 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 205, name: IncomingSocketThread/Receiver)
,09-14 10:27:02.785  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:27:02.785  5615  5672 I jxcore-log: 
,09-14 10:27:02.902  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:02.905  5936  5936 D BtGatt.ScanManager: awakened up at time 2217052
,09-14 10:27:02.907  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:02.912  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:27:02.912  5615  5672 I jxcore-log: 
,09-14 10:27:02.914  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:02.915  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:02.916  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:27:02.916  5615  5672 I jxcore-log: 
,09-14 10:27:03.420  5936  5936 D BtGatt.ScanManager: awakened up at time 2217567
,09-14 10:27:03.422  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:03.438  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:03.438  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:03.903  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:03.943  5936  5936 D BtGatt.ScanManager: awakened up at time 2218089
,09-14 10:27:03.946  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:03.959  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:03.959  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:04.190  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:27:04.190  5615  5672 I jxcore-log: 
,09-14 10:27:04.198  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:27:04.198  5615  5672 I jxcore-log: 
,09-14 10:27:04.229  5615  5672 I jxcore-log: DEBUG createNativeListener: 
09-14 10:27:04.229  5615  5672 I jxcore-log: 
,09-14 10:27:04.230  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:27:04.230  5615  5672 I jxcore-log: 
,09-14 10:27:04.464  5936  5936 D BtGatt.ScanManager: awakened up at time 2218611
,09-14 10:27:04.467  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:04.482  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:04.482  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:04.598  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:27:04.598  5615  5672 I jxcore-log: 
,09-14 10:27:04.904  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:04.986  5936  5936 D BtGatt.ScanManager: awakened up at time 2219133
09-14 10:27:04.988  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:05.004  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:05.004  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:05.868  5936  5936 D BtGatt.ScanManager: awakened up at time 2220015
,09-14 10:27:05.870  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:05.874  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:05.874  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:05.904  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 10:27:07.556   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2221703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:27:09.873  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-14 10:27:10.880  5936  5936 D BtGatt.ScanManager: awakened up at time 2225027
,09-14 10:27:10.882  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:10.900  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:10.900  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:15.906  5936  5936 D BtGatt.ScanManager: awakened up at time 2230053
09-14 10:27:15.908  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:15.923  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:27:15.923  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:19.802  5615  5615 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,09-14 10:27:19.802  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 0 -> 2
09-14 10:27:19.802  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 1 -> 3
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 0 -> 2
,09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-14 10:27:19.803  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:27:19.804  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:27:19.806  5615  5615 D BluetoothAdapter: STATE_ON
,09-14 10:27:19.808  5936  5972 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:27:19.811  5936  5947 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:27:19.813  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:27:19.813  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:27:19.813  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 10:27:19.813  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:27:19.813  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:27:19.814  5615  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:27:19.817  5615  5615 D BluetoothAdapter: STATE_ON
09-14 10:27:19.818  5936  5936 D BtGatt.ScanManager: awakened up at time 2233965
,09-14 10:27:19.825  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 10:27:19.825  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:19.825  5936  5973 D BtGatt.GattService: registerClient() - UUID=ee016a76-a07d-460c-bcbc-3f7c60087f41
09-14 10:27:19.825  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:27:19.826  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=ee016a76-a07d-460c-bcbc-3f7c60087f41, clientIf=5
,09-14 10:27:19.830  5615  5625 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:27:19.831  5936  5972 D BtGatt.GattService: start scan with filters
,09-14 10:27:19.838  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 10:27:19.838  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:27:19.838  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:19.838  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:27:19.838  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:19.848  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:27:19.849  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:19.850  5936  5955 D BtGatt.ScanManager: handling starting scan
,09-14 10:27:19.858  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 10:27:19.858  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:19.858  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:27:19.865  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 10:27:19.865  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:19.866  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:27:19.866  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:27:19.878  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:27:19.878  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:19.884  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:27:19.885  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:20.905  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:21.906  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:22.650   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2236797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:27:22.907  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:23.908  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:24.888  5936  5936 D BtGatt.ScanManager: awakened up at time 2239035
,09-14 10:27:24.892  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:24.909  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:24.924  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:27:24.924  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:24.924  5936  5952 D BtGatt.GattService: current time is 2239071754492
09-14 10:27:24.925  5936  5952 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -78, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:27:24.925  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:24.926  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-14 10:27:24.926  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:27:24.926  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:27:24.927  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:27:24.927  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:27:25.910  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 10:27:29.931  5936  5936 D BtGatt.ScanManager: awakened up at time 2244078
,09-14 10:27:29.933  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:29.966  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-14 10:27:29.967  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:29.967  5936  5952 D BtGatt.GattService: current time is 2244114065359
,09-14 10:27:29.967  5936  5952 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -75, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,09-14 10:27:29.968  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:27:29.968  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:29.968  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:29.969  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:27:29.969  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:27:29.970  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-14 10:27:31.397   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2245543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:27:31.864  3392  3597 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-14 10:27:31.865  3392  3597 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-14 10:27:31.898  3600  3600 I ConfigService: onCreate
,09-14 10:27:34.972  5936  5936 D BtGatt.ScanManager: awakened up at time 2249118
09-14 10:27:34.974  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:35.007  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-14 10:27:35.007  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:35.007  5936  5952 D BtGatt.GattService: current time is 2249154336382
09-14 10:27:35.008  5936  5952 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -76, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -73, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 10:27:35.008  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:27:35.008  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:27:35.009  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:35.009  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:27:35.009  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:35.010  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 10:27:36.934  3600  3600 I ConfigService: onDestroy
,09-14 10:27:37.785  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-14 10:27:37.785  5615  5672 I jxcore-log: 
,09-14 10:27:37.787  5615  6080 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 204, thread name: IncomingSocketThread/Sender)
09-14 10:27:37.787  5615  6080 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-14 10:27:37.787  5615  6080 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: IncomingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
09-14 10:27:37.794  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:27:37.794  5615  5672 I jxcore-log: 
09-14 10:27:37.799  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:27:37.799  5615  5672 I jxcore-log: 
,09-14 10:27:40.015  5936  5936 D BtGatt.ScanManager: awakened up at time 2254162
09-14 10:27:40.017  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:40.058  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:27:40.058  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:40.059  5936  5952 D BtGatt.GattService: current time is 2254205924073
09-14 10:27:40.059  5936  5952 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -74, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-14 10:27:40.060  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:40.062  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:27:40.063  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-14 10:27:40.063  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:27:40.064  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:40.064  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-14 10:27:45.065  5936  5936 D BtGatt.ScanManager: awakened up at time 2259212
,09-14 10:27:45.069  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:45.107  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:27:45.108  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:45.108  5936  5952 D BtGatt.GattService: current time is 2259255059940
09-14 10:27:45.108  5936  5952 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -78, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -92, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -74, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-14 10:27:45.109  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:27:45.109  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:45.110  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:45.110  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:27:45.110  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 10:27:45.110  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-14 10:27:45.912  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:46.913  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:47.691   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2261837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:27:47.914  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:48.916  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:49.917  5537  5537 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:27:50.114  5936  5936 D BtGatt.ScanManager: awakened up at time 2264261
,09-14 10:27:50.117  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:50.155  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:27:50.155  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:50.155  5936  5952 D BtGatt.GattService: current time is 2264302322318
09-14 10:27:50.156  5936  5952 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -73, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -77, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:27:50.156  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:50.157  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:27:50.157  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:27:50.157  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:50.158  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:27:50.158  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:27:50.918  5537  5537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 10:27:55.160  5936  5936 D BtGatt.ScanManager: awakened up at time 2269307
,09-14 10:27:55.163  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:55.202  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-14 10:27:55.203  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:55.203  5936  5952 D BtGatt.GattService: current time is 2269350324123
,09-14 10:27:55.204  5936  5952 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -113, -15, -120, 119, -99, 72, 1, -128, -94, 14, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -50, 47, -4, 43, 77, -86, -88, -15, 98, 32, 74, -39, -26, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -76, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -113, -15, -120, 119, -99, 72, 1, -128, -94, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -49, 47, -31, 29, 88, 123, -33, 35, -4, 31, -12, -89, 1, 0]
09-14 10:27:55.204  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:55.205  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:27:55.205  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:27:55.206  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -50, 47, -4, 43, 77, -86, -88, -15, 98, 32, 74, -39, -26]
09-14 10:27:55.210  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:27:55.210  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:55.211  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:27:55.211  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -49, 47, -31, 29, 88, 123, -33, 35, -4, 31, -12, -89, 1]
,09-14 10:27:56.463   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2270610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:27:59.660  5615  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: checkListForExpiredPeers: Peer [<no peer name> 44:78:3E:94:4A:3E 5] expired
,09-14 10:27:59.662  5615  5615 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 44:78:3E:94:4A:3E 5]
09-14 10:27:59.662  5615  5615 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 44:78:3E:94:4A:3E
,09-14 10:27:59.662  5615  5615 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID 44:78:3E:94:4A:3E
09-14 10:27:59.663  5615  5615 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 44:78:3E:94:4A:3E 5], added - the peer count is 1
,09-14 10:27:59.663  5615  5615 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 5], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
,09-14 10:27:59.705  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-14 10:27:59.714  5936  5936 D BtGatt.ScanManager: awakened up at time 2273859
,09-14 10:27:59.718  5615  5615 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,09-14 10:27:59.718  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 2 -> 0
09-14 10:27:59.719  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 3 -> 1
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 2 -> 0
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-14 10:27:59.720  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
09-14 10:27:59.720  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:27:59.720  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 10:27:59.721  5615  5615 D BluetoothAdapter: STATE_ON
,09-14 10:27:59.722  5936  5946 D BtGatt.GattService: stopScan() - queue size =1
,09-14 10:27:59.723  5936  5947 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:27:59.723  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:27:59.723  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:27:59.723  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
09-14 10:27:59.723  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:27:59.723  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:27:59.724  5615  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:27:59.725  5615  5615 D BluetoothAdapter: STATE_ON
09-14 10:27:59.726  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-14 10:27:59.726  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:59.726  5936  5952 D BtGatt.GattService: current time is 2273873621761
09-14 10:27:59.727  5936  5952 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -70, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -113, -15, -120, 119, -99, 72, 1, -128, -97, 14, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -48, 47, -126, -5, 41, 126, 92, 90, 26, -93, 62, 89, -64, 0, 37, -47, 14, -113, 116, -46, 1, -128, -78, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -92, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -113, -15, -120, 119, -99, 72, 1, -128, -97, 0, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -47, 47, 38, -98, 105, 115, 94, 49, -1, 107, 106, 79, -91, 0]
09-14 10:27:59.727  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:27:59.727  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -48, 47, -126, -5, 41, 126, 92, 90, 26, -93, 62, 89, -64]
09-14 10:27:59.727  5936  5946 D BtGatt.GattService: registerClient() - UUID=685d3745-f4d6-4901-86b9-c5a9ec96b96f
09-14 10:27:59.727  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:27:59.727  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:27:59.728  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:27:59.728  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:27:59.728  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -47, 47, 38, -98, 105, 115, 94, 49, -1, 107, 106, 79, -91]
09-14 10:27:59.728  5936  5952 D BtGatt.GattService: onClientRegistered() - UU,ID=685d3745-f4d6-4901-86b9-c5a9ec96b96f, clientIf=5
09-14 10:27:59.729  5615  6055 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:27:59.729  5936  5964 D BtGatt.GattService: start scan with filters
09-14 10:27:59.729  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:27:59.730  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:59.730  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:27:59.732  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 10:27:59.733  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:27:59.733  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:59.733  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 10:27:59.733  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:27:59.735  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:27:59.735  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:59.737  5936  5955 D BtGatt.ScanManager: handling starting scan
,09-14 10:27:59.739  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:27:59.740  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:59.740  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:27:59.742  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-14 10:27:59.742  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:27:59.742  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:27:59.742  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:27:59.751  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 10:27:59.751  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:27:59.753  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 10:27:59.753  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:00.205  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-14 10:28:00.259  5936  5936 D BtGatt.ScanManager: awakened up at time 2274406
09-14 10:28:00.262  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:00.276  5936  5959 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 2 closed: Closed (res: 19)
,09-14 10:28:00.276  5936  5961 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 9
09-14 10:28:00.276  5615  6076 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: OutgoingSocketThread/Receiver): bt socket closed, read return: -1
,09-14 10:28:00.277  5615  6076 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Failed to write to the output stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
09-14 10:28:00.277  5615  6076 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> 44:78:3E:94:4A:3E] disconnected: Failed to write to the output stream: bt socket closed, read return: -1
09-14 10:28:00.277  5615  6076 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:78:3E:94:4A:3E
09-14 10:28:00.277  5615  6076 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 199)
09-14 10:28:00.277  5615  6076 V io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
,09-14 10:28:00.277  5615  6076 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 201
09-14 10:28:00.278  5615  6076 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 201, name: OutgoingSocketThread/Receiver)
09-14 10:28:00.278  5615  6076 V io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
09-14 10:28:00.278  5615  6076 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 200
09-14 10:28:00.278  5615  6076 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 200, name: OutgoingSocketThread/Sender)
09-14 10:28:00.278  5615  6076 V io.jxcore.node.OutgoingSocketThread: close: Closing the Bluetooth socket...
09-14 10:28:00.278  5615  6076 V io.jxcore.node.OutgoingSocketThread: close: Closing the localhost socket...
,09-14 10:28:00.278  5615  6076 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 199)
09-14 10:28:00.278  5615  6076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 10:28:00.278  5615  6076 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
09-14 10:28:00.279  5615  6075 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: OutgoingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1027 and the total number of bytes written 1027
,09-14 10:28:00.285  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-14 10:28:00.292  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-14 10:28:00.293  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:28:00.294  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:00.301  5615  5672 I jxcore-log: DEBUG createPeerListener: Recreating listener
09-14 10:28:00.301  5615  5672 I jxcore-log: 
,09-14 10:28:00.303  5615  5672 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-14 10:28:00.303  5615  5672 I jxcore-log: 
,09-14 10:28:00.307  5615  5672 I jxcore-log: DEBUG createPeerListener: listening 48495
09-14 10:28:00.307  5615  5672 I jxcore-log: 
,09-14 10:28:00.308  5615  5672 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-14 10:28:00.308  5615  5672 I jxcore-log: 
,09-14 10:28:00.332  5615  5672 I jxcore-log: DEBUG createPeerListener: first connection
09-14 10:28:00.332  5615  5672 I jxcore-log: 
,09-14 10:28:00.336  5615  5672 D io.jxcore.node.JXcoreExtension: connect: 44:78:3E:94:4A:3E
09-14 10:28:00.336  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 44:78:3E:94:4A:3E
09-14 10:28:00.336  5615  5672 I io.jxcore.node.ConnectionHelper: connect: We already have an incoming connection to peer with ID 44:78:3E:94:4A:3E, but will connect anyway...
,09-14 10:28:00.336  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 44:78:3E:94:4A:3E 5]
,09-14 10:28:00.338  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Samsung Galaxy S7 in address 44:78:3E:94:4A:3E
09-14 10:28:00.338  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-14 10:28:00.338  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-14 10:28:00.340  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Samsung Galaxy S7 44:78:3E:94:4A:3E
,09-14 10:28:00.340  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Samsung Galaxy S7 in address 44:78:3E:94:4A:3E
09-14 10:28:00.340  5615  5672 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 44:78:3E:94:4A:3E)
09-14 10:28:00.340  5615  6085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 44:78:3E:94:4A:3E (thread ID: 206)
09-14 10:28:00.341  5615  6085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:28:00.343  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
09-14 10:28:00.339  5973  5973 W Binder_5: type=1400 audit(0.0:143): avc: denied { ioctl } for path="socket:[39106]" dev="sockfs" ino=39106 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:28:00.339  5973  5973 W Binder_5: type=1400 audit(0.0:144): avc: denied { ioctl } for path="socket:[39106]" dev="sockfs" ino=39106 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:28:00.799  5936  5936 D BtGatt.ScanManager: awakened up at time 2274945
,09-14 10:28:00.802  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:00.815  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:00.815  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:01.207  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-14 10:28:01.254  5936  5959 W bt_sdp  : process_service_search_attr_rsp
,09-14 10:28:01.320  5936  5936 D BtGatt.ScanManager: awakened up at time 2275466
,09-14 10:28:01.321  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:01.324  5615  6085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> 44:78:3E:94:4A:3E 5] (thread ID: 206)
,09-14 10:28:01.324  5615  6085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 206)
,09-14 10:28:01.326  5615  6085 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 207)
09-14 10:28:01.326  5615  6085 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 207)
09-14 10:28:01.326  5615  6085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 206)
09-14 10:28:01.327  5615  6086 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 207)
,09-14 10:28:01.340  5936  5959 W bt_btif : new conn_srvc id:26, app_id:1
,09-14 10:28:01.343  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:01.343  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:01.361  5615  6086 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 207)
,09-14 10:28:01.362  5615  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:01.362  5615  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 206)
09-14 10:28:01.362  5615  6086 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> 44:78:3E:94:4A:3E] (thread ID: 206)
09-14 10:28:01.362  5615  6086 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 207)
09-14 10:28:01.362  5615  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:01.362  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:01.363  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
09-14 10:28:01.363  5615  5615 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
09-14 10:28:01.364  5615  6087 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 208)
09-14 10:28:01.364  5615  6087 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47347
,09-14 10:28:01.364  5615  6087 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-14 10:28:01.364  5615  6087 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 47347 (peer ID: 44:78:3E:94:4A:3E)
09-14 10:28:01.365  5615  6087 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "44:78:3E:94:4A:3E" removed
,09-14 10:28:01.369  5615  5672 I jxcore-log: DEBUG createPeerListener: forward connection
09-14 10:28:01.369  5615  5672 I jxcore-log: 
,09-14 10:28:01.373  5615  6087 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47347
09-14 10:28:01.373  5615  6087 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:28:01.373  5615  6087 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:28:01.374  5615  6087 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:28:01.374  5615  6087 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 208)
09-14 10:28:01.375  5615  6087 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 208)
,09-14 10:28:01.377  5615  6089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 210, name: OutgoingSocketThread/Receiver)
,09-14 10:28:01.377  5615  6088 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 209, name: OutgoingSocketThread/Sender)
,09-14 10:28:01.400  5615  6081 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 205, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
,09-14 10:28:01.400  5615  6081 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
09-14 10:28:01.400  5615  6081 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> 44:78:3E:94:4A:3E] disconnected: Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)
09-14 10:28:01.400  5615  6081 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 203
09-14 10:28:01.400  5615  6081 V io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
09-14 10:28:01.400  5615  6081 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 205
,09-14 10:28:01.400  5615  6081 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 205, name: IncomingSocketThread/Receiver)
,09-14 10:28:01.400  5615  6081 V io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
09-14 10:28:01.400  5615  6081 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 204
09-14 10:28:01.401  5615  6081 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 204, name: IncomingSocketThread/Sender)
09-14 10:28:01.401  5615  6081 V io.jxcore.node.IncomingSocketThread: close: Closing the Bluetooth socket...
,09-14 10:28:01.401  5615  6081 V io.jxcore.node.IncomingSocketThread: close: Closing the localhost socket...
09-14 10:28:01.401  5615  6081 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 203)
09-14 10:28:01.401  5615  6081 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-14 10:28:01.401  5615  6081 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 205, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1027 and the total number of bytes written 909
09-14 10:28:01.404  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from ACTIVE to SNIFF.
,09-14 10:28:01.452  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to SNIFF.
,09-14 10:28:01.452  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-14 10:28:01.470  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from UNKNOWN to ACTIVE.
,09-14 10:28:01.664  5936  5959 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,09-14 10:28:01.664  5936  5959 E bt_btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
09-14 10:28:01.664  5936  5959 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-14 10:28:01.847  5936  5936 D BtGatt.ScanManager: awakened up at time 2275994
,09-14 10:28:01.850  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:01.853  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:01.853  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:02.155  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-14 10:28:02.313  5615  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,09-14 10:28:02.314  5615  6064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 211)
09-14 10:28:02.314  5615  6064 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 10:28:02.315  5615  6090 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 211)
09-14 10:28:02.315  5615  6064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 10:28:02.316  5936  5959 W bt_btif : new conn_srvc id:26, app_id:255
,09-14 10:28:02.313  5972  5972 W Binder_4: type=1400 audit(0.0:145): avc: denied { ioctl } for path="socket:[37457]" dev="sockfs" ino=37457 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 10:28:02.316  5972  5972 W Binder_4: type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[37457]" dev="sockfs" ino=37457 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 10:28:02.322  5615  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-14 10:28:02.357  5936  5936 D BtGatt.ScanManager: awakened up at time 2276504
,09-14 10:28:02.359  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:02.369  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:02.369  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:02.386  5615  6090 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 211)
,09-14 10:28:02.388  5615  6090 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:02.388  5615  6090 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 211)
,09-14 10:28:02.389  5615  6090 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 211
09-14 10:28:02.389  5615  6090 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 211)
,09-14 10:28:02.389  5615  6090 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:02.389  5615  6090 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 211)
,09-14 10:28:02.389  5615  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:02.390  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> 44:78:3E:94:4A:3E]
,09-14 10:28:02.391  5615  5615 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> 44:78:3E:94:4A:3E], created successfully
,09-14 10:28:02.391  5615  5615 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
09-14 10:28:02.392  5615  6091 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 212)
09-14 10:28:02.400  5615  6091 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 39885
09-14 10:28:02.400  5615  6091 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-14 10:28:02.400  5615  6091 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-14 10:28:02.401  5615  6091 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-14 10:28:02.404  5615  6091 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 212)
,09-14 10:28:02.404  5615  6091 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 212)
,09-14 10:28:02.406  5615  6093 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 213, name: IncomingSocketThread/Sender)
,09-14 10:28:02.408  5615  6094 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 214, name: IncomingSocketThread/Receiver)
,09-14 10:28:02.453  5615  5672 I jxcore-log: INFO testThaliNotification: PeerAdvertisesDataForUs:AndroidBluetooth, 127.0.0.1, 127.0.0.1, 48495
09-14 10:28:02.453  5615  5672 I jxcore-log: 
,09-14 10:28:02.472  5615  5672 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-14 10:28:02.472  5615  5672 I jxcore-log: 
,09-14 10:28:02.474  5615  5672 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-14 10:28:02.474  5615  5672 I jxcore-log: 
,09-14 10:28:02.475  5615  5672 I jxcore-log: DEBUG createNativeListener: new mux
09-14 10:28:02.475  5615  5672 I jxcore-log: 
,09-14 10:28:02.502  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:28:02.502  5615  5672 I jxcore-log: 
,09-14 10:28:02.505  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:28:02.505  5615  5672 I jxcore-log: 
,09-14 10:28:02.872  5936  5936 D BtGatt.ScanManager: awakened up at time 2277019
,09-14 10:28:02.875  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:02.888  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:02.888  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:03.073  5615  5672 I jxcore-log: DEBUG createNativeListener: new stream: 
09-14 10:28:03.073  5615  5672 I jxcore-log: 
,09-14 10:28:03.078  5615  5672 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-14 10:28:03.078  5615  5672 I jxcore-log: 
,09-14 10:28:03.107  5615  5672 I jxcore-log: DEBUG createNativeListener: 
09-14 10:28:03.107  5615  5672 I jxcore-log: 
,09-14 10:28:03.108  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:28:03.108  5615  5672 I jxcore-log: 
,09-14 10:28:03.394  5936  5936 D BtGatt.ScanManager: awakened up at time 2277540
,09-14 10:28:03.397  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:03.413  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:03.413  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:03.430  5615  5672 I jxcore-log: DEBUG createNativeListener: stream close:
09-14 10:28:03.430  5615  5672 I jxcore-log: 
,09-14 10:28:03.918  5936  5936 D BtGatt.ScanManager: awakened up at time 2278065
,09-14 10:28:03.921  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:03.936  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:28:03.936  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:08.411  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from ACTIVE to SNIFF.
,09-14 10:28:08.940  5936  5936 D BtGatt.ScanManager: awakened up at time 2283087
09-14 10:28:08.942  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:08.955  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:08.955  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:12.757   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2286904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:28:13.961  5936  5936 D BtGatt.ScanManager: awakened up at time 2288107
,09-14 10:28:13.964  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:13.980  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:28:13.980  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:15.919  5537  5537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 10:28:15.919  5537  5537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 10:28:18.444  5615  5615 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,09-14 10:28:18.445  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 0 -> 2
09-14 10:28:18.445  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 1 -> 3
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 0 -> 2
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-14 10:28:18.446  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 10:28:18.447  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 10:28:18.452  5615  5615 D BluetoothAdapter: STATE_ON
09-14 10:28:18.454  5936  5964 D BtGatt.GattService: stopScan() - queue size =1
,09-14 10:28:18.460  5936  5972 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 10:28:18.462  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 10:28:18.462  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-14 10:28:18.462  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 10:28:18.462  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 10:28:18.462  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 10:28:18.463  5615  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 10:28:18.466  5615  5615 D BluetoothAdapter: STATE_ON
09-14 10:28:18.469  5936  5936 D BtGatt.ScanManager: awakened up at time 2292616
09-14 10:28:18.473  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 10:28:18.473  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:18.474  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
09-14 10:28:18.474  5936  5947 D BtGatt.GattService: registerClient() - UUID=703d63c6-29b5-49d0-a010-555b66388e95
09-14 10:28:18.474  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=703d63c6-29b5-49d0-a010-555b66388e95, clientIf=5
09-14 10:28:18.475  5615  5626 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 10:28:18.475  5936  5972 D BtGatt.GattService: start scan with filters
09-14 10:28:18.480  5615  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 10:28:18.480  5615  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 10:28:18.485  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 10:28:18.485  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:18.486  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:18.494  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 10:28:18.494  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:18.496  5936  5955 D BtGatt.ScanManager: handling starting scan
,09-14 10:28:18.504  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 10:28:18.504  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:18.505  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 10:28:18.511  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-14 10:28:18.512  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:18.512  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
09-14 10:28:18.512  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 10:28:18.525  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 10:28:18.525  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:18.532  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 10:28:18.532  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:21.504   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2295650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:28:23.537  5936  5936 D BtGatt.ScanManager: awakened up at time 2297683
,09-14 10:28:23.540  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:23.581  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-14 10:28:23.581  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:23.581  5936  5952 D BtGatt.GattService: current time is 2297728604867
09-14 10:28:23.582  5936  5952 D BtGatt.GattService: Batch record : [-113, -15, -120, 119, -99, 72, 1, -128, -96, 98, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -42, 47, -40, -50, 61, 121, 33, 5, 15, -22, -6, -73, 83, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -78, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:28:23.582  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -42, 47, -40, -50, 61, 121, 33, 5, 15, -22, -6, -73, 83]
,09-14 10:28:23.583  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:28:23.584  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:28:23.584  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:23.584  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-14 10:28:23.585  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-14 10:28:23.585  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:28:28.587  5936  5936 D BtGatt.ScanManager: awakened up at time 2302733
,09-14 10:28:28.590  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:28.631  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:28:28.632  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:28.632  5936  5952 D BtGatt.GattService: current time is 2302779108755
09-14 10:28:28.632  5936  5952 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -84, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -71, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -92, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -88, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 10:28:28.633  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:28:28.633  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:28:28.634  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-14 10:28:28.634  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:28:28.634  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:28:28.635  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 10:28:33.638  5936  5936 D BtGatt.ScanManager: awakened up at time 2307785
09-14 10:28:33.640  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:33.678  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:28:33.678  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:33.678  5936  5952 D BtGatt.GattService: current time is 2307825535820
09-14 10:28:33.679  5936  5952 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -73, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -77, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:28:33.679  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:33.680  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:33.680  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:28:33.681  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:28:33.681  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-14 10:28:33.682  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:28:37.476  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-14 10:28:37.476  5615  5672 I jxcore-log: 
,09-14 10:28:37.478  5615  6093 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 213, thread name: IncomingSocketThread/Sender)
09-14 10:28:37.478  5615  6093 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-14 10:28:37.479  5615  6093 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 213, name: IncomingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
,09-14 10:28:37.482  5615  5672 I jxcore-log: DEBUG createNativeListener: mux close
09-14 10:28:37.482  5615  5672 I jxcore-log: 
,09-14 10:28:37.490  5615  5672 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-14 10:28:37.490  5615  5672 I jxcore-log: 
,09-14 10:28:37.810   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2311956, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:28:38.684  5936  5936 D BtGatt.ScanManager: awakened up at time 2312831
,09-14 10:28:38.686  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:38.723  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-14 10:28:38.723  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:38.723  5936  5952 D BtGatt.GattService: current time is 2312870734657
,09-14 10:28:38.724  5936  5952 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -70, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -81, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:38.724  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:28:38.725  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:38.725  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:28:38.726  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:28:38.727  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:40.930  5537  5539 E QC-QMI  : qmi_client [5537] 1f: failed to locate client data
,09-14 10:28:40.935   518   518 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-14 10:28:40.936   518   518 E QC-QMI  : QMUX qmux_client_id=1f not found in qmux client list, unable to remove
09-14 10:28:40.937  5537  5537 I Atfwd_Daemon: Stop the daemon....
,09-14 10:28:41.051  6098  6098 I libmdmdetect: ESOC framework not supported
,09-14 10:28:41.052  6098  6098 I libmdmdetect: Found internal modem: modem
,09-14 10:28:41.053  6098  6098 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-14 10:28:41.049  6098  6098 W ATFWD-daemon: type=1400 audit(0.0:147): avc: denied { read write } for name="diag" dev="tmpfs" ino=12411 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-14 10:28:41.063  6098  6098 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-14 10:28:41.064  6098  6098 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-14 10:28:41.064  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:42.068  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:43.070  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:43.730  5936  5936 D BtGatt.ScanManager: awakened up at time 2317877
,09-14 10:28:43.732  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:43.763  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:28:43.763  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:43.763  5936  5952 D BtGatt.GattService: current time is 2317910564117
09-14 10:28:43.764  5936  5952 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -78, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -87, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -78, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -70, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:28:43.764  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:43.764  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:28:43.764  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:43.765  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:28:43.765  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:28:43.765  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-14 10:28:44.071  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:45.073  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:46.074  6098  6098 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 10:28:46.544   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2320690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:28:48.771  5936  5936 D BtGatt.ScanManager: awakened up at time 2322918
,09-14 10:28:48.773  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:48.810  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-14 10:28:48.810  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:48.810  5936  5952 D BtGatt.GattService: current time is 2322957354672
,09-14 10:28:48.811  5936  5952 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -79, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -87, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:48.811  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-14 10:28:48.812  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-14 10:28:48.812  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 10:28:48.812  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-14 10:28:48.813  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-14 10:28:48.813  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:51.075  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:52.077  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:53.078  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:53.815  5936  5936 D BtGatt.ScanManager: awakened up at time 2327962
,09-14 10:28:53.818  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:53.854  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-14 10:28:53.854  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:53.855  5936  5952 D BtGatt.GattService: current time is 2328001984393
,09-14 10:28:53.855  5936  5952 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -77, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -84, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -72, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:28:53.856  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-14 10:28:53.857  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-14 10:28:53.857  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-14 10:28:53.857  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:28:53.858  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:28:53.858  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:53.859  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-14 10:28:54.079  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:55.080  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:28:56.081  6098  6098 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 10:28:58.860  5936  5936 D BtGatt.ScanManager: awakened up at time 2333007
,09-14 10:28:58.865  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:58.899  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,09-14 10:28:58.899  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:28:58.899  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:28:58.899  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
09-14 10:28:58.899  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 10:28:58.899  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-14 10:28:58.901  5615  5672 D BluetoothAdapter: STATE_ON
,09-14 10:28:58.902  5936  5946 D BtGatt.GattService: stopScan() - queue size =1
09-14 10:28:58.904  5936  5964 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 10:28:58.904  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 10:28:58.904  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 10:28:58.904  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-14 10:28:58.905  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 10:28:58.905  5615  5672 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 10:28:58.907  5615  5672 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 10:28:58.907  5615  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 10:28:58.914  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-14 10:28:58.914  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:58.914  5936  5952 D BtGatt.GattService: current time is 2333061433699
09-14 10:28:58.914  5936  5952 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -93, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -69, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -78, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -89, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -46, -4, -117, 6, 105, -37, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:58.915  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-14 10:28:58.915  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-14 10:28:58.915  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-14 10:28:58.915  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-14 10:28:58.916  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-14 10:28:58.917  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-14 10:28:58.917  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-14 10:28:58.923  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 10:28:58.923  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:58.924  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
,09-14 10:28:58.931  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 10:28:58.931  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 10:28:58.931  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 10:28:58.938  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 10:28:58.938  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 10:28:59.409  5615  5615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 10:28:59.409  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:28:59.410  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-14 10:28:59.415  5615  5672 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 10:28:59.415  5615  5672 I jxcore-log: 
,09-14 10:28:59.429  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:28:59.429  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-14 10:28:59.430  5615  5672 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 44:78:3E:94:4A:3E]
09-14 10:28:59.430  5615  5672 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 208)
09-14 10:28:59.430  5615  5672 V io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
09-14 10:28:59.430  5615  5672 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 210
09-14 10:28:59.431  5615  5672 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 210, name: OutgoingSocketThread/Receiver)
09-14 10:28:59.431  5615  5672 V io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
09-14 10:28:59.431  5615  5672 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 209
09-14 10:28:59.431  5615  5672 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 209, name: OutgoingSocketThread/Sender)
09-14 10:28:59.432  5615  6089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 210, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 1569 and the total number of bytes written 1569
09-14 10:28:59.432  5615  5672 V io.jxcore.node.OutgoingSocketThread: close: Closing the Bluetooth socket...
09-14 10:28:59.432  5615  5672 V io.jxcore.node.OutgoingSocketThread: close: Closing the localhost socket...
09-14 10:28:59.432  5615  5672 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 208)
09-14 10:28:59.432  5615  6088 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 209, name: OutgoingSocketThread/Sender), during the lifetime of the thread the total number of bytes read was 907 and the total number of bytes written 907
09-14 10:28:59.432  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:28:59.432  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 10:28:59.433  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 10:28:59.433  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 10:28:59.433  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 10:28:59.433  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-14 10:28:59.433  5615  5672 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 10:28:59.434  5615  5672 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 10:28:59.434  5615  6064 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 10:28:59.434  5615  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 10:28:59.434  5615  5672 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 10:28:59.434  5615  6064 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 10:28:59.436  5615  6064 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 10:28:59.436  5615  5672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-14 10:28:59.437  5615  5672 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-14 10:28:59.443  5615  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 1,0:28:59.443  5615  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 10:28:59.443  5615  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-14 10:28:59.452  5615  5672 I jxcore-log: DEBUG createPeerListener: Recreating listener
09-14 10:28:59.452  5615  5672 I jxcore-log: 
,09-14 10:28:59.454  5615  5672 I jxcore-log: DEBUG createPeerListener: createPeerListener creating new server
09-14 10:28:59.454  5615  5672 I jxcore-log: 
,09-14 10:28:59.458  5615  5672 I jxcore-log: DEBUG createPeerListener: listening 42920
09-14 10:28:59.458  5615  5672 I jxcore-log: 
,09-14 10:28:59.459  5615  5672 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
09-14 10:28:59.459  5615  5672 I jxcore-log: 
,09-14 10:28:59.469  5615  5672 I jxcore-log: not ok 153 Peer made successful https requests to all peers
09-14 10:28:59.469  5615  5672 I jxcore-log: 
09-14 10:28:59.469  5615  5672 I jxcore-log:   ---
09-14 10:28:59.469  5615  5672 I jxcore-log: 
09-14 10:28:59.469  5615  5672 I jxcore-log:     operator: ok
09-14 10:28:59.469  5615  5672 I jxcore-log: 
,09-14 10:28:59.470  5615  5672 I jxcore-log:     expected: true
09-14 10:28:59.470  5615  5672 I jxcore-log: 
09-14 10:28:59.470  5615  5672 I jxcore-log:     actual:   false
09-14 10:28:59.470  5615  5672 I jxcore-log: 
09-14 10:28:59.470  5615  5672 I jxcore-log:   ...
09-14 10:28:59.470  5615  5672 I jxcore-log: 
09-14 10:28:59.471  5615  5672 I jxcore-log: ok 154 Peer received right amount of https requests
09-14 10:28:59.471  5615  5672 I jxcore-log: 
,09-14 10:28:59.472  5615  5672 I jxcore-log: ok 155 HTTPS server received zero PSK Identities. Count:0
09-14 10:28:59.472  5615  5672 I jxcore-log: 
,09-14 10:28:59.477  5615  5672 I jxcore-log: # teardown
09-14 10:28:59.477  5615  5672 I jxcore-log: 
,09-14 10:28:59.505  5936  5959 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 2 closed: Closed (res: 19)
09-14 10:28:59.505  5936  5961 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 11
,09-14 10:28:59.505  5615  6094 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 214, thread name: IncomingSocketThread/Receiver): bt socket closed, read return: -1
09-14 10:28:59.505  5615  6094 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
09-14 10:28:59.506  5615  6094 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> 44:78:3E:94:4A:3E] disconnected: Failed to write to the output stream: bt socket closed, read return: -1
09-14 10:28:59.506  5615  6094 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 212
09-14 10:28:59.506  5615  6094 V io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
09-14 10:28:59.506  5615  6094 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 214
09-14 10:28:59.506  5615  6094 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 214, name: IncomingSocketThread/Receiver)
09-14 10:28:59.506  5615  6094 V io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
09-14 10:28:59.506  5615  6094 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 213
09-14 10:28:59.507  5615  6094 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 213, name: IncomingSocketThread/Sender)
09-14 10:28:59.507  5615  6094 V io.jxcore.node.IncomingSocketThread: close: Closing the Bluetooth socket...
09-14 10:28:59.507  5615  6094 V io.jxcore.node.IncomingSocketThread: close: Closing the localhost socket...
09-14 10:28:59.507  5615  6094 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 212)
09-14 10:28:59.507  5615  6094 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-14 10:28:59.507  5615  6094 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 214, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 903 and the total number of bytes written 903
,09-14 10:28:59.514  5936  5959 W bt_btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
09-14 10:28:59.514  5936  5959 W bt_rfcomm: port_rfc_closed RFCOMM connection in state 3 closed: Closed (res: 19)
,09-14 10:28:59.920  5615  5672 I jxcore-log: INFO testThaliNotification: Participants:3 Peers Replied to us:1 Peers requested to:2
09-14 10:28:59.920  5615  5672 I jxcore-log: 
,09-14 10:28:59.931  5615  5672 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-14 10:28:59.931  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 10:28:59.931  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 10:28:59.931  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:28:59.937  5615  5672 I jxcore-log: # setup
09-14 10:28:59.937  5615  5672 I jxcore-log: 
,09-14 10:28:59.940  5615  5672 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
09-14 10:28:59.940  5615  5672 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-14 10:28:59.941  5615  5672 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 10:28:59.941  5615  5672 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 10:29:00.008  5936  5959 D bt_btm_pm: btm_pm_snd_md_req switching from SNIFF to ACTIVE.
,09-14 10:29:00.244  5615  5672 I jxcore-log: # 39. Test BEACONS_RETRIEVED_AND_PARSED locally
09-14 10:29:00.244  5615  5672 I jxcore-log: 
,09-14 10:29:00.489  5615  5672 I jxcore-log: ok 156 peerIdentifier should be identifier
09-14 10:29:00.489  5615  5672 I jxcore-log: 
,09-14 10:29:00.490  5615  5672 I jxcore-log: ok 157 Response should be BEACONS_RETRIEVED_AND_PARSED
09-14 10:29:00.490  5615  5672 I jxcore-log: 
,09-14 10:29:00.492  5615  5672 I jxcore-log: ok 158 good beacon
09-14 10:29:00.492  5615  5672 I jxcore-log: 
,09-14 10:29:00.495  5615  5672 I jxcore-log: ok 159 good preAmble
09-14 10:29:00.495  5615  5672 I jxcore-log: 
,09-14 10:29:00.496  5615  5672 I jxcore-log: ok 160 public keys match!
09-14 10:29:00.496  5615  5672 I jxcore-log: 
,09-14 10:29:00.499  5615  5672 I jxcore-log: ok 161 must return null after successful call
09-14 10:29:00.499  5615  5672 I jxcore-log: 
,09-14 10:29:00.500  5615  5672 I jxcore-log: ok 162 Once start returns the action should be in KILLED state
09-14 10:29:00.500  5615  5672 I jxcore-log: 
,09-14 10:29:00.506  5936  5959 D bt_btm_pm: btm_pm_proc_mode_change switched from UNKNOWN to ACTIVE.
,09-14 10:29:00.510  5615  5672 I jxcore-log: # teardown
09-14 10:29:00.510  5615  5672 I jxcore-log: 
,09-14 10:29:00.581  5615  5672 I jxcore-log: # setup
09-14 10:29:00.581  5615  5672 I jxcore-log: 
,09-14 10:29:00.817  5615  5672 I jxcore-log: # 40. Test HTTP_BAD_RESPONSE locally
09-14 10:29:00.817  5615  5672 I jxcore-log: 
,09-14 10:29:00.952  5615  5672 I jxcore-log: ok 163 Response should be HTTP_BAD_RESPONSE
09-14 10:29:00.952  5615  5672 I jxcore-log: 
,09-14 10:29:00.957  5615  5672 I jxcore-log: ok 164 must return null after successful call
09-14 10:29:00.957  5615  5672 I jxcore-log: 
,09-14 10:29:00.970  5615  5672 I jxcore-log: # teardown
09-14 10:29:00.970  5615  5672 I jxcore-log: 
,09-14 10:29:01.084  5615  5672 I jxcore-log: # setup
09-14 10:29:01.084  5615  5672 I jxcore-log: 
,09-14 10:29:01.300  5615  5672 I jxcore-log: # 41. Test NETWORK_PROBLEM locally
09-14 10:29:01.300  5615  5672 I jxcore-log: 
,09-14 10:29:02.004  5615  5672 I jxcore-log: ok 165 Response should be NETWORK_PROBLEM
09-14 10:29:02.004  5615  5672 I jxcore-log: 
,09-14 10:29:02.015  5615  5672 I jxcore-log: ok 166 reject reason should be: Could not establish TCP connection
09-14 10:29:02.015  5615  5672 I jxcore-log: 
,09-14 10:29:02.026  5615  5672 I jxcore-log: # teardown
09-14 10:29:02.026  5615  5672 I jxcore-log: 
,09-14 10:29:02.062  5615  5672 I jxcore-log: # setup
09-14 10:29:02.062  5615  5672 I jxcore-log: 
,09-14 10:29:02.850   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2336997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 10:29:03.434  5615  5672 I jxcore-log: # 42. Call the start two times
09-14 10:29:03.434  5615  5672 I jxcore-log: 
,09-14 10:29:03.507  5615  5672 I jxcore-log: ok 167 Call start once
09-14 10:29:03.507  5615  5672 I jxcore-log: 
,09-14 10:29:03.623  5615  5672 I jxcore-log: ok 168 Response should be BEACONS_RETRIEVED_AND_PARSED
09-14 10:29:03.623  5615  5672 I jxcore-log: 
,09-14 10:29:03.625  5615  5672 I jxcore-log: ok 169 must return null after successful call.
09-14 10:29:03.625  5615  5672 I jxcore-log: 
,09-14 10:29:03.637  5615  5672 I jxcore-log: # teardown
09-14 10:29:03.637  5615  5672 I jxcore-log: 
,09-14 10:29:04.800  5936  5959 I bt_btm_sec: btm_sec_disconnected clearing pending flag handle:11 reason:19
,09-14 10:29:04.804  5936  5952 E BluetoothRemoteDevices: state12newState1
,09-14 10:29:04.810  5936  5936 D BluetoothMapService: onReceive
,09-14 10:29:04.810  5936  5936 D BluetoothMapService: onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,09-14 10:29:04.838   923  3467 I ActivityManager: Start proc 6103:com.google.android.googlequicksearchbox:search/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,09-14 10:29:04.850  5615  5672 I jxcore-log: # setup
09-14 10:29:04.850  5615  5672 I jxcore-log: 
,09-14 10:29:04.958   923   940 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ba1468:true
,09-14 10:29:04.966  6103  6103 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:78:3E:94:4A:3E, alias=null, name=Samsung Galaxy S7, majorDeviceClass=7936, deviceClass=7936]
,09-14 10:29:04.993  5615  5672 I jxcore-log: # 43. Call the kill before calling the start
09-14 10:29:04.993  5615  5672 I jxcore-log: 
,09-14 10:29:05.064   923  3422 I ActivityManager: Start proc 6121:com.google.android.partnersetup/u0a18 for content provider com.google.android.partnersetup/.RlzAppProvider
,09-14 10:29:05.093  5615  5672 I jxcore-log: ok 170 Should be Killed
09-14 10:29:05.093  5615  5672 I jxcore-log: 
,09-14 10:29:05.095  5615  5672 I jxcore-log: ok 171 Start after killed
09-14 10:29:05.095  5615  5672 I jxcore-log: 
,09-14 10:29:05.099  5615  5672 I jxcore-log: # teardown
09-14 10:29:05.099  5615  5672 I jxcore-log: 
,09-14 10:29:05.107  6121  6121 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,09-14 10:29:05.154  6103  6103 I BluetoothClassifier: Bluetooth Device Name: Samsung Galaxy S7
,09-14 10:29:05.239  5615  5672 I jxcore-log: # setup
09-14 10:29:05.239  5615  5672 I jxcore-log: 
,09-14 10:29:05.460  5615  5672 I jxcore-log: # 44. Call the kill immediately after the start
09-14 10:29:05.460  5615  5672 I jxcore-log: 
,09-14 10:29:06.082  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:06.155  5615  5672 I jxcore-log: ok 172 Should be KILLED
09-14 10:29:06.155  5615  5672 I jxcore-log: 
,09-14 10:29:06.158  5615  5672 I jxcore-log: ok 173 must return null after successful kill
09-14 10:29:06.158  5615  5672 I jxcore-log: 
,09-14 10:29:06.166  5615  5672 I jxcore-log: # teardown
09-14 10:29:06.166  5615  5672 I jxcore-log: 
,09-14 10:29:06.804  5615  5672 I jxcore-log: # setup
09-14 10:29:06.804  5615  5672 I jxcore-log: 
,09-14 10:29:07.083  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:07.121  5615  5672 I jxcore-log: # 45. Call the kill while waiting a response from the server
09-14 10:29:07.121  5615  5672 I jxcore-log: 
,09-14 10:29:08.084  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:09.086  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:10.087  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:10.151  5615  5672 I jxcore-log: ok 174 Should be KILLED
09-14 10:29:10.151  5615  5672 I jxcore-log: 
,09-14 10:29:10.154  5615  5672 I jxcore-log: ok 175 must return null after successful kill
09-14 10:29:10.154  5615  5672 I jxcore-log: 
,09-14 10:29:10.168  5615  5672 I jxcore-log: # teardown
09-14 10:29:10.168  5615  5672 I jxcore-log: 
,09-14 10:29:10.797  5615  5672 I jxcore-log: # setup
09-14 10:29:10.797  5615  5672 I jxcore-log: 
,09-14 10:29:11.088  6098  6098 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 10:29:11.642  5615  5672 I jxcore-log: # 46. Test to exceed the max content size locally
09-14 10:29:11.642  5615  5672 I jxcore-log: 
,09-14 10:29:11.797  5615  5672 I jxcore-log: ok 176 HTTP_BAD_RESPONSE should be response when content size is exceeded
09-14 10:29:11.797  5615  5672 I jxcore-log: 
,09-14 10:29:11.804  5615  5672 I jxcore-log: ok 177 must return null after successful call
09-14 10:29:11.804  5615  5672 I jxcore-log: 
,09-14 10:29:11.816  5615  5672 I jxcore-log: # teardown
09-14 10:29:11.816  5615  5672 I jxcore-log: 
,09-14 10:29:12.646  5615  5672 I jxcore-log: # setup
09-14 10:29:12.646  5615  5672 I jxcore-log: 
,09-14 10:29:12.835  5615  5672 I jxcore-log: # 47. Close the server socket while the client is waiting a response from the server. Local test.
09-14 10:29:12.835  5615  5672 I jxcore-log: 
,09-14 10:29:15.481  5615  5672 I jxcore-log: ok 178 Should be NETWORK_PROBLEM caused closing server socket
09-14 10:29:15.481  5615  5672 I jxcore-log: 
,09-14 10:29:15.488  5615  5672 I jxcore-log: ok 179 Should be Could not establish TCP connection
09-14 10:29:15.488  5615  5672 I jxcore-log: 
,09-14 10:29:15.497  5615  5672 I jxcore-log: # teardown
09-14 10:29:15.497  5615  5672 I jxcore-log: 
,09-14 10:29:16.349  5615  5672 I jxcore-log: # setup
09-14 10:29:16.349  5615  5672 I jxcore-log: 
,09-14 10:29:16.928  5615  5672 I jxcore-log: # 48. Close the client socket while the client is waiting a response from the server. Local test.
09-14 10:29:16.928  5615  5672 I jxcore-log: 
,09-14 10:29:19.577  5615  5672 I jxcore-log: ok 180 Should be NETWORK_PROBLEM caused closing client socket
09-14 10:29:19.577  5615  5672 I jxcore-log: 
,09-14 10:29:19.589  5615  5672 I jxcore-log: ok 181 Should be Could not establish TCP connection
09-14 10:29:19.589  5615  5672 I jxcore-log: 
,09-14 10:29:19.603  5615  5672 I jxcore-log: # teardown
09-14 10:29:19.603  5615  5672 I jxcore-log: 
,09-14 10:29:19.694  5615  5672 I jxcore-log: # setup
09-14 10:29:19.694  5615  5672 I jxcore-log: 
,09-14 10:29:19.773  5615  5672 I jxcore-log: # 49. #generatePreambleAndBeacons bad args
09-14 10:29:19.773  5615  5672 I jxcore-log: 
,09-14 10:29:19.885  5615  5672 I jxcore-log: ok 182 publicKeysToNotify cannot be null
09-14 10:29:19.885  5615  5672 I jxcore-log: 
,09-14 10:29:19.890  5615  5672 I jxcore-log: ok 183 ecdh for local device cannot be null
09-14 10:29:19.890  5615  5672 I jxcore-log: 
,09-14 10:29:19.893  5615  5672 I jxcore-log: ok 184 milliseconds cannot be less than 0
09-14 10:29:19.893  5615  5672 I jxcore-log: 
,09-14 10:29:19.897  5615  5672 I jxcore-log: ok 185 milliseconds cannot be 0
09-14 10:29:19.897  5615  5672 I jxcore-log: 
,09-14 10:29:19.900  5615  5672 I jxcore-log: ok 186 milliseconds cannot be greater than one_day
09-14 10:29:19.900  5615  5672 I jxcore-log: 
,09-14 10:29:19.904  5615  5672 I jxcore-log: # teardown
09-14 10:29:19.904  5615  5672 I jxcore-log: 
,09-14 10:29:19.984  5615  5672 I jxcore-log: # setup
09-14 10:29:19.984  5615  5672 I jxcore-log: 
,09-14 10:29:20.076  5615  5672 I jxcore-log: # 50. #generatePreambleAndBeacons empty keys to notify
09-14 10:29:20.076  5615  5672 I jxcore-log: 
,09-14 10:29:20.177  5615  5672 I jxcore-log: ok 187 should be equal
09-14 10:29:20.177  5615  5672 I jxcore-log: 
,09-14 10:29:20.180  5615  5672 I jxcore-log: # teardown
09-14 10:29:20.180  5615  5672 I jxcore-log: 
,09-14 10:29:20.295  5615  5672 I jxcore-log: # setup
09-14 10:29:20.295  5615  5672 I jxcore-log: 
,09-14 10:29:20.375  5615  5672 I jxcore-log: # 51. #generatePreambleAndBeacons multiple keys to notify
09-14 10:29:20.375  5615  5672 I jxcore-log: 
,09-14 10:29:20.555  5615  5672 I jxcore-log: ok 188 should be equal
09-14 10:29:20.555  5615  5672 I jxcore-log: 
,09-14 10:29:20.555  5615  5672 I jxcore-log: ok 189 should be equal
09-14 10:29:20.555  5615  5672 I jxcore-log: 
09-14 10:29:20.556  5615  5672 I jxcore-log: ok 190 (unnamed assert)
09-14 10:29:20.556  5615  5672 I jxcore-log: 
09-14 10:29:20.557  5615  5672 I jxcore-log: ok 191 should be equal
09-14 10:29:20.557  5615  5672 I jxcore-log: 
,09-14 10:29:20.558  5615  5672 I jxcore-log: # teardown
09-14 10:29:20.558  5615  5672 I jxcore-log: 
,09-14 10:29:20.611  5615  5672 I jxcore-log: # setup
09-14 10:29:20.611  5615  5672 I jxcore-log: 
,09-14 10:29:20.680  5615  5672 I jxcore-log: # 52. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
09-14 10:29:20.680  5615  5672 I jxcore-log: 
,09-14 10:29:20.774  5615  5672 I jxcore-log: ok 192 should throw
09-14 10:29:20.774  5615  5672 I jxcore-log: 
,09-14 10:29:20.778  5615  5672 I jxcore-log: # teardown
09-14 10:29:20.778  5615  5672 I jxcore-log: 
,09-14 10:29:20.888  5615  5672 I jxcore-log: # setup
09-14 10:29:20.888  5615  5672 I jxcore-log: 
,09-14 10:29:20.965  5615  5672 I jxcore-log: # 53. #parseBeacons invalid expiration in beaconStreamWithPreAmble
09-14 10:29:20.965  5615  5672 I jxcore-log: 
,09-14 10:29:21.074  5615  5672 I jxcore-log: ok 193 Preamble expiration must be a 64 bit integer
09-14 10:29:21.074  5615  5672 I jxcore-log: 
,09-14 10:29:21.077  5615  5672 I jxcore-log: # teardown
09-14 10:29:21.077  5615  5672 I jxcore-log: 
,09-14 10:29:21.137  5615  5672 I jxcore-log: # setup
09-14 10:29:21.137  5615  5672 I jxcore-log: 
,09-14 10:29:21.223  5615  5672 I jxcore-log: # 54. #parseBeacons expiration out of range lower
09-14 10:29:21.223  5615  5672 I jxcore-log: 
,09-14 10:29:21.354  5615  5672 I jxcore-log: ok 194 Expiration out of range
09-14 10:29:21.354  5615  5672 I jxcore-log: 
,09-14 10:29:21.357  5615  5672 I jxcore-log: # teardown
09-14 10:29:21.357  5615  5672 I jxcore-log: 
,09-14 10:29:21.440  5615  5672 I jxcore-log: # setup
09-14 10:29:21.440  5615  5672 I jxcore-log: 
,09-14 10:29:21.508  5615  5672 I jxcore-log: # 55. #parseBeacons expiration out of range lower
09-14 10:29:21.508  5615  5672 I jxcore-log: 
,09-14 10:29:21.637  5615  5672 I jxcore-log: ok 195 Expiration out of range
09-14 10:29:21.637  5615  5672 I jxcore-log: 
,09-14 10:29:21.639  5615  5672 I jxcore-log: # teardown
09-14 10:29:21.639  5615  5672 I jxcore-log: 
,09-14 10:29:21.702  5615  5672 I jxcore-log: # setup
09-14 10:29:21.702  5615  5672 I jxcore-log: 
,09-14 10:29:21.821  5615  5672 I jxcore-log: # 56. #parseBeacons no beacons returns null
09-14 10:29:21.821  5615  5672 I jxcore-log: 
,09-14 10:29:21.891  5615  5672 I jxcore-log: ok 196 should be equal
09-14 10:29:21.891  5615  5672 I jxcore-log: 
,09-14 10:29:21.893  5615  5672 I jxcore-log: # teardown
09-14 10:29:21.893  5615  5672 I jxcore-log: 
,09-14 10:29:21.962  5615  5672 I jxcore-log: # setup
09-14 10:29:21.962  5615  5672 I jxcore-log: 
,09-14 10:29:23.094  5615  5672 I jxcore-log: # 57. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
09-14 10:29:23.094  5615  5672 I jxcore-log: 
,09-14 10:29:23.523  5615  5672 I jxcore-log: ok 197 Malformed encrypted beacon key ID
09-14 10:29:23.523  5615  5672 I jxcore-log: 
09-14 10:29:23.525  5615  5672 I jxcore-log: # teardown
09-14 10:29:23.525  5615  5672 I jxcore-log: 
,09-14 10:29:25.544  5615  5672 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 10:29:25.544  5615  5672 I jxcore-log: 
,09-14 10:29:25.545  5615  5672 I jxcore-log: websocket error
09-14 10:29:25.545  5615  5672 I jxcore-log: 
09-14 10:29:25.545  5615  5672 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 10:29:25.545  5615  5672 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 10:29:25.545  5615  5672 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 10:29:25.545  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:25.545  5615  5672 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 10:29:25.545  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:25.545  5615  5672 I jxcore-log: 
,09-14 10:29:26.089  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:27.091  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:28.092  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:28.170  5615  5672 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 10:29:28.170  5615  5672 I jxcore-log: 
09-14 10:29:28.170  5615  5672 I jxcore-log: websocket error
09-14 10:29:28.170  5615  5672 I jxcore-log: 
09-14 10:29:28.170  5615  5672 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 10:29:28.170  5615  5672 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 10:29:28.170  5615  5672 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 10:29:28.170  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:28.170  5615  5672 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 10:29:28.170  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:28.170  5615  5672 I jxcore-log: 
,09-14 10:29:29.094  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:30.095  6098  6098 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 10:29:31.096  6098  6098 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 10:29:38.864   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2373010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 10:29:40.234  5615  5672 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 10:29:40.234  5615  5672 I jxcore-log: 
09-14 10:29:40.235  5615  5672 I jxcore-log: websocket error
09-14 10:29:40.235  5615  5672 I jxcore-log: 
,09-14 10:29:40.235  5615  5672 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 10:29:40.235  5615  5672 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 10:29:40.235  5615  5672 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 10:29:40.235  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:40.235  5615  5672 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 10:29:40.235  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:40.235  5615  5672 I jxcore-log: 
,09-14 10:29:45.224   923  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=2379370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 10:29:45.291  5615  5672 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-14 10:29:45.291  5615  5672 I jxcore-log: 
,09-14 10:29:45.291  5615  5672 I jxcore-log: websocket error
09-14 10:29:45.291  5615  5672 I jxcore-log: 
,09-14 10:29:45.292  5615  5672 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-14 10:29:45.292  5615  5672 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-14 10:29:45.292  5615  5672 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-14 10:29:45.292  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:45.292  5615  5672 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-14 10:29:45.292  5615  5672 I jxcore-log: emit@events.js:82:1
09-14 10:29:45.292  5615  5672 I jxcore-log: 

```
