#### Test 50242285e132180_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,D/AndroidRuntime( 5032): 
D/AndroidRuntime( 5032): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5032): CheckJNI is OFF
D/AndroidRuntime( 5032): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5032): Shutting down VM
I/ActivityManager(  884): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5051 uid=10359 gids={50359, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5051): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5051): Time to load native libraries: 2 ms (timestamps 7455-7457)
I/LibraryLoader( 5051): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5051): Binding Chromium to main looper Looper (main, tid 1) {b229d98}
I/LibraryLoader( 5051): Expected native library version number "",actual native library version number ""
I/chromium( 5051): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5051): Initializing chromium process, singleProcess=true
W/art     ( 5051): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5051): ApplicationContext is null in ApplicationStatus
W/chromium( 5051): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5051): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5051): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5051): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5051): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5051): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5051): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5051): Local Branch: 
I/Adreno-EGL( 5051): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5051): Local Patches: NONE
I/Adreno-EGL( 5051): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@255fa689:true
D/BluetoothAdapter( 5051): 366273581: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5051): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5051): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5051): CordovaWebView is running on device made by: motorola
W/art     ( 5051): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5051): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5051): Render dirty regions requested: true
D/Atlas   ( 5051): Validating map...
W/chromium( 5051): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5051): Initialized EGL, version 1.4
D/OpenGLRenderer( 5051): Enabling debug mode 0
I/Keyboard.Facilitator( 1409): onFinishInput()
I/LaunchCheckinHandler(  884): Displayed com.example.hello/.MainActivity,cp,ca,970
I/ActivityManager(  884): Displayed com.example.hello/.MainActivity: +970ms
E/Adreno-ES20( 5051): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5051): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 5051): Cannot call determinedVisibility() - never saw a connection for the pid: 5051
,I/chromium( 5051): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5051): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5051): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5051): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5051): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5051): JniHelper::setJavaVM(0xb79bc310), pthread_self() = -1210975584
D/JX-Cordova( 5051): jxcore cordova android initializing
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (18:221 vsyncs) (20:1033)
I/SFPerfTracer(  280):      triggers: (rate: 10:488) (compose: 0:1) (post: 0:1) (render: 0:2) (26:944 frames) (27:1033)
D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb8d23028): 0:14)* (StatusBar (0xb8d2f870): 0:98) (NavigationBar (0xb8d32f18): 0:24) (com.android.systemui.ImageWallpaper (0xb8d491f8): 0:5)* (DimLayer (0xb8d4eef0): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8d58758): 0:54)- (Starting com.example.hello (0xb8d56df0): 0:39)- (com.example.hello/com.example.hello.MainActivity (0xb8d29748): 27:34) 
,W/jxcore-log( 5051): Initializing JXcore engine
W/jxcore-log( 5051): JXcore engine is ready
W/jxcore-log( 5051): Starting JXcore engine
W/m.example.hello( 5051): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10359 path="socket:[6523]" dev="sockfs" ino=6523 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5051): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10359 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5051): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10359 path="socket:[7500]" dev="sockfs" ino=7500 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5051): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10359 path="socket:[20964]" dev="sockfs" ino=20964 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5051): Platform android
W/jxcore-log( 5051): 
W/jxcore-log( 5051): Process ARCH arm
W/jxcore-log( 5051): 
I/jxcore-log( 5051): JXcore Cordova bridge is ready!
I/jxcore-log( 5051): 
W/jxcore-log( 5051): JXcore engine is started
E/jxcore-log( 5051): >> motorola-XT1072
E/jxcore-log( 5051): 
I/jxcore-log( 5051): Total memory 916258816
I/jxcore-log( 5051): 
I/jxcore-log( 5051): Free memory 35491840
I/jxcore-log( 5051): 
I/jxcore-log( 5051): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5051): 
I/jxcore-log( 5051): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5051): 
I/jxcore-log( 5051): userPath [ 'www' ]
I/jxcore-log( 5051): 
I/jxcore-log( 5051): Size 720 1184
I/jxcore-log( 5051): 
I/jxcore-log( 5051): Screen Brightness 82
I/jxcore-log( 5051): 
E/jxcore-log( 5051): Dummy Error Log.
E/jxcore-log( 5051): 
,I/jxcore-log( 5051): getBuffer is called!!!!
I/jxcore-log( 5051): 
,D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  884): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  884): Message: 2
,D/WifiService(  884): New client listening to asynchronous messages
,D/WifiService(  884): setWifiEnabled: false pid=5051, uid=10359
E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/jxcore-log( 5051): ****TEST TOOK:  5071  ms ****
I/jxcore-log( 5051): 
I/jxcore-log( 5051): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5051): 
,D/AndroidRuntime( 5124): 
D/AndroidRuntime( 5124): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5124): CheckJNI is OFF
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
D/        (  884): BstSensorExt: id=1598182242, en=0
D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  884): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  884): Display changed displayId=0
,D/AndroidRuntime( 5124): Calling main entry com.android.commands.pm.Pm
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb8c1d550
,D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,I/ActivityManager(  884): Force stopping com.example.hello appid=10359 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 5051:com.example.hello/u0a359 (adj 0): stop com.example.hello
,I/WindowState(  884): WIN DEATH: Window{20243f9 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  884): Client connection lost with reason: 4
,W/PackageSettings(  884): Skipping PackageSetting{2e1fa92b com.test.thalitest/10356} due to missing metadata
,I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8ede820
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1192367992)
,W/ActivityManager(  884): Force removing ActivityRecord{3d8a841d u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  884): Display changed displayId=0
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  884): Spurious death for ProcessRecord{3a35d384 5051:com.example.hello/u0a359}, curProc for 5051: null
,I/ActivityManager(  884): Force stopping com.example.hello appid=10359 user=0: pkg removed
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 7318(532KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 508us total 40.382ms
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1192367992) wakelock released: 1, error no: 0
I/rmt_storage(  302): 
,I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8ede820
,I/art     ( 3056): Explicit concurrent mark sweep GC freed 11048(1680KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/12MB, paused 765us total 99.334ms
,W/GeofencerStateMachine( 1712): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
I/SFPerfTracer(  280):       trigger: frame rate (-26.138%)	(44.317 fps)	(22.564 ms) 	(2 drops)	(17 frames)
I/SFPerfTracer(  280):      triggers: (rate: 11:491) (compose: 0:1) (post: 0:1) (render: 0:2) (17:974 frames) (18:1071)
D/SFPerfTracer(  280):        layers: (4:10) (FocusedStackFrame (0xb8d23028): 0:14)* (StatusBar (0xb8d2f870): 0:98) (NavigationBar (0xb8d32f18): 0:24) (com.android.systemui.ImageWallpaper (0xb8d491f8): 0:5)* (DimLayer (0xb8d4eef0): 0:6)* (com.example.hello/com.example.hello.MainActivity (0xb8d29748): 0:51) (ColorFade (0xb8d56df0): 18:20) 
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,D/SurfaceControl(  884): Excessive delay in setPowerMode(): 356ms
,I/PowerManagerService(  884): Sleeping (uid 1000)...
,D/OtaApp  ( 2654): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2654): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2654): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2654): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2654): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2654): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  884): send {25335891, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
I/Decoder ( 1409): createOrResetDecoder
W/InputMethodManagerService(  884): Got RemoteException sending setActive(false) notification to pid 5051 uid 10359
,I/Keyboard.Facilitator( 1409): onFinishInput()
,D/VoicemailCleanupService( 4908): Cleaning up data for package: com.example.hello
,I/art     (  884): Explicit concurrent mark sweep GC freed 11886(933KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.924ms total 213.597ms
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5156 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1608): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
,W/asset   ( 5156): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5156): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5156): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5156): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  884): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task.xml
,I/WindowManager(  884): AOD feature not enabled!
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  307): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  307): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  307): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  307): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  307): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  307): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2e2d89c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb79bc310, mCls = 0x10192a
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
E/WifiStateMachine(  884): setSuspendOptimizations: 4 false
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 4
,I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5181 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  884): Explicit concurrent mark sweep GC freed 5529(284KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.851ms total 188.671ms
,D/AndroidRuntime( 5124): Shutting down VM
,I/ActivityManager(  884): Killing 4847:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10057/pid_4847/cgroup.procs: No such file or directory
,I/Launcher( 1562): Deferring update until onResume
,W/ContextImpl( 5181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5203 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4886:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_4886/cgroup.procs: No such file or directory
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2e2d89c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb79bc310, mCls = 0x18be
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
I/Keyboard.Facilitator( 1409): onFinishInput()
E/WifiStateMachine(  884): setSuspendOptimizations: 4 true
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 0
,D/audio_hw_primary(  307): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  307): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  307): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  307): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  307): adev_set_parameters: ERROR: set param called even when stream out is null
,E/SQLiteDatabase( 3056): Error inserting name=ScreenExtraTrigger state=screx=2 timestamp=1449501202499 timezone=3600
E/SQLiteDatabase( 3056): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3056): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3056): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 3056): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3056): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3056): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 3056): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1341)
E/SQLiteDatabase( 3056): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 3056): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:204)
E/SQLiteDatabase( 3056): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:323)
E/SQLiteDatabase( 3056): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:64)
E/SQLiteDatabase( 3056): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:207)
E/SQLiteDatabase( 3056): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 3056): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3056): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3056): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Launcher( 1562): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@10f90d62 new=com.google.android.velvet.VelvetApplication@10f90d62
,E/SQLiteLog( 1562): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/PackageBroadcastService( 1927): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1927): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1927): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1927): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1927): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1927): Module APK com.google.android.play.games already loaded
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/LocationSettingsChecker( 1927): Removing dialog suppression flag for package com.example.hello

```
