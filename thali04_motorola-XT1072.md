#### Test 50242285e707819_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 5123): 
D/AndroidRuntime( 5123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5123): CheckJNI is OFF
D/AndroidRuntime( 5123): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (190 us)
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5123): Shutting down VM
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5142 uid=10358 gids={50358, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5142): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5142): Time to load native libraries: 3 ms (timestamps 7231-7234)
I/LibraryLoader( 5142): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5142): Binding Chromium to main looper Looper (main, tid 1) {1afc2ded}
,I/LibraryLoader( 5142): Expected native library version number "",actual native library version number ""
I/chromium( 5142): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5142): Initializing chromium process, singleProcess=true
,W/art     ( 5142): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5142): ApplicationContext is null in ApplicationStatus
,W/chromium( 5142): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5142): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5142): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5142): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5142): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5142): Local Branch: 
I/Adreno-EGL( 5142): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5142): Local Patches: NONE
I/Adreno-EGL( 5142): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2874388f:true
,D/BluetoothAdapter( 5142): 160374684: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5142): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5142): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5142): CordovaWebView is running on device made by: motorola
,W/art     ( 5142): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5142): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5142): Render dirty regions requested: true
I/SFPerfTracer(  280):      triggers: (rate: 9:245) (compose: 0:1) (post: 0:1) (render: 0:2) (12:1087 frames) (13:1179)
D/SFPerfTracer(  280):        layers: (5:11) (FocusedStackFrame (0xb7f73750): 0:12)* (StatusBar (0xb7ed7370): 0:145) (NavigationBar (0xb7eda5a8): 0:22) (com.android.systemui.ImageWallpaper (0xb7f03418): 0:5)* (DimLayer (0xb7f08d20): 0:6) (Starting com.motorola.ccc.ota (0xb7f0b110): 0:26)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f88870): 0:59) (Starting com.example.hello (0xb7f5d5d0): 13:28) 
,D/Atlas   ( 5142): Validating map...
,W/chromium( 5142): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5142): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5142): Enabling debug mode 0
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.example.hello/.MainActivity,cp,ca,976
,I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +976ms
,E/Adreno-ES20( 5142): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5142): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5142): Cannot call determinedVisibility() - never saw a connection for the pid: 5142
,I/chromium( 5142): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5142): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5142): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 5142): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5142): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/jxcore_app_log( 5142): JniHelper::setJavaVM(0xb8021310), pthread_self() = -1204274544
D/JX-Cordova( 5142): jxcore cordova android initializing
W/jxcore-log( 5142): Initializing JXcore engine
W/jxcore-log( 5142): JXcore engine is ready
W/jxcore-log( 5142): Starting JXcore engine
W/m.example.hello( 5142): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10358 path="socket:[5818]" dev="sockfs" ino=5818 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5142): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10358 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5142): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10358 path="socket:[6593]" dev="sockfs" ino=6593 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5142): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10358 path="socket:[22561]" dev="sockfs" ino=22561 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5142): Platform android
W/jxcore-log( 5142): 
W/jxcore-log( 5142): Process ARCH arm
W/jxcore-log( 5142): 
I/jxcore-log( 5142): JXcore Cordova bridge is ready!
I/jxcore-log( 5142): 
W/jxcore-log( 5142): JXcore engine is started
,E/jxcore-log( 5142): >> motorola-XT1072
E/jxcore-log( 5142): 
,I/jxcore-log( 5142): Total memory 916258816
I/jxcore-log( 5142): 
I/jxcore-log( 5142): Free memory 35405824
I/jxcore-log( 5142): 
I/jxcore-log( 5142): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5142): 
I/jxcore-log( 5142): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5142): 
I/jxcore-log( 5142): userPath [ 'www' ]
I/jxcore-log( 5142): 
,I/jxcore-log( 5142): Size 720 1184
I/jxcore-log( 5142): 
,I/jxcore-log( 5142): Screen Brightness 82
I/jxcore-log( 5142): 
,E/jxcore-log( 5142): Dummy Error Log.
E/jxcore-log( 5142): 
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:288 vsyncs) (2:1234)
,I/jxcore-log( 5142): getBuffer is called!!!!
I/jxcore-log( 5142): 
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  883): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  883): Message: 2
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: false pid=5142, uid=10358
,E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5142): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 5142): 
I/jxcore-log( 5142): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5142): 
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
D/        (  883): BstSensorExt: id=1598182242, en=0
,D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  883): Display changed displayId=0
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb7e4d550
,D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,D/AndroidRuntime( 5230): 
D/AndroidRuntime( 5230): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5230): CheckJNI is OFF
I/rmt_storage(  291): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7103820
I/rmt_storage(  291): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  291): wakelock acquired: 1, error no: 42
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1223673720)
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1223673720) wakelock released: 1, error no: 0
I/rmt_storage(  291): 
,I/rmt_storage(  291): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7103820
,D/AndroidRuntime( 5230): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.example.hello appid=10358 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 5142:com.example.hello/u0a358 (adj 0): stop com.example.hello
,I/WindowState(  883): WIN DEATH: Window{211a637f u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
,I/SFPerfTracer(  280):       trigger: frame rate (-28.754%)	(42.747 fps)	(23.393 ms) 	(3 drops)	(15 frames)
I/SFPerfTracer(  280):      triggers: (rate: 10:251) (compose: 0:1) (post: 0:1) (render: 0:2) (15:1156 frames) (16:1265)
D/SFPerfTracer(  280):        layers: (4:12) (FocusedStackFrame (0xb7f73750): 0:15)* (StatusBar (0xb7ed7370): 0:145) (NavigationBar (0xb7eda5a8): 0:22) (com.android.systemui.ImageWallpaper (0xb7f03418): 0:5)* (DimLayer (0xb7f08d20): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f88870): 0:60)- (Starting com.example.hello (0xb7f5d5d0): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb7f5ea20): 0:56) (ColorFade (0xb7f5d5d0): 16:18) 
,D/SurfaceControl(  883): Excessive delay in setPowerMode(): 309ms
,W/PackageSettings(  883): Skipping PackageSetting{1246c6f4 com.test.thalitest/10356} due to missing metadata
,I/WindowManager(  883): AOD feature not enabled!
,W/ActivityManager(  883): Force removing ActivityRecord{39928c43 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  883): Spurious death for ProcessRecord{12093f02 5142:com.example.hello/u0a358}, curProc for 5142: null
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,I/ActivityManager(  883): Force stopping com.example.hello appid=10358 user=0: pkg removed
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/ActivityManager(  883): Display changed displayId=0
,W/GeofencerStateMachine( 1755): Ignoring removeGeofence because network location is disabled.
I/art     ( 3100): Explicit concurrent mark sweep GC freed 8747(1462KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 895us total 49.025ms
,D/OtaApp  ( 2694): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2694): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
,D/Checkin ( 2694): publish the event [tag = MOT_OTA event name = LOG]
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
,I/Decoder ( 1406): createOrResetDecoder
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5255 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/OtaApp  ( 2694): [debug] > cancelling the previous pending intent set for download later
,I/art     ( 1559): Explicit concurrent mark sweep GC freed 7334(533KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 453us total 128.785ms
,I/OtaApp  ( 2694): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2694): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  883): send {1972eb74, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,I/ConfigService( 1598): onCreate
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 5142 uid 10358
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/art     (  883): Explicit concurrent mark sweep GC freed 13438(993KB) AllocSpace objects, 4(143KB) LOS objects, 33% free, 20MB/30MB, paused 6.850ms total 175.855ms
,I/art     (  883): WaitForGcToComplete blocked for 102.834ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 5255): Cleaning up data for package: com.example.hello
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5284 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
I/ContactLocale( 5255): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  883): Explicit concurrent mark sweep GC freed 4390(250KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 3.515ms total 173.060ms
,D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
E/msm8974_platform(  297): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2de189c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8021310, mCls = 0x201916
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,I/ActivityManager(  883): Killing 5002:com.motorola.context/u0a8 (adj 15): empty #7
E/WifiStateMachine(  883): setSuspendOptimizations: 4 false
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 4
,D/AndroidRuntime( 5230): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_5002/cgroup.procs: No such file or directory
,I/Launcher( 1559): Deferring update until onResume
,W/asset   ( 5284): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5284): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5284): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2de189c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8021310, mCls = 0x2018e2
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  883): setSuspendOptimizations: 4 true
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5302 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 22.505ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.251ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.521ms
,I/ActivityManager(  883): Killing 4900:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/ContextImpl( 5302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_4900/cgroup.procs: No such file or directory
,E/SQLiteDatabase( 5302): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5302): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5302): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5302): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5302): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 5302): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 5302): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5302): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5302): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5302): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
E/AndroidRuntime( 5302): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5302): Process: com.android.keychain, PID: 5302
E/AndroidRuntime( 5302): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5302): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5302): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5302): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5302): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 5302): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 5302): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5302): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5302): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5302): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5326 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Process ( 5302): Sending signal. PID: 5302 SIG: 9
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
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  883): Process com.android.keychain (pid 5302) has died
,W/ActivityManager(  883): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms

```
