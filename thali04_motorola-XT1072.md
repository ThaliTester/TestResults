#### Test 50388019b17f598_thali04_motorola-XT1072 Logs


```
--------- beginning of main
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
E/WifiStateMachine(  881): [1,448,386,060,768 ms] noteScanEnd no scan source
E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@e65b7f5 sup_state=COMPLETED debouncing=false
V/GLSActivity( 1621): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1621): Vacuum at: now=1448386060919 tag=VacuumService
,D/GetConfigurationSnapshotOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/PhenotypeFlagCommitter( 1621): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1621): Using platform SSLCertificateSocketFactory
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/AndroidRuntime( 6273): 
D/AndroidRuntime( 6273): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6273): CheckJNI is OFF
D/UdcCache:FPQuery( 1967): Bootstrapping UDC settings cache for all accounts
V/GLSActivity( 1621): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1621): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6273): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (145 us)
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 6273): Shutting down VM
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6303 uid=10324 gids={50324, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6303): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
I/LibraryLoader( 6303): Time to load native libraries: 2 ms (timestamps 1405-1407)
I/LibraryLoader( 6303): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6303): Binding Chromium to main looper Looper (main, tid 1) {6b2610}
I/LibraryLoader( 6303): Expected native library version number "",actual native library version number ""
I/chromium( 6303): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6303): Initializing chromium process, singleProcess=true
W/art     ( 6303): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6303): ApplicationContext is null in ApplicationStatus
W/chromium( 6303): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/Uploader( 1621):  no longer exists, so no auth token.
E/libEGL  ( 6303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6303): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6303): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6303): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6303): Local Branch: 
I/Adreno-EGL( 6303): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6303): Local Patches: NONE
I/Adreno-EGL( 6303): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36ec04f0:true
I/SFPerfTracer(  279):      triggers: (rate: 14:479) (compose: 0:1) (post: 0:1) (render: 0:2) (18:942 frames) (19:1029)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb8b86980): 1:14)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8b2b408): 0:41)- (StatusBar (0xb8bca118): 0:135) (NavigationBar (0xb8bcbe30): 0:19) (com.android.systemui.ImageWallpaper (0xb8b53588): 0:8)* (DimLayer (0xb8b57848): 1:4) (Starting com.motorola.ccc.ota (0xb8b59560): 0:35)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8bd9ed8): 18:45) (Starting com.example.hello (0xb8b2b3a0): 2:4)* 
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/art     ( 6303): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6303): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6303): CordovaWebView is running on device made by: motorola
W/art     ( 6303): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6303): Attempt to remove local handle scope entry from IRT, ignoring
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/OpenGLRenderer( 6303): Render dirty regions requested: true
D/Atlas   ( 6303): Validating map...
W/chromium( 6303): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:237 vsyncs) (45:1055)
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
I/OpenGLRenderer( 6303): Initialized EGL, version 1.4
D/OpenGLRenderer( 6303): Enabling debug mode 0
I/Keyboard.Facilitator( 1420): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.example.hello/.MainActivity,cp,ca,960
I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +960ms
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
E/Adreno-ES20( 6303): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6303): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6303): Cannot call determinedVisibility() - never saw a connection for the pid: 6303
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
I/chromium( 6303): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/GetCommittedConfigurationOperation( 1621): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/JsMessageQueue( 6303): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 6303): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 6303): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6303): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 6303): JniHelper::setJavaVM(0xb8ec9310), pthread_self() = -1188720376
,D/JX-Cordova( 6303): jxcore cordova android initializing
,W/jxcore-log( 6303): Initializing JXcore engine
W/jxcore-log( 6303): JXcore engine is ready
W/jxcore-log( 6303): Starting JXcore engine
W/m.example.hello( 6303): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10324 path="socket:[5675]" dev="sockfs" ino=5675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6303): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10324 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 6303): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10324 path="socket:[6674]" dev="sockfs" ino=6674 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 6303): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10324 path="socket:[27899]" dev="sockfs" ino=27899 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6303): Platform android
W/jxcore-log( 6303): 
W/jxcore-log( 6303): Process ARCH arm
W/jxcore-log( 6303): 
I/jxcore-log( 6303): JXcore Cordova bridge is ready!
I/jxcore-log( 6303): 
W/jxcore-log( 6303): JXcore engine is started
E/jxcore-log( 6303): >> motorola-XT1072
E/jxcore-log( 6303): 
I/jxcore-log( 6303): Total memory 916258816
I/jxcore-log( 6303): 
I/jxcore-log( 6303): Free memory 32833536
I/jxcore-log( 6303): 
I/jxcore-log( 6303): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6303): 
I/jxcore-log( 6303): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6303): 
I/jxcore-log( 6303): userPath [ 'www' ]
I/jxcore-log( 6303): 
I/jxcore-log( 6303): Size 720 1184
I/jxcore-log( 6303): 
I/jxcore-log( 6303): Screen Brightness 82
I/jxcore-log( 6303): 
E/jxcore-log( 6303): Dummy Error Log.
E/jxcore-log( 6303): 
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 6303): getBuffer is called!!!!
I/jxcore-log( 6303): 
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/BackupManagerService(  881): Timeout restoring application @pm@
W/BackupManagerService(  881): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1762): Restore processing aborted, no more packages
E/BackupManagerService(  881): Failure getting next package name
E/BackupManagerService(  881): Duplicate finish
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@17ae5149 mBinding = false
,W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  881): Message: 2
,D/BluetoothManagerService(  881): Sending off request.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/BluetoothAdapterState( 2420): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2420): Setting state to 13
I/BluetoothAdapterState( 2420): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2420): onBluetoothDisable()
I/BluetoothAdapterState( 2420): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2420): Scan Mode:20
,D/BluetoothAdapterState( 2420): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/BtOppRfcommListener( 2420): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/WifiService(  881): New client listening to asynchronous messages
,V/BluetoothMapMasInstance( 2420): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2420): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2420): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 2420): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 2420): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 2420): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2420): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2420): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-btif ( 2420): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 2420): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2420): L2CAP - PSM: 0x0017 not found for deregistration
,D/WifiService(  881): setWifiEnabled: false pid=6303, uid=10324
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,D/btif_config_util( 2420): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2420): onReceive
D/BluetoothMapService( 2420): STATE_TURNING_OFF
,D/BluetoothMapService( 2420): MAP Service closeService in
D/BluetoothMapMasInstance( 2420): MAP Service shutdown
,I/BtOppRfcommListener( 2420): stopping Accept Thread
I/BtOppRfcommListener( 2420): BluetoothSocket listen thread finished
,E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 6303): ****TEST TOOK:  5204  ms ****
I/jxcore-log( 6303): 
,I/jxcore-log( 6303): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6303): 
,I/ActivityManager(  881): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6415 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  289): Clearing all IP addresses on wlan0
D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,V/NativeCrypto( 1621): Read error: ssl=0xb91b7cc8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1621): SSL shutdown failed: ssl=0xb91b7cc8: I/O error during system call, Broken pipe
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  881): connected time updated 89265
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/wpa_supplicant( 1427): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1427): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): [1,448,386,069,145 ms] noteScanEnd no scan source
D/WifiScanningService(  881): SCAN_AVAILABLE : 1
D/RttService(  881): SCAN_AVAILABLE : 1
,D/WifiP2pService(  881): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pDisablingState
D/WifiP2pService(  881): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): p2p socket connection lost
,D/WifiP2pService(  881): P2pDisabledState
D/WifiScanningService(  881): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  881): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 2420): ag scb idx 1 not allocated
E/bt-btif ( 2420): BTA AG is already disabled, ignoring ...
,I/bt_userial_mct( 2420): exiting userial_read_thread
D/bt_userial_mct( 2420): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2420): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 2420): hw_epilog_process
W/bt-l2cap( 2420): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2420): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2420): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2420): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2420): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2420): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 2420): userial_close
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  881): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  881): Explicit concurrent mark sweep GC freed 40977(1924KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.691ms total 173.257ms
,W/ResourcesManager( 6415): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/bt_hwcfg( 2420): Starting hciattach daemon
I/bt_hwcfg( 2420): try to set false
I/bt_vendor( 2420): cleanup
I/GKI_LINUX( 2420): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2420): GKI_exit_task 0 done
D/AndroidRuntime( 6446): 
D/AndroidRuntime( 6446): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/GKI_LINUX( 2420): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2420): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterService( 2420): mProfilesStarted : true supportedProfileServices.length : 7
,D/AndroidRuntime( 6446): CheckJNI is OFF
,D/HeadsetService( 2420): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2420): quit
D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
D/HeadsetStateMachine( 2420): Exit Disconnected: -1
D/BluetoothAdapterState( 2420): Stopping profile services that were post enabled
,D/A2dpService( 2420): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2420): Exit Disconnected: -1
,D/BluetoothHeadset( 1520): Proxy object disconnected
D/BluetoothHeadset( 1520): Proxy object disconnected
,D/BluetoothHeadset( 1555): Proxy object disconnected
,D/BluetoothHeadset(  881): Proxy object disconnected
D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 1
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
,D/HidService( 2420): Received stop request...Stopping profile...
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524292
D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
D/ConnectivityManager.CallbackHandler( 1967): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,D/HealthService( 2420): Received stop request...Stopping profile...
,D/BluetoothA2dp(  881): Proxy object disconnected
D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 2
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
D/PanService( 2420): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
D/BtGatt.DebugUtils( 2420): handleDebugAction() action=null
E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/BtGatt.GattService( 2420): Received stop request...Stopping profile...
D/BtGatt.GattService( 2420): stop()
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,D/BtGatt.AdvertiseManager( 2420): advertise clients cleared
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ContextImpl( 6415): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): stopping supplicant
D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
,D/BluetoothMapService( 2420): Received stop request...Stopping profile...
,D/BluetoothMapService( 2420): stop()
D/BluetoothMapEmailAppObserver( 2420): deinitObservers()
D/BluetoothMapEmailAppObserver( 2420): removeReceiver()
,D/BluetoothAdapterService( 2420): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b2610
E/WifiStateMachine(  881): setWifiState: disabling
,D/HeadsetStateMachine( 2420): Unbinding service...
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/BluetoothHeadsetServiceJni( 2420): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2420): Cleaning up Bluetooth Handsfree callback object
,I/GKI_LINUX( 2420): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2420): GKI_exit_task 2 done
,I/GKI_LINUX( 2420): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2420): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2420): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 2420): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 2420): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 2420): Cleaning up Bluetooth Health object
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2901b905:true
,W/BluetoothPanServiceJni( 2420): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2420): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 2420): MAP Service closeService in
,D/BluetoothMapService( 2420): cleanup()
D/BluetoothMapService( 2420): MAP Service closeService in
,D/BluetoothAdapterState( 2420): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 2420): Setting state to 10
,I/BluetoothAdapterState( 2420): Bluetooth adapter state changed: 13-> 10
,I/BluetoothAdapterState( 2420): Entering OffState
D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  881): Broadcasting onBluetoothStateChange(false) to 5 receivers.
,D/BluetoothA2dp(  881): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1555): onBluetoothStateChange: up=false
,I/wpa_supplicant( 1427): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/AuthorizationBluetoothService( 1621): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothHeadset( 1520): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1520): onBluetoothStateChange: up=false
D/BluetoothHeadset(  881): onBluetoothStateChange: up=false
D/BluetoothManagerService(  881): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  881): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  881): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@17ae5149 mBinding = false
D/BluetoothManagerService(  881): Sending unbind request.
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 13 -> 10
,I/wpa_supplicant( 1427): eap_proxy Deinitialzed
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6470 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
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
D/BluetoothManagerService(  881): Message: 30
,I/GKI_LINUX( 2420): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2420): GKI_exit_task 1 done
I/GKI_LINUX( 2420): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2420): cleanupNative: return from cleanup
,I/art     ( 2420): System.exit called, status: 0
I/AndroidRuntime( 2420): VM exiting with result code 0, cleanup skipped.
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1427): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292):  Wpa Supplicant Exiting !!
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  292): wifi_close_sockets: Exit
E/WifiStateMachine(  881): Supplicant connection lost
,I/art     ( 1555): Explicit concurrent mark sweep GC freed 33354(2MB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.381ms total 130.421ms
,D/AndroidRuntime( 6446): Calling main entry com.android.commands.pm.Pm
,D/BluetoothAdapter( 1292): 802179188: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1292): 802179188: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1292): 802179188: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  881): Message: 30
,D/BluetoothAdapter( 1762): 943927243: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1762): 943927243: getState() :  mService = null. Returning STATE_OFF
,E/QC-QMI  (  438): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  438): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  438): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  438): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  438): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,I/ActivityManager(  881): Process com.android.bluetooth (pid 2420) has died
,W/PackageSettings(  881): Skipping PackageSetting{ef74683 com.test.thalitest/10323} due to missing metadata
,I/ActivityManager(  881): Force stopping com.example.hello appid=10324 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6303:com.example.hello/u0a324 (adj 0): stop com.example.hello
D/LocalBluetoothProfileManager( 6415): Adding local MAP profile
D/BluetoothMap( 6415): Create BluetoothMap proxy object
,D/BluetoothManagerService(  881): Message: 30
D/Checkin ( 2968): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2968): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/WindowState(  881): WIN DEATH: Window{187e8095 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,I/rmt_storage(  288): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7038820
,I/rmt_storage(  288): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  288): wakelock acquired: 1, error no: 42
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1224505208)
,W/ActivityManager(  881): Force removing ActivityRecord{deb0fa8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1224505208) wakelock released: 1, error no: 0
I/rmt_storage(  288): 
,I/rmt_storage(  288): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7038820
,E/WifiStateMachine(  881): setWifiState: disabled
I/ActivityManager(  881): Force stopping com.example.hello appid=10324 user=0: pkg removed
,W/ResourcesManager( 6470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager(  881): Spurious death for ProcessRecord{19b11eb9 6303:com.example.hello/u0a324}, curProc for 6303: null
,W/GeofencerStateMachine( 1762): Ignoring removeGeofence because network location is disabled.
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
D/OtaApp  ( 2543): [debug] > DownloadActivity, FormattedText
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
I/OtaApp  ( 2543): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2543): publish the event [tag = MOT_OTA event name = LOG]
,D/BluetoothManagerService(  881): Message: 30
,W/ResourcesManager( 1555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     ( 2968): Explicit concurrent mark sweep GC freed 7878(1475KB) AllocSpace objects, 3(50KB) LOS objects, 39% free, 7MB/12MB, paused 589us total 52.175ms
,I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
I/Decoder ( 1420): createOrResetDecoder
,W/Settings( 1762): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/OtaApp  ( 2543): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2543): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2543): publish the event [tag = MOT_OTA event name = LOG]
,D/LocalBluetoothProfileManager( 6415): LocalBluetoothProfileManager construction complete
,I/art     ( 1574): Explicit concurrent mark sweep GC freed 4415(280KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 511us total 95.711ms
,I/ConfigService( 1621): onCreate
W/InputMethodManagerService(  881): Got RemoteException sending setActive(false) notification to pid 6303 uid 10324
,D/DockEventReceiver( 6415): finishStartingService: stopping service
I/Keyboard.Facilitator( 1420): onFinishInput()
,I/ActivityManager(  881): Killing 5880:com.android.vending/u0a32 (adj 15): empty #7
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  881): Explicit concurrent mark sweep GC freed 16900(1126KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.304ms total 175.033ms
,D/AndroidRuntime( 6446): Shutting down VM
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_5880/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1420): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1420): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1420): run()
I/StatsUtilsManager( 1420): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1420): shouldRecordStats() = Too Soon
,I/Babel_SMS( 6470): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6470): MmsConfig.loadMmsSettings
I/Babel_SMS( 6470): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6470): MmsConfig.loadFromDatabase
,D/TCMD    (  480): NL - Read 444 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 17
D/TCMD    (  480): Listening for incoming client connection request
,E/Babel_SMS( 6470): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6470): MmsConfig.loadFromResources
,E/Babel_SMS( 6470): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6470): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/Settings( 6470): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TCMD    (  480): NL - Read 444 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 17
D/TCMD    (  480): Listening for incoming client connection request
,I/Babel_Crash( 6470): startup - clean
I/Launcher( 1574): Deferring update until onResume
,I/Babel   ( 6470): deleted: false for 0
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6519 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/qdoverlay(  279): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  279): src msmfb_img w=736 h=64 format=13 MDP_RGBA_8888
E/qdoverlay(  279): src_rect mdp_rect x=0 y=0 w=720 h=50
E/qdoverlay(  279): dst_rect mdp_rect x=0 y=0 w=720 h=50
E/qdoverlay(  279): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  279): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  279): src_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  279): dst_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  279): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  279): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  279): src_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  279): dst_rect mdp_rect x=0 y=0 w=720 h=1280
E/qdoverlay(  279): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  279): MdpCtrl close error in unset
,W/VideoCapabilities( 6470): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6470): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6470): Unsupported mime video/mpeg2
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,E/qdoverlay(  279): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  279): MdpCtrl close error in unset

```
