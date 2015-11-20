#### Test 50388019aa1a16d_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
--------- beginning of system
E/BackupManagerService(  883): Timeout restoring application @pm@
W/BackupManagerService(  883): Tried to clear data for @pm@ but not found
W/GmsBackupTransport( 1781): Restore processing aborted, no more packages
E/BackupManagerService(  883): Failure getting next package name
E/BackupManagerService(  883): Duplicate finish
D/AndroidRuntime( 6505): 
D/AndroidRuntime( 6505): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6505): CheckJNI is OFF
D/AndroidRuntime( 6505): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/LaunchCheckinHandler(  883): cleanup(): cleared. Last call was 23812 ms ago
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (153 us)
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 6505): Shutting down VM
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6524 uid=10305 gids={50305, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6524): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6524): Time to load native libraries: 2 ms (timestamps 8997-8999)
I/LibraryLoader( 6524): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6524): Binding Chromium to main looper Looper (main, tid 1) {2d7a5557}
I/LibraryLoader( 6524): Expected native library version number "",actual native library version number ""
I/chromium( 6524): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6524): Initializing chromium process, singleProcess=true
W/art     ( 6524): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6524): ApplicationContext is null in ApplicationStatus
W/chromium( 6524): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6524): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6524): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6524): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6524): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6524): Local Branch: 
I/Adreno-EGL( 6524): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6524): Local Patches: NONE
I/Adreno-EGL( 6524): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@334b7caf:true
W/art     ( 6524): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6524): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6524): CordovaWebView is running on device made by: motorola
W/art     ( 6524): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6524): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6524): Render dirty regions requested: true
D/Atlas   ( 6524): Validating map...
W/chromium( 6524): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/SFPerfTracer(  279):      triggers: (rate: 15:479) (compose: 0:2) (post: 0:1) (render: 0:2) (0:928 frames) (1:1013)
D/SFPerfTracer(  279):        layers: (3:10) (FocusedStackFrame (0xb7c70230): 1:12)* (DimLayer (0xb7ca2b50): 1:8)* (StatusBar (0xb7d1eb90): 0:120) (NavigationBar (0xb7d204f8): 0:21) (com.android.systemui.ImageWallpaper (0xb7d25d00): 0:31)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7d2c470): 0:62)- (Starting com.example.hello (0xb7ca6e58): 1:30) 
I/art     (  883): Explicit concurrent mark sweep GC freed 34773(1621KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.345ms total 130.796ms
I/OpenGLRenderer( 6524): Initialized EGL, version 1.4
D/OpenGLRenderer( 6524): Enabling debug mode 0
I/LaunchCheckinHandler(  883): Displayed com.example.hello/.MainActivity,cp,ca,1082
I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +1s82ms
I/Keyboard.Facilitator( 1419): onFinishInput()
E/Adreno-ES20( 6524): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6524): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6524): Cannot call determinedVisibility() - never saw a connection for the pid: 6524
I/chromium( 6524): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 6524): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 6524): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (18:248 vsyncs) (20:1036)
E/Adreno-ES20( 6524): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6524): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/jxcore_app_log( 6524): JniHelper::setJavaVM(0xb7da6310), pthread_self() = -1206651448
D/JX-Cordova( 6524): jxcore cordova android initializing
W/jxcore-log( 6524): Initializing JXcore engine
W/jxcore-log( 6524): JXcore engine is ready
W/jxcore-log( 6524): Starting JXcore engine
W/m.example.hello( 6524): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10305 path="socket:[5761]" dev="sockfs" ino=5761 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6524): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10305 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 6524): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10305 path="socket:[5873]" dev="sockfs" ino=5873 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6524): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10305 path="socket:[28272]" dev="sockfs" ino=28272 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6524): Platform android
W/jxcore-log( 6524): 
W/jxcore-log( 6524): Process ARCH arm
W/jxcore-log( 6524): 
I/jxcore-log( 6524): JXcore Cordova bridge is ready!
I/jxcore-log( 6524): 
W/jxcore-log( 6524): JXcore engine is started
,E/jxcore-log( 6524): >> motorola-XT1072
E/jxcore-log( 6524): 
I/jxcore-log( 6524): Total memory 916258816
I/jxcore-log( 6524): 
I/jxcore-log( 6524): Free memory 35090432
I/jxcore-log( 6524): 
I/jxcore-log( 6524): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6524): 
,I/jxcore-log( 6524): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6524): 
I/jxcore-log( 6524): userPath [ 'www' ]
I/jxcore-log( 6524): 
,I/jxcore-log( 6524): Size 720 1184
I/jxcore-log( 6524): 
,I/jxcore-log( 6524): Screen Brightness 82
I/jxcore-log( 6524): 
,E/jxcore-log( 6524): Dummy Error Log.
E/jxcore-log( 6524): 
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,I/jxcore-log( 6524): getBuffer is called!!!!
I/jxcore-log( 6524): 
,D/TaskPersister(  883): removeObsoleteFile: deleting file=28_task_thumbnail.png
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
D/        (  883): BstSensorExt: id=1598182242, en=0
D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 232
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  883): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb7bef550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  288): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb802c820
I/rmt_storage(  288): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  288): wakelock acquired: 1, error no: 42
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1207777144)
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1207777144) wakelock released: 1, error no: 0
I/rmt_storage(  288): 
,I/rmt_storage(  288): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb802c820
,V/AlarmManager(  883): send {203516bf, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {203516bf, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  883): Excessive delay in setPowerMode(): 361ms
,I/SFPerfTracer(  279):       trigger: frame rate (-32.594%)	(40.444 fps)	(24.726 ms) 	(4 drops)	(15 frames)
I/SFPerfTracer(  279):      triggers: (rate: 16:485) (compose: 0:3) (post: 0:1) (render: 0:3) (15:994 frames) (16:1093)
D/SFPerfTracer(  279):        layers: (4:11) (FocusedStackFrame (0xb7c70230): 0:14)* (DimLayer (0xb7ca2b50): 0:8)* (StatusBar (0xb7d1eb90): 0:120) (NavigationBar (0xb7d204f8): 0:21) (com.android.systemui.ImageWallpaper (0xb7d25d00): 0:31)* (Starting com.example.hello (0xb7ca6e58): 0:41)- (com.example.hello/com.example.hello.MainActivity (0xb7d2a128): 0:54) (ColorFade (0xb7ca6e58): 16:18) 
,I/WindowManager(  883): AOD feature not enabled!
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
E/msm8974_platform(  294): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  883): do suspend false
,D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
,I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/Keyboard.Facilitator( 1419): onFinishInput()
D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  883): do suspend true
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  883): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@307159f0 mBinding = false
,W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  883): Message: 2
,D/BluetoothManagerService(  883): Sending off request.
,D/BluetoothAdapterState( 2513): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2513): Setting state to 13
I/BluetoothAdapterState( 2513): Bluetooth adapter state changed: 12-> 13
,D/BluetoothManagerService(  883): Message: 60
D/BluetoothManagerService(  883): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  883): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 2513): onBluetoothDisable()
I/BluetoothAdapterState( 2513): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2513): Scan Mode:20
,D/BluetoothAdapterState( 2513): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/BluetoothMapService( 2513): onReceive
D/BluetoothMapService( 2513): STATE_TURNING_OFF
D/BluetoothMapService( 2513): MAP Service closeService in
D/BluetoothMapMasInstance( 2513): MAP Service shutdown
,E/BtOppRfcommListener( 2513): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2513): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,V/BluetoothMapMasInstance( 2513): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2513): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2513): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 2513): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 2513): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 2513): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2513): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2513): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 2513): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BtOppRfcommListener( 2513): stopping Accept Thread
,I/BtOppRfcommListener( 2513): BluetoothSocket listen thread finished
,W/bt-l2cap( 2513): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2513): L2CAP - PSM: 0x0017 not found for deregistration
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  883): New client listening to asynchronous messages
D/WifiService(  883): setWifiEnabled: false pid=6524, uid=10305
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 6524): ****TEST TOOK:  5170  ms ****
I/jxcore-log( 6524): 
I/jxcore-log( 6524): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6524): 
E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,I/ActivityManager(  883): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6635 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  289): Clearing all IP addresses on wlan0
D/TCMD    (  489): NL - Read 60 bytes from update socket.
D/TCMD    (  489): NL - ignore NL message, type = 21
D/TCMD    (  489): Listening for incoming client connection request
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,V/NativeCrypto( 1619): Read error: ssl=0xb8154b18: I/O error during system call, Connection timed out
,V/NativeCrypto( 1619): SSL shutdown failed: ssl=0xb8154b18: I/O error during system call, Broken pipe
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,D/WifiMetrics(  883): connected time updated 96741
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1417): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): [1,448,020,302,857 ms] noteScanEnd no scan source
,D/WifiScanningService(  883): SCAN_AVAILABLE : 1
D/RttService(  883): SCAN_AVAILABLE : 1
D/WifiScanningService(  883): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  883): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pDisablingState
D/WifiP2pService(  883): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): p2p socket connection lost
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  883): P2pDisabledState
,E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
I/bt_userial_mct( 2513): exiting userial_read_thread
D/bt_userial_mct( 2513): Leaving userial_evt_read_thread()
W/bt-btif ( 2513): ag scb idx 1 not allocated
E/bt-btif ( 2513): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2513): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2513): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2513): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2513): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2513): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2513): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 2513): userial_close_reader Joined userial reader thread: 0
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/bt_hwcfg( 2513): hw_epilog_process
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/bt_userial_mct( 2513): userial_close
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1971): CM callback handler got msg 524292
,E/WifiStateMachine(  883): stopping supplicant
,E/WifiStateMachine(  883): setWifiState: disabling
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,W/ResourcesManager( 6635): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ContextImpl( 6635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AuthorizationBluetoothService( 1619): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52a251c:true
,I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/TCMD    (  489): NL - Read 1004 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 68 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 68 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
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
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/Tethering(  883): InitialState.processMessage what=4
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6675 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1417): eap_proxy Deinitialzed
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/TCMD    (  489): NL - Read 1004 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
,I/wpa_supplicant( 1417): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292):  Wpa Supplicant Exiting !!
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
,E/WifiStateMachine(  883): Supplicant connection lost
D/MDMCTBK (  292): wifi_close_sockets: Exit
,I/bt_hwcfg( 2513): Starting hciattach daemon
I/bt_hwcfg( 2513): try to set false
I/bt_vendor( 2513): cleanup
I/GKI_LINUX( 2513): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2513): GKI_exit_task 0 done
I/GKI_LINUX( 2513): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2513): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2513): mProfilesStarted : true supportedProfileServices.length : 7
,D/HeadsetService( 2513): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2513): quit
D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
,D/BluetoothHeadset( 1521): Proxy object disconnected
D/BluetoothHeadset( 1556): Proxy object disconnected
D/BluetoothHeadset( 1521): Proxy object disconnected
D/HeadsetStateMachine( 2513): Exit Disconnected: -1
,D/BluetoothHeadset(  883): Proxy object disconnected
,D/AudioService(  883): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothAdapterState( 2513): Stopping profile services that were post enabled
,D/BluetoothManagerService(  883): Message: 30
D/A2dpService( 2513): Received stop request...Stopping profile...
D/A2dpStateMachine( 2513): Exit Disconnected: -1
,D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
,D/BluetoothA2dp(  883): Proxy object disconnected
D/AudioService(  883): onServiceDisconnected: Bluetooth profile: 2
,D/BluetoothManagerService(  883): Message: 30
D/HidService( 2513): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
D/HealthService( 2513): Received stop request...Stopping profile...
,D/LocalBluetoothProfileManager( 6635): Adding local MAP profile
,D/BluetoothMap( 6635): Create BluetoothMap proxy object
,D/BluetoothManagerService(  883): Message: 30
,D/AndroidRuntime( 6665): 
D/AndroidRuntime( 6665): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
,D/PanService( 2513): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
,D/BtGatt.DebugUtils( 2513): handleDebugAction() action=null
,D/BtGatt.GattService( 2513): Received stop request...Stopping profile...
D/BtGatt.GattService( 2513): stop()
,E/QC-QMI  (  433): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,D/BtGatt.AdvertiseManager( 2513): advertise clients cleared
,D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
,D/AndroidRuntime( 6665): CheckJNI is OFF
D/HeadsetStateMachine( 2513): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2513): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 2513): Cleaning up Bluetooth Handsfree callback object
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,D/BluetoothMapService( 2513): Received stop request...Stopping profile...
D/BluetoothMapService( 2513): stop()
D/BluetoothMapEmailAppObserver( 2513): deinitObservers()
D/BluetoothMapEmailAppObserver( 2513): removeReceiver()
D/BluetoothAdapterService( 2513): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d7a5557
E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
I/GKI_LINUX( 2513): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2513): GKI_exit_task 2 done
I/GKI_LINUX( 2513): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2513): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2513): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2513): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2513): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 2513): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2513): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2513): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 2513): MAP Service closeService in
D/BluetoothAdapterState( 2513): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2513): Setting state to 10
I/BluetoothAdapterState( 2513): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 2513): cleanup()
D/BluetoothMapService( 2513): MAP Service closeService in
D/BluetoothManagerService(  883): Message: 60
D/BluetoothManagerService(  883): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  883): Broadcasting onBluetoothStateChange(false) to 8 receivers.
I/BluetoothAdapterState( 2513): Entering OffState
D/BluetoothHeadset( 1521): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  883): onBluetoothStateChange: up=false
,D/BluetoothPan( 6635): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1556): onBluetoothStateChange: up=false
,D/BluetoothMap( 6635): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1521): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 6635): onBluetoothStateChange: up=false
D/LocalBluetoothProfileManager( 6635): LocalBluetoothProfileManager construction complete
D/BluetoothHeadset(  883): onBluetoothStateChange: up=false
W/ResourcesManager( 6675): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/BluetoothManagerService(  883): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  883): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/DockEventReceiver( 6635): finishStartingService: stopping service
D/BluetoothManagerService(  883): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@307159f0 mBinding = false
,I/ActivityManager(  883): Killing 6295:com.google.android.talk/u0a70 (adj 15): empty #7
D/BluetoothManagerService(  883): Sending unbind request.
,D/BluetoothManagerService(  883): Bluetooth State Change Intent: 13 -> 10
D/BluetoothManagerService(  883): Message: 30
,E/WifiStateMachine(  883): setWifiState: disabled
,D/BluetoothAdapter( 1295): 817169242: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1295): 817169242: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1295): 817169242: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1781): 341550621: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1781): 341550621: getState() :  mService = null. Returning STATE_OFF
,W/BroadcastQueue(  883): Failure sending broadcast Intent { act=android.net.wifi.supplicant.CONNECTION_CHANGE flg=0x4000010 (has extras) }
W/BroadcastQueue(  883): android.os.DeadObjectException
W/BroadcastQueue(  883): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  883): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  883): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1099)
W/BroadcastQueue(  883): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:449)
W/BroadcastQueue(  883): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:539)
W/BroadcastQueue(  883): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:587)
W/BroadcastQueue(  883): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:154)
W/BroadcastQueue(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  883): 	at android.os.Looper.loop(Looper.java:135)
W/BroadcastQueue(  883): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  883): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6295/cgroup.procs: No such file or directory
,I/GKI_LINUX( 2513): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2513): GKI_exit_task 1 done
I/GKI_LINUX( 2513): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2513): cleanupNative: return from cleanup
,W/Settings( 1781): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 2513): System.exit called, status: 0
I/AndroidRuntime( 2513): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6709 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.007ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.830ms
,D/AndroidRuntime( 6665): Calling main entry com.android.commands.pm.Pm
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.228ms
,W/PackageSettings(  883): Skipping PackageSetting{199e9c46 com.test.thalitest/10304} due to missing metadata
I/ActivityManager(  883): Process com.android.bluetooth (pid 2513) has died
,I/ActivityManager(  883): Force stopping com.example.hello appid=10305 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 6524:com.example.hello/u0a305 (adj 0): stop com.example.hello
,W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WindowState(  883): WIN DEATH: Window{30daef9f u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  883): Client connection lost with reason: 4
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{f650663 u0 com.example.hello/.MainActivity t29}
,V/ActivityManager(  883): Display changed displayId=0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  883): Force stopping com.example.hello appid=10305 user=0: pkg removed
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{f650663 u0 com.example.hello/.MainActivity t29 f}
,W/ActivityManager(  883): Duplicate finish request for ActivityRecord{f650663 u0 com.example.hello/.MainActivity t29 f}
,I/art     ( 3055): Explicit concurrent mark sweep GC freed 7112(1235KB) AllocSpace objects, 4(66KB) LOS objects, 39% free, 7MB/12MB, paused 614us total 39.062ms
,W/ActivityManager(  883): Spurious death for ProcessRecord{146042aa 6524:com.example.hello/u0a305}, curProc for 6524: null
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
W/GeofencerStateMachine( 1781): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Killing 6246:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/TCMD    (  489): NL - Read 444 bytes from update socket.
D/TCMD    (  489): NL - ignore NL message, type = 17
D/TCMD    (  489): Listening for incoming client connection request
,I/art     ( 1575): Explicit concurrent mark sweep GC freed 4331(276KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 487us total 86.202ms
,I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
,I/Decoder ( 1419): createOrResetDecoder
,D/TCMD    (  489): NL - Read 1004 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
,I/art     (  883): Explicit concurrent mark sweep GC freed 33744(1999KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/31MB, paused 1.776ms total 164.419ms
I/art     (  883): WaitForGcToComplete blocked for 131.422ms for cause Explicit
,I/ConfigService( 1619): onCreate
,D/TCMD    (  489): NL - Read 444 bytes from update socket.
D/TCMD    (  489): NL - ignore NL message, type = 17
D/TCMD    (  489): Listening for incoming client connection request
,D/OtaApp  ( 2638): [debug] > DownloadActivity, FormattedText
W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_6246/cgroup.procs: No such file or directory
I/OtaApp  ( 2638): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2638): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2638): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2638): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2638): publish the event [tag = MOT_OTA event name = LOG]
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 6524 uid 10305
,I/Keyboard.Facilitator( 1419): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
,I/Babel_SMS( 6709): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6709): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6709): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6709): MmsConfig.loadFromDatabase
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
,E/Babel_SMS( 6709): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6709): MmsConfig.loadFromResources
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
,E/Babel_SMS( 6709): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6709): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Launcher( 1575): Deferring update until onResume
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
,D/TaskPersister(  883): removeObsoleteFile: deleting file=29_task.xml
,D/TaskPersister(  883): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Too Soon
,I/art     (  883): Explicit concurrent mark sweep GC freed 7010(374KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.896ms total 236.766ms
,W/Settings( 6709): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6709): startup - clean
,I/Babel   ( 6709): deleted: false for 0
,D/AndroidRuntime( 6665): Shutting down VM
,W/ContextImpl( 6635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6753 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 6635): finishStartingService: stopping service
,D/Checkin ( 3055): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/AudioCapabilities( 6709): Unsupported mime audio/amr-wb-plus
,D/Checkin ( 3055): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/VideoCapabilities( 6709): Unsupported mime video/mpeg2
,W/ResourcesManager( 6753): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
I/VideoCapabilities( 6709): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 6331:android.process.acore/u0a7 (adj 15): empty #7
,D/Checkin ( 3055): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3055): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 3055): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6331/cgroup.procs: No such file or directory
,I/vclib   ( 6709): onServiceConnected
W/Babel   ( 6709): Attempted to change video mute state without an active call.
,D/AdapterServiceConfig( 6753): Adding HeadsetService
D/AdapterServiceConfig( 6753): Adding A2dpService
D/AdapterServiceConfig( 6753): Adding HidService
D/AdapterServiceConfig( 6753): Adding HealthService
D/AdapterServiceConfig( 6753): Adding PanService
D/AdapterServiceConfig( 6753): Adding GattService
D/AdapterServiceConfig( 6753): Adding BluetoothMapService
,I/ActivityManager(  883): Killing 6382:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/AuthorizationBluetoothService( 1619): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6382/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6774 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,D/Checkin ( 3055): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
