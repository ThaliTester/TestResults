#### Test 55634150e857e16_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,I/PowerManagerService(  879): Nap time (uid 1000)...
I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
--------- beginning of main
I/Adreno-EGL(  879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  879): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  879): Build Date: 10/28/14 Tue
I/Adreno-EGL(  879): Local Branch: 
I/Adreno-EGL(  879): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  879): Local Patches: NONE
I/Adreno-EGL(  879): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
D/AndroidRuntime( 6451): 
D/AndroidRuntime( 6451): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6451): CheckJNI is OFF
V/AlarmManager(  879): send {1de153ac, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  879): done {1de153ac, *alarm*:android.intent.action.TIME_TICK} [45ms]
D/AndroidRuntime( 6451): Calling main entry com.android.commands.am.Am
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/        (  879): activate, handle: 1598182242, enabled: 0, index 2
D/        (  879): BstSensorExt: id=1598182242, en=0
D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 239
D/        (  879): activate, handle: 2, enabled: 0, index 5
D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb8560550
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  879): Excessive delay in setPowerMode(): 328ms
I/WindowManager(  879): AOD feature not enabled!
I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/AndroidRuntime( 6451): Shutting down VM
I/ActivityManager(  879): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6478 uid=10439 gids={50439, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/PowerManagerService(  879): Sleeping (uid 1000)...
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  879): do suspend false
D/audio_hw_primary(  302): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  302): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  302): platform_set_parameters: exit with code(0)
E/msm8974_platform(  302): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  302): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  302): adev_set_parameters: ERROR: set param called even when stream out is null
I/rmt_storage(  297): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73f2820
I/rmt_storage(  297): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  297): wakelock acquired: 1, error no: 42
I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220597624)
I/WebViewFactory( 6478): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6478): Time to load native libraries: 2 ms (timestamps 5866-5868)
I/LibraryLoader( 6478): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6478): Binding Chromium to main looper Looper (main, tid 1) {16b8bbbf}
I/LibraryLoader( 6478): Expected native library version number "",actual native library version number ""
I/chromium( 6478): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6478): Initializing chromium process, singleProcess=true
W/art     ( 6478): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6478): ApplicationContext is null in ApplicationStatus
I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  297): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220597624) wakelock released: 1, error no: 0
I/rmt_storage(  297): 
I/rmt_storage(  297): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb73f2820
W/chromium( 6478): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6478): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6478): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6478): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6478): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6478): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6478): Local Branch: 
I/Adreno-EGL( 6478): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6478): Local Patches: NONE
I/Adreno-EGL( 6478): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36633408:true
D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
E/        (  879): <BST> disable accel, orig state: 1
I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
D/audio_hw_primary(  302): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  302): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  302): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  302): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  302): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  879): do suspend true
W/ActivityManager(  879): Activity pause timeout for ActivityRecord{300e4d8 u0 com.example.hello/.MainActivity t3}
W/art     ( 6478): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6478): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6478): CordovaWebView is running on device made by: motorola
W/art     ( 6478): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6478): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  879): Explicit concurrent mark sweep GC freed 37347(1890KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.311ms total 134.990ms
D/OpenGLRenderer( 6478): Render dirty regions requested: true
I/ThermalEngine(  312): Sensor:xo_therm_pu2:32000 mC
D/Atlas   ( 6478): Validating map...
W/chromium( 6478): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6478): Initialized EGL, version 1.4
D/OpenGLRenderer( 6478): Enabling debug mode 0
I/Keyboard.Facilitator( 1418): onFinishInput()
I/LaunchCheckinHandler(  879): Displayed com.example.hello/.MainActivity,cp,ca,1004
I/ActivityManager(  879): Displayed com.example.hello/.MainActivity: +921ms (total +1s5ms)
W/IInputConnectionWrapper( 6478): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6478): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6478): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6478): Cannot call determinedVisibility() - never saw a connection for the pid: 6478
I/chromium( 6478): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 6478): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 6478): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 6478): JniHelper::setJavaVM(0xb7a91310), pthread_self() = -1211001608
D/JX-Cordova( 6478): jxcore cordova android initializing
W/jxcore-log( 6478): Initializing JXcore engine
W/jxcore-log( 6478): JXcore engine is ready
W/jxcore-log( 6478): Starting JXcore engine
W/m.example.hello( 6478): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10439 path="socket:[7367]" dev="sockfs" ino=7367 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6478): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10439 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 6478): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10439 path="socket:[6736]" dev="sockfs" ino=6736 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6478): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10439 path="socket:[22181]" dev="sockfs" ino=22181 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6478): Platform android
W/jxcore-log( 6478): 
W/jxcore-log( 6478): Process ARCH arm
W/jxcore-log( 6478): 
,I/jxcore-log( 6478): JXcore Cordova bridge is ready!
I/jxcore-log( 6478): 
W/jxcore-log( 6478): JXcore engine is started
,E/jxcore-log( 6478): >> motorola-XT1072
E/jxcore-log( 6478): 
,I/jxcore-log( 6478): Total memory 916258816
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): Free memory 33849344
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): userPath [ 'www', 'www' ]
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): Size 720 1184
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): Screen Brightness 82
I/jxcore-log( 6478): 
,E/jxcore-log( 6478): Dummy Error Log.
E/jxcore-log( 6478): 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/jxcore-log( 6478): getBuffer is called!!!!
I/jxcore-log( 6478): 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/TaskPersister(  879): removeObsoleteFile: deleting file=2_task_thumbnail.png
,V/AlarmManager(  879): send {24a2f713, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {24a2f713, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  879): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2c5d2d50 mBinding = false
,W/Settings( 1475): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  879): Message: 2
,D/BluetoothManagerService(  879): Sending off request.
,D/BluetoothAdapterState( 2470): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2470): Setting state to 13
I/BluetoothAdapterState( 2470): Bluetooth adapter state changed: 12-> 13
,D/BluetoothManagerService(  879): Message: 60
D/BluetoothManagerService(  879): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  879): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 2470): onBluetoothDisable()
I/BluetoothAdapterState( 2470): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothMapService( 2470): onReceive
D/BluetoothMapService( 2470): STATE_TURNING_OFF
,D/BluetoothMapService( 2470): MAP Service closeService in
D/BluetoothMapMasInstance( 2470): MAP Service shutdown
,V/BluetoothMapMasInstance( 2470): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2470): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2470): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 2470): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 2470): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 2470): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2470): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2470): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/BtOppRfcommListener( 2470): stopping Accept Thread
,E/BtOppRfcommListener( 2470): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2470): BluetoothSocket listen thread finished
,I/ActivityManager(  879): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6571 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 2470): Scan Mode:20
D/BluetoothAdapterState( 2470): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,W/Settings( 1475): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/bt-btif ( 2470): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 2470): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2470): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 2470): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiService(  879): New client listening to asynchronous messages
,D/WifiService(  879): setWifiEnabled: false pid=6478, uid=10439
E/WifiService(  879): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6478): ****TEST TOOK:  5222  ms ****
I/jxcore-log( 6478): 
,I/jxcore-log( 6478): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6478): 
,E/WifiStateMachine(  879): WifiStateMachine: Leaving Connected state
W/Settings( 1475): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  879): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1475): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  298): Clearing all IP addresses on wlan0
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 21
D/TCMD    (  482): Listening for incoming client connection request
,V/NativeCrypto( 1749): Read error: ssl=0xb7ddef58: I/O error during system call, Connection timed out
,V/NativeCrypto( 1749): SSL shutdown failed: ssl=0xb7ddef58: I/O error during system call, Broken pipe
,D/ConnectivityService(  879): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine(  879): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiMetrics(  879): connected time updated 103497
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  879): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiScanningService(  879): SCAN_AVAILABLE : 1
D/RttService(  879): SCAN_AVAILABLE : 1
D/RttService(  879): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  879): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): [1,452,528,727,833 ms] noteScanEnd no scan source
D/WifiP2pService(  879): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiP2pService(  879): P2pDisablingState
D/WifiP2pService(  879): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): p2p socket connection lost
D/WifiP2pService(  879): P2pDisabledState
E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  879): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
,W/ResourcesManager( 6571): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ContextImpl( 6571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  879): Message: 20
,D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31efce7c:true
,D/WifiP2pService(  879): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt_userial_mct( 2470): exiting userial_read_thread
D/bt_userial_mct( 2470): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2470): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 2470): hw_epilog_process
,D/bt_userial_mct( 2470): userial_close
,W/bt-btif ( 2470): ag scb idx 1 not allocated
E/bt-btif ( 2470): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2470): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2470): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2470): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2470): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2470): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2470): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  879): Message: 30
,D/BluetoothManagerService(  879): Message: 30
,D/LocalBluetoothProfileManager( 6571): Adding local MAP profile
D/BluetoothMap( 6571): Create BluetoothMap proxy object
,D/BluetoothManagerService(  879): Message: 30
,D/BluetoothManagerService(  879): Message: 30
,D/LocalBluetoothProfileManager( 6571): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 6571): finishStartingService: stopping service
,D/BluetoothInputDevice( 6571): Proxy object connected
,D/HidProfile( 6571): Bluetooth service connected
,D/BluetoothPan( 6571): BluetoothPAN Proxy object connected
,D/PanProfile( 6571): Bluetooth service connected
D/BluetoothMap( 6571): Proxy object connected
,D/MapProfile( 6571): Bluetooth service connected
D/BluetoothMap( 6571): getConnectedDevices()
D/BluetoothMap( 6571): Bluetooth is Not enabled
,I/ActivityManager(  879): Killing 6249:com.google.android.talk/u0a70 (adj 15): empty #7
,I/bt_hwcfg( 2470): Starting hciattach daemon
I/bt_hwcfg( 2470): try to set false
,I/bt_vendor( 2470): cleanup
I/GKI_LINUX( 2470): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2470): GKI_exit_task 0 done
I/GKI_LINUX( 2470): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2470): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2470): mProfilesStarted : true supportedProfileServices.length : 7
,D/CommandListener(  298): Clearing all IP addresses on wlan0
,D/ConnectivityService(  879): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
D/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  879): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Disconnected - quitting
,D/AndroidRuntime( 6611): 
D/AndroidRuntime( 6611): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6249/cgroup.procs: No such file or directory
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/HeadsetService( 2470): Received stop request...Stopping profile...
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AndroidRuntime( 6611): CheckJNI is OFF
D/HeadsetStateMachine( 2470): quit
,D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,D/HeadsetStateMachine( 2470): Exit Disconnected: -1
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  879): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  879): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  879): stopping supplicant
,D/BluetoothHeadset( 1517): Proxy object disconnected
,D/BluetoothHeadset( 1517): Proxy object disconnected
,E/WifiStateMachine(  879): setWifiState: disabling
,D/A2dpService( 2470): Received stop request...Stopping profile...
D/BluetoothHeadset( 1553): Proxy object disconnected
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/A2dpStateMachine( 2470): Exit Disconnected: -1
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,D/BluetoothAdapterState( 2470): Stopping profile services that were post enabled
,D/HidService( 2470): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/HealthService( 2470): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/BluetoothInputDevice( 6571): Proxy object disconnected
,D/HidProfile( 6571): Bluetooth service disconnected
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  300): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  300):  STA Disconnected !!
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): get_property_value, Enter
I/MDMCTBK (  300): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  300): get_property_value, Exit
I/MDMCTBK (  300): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  300): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  300): set_property_value, Enter
I/MDMCTBK (  300): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/Tethering(  879): InitialState.processMessage what=4
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
,D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/MDMCTBK (  300): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  300): set_property_value, Exit
I/MDMCTBK (  300): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  300): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  300): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  300): set_property_value, Enter
I/MDMCTBK (  300): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  300): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  300): set_property_value, Exit
E/MDMCTBK (  300): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
D/BluetoothHeadset(  879): Proxy object disconnected
D/AudioService(  879): onServiceDisconnected: Bluetooth profile: 1
,D/BluetoothA2dp(  879): Proxy object disconnected
D/AudioService(  879): onServiceDisconnected: Bluetooth profile: 2
,D/HeadsetStateMachine( 2470): Unbinding service...
,D/Tethering(  879): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/BluetoothHeadsetServiceJni( 2470): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2470): Cleaning up Bluetooth Handsfree callback object
E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  0
D/Tethering(  879):  1
D/Tethering(  879):  5
D/Tethering(  879):  7
,D/Tethering(  879): sendTetherStateChangedBroadcast 0, 0, 0
D/PanService( 2470): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,D/BluetoothPan( 6571): BluetoothPAN Proxy object disconnected
D/PanProfile( 6571): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 2470): handleDebugAction() action=null
,D/BtGatt.GattService( 2470): Received stop request...Stopping profile...
D/BtGatt.GattService( 2470): stop()
I/wpa_supplicant( 1408): eap_proxy Deinitialzed
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  300): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/BtGatt.AdvertiseManager( 2470): advertise clients cleared
,D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,I/GKI_LINUX( 2470): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2470): GKI_exit_task 2 done
I/GKI_LINUX( 2470): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 2470): Received stop request...Stopping profile...
D/BluetoothMapService( 2470): stop()
,D/BluetoothMapEmailAppObserver( 2470): deinitObservers()
D/BluetoothMapEmailAppObserver( 2470): removeReceiver()
,D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16b8bbbf
,W/BluetoothHidServiceJni( 2470): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2470): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2470): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 2470): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2470): Cleaning up Bluetooth Health object
D/BluetoothMap( 6571): Proxy object disconnected
D/MapProfile( 6571): Bluetooth service disconnected
,W/BluetoothPanServiceJni( 2470): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2470): Cleaning up Bluetooth PAN callback object
,D/AuthorizationBluetoothService( 1749): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothMapService( 2470): MAP Service closeService in
D/BluetoothMapService( 2470): cleanup()
D/BluetoothMapService( 2470): MAP Service closeService in
D/BluetoothAdapterState( 2470): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2470): Setting state to 10
I/BluetoothAdapterState( 2470): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  879): Message: 60
D/BluetoothManagerService(  879): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  879): Broadcasting onBluetoothStateChange(false) to 9 receivers.
,I/BluetoothAdapterState( 2470): Entering OffState
D/BluetoothHeadset( 1517): onBluetoothStateChange: up=false
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  300): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  300):  Wpa Supplicant Exiting !!
D/MDMCTBK (  300): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  300): wifi_close_sockets: Close Wifi socket
,E/WifiStateMachine(  879): Supplicant connection lost
,D/MDMCTBK (  300): wifi_close_sockets: Exit
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6632 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/AndroidRuntime( 6611): Calling main entry com.android.commands.pm.Pm
,D/BluetoothHeadset( 1553): onBluetoothStateChange: up=false
D/BluetoothHeadset(  879): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  879): onBluetoothStateChange: up=false
,D/BluetoothPbap( 6571): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1517): onBluetoothStateChange: up=false
,D/BluetoothPan( 6571): onBluetoothStateChange on: false
E/QC-QMI  (  433): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/BluetoothMap( 6571): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 6571): onBluetoothStateChange: up=false
,W/PackageSettings(  879): Skipping PackageSetting{12dc954e com.test.thalitest/10437} due to missing metadata
,I/ActivityManager(  879): Force stopping com.example.hello appid=10439 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 6478:com.example.hello/u0a439 (adj 0): stop com.example.hello
,D/Checkin ( 3052): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3052): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/ResourcesManager( 6632): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/WindowState(  879): WIN DEATH: Window{204faf38 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
,I/ActivityManager(  879):   Force finishing activity ActivityRecord{300e4d8 u0 com.example.hello/.MainActivity t3}
,V/ActivityManager(  879): Display changed displayId=0
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  879): Spurious death for ProcessRecord{29c5530a 6478:com.example.hello/u0a439}, curProc for 6478: null
E/WifiStateMachine(  879): setWifiState: disabled
D/BluetoothManagerService(  879): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  879): Broadcasting onBluetoothServiceDown() to 7 receivers.
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/BluetoothManagerService(  879): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2c5d2d50 mBinding = false
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothManagerService(  879): Sending unbind request.
,I/ActivityManager(  879): Force stopping com.example.hello appid=10439 user=0: pkg removed
,W/Settings( 1749): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothManagerService(  879): Bluetooth State Change Intent: 13 -> 10
,I/Keyboard.Facilitator( 1418): resetDictionaries() : en_US
,D/OtaApp  ( 2590): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2590): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.DecoderInitializer( 1418): run()
,I/Decoder ( 1418): createOrResetDecoder
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/GKI_LINUX( 2470): gki_task task_id=1 [BTIF] terminating
D/OtaApp  ( 2590): [debug] > cancelling the previous pending intent set for download later
I/GKI_LINUX( 2470): GKI_exit_task 1 done
I/GKI_LINUX( 2470): GKI_shutdown(): task [BTIF] terminated
D/BluetoothAdapter( 1288): 1032744930: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 1032744930: getState() :  mService = null. Returning STATE_OFF
W/GeofencerStateMachine( 1749): Ignoring removeGeofence because network location is disabled.
D/BluetoothAdapter( 1288): 1032744930: getState() :  mService = null. Returning STATE_OFF
I/OtaApp  ( 2590): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2590): publish the event [tag = MOT_OTA event name = LOG]
,I/BluetoothServiceJni( 2470): cleanupNative: return from cleanup
,I/art     ( 1570): Explicit concurrent mark sweep GC freed 4331(275KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 501us total 105.280ms
,I/art     ( 2470): System.exit called, status: 0
I/AndroidRuntime( 2470): VM exiting with result code 0, cleanup skipped.
,I/art     ( 3052): Explicit concurrent mark sweep GC freed 10193(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 1.169ms total 57.092ms
,I/ConfigService( 1749): onCreate
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 20901(1249KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 1.050ms total 120.945ms
,D/BluetoothAdapter( 1749): 608973206: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1749): 608973206: getState() :  mService = null. Returning STATE_OFF
,I/art     (  879): Explicit concurrent mark sweep GC freed 28504(1730KB) AllocSpace objects, 5(270KB) LOS objects, 33% free, 20MB/31MB, paused 5.938ms total 166.754ms
I/art     (  879): WaitForGcToComplete blocked for 164.953ms for cause Explicit
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6662 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/InputMethodManagerService(  879): Got RemoteException sending setActive(false) notification to pid 6478 uid 10439
,I/Keyboard.Facilitator( 1418): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1418): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1418): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1418): run()
I/StatsUtilsManager( 1418): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1418): shouldRecordStats() = Too Soon
,I/ActivityManager(  879): Process com.android.bluetooth (pid 2470) has died
,I/ActivityManager(  879): Killing 6286:android.process.acore/u0a7 (adj 15): empty #7
,W/ResourcesManager( 6662): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  879): Explicit concurrent mark sweep GC freed 6204(333KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.963ms total 186.443ms
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6286/cgroup.procs: No such file or directory
,D/TCMD    (  482): NL - Read 444 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 17
D/TCMD    (  482): Listening for incoming client connection request
,D/TaskPersister(  879): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=2_task.xml
,I/Launcher( 1570): Deferring update until onResume
,D/AndroidRuntime( 6611): Shutting down VM
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/PhenotypeConfigurator( 1749): Scheduling Phenotype for one-off execution 12161 seconds from now (1452528729100)
,D/GetConfigurationSnapshotOperation( 1749): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/TCMD    (  482): NL - Read 444 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 17
,D/TCMD    (  482): Listening for incoming client connection request
,I/Babel_SMS( 6662): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6662): MmsConfig.loadMmsSettings
I/Babel_SMS( 6662): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6662): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6662): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6662): MmsConfig.loadFromResources
,E/Babel_SMS( 6662): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6662): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6662): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6662): startup - clean
,I/PhenotypeFlagCommitter( 1749): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1749): Using platform SSLCertificateSocketFactory
,I/Babel   ( 6662): deleted: false for 0
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6697 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 6662): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6662): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6662): Unsupported mime video/mpeg2
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,D/Checkin ( 3052): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3052): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]

```
