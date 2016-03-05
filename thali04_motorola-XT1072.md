#### Test 616581981d889bb_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:33000 mC
D/AndroidRuntime( 5253): 
D/AndroidRuntime( 5253): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5253): CheckJNI is OFF
D/AndroidRuntime( 5253): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5253): Shutting down VM
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5272 uid=10551 gids={50551, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5272): Time to load native libraries: 2 ms (timestamps 7342-7344)
,I/LibraryLoader( 5272): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5272): Binding Chromium to main looper Looper (main, tid 1) {1ab60fba}
,I/LibraryLoader( 5272): Expected native library version number "",actual native library version number ""
,I/chromium( 5272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SFPerfTracer(  279):      triggers: (rate: 15:569) (compose: 0:1) (post: 0:1) (render: 0:2) (18:863 frames) (19:940)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb86fd060): 1:13)* (DimLayer (0xb86d04c0): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb86d3d50): 0:44)- (StatusBar (0xb866ce60): 19:156) (NavigationBar (0xb866f250): 13:37) (com.android.systemui.ImageWallpaper (0xb8672cd8): 0:5)* (Starting com.motorola.ccc.ota (0xb8705470): 0:37)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb86ae6d0): 18:43) (Starting com.test.thalitest (0xb86d3d50): 1:4)* 
,I/BrowserStartupController( 5272): Initializing chromium process, singleProcess=true
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5272): ApplicationContext is null in ApplicationStatus
,W/chromium( 5272): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5272): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5272): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5272): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5272): Local Branch: 
I/Adreno-EGL( 5272): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5272): Local Patches: NONE
I/Adreno-EGL( 5272): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f30536:true
,D/BluetoothAdapter( 5272): 778346100: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5272): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5272): CordovaWebView is running on device made by: motorola
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5272): Render dirty regions requested: true
,D/Atlas   ( 5272): Validating map...
,W/chromium( 5272): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5272): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5272): Enabling debug mode 0
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1045
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s45ms
I/Keyboard.Facilitator( 1406): onFinishInput()
,E/Adreno-ES20( 5272): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5272): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5272): Cannot call determinedVisibility() - never saw a connection for the pid: 5272
,D/JsMessageQueue( 5272): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5272): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5272): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5272): JniHelper::setJavaVM(0xb779d310), pthread_self() = -1213179960
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b0d427 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be1cb72 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5272): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  879): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5272): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5272): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5272): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5272): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5272): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:272 vsyncs) (45:1014)
,W/jxcore-log( 5272): Initializing JXcore engine
W/jxcore-log( 5272): JXcore engine is ready
,W/Thread-609( 5335): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10551 path="socket:[5843]" dev="sockfs" ino=5843 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-609( 5335): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10551 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-609( 5335): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10551 path="socket:[6675]" dev="sockfs" ino=6675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-609( 5335): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10551 path="socket:[23566]" dev="sockfs" ino=23566 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5272): Starting JXcore engine
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task_thumbnail.png
,V/AlarmManager(  879): send {36f02e1f, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  879): send {1d4b456c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  879): done {36f02e1f, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [9ms]
,V/AlarmManager(  879): done {1d4b456c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [12ms]
,D/Finsky  ( 5105): [595] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5105): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:33000 mC
,W/jxcore-log( 5272): Platform android
W/jxcore-log( 5272): 
W/jxcore-log( 5272): Process ARCH arm
W/jxcore-log( 5272): 
,I/jxcore-log( 5272): JXcore Cordova bridge is ready!
I/jxcore-log( 5272): 
W/jxcore-log( 5272): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5272): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2522):  Nonce Reponse 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: nonce.json
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2522): Explicit concurrent mark sweep GC freed 19091(1147KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 10MB/18MB, paused 1.134ms total 62.103ms
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:34000 mC
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5272): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 5272): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 5272): BLE multiple advertisement supported
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): My device name is: motorola-XT1072
I/jxcore-log( 5272): 
,V/AlarmManager(  879): send {1f5fb212, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {1f5fb212, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=308, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311155, SEQNUM=4361, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12419, POWER_SUPPLY_CHARGE_COUNTER=-402, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  879): Nap time (uid 1000)...
I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  879): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  879): Build Date: 10/28/14 Tue
I/Adreno-EGL(  879): Local Branch: 
I/Adreno-EGL(  879): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  879): Local Patches: NONE
I/Adreno-EGL(  879): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SFPerfTracer(  279):      triggers: (rate: 15:571) (compose: 0:1) (post: 0:1) (render: 0:2) (1:944 frames) (2:1041)
D/SFPerfTracer(  279):        layers: (3:12) (FocusedStackFrame (0xb86fd060): 0:16)* (DimLayer (0xb86d04c0): 0:6)* (StatusBar (0xb866ce60): 0:159) (NavigationBar (0xb866f250): 0:37) (com.android.systemui.ImageWallpaper (0xb8672cd8): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb86ae6d0): 0:53)- (Starting com.test.thalitest (0xb86d3d50): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8705470): 0:55) (ColorFade (0xb86d3d50): 1:1)* 
,D/        (  879): activate, handle: 1598182242, enabled: 0, index 2
D/        (  879): BstSensorExt: id=1598182242, en=0
,D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 223
,D/        (  879): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb85d3550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  879): Display changed displayId=0
,I/rmt_storage(  291): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8964820
I/rmt_storage(  291): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  291): wakelock acquired: 1, error no: 42
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1198111432)
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1198111432) wakelock released: 1, error no: 0
I/rmt_storage(  291): 
,I/rmt_storage(  291): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8964820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  879): Excessive delay in setPowerMode(): 324ms
,I/PowerManagerService(  879): Sleeping (uid 1000)...
,I/WindowManager(  879): AOD feature not enabled!
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2def89c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb779d310, mCls = 0x1526
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
E/msm8974_platform(  297): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 false
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 4
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2def89c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb779d310, mCls = 0x20150a
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
,D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  879): <BST> disable accel, orig state: 1
I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 true
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 0
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:34000 mC
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  879): send {3c03c217, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {3c03c217, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5272): 
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 5272): 
,I/io.jxcore.node.ConnectivityInfo( 5272): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5272):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5272):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5272):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 5272):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5272):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 5272):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 5272):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 5272):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 5272): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 5272): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 5272): 
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:34000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=307, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311398, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-471, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
,I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  879): send {1d4b456c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  879): send {238f0809, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  879): done {1d4b456c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [2ms]
,V/AlarmManager(  879): done {238f0809, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [4ms]
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 5272): 
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 5272): 
,E/global frequency( 2522): no tags to log
D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 5272): 
,E/PhoneInterfaceManager( 1535): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  879): Explicit concurrent mark sweep GC freed 15927(887KB) AllocSpace objects, 5(321KB) LOS objects, 33% free, 20MB/30MB, paused 1.529ms total 113.160ms
,V/AlarmManager(  879): send {1e7868b3, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {1e7868b3, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 53158(2MB) AllocSpace objects, 32(1029KB) LOS objects, 40% free, 7MB/12MB, paused 878us total 44.274ms
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log( 5272): 
,E/PhoneInterfaceManager( 1535): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1535): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/jxcore-log( 5272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5272): 
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 4203(175KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 590us total 28.357ms
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2522): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2522): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2522): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/jxcore-log( 5272): Unit Test app is loaded
I/jxcore-log( 5272): 
,I/chromium( 5272): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/jxcore-log( 5272): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 5272): 
,I/global frequency( 2522): BcsDSCheckin.events found events 1271
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:34000 mC
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2522): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2522): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2522): unknown error code mapping for: 0
,I/global frequency( 2522): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2522): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2522): Explicit concurrent mark sweep GC freed 28580(2MB) AllocSpace objects, 6(118KB) LOS objects, 39% free, 11MB/18MB, paused 1.156ms total 78.775ms
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2522):  Nonce Reponse 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=296, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311113, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-544, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  879): send {1f5fb212, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {1d4b456c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {1d4b456c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [10ms]
,V/AlarmManager(  879): done {1f5fb212, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/art     (  879): Explicit concurrent mark sweep GC freed 8283(424KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.339ms total 115.164ms
,I/VacuumService( 1686): Vacuum at: now=1457138589517 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1686): disconnect managed GoogleApiClient
,I/Keyboard.Facilitator.LanguageModelFlusher( 1406): run()
,I/Keyboard.Facilitator( 1406): flushDynamicLanguageModels()
,I/ConfigService( 1686): onCreate
,V/AlarmManager(  879): send {13a5c7a5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  879): done {13a5c7a5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1686): onDestroy
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311855, SEQNUM=4381, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-575, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {238f0809, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  879): send {1f5fb212, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {238f0809, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [7ms]
,V/AlarmManager(  879): done {1f5fb212, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311159, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-640, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2522):  Nonce Reponse 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 3271(130KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 777us total 30.350ms
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311626, SEQNUM=4389, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1514, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {1f5fb212, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {3cc71510, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): send {104bd7f6, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  879): done {3cc71510, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [20ms]
,V/AlarmManager(  879): done {104bd7f6, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [37ms]
,V/AlarmManager(  879): done {1f5fb212, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/EventLogService( 1935): Aggregate from 1457136889912 (log), 1457136889912 (data)
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2522):  Nonce Reponse 
,I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2522): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2522): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2522): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2522): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2522): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5460): 
D/AndroidRuntime( 5460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5460): CheckJNI is OFF
D/AndroidRuntime( 5460): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10551 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 5272:com.test.thalitest/u0a551 (adj 0): stop com.test.thalitest
W/PackageSettings(  879): Skipping PackageSetting{d893a32 com.example.hello/10548} due to missing metadata
I/WindowState(  879): WIN DEATH: Window{16e527e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
I/ActivityManager(  879):   Force finishing activity ActivityRecord{1818f8dc u0 com.test.thalitest/.MainActivity t9}
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  879): Spurious death for ProcessRecord{1d1091df 5272:com.test.thalitest/u0a551}, curProc for 5272: null
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10551 user=0: pkg removed
I/ActivityManager(  879):   Force finishing activity ActivityRecord{1818f8dc u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  879): Duplicate finish request for ActivityRecord{1818f8dc u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 2965): Explicit concurrent mark sweep GC freed 3834(790KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 7MB/12MB, paused 800us total 55.704ms
D/OtaApp  ( 2522): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2522): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2522): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1686): Ignoring removeGeofence because network location is disabled.
D/OtaApp  ( 2522): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2522): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
I/art     ( 1554): Explicit concurrent mark sweep GC freed 7406(539KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 552us total 90.226ms
I/art     ( 1935): Explicit concurrent mark sweep GC freed 3928(226KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 1.027ms total 90.036ms
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
D/VoicemailCleanupService( 4932): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
I/Decoder ( 1406): createOrResetDecoder
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5492 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
W/InputMethodManagerService(  879): Got RemoteException sending setActive(false) notification to pid 5272 uid 10551
I/Keyboard.Facilitator( 1406): onFinishInput()
I/ConfigService( 1686): onCreate
I/art     (  879): Explicit concurrent mark sweep GC freed 17198(1170KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/30MB, paused 1.787ms total 198.443ms
I/art     (  879): WaitForGcToComplete blocked for 129.363ms for cause Explicit
W/asset   ( 5492): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5492): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5492): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5492): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5513 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task.xml
I/ActivityManager(  879): Killing 5077:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  879): Explicit concurrent mark sweep GC freed 5001(257KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.621ms total 165.321ms
I/Launcher( 1554): Deferring update until onResume
W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_5077/cgroup.procs: No such file or directory
D/AndroidRuntime( 5460): Shutting down VM
W/ContextImpl( 5513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1935): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1935): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1935): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1686): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1686): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1935): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1935): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1935): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1935): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1935): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5542 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1935): doRemovePackageData com.test.thalitest
W/Launcher( 1554): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@172a647 new=com.google.android.velvet.VelvetApplication@172a647
I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5566 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  315): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.125ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 19.786ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.567ms
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
