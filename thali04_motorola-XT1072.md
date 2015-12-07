#### Test 502422852e23b2c_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,I/PowerManagerService(  881): Nap time (uid 1000)...
I/PowerManagerService(  881): Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
I/Adreno-EGL(  881): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  881): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  881): Build Date: 10/28/14 Tue
I/Adreno-EGL(  881): Local Branch: 
I/Adreno-EGL(  881): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  881): Local Patches: NONE
I/Adreno-EGL(  881): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (184 us)
D/AndroidRuntime( 4972): 
D/AndroidRuntime( 4972): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4972): CheckJNI is OFF
D/AndroidRuntime( 4972): Calling main entry com.android.commands.am.Am
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4972): Shutting down VM
D/        (  881): activate, handle: 1598182242, enabled: 0, index 2
D/        (  881): BstSensorExt: id=1598182242, en=0
D/        (  881): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 228
I/SFPerfTracer(  279):      triggers: (rate: 13:581) (compose: 0:2) (post: 0:1) (render: 0:2) (18:822 frames) (19:904)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb7153698): 0:10)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7190350): 0:46)- (StatusBar (0xb7194640): 0:111) (NavigationBar (0xb716b908): 0:25) (com.android.systemui.ImageWallpaper (0xb716d620): 0:8)* (DimLayer (0xb71e6e70): 0:3)* (Starting com.motorola.ccc.ota (0xb71e8b88): 0:31)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb71ea8a0): 0:28) (ColorFade (0xb7190350): 19:21) 
D/        (  881): activate, handle: 2, enabled: 0, index 5
D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb70b8550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
I/DisplayManagerService(  881): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  881): Display changed displayId=0
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4992 uid=10357 gids={50357, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb829f820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205208952)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205208952) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb829f820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  881): Excessive delay in setPowerMode(): 328ms
,I/WindowManager(  881): AOD feature not enabled!
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/PowerManagerService(  881): Sleeping (uid 1000)...
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/ActivityManager(  881): Display changed displayId=0
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e5289c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb7d76310, mCls = 0x101922
I/WifiNative-HAL(  881): Could not start hal
,D/WifiStateMachine(  881): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 false
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 4
,I/WebViewFactory( 4992): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4992): Time to load native libraries: 2 ms (timestamps 5472-5474)
I/LibraryLoader( 4992): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4992): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 4992): Expected native library version number "",actual native library version number ""
,I/chromium( 4992): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4992): Initializing chromium process, singleProcess=true
,W/art     ( 4992): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4992): ApplicationContext is null in ApplicationStatus
,W/chromium( 4992): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4992): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4992): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4992): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4992): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4992): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4992): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4992): Local Branch: 
I/Adreno-EGL( 4992): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4992): Local Patches: NONE
I/Adreno-EGL( 4992): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@350cfebc:true
,D/BluetoothAdapter( 4992): 174437516: getState() :  mService = null. Returning STATE_OFF
,D/        (  881): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  881): <BST> disable accel, orig state: 1
I/        (  881): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e5289c
,D/wifi    (  881): halHandle = 0x0, mVM = 0xb7d76310, mCls = 0x1832
I/WifiNative-HAL(  881): Could not start hal
D/WifiStateMachine(  881): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: false
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 true
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 0
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{1197da8c u0 com.example.hello/.MainActivity t3}
,W/art     ( 4992): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4992): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4992): CordovaWebView is running on device made by: motorola
,W/art     ( 4992): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4992): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4992): Render dirty regions requested: true
,D/Atlas   ( 4992): Validating map...
,W/chromium( 4992): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4992): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4992): Enabling debug mode 0
,I/Keyboard.Facilitator( 1404): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.example.hello/.MainActivity,cp,ca,1152
,W/IInputConnectionWrapper( 4992): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4992): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4992): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4992): Cannot call determinedVisibility() - never saw a connection for the pid: 4992
,I/chromium( 4992): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4992): Set native->JS mode to OnlineEventsBridgeMode
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,E/AndroidProtocolHandler( 4992): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 4992): JniHelper::setJavaVM(0xb7d76310), pthread_self() = -1206877632
,D/JX-Cordova( 4992): jxcore cordova android initializing
,W/jxcore-log( 4992): Initializing JXcore engine
W/jxcore-log( 4992): JXcore engine is ready
,W/jxcore-log( 4992): Starting JXcore engine
,W/m.example.hello( 4992): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10357 path="socket:[9741]" dev="sockfs" ino=9741 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4992): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10357 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4992): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10357 path="socket:[8701]" dev="sockfs" ino=8701 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4992): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10357 path="socket:[20960]" dev="sockfs" ino=20960 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4992): Platform android
W/jxcore-log( 4992): 
W/jxcore-log( 4992): Process ARCH arm
W/jxcore-log( 4992): 
,I/jxcore-log( 4992): JXcore Cordova bridge is ready!
I/jxcore-log( 4992): 
,W/jxcore-log( 4992): JXcore engine is started
,E/jxcore-log( 4992): >> motorola-XT1072
E/jxcore-log( 4992): 
,I/jxcore-log( 4992): Total memory 916258816
I/jxcore-log( 4992): 
I/jxcore-log( 4992): Free memory 34631680
I/jxcore-log( 4992): 
,I/jxcore-log( 4992): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4992): 
,I/jxcore-log( 4992): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4992): 
,I/jxcore-log( 4992): userPath [ 'www' ]
I/jxcore-log( 4992): 
I/jxcore-log( 4992): Size 720 1184
I/jxcore-log( 4992): 
I/jxcore-log( 4992): Screen Brightness 82
I/jxcore-log( 4992): 
,E/jxcore-log( 4992): Dummy Error Log.
E/jxcore-log( 4992): 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/jxcore-log( 4992): getBuffer is called!!!!
I/jxcore-log( 4992): 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task_thumbnail.png
,V/AlarmManager(  881): send {2079b197, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  881): done {2079b197, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  881): Message: 2
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: false pid=4992, uid=10357
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4992): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 4992): 
I/jxcore-log( 4992): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4992): 
,D/AndroidRuntime( 5076): 
D/AndroidRuntime( 5076): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5076): CheckJNI is OFF
,D/AndroidRuntime( 5076): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.example.hello appid=10357 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 4992:com.example.hello/u0a357 (adj 0): stop com.example.hello
,I/WindowState(  881): WIN DEATH: Window{27eb8eec u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,W/PackageSettings(  881): Skipping PackageSetting{62c8e4d com.test.thalitest/10356} due to missing metadata
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{1197da8c u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  881): Spurious death for ProcessRecord{19b6cf84 4992:com.example.hello/u0a357}, curProc for 4992: null
,I/ActivityManager(  881): Force stopping com.example.hello appid=10357 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{1197da8c u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{1197da8c u0 com.example.hello/.MainActivity t3 f}
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/GeofencerStateMachine( 1711): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1404): resetDictionaries() : en_US
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,D/OtaApp  ( 2774): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2774): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2774): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2774): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2774): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2774): publish the event [tag = MOT_OTA event name = LOG]
I/Keyboard.Facilitator.DecoderInitializer( 1404): run()
,I/Decoder ( 1404): createOrResetDecoder
,D/VoicemailCleanupService( 4849): Cleaning up data for package: com.example.hello
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5105 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1557): Explicit concurrent mark sweep GC freed 7346(534KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 482us total 143.478ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.933ms
,I/ConfigService( 1614): onCreate
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.908ms
,W/InputMethodManagerService(  881): Got RemoteException sending setActive(false) notification to pid 4992 uid 10357
I/art     (  881): Explicit concurrent mark sweep GC freed 15485(1128KB) AllocSpace objects, 5(248KB) LOS objects, 33% free, 20MB/30MB, paused 2.156ms total 175.888ms
,I/Keyboard.Facilitator( 1404): onFinishInput()
,I/art     (  881): WaitForGcToComplete blocked for 112.067ms for cause Explicit
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.696ms
,W/asset   ( 5105): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5105): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5105): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5105): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1404): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1404): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1404): run()
I/StatsUtilsManager( 1404): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1404): shouldRecordStats() = Too Soon
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5132 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Launcher( 1557): Deferring update until onResume
,I/ActivityManager(  881): Killing 4780:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/art     (  881): Explicit concurrent mark sweep GC freed 5499(302KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.326ms total 175.654ms
,D/AndroidRuntime( 5076): Shutting down VM
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_4780/cgroup.procs: No such file or directory
,W/ContextImpl( 5132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5153 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 4819:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_4819/cgroup.procs: No such file or directory
,W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,E/SQLiteLog( 1557): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1943): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1943): Removing dialog suppression flag for package com.example.hello
,E/SQLiteLog( 1943): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 1614): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,E/SQLiteDatabase( 1943): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1943): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFi,le:68)
E/SQLiteOpenHelper( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1943): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1943): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1943): 	at android.,content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 1943): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1943): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
W/SQLiteOpenHelper( 1943): Opened phenotype.db in read-only mode
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
E/AndroidRuntime( 1943): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1943): Process: com.google.android.gms, PID: 1943
E/AndroidRuntime( 1943): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1943): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1943): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1943): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1943): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1943): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1943): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1943): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1943): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
