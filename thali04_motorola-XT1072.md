#### Test 50388019809f971_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311999, SEQNUM=4368, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18529, POWER_SUPPLY_CHARGE_COUNTER=-480, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
D/AndroidRuntime( 4865): 
D/AndroidRuntime( 4865): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4865): CheckJNI is OFF
D/AndroidRuntime( 4865): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (270 us)
W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4865): Shutting down VM
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4884 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 4884): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
--------- beginning of crash
F/libc    ( 4865): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb4f6c010 in tid 4882 (Binder_2)
,E/DEBUG   (  292): unexpected waitpid response: n=4882, status=00000001
E/        (  292): ptrace detach from 4882 failed: No such process
,E/        (  292): debuggerd committing suicide to free the zombie!
,I/        ( 4901): debuggerd: Jan  6 2015 18:21:45
,I/LibraryLoader( 4884): Time to load native libraries: 9 ms (timestamps 2951-2960)
I/LibraryLoader( 4884): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4884): Binding Chromium to main looper Looper (main, tid 1) {29e2080}
,I/LibraryLoader( 4884): Expected native library version number "",actual native library version number ""
I/chromium( 4884): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4884): Initializing chromium process, singleProcess=true
W/art     ( 4884): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4884): ApplicationContext is null in ApplicationStatus
,W/chromium( 4884): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4884): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4884): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4884): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4884): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4884): Local Branch: 
I/Adreno-EGL( 4884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4884): Local Patches: NONE
I/Adreno-EGL( 4884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14951422:true
,D/BluetoothAdapter( 4884): 955791626: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 4884): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4884): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4884): CordovaWebView is running on device made by: motorola
,W/art     ( 4884): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4884): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4884): Render dirty regions requested: true
,D/Atlas   ( 4884): Validating map...
,W/chromium( 4884): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:253 vsyncs) (45:1057)
,I/OpenGLRenderer( 4884): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4884): Enabling debug mode 0
,I/LaunchCheckinHandler(  883): Displayed com.example.hello/.MainActivity,cp,ca,945
I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +945ms
,I/Keyboard.Facilitator( 1411): onFinishInput()
,E/Adreno-ES20( 4884): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4884): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4884): Cannot call determinedVisibility() - never saw a connection for the pid: 4884
,I/chromium( 4884): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4884): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4884): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Adreno-ES20( 4884): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4884): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 4884): JniHelper::setJavaVM(0xb733c310), pthread_self() = -1217813224
,D/JX-Cordova( 4884): jxcore cordova android initializing
,W/jxcore-log( 4884): Initializing JXcore engine
W/jxcore-log( 4884): JXcore engine is ready
,W/jxcore-log( 4884): Starting JXcore engine
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
D/        (  883): BstSensorExt: id=1598182242, en=0
,D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb6fe3550
D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  883): Display changed displayId=0
,W/m.example.hello( 4884): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10333 path="socket:[6546]" dev="sockfs" ino=6546 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4884): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10333 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 4884): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10333 path="socket:[9469]" dev="sockfs" ino=9469 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4884): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10333 path="socket:[21947]" dev="sockfs" ino=21947 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c94820
,I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211545464)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211545464) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7c94820
,W/jxcore-log( 4884): Platform android
W/jxcore-log( 4884): 
,W/jxcore-log( 4884): Process ARCH arm
W/jxcore-log( 4884): 
,I/jxcore-log( 4884): JXcore Cordova bridge is ready!
I/jxcore-log( 4884): 
W/jxcore-log( 4884): JXcore engine is started
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
I/SFPerfTracer(  280):      triggers: (rate: 15:473) (compose: 0:1) (post: 0:2) (render: 0:4) (19:1023 frames) (20:1116)
D/SFPerfTracer(  280):        layers: (4:12) (FocusedStackFrame (0xb70995c0): 0:14)* (StatusBar (0xb706bac0): 0:140) (NavigationBar (0xb706f948): 0:23) (com.android.systemui.ImageWallpaper (0xb70f9658): 0:36)* (DimLayer (0xb70febf8): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb711e7b8): 0:57)- (Starting com.example.hello (0xb711d528): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb7118368): 8:38) (ColorFade (0xb711e7b8): 19:21) 
D/SurfaceControl(  883): Excessive delay in setPowerMode(): 328ms
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,I/WindowManager(  883): AOD feature not enabled!
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ProcessCpuTracker(  883): Skipping unknown process pid 4950
,W/ProcessCpuTracker(  883): Skipping unknown process pid 4951
W/ProcessCpuTracker(  883): Skipping unknown process pid 4953
W/ProcessCpuTracker(  883): Skipping unknown process pid 4955
,E/jxcore-log( 4884): >> motorola-XT1072
E/jxcore-log( 4884): 
I/jxcore-log( 4884): Total memory 916258816
I/jxcore-log( 4884): 
I/jxcore-log( 4884): Free memory 34258944
I/jxcore-log( 4884): 
I/jxcore-log( 4884): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4884): 
I/jxcore-log( 4884): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4884): 
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2ddc89c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb733c310, mCls = 0x1017ea
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,I/jxcore-log( 4884): userPath [ 'www' ]
I/jxcore-log( 4884): 
E/WifiStateMachine(  883): setSuspendOptimizations: 4 false
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 4
,I/jxcore-log( 4884): Size 720 1184
I/jxcore-log( 4884): 
,I/jxcore-log( 4884): Screen Brightness 82
I/jxcore-log( 4884): 
E/jxcore-log( 4884): Dummy Error Log.
E/jxcore-log( 4884): 
,D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2ddc89c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb733c310, mCls = 0x101786
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
,I/Keyboard.Facilitator( 1411): onFinishInput()
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 true
E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,I/jxcore-log( 4884): getBuffer is called!!!!
I/jxcore-log( 4884): 
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  883): send {274d4464, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  883): done {274d4464, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  883): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  883): Message: 2
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: false pid=4884, uid=10333
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4884): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 4884): 
I/jxcore-log( 4884): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4884): 
,D/AndroidRuntime( 4987): 
D/AndroidRuntime( 4987): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4987): CheckJNI is OFF
,D/AndroidRuntime( 4987): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 4884:com.example.hello/u0a333 (adj 0): stop com.example.hello
,I/WindowState(  883): WIN DEATH: Window{108ec9d2 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,W/PackageSettings(  883): Skipping PackageSetting{e1280b3 com.test.thalitest/10332} due to missing metadata
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{2ac195e6 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  883): Display changed displayId=0
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  883): Spurious death for ProcessRecord{1014c6cd 4884:com.example.hello/u0a333}, curProc for 4884: null
,W/ContextImpl( 1451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  883): Force stopping com.example.hello appid=10333 user=0: pkg removed
,D/OtaApp  ( 2600): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2600): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2600): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2600): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2600): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,D/Checkin ( 2600): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1411): resetDictionaries() : en_US
,D/VoicemailCleanupService( 4599): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator.DecoderInitializer( 1411): run()
,I/Decoder ( 1411): createOrResetDecoder
,I/art     ( 1560): Explicit concurrent mark sweep GC freed 7316(532KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 563us total 137.426ms
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5017 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1621): onCreate
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.422ms
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 4884 uid 10333
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 23.894ms
,I/art     (  883): Explicit concurrent mark sweep GC freed 16535(1181KB) AllocSpace objects, 5(243KB) LOS objects, 33% free, 20MB/30MB, paused 2.750ms total 196.010ms
,I/art     (  883): WaitForGcToComplete blocked for 112.134ms for cause Explicit
,W/asset   ( 5017): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5017): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5017): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5017): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.762ms
,E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15b093a1)
,E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18b019c6)
E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1ff97d87)
,E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ee3c4b4)
I/art     ( 1621): Explicit concurrent mark sweep GC freed 17765(1459KB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 11MB/18MB, paused 1.714ms total 57.266ms
E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421c8dd)
E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5840c52)
E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e666b23)
E/DataBuffer( 1621): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36527820)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): run()
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5042 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = contacts
,I/ActivityManager(  883): Killing 4700:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1411): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1411): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1411): run()
I/StatsUtilsManager( 1411): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1411): shouldRecordStats() = Too Soon
,I/art     (  883): Explicit concurrent mark sweep GC freed 5367(268KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.804ms total 183.182ms
,D/AndroidRuntime( 4987): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_4700/cgroup.procs: No such file or directory
,I/Launcher( 1560): Deferring update until onResume
,W/ContextImpl( 5042): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5064 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  883): Killing 4746:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_4746/cgroup.procs: No such file or directory
,W/Launcher( 1560): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@38f8390a new=com.google.android.velvet.VelvetApplication@38f8390a
,E/SQLiteLog( 1560): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/PackageBroadcastService( 1940): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1940): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1940): Removing dialog suppression flag for package com.example.hello
,E/SQLiteLog( 1940): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1621): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
,D/AndroidRuntime( 1621): Shutting down VM
,E/AndroidRuntime( 1621): FATAL EXCEPTION: main
E/AndroidRuntime( 1621): Process: com.google.process.gapps, PID: 1621
E/AndroidRuntime( 1621): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1621): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1621): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1621): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1621): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1621): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1621): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1621): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1621): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1621): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1621): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1621): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1621): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1621): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1621): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1621): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1621): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1621): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1621): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1621): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1621): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1621): 	... 9 more
,E/SQLiteLog( 1940): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 1940): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1940): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1940): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1940): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1940): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1940): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/DriveAsyncService( 1940): disk I/O error (code 3850)
E/DriveAsyncService( 1940): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1940): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1940): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1940): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1940): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1940): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1940): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1940): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1940): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 1940): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1940): Process: com.google.android.gms, PID: 1940
E/AndroidRuntime( 1940): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1940): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1940): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1940): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1940): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1940): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1940): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1940): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1940): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1940): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1940): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1940): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1940): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1940): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1940): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  883): Process com.google.android.gms has crashed too many times: killing!
E/DropBoxManagerService(  883): Can't write: system_app_crash
E/DropBoxManagerService(  883): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  883): Killing 1940:com.google.android.gms/u0a16 (adj 5): crash
E/DropBoxManagerService(  883): Can't write: system_app_crash
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
,D/ConnectivityService(  883): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d54d584)
D/ConnectivityService(  883): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  883): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
W/ActivityManager(  883): Spurious death for ProcessRecord{b6638c9 1940:com.google.android.gms/u0a16}, curProc for 1940: null
I/Process ( 1621): Sending signal. PID: 1621 SIG: 9
E/MP-Decision( 2141): Error(-22) changing core 3 status to online

```
