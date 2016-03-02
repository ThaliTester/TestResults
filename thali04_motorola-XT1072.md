#### Test 61432979123161a_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 5253): 
D/AndroidRuntime( 5253): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5253): CheckJNI is OFF
D/AndroidRuntime( 5253): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (178 us)
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5253): Shutting down VM
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5272 uid=10540 gids={50540, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5272): Time to load native libraries: 1 ms (timestamps 7522-7523)
I/LibraryLoader( 5272): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5272): Binding Chromium to main looper Looper (main, tid 1) {1a7a08cf}
,I/LibraryLoader( 5272): Expected native library version number "",actual native library version number ""
I/chromium( 5272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5272): Initializing chromium process, singleProcess=true
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5272): ApplicationContext is null in ApplicationStatus
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
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ff0dcd:true
,D/BluetoothAdapter( 5272): 1046997064: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5272): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5272): CordovaWebView is running on device made by: motorola
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5272): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5272): Render dirty regions requested: true
,D/Atlas   ( 5272): Validating map...
,W/chromium( 5272): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5272): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5272): Enabling debug mode 0
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1039
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s39ms
,I/Keyboard.Facilitator( 1402): onFinishInput()
,I/SFPerfTracer(  278):      triggers: (rate: 16:460) (compose: 0:1) (post: 0:3) (render: 0:4) (1:913 frames) (2:1006)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb8dee220): 1:14)* (DimLayer (0xb8dc8b58): 0:6)* (StatusBar (0xb8dcbb48): 0:154) (NavigationBar (0xb8e0bc18): 0:36) (com.android.systemui.ImageWallpaper (0xb8e0fd38): 0:9)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8e50a60): 0:54)- (Starting com.test.thalitest (0xb8e4f7d0): 1:30) (com.test.thalitest/com.test.thalitest.MainActivity (0xb8dcf018): 2:3)* 
,V/AlarmManager(  879): send {18dbf6df, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  879): send {59cf1a0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  879): done {18dbf6df, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [9ms]
,V/AlarmManager(  879): done {59cf1a0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [13ms]
,E/Adreno-ES20( 5272): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5272): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5272): Cannot call determinedVisibility() - never saw a connection for the pid: 5272
,D/Finsky  ( 5108): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5108): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/JsMessageQueue( 5272): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5272): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5272): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5272): JniHelper::setJavaVM(0xb8618310), pthread_self() = -1198002880
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5272): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99d2aa8 added. We now have 1 listener(s)
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@327eb0a7 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5272): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  879): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5272): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5272): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setDiscoveryMode: Discovery mode BLE is supported
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5272): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5272): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5272): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5272): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (39:260 vsyncs) (41:1047)
,W/jxcore-log( 5272): Initializing JXcore engine
W/jxcore-log( 5272): JXcore engine is ready
,W/Thread-590( 5350): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10540 path="socket:[5868]" dev="sockfs" ino=5868 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-590( 5350): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10540 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-590( 5350): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10540 path="socket:[9468]" dev="sockfs" ino=9468 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-590( 5350): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10540 path="socket:[22823]" dev="sockfs" ino=22823 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5272): Starting JXcore engine
,W/jxcore-log( 5272): Platform android
W/jxcore-log( 5272): 
,W/jxcore-log( 5272): Process ARCH arm
W/jxcore-log( 5272): 
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task_thumbnail.png
,I/jxcore-log( 5272): JXcore Cordova bridge is ready!
I/jxcore-log( 5272): 
,W/jxcore-log( 5272): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5272): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5272): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5272): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5272): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5272): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2653): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2653): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2653): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2653): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2653): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2653): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2653): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2653): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5272): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1402): onFinishInput()
,I/SFPerfTracer(  278):      triggers: (rate: 16:460) (compose: 0:1) (post: 0:3) (render: 0:4) (17:1007 frames) (18:1113)
D/SFPerfTracer(  278):        layers: (4:11) (FocusedStackFrame (0xb8dee220): 0:17)* (DimLayer (0xb8dc8b58): 0:7) (StatusBar (0xb8dcbb48): 0:173) (NavigationBar (0xb8e0bc18): 0:49) (com.android.systemui.ImageWallpaper (0xb8e0fd38): 0:9)* (Starting com.test.thalitest (0xb8e4f7d0): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8dcf018): 1:79)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8e4f7d0): 18:29) 
,I/ActivityManager(  879): Killing 4938:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_4938/cgroup.procs: No such file or directory
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310432, SEQNUM=4398, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15825, POWER_SUPPLY_CHARGE_COUNTER=-451, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  879): Nap time (uid 1000)...
I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  879): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  879): Build Date: 10/28/14 Tue
I/Adreno-EGL(  879): Local Branch: 
I/Adreno-EGL(  879): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  879): Local Patches: NONE
I/Adreno-EGL(  879): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  879): activate, handle: 1598182242, enabled: 0, index 2
D/        (  879): BstSensorExt: id=1598182242, en=0
D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 222
,D/        (  879): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  879): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb8d15550
D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  301): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb866a820
I/rmt_storage(  301): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  301): wakelock acquired: 1, error no: 42
I/rmt_storage(  301): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201231736)
,I/rmt_storage(  301): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  301): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  301): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201231736) wakelock released: 1, error no: 0
I/rmt_storage(  301): 
,I/rmt_storage(  301): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb866a820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
D/SurfaceControl(  879): Excessive delay in setPowerMode(): 327ms
,I/PowerManagerService(  879): Sleeping (uid 1000)...
,I/WindowManager(  879): AOD feature not enabled!
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  307): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  307): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  307): platform_set_parameters: exit with code(0)
E/msm8974_platform(  307): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  307): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  307): adev_set_parameters: ERROR: set param called even when stream out is null
I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2e1b89c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb8618310, mCls = 0x201622
I/WifiNative-HAL(  879): Could not start hal
,D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 false
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 4
,D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
E/        (  879): <BST> disable accel, orig state: 1
I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  879): startHal
E/wifi    (  879): getStaticLongField sWifiHalHandle 0xa2e1b89c
D/wifi    (  879): halHandle = 0x0, mVM = 0xb8618310, mCls = 0x15fa
I/WifiNative-HAL(  879): Could not start hal
D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
D/audio_hw_primary(  307): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  307): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  307): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  307): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  307): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  879): setSuspendOptimizations: 4 true
E/WifiStateMachine(  879): mSuspendOptNeedsDisabled 0
,I/Keyboard.Facilitator( 1402): onFinishInput()
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  879): send {65655cf, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {65655cf, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  879): send {3a8ca4d, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {3a8ca4d, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,E/global frequency( 2653): no tags to log
,D/Checkin ( 2653): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2653): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1534): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  879): Explicit concurrent mark sweep GC freed 17469(936KB) AllocSpace objects, 6(255KB) LOS objects, 33% free, 21MB/31MB, paused 1.436ms total 121.826ms
,D/BSUtils ( 2653): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2653): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2653): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1534): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 49008(2MB) AllocSpace objects, 24(821KB) LOS objects, 39% free, 7MB/12MB, paused 788us total 45.390ms
,D/BSUtils ( 2653): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2653): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2653): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1534): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2653): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2653): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2653): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2653): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2653): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2653): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2653): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2653): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2653): BcsDSCheckin.events found events 526
,D/Checkin ( 2653): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2653): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2653): Explicit concurrent mark sweep GC freed 18918(1230KB) AllocSpace objects, 3(47KB) LOS objects, 40% free, 11MB/19MB, paused 1.029ms total 65.680ms
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2653): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2653): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2653): unknown error code mapping for: 0
,I/global frequency( 2653): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 2653): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2653): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2653): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  879): send {6150b23, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {b8c7feb, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {b8c7feb, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,V/AlarmManager(  879): done {6150b23, *alarm*:android.intent.action.TIME_TICK} [34ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310705, SEQNUM=4411, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-547, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2653): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 3744(147KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 871us total 33.016ms
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2653):  Nonce Reponse 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2653): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2653): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2653): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {3a8ca4d, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): done {3a8ca4d, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5ms]
,I/VacuumService( 1691): Vacuum at: now=1456940365232 tag=VacuumService
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1402): run()
I/Keyboard.Facilitator( 1402): flushDynamicLanguageModels()
,I/ConfigService( 1691): onCreate
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1691): onDestroy
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310610, SEQNUM=4415, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-640, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {59cf1a0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  879): send {1c34651d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  879): done {59cf1a0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  879): done {1c34651d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [9ms]
,I/ClearcutLoggerApiImpl( 1691): disconnect managed GoogleApiClient
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311151, SEQNUM=4416, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-720, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  879): send {6150b23, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {6150b23, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2653): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     (  879): Explicit concurrent mark sweep GC freed 11780(614KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.714ms total 115.867ms
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
,I/ Nonce  ( 2653):  Nonce Reponse 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2653): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2653): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2653): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2653): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310775, SEQNUM=4420, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-991, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310715, SEQNUM=4421, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-108, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311309, SEQNUM=4424, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-129, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2653): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2653):  Nonce Reponse 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2653): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2653): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2653): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2653): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2653): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2653): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2653): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2653): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311005, SEQNUM=4425, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-138, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {6150b23, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {21d0daa3, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): send {2849b254, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  879): done {21d0daa3, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [15ms]
,V/AlarmManager(  879): done {6150b23, *alarm*:android.intent.action.TIME_TICK} [46ms]
,V/AlarmManager(  879): done {2849b254, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [51ms]
,I/EventLogService( 1939): Aggregate from 1456939602033 (log), 1456939602033 (data)
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
