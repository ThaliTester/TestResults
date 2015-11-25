#### Test 503880194bce128_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (318 us)
D/AndroidRuntime( 5032): 
D/AndroidRuntime( 5032): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5032): CheckJNI is OFF
D/AndroidRuntime( 5032): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
D/        (  883): BstSensorExt: id=1598182242, en=0
D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 228
D/        (  883): activate, handle: 2, enabled: 0, index 5
D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb8015550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/AndroidRuntime( 5032): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5052 uid=10330 gids={50330, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7aa7820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1213564792)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1213564792) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7aa7820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  883): Excessive delay in setPowerMode(): 330ms
,I/WindowManager(  883): AOD feature not enabled!
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e4b89c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb780a310, mCls = 0x188a
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 false
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 4
,I/WebViewFactory( 5052): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5052): Time to load native libraries: 3 ms (timestamps 5514-5517)
I/LibraryLoader( 5052): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5052): Binding Chromium to main looper Looper (main, tid 1) {3af75713}
,I/LibraryLoader( 5052): Expected native library version number "",actual native library version number ""
I/chromium( 5052): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5052): Initializing chromium process, singleProcess=true
,W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5052): ApplicationContext is null in ApplicationStatus
,W/chromium( 5052): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5052): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5052): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5052): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5052): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5052): Local Branch: 
I/Adreno-EGL( 5052): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5052): Local Patches: NONE
I/Adreno-EGL( 5052): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e4b89c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb780a310, mCls = 0x1856
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 true
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f4f3d67:true
,D/BluetoothAdapter( 5052): 514604890: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{8314877 u0 com.example.hello/.MainActivity t3}
,W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5052): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5052): CordovaWebView is running on device made by: motorola
,W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5052): Render dirty regions requested: true
,D/Atlas   ( 5052): Validating map...
,W/chromium( 5052): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5052): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5052): Enabling debug mode 0
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.example.hello/.MainActivity,cp,ca,1212
,W/IInputConnectionWrapper( 5052): showStatusIcon on inactive InputConnection
,I/SFPerfTracer(  279):      triggers: (rate: 13:546) (compose: 0:1) (post: 0:1) (render: 0:2) (0:877 frames) (1:964)
D/SFPerfTracer(  279):        layers: (0:14) (FocusedStackFrame (0xb8146db0): 1:12)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb812deb8): 0:46)- (StatusBar (0xb809dac0): 0:103)* (NavigationBar (0xb80a17b0): 0:21)* (com.android.systemui.ImageWallpaper (0xb8134950): 0:34)* (DimLayer (0xb813a1f8): 0:3)* (Starting com.motorola.ccc.ota (0xb814f658): 0:25)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8150fc0): 0:25)- (ColorFade (0xb812deb8): 0:23)* (Starting com.example.hello (0xb814f658): 1:7)* (com.example.hello/com.example.hello.MainActivity (0xb8150fc0): 1:2)* 
,E/Adreno-ES20( 5052): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5052): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5052): Cannot call determinedVisibility() - never saw a connection for the pid: 5052
,I/chromium( 5052): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5052): Set native->JS mode to OnlineEventsBridgeMode
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,E/AndroidProtocolHandler( 5052): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5052): JniHelper::setJavaVM(0xb780a310), pthread_self() = -1212568520
D/JX-Cordova( 5052): jxcore cordova android initializing
,W/jxcore-log( 5052): Initializing JXcore engine
W/jxcore-log( 5052): JXcore engine is ready
,W/jxcore-log( 5052): Starting JXcore engine
,W/m.example.hello( 5052): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10330 path="socket:[5843]" dev="sockfs" ino=5843 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 5052): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10330 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5052): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10330 path="socket:[5971]" dev="sockfs" ino=5971 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5052): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10330 path="socket:[19282]" dev="sockfs" ino=19282 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5052): Platform android
W/jxcore-log( 5052): 
W/jxcore-log( 5052): Process ARCH arm
W/jxcore-log( 5052): 
,I/jxcore-log( 5052): JXcore Cordova bridge is ready!
I/jxcore-log( 5052): 
,W/jxcore-log( 5052): JXcore engine is started
,E/jxcore-log( 5052): >> motorola-XT1072
E/jxcore-log( 5052): 
,I/jxcore-log( 5052): Total memory 916258816
I/jxcore-log( 5052): 
I/jxcore-log( 5052): Free memory 33542144
I/jxcore-log( 5052): 
I/jxcore-log( 5052): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5052): 
I/jxcore-log( 5052): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5052): 
,I/jxcore-log( 5052): userPath [ 'www' ]
I/jxcore-log( 5052): 
,I/jxcore-log( 5052): Size 720 1184
I/jxcore-log( 5052): 
,I/jxcore-log( 5052): Screen Brightness 82
I/jxcore-log( 5052): 
E/jxcore-log( 5052): Dummy Error Log.
E/jxcore-log( 5052): 
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/jxcore-log( 5052): getBuffer is called!!!!
I/jxcore-log( 5052): 
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task_thumbnail.png
,V/AlarmManager(  883): send {26541fae, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  883): done {26541fae, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  883): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  883): Message: 2
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: false pid=5052, uid=10330
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5052): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 5052): 
I/jxcore-log( 5052): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5052): 
,D/AndroidRuntime( 5146): 
D/AndroidRuntime( 5146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5146): CheckJNI is OFF
,D/AndroidRuntime( 5146): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.example.hello appid=10330 user=-1: uninstall pkg
,I/ActivityManager(  883): Killing 5052:com.example.hello/u0a330 (adj 0): stop com.example.hello
,I/WindowState(  883): WIN DEATH: Window{10c4e57 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  883): Client connection lost with reason: 4
,W/PackageSettings(  883): Skipping PackageSetting{3aa90e72 com.test.thalitest/10328} due to missing metadata
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{8314877 u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  883): Spurious death for ProcessRecord{220cb14f 5052:com.example.hello/u0a330}, curProc for 5052: null
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  883): Force stopping com.example.hello appid=10330 user=0: pkg removed
,I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 2699): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2699): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2699): publish the event [tag = MOT_OTA event name = LOG]
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
,I/Decoder ( 1413): createOrResetDecoder
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5176 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2699): [debug] > cancelling the previous pending intent set for download later
,D/VoicemailCleanupService( 4798): Cleaning up data for package: com.example.hello
,I/art     ( 1559): Explicit concurrent mark sweep GC freed 3678(245KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 478us total 122.586ms
,I/OtaApp  ( 2699): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2699): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1616): onCreate
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 5052 uid 10330
,I/Keyboard.Facilitator( 1413): onFinishInput()
,W/asset   ( 5176): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5176): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5176): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5176): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  883): Explicit concurrent mark sweep GC freed 16419(1162KB) AllocSpace objects, 5(245KB) LOS objects, 33% free, 20MB/30MB, paused 2.275ms total 210.346ms
,I/art     (  883): WaitForGcToComplete blocked for 111.398ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5201 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  883): Killing 4882:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/Launcher( 1559): Deferring update until onResume
,I/art     (  883): Explicit concurrent mark sweep GC freed 4838(254KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.661ms total 149.789ms
,D/AndroidRuntime( 5146): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_4882/cgroup.procs: No such file or directory
,D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,W/ContextImpl( 5201): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5219 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 4918:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_4918/cgroup.procs: No such file or directory
,W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@289e4305 new=com.google.android.velvet.VelvetApplication@289e4305
,D/PackageBroadcastService( 1942): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1942): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1942): Removing dialog suppression flag for package com.example.hello
,E/SQLiteLog( 1616): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 1616): Shutting down VM
,E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
,--------- beginning of crash
E/AndroidRuntime( 1616): FATAL EXCEPTION: main
E/AndroidRuntime( 1616): Process: com.google.process.gapps, PID: 1616
E/AndroidRuntime( 1616): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1616): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1616): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1616): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1616): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1616): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1616): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1616): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1616): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1616): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1616): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1616): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1616): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1616): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1616): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1616): 	... 9 more
,E/SQLiteDatabase( 1942): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
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
E/SQLiteDatabase( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1942): Couldn't open phenotype.db for writing (will try read-only):
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
E/SQLiteOpenHelper( 1942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFi,le:68)
E/SQLiteOpenHelper( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 1942): Opened phenotype.db in read-only mode
,E/SQLiteDatabase( 1942): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
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
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1942): Couldn't open metrics.db for writing (will try read-only):
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
E/SQLiteOpenHelper( 1942): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1942): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/Process ( 1616): Sending signal. PID: 1616 SIG: 9
,W/SQLiteOpenHelper( 1942): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/DropBoxManagerService(  883): Can't write: system_app_crash
E/DropBoxManagerService(  883): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  883): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  883): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  883): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  883): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  883): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  883): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  883): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  883): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  883): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  883): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  883): 	... 5 more
E/SQLiteLog( 1942): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1942): Sending signal. PID: 1942 SIG: 9
,D/ConnectivityService(  883): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@15b004c9)
D/ConnectivityService(  883): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  883): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiService(  883): Client connection lost with reason: 4
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
