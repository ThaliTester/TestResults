#### Test 503880197c51433_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/AndroidRuntime( 5899): 
D/AndroidRuntime( 5899): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5899): CheckJNI is OFF
D/AndroidRuntime( 5899): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/LaunchCheckinHandler(  881): cleanup(): cleared. Last call was 20534 ms ago
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (163 us)
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5899): Shutting down VM
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5918 uid=10316 gids={50316, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5918): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5918): Time to load native libraries: 14 ms (timestamps 3695-3709)
I/LibraryLoader( 5918): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5918): Binding Chromium to main looper Looper (main, tid 1) {2a6c33ad}
I/LibraryLoader( 5918): Expected native library version number "",actual native library version number ""
I/chromium( 5918): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5918): Initializing chromium process, singleProcess=true
W/art     ( 5918): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5918): ApplicationContext is null in ApplicationStatus
W/chromium( 5918): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5918): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5918): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5918): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5918): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5918): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5918): Local Branch: 
I/Adreno-EGL( 5918): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5918): Local Patches: NONE
I/Adreno-EGL( 5918): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
I/SFPerfTracer(  279):      triggers: (rate: 12:562) (compose: 0:1) (post: 0:1) (render: 0:2) (18:847 frames) (19:940)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb715d388): 1:12)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb70c9b90): 0:39)- (StatusBar (0xb7169688): 0:144) (NavigationBar (0xb716cdb0): 0:22) (com.android.systemui.ImageWallpaper (0xb71097c0): 0:31)* (DimLayer (0xb710d518): 1:4) (Starting com.motorola.ccc.ota (0xb710f908): 0:30)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7176fa8): 18:47) (Starting com.example.hello (0xb70c9b90): 2:4)* 
I/ActivityManager(  881): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5943 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  881): send {1e9fe985, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  881): send {280e863a, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
V/AlarmManager(  881): send {18823997, *alarm*:com.android.server.WifiManager.action.START_SCAN}
V/AlarmManager(  881): done {1e9fe985, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [58ms]
V/AlarmManager(  881): done {280e863a, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [79ms]
E/WifiStateMachine(  881): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=20.83 rxSuccessRate=14.93 targetRoamBSSID=any RSSI=-58
E/WifiStateMachine(  881): WifiStateMachine CMD_START_SCAN with age=51446 interval=30000 maxinterval=300000
E/WifiStateMachine(  881): WifiStateMachine CMD_START_SCAN try full band scan age=51446 interval=30000 maxinterval=300000
E/WifiStateMachine(  881): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  881): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  881): WifiStateMachine starting scan for "NG700"WPA_PSK with 2462
E/WifiStateMachine(  881): [1,420,590,065,614 ms] noteScanstart no scan source
I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
V/AlarmManager(  881): done {18823997, *alarm*:com.android.server.WifiManager.action.START_SCAN} [83ms]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  486): NL - Read 56 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
E/WifiStateMachine(  881): [1,420,590,065,682 ms] noteScanEnd no scan source
E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@31b4779e sup_state=COMPLETED debouncing=false
I/art     (  881): Explicit concurrent mark sweep GC freed 31360(1525KB) AllocSpace objects, 1(118KB) LOS objects, 33% free, 20MB/31MB, paused 1.778ms total 140.511ms
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@330a5432:true
D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
D/Finsky  ( 5943): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 23 Nov 2015 17:17:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1420590065925], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1420590065912]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 3420): CM callback handler got msg 524290
W/art     ( 5918): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5918): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5918): CordovaWebView is running on device made by: motorola
W/art     ( 5918): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5918): Attempt to remove local handle scope entry from IRT, ignoring
D/Finsky  ( 5943): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5943): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5943): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/OpenGLRenderer( 5918): Render dirty regions requested: true
D/Atlas   ( 5918): Validating map...
W/chromium( 5918): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/Finsky  ( 5943): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5943): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5943): Skipping gmscore version check
D/Finsky  ( 5943): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5943): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/OpenGLRenderer( 5918): Initialized EGL, version 1.4
D/OpenGLRenderer( 5918): Enabling debug mode 0
I/Keyboard.Facilitator( 1412): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.example.hello/.MainActivity,cp,ca,1113
I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +1s113ms
D/Finsky  ( 5943): [690] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5943): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/Adreno-ES20( 5918): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5918): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 5918): Cannot call determinedVisibility() - never saw a connection for the pid: 5918
I/chromium( 5918): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 5918): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5918): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/jxcore_app_log( 5918): JniHelper::setJavaVM(0xb8039310), pthread_self() = -1203960632
D/JX-Cordova( 5918): jxcore cordova android initializing
,E/Adreno-ES20( 5918): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5918): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/Babel_CronetHttpRequestSender( 5579): Http error response 
,W/Babel_CronetHttpRequestSender( 5579): Cronet HTTP request failed
W/Babel_CronetHttpRequestSender( 5579): java.io.IOException: System error: net::ERR_ABORTED(-3)
W/Babel_CronetHttpRequestSender( 5579): 	at org.chromium.net.ChromiumUrlRequest.d(SourceFile:185)
W/Babel_CronetHttpRequestSender( 5579): 	at bux.b(SourceFile:79)
W/Babel_CronetHttpRequestSender( 5579): 	at org.chromium.net.ChromiumUrlRequest.finish(SourceFile:2501)
,W/Babel_RequestWriter( 5579): Error making http request: url https://www.googleapis.com/chat/v1android/devices/registerdevice?alt=proto
W/Babel_RequestWriter( 5579): java.io.IOException: System error: net::ERR_ABORTED(-3)
W/Babel_RequestWriter( 5579): 	at org.chromium.net.ChromiumUrlRequest.d(SourceFile:185)
W/Babel_RequestWriter( 5579): 	at bux.b(SourceFile:79)
W/Babel_RequestWriter( 5579): 	at org.chromium.net.ChromiumUrlRequest.finish(SourceFile:2501)
,W/jxcore-log( 5918): Initializing JXcore engine
W/jxcore-log( 5918): JXcore engine is ready
,W/jxcore-log( 5918): Starting JXcore engine
,W/m.example.hello( 5918): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10316 path="socket:[5580]" dev="sockfs" ino=5580 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 5918): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10316 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5918): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10316 path="socket:[6886]" dev="sockfs" ino=6886 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 5918): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10316 path="socket:[23362]" dev="sockfs" ino=23362 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5918): Platform android
W/jxcore-log( 5918): 
W/jxcore-log( 5918): Process ARCH arm
W/jxcore-log( 5918): 
,I/jxcore-log( 5918): JXcore Cordova bridge is ready!
I/jxcore-log( 5918): 
W/jxcore-log( 5918): JXcore engine is started
,E/jxcore-log( 5918): >> motorola-XT1072
E/jxcore-log( 5918): 
I/jxcore-log( 5918): Total memory 916258816
I/jxcore-log( 5918): 
I/jxcore-log( 5918): Free memory 35278848
I/jxcore-log( 5918): 
I/jxcore-log( 5918): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5918): 
I/jxcore-log( 5918): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5918): 
I/jxcore-log( 5918): userPath [ 'www' ]
I/jxcore-log( 5918): 
,I/jxcore-log( 5918): Size 720 1184
I/jxcore-log( 5918): 
,I/jxcore-log( 5918): Screen Brightness 82
I/jxcore-log( 5918): 
,E/jxcore-log( 5918): Dummy Error Log.
E/jxcore-log( 5918): 
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:245 vsyncs) (2:1013)
,I/jxcore-log( 5918): getBuffer is called!!!!
I/jxcore-log( 5918): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:35000 mC
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task_thumbnail.png
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  881): Killing 5788:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_5788/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37cf251d mBinding = false
,W/Settings( 1466): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  881): Message: 2
,D/BluetoothManagerService(  881): Sending off request.
,D/BluetoothAdapterState( 2514): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2514): Setting state to 13
,I/BluetoothAdapterState( 2514): Bluetooth adapter state changed: 12-> 13
,D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 12 -> 13
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/BluetoothMapService( 2514): onReceive
,D/BluetoothMapService( 2514): STATE_TURNING_OFF
,D/BluetoothAdapterProperties( 2514): onBluetoothDisable()
,D/BluetoothMapService( 2514): MAP Service closeService in
D/BluetoothMapMasInstance( 2514): MAP Service shutdown
,I/BluetoothAdapterState( 2514): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,V/BluetoothMapMasInstance( 2514): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2514): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2514): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 2514): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 2514): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 2514): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2514): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2514): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 2514): stopping Accept Thread
,E/BtOppRfcommListener( 2514): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2514): BluetoothSocket listen thread finished
,D/WifiService(  881): New client listening to asynchronous messages
,W/Settings( 1466): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  881): setWifiEnabled: false pid=5918, uid=10316
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 5918): ****TEST TOOK:  5163  ms ****
I/jxcore-log( 5918): 
,I/jxcore-log( 5918): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5918): 
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  292): Clearing all IP addresses on wlan0
D/TCMD    (  486): NL - Read 60 bytes from update socket.
D/TCMD    (  486): NL - ignore NL message, type = 21
D/TCMD    (  486): Listening for incoming client connection request
I/ActivityManager(  881): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6052 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BluetoothAdapterProperties( 2514): Scan Mode:20
D/BluetoothAdapterState( 2514): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/bt-btif ( 2514): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2514): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2514): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 2514): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  881): connected time updated 59186
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1415): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  881): [1,420,590,072,729 ms] noteScanEnd no scan source
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiP2pService(  881): InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  881): SCAN_AVAILABLE : 1
D/WifiP2pService(  881): P2pDisablingState
D/RttService(  881): SCAN_AVAILABLE : 1
D/WifiP2pService(  881): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): p2p socket connection lost
,D/WifiP2pService(  881): P2pDisabledState
D/WifiScanningService(  881): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
D/RttService(  881): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  881): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 3420): CM callback handler got msg 524292
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=null
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): stopping supplicant
,E/WifiStateMachine(  881): setWifiState: disabling
I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 68 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
D/TCMD    (  486): NL - Read 68 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,D/Tethering(  881): InitialState.processMessage what=4
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
,I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
,I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
,I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
E/Tethering(  881): ApnList is empty for checkDunConfigured()
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
D/Tethering(  881):  upstream interface types: 
,I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/Tethering(  881):  0
D/Tethering(  881):  1
,D/Tethering(  881):  5
D/Tethering(  881):  7
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1415): eap_proxy Deinitialzed
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 0
,W/bt-btif ( 2514): ag scb idx 1 not allocated
E/bt-btif ( 2514): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2514): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2514): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2514): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2514): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2514): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2514): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 2514): exiting userial_read_thread
D/bt_userial_mct( 2514): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2514): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 2514): hw_epilog_process
D/bt_userial_mct( 2514): userial_close
,W/ResourcesManager( 6052): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,I/wpa_supplicant( 1415): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  294): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  294):  Wpa Supplicant Exiting !!
D/MDMCTBK (  294): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  294): wifi_close_sockets: Close Wifi socket
,E/WifiStateMachine(  881): Supplicant connection lost
,D/MDMCTBK (  294): wifi_close_sockets: Exit
,W/ContextImpl( 6052): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AuthorizationBluetoothService( 1668): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  881): Message: 20
,D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ae3b160:true
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6092 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/AndroidRuntime( 6082): 
D/AndroidRuntime( 6082): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6082): CheckJNI is OFF
,I/bt_hwcfg( 2514): Starting hciattach daemon
I/bt_hwcfg( 2514): try to set false
E/QC-QMI  (  436): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,I/bt_vendor( 2514): cleanup
I/GKI_LINUX( 2514): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2514): GKI_exit_task 0 done
I/GKI_LINUX( 2514): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2514): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2514): mProfilesStarted : true supportedProfileServices.length : 7
,D/HeadsetService( 2514): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2514): quit
,D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
D/HeadsetStateMachine( 2514): Exit Disconnected: -1
E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,D/BluetoothHeadset( 1513): Proxy object disconnected
E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/BluetoothHeadset( 1513): Proxy object disconnected
D/BluetoothHeadset(  881): Proxy object disconnected
D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 1
,D/BluetoothManagerService(  881): Message: 30
,D/BluetoothHeadset( 1536): Proxy object disconnected
,E/WifiStateMachine(  881): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothAdapterState( 2514): Stopping profile services that were post enabled
,D/A2dpService( 2514): Received stop request...Stopping profile...
D/A2dpStateMachine( 2514): Exit Disconnected: -1
,W/Settings( 5579): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
,D/BluetoothA2dp(  881): Proxy object disconnected
D/HidService( 2514): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
,D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 2
,D/HealthService( 2514): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
,D/PanService( 2514): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
,D/BtGatt.DebugUtils( 2514): handleDebugAction() action=null
,D/BtGatt.GattService( 2514): Received stop request...Stopping profile...
,D/BtGatt.GattService( 2514): stop()
,D/BtGatt.AdvertiseManager( 2514): advertise clients cleared
,D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
,D/HeadsetStateMachine( 2514): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2514): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2514): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothMapService( 2514): Received stop request...Stopping profile...
D/BluetoothMapService( 2514): stop()
,D/BluetoothMapEmailAppObserver( 2514): deinitObservers()
,D/BluetoothMapEmailAppObserver( 2514): removeReceiver()
,W/Settings( 1763): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothAdapterService( 2514): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a6c33ad
,I/GKI_LINUX( 2514): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2514): GKI_exit_task 2 done
,I/GKI_LINUX( 2514): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2514): Cleaning up Bluetooth HID Interface...
,D/BluetoothManagerService(  881): Message: 30
,D/LocalBluetoothProfileManager( 6052): Adding local MAP profile
W/ResourcesManager( 6092): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/bt-btif ( 2514): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2514): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2514): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2514): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2514): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2514): Cleaning up Bluetooth PAN callback object
D/BluetoothMap( 6052): Create BluetoothMap proxy object
D/BluetoothManagerService(  881): Message: 30
D/BluetoothMapService( 2514): MAP Service closeService in
D/BluetoothMapService( 2514): cleanup()
D/BluetoothMapService( 2514): MAP Service closeService in
D/BluetoothAdapterState( 2514): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2514): Setting state to 10
I/BluetoothAdapterState( 2514): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  881): Broadcasting onBluetoothStateChange(false) to 8 receivers.
I/BluetoothAdapterState( 2514): Entering OffState
D/BluetoothHeadset( 1513): onBluetoothStateChange: up=false
D/BluetoothHeadset(  881): onBluetoothStateChange: up=false
D/BluetoothPan( 6052): onBluetoothStateChange on: false
D/BluetoothHeadset( 1513): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1536): onBluetoothStateChange: up=false
D/LocalBluetoothProfileManager( 6052): LocalBluetoothProfileManager construction complete
,D/BluetoothInputDevice( 6052): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  881): onBluetoothStateChange: up=false
D/BluetoothMap( 6052): onBluetoothStateChange: up=false
D/BluetoothManagerService(  881): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  881): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  881): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@37cf251d mBinding = false
D/BluetoothManagerService(  881): Sending unbind request.
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 13 -> 10
D/BluetoothManagerService(  881): Message: 30
D/BluetoothAdapter( 1288): 1024541416: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 1024541416: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 1024541416: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1763): 167054852: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1763): 167054852: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2514): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2514): GKI_exit_task 1 done
,I/GKI_LINUX( 2514): GKI_shutdown(): task [BTIF] terminated
D/DockEventReceiver( 6052): finishStartingService: stopping service
I/BluetoothServiceJni( 2514): cleanupNative: return from cleanup
I/ActivityManager(  881): Killing 5692:android.process.acore/u0a7 (adj 15): empty #7
,I/art     ( 2514): System.exit called, status: 0
I/AndroidRuntime( 2514): VM exiting with result code 0, cleanup skipped.
,I/rmt_storage(  291): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8765820
,I/rmt_storage(  291): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  291): wakelock acquired: 1, error no: 42
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1200203640)
,D/AndroidRuntime( 6082): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.example.hello appid=10316 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5918:com.example.hello/u0a316 (adj 0): stop com.example.hello
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1200203640) wakelock released: 1, error no: 0
I/rmt_storage(  291): 
,I/rmt_storage(  291): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8765820
,W/PackageSettings(  881): Skipping PackageSetting{aedbbb4 com.test.thalitest/10315} due to missing metadata
,I/WindowState(  881): WIN DEATH: Window{e1c2de2 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  881): Client connection lost with reason: 4
,W/ActivityManager(  881): Force removing ActivityRecord{385a27b8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/TCMD    (  486): NL - Read 444 bytes from update socket.
D/TCMD    (  486): NL - ignore NL message, type = 17
D/TCMD    (  486): Listening for incoming client connection request
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5692/cgroup.procs: No such file or directory
,D/TCMD    (  486): NL - Read 1004 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
,I/ActivityManager(  881): Process com.android.bluetooth (pid 2514) has died
,I/ActivityManager(  881): Force stopping com.example.hello appid=10316 user=0: pkg removed
,D/TCMD    (  486): NL - Read 444 bytes from update socket.
D/TCMD    (  486): NL - ignore NL message, type = 17
D/TCMD    (  486): Listening for incoming client connection request
,W/ActivityManager(  881): Spurious death for ProcessRecord{191b9789 5918:com.example.hello/u0a316}, curProc for 5918: null
,W/GeofencerStateMachine( 1763): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
D/OtaApp  ( 2636): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2636): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2636): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2636): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2636): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2636): publish the event [tag = MOT_OTA event name = LOG]
,I/art     ( 3110): Explicit concurrent mark sweep GC freed 7340(1463KB) AllocSpace objects, 2(34KB) LOS objects, 39% free, 7MB/12MB, paused 1.314ms total 45.680ms
,I/Keyboard.Facilitator( 1412): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1412): run()
,I/Decoder ( 1412): createOrResetDecoder
,I/ConfigService( 1668): onCreate
W/ContextImpl( 6052): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 1553): Explicit concurrent mark sweep GC freed 3611(241KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 518us total 139.323ms
,I/ActivityManager(  881): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6137 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/DockEventReceiver( 6052): finishStartingService: stopping service
,D/Checkin ( 3110): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/InputMethodManagerService(  881): Got RemoteException sending setActive(false) notification to pid 5918 uid 10316
,I/ActivityManager(  881): Killing 5826:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  881): Explicit concurrent mark sweep GC freed 30717(1816KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/31MB, paused 1.639ms total 186.823ms
,I/art     (  881): WaitForGcToComplete blocked for 185.890ms for cause Explicit
,D/Checkin ( 3110): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/Keyboard.Facilitator( 1412): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): run()
,D/Checkin ( 3110): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3110): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_5826/cgroup.procs: No such file or directory
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = history
,W/ResourcesManager( 6137): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1412): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1412): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1412): run()
I/StatsUtilsManager( 1412): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1412): shouldRecordStats() = Too Soon
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/art     (  881): Explicit concurrent mark sweep GC freed 6199(339KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.821ms total 181.568ms
,D/Checkin ( 3110): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/AdapterServiceConfig( 6137): Adding HeadsetService
,D/AdapterServiceConfig( 6137): Adding A2dpService
D/AdapterServiceConfig( 6137): Adding HidService
D/AdapterServiceConfig( 6137): Adding HealthService
D/AdapterServiceConfig( 6137): Adding PanService
D/AdapterServiceConfig( 6137): Adding GattService
D/AdapterServiceConfig( 6137): Adding BluetoothMapService
,I/ActivityManager(  881): Killing 5657:com.android.defcontainer/u0a10 (adj 15): empty #7
,D/AndroidRuntime( 6082): Shutting down VM
,D/Checkin ( 3110): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  294): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  294): MdmCutbackHndler,wifi, new_state =0
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
,W/libprocessgroup(  881): failed to open /acct/uid_10010/pid_5657/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1668): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Launcher( 1553): Deferring update until onResume
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6156 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/VoicemailCleanupService( 6156): Cleaning up data for package: com.example.hello
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6176 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 6156): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 5943:com.android.vending/u0a32 (adj 15): empty #7
,I/SFPerfTracer(  279):      triggers: (rate: 12:569) (compose: 0:1) (post: 0:1) (render: 0:2) (21:942 frames) (22:1061)
D/SFPerfTracer(  279):        layers: (3:12) (FocusedStackFrame (0xb715d388): 0:16)* (StatusBar (0xb7169688): 0:147) (NavigationBar (0xb716cdb0): 0:22) (com.android.systemui.ImageWallpaper (0xb71097c0): 0:31)* (DimLayer (0xb710d518): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7176fa8): 0:55)- (Starting com.example.hello (0xb70c9b90): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb7179398): 0:53)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb70c9b90): 22:30) 
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_5943/cgroup.procs: No such file or directory
,W/asset   ( 6176): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 6176): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6176): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6176): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,E/SQLiteLog( 6156): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 6156): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 6156): Process: android.process.acore, PID: 6156
E/AndroidRuntime( 6156): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6156): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6156): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6156): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6156): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6156): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6156): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 6156): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1736)
E/AndroidRuntime( 6156): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1494)
E/AndroidRuntime( 6156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6156): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6156): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
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
,D/OpenGLRenderer(  881): Render dirty regions requested: true
D/Atlas   (  881): Validating map...
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6200 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,E/SharedPreferencesImpl( 6176): Couldn't rename file /data/data/com.motorola.MotGallery2/shared_prefs/com.motorola.MotGallery2_preferences.xml to backup file /data/data/com.motorola.MotGallery2/shared_prefs/com.motorola.MotGallery2_preferences.xml.bak
,I/ActivityManager(  881): Killing 3420:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  881): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2c74089d)
,D/ConnectivityService(  881): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_3420/cgroup.procs: No such file or directory
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
