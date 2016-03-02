#### Test 613623666a5dbc7_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 5149): 
D/AndroidRuntime( 5149): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5149): CheckJNI is OFF
D/AndroidRuntime( 5149): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (164 us)
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5149): Shutting down VM
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5168 uid=10535 gids={50535, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5168): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5168): Time to load native libraries: 7 ms (timestamps 7360-7367)
I/LibraryLoader( 5168): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5168): Binding Chromium to main looper Looper (main, tid 1) {2243a717}
,I/LibraryLoader( 5168): Expected native library version number "",actual native library version number ""
,I/chromium( 5168): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5168): Initializing chromium process, singleProcess=true
I/SFPerfTracer(  278):      triggers: (rate: 12:362) (compose: 0:1) (post: 0:1) (render: 0:2) (18:1005 frames) (19:1077)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb768d218): 1:11)* (DimLayer (0xb7694ac0): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb769b530): 0:36)- (StatusBar (0xb76988a0): 19:160) (NavigationBar (0xb772cff8): 13:36) (com.android.systemui.ImageWallpaper (0xb77301b8): 0:5)* (Starting com.motorola.ccc.ota (0xb773c5b8): 0:38)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7747c08): 18:46) (Starting com.test.thalitest (0xb769b530): 2:5)* 
,W/art     ( 5168): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5168): ApplicationContext is null in ApplicationStatus
,W/chromium( 5168): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5168): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5168): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5168): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5168): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5168): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5168): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5168): Local Branch: 
I/Adreno-EGL( 5168): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5168): Local Patches: NONE
I/Adreno-EGL( 5168): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dfd1f4d:true
,D/BluetoothAdapter( 5168): 502209390: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5168): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5168): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5168): CordovaWebView is running on device made by: motorola
,W/art     ( 5168): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5168): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5168): Render dirty regions requested: true
,D/Atlas   ( 5168): Validating map...
,W/chromium( 5168): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5168): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5168): Enabling debug mode 0
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1045
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s45ms
,E/Adreno-ES20( 5168): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5168): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5168): Cannot call determinedVisibility() - never saw a connection for the pid: 5168
,D/JsMessageQueue( 5168): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  883): send {3e85ff37, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): done {3e85ff37, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [2ms]
,E/Adreno-ES20( 5168): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5168): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5168): JniHelper::setJavaVM(0xb8a7a310), pthread_self() = -1193415368
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@146ed5d0 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5168): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f613ef added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5168): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  883): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5168): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5168): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5168): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5168): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5168): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5168): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:288 vsyncs) (45:1150)
,W/jxcore-log( 5168): Initializing JXcore engine
W/jxcore-log( 5168): JXcore engine is ready
,W/Thread-594( 5262): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10535 path="socket:[5633]" dev="sockfs" ino=5633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-594( 5262): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10535 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-594( 5262): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10535 path="socket:[9659]" dev="sockfs" ino=9659 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-594( 5262): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10535 path="socket:[23753]" dev="sockfs" ino=23753 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5168): Starting JXcore engine
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task_thumbnail.png
,W/jxcore-log( 5168): Platform android
W/jxcore-log( 5168): 
W/jxcore-log( 5168): Process ARCH arm
W/jxcore-log( 5168): 
,I/jxcore-log( 5168): JXcore Cordova bridge is ready!
I/jxcore-log( 5168): 
,W/jxcore-log( 5168): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5168): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5168): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5168): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5168): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5168): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2531): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2531): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2531): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2531): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2531): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2531): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2531): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2531): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1405): onFinishInput()
W/IInputConnectionWrapper( 5168): showStatusIcon on inactive InputConnection
,I/SFPerfTracer(  278):      triggers: (rate: 12:363) (compose: 0:1) (post: 0:1) (render: 0:2) (12:1098 frames) (13:1189)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb768d218): 0:16)* (DimLayer (0xb7694ac0): 0:7) (StatusBar (0xb76988a0): 13:176) (NavigationBar (0xb772cff8): 12:50) (com.android.systemui.ImageWallpaper (0xb77301b8): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7747c08): 0:55)- (Starting com.test.thalitest (0xb769b530): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb773c5b8): 13:73) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb769b530): 0:4)* 
,I/SFPerfTracer(  278):      triggers: (rate: 12:364) (compose: 0:1) (post: 0:1) (render: 0:4) (17:1121 frames) (18:1214)
D/SFPerfTracer(  278):        layers: (4:10) (FocusedStackFrame (0xb768d218): 0:16)* (DimLayer (0xb7694ac0): 0:7) (StatusBar (0xb76988a0): 0:179) (NavigationBar (0xb772cff8): 0:50) (com.android.systemui.ImageWallpaper (0xb77301b8): 0:5)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb773c5b8): 1:81)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb769b530): 18:26) 
,I/ActivityManager(  883): Killing 4987:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_4987/cgroup.procs: No such file or directory
,I/PowerManagerService(  883): Nap time (uid 1000)...
,I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
D/        (  883): BstSensorExt: id=1598182242, en=0
,D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 222
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb760c550
D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  883): Display changed displayId=0
,I/rmt_storage(  311): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb756a820
I/rmt_storage(  311): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  311): wakelock acquired: 1, error no: 42
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219057528)
,I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219057528) wakelock released: 1, error no: 0
I/rmt_storage(  311): 
,I/rmt_storage(  311): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb756a820
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  883): Excessive delay in setPowerMode(): 329ms
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,I/WindowManager(  883): AOD feature not enabled!
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  317): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  317): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  317): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  317): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  317): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  317): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e7589c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8a7a310, mCls = 0x101756
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 false
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 4
,I/WifiNative-HAL(  883): startHal
,E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e7589c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8a7a310, mCls = 0x10172e
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
I/Keyboard.Facilitator( 1405): onFinishInput()
D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  317): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  317): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  317): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  317): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  317): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 true
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:31000 mC
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  883): send {37463a29, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  883): done {37463a29, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311905, SEQNUM=4363, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16326, POWER_SUPPLY_CHARGE_COUNTER=-919, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  315): NetlinkHandler, power_supply subsys
I/MDMCTBK (  315): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  315): checkDefaultInst, current pid is = 315
I/MDMCTBK (  315): checkDefaultInst, pid match
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  315): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  315): NetlinkHandler, power_supply subsys
I/MDMCTBK (  315): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  315): checkDefaultInst, current pid is = 315
I/MDMCTBK (  315): checkDefaultInst, pid match
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  315): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1cf967b5, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {28347625, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {28347625, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [9ms]
,V/AlarmManager(  883): done {1cf967b5, *alarm*:android.intent.action.TIME_TICK} [41ms]
,E/global frequency( 2531): no tags to log
,D/Checkin ( 2531): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2531): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,V/AlarmManager(  883): send {13df4fe5, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {13df4fe5, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2531): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2531): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2531): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 38487(2MB) AllocSpace objects, 17(583KB) LOS objects, 39% free, 7MB/12MB, paused 759us total 37.152ms
,D/BSUtils ( 2531): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2531): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2531): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  883): Explicit concurrent mark sweep GC freed 14083(840KB) AllocSpace objects, 6(255KB) LOS objects, 33% free, 20MB/31MB, paused 1.412ms total 120.239ms
,D/BSUtils ( 2531): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2531): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2531): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2531): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2531): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2531): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2531): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2531): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2531): BcsDSCheckin.events found events 185
,D/Checkin ( 2531): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2531): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2531): Explicit concurrent mark sweep GC freed 16071(998KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.198ms total 59.801ms
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2531): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2531): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2531): unknown error code mapping for: 0
I/global frequency( 2531): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2531): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2531): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 3220(128KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 790us total 34.405ms
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2531):  Nonce Reponse 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2531): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2531): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2531): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {28347625, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {28347625, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,I/VacuumService( 1695): Vacuum at: now=1456906230857 tag=VacuumService
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311486, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18529, POWER_SUPPLY_CHARGE_COUNTER=-1118, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  315): NetlinkHandler, power_supply subsys
I/MDMCTBK (  315): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  315): checkDefaultInst, current pid is = 315
I/MDMCTBK (  315): checkDefaultInst, pid match
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  315): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  315): NetlinkHandler, power_supply subsys
I/MDMCTBK (  315): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  315): checkDefaultInst, current pid is = 315
I/MDMCTBK (  315): checkDefaultInst, pid match
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  315): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1695): onCreate
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ConfigService( 1695): onDestroy
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1695): disconnect managed GoogleApiClient
,V/AlarmManager(  883): send {3e85ff37, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  883): send {1cf967b5, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {3e85ff37, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [5ms]
,V/AlarmManager(  883): done {1cf967b5, *alarm*:android.intent.action.TIME_TICK} [40ms]
,V/AlarmManager(  883): send {2246a547, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): done {2246a547, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  315): NetlinkHandler, power_supply subsys
I/MDMCTBK (  315): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  315): checkDefaultInst, current pid is = 315
I/MDMCTBK (  315): checkDefaultInst, pid match
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  315): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  315): NetlinkHandler, power_supply subsys
I/MDMCTBK (  315): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  315): checkDefaultInst, current pid is = 315
I/MDMCTBK (  315): checkDefaultInst, pid match
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  315): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  315): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311936, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-1805, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2531): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2531):  Nonce Reponse 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2531): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2531): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2531): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  883): send {1cf967b5, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {395bd436, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  883): send {2b83bc9e, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,D/Finsky  ( 5057): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  883): send {31780109, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): done {2b83bc9e, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [21ms]
,V/AlarmManager(  883): done {395bd436, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [25ms]
,V/AlarmManager(  883): done {1cf967b5, *alarm*:android.intent.action.TIME_TICK} [53ms]
,V/AlarmManager(  883): done {31780109, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [65ms]
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1941): Aggregate from 1456904947184 (log), 1456904947184 (data)
,W/Finsky  ( 5057): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5383 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 12953(629KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.311ms total 115.594ms
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5383): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5383): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Finsky  ( 5057): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 5383): VM with version 2.1.0 has multidex support
I/MultiDex( 5383): install
,I/MultiDex( 5383): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5383): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5383): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5383): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@83a000b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5383): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1695): callingUid 10016, callindPid: 1695
,E/MDM     ( 1695): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1695): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 5383): Reading stored module config
D/LocationInitializer( 1941): Restart initialization of location
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1695): No location to return for getLastLocation()
W/FusedLocationProvider( 1695): location=null
,D/ChimeraCfgMgr( 5383): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 5383): Connecting to CarCallService...
,I/art     ( 5383): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5383): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5383): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5383): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5383): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5383): Creating a new PhoneAdapter instance
,W/ActivityManager(  883): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5383): setListener: com.google.android.gms.car.dn@1363e256
,W/ActivityManager(  883): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5383): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5383): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5383): Package validated; name: com.android.vending
,V/Finsky  ( 5057): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5057): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5057): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  883): send {2304b4da, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5057): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,V/AlarmManager(  883): done {2304b4da, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [24ms]
,D/DeviceConnectionService( 1695): client connected with version: 8296000
,D/Finsky  ( 5057): [591] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5057): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5057): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  883): Killing 4888:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_4888/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5383): mConnectedToCar = false, abort
,E/ActivityThread( 5383): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e6f217e that was originally bound here
E/ActivityThread( 5383): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e6f217e that was originally bound here
E/ActivityThread( 5383): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5383): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5383): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5383): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5383): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5383): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5383): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5383): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5383): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5383): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5383): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5383): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5383): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5383): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5383): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5383): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5383): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5383): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@17cae471 that was originally bound here
E/ActivityThread( 5383): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@17cae471 that was originally bound here
E/ActivityThread( 5383): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5383): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5383): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5383): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5383): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5383): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5383): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5383): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5383): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5383): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5383): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5383): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5383): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5383): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5383): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5383): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5383): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5383): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5383): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  883): Unbind failed: could not find connection for android.os.BinderProxy@2014a283
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  883): send {2fb8c39, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  883): done {2fb8c39, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,D/Finsky  ( 5057): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5057): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ClearcutLoggerApiImpl( 1695): disconnect managed GoogleApiClient
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2531): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2531):  Nonce Reponse 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2531): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2531): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2531): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2531): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2531): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2531): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2531): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2531): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
