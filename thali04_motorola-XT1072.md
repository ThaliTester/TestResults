#### Test 503880196b4ec73_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
--------- beginning of system
D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311518, SEQNUM=4339, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15224, POWER_SUPPLY_CHARGE_COUNTER=-510, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
D/AndroidRuntime( 4938): 
D/AndroidRuntime( 4938): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4938): CheckJNI is OFF
D/AndroidRuntime( 4938): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  281): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (142 us)
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4938): Shutting down VM
I/ActivityManager(  884): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4954 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 4954): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4954): Time to load native libraries: 2 ms (timestamps 2948-2950)
,I/LibraryLoader( 4954): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4954): Binding Chromium to main looper Looper (main, tid 1) {131e6d8d}
,I/LibraryLoader( 4954): Expected native library version number "",actual native library version number ""
,I/chromium( 4954): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4954): Initializing chromium process, singleProcess=true
,W/art     ( 4954): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4954): ApplicationContext is null in ApplicationStatus
,W/chromium( 4954): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4954): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4954): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4954): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4954): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4954): Local Branch: 
I/Adreno-EGL( 4954): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4954): Local Patches: NONE
I/Adreno-EGL( 4954): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  884): Message: 20
,D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1be55e2c:true
,D/BluetoothAdapter( 4954): 454120841: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 4954): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4954): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4954): CordovaWebView is running on device made by: motorola
,W/art     ( 4954): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4954): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4954): Render dirty regions requested: true
,D/Atlas   ( 4954): Validating map...
,W/chromium( 4954): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4954): Initialized EGL, version 1.4
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:168 vsyncs) (45:1019)
,D/OpenGLRenderer( 4954): Enabling debug mode 0
,I/LaunchCheckinHandler(  884): Displayed com.example.hello/.MainActivity,cp,ca,924
,I/ActivityManager(  884): Displayed com.example.hello/.MainActivity: +924ms
,I/Keyboard.Facilitator( 1412): onFinishInput()
,E/Adreno-ES20( 4954): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4954): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4954): Cannot call determinedVisibility() - never saw a connection for the pid: 4954
,I/chromium( 4954): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4954): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4954): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,I/SFPerfTracer(  281):      triggers: (rate: 12:426) (compose: 0:1) (post: 0:1) (render: 0:2) (29:969 frames) (30:1063)
D/SFPerfTracer(  281):        layers: (3:11) (FocusedStackFrame (0xb7fc7198): 0:17)* (StatusBar (0xb7f43ac0): 0:80) (NavigationBar (0xb7f45c58): 0:22) (com.android.systemui.ImageWallpaper (0xb7fb7bb8): 0:8)* (DimLayer (0xb7fbc550): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7ff6968): 0:56)- (Starting com.example.hello (0xb7fd8df0): 0:39)- (com.example.hello/com.example.hello.MainActivity (0xb7fbe940): 30:34) 
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Adreno-ES20( 4954): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4954): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 4954): JniHelper::setJavaVM(0xb723e310), pthread_self() = -1218837976
D/JX-Cordova( 4954): jxcore cordova android initializing
,W/jxcore-log( 4954): Initializing JXcore engine
W/jxcore-log( 4954): JXcore engine is ready
,W/jxcore-log( 4954): Starting JXcore engine
,W/m.example.hello( 4954): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10317 path="socket:[9815]" dev="sockfs" ino=9815 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4954): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10317 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4954): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10317 path="socket:[9951]" dev="sockfs" ino=9951 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4954): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10317 path="socket:[18349]" dev="sockfs" ino=18349 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
D/        (  884): BstSensorExt: id=1598182242, en=0
,D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 222
,D/        (  884): activate, handle: 2, enabled: 0, index 5
D/SurfaceFlinger(  281): Set power mode=0, type=0 flinger=0xb7ebb550
,D/qdhwcomposer(  281): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  884): Display changed displayId=0
,W/jxcore-log( 4954): Platform android
W/jxcore-log( 4954): 
W/jxcore-log( 4954): Process ARCH arm
W/jxcore-log( 4954): 
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8256820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205507960)
,I/jxcore-log( 4954): JXcore Cordova bridge is ready!
I/jxcore-log( 4954): 
,W/jxcore-log( 4954): JXcore engine is started
,E/jxcore-log( 4954): >> motorola-XT1072
E/jxcore-log( 4954): 
,I/jxcore-log( 4954): Total memory 916258816
I/jxcore-log( 4954): 
,I/jxcore-log( 4954): Free memory 34963456
I/jxcore-log( 4954): 
I/jxcore-log( 4954): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4954): 
I/jxcore-log( 4954): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4954): 
,I/jxcore-log( 4954): userPath [ 'www' ]
I/jxcore-log( 4954): 
,I/jxcore-log( 4954): Size 720 1184
I/jxcore-log( 4954): 
,I/jxcore-log( 4954): Screen Brightness 82
I/jxcore-log( 4954): 
,E/jxcore-log( 4954): Dummy Error Log.
E/jxcore-log( 4954): 
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205507960) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8256820
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  281): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  281): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  884): Excessive delay in setPowerMode(): 325ms
,I/PowerManagerService(  884): Sleeping (uid 1000)...
,I/WindowManager(  884): AOD feature not enabled!
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  298): platform_set_parameters: exit with code(0)
E/msm8974_platform(  298): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  298): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  298): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  884): startHal
,E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2d8e89c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb723e310, mCls = 0x2014e2
I/WifiNative-HAL(  884): Could not start hal
D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 false
,E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 4
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  884): startHal
E/wifi    (  884): getStaticLongField sWifiHalHandle 0xa2d8e89c
D/wifi    (  884): halHandle = 0x0, mVM = 0xb723e310, mCls = 0x14ae
I/WifiNative-HAL(  884): Could not start hal
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=off
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  298): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  298): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  298): adev_set_parameters: ERROR: set param called even when stream out is null
,I/Keyboard.Facilitator( 1412): onFinishInput()
,E/WifiStateMachine(  884): setSuspendOptimizations: 4 true
E/WifiStateMachine(  884): mSuspendOptNeedsDisabled 0
,I/jxcore-log( 4954): getBuffer is called!!!!
I/jxcore-log( 4954): 
,D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  884): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  884): Message: 2
,D/WifiService(  884): New client listening to asynchronous messages
,D/WifiService(  884): setWifiEnabled: false pid=4954, uid=10317
E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4954): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 4954): 
I/jxcore-log( 4954): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4954): 
,V/AlarmManager(  884): send {287b9dde, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  884): done {287b9dde, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [3ms]
,D/AndroidRuntime( 5055): 
D/AndroidRuntime( 5055): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5055): CheckJNI is OFF
,D/AndroidRuntime( 5055): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  884): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
,I/ActivityManager(  884): Killing 4954:com.example.hello/u0a317 (adj 0): stop com.example.hello
,I/WindowState(  884): WIN DEATH: Window{3412aa5c u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  884): Client connection lost with reason: 4
,W/PackageSettings(  884): Skipping PackageSetting{33b3a914 com.test.thalitest/10315} due to missing metadata
,I/ActivityManager(  884):   Force finishing activity ActivityRecord{3ca1e4d0 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  884): Display changed displayId=0
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  884): Spurious death for ProcessRecord{1e700bbf 4954:com.example.hello/u0a317}, curProc for 4954: null
,I/ActivityManager(  884): Force stopping com.example.hello appid=10317 user=0: pkg removed
,I/ActivityManager(  884):   Force finishing activity ActivityRecord{3ca1e4d0 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  884): Duplicate finish request for ActivityRecord{3ca1e4d0 u0 com.example.hello/.MainActivity t3 f}
,I/art     ( 4746): Explicit concurrent mark sweep GC freed 647(37KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 404us total 44.661ms
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1709): Ignoring removeGeofence because network location is disabled.
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/Keyboard.Facilitator( 1412): resetDictionaries() : en_US
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5083 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Keyboard.Facilitator.DecoderInitializer( 1412): run()
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 540(37KB) AllocSpace objects, 1(36KB) LOS objects, 25% free, 13MB/17MB, paused 1.773ms total 119.272ms
,I/art     (  884): Explicit concurrent mark sweep GC freed 21498(1386KB) AllocSpace objects, 6(337KB) LOS objects, 33% free, 20MB/30MB, paused 1.648ms total 136.749ms
,I/art     (  884): WaitForGcToComplete blocked for 42.530ms for cause Explicit
,I/Decoder ( 1412): createOrResetDecoder
,D/OtaApp  ( 2491): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2491): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2491): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2491): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1615): onCreate
,W/InputMethodManagerService(  884): Got RemoteException sending setActive(false) notification to pid 4954 uid 10317
I/Keyboard.Facilitator( 1412): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = user
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1412): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1412): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1412): run()
,I/StatsUtilsManager( 1412): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1412): shouldRecordStats() = Too Soon
,D/TaskPersister(  884): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task.xml
,D/VoicemailCleanupService( 5083): Cleaning up data for package: com.example.hello
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5108 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 5083): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  884): Explicit concurrent mark sweep GC freed 8338(470KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.829ms total 215.311ms
,I/Launcher( 1561): Deferring update until onResume
,I/ActivityManager(  884): Killing 4813:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/AndroidRuntime( 5055): Shutting down VM
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_4813/cgroup.procs: No such file or directory
,W/asset   ( 5108): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5108): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5108): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5108): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5127 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4746:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_4746/cgroup.procs: No such file or directory
,W/ContextImpl( 5127): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5151 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4840:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_4840/cgroup.procs: No such file or directory
,W/Launcher( 1561): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e1e95af new=com.google.android.velvet.VelvetApplication@e1e95af
,E/SQLiteLog( 1561): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1944): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1944): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1944): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1944): Clearing selected account for com.example.hello
,E/SQLiteLog( 1615): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1615): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 1615): FATAL EXCEPTION: main
E/AndroidRuntime( 1615): Process: com.google.process.gapps, PID: 1615
E/AndroidRuntime( 1615): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1615): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1615): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1615): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1615): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1615): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1615): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1615): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1615): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1615): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1615): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1615): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1615): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1615): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1615): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1615): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1615): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1615): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1615): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1615): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1615): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1615): 	... 9 more
I/Process ( 1615): Sending signal. PID: 1615 SIG: 9
,E/DropBoxManagerService(  884): Can't write: system_app_crash
E/DropBoxManagerService(  884): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  884): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  884): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  884): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  884): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  884): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  884): 	... 5 more
,E/lowmemorykiller(  278): Error writing /proc/1615/oom_score_adj; errno=22
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,E/SQLiteLog( 1944): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 1944): Removing dialog suppression flag for package com.example.hello

```
