#### Test 5038801913f4183_thali04_motorola-XT1072 Logs


```
--------- beginning of system
E/BackupManagerService(  880): Timeout restoring application @pm@
W/BackupManagerService(  880): Tried to clear data for @pm@ but not found
--------- beginning of main
W/GmsBackupTransport( 1743): Restore processing aborted, no more packages
E/BackupManagerService(  880): Failure getting next package name
E/BackupManagerService(  880): Duplicate finish
,D/AndroidRuntime( 6542): 
D/AndroidRuntime( 6542): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6542): CheckJNI is OFF
D/AndroidRuntime( 6542): Calling main entry com.android.commands.am.Am
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 6542): Shutting down VM
I/ActivityManager(  880): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6561 uid=10375 gids={50375, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6561): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6561): Time to load native libraries: 1 ms (timestamps 9054-9055)
I/LibraryLoader( 6561): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6561): Binding Chromium to main looper Looper (main, tid 1) {5fb199}
I/LibraryLoader( 6561): Expected native library version number "",actual native library version number ""
I/chromium( 6561): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/BrowserStartupController( 6561): Initializing chromium process, singleProcess=true
W/art     ( 6561): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6561): ApplicationContext is null in ApplicationStatus
W/chromium( 6561): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6561): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6561): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6561): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6561): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6561): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6561): Local Branch: 
I/Adreno-EGL( 6561): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6561): Local Patches: NONE
I/Adreno-EGL( 6561): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a80d951:true
W/art     ( 6561): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6561): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6561): CordovaWebView is running on device made by: motorola
W/art     ( 6561): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6561): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6561): Render dirty regions requested: true
D/Atlas   ( 6561): Validating map...
W/chromium( 6561): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6561): Initialized EGL, version 1.4
D/OpenGLRenderer( 6561): Enabling debug mode 0
I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (45:249 vsyncs) (47:1048)
I/LaunchCheckinHandler(  880): Displayed com.example.hello/.MainActivity,cp,ca,929
I/ActivityManager(  880): Displayed com.example.hello/.MainActivity: +929ms
I/Keyboard.Facilitator( 1417): onFinishInput()
E/Adreno-ES20( 6561): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6561): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6561): Cannot call determinedVisibility() - never saw a connection for the pid: 6561
I/chromium( 6561): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 6561): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 6561): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 6561): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6561): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 6561): JniHelper::setJavaVM(0xb8b0e310), pthread_self() = -1192825952
,D/JX-Cordova( 6561): jxcore cordova android initializing
,I/SFPerfTracer(  279):      triggers: (rate: 13:455) (compose: 0:2) (post: 0:1) (render: 0:2) (31:996 frames) (32:1093)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb771da68): 0:15)* (StatusBar (0xb7661ac8): 0:154) (NavigationBar (0xb7665730): 0:21) (com.android.systemui.ImageWallpaper (0xb7668768): 0:6)* (DimLayer (0xb76e2030): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7716a28): 0:53)- (Starting com.example.hello (0xb770d710): 0:41)- (com.example.hello/com.example.hello.MainActivity (0xb77154a0): 32:36) 
,W/jxcore-log( 6561): Initializing JXcore engine
W/jxcore-log( 6561): JXcore engine is ready
,W/jxcore-log( 6561): Starting JXcore engine
,W/m.example.hello( 6561): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10375 path="socket:[7582]" dev="sockfs" ino=7582 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6561): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10375 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 6561): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10375 path="socket:[9419]" dev="sockfs" ino=9419 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 6561): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10375 path="socket:[27327]" dev="sockfs" ino=27327 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6561): Platform android
W/jxcore-log( 6561): 
,W/jxcore-log( 6561): Process ARCH arm
W/jxcore-log( 6561): 
,I/jxcore-log( 6561): JXcore Cordova bridge is ready!
I/jxcore-log( 6561): 
W/jxcore-log( 6561): JXcore engine is started
,E/jxcore-log( 6561): >> motorola-XT1072
E/jxcore-log( 6561): 
,I/jxcore-log( 6561): Total memory 916258816
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): Free memory 35352576
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): userPath [ 'www' ]
I/jxcore-log( 6561): 
,I/jxcore-log( 6561): Size 720 1184
I/jxcore-log( 6561): 
I/jxcore-log( 6561): Screen Brightness 82
I/jxcore-log( 6561): 
E/jxcore-log( 6561): Dummy Error Log.
E/jxcore-log( 6561): 
,I/jxcore-log( 6561): getBuffer is called!!!!
I/jxcore-log( 6561): 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/PowerManagerService(  880): Nap time (uid 1000)...
I/PowerManagerService(  880): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  880): Build Date: 10/28/14 Tue
I/Adreno-EGL(  880): Local Branch: 
I/Adreno-EGL(  880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  880): Local Patches: NONE
I/Adreno-EGL(  880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  880): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  880): BstSensorExt: id=1598182242, en=0
D/        (  880): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 232
,D/        (  880): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  880): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb75d9550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/rmt_storage(  289): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb715b820
I/rmt_storage(  289): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  289): wakelock acquired: 1, error no: 42
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1223314120)
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1223314120) wakelock released: 1, error no: 0
I/rmt_storage(  289): 
,I/rmt_storage(  289): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb715b820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
I/SFPerfTracer(  279):       trigger: frame rate (-46.133%)	(32.320 fps)	(30.940 ms) 	(5 drops)	(12 frames)
I/SFPerfTracer(  279):      triggers: (rate: 14:461) (compose: 0:3) (post: 0:1) (render: 0:3) (12:1020 frames) (13:1125)
D/SFPerfTracer(  279):        layers: (4:10) (FocusedStackFrame (0xb771da68): 0:15)* (StatusBar (0xb7661ac8): 0:154) (NavigationBar (0xb7665730): 0:21) (com.android.systemui.ImageWallpaper (0xb7668768): 0:6)* (DimLayer (0xb76e2030): 0:6)* (com.example.hello/com.example.hello.MainActivity (0xb77154a0): 0:52) (ColorFade (0xb770d710): 13:15) 
,D/SurfaceControl(  880): Excessive delay in setPowerMode(): 363ms
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/WindowManager(  880): AOD feature not enabled!
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
E/msm8974_platform(  294): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
,D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/native  (  880): do suspend false
,I/Keyboard.Facilitator( 1417): onFinishInput()
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  880): do suspend true
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@cb6204a mBinding = false
,W/Settings( 1478): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  880): Message: 2
,D/BluetoothManagerService(  880): Sending off request.
,D/BluetoothAdapterState( 2465): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2465): Setting state to 13
I/BluetoothAdapterState( 2465): Bluetooth adapter state changed: 12-> 13
,D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 2465): onBluetoothDisable()
I/BluetoothAdapterState( 2465): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothMapService( 2465): onReceive
D/BluetoothMapService( 2465): STATE_TURNING_OFF
,D/BluetoothMapService( 2465): MAP Service closeService in
D/BluetoothMapMasInstance( 2465): MAP Service shutdown
,V/BluetoothMapMasInstance( 2465): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2465): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2465): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 2465): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 2465): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 2465): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2465): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2465): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 2465): stopping Accept Thread
,E/BtOppRfcommListener( 2465): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2465): BluetoothSocket listen thread finished
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: false pid=6561, uid=10375
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6657 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 2465): Scan Mode:20
,D/BluetoothAdapterState( 2465): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,W/Settings( 1478): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/bt-btif ( 2465): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 2465): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2465): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2465): L2CAP - PSM: 0x0017 not found for deregistration
,I/jxcore-log( 6561): ****TEST TOOK:  5210  ms ****
I/jxcore-log( 6561): 
I/jxcore-log( 6561): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6561): 
,W/Settings( 1478): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1478): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  495): NL - Read 60 bytes from update socket.
D/TCMD    (  495): NL - ignore NL message, type = 21
D/TCMD    (  495): Listening for incoming client connection request
,V/NativeCrypto( 1743): Read error: ssl=0xb8e13d68: I/O error during system call, Connection timed out
E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 95737
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): [1,450,199,099,513 ms] noteScanEnd no scan source
D/WifiScanningService(  880): SCAN_AVAILABLE : 1
D/WifiP2pService(  880): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  880): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  880): SCAN_AVAILABLE : 1
D/RttService(  880): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiP2pService(  880): P2pDisablingState
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  880): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): p2p socket connection lost
D/WifiP2pService(  880): P2pDisabledState
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,W/bt-btif ( 2465): ag scb idx 1 not allocated
E/bt-btif ( 2465): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2465): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2465): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2465): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2465): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2465): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2465): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 2465): exiting userial_read_thread
D/bt_userial_mct( 2465): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2465): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 2465): hw_epilog_process
D/bt_userial_mct( 2465): userial_close
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524292
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  880): stopping supplicant
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): setWifiState: disabling
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/art     (  880): Explicit concurrent mark sweep GC freed 44460(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 3.593ms total 185.113ms
,V/NativeCrypto( 1743): SSL shutdown failed: ssl=0xb8e13d68: I/O error during system call, Broken pipe
,D/TCMD    (  495): NL - Read 1004 bytes from update socket.
D/TCMD    (  495): NL - message type is RTM_NEWLINK
D/TCMD    (  495): Listening for incoming client connection request
D/TCMD    (  495): NL - Read 68 bytes from update socket.
D/TCMD    (  495): NL - message type is RTM_NEWLINK
D/TCMD    (  495): Listening for incoming client connection request
D/TCMD    (  495): NL - Read 68 bytes from update socket.
D/TCMD    (  495): NL - message type is RTM_NEWLINK
D/TCMD    (  495): Listening for incoming client connection request
D/Tethering(  880): InitialState.processMessage what=4
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1397): eap_proxy Deinitialzed
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
,D/AndroidRuntime( 6690): 
D/AndroidRuntime( 6690): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6690): CheckJNI is OFF
,I/bt_hwcfg( 2465): Starting hciattach daemon
I/bt_hwcfg( 2465): try to set false
,I/bt_vendor( 2465): cleanup
I/GKI_LINUX( 2465): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2465): GKI_exit_task 0 done
I/GKI_LINUX( 2465): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2465): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2465): mProfilesStarted : true supportedProfileServices.length : 7
,D/HeadsetService( 2465): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 2465): Stopping profile services that were post enabled
,D/HeadsetStateMachine( 2465): quit
,D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
,D/BluetoothHeadset(  880): Proxy object disconnected
D/AudioService(  880): onServiceDisconnected: Bluetooth profile: 1
,D/BluetoothHeadset( 1517): Proxy object disconnected
D/BluetoothHeadset( 1517): Proxy object disconnected
,D/BluetoothHeadset( 1552): Proxy object disconnected
,D/A2dpService( 2465): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2465): Exit Disconnected: -1
,D/HeadsetStateMachine( 2465): Exit Disconnected: -1
,D/TCMD    (  495): NL - Read 1004 bytes from update socket.
D/TCMD    (  495): NL - message type is RTM_NEWLINK
D/TCMD    (  495): Listening for incoming client connection request
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  292):  Wpa Supplicant Exiting !!
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
E/WifiStateMachine(  880): Supplicant connection lost
,D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
,D/BluetoothA2dp(  880): Proxy object disconnected
D/AudioService(  880): onServiceDisconnected: Bluetooth profile: 2
,D/HidService( 2465): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
,D/MDMCTBK (  292): wifi_close_sockets: Exit
,D/HealthService( 2465): Received stop request...Stopping profile...
,W/ResourcesManager( 6657): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
,D/PanService( 2465): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
D/BtGatt.DebugUtils( 2465): handleDebugAction() action=null
,D/BtGatt.GattService( 2465): Received stop request...Stopping profile...
D/BtGatt.GattService( 2465): stop()
,D/BtGatt.AdvertiseManager( 2465): advertise clients cleared
,D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
,D/BluetoothMapService( 2465): Received stop request...Stopping profile...
D/BluetoothMapService( 2465): stop()
,D/BluetoothMapEmailAppObserver( 2465): deinitObservers()
,D/BluetoothMapEmailAppObserver( 2465): removeReceiver()
D/BluetoothAdapterService( 2465): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5fb199
,D/HeadsetStateMachine( 2465): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2465): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2465): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 2465): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2465): GKI_exit_task 2 done
I/GKI_LINUX( 2465): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2465): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2465): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2465): Cleaning up Bluetooth GID callback object
,E/QC-QMI  (  429): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,W/BluetoothHealthServiceJni( 2465): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 2465): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2465): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2465): Cleaning up Bluetooth PAN callback object
,E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,D/BluetoothMapService( 2465): MAP Service closeService in
,D/BluetoothAdapterState( 2465): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2465): Setting state to 10
I/BluetoothAdapterState( 2465): Bluetooth adapter state changed: 13-> 10
,D/BluetoothMapService( 2465): cleanup()
D/BluetoothMapService( 2465): MAP Service closeService in
E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(false) to 5 receivers.
D/BluetoothHeadset(  880): onBluetoothStateChange: up=false
,E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
I/BluetoothAdapterState( 2465): Entering OffState
,D/BluetoothHeadset( 1517): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  880): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1552): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1517): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  880): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceDown() to 7 receivers.
,D/BluetoothManagerService(  880): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@cb6204a mBinding = false
,D/BluetoothManagerService(  880): Sending unbind request.
,D/BluetoothManagerService(  880): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1288): 943803460: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1288): 943803460: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 943803460: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2465): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2465): GKI_exit_task 1 done
,I/GKI_LINUX( 2465): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2465): cleanupNative: return from cleanup
,I/art     ( 2465): System.exit called, status: 0
I/AndroidRuntime( 2465): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1743): 904569019: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1743): 904569019: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 6657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AndroidRuntime( 6690): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Process com.android.bluetooth (pid 2465) has died
W/ActivityManager(  880): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,W/PackageSettings(  880): Skipping PackageSetting{299d48d0 com.test.thalitest/10374} due to missing metadata
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d5aa84:true
,I/ActivityManager(  880): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6718 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  880): Force stopping com.example.hello appid=10375 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6561:com.example.hello/u0a375 (adj 0): stop com.example.hello
,I/WindowState(  880): WIN DEATH: Window{25d9b8c1 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  880): Client connection lost with reason: 4
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{2e02f865 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  880): Display changed displayId=0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,E/WifiStateMachine(  880): setWifiState: disabled
,I/ActivityManager(  880): Force stopping com.example.hello appid=10375 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{2e02f865 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{2e02f865 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager(  880): Spurious death for ProcessRecord{806026d 6561:com.example.hello/u0a375}, curProc for 6561: null
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/GeofencerStateMachine( 1743): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/OtaApp  ( 2611): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2611): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2611): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2611): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
,W/Settings( 6340): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapter( 6657): 103902302: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 3040): Explicit concurrent mark sweep GC freed 7122(1291KB) AllocSpace objects, 3(50KB) LOS objects, 40% free, 7MB/12MB, paused 9.274ms total 107.006ms
,I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
,D/BluetoothManagerService(  880): Message: 30
I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
W/Settings( 1743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Decoder ( 1417): createOrResetDecoder
,W/ResourcesManager( 6718): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 6657): Adding local MAP profile
,D/BluetoothMap( 6657): Create BluetoothMap proxy object
D/BluetoothManagerService(  880): Message: 30
,I/art     ( 1570): Explicit concurrent mark sweep GC freed 4436(282KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 657us total 49.394ms
,I/ConfigService( 1743): onCreate
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 6657): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 6657): finishStartingService: stopping service
,I/ActivityManager(  880): Killing 6340:com.google.android.talk/u0a70 (adj 15): empty #7
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 19915(1190KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 1.060ms total 216.332ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
,W/InputMethodManagerService(  880): Got RemoteException sending setActive(false) notification to pid 6561 uid 10375
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
,I/art     (  880): Explicit concurrent mark sweep GC freed 17942(1152KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 2.371ms total 197.592ms
,D/AndroidRuntime( 6690): Shutting down VM
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6340/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 6718): Adding HeadsetService
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
D/AdapterServiceConfig( 6718): Adding A2dpService
D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
D/AdapterServiceConfig( 6718): Adding HidService
D/AdapterServiceConfig( 6718): Adding HealthService
D/AdapterServiceConfig( 6718): Adding PanService
,D/AdapterServiceConfig( 6718): Adding GattService
I/Launcher( 1570): Deferring update until onResume
D/AdapterServiceConfig( 6718): Adding BluetoothMapService
,D/TCMD    (  495): NL - Read 444 bytes from update socket.
,D/TCMD    (  495): NL - ignore NL message, type = 17
D/TCMD    (  495): Listening for incoming client connection request
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@306c32d3:true
,D/BluetoothAdapter( 6718): 741919604: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothPbap( 6657): Proxy object connected
,D/PbapServerProfile( 6657): Bluetooth service connected
D/BluetoothPbap( 6657): Proxy object disconnected
,D/PbapServerProfile( 6657): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1743): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  880): Killing 6380:android.process.acore/u0a7 (adj 15): empty #7
,D/TCMD    (  495): NL - Read 1004 bytes from update socket.
D/TCMD    (  495): NL - message type is RTM_NEWLINK
,D/TCMD    (  495): Listening for incoming client connection request
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6380/cgroup.procs: No such file or directory
,D/TCMD    (  495): NL - Read 444 bytes from update socket.
D/TCMD    (  495): NL - ignore NL message, type = 17
D/TCMD    (  495): Listening for incoming client connection request
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6759 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6759): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6780 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Checkin ( 3040): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3040): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  880): Killing 6432:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
