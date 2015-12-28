#### Test 503880191ec81a5_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AndroidRuntime( 6731): 
D/AndroidRuntime( 6731): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6731): CheckJNI is OFF
D/AndroidRuntime( 6731): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (143 us)
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 6731): Shutting down VM
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6750 uid=10405 gids={50405, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6750): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6750): Time to load native libraries: 2 ms (timestamps 507-509)
I/LibraryLoader( 6750): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6750): Binding Chromium to main looper Looper (main, tid 1) {1b217bcf}
I/LibraryLoader( 6750): Expected native library version number "",actual native library version number ""
,I/chromium( 6750): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6750): Initializing chromium process, singleProcess=true
W/art     ( 6750): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6750): ApplicationContext is null in ApplicationStatus
,W/chromium( 6750): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6750): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6750): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6750): Local Branch: 
I/Adreno-EGL( 6750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6750): Local Patches: NONE
I/Adreno-EGL( 6750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
,D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f47abb9:true
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,E/BackupManagerService(  881): Timeout restoring application @pm@
,W/BackupManagerService(  881): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1805): Restore processing aborted, no more packages
,E/BackupManagerService(  881): Failure getting next package name
,E/BackupManagerService(  881): Duplicate finish
,W/art     ( 6750): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6750): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6750): CordovaWebView is running on device made by: motorola
,W/art     ( 6750): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6750): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6750): Render dirty regions requested: true
,D/Atlas   ( 6750): Validating map...
,W/chromium( 6750): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (44:242 vsyncs) (46:1048)
,I/OpenGLRenderer( 6750): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6750): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.example.hello/.MainActivity,cp,ca,995
I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +995ms
,E/Adreno-ES20( 6750): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6750): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6750): Cannot call determinedVisibility() - never saw a connection for the pid: 6750
,I/chromium( 6750): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 6750): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 6750): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 6750): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6750): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 6750): JniHelper::setJavaVM(0xb81f7310), pthread_self() = -1201986040
D/JX-Cordova( 6750): jxcore cordova android initializing
,I/SFPerfTracer(  278):      triggers: (rate: 13:448) (compose: 0:2) (post: 0:1) (render: 0:2) (25:998 frames) (26:1090)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb7209210): 0:14)* (StatusBar (0xb7263f58): 0:154) (NavigationBar (0xb72bfba8): 0:23) (com.android.systemui.ImageWallpaper (0xb728e9b0): 0:5)* (DimLayer (0xb72923c0): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb72a8f50): 0:56)- (Starting com.example.hello (0xb7260120): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb7294ab8): 26:36) 
,W/jxcore-log( 6750): Initializing JXcore engine
W/jxcore-log( 6750): JXcore engine is ready
,W/jxcore-log( 6750): Starting JXcore engine
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,W/m.example.hello( 6750): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10405 path="socket:[7534]" dev="sockfs" ino=7534 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6750): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10405 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 6750): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10405 path="socket:[8564]" dev="sockfs" ino=8564 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6750): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10405 path="socket:[26972]" dev="sockfs" ino=26972 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6750): Platform android
W/jxcore-log( 6750): 
W/jxcore-log( 6750): Process ARCH arm
W/jxcore-log( 6750): 
,I/jxcore-log( 6750): JXcore Cordova bridge is ready!
I/jxcore-log( 6750): 
,W/jxcore-log( 6750): JXcore engine is started
,E/jxcore-log( 6750): >> motorola-XT1072
E/jxcore-log( 6750): 
I/jxcore-log( 6750): Total memory 916258816
I/jxcore-log( 6750): 
I/jxcore-log( 6750): Free memory 34746368
I/jxcore-log( 6750): 
I/jxcore-log( 6750): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6750): 
I/jxcore-log( 6750): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6750): 
,I/jxcore-log( 6750): userPath [ 'www' ]
I/jxcore-log( 6750): 
I/jxcore-log( 6750): Size 720 1184
I/jxcore-log( 6750): 
I/jxcore-log( 6750): Screen Brightness 82
I/jxcore-log( 6750): 
E/jxcore-log( 6750): Dummy Error Log.
E/jxcore-log( 6750): 
,I/jxcore-log( 6750): getBuffer is called!!!!
I/jxcore-log( 6750): 
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/PowerManagerService(  881): Nap time (uid 1000)...
I/PowerManagerService(  881): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  881): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  881): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  881): Build Date: 10/28/14 Tue
I/Adreno-EGL(  881): Local Branch: 
I/Adreno-EGL(  881): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  881): Local Patches: NONE
I/Adreno-EGL(  881): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  881): activate, handle: 1598182242, enabled: 0, index 2
D/        (  881): BstSensorExt: id=1598182242, en=0
D/        (  881): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 236
,D/        (  881): activate, handle: 2, enabled: 0, index 5
I/DisplayManagerService(  881): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  881): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb7188550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/rmt_storage(  289): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb81d2820
I/rmt_storage(  289): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  289): wakelock acquired: 1, error no: 42
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1206049480)
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1206049480) wakelock released: 1, error no: 0
I/rmt_storage(  289): 
,I/rmt_storage(  289): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb81d2820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
I/SFPerfTracer(  278):       trigger: frame rate (-28.727%)	(42.764 fps)	(23.384 ms) 	(3 drops)	(15 frames)
I/SFPerfTracer(  278):      triggers: (rate: 14:451) (compose: 0:2) (post: 0:1) (render: 0:2) (15:1026 frames) (16:1125)
D/SFPerfTracer(  278):        layers: (4:10) (FocusedStackFrame (0xb7209210): 0:14)* (StatusBar (0xb7263f58): 0:154) (NavigationBar (0xb72bfba8): 0:23) (com.android.systemui.ImageWallpaper (0xb728e9b0): 0:5)* (DimLayer (0xb72923c0): 0:6)* (com.example.hello/com.example.hello.MainActivity (0xb7294ab8): 0:53) (ColorFade (0xb72a8f50): 16:18) 
,D/SurfaceControl(  881): Excessive delay in setPowerMode(): 342ms
,I/PowerManagerService(  881): Sleeping (uid 1000)...
,I/WindowManager(  881): AOD feature not enabled!
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WifiStateMachine(  881): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  881): do suspend false
,I/Keyboard.Facilitator( 1414): onFinishInput()
D/        (  881): activate, handle: 1598182229, enabled: 0, index 0
E/        (  881): <BST> disable accel, orig state: 1
I/        (  881): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  881): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  881): do suspend true
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ef49612 mBinding = false
,W/Settings( 1474): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  881): Message: 2
,D/BluetoothManagerService(  881): Sending off request.
,D/BluetoothAdapterState( 2674): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2674): Setting state to 13
I/BluetoothAdapterState( 2674): Bluetooth adapter state changed: 12-> 13
,D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 2674): onBluetoothDisable()
I/BluetoothAdapterState( 2674): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothMapService( 2674): onReceive
D/BluetoothMapService( 2674): STATE_TURNING_OFF
,D/BluetoothMapService( 2674): MAP Service closeService in
D/BluetoothMapMasInstance( 2674): MAP Service shutdown
,V/BluetoothMapMasInstance( 2674): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2674): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2674): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 2674): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 2674): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 2674): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2674): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2674): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 2674): stopping Accept Thread
,E/BtOppRfcommListener( 2674): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BtOppRfcommListener( 2674): BluetoothSocket listen thread finished
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  881): New client listening to asynchronous messages
,I/ActivityManager(  881): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6861 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 2674): Scan Mode:20
D/BluetoothAdapterState( 2674): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,W/Settings( 1474): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/bt-btif ( 2674): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 2674): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2674): L2CAP - PSM: 0x0017 not found for deregistration
D/WifiService(  881): setWifiEnabled: false pid=6750, uid=10405
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,D/btif_config_util( 2674): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6750): ****TEST TOOK:  5197  ms ****
I/jxcore-log( 6750): 
I/jxcore-log( 6750): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6750): 
W/Settings( 1474): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1474): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 21
D/TCMD    (  457): Listening for incoming client connection request
,V/NativeCrypto( 1805): Read error: ssl=0xb84d5e60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1805): SSL shutdown failed: ssl=0xb84d5e60: I/O error during system call, Broken pipe
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiMetrics(  881): connected time updated 97160
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiScanningService(  881): SCAN_AVAILABLE : 1
D/RttService(  881): SCAN_AVAILABLE : 1
D/WifiScanningService(  881): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  881): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  881): [1,451,341,538,062 ms] noteScanEnd no scan source
D/WifiP2pService(  881): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pDisablingState
D/WifiP2pService(  881): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): p2p socket connection lost
D/WifiP2pService(  881): P2pDisabledState
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,W/ResourcesManager( 6861): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/WifiP2pService(  881): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 2674): ag scb idx 1 not allocated
E/bt-btif ( 2674): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2674): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2674): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2674): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2674): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 2674): exiting userial_read_thread
W/bt-l2cap( 2674): L2CAP - PSM: 0x0019 not found for deregistration
D/bt_userial_mct( 2674): Leaving userial_evt_read_thread()
W/bt-l2cap( 2674): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 2674): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 2674): hw_epilog_process
D/bt_userial_mct( 2674): userial_close
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  881): stopping supplicant
,E/WifiStateMachine(  881): setWifiState: disabling
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/TCMD    (  457): NL - Read 1004 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
,D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/MDMCTBK (  293):  STA Disconnected !!
D/TCMD    (  457): Listening for incoming client connection request
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
D/TCMD    (  457): NL - Read 68 bytes from update socket.
I/MDMCTBK (  293): checkDefaultInst, pid match
D/TCMD    (  457): NL - message type is RTM_NEWLINK
I/MDMCTBK (  293): get_property_value, Enter
D/TCMD    (  457): Listening for incoming client connection request
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  881): InitialState.processMessage what=4
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1433): eap_proxy Deinitialzed
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/art     (  881): Explicit concurrent mark sweep GC freed 44741(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 2.044ms total 160.867ms
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TCMD    (  457): NL - Read 1004 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293):  Wpa Supplicant Exiting !!
D/MDMCTBK (  293): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  293): wifi_close_sockets: Close Wifi socket
,E/WifiStateMachine(  881): Supplicant connection lost
D/MDMCTBK (  293): wifi_close_sockets: Exit
,W/ContextImpl( 6861): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AndroidRuntime( 6889): 
D/AndroidRuntime( 6889): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6889): CheckJNI is OFF
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f79693f:true
,I/bt_hwcfg( 2674): Starting hciattach daemon
I/bt_hwcfg( 2674): try to set false
,I/bt_vendor( 2674): cleanup
I/GKI_LINUX( 2674): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2674): GKI_exit_task 0 done
I/GKI_LINUX( 2674): GKI_shutdown(): task [BTU] terminated
,E/QC-QMI  (  428): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,D/BluetoothAdapterState( 2674): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2674): mProfilesStarted : true supportedProfileServices.length : 7
,D/HeadsetService( 2674): Received stop request...Stopping profile...
D/HeadsetStateMachine( 2674): quit
,D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
D/HeadsetStateMachine( 2674): Exit Disconnected: -1
E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,D/BluetoothHeadset( 1550): Proxy object disconnected
,E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
D/BluetoothHeadset(  881): Proxy object disconnected
D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 1
E/QC-QMI  (  428): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
D/BluetoothHeadset( 1514): Proxy object disconnected
,D/A2dpService( 2674): Received stop request...Stopping profile...
D/A2dpStateMachine( 2674): Exit Disconnected: -1
,D/BluetoothHeadset( 1514): Proxy object disconnected
,D/BluetoothManagerService(  881): Message: 30
,D/BluetoothAdapterState( 2674): Stopping profile services that were post enabled
,D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,D/BluetoothA2dp(  881): Proxy object disconnected
,D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 2674): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,D/HealthService( 2674): Received stop request...Stopping profile...
D/BluetoothManagerService(  881): Message: 30
,D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,D/LocalBluetoothProfileManager( 6861): Adding local MAP profile
,D/HeadsetStateMachine( 2674): Unbinding service...
,D/BluetoothMap( 6861): Create BluetoothMap proxy object
D/BluetoothManagerService(  881): Message: 30
,W/BluetoothHeadsetServiceJni( 2674): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2674): Cleaning up Bluetooth Handsfree callback object
D/AuthorizationBluetoothService( 1805): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/PanService( 2674): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,D/BtGatt.DebugUtils( 2674): handleDebugAction() action=null
D/BtGatt.GattService( 2674): Received stop request...Stopping profile...
,D/BtGatt.GattService( 2674): stop()
,D/BluetoothManagerService(  881): Message: 30
,D/BtGatt.AdvertiseManager( 2674): advertise clients cleared
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6912 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,E/WifiStateMachine(  881): setWifiState: disabled
,D/LocalBluetoothProfileManager( 6861): LocalBluetoothProfileManager construction complete
D/BluetoothMapService( 2674): Received stop request...Stopping profile...
D/BluetoothMapService( 2674): stop()
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothMapEmailAppObserver( 2674): deinitObservers()
D/BluetoothMapEmailAppObserver( 2674): removeReceiver()
,D/BluetoothAdapterService( 2674): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b217bcf
,I/GKI_LINUX( 2674): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2674): GKI_exit_task 2 done
I/GKI_LINUX( 2674): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2674): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2674): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2674): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2674): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2674): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2674): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2674): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2674): MAP Service closeService in
D/BluetoothMapService( 2674): cleanup()
D/BluetoothMapService( 2674): MAP Service closeService in
D/BluetoothAdapterState( 2674): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2674): Setting state to 10
I/BluetoothAdapterState( 2674): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  881): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 2674): Entering OffState
D/BluetoothInputDevice( 6861): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1550): onBluetoothStateChange: up=false
D/AndroidRuntime( 6889): Calling main entry com.android.commands.pm.Pm
D/BluetoothPbap( 6861): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1514): onBluetoothStateChange: up=false
D/BluetoothHeadset(  881): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1514): onBluetoothStateChange: up=false
D/BluetoothMap( 6861): onBluetoothStateChange: up=false
D/BluetoothA2dp(  881): onBluetoothStateChange: up=false
D/BluetoothPan( 6861): onBluetoothStateChange on: false
D/BluetoothManagerService(  881): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  881): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  881): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ef49612 mBinding = false
D/BluetoothManagerService(  881): Sending unbind request.
,D/BluetoothManagerService(  881): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1288): 306474290: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 306474290: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 306474290: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2674): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2674): GKI_exit_task 1 done
,I/GKI_LINUX( 2674): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2674): cleanupNative: return from cleanup
,I/ActivityManager(  881): Force stopping com.example.hello appid=10405 user=-1: uninstall pkg
,I/ActivityManager(  881): Killing 6750:com.example.hello/u0a405 (adj 0): stop com.example.hello
,I/art     ( 2674): System.exit called, status: 0
I/AndroidRuntime( 2674): VM exiting with result code 0, cleanup skipped.
,W/Settings( 1805): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WindowState(  881): WIN DEATH: Window{224df529 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,W/PackageSettings(  881): Skipping PackageSetting{6dc0f9e com.test.thalitest/10404} due to missing metadata
,D/BluetoothAdapter( 1805): 983936893: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1805): 983936893: getState() :  mService = null. Returning STATE_OFF
,D/Checkin ( 3242): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3242): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{3f4daa4d u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  881): Display changed displayId=0
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  881): Process com.android.bluetooth (pid 2674) has died
W/ActivityManager(  881): Spurious death for ProcessRecord{13b7363c 6750:com.example.hello/u0a405}, curProc for 6750: null
,I/ActivityManager(  881): Force stopping com.example.hello appid=10405 user=0: pkg removed
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{3f4daa4d u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{3f4daa4d u0 com.example.hello/.MainActivity t3 f}
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/DockEventReceiver( 6861): finishStartingService: stopping service
,W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
,W/ResourcesManager( 6912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 3242): Explicit concurrent mark sweep GC freed 8089(1257KB) AllocSpace objects, 4(66KB) LOS objects, 39% free, 7MB/12MB, paused 569us total 55.263ms
,I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
I/Decoder ( 1414): createOrResetDecoder
,D/OtaApp  ( 2784): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2784): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2784): publish the event [tag = MOT_OTA event name = LOG]
,D/TCMD    (  457): NL - Read 444 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 17
D/TCMD    (  457): Listening for incoming client connection request
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 4414(280KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 479us total 82.407ms
,I/ActivityManager(  881): Killing 6501:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/OtaApp  ( 2784): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2784): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2784): publish the event [tag = MOT_OTA event name = LOG]
,D/TCMD    (  457): NL - Read 1004 bytes from update socket.
,D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 18800(1117KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 1.366ms total 134.156ms
,D/TCMD    (  457): NL - Read 444 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 17
,D/TCMD    (  457): Listening for incoming client connection request
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ConfigService( 1805): onCreate
W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_6501/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Launcher( 1567): Deferring update until onResume
,W/InputMethodManagerService(  881): Got RemoteException sending setActive(false) notification to pid 6750 uid 10405
,I/Keyboard.Facilitator( 1414): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
,I/art     (  881): Explicit concurrent mark sweep GC freed 18524(1230KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/31MB, paused 3.109ms total 237.757ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
,D/AndroidRuntime( 6889): Shutting down VM
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
I/PhenotypeConfigurator( 1805): Scheduling Phenotype for one-off execution 6563 seconds from now (1451341539128)
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
,I/Babel_SMS( 6912): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6912): MmsConfig.loadMmsSettings
I/Babel_SMS( 6912): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/GetConfigurationSnapshotOperation( 1805): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/Babel_SMS( 6912): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6912): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6912): MmsConfig.loadFromResources
,E/Babel_SMS( 6912): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6912): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6912): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6912): startup - clean
,I/Babel   ( 6912): deleted: false for 0
,I/PhenotypeFlagCommitter( 1805): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1805): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6957 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6957): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6912): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6912): Unsupported mime video/mpeg2
,E/SQLiteDatabase( 6957): Failed to open database '/data/data/com.motorola.context/databases/context_engine.db'.
E/SQLiteDatabase( 6957): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6957): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6957): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6957): 	at com.motorola.context.provider.InternalProvider.onCreate(InternalProvider.java:99)
E/SQLiteDatabase( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/SQLiteDatabase( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/SQLiteDatabase( 6957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6957): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6957): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/SQLiteDatabase( 6957): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6957): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6957): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/SQLiteDatabase( 6957): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
D/AndroidRuntime( 6957): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 6957): FATAL EXCEPTION: main
E/AndroidRuntime( 6957): Process: com.motorola.context, PID: 6957
E/AndroidRuntime( 6957): java.lang.RuntimeException: Unable to get provider com.motorola.context.provider.InternalProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5054)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/AndroidRuntime( 6957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6957): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 6957): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6957): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6957): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 6957): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 6957): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 6957): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 6957): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6957): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6957): 	at com.motorola.context.provider.InternalProvider.onCreate(InternalProvider.java:99)
E/AndroidRuntime( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/AndroidRuntime( 6957): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/AndroidRuntime( 6957): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/AndroidRuntime( 6957): 	... 11 more
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  881): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  881): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  881): 	... 5 more
I/Process ( 6957): Sending signal. PID: 6957 SIG: 9
I/VideoCapabilities( 6912): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc

```
