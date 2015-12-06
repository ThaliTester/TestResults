#### Test 502422853393492_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/AndroidRuntime( 5012): 
D/AndroidRuntime( 5012): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5012): CheckJNI is OFF
D/AndroidRuntime( 5012): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (204 us)
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5012): Shutting down VM
I/ActivityManager(  884): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5031 uid=10354 gids={50354, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5031): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5031): Time to load native libraries: 3 ms (timestamps 8135-8138)
I/LibraryLoader( 5031): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5031): Binding Chromium to main looper Looper (main, tid 1) {104bad96}
I/LibraryLoader( 5031): Expected native library version number "",actual native library version number ""
I/chromium( 5031): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5031): Initializing chromium process, singleProcess=true
W/art     ( 5031): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5031): ApplicationContext is null in ApplicationStatus
W/chromium( 5031): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5031): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5031): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5031): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5031): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5031): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5031): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5031): Local Branch: 
I/Adreno-EGL( 5031): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5031): Local Patches: NONE
I/Adreno-EGL( 5031): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e1d0da4:true
D/BluetoothAdapter( 5031): 366683059: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5031): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5031): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5031): CordovaWebView is running on device made by: motorola
W/art     ( 5031): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5031): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5031): Render dirty regions requested: true
D/Atlas   ( 5031): Validating map...
W/chromium( 5031): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5031): Initialized EGL, version 1.4
D/OpenGLRenderer( 5031): Enabling debug mode 0
I/LaunchCheckinHandler(  884): Displayed com.example.hello/.MainActivity,cp,ca,998
I/ActivityManager(  884): Displayed com.example.hello/.MainActivity: +998ms
I/Keyboard.Facilitator( 1404): onFinishInput()
E/Adreno-ES20( 5031): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5031): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 5031): Cannot call determinedVisibility() - never saw a connection for the pid: 5031
I/chromium( 5031): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 5031): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5031): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5031): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5031): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5031): JniHelper::setJavaVM(0xb88d9310), pthread_self() = -1194923920
D/JX-Cordova( 5031): jxcore cordova android initializing
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (37:306 vsyncs) (39:1056)
,I/SFPerfTracer(  280):      triggers: (rate: 11:545) (compose: 0:1) (post: 0:1) (render: 0:2) (26:964 frames) (27:1055)
D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb8975338): 0:14)* (StatusBar (0xb89ddb70): 0:149) (NavigationBar (0xb8a2ef30): 0:25) (com.android.systemui.ImageWallpaper (0xb89a7088): 0:35)* (DimLayer (0xb89aaa10): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8a14160): 0:55)- (Starting com.example.hello (0xb89e0f28): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb89ad108): 27:33) 
,W/jxcore-log( 5031): Initializing JXcore engine
W/jxcore-log( 5031): JXcore engine is ready
,W/jxcore-log( 5031): Starting JXcore engine
,W/m.example.hello( 5031): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10354 path="socket:[5750]" dev="sockfs" ino=5750 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5031): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10354 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5031): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10354 path="socket:[7485]" dev="sockfs" ino=7485 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5031): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10354 path="socket:[21153]" dev="sockfs" ino=21153 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5031): Platform android
W/jxcore-log( 5031): 
,W/jxcore-log( 5031): Process ARCH arm
W/jxcore-log( 5031): 
,I/jxcore-log( 5031): JXcore Cordova bridge is ready!
I/jxcore-log( 5031): 
W/jxcore-log( 5031): JXcore engine is started
,E/jxcore-log( 5031): >> motorola-XT1072
E/jxcore-log( 5031): 
,I/jxcore-log( 5031): Total memory 916258816
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): Free memory 36704256
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): userPath [ 'www' ]
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): Size 720 1184
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): Screen Brightness 82
I/jxcore-log( 5031): 
,E/jxcore-log( 5031): Dummy Error Log.
E/jxcore-log( 5031): 
,V/AlarmManager(  884): send {8a99d6c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): send {2a617548, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  884): done {8a99d6c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,V/AlarmManager(  884): done {2a617548, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [9ms]
,I/jxcore-log( 5031): getBuffer is called!!!!
I/jxcore-log( 5031): 
,D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
D/        (  884): BstSensorExt: id=1598182242, en=0
,D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  884): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb88f4550
D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
V/ActivityManager(  884): Display changed displayId=0
,I/rmt_storage(  291): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8030820
I/rmt_storage(  291): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  291): wakelock acquired: 1, error no: 42
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1207760760)
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1207760760) wakelock released: 1, error no: 0
I/rmt_storage(  291): 
I/rmt_storage(  291): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8030820
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  884): Excessive delay in setPowerMode(): 326ms
,I/PowerManagerService(  884): Sleeping (uid 1000)...
,I/WindowManager(  884): AOD feature not enabled!
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
E/msm8974_platform(  296): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2e7489c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb88d9310, mCls = 0x1836
I/WifiNative-HAL(  884): Could not start hal
,D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
E/WifiStateMachine(  884): setSuspendOptimizations: 4 false
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 4
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2e7489c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb88d9310, mCls = 0x17fe
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 true
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 0
I/Keyboard.Facilitator( 1404): onFinishInput()
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  884): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  884): Message: 2
,D/WifiService(  884): New client listening to asynchronous messages
,D/WifiService(  884): setWifiEnabled: false pid=5031, uid=10354
E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5031): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 5031): 
,I/jxcore-log( 5031): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5031): 
,D/CdsService( 2493): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2493): [i] > Retry handler returned true; Retry web request after backoff time: 60000
,D/Checkin ( 2493): publish the event [tag = MOT_OTA event name = LOG]
,D/AndroidRuntime( 5135): 
D/AndroidRuntime( 5135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5135): CheckJNI is OFF
,D/AndroidRuntime( 5135): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  884): Force stopping com.example.hello appid=10354 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 5031:com.example.hello/u0a354 (adj 0): stop com.example.hello
,I/WindowState(  884): WIN DEATH: Window{25b127d4 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  884): Client connection lost with reason: 4
,I/ActivityManager(  884):   Force finishing activity ActivityRecord{14a49ec8 u0 com.example.hello/.MainActivity t3}
,W/PackageSettings(  884): Skipping PackageSetting{d3f81e1 com.test.thalitest/10351} due to missing metadata
,V/ActivityManager(  884): Display changed displayId=0
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  884): Spurious death for ProcessRecord{2068ee96 5031:com.example.hello/u0a354}, curProc for 5031: null
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  884): Force stopping com.example.hello appid=10354 user=0: pkg removed
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1708): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1404): resetDictionaries() : en_US
,I/art     ( 2918): Explicit concurrent mark sweep GC freed 9521(1531KB) AllocSpace objects, 8(129KB) LOS objects, 39% free, 7MB/12MB, paused 667us total 61.204ms
,D/OtaApp  ( 2493): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2493): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2493): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.DecoderInitializer( 1404): run()
,D/OtaApp  ( 2493): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2493): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
I/Decoder ( 1404): createOrResetDecoder
D/Checkin ( 2493): publish the event [tag = MOT_OTA event name = LOG]
,D/VoicemailCleanupService( 4615): Cleaning up data for package: com.example.hello
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 7330(533KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 500us total 151.391ms
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5171 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  884): Explicit concurrent mark sweep GC freed 13730(1015KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.881ms total 173.944ms
,I/art     (  884): WaitForGcToComplete blocked for 75.992ms for cause Explicit
I/ConfigService( 1623): onCreate
,W/InputMethodManagerService(  884): Got RemoteException sending setActive(false) notification to pid 5031 uid 10354
,I/Keyboard.Facilitator( 1404): onFinishInput()
,W/asset   ( 5171): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5171): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5171): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5171): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1404): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1404): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1404): run()
I/StatsUtilsManager( 1404): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1404): shouldRecordStats() = Too Soon
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5196 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  884): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task.xml
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 369us total 21.096ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 19.914ms
,I/Launcher( 1561): Deferring update until onResume
,I/ActivityManager(  884): Killing 4793:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.950ms
,I/art     (  884): Explicit concurrent mark sweep GC freed 6405(340KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.616ms total 210.281ms
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_4793/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5135): Shutting down VM
,W/ContextImpl( 5196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5214 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4577:com.android.defcontainer/u0a10 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10010/pid_4577/cgroup.procs: No such file or directory
,W/Launcher( 1561): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@22a0ed70 new=com.google.android.velvet.VelvetApplication@22a0ed70
,D/PackageBroadcastService( 4688): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 4688): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 4688): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4688): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4688): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4688): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1623): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1623): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5238 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/LocationSettingsChecker( 4688): Removing dialog suppression flag for package com.example.hello
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/gH_CompatibleDatabase( 4688): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 4688): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4688): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 4688): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 4688): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 4688): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 4688): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4688): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 4688): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 4688): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4688): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 4688): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4688): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4688): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4688): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GMPM-SVC( 4688): App measurement is starting up
,I/PeopleContactsSync( 4688): CP2 sync disabled
,I/Icing   ( 4688): doRemovePackageData com.example.hello
,D/ConnectivityService(  884): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/art     ( 1623): Explicit concurrent mark sweep GC freed 16097(918KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.493ms total 52.003ms
,E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29602fe1)
,E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15912106)
,E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@377f13c7)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c0c3df4)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1acee91d)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e8e4792)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@94f2563)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21a94560)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3075fa19)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cc54ade)
E/DataBuffer( 1623): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2284b4bf)
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5281 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
