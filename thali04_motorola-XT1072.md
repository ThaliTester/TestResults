#### Test 613623660556c10_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 5164): 
D/AndroidRuntime( 5164): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5164): CheckJNI is OFF
D/AndroidRuntime( 5164): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (165 us)
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5164): Shutting down VM
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5183 uid=10536 gids={50536, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5183): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5183): Time to load native libraries: 3 ms (timestamps 7411-7414)
,I/LibraryLoader( 5183): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5183): Binding Chromium to main looper Looper (main, tid 1) {c136977}
I/LibraryLoader( 5183): Expected native library version number "",actual native library version number ""
,I/chromium( 5183): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SFPerfTracer(  279):      triggers: (rate: 12:322) (compose: 0:1) (post: 0:1) (render: 0:2) (18:1015 frames) (19:1093)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb71d4a60): 1:14)* (DimLayer (0xb71810f0): 1:6) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7183728): 0:45)- (StatusBar (0xb7187250): 19:157) (NavigationBar (0xb71c4610): 13:35) (com.android.systemui.ImageWallpaper (0xb71c7df0): 0:8)* (Starting com.motorola.ccc.ota (0xb71bb5f0): 0:20)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb71e6dd0): 18:52) (Starting com.test.thalitest (0xb71bb5f0): 1:4)* 
,I/BrowserStartupController( 5183): Initializing chromium process, singleProcess=true
,W/art     ( 5183): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5183): ApplicationContext is null in ApplicationStatus
,W/chromium( 5183): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5183): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5183): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5183): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5183): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5183): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5183): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5183): Local Branch: 
I/Adreno-EGL( 5183): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5183): Local Patches: NONE
I/Adreno-EGL( 5183): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11106da6:true
,D/BluetoothAdapter( 5183): 685967182: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5183): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5183): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5183): CordovaWebView is running on device made by: motorola
,W/art     ( 5183): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5183): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5183): Render dirty regions requested: true
,D/Atlas   ( 5183): Validating map...
,W/chromium( 5183): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (45:227 vsyncs) (47:1121)
,I/OpenGLRenderer( 5183): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5183): Enabling debug mode 0
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1067
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +1s67ms
,I/Keyboard.Facilitator( 1407): onFinishInput()
,E/Adreno-ES20( 5183): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5183): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5183): Cannot call determinedVisibility() - never saw a connection for the pid: 5183
,V/AlarmManager(  880): send {84b899a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  880): done {84b899a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [1ms]
,D/JsMessageQueue( 5183): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5183): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5183): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5183): JniHelper::setJavaVM(0xb8855310), pthread_self() = -1195668144
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb516b0 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5183): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23a6724f added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5183): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  880): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5183): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5183): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183): setDiscoveryMode: Discovery mode BLE is supported
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5183): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5183): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5183): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5183): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5183): Initializing JXcore engine
W/jxcore-log( 5183): JXcore engine is ready
,W/Thread-605( 5260): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10536 path="socket:[5615]" dev="sockfs" ino=5615 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-605( 5260): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10536 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-605( 5260): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10536 path="socket:[6935]" dev="sockfs" ino=6935 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-605( 5260): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10536 path="socket:[23412]" dev="sockfs" ino=23412 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5183): Starting JXcore engine
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task_thumbnail.png
,W/jxcore-log( 5183): Platform android
W/jxcore-log( 5183): 
,W/jxcore-log( 5183): Process ARCH arm
W/jxcore-log( 5183): 
,I/jxcore-log( 5183): JXcore Cordova bridge is ready!
I/jxcore-log( 5183): 
,W/jxcore-log( 5183): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5183): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5183): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5183): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5183): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5183): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2536): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2536): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2536): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2536): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5183): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1407): onFinishInput()
,I/SFPerfTracer(  279):      triggers: (rate: 12:322) (compose: 0:1) (post: 0:1) (render: 0:2) (14:1109 frames) (15:1206)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb71d4a60): 0:19)* (DimLayer (0xb71810f0): 1:9) (StatusBar (0xb7187250): 15:172) (NavigationBar (0xb71c4610): 13:48) (com.android.systemui.ImageWallpaper (0xb71c7df0): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb71e6dd0): 0:62)- (Starting com.test.thalitest (0xb71bb5f0): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7183728): 15:72) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb71e6dd0): 1:4)* 
,I/ActivityManager(  880): Killing 4986:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4986/cgroup.procs: No such file or directory
,I/PowerManagerService(  880): Nap time (uid 1000)...
I/PowerManagerService(  880): Going to sleep due to screen timeout (uid 1000)...
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (48:332 vsyncs) (50:1238)
,I/Adreno-EGL(  880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  880): Build Date: 10/28/14 Tue
I/Adreno-EGL(  880): Local Branch: 
I/Adreno-EGL(  880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  880): Local Patches: NONE
I/Adreno-EGL(  880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  880): activate, handle: 1598182242, enabled: 0, index 2
D/        (  880): BstSensorExt: id=1598182242, en=0
D/        (  880): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  880): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  880): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb70a9550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  288): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8b94820
,I/rmt_storage(  288): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  288): wakelock acquired: 1, error no: 42
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1195816824)
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1195816824) wakelock released: 1, error no: 0
I/rmt_storage(  288): 
I/rmt_storage(  288): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8b94820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  880): Excessive delay in setPowerMode(): 327ms
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/WindowManager(  880): AOD feature not enabled!
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2dea89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb8855310, mCls = 0x201716
I/WifiNative-HAL(  880): Could not start hal
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  294): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
E/WifiStateMachine(  880): setSuspendOptimizations: 4 false
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 4
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2dea89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb8855310, mCls = 0x16fa
I/WifiNative-HAL(  880): Could not start hal
D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  880): setSuspendOptimizations: 4 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,I/Keyboard.Facilitator( 1407): onFinishInput()
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  880): send {1c46ebe, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {11a83d92, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  880): done {11a83d92, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [7ms]
,V/AlarmManager(  880): done {1c46ebe, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {530a61e, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {530a61e, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,E/global frequency( 2536): no tags to log
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 53827(2MB) AllocSpace objects, 33(1042KB) LOS objects, 39% free, 7MB/12MB, paused 698us total 47.932ms
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  880): send {2688a0de, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {2688a0de, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,I/art     (  880): Explicit concurrent mark sweep GC freed 13242(794KB) AllocSpace objects, 6(256KB) LOS objects, 33% free, 20MB/31MB, paused 1.578ms total 130.173ms
,I/art     ( 2536): Explicit concurrent mark sweep GC freed 10503(555KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 10MB/18MB, paused 1.030ms total 53.998ms
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 4141(172KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 511us total 26.532ms
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2536): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2536): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2536): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2536): BcsDSCheckin.events found events 231
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2536): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2536): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2536): unknown error code mapping for: 0
I/global frequency( 2536): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2536): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310916, SEQNUM=4366, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-486, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2536):  Nonce Reponse 
I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2536): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2536): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {530a61e, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {530a61e, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,I/VacuumService( 1695): Vacuum at: now=1456909014092 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1695): onCreate
,V/AlarmManager(  880): send {84b899a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  880): send {1c46ebe, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {84b899a, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [5ms]
,V/AlarmManager(  880): done {1c46ebe, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1695): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1695): disconnect managed GoogleApiClient
,V/AlarmManager(  880): send {24770678, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {24770678, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311686, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-632, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2536):  Nonce Reponse 
I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2536): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2536): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310977, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1328, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {1c46ebe, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {35df4e45, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {35df4e45, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [4ms]
,V/AlarmManager(  880): done {1c46ebe, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2536):  Nonce Reponse 
I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2536): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 3695(145KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 762us total 31.112ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 12578(618KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.632ms total 111.699ms
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2536): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2536): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
