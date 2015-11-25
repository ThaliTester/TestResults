#### Test 503880196dc97cd_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
D/AndroidRuntime( 4764): 
D/AndroidRuntime( 4764): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4764): CheckJNI is OFF
D/AndroidRuntime( 4764): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (158 us)
W/ContextImpl( 1449): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4764): Shutting down VM
I/ActivityManager(  880): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4783 uid=10329 gids={50329, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 23.568ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.514ms
W/ContextImpl( 1449): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 21.981ms
,I/WebViewFactory( 4783): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4783): Time to load native libraries: 3 ms (timestamps 7395-7398)
I/LibraryLoader( 4783): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4783): Binding Chromium to main looper Looper (main, tid 1) {3da00125}
I/LibraryLoader( 4783): Expected native library version number "",actual native library version number ""
I/chromium( 4783): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4783): Initializing chromium process, singleProcess=true
W/art     ( 4783): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4783): ApplicationContext is null in ApplicationStatus
W/chromium( 4783): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4783): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4783): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4783): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4783): Local Branch: 
I/Adreno-EGL( 4783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4783): Local Patches: NONE
I/Adreno-EGL( 4783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d79f80:true
D/BluetoothAdapter( 4783): 233819271: getState() :  mService = null. Returning STATE_OFF
V/AlarmManager(  880): send {37410948, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): done {37410948, *alarm*:android.intent.action.TIME_TICK} [22ms]
W/art     ( 4783): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4783): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4783): CordovaWebView is running on device made by: motorola
W/art     ( 4783): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4783): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 4783): Render dirty regions requested: true
D/Atlas   ( 4783): Validating map...
W/chromium( 4783): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 4783): Initialized EGL, version 1.4
D/OpenGLRenderer( 4783): Enabling debug mode 0
I/LaunchCheckinHandler(  880): Displayed com.example.hello/.MainActivity,cp,ca,971
I/ActivityManager(  880): Displayed com.example.hello/.MainActivity: +971ms
I/Keyboard.Facilitator( 1406): onFinishInput()
,E/Adreno-ES20( 4783): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4783): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4783): Cannot call determinedVisibility() - never saw a connection for the pid: 4783
,I/chromium( 4783): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4783): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4783): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 4783): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4783): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 4783): JniHelper::setJavaVM(0xb75be310), pthread_self() = -1215170720
,D/JX-Cordova( 4783): jxcore cordova android initializing
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (41:241 vsyncs) (43:975)
,I/SFPerfTracer(  280):      triggers: (rate: 12:548) (compose: 0:2) (post: 0:1) (render: 0:2) (29:877 frames) (30:974)
,D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb71c9f50): 0:17)* (StatusBar (0xb71a1308): 0:103) (NavigationBar (0xb71a36f8): 0:20) (com.android.systemui.ImageWallpaper (0xb7182b58): 0:8)* (DimLayer (0xb7186c18): 0:7)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb71d5738): 0:56)- (Starting com.example.hello (0xb7189008): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb71930b8): 30:35) 
,W/jxcore-log( 4783): Initializing JXcore engine
W/jxcore-log( 4783): JXcore engine is ready
,W/jxcore-log( 4783): Starting JXcore engine
,W/m.example.hello( 4783): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10329 path="socket:[9283]" dev="sockfs" ino=9283 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4783): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10329 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3091 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 4783): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10329 path="socket:[6537]" dev="sockfs" ino=6537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4783): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10329 path="socket:[20897]" dev="sockfs" ino=20897 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4783): Platform android
W/jxcore-log( 4783): 
W/jxcore-log( 4783): Process ARCH arm
W/jxcore-log( 4783): 
,I/jxcore-log( 4783): JXcore Cordova bridge is ready!
I/jxcore-log( 4783): 
,W/jxcore-log( 4783): JXcore engine is started
,E/jxcore-log( 4783): >> motorola-XT1072
E/jxcore-log( 4783): 
,I/jxcore-log( 4783): Total memory 916258816
I/jxcore-log( 4783): 
,I/jxcore-log( 4783): Free memory 35004416
I/jxcore-log( 4783): 
,I/jxcore-log( 4783): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4783): 
I/jxcore-log( 4783): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4783): 
,I/jxcore-log( 4783): userPath [ 'www' ]
I/jxcore-log( 4783): 
,I/jxcore-log( 4783): Size 720 1184
I/jxcore-log( 4783): 
,I/jxcore-log( 4783): Screen Brightness 82
I/jxcore-log( 4783): 
,E/jxcore-log( 4783): Dummy Error Log.
E/jxcore-log( 4783): 
,I/jxcore-log( 4783): getBuffer is called!!!!
I/jxcore-log( 4783): 
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task_thumbnail.png
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
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  880): Message: 2
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: false pid=4783, uid=10329
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/PowerManagerService(  880): Nap time (uid 1000)...
I/PowerManagerService(  880): Going to sleep due to screen timeout (uid 1000)...
,I/jxcore-log( 4783): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 4783): 
,I/jxcore-log( 4783): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4783): 
,I/Adreno-EGL(  880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  880): Build Date: 10/28/14 Tue
I/Adreno-EGL(  880): Local Branch: 
I/Adreno-EGL(  880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  880): Local Patches: NONE
I/Adreno-EGL(  880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/AndroidRuntime( 4883): 
D/AndroidRuntime( 4883): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4883): CheckJNI is OFF
,D/AndroidRuntime( 4883): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.example.hello appid=10329 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 4783:com.example.hello/u0a329 (adj 0): stop com.example.hello
,D/        (  880): activate, handle: 1598182242, enabled: 0, index 2
D/        (  880): BstSensorExt: id=1598182242, en=0
D/        (  880): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  880): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  880): Display changed displayId=0
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb709b550
D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,I/WindowState(  880): WIN DEATH: Window{27d1e8b0 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
,W/PackageSettings(  880): Skipping PackageSetting{1ecfd20c com.test.thalitest/10328} due to missing metadata
,W/ActivityManager(  880): Force removing ActivityRecord{2cc30be4 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,W/ContextImpl( 1449): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  880): Spurious death for ProcessRecord{39461647 4783:com.example.hello/u0a329}, curProc for 4783: null
I/ActivityManager(  880): Force stopping com.example.hello appid=10329 user=0: pkg removed
,I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1705): Ignoring removeGeofence because network location is disabled.
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f89820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1208445640)
,D/VoicemailCleanupService( 4500): Cleaning up data for package: com.example.hello
,I/art     ( 2948): Explicit concurrent mark sweep GC freed 9080(1512KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 7MB/12MB, paused 818us total 41.056ms
,I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
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
,I/Decoder ( 1406): createOrResetDecoder
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4914 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1555): Explicit concurrent mark sweep GC freed 7321(532KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 857us total 101.877ms
,I/ConfigService( 1605): onCreate
,W/asset   ( 4914): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 4914): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 4914): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4914): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1208445640) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/art     (  880): Explicit concurrent mark sweep GC freed 10859(876KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.869ms total 161.752ms
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7f89820
,I/art     (  880): WaitForGcToComplete blocked for 98.011ms for cause Explicit
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
D/SurfaceControl(  880): Excessive delay in setPowerMode(): 326ms
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/OtaApp  ( 2547): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2547): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2547): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
D/OtaApp  ( 2547): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2547): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2547): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  880): send {2089aeb5, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,W/InputMethodManagerService(  880): Got RemoteException sending setActive(false) notification to pid 4783 uid 10329
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
,I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4939 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/WindowManager(  880): AOD feature not enabled!
,D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,W/ContextImpl( 1449): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  880): Killing 4599:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/art     (  880): Explicit concurrent mark sweep GC freed 6432(358KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.548ms total 218.105ms
,D/AndroidRuntime( 4883): Shutting down VM
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4599/cgroup.procs: No such file or directory
,I/Launcher( 1555): Deferring update until onResume
,D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
E/msm8974_platform(  297): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e2c89c
,D/wifi    (  880): halHandle = 0x0, mVM = 0xb75be310, mCls = 0x1018b6
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  880): setSuspendOptimizations: 4 false
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 4
,W/ContextImpl( 4939): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4959 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 4642:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_4642/cgroup.procs: No such file or directory
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e2c89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb75be310, mCls = 0x2017ee
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
D/audio_hw_primary(  297): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  297): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  297): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  297): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  880): setSuspendOptimizations: 4 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
I/Keyboard.Facilitator( 1406): onFinishInput()
,W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@defcc87 new=com.google.android.velvet.VelvetApplication@defcc87
,D/PackageBroadcastService( 1942): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1942): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1942): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1942): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/NetworkScheduler.SchedulerReceiver( 1605): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1605): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1942): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1942): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1942): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4984 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 1942): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1942): Module APK com.google.android.play.games already loaded
,I/PeopleContactsSync( 1942): CP2 sync disabled
,I/Icing   ( 1942): doRemovePackageData com.example.hello
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
