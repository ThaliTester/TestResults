#### Test 61362366121daa0_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 5185): 
D/AndroidRuntime( 5185): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5185): CheckJNI is OFF
D/AndroidRuntime( 5185): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (209 us)
W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5185): Shutting down VM
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5204 uid=10538 gids={50538, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5204): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5204): Time to load native libraries: 2 ms (timestamps 7365-7367)
,I/LibraryLoader( 5204): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5204): Binding Chromium to main looper Looper (main, tid 1) {531dfa}
,I/LibraryLoader( 5204): Expected native library version number "",actual native library version number ""
,I/chromium( 5204): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5204): Initializing chromium process, singleProcess=true
,W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5204): ApplicationContext is null in ApplicationStatus
,W/chromium( 5204): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5204): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5204): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5204): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5204): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5204): Local Branch: 
I/Adreno-EGL( 5204): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5204): Local Patches: NONE
I/Adreno-EGL( 5204): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  891): Message: 20
D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@321b4a6:true
,D/BluetoothAdapter( 5204): 587152052: getState() :  mService = null. Returning STATE_OFF
,I/art     (  891): Explicit concurrent mark sweep GC freed 14268(695KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.579ms total 158.715ms
,W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5204): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5204): CordovaWebView is running on device made by: motorola
,W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5204): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5204): Render dirty regions requested: true
,D/Atlas   ( 5204): Validating map...
,W/chromium( 5204): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5204): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5204): Enabling debug mode 0
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/LaunchCheckinHandler(  891): Displayed com.test.thalitest/.MainActivity,cp,ca,1028
I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +1s28ms
,E/Adreno-ES20( 5204): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5204): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5204): Cannot call determinedVisibility() - never saw a connection for the pid: 5204
,V/AlarmManager(  891): send {92b6659, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  891): send {3c4033fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  891): done {92b6659, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [8ms]
V/AlarmManager(  891): done {3c4033fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [10ms]
,D/Finsky  ( 5125): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5125): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/JsMessageQueue( 5204): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5204): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5204): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5204): JniHelper::setJavaVM(0xb80e2310), pthread_self() = -1203472528
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fad967 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5204): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215281b2 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5204): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  891): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5204): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5204): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5204): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5204): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5204): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5204): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5204): Initializing JXcore engine
W/jxcore-log( 5204): JXcore engine is ready
,W/Thread-600( 5283): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10538 path="socket:[6747]" dev="sockfs" ino=6747 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-600( 5283): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10538 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-600( 5283): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10538 path="socket:[7463]" dev="sockfs" ino=7463 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-600( 5283): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10538 path="socket:[22427]" dev="sockfs" ino=22427 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5204): Starting JXcore engine
,D/TaskPersister(  891): removeObsoleteFile: deleting file=5_task_thumbnail.png
,W/jxcore-log( 5204): Platform android
W/jxcore-log( 5204): 
,W/jxcore-log( 5204): Process ARCH arm
W/jxcore-log( 5204): 
,I/jxcore-log( 5204): JXcore Cordova bridge is ready!
I/jxcore-log( 5204): 
,W/jxcore-log( 5204): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5204): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5204): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5204): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5204): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/PluginManager( 5204): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2556): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2556): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (15:298 vsyncs) (17:1163)
,I/SFPerfTracer(  278):      triggers: (rate: 13:372) (compose: 0:1) (post: 0:1) (render: 0:2) (16:1074 frames) (17:1163)
,D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb82f9230): 0:14)* (DimLayer (0xb82eb0f0): 0:8)* (StatusBar (0xb8302b08): 0:181) (NavigationBar (0xb8272ad0): 0:36) (com.android.systemui.ImageWallpaper (0xb82747e8): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb82d2568): 0:59)- (Starting com.test.thalitest (0xb82d12d8): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb82fed58): 17:50) 
D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2556): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2556): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2556): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5204): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/SFPerfTracer(  278):      triggers: (rate: 13:373) (compose: 0:1) (post: 0:1) (render: 0:4) (16:1112 frames) (17:1208)
D/SFPerfTracer(  278):        layers: (4:10) (FocusedStackFrame (0xb82f9230): 0:16)* (DimLayer (0xb82eb0f0): 0:9) (StatusBar (0xb8302b08): 0:200) (NavigationBar (0xb8272ad0): 0:49) (com.android.systemui.ImageWallpaper (0xb82747e8): 0:5)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb82fed58): 1:75)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb82d12d8): 17:26) 
,I/ActivityManager(  891): Killing 4951:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_4951/cgroup.procs: No such file or directory
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311526, SEQNUM=4356, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-19631, POWER_SUPPLY_CHARGE_COUNTER=-583, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/PowerManagerService(  891): Nap time (uid 1000)...
I/PowerManagerService(  891): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  891): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  891): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  891): Build Date: 10/28/14 Tue
I/Adreno-EGL(  891): Local Branch: 
I/Adreno-EGL(  891): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  891): Local Patches: NONE
I/Adreno-EGL(  891): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  891): activate, handle: 1598182242, enabled: 0, index 2
D/        (  891): BstSensorExt: id=1598182242, en=0
D/        (  891): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  891): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  891): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  891): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb81ea550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  297): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8891820
,I/rmt_storage(  297): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  297): wakelock acquired: 1, error no: 42
I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1198974840)
,I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1198974840) wakelock released: 1, error no: 0
I/rmt_storage(  297): 
,I/rmt_storage(  297): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8891820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  891): Excessive delay in setPowerMode(): 330ms
,I/PowerManagerService(  891): Sleeping (uid 1000)...
,I/WindowManager(  891): AOD feature not enabled!
,W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  306): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  306): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  306): platform_set_parameters: exit with code(0)
E/msm8974_platform(  306): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  306): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  306): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  891): startHal
E/wifi    (  891): getStaticLongField sWifiHalHandle 0xa2e0f89c
D/wifi    (  891): halHandle = 0x0, mVM = 0xb80e2310, mCls = 0x2017ca
I/WifiNative-HAL(  891): Could not start hal
D/WifiStateMachine(  891): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  891): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  891): setSuspendOptimizations: 4 false
E/WifiStateMachine(  891): mSuspendOptNeedsDisabled 4
,D/        (  891): activate, handle: 1598182229, enabled: 0, index 0
,I/WifiNative-HAL(  891): startHal
E/wifi    (  891): getStaticLongField sWifiHalHandle 0xa2e0f89c
D/wifi    (  891): halHandle = 0x0, mVM = 0xb80e2310, mCls = 0x20178a
I/WifiNative-HAL(  891): Could not start hal
D/WifiStateMachine(  891): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  891): handleScreenStateChanged Exit: false
,E/        (  891): <BST> disable accel, orig state: 1
I/        (  891): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/Keyboard.Facilitator( 1413): onFinishInput()
,D/audio_hw_primary(  306): adev_set_parameters: enter: screen_state=off
,E/WifiStateMachine(  891): setSuspendOptimizations: 4 true
E/WifiStateMachine(  891): mSuspendOptNeedsDisabled 0
,V/msm8974_platform(  306): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  306): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  306): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  306): adev_set_parameters: ERROR: set param called even when stream out is null
,D/TaskPersister(  891): removeObsoleteFile: deleting file=5_task.xml
,D/CdsService( 2556): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2556): [i] > Retry handler returned true; Retry web request after backoff time: 60000
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1473): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/art     ( 2962): Background sticky concurrent mark sweep GC freed 11398(1913KB) AllocSpace objects, 12(193KB) LOS objects, 21% free, 7MB/9MB, paused 5.223ms total 42.285ms
,V/AlarmManager(  891): send {24b84e63, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  891): done {24b84e63, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  891): send {2189569e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  891): send {396829ff, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  891): done {396829ff, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [12ms]
,V/AlarmManager(  891): done {2189569e, *alarm*:android.intent.action.TIME_TICK} [43ms]
,E/global frequency( 2556): no tags to log
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  891): send {dedba60, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  891): done {dedba60, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2556): Explicit concurrent mark sweep GC freed 33913(1911KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.603ms total 73.511ms
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1473): Explicit concurrent mark sweep GC freed 38136(2MB) AllocSpace objects, 17(583KB) LOS objects, 39% free, 7MB/12MB, paused 680us total 37.340ms
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  891): Explicit concurrent mark sweep GC freed 12836(773KB) AllocSpace objects, 6(257KB) LOS objects, 33% free, 20MB/31MB, paused 1.479ms total 122.924ms
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2556): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2556): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2556): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2556): BcsDSCheckin.events found events 372
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2556): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2556): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2556): unknown error code mapping for: 0
,I/global frequency( 2556): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2556): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310675, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-713, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2556): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2556): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1473): Explicit concurrent mark sweep GC freed 3615(142KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 761us total 33.391ms
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2556):  Nonce Reponse 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2556): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2556): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2556): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  891): send {396829ff, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  891): done {396829ff, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,I/VacuumService( 1696): Vacuum at: now=1456925917790 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1696): onCreate
,D/CdsService( 2556): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2556): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1696): onDestroy
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  891): send {3c4033fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  891): send {2189569e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): done {3c4033fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [5ms]
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311490, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-17427, POWER_SUPPLY_CHARGE_COUNTER=-830, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  891): done {2189569e, *alarm*:android.intent.action.TIME_TICK} [64ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1696): disconnect managed GoogleApiClient
,V/AlarmManager(  891): send {3418c451, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  891): done {3418c451, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [70ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2556): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2556): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2556):  Nonce Reponse 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2556): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2556): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2556): Explicit concurrent mark sweep GC freed 19847(1348KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.573ms total 128.361ms
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2556): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2556): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2556): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311356, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1816, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  891): send {2189569e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  891): send {395a6854, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  891): done {395a6854, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [4ms]
,V/AlarmManager(  891): done {2189569e, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2556): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2556): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2556):  Nonce Reponse 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2556): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2556): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2556): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2556): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2556): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2556): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310135, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311300, SEQNUM=4386, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310715, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  891): User[0] Flushing usage stats to disk
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  891): Explicit concurrent mark sweep GC freed 14117(783KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/31MB, paused 1.435ms total 134.256ms
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5460): 
D/AndroidRuntime( 5460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5460): CheckJNI is OFF
D/AndroidRuntime( 5460): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10538 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 5204:com.test.thalitest/u0a538 (adj 11): stop com.test.thalitest
D/WifiService(  891): Client connection lost with reason: 4
W/PackageSettings(  891): Skipping PackageSetting{1dba3072 com.example.hello/10533} due to missing metadata
W/ActivityManager(  891): Spurious death for ProcessRecord{3d7441ee 5204:com.test.thalitest/u0a538}, curProc for 5204: null
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10538 user=0: pkg removed
W/GeofencerStateMachine( 1696): Ignoring removeGeofence because network location is disabled.
I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  891): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5484 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
I/art     ( 1566): Explicit concurrent mark sweep GC freed 7358(535KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 506us total 86.138ms
I/art     ( 2962): Explicit concurrent mark sweep GC freed 3846(798KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 7MB/12MB, paused 781us total 95.636ms
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
I/art     ( 5034): Explicit concurrent mark sweep GC freed 688(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 369us total 115.558ms
I/Decoder ( 1413): createOrResetDecoder
I/art     ( 1942): Explicit concurrent mark sweep GC freed 13829(816KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 951us total 181.293ms
I/art     (  891): Explicit concurrent mark sweep GC freed 6505(565KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 4.566ms total 179.491ms
I/art     (  891): WaitForGcToComplete blocked for 155.162ms for cause Explicit
I/ConfigService( 1696): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5484): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  891): Explicit concurrent mark sweep GC freed 4294(197KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.493ms total 158.362ms
I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5512 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  891): removeObsoleteFile: deleting file=6_task.xml
D/TaskPersister(  891): removeObsoleteFile: deleting file=6_task_thumbnail.png
I/ContactLocale( 5484): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Launcher( 1566): Deferring update until onResume
D/AndroidRuntime( 5460): Shutting down VM
W/asset   ( 5512): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5512): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5512): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5512): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  891): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5533 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Killing 5093:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/ContextImpl( 5533): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_5093/cgroup.procs: No such file or directory
D/PackageBroadcastService( 1942): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1942): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1942): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1696): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1696): Shutting down VM
D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 1942): disk I/O error (code 3850)
E/DriveAsyncService( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1942): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1942): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1696): FATAL EXCEPTION: main
E/AndroidRuntime( 1696): Process: com.google.android.gms.persistent, PID: 1696
E/AndroidRuntime( 1696): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1696): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1696): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1696): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1696): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1696): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1696): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1696): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1696): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1696): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1696): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1696): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1696): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1696): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1696): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1696): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1696): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1696): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1696): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1696): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1696): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1696): 	... 9 more
I/Process ( 1696): Sending signal. PID: 1696 SIG: 9
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1942): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/FileUtils( 1942): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/JavaBinder(  891): !!! FAILED BINDER TRANSACTION !!!
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/gH_CompatibleDatabase( 1942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1942): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/SQLiteDatabase( 1942): Failed to open database '/data/data/com.google.android.gms/databases/help_responses.db'.
E/SQLiteDatabase( 1942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.b.b.a(SourceFile:108)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.b.b.d(SourceFile:529)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/SQLiteDatabase( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1942): Couldn't open help_responses.db for writing (will try read-only):
E/SQLiteOpenHelper( 1942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.b.b.a(SourceFile:108)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.b.b.d(SourceFile:529)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/SQLiteOpenHelper( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1942): Opened help_responses.db in read-only mode
D/gH_CompatibleDatabase( 1942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
E/DropBoxManagerService(  891): Can't write: system_app_crash
E/DropBoxManagerService(  891): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  891): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  891): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  891): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  891): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  891): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  891): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  891): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  891): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  891): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  891): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  891): 	... 5 more
E/ClearPendingStateOp( 1942): Runtime exception while performing operation
E/ClearPendingStateOp( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1942): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1942): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
F/ClearPendingStateOp( 1942): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1942): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1942): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1942): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1942): Sending signal. PID: 1942 SIG: 9
D/GpsStatusListenerHelper(  891): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@e471e7d
V/BackupManagerService(  891): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  891): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
D/WifiService(  891): Client connection lost with reason: 4
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
D/ConnectivityService(  891): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@11404172)
D/ConnectivityService(  891): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  891): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
