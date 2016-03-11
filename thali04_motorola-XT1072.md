#### Test 62560673e7cbba2_thali04_motorola-XT1072 Logs


```
--------- beginning of system
W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_5193/cgroup.procs: No such file or directory
--------- beginning of main
D/EmailService.MarketingOptInSetter( 2715): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  885): failed to open /acct/uid_10010/pid_3697/cgroup.procs: No such file or directory
I/SundryService( 2715): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
E/SQLiteLog( 2715): (284) automatic index on registration(APP_ID)
D/WaitableIntentService( 2715): ServiceHandler.handleMessage: mWaitCount=1
I/PushService( 2715): started with background data enabled, making sure notification mechanism is enabled
I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5361 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
W/ResourcesManager( 5361): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5385 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 1964:com.google.android.gms/u0a16 (adj 15): empty #7
D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@8e739b6)
D/WifiService(  885): Client connection lost with reason: 4
D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_1964/cgroup.procs: No such file or directory
E/SQLiteLog( 5385): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5405 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5405): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AnalyticsLogBase( 5385): PlayLogger.onLoggerConnected
I/ActivityManager(  885): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5423 uid=10096 gids={50096, 9997} abi=armeabi-v7a
I/ActivityManager(  885): Killing 5049:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
I/ActivityManager(  885): Killing 4309:com.google.process.gapps/u0a16 (adj 15): empty #8
D/AndroidRuntime( 5383): 
D/AndroidRuntime( 5383): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5383): CheckJNI is OFF
W/libprocessgroup(  885): failed to open /acct/uid_10105/pid_5049/cgroup.procs: No such file or directory
I/CalendarProvider2( 5405): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_4309/cgroup.procs: No such file or directory
I/System.out( 5423): TimeService: Loaded Library 
D/TimeService( 5423): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457713684486
D/        ( 5423): TimeServiceNative: User Time to be set is 1457713684487
D/QC-time-services( 5423): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5423): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5423): Lib:time_genoff_operation: pargs->ts_val = 1457713684487
D/QC-time-services( 5423): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  865): Daemon: Connection accepted:time_genoff
D/QC-time-services(  865): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457713684487
D/QC-time-services(  865): Daemon:genoff_opr: Base = 2, val = 1457713684487, operation = 0
D/QC-time-services(  865): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/11/116 16:26:17
D/QC-time-services(  865): Daemon:Value read from RTC seconds = 1457713577000
D/QC-time-services(  865): Daemon:new time 1457713684487 
D/QC-time-services(  865): Daemon: delta 107487 genoff 107487 
D/QC-time-services(  865): Daemon:genoff_persistent_update: Writing genoff = 107487 to memory
D/QC-time-services(  865): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  865): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  865): Updating the TOD offset
D/QC-time-services(  865): Daemon:genoff_persistent_update: Writing genoff = 107487 to memory
D/QC-time-services(  865): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  865): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  865): Daemon:Update to modem bit set
D/QC-time-services(  865): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  865): Daemon: Base = 2, Value being sent to MODEM = 18446743757744859103
E/QC-time-services( 5423): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  865): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  865): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager(  885): Start proc com.google.android.gms for broadcast com.google.android.gms/.checkin.CheckinService$Receiver: pid=5452 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
W/ResourcesManager( 5452): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5452): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 5383): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (183 us)
I/MultiDex( 5452): VM with version 2.1.0 has multidex support
I/MultiDex( 5452): install
I/MultiDex( 5452): VM has multidex support, MultiDex support library is disabled.
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5383): Shutting down VM
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5471 uid=10572 gids={50572, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  885): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5494 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 22.152ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.218ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 22.010ms
,I/GservicesProvider( 5494): Gservices pushing to system: true; secure/global: true
,I/WebViewFactory( 5471): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5471): Time to load native libraries: 3 ms (timestamps 1987-1990)
I/LibraryLoader( 5471): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5471): Binding Chromium to main looper Looper (main, tid 1) {2b819bbe}
,I/LibraryLoader( 5471): Expected native library version number "",actual native library version number ""
,I/chromium( 5471): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5471): Initializing chromium process, singleProcess=true
,W/art     ( 5471): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5471): ApplicationContext is null in ApplicationStatus
,I/GoogleHttpClient( 5494): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5494): GMS http client unavailable, use old client
,W/chromium( 5471): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5471): Local Branch: 
I/Adreno-EGL( 5471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5471): Local Patches: NONE
I/Adreno-EGL( 5471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/JNIHelp ( 5452): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33a326ee:true
,W/ActivityThread( 5452): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5452): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37f8ef18: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5452): Installed default security provider GmsCore_OpenSSL
,W/art     ( 5471): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5471): onDetachedFromWindow called when already detached. Ignoring
,I/CalendarProvider2( 5405): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5405): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Killing 5267:com.android.chrome/u0a52 (adj 15): empty #7
,D/SystemWebViewEngine( 5471): CordovaWebView is running on device made by: motorola
,D/NativeLibraryUtils( 5452): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_5267/cgroup.procs: No such file or directory
,W/art     ( 5471): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5471): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  885): Killing 5302:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_5302/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 5471): Render dirty regions requested: true
,D/Atlas   ( 5471): Validating map...
,W/chromium( 5471): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5471): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5471): Enabling debug mode 0
,I/Keyboard.Facilitator( 1421): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1037
,I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +1s37ms
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Adreno-ES20( 5471): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5471): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5471): Cannot call determinedVisibility() - never saw a connection for the pid: 5471
,D/JsMessageQueue( 5471): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  885): Killing 5330:android.process.acore/u0a7 (adj 15): empty #7
,E/Adreno-ES20( 5471): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5471): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5568 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): send {1cc88c76, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_5330/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/jxcore_app_log( 5471): JniHelper::setJavaVM(0xb874a310), pthread_self() = -1196721960
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33de12a added. We now have 1 listener(s)
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5471): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5471): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5471): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5471): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14a13291 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5471): addListener: New listener added - the number of listeners is now 1
D/WifiService(  885): New client listening to asynchronous messages
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5471): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5471): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 5471): Constructor: Bluetooth LE discovery mode is not supported
,I/GAv4    ( 5568): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5568):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5568):   adb logcat -s GAv4
,W/GAv4    ( 5568): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5568): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5568): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  885): Killing 5361:com.motorola.context/u0a8 (adj 15): empty #7
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (21:265 vsyncs) (23:1024)
,I/SFPerfTracer(  279):      triggers: (rate: 10:535) (compose: 0:1) (post: 0:1) (render: 0:2) (34:933 frames) (35:1024)
D/SFPerfTracer(  279):        layers: (3:13) (FocusedStackFrame (0xb85171c0): 0:14)* (DimLayer (0xb84bc5e0): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb84c0980): 0:51)- (StatusBar (0xb85310d0): 0:126) (NavigationBar (0xb8532de8): 0:36) (com.android.systemui.ImageWallpaper (0xb8537598): 0:34)* (Starting com.motorola.ccc.ota (0xb853e858): 0:29)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb85404c8): 0:50)- (Starting com.test.thalitest (0xb84c0970): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb853e2d8): 35:42) 
,I/chromium( 5471): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Central_PollingManager( 1469): wake lock released
W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_5361/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5600 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/global frequency( 2715): no tags to log
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/ResourcesManager( 5600): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 4422(189KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 597us total 33.648ms
,I/art     (  885): Explicit concurrent mark sweep GC freed 16167(831KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.969ms total 141.765ms
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2715): Explicit concurrent mark sweep GC freed 15537(1087KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/19MB, paused 3.611ms total 74.973ms
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 3409(135KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 474us total 25.754ms
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/OtaApp  ( 2715): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2715): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2715): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/OtaApp  ( 2715): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2715): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,I/global frequency( 2715): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
I/OtaApp  ( 2715): [info] > Exceed max defer attempts for optional update, suppresing later btn
,E/global frequency( 2715): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,D/Checkin ( 2715): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/OtaApp  ( 2715): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2715): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2715): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2715): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2715): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2715): [debug] > cancelling the previous pending intent set for download later
,D/Checkin ( 2715): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/OtaApp  ( 2715): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=27.44 rxSuccessRate=21.63 targetRoamBSSID=any RSSI=-41
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=1457713687833 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=1457713687833 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  885): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  885): [1,457,713,687,837 ms] noteScanstart no scan source
,I/global frequency( 2715): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/SundryService( 2715): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2715): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2715): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2715): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager(  885): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5623 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  885): done {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN} [45285ms]
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/WifiStateMachine(  885): [1,457,713,687,901 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@36c18b63 sup_state=COMPLETED debouncing=false
,I/Keyboard.Facilitator( 1421): onFinishInput()
,W/IInputConnectionWrapper( 5471): showStatusIcon on inactive InputConnection
,D/GetNotificationsWS( 2715): unbindWebServices(): un-registering our AIDL callback...
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,192
,I/Gmail   ( 5623): getAccountsCursor
,D/ActivityThread( 5623): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5646 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  885): send {157e7b2, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  885): send {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN}
V/AlarmManager(  885): done {157e7b2, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [46ms]
,I/ActivityManager(  885): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5663 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 5646): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/GAV2    ( 5623): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  885): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5623): Observing account changes for notifications
,I/Exchange( 5663): EasService.onCreate
,I/Exchange( 5663): RestartPingTask
,I/Exchange( 5663): RestartPingsTask did not start any pings.
I/Exchange( 5663): PSS stopIfIdle
I/Exchange( 5663): PSS has no active accounts; stopping service.
,D/Finsky  ( 5646): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5646): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5646): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  885): Explicit concurrent mark sweep GC freed 11664(593KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.824ms total 120.093ms
,D/Finsky  ( 5646): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/Gmail   ( 5623): getAccountsCursor
,W/jxcore-log( 5471): Initializing JXcore engine
W/jxcore-log( 5471): JXcore engine is ready
,I/Exchange( 5663): onDestroy
,D/Finsky  ( 5646): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5646): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  885): Killing 5423:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Ads     ( 5646): Skipping gmscore version check
,W/Thread-625( 5592): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10572 path="socket:[6643]" dev="sockfs" ino=6643 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-625( 5592): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10572 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-625( 5592): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10572 path="socket:[9640]" dev="sockfs" ino=9640 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-625( 5592): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10572 path="socket:[23056]" dev="sockfs" ino=23056 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5471): Starting JXcore engine
,W/libprocessgroup(  885): failed to open /acct/uid_10096/pid_5423/cgroup.procs: No such file or directory
,D/Finsky  ( 5646): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5452): Reading stored module config
,D/Finsky  ( 5646): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/SQLiteLog( 5623): (283) recovered 45 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/WearableService( 1750): callingUid 10016, callindPid: 1750
,E/MDM     ( 1750): [224] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5452): Restart initialization of location
,D/AuthorizationBluetoothService( 1750): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ContextImpl( 5385): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5385): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4-SVC( 5452): Google Analytics 8.7.03 is starting up.
,V/AlarmManager(  885): done {1b4dfd4f, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [14515ms]
,E/SQLiteLog( 5405): (284) automatic index on view_events(_id)
,D/3CDM.DeviceAdminPushReceiver( 2715): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2715): Type: null
D/3CDM.DeviceAdminPushReceiver( 2715): Data: null
,D/3CDM.Service( 2715): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,D/3CDM.Service( 2715): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2715): DeviceAdmin - syncWithCCC
,I/CE-UpdateModelService( 5600): ACTION_REGISTRATION_COMPLETE
D/3CDM.Service( 2715): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2715): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
,D/3CDM.Service( 2715): blur.service.cred.locationToken = null
D/3CDM.Service( 2715): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2715): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2715): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2715): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,D/3CDM.Service( 2715): Sync to CCE settings done, instantiate Locate now.
,I/Gmail   ( 5623): notifyAccountChanged
,I/Gmail   ( 5623): getAccountsCursor
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5623): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/AlarmManager(  885): done {566f940, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [12498ms]
,I/Gmail   ( 5623): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 5452): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5452): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Gmail   ( 5623): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5623): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/BSUtils ( 2715): set .setup.DeviceAdminSetupReceiver enabled
,W/art     ( 5452): Suspending all threads took: 29.390ms
,I/art     ( 5452): Background partial concurrent mark sweep GC freed 4040(453KB) AllocSpace objects, 10(159KB) LOS objects, 40% free, 10MB/17MB, paused 47.676ms total 140.142ms
,I/art     ( 5452): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/Checkin ( 3177): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/Gmail   ( 5623): getAccountsCursor
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/PlaySystemBroadcastReceiver( 5452): Processed handlePeopleChanged at 96385
,W/GCoreFlp( 1750): No location to return for getLastLocation()
,W/FusedLocationProvider( 1750): location=null
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:39000 mC
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5752 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5752): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5770 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/BaseAppContext( 5452): Using Auth Proxy for data requests.
,E/BaseAppContext( 5452): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/BaseAppContext( 5452): Using Auth Proxy for data requests.
,W/BaseAppContext( 5452): Using Auth Proxy for data requests.
,W/BaseAppContext( 5452): Using Auth Proxy for data requests.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 5452): Using Auth Proxy for data requests.
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ContactLocale( 5770): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Babel_SMS( 5752): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5752): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5752): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 5752): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5752): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5752): MmsConfig.loadFromResources
,E/Babel_SMS( 5752): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5752): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/qtaguid ( 5646): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5646): Untagging socket 37 failed errno=-22
W/IcingInternalCorpora( 5452): getNumBytesRead when not calculated.
W/NetworkManagementSocketTagger( 5646): untagSocket(37) failed with errno -22
,D/Finsky  ( 5646): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/Settings( 5752): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5752): startup - clean
,I/Babel   ( 5752): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5807 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5807): VM with version 2.1.0 has multidex support
I/MultiDex( 5807): install
I/MultiDex( 5807): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 5494): Explicit concurrent mark sweep GC freed 7780(391KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 560us total 35.399ms
,V/JNIHelp ( 5807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5830 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
W/VideoCapabilities( 5752): Unrecognized profile 2130706433 for video/avc
,W/DataBroker( 5452): No player ID found when refreshing
,W/AudioCapabilities( 5752): Unsupported mime audio/amr-wb-plus
,W/ActivityThread( 5807): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5807): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5807): Installed default security provider GmsCore_OpenSSL
,W/VideoCapabilities( 5752): Unsupported mime video/mpeg2
,D/ChimeraCfgMgr( 5807): Reading stored module config
,D/PhoneMonitor( 5830): Register our PhoneStateListener
,I/VideoCapabilities( 5752): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5752): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5752): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5752): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5752): Unrecognized profile 2130706433 for video/avc
,I/qtaguid ( 5646): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5646): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5646): untagSocket(37) failed with errno -22
,I/art     (  885): Explicit concurrent mark sweep GC freed 11537(531KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/31MB, paused 1.689ms total 124.779ms
,I/ActivityManager(  885): Killing 5568:com.google.android.deskclock/u0a55 (adj 15): empty #7
,D/NativeLibraryUtils( 5807): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  885): failed to open /acct/uid_10055/pid_5568/cgroup.procs: No such file or directory
,I/vclib   ( 5752): onServiceConnected
,W/Babel   ( 5752): Attempted to change video mute state without an active call.
,V/SetupWizard( 5830): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 5663:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,E/SQLiteLog( 5452): (284) automatic index on invitations(external_inviter_id)
,W/libprocessgroup(  885): failed to open /acct/uid_10060/pid_5663/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5807): Connecting to CarCallService...
,I/art     ( 5807): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5807): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5863 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/CAR.SERVICE( 5807): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  885): Killing 5623:com.google.android.gm/u0a63 (adj 15): empty #7
,D/GCM     ( 1750): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_5623/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {30a5427e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/CAR.TEL.Service( 5807): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5807): Creating a new PhoneAdapter instance
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5807): setListener: com.google.android.gms.car.dn@198367e
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5807): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5807): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5807): Package validated; name: com.android.vending
,V/Finsky  ( 5646): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5889 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 502us total 21.504ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.263ms
,I/ActivityManager(  885): Killing 5405:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.980ms
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_5405/cgroup.procs: No such file or directory
,I/qtaguid ( 5646): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5646): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5646): untagSocket(37) failed with errno -22
I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5907 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5907): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5907): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,W/ActivityManager(  885): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5646): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5646): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 5646): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5931 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 5646): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  885): send {3bb872f4, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Killing 5600:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_5600/cgroup.procs: No such file or directory
,D/DeviceConnectionService( 1750): client connected with version: 8296000
,D/Finsky  ( 5646): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5646): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5950 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5863:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 5752): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5752): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/asset   ( 5950): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5950): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5950): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5950): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 5830:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_5863/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_5830/cgroup.procs: No such file or directory
,V/JNIHelp ( 5752): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd8233b new=com.google.android.velvet.VelvetApplication@3bd8233b
,I/UpdateIcingCorporaServi( 5889): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/CalendarProvider2( 5907): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5907): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/PkgBroadcastIntentOp( 5452): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 5452): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5992 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 5752): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5752): Installed default security provider GmsCore_OpenSSL
,D/WearableController( 5452): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  885): Killing 5907:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/UpdateIcingCorporaServi( 5889): UpdateCorporaTask done [took 217 ms] updated apps [took 217 ms] 
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_5907/cgroup.procs: No such file or directory
,W/ResourcesManager( 5992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 5807:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_5807/cgroup.procs: No such file or directory
,W/ActivityManager(  885): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/Icing   ( 5452): Storage manager: low false usage 1.78MB avail 3.08GB capacity 4.85GB
,E/Icing   ( 5452): Array storage bad crc 76623919 vs 1978982831
E/Icing   ( 5452): Array storage bad crc 4075556826 vs 1164828112
,E/Icing   ( 5452): Array storage bad crc 3299103562 vs 1601459076
E/Icing   ( 5452): Trie mmap suffix failed
,W/Icing   ( 5452): Docstore bad crc 0x8900f3bc vs 0x90518a09
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6033 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
E/Icing   ( 5452): Array storage bad crc 489021668 vs 0
V/AlarmManager(  885): done {6d0bf3a, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [12217ms]
,E/Icing   ( 5452): Trie mmap node failed
,W/ResourcesManager( 6033): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
I/ActivityManager(  885): Killing 5931:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_5931/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6052 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5950:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Icing   ( 5452): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_5950/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6075 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5889:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_5889/cgroup.procs: No such file or directory
,W/asset   ( 6075): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6075): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6075): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6075): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6101 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 5452): Internal init done: storage state 0
,I/ActivityManager(  885): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6118 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/Icing   ( 5452): 24 corpora need re-polling
I/ActivityManager(  885): Killing 5992:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/Icing   ( 5452): Post-init done
,I/Icing   ( 5452): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_5992/cgroup.procs: No such file or directory
,I/art     (  885): Explicit concurrent mark sweep GC freed 14642(718KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.600ms total 122.379ms
,W/ResourcesManager( 6118): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6118): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5452): Indexing 4872BCF0222204F7BD264D301612C97BCD2D2DDC from com.google.android.googlequicksearchbox
,D/PkgBroadcastIntentOp( 5452): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/AsyncTaskServiceImpl( 5452): Submit a task: k
,D/WearableController( 5452): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/k       ( 5452): Processing package: com.test.thalitest
,I/MultiDex( 6118): VM with version 2.1.0 has multidex support
I/MultiDex( 6118): install
,I/MultiDex( 6118): VM has multidex support, MultiDex support library is disabled.
,D/GassUtils( 5452): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5452): Found info for package com.test.thalitest in db.
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6147 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/SQLiteLog( 6101): (284) automatic index on phones(data_id)
,V/JNIHelp ( 6118): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=351, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311500, SEQNUM=4390, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-56, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
I/Icing   ( 5452): Indexing done 4872BCF0222204F7BD264D301612C97BCD2D2DDC
I/Icing   ( 5452): Indexing 66B77DC231A28AED1F70AB8F1470C430B255E161 from com.google.android.googlequicksearchbox
,W/ActivityThread( 6118): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6118): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6118): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 6118): Reading stored module config
,I/PeopleDatabaseHelper( 5452): cleanUpNonGplusAccounts done.
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/UpdateIcingCorporaServi( 6101): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Icing   ( 5452): Indexing done 66B77DC231A28AED1F70AB8F1470C430B255E161
I/Icing   ( 5452): Indexing FAC5D5C372F1FE03E0CF6D19726C451BC6ABAC12 from com.google.android.googlequicksearchbox
D/NativeLibraryUtils( 6118): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6118): Connecting to CarCallService...
,E/SQLiteLog( 6101): (284) automatic index on emails(data_id)
,I/art     ( 6118): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6118): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6118): com.google.android.projection.gearhead isn't installed.
,I/Icing   ( 5452): Indexing done FAC5D5C372F1FE03E0CF6D19726C451BC6ABAC12
I/Icing   ( 5452): Not indexing corpus from package com.android.chrome as it has never connected
,D/CAR.TEL.Service( 6118): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6118): Creating a new PhoneAdapter instance
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6118): setListener: com.google.android.gms.car.dn@198367e
W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6118): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6118): Starting CarCallService with initial phone null
I/ActivityManager(  885): Killing 5646:com.android.vending/u0a32 (adj 15): empty #7
,E/Icing   ( 5452): Aborting indexing of corpus omnibox
,I/Icing   ( 5452): Not indexing corpus from package com.google.android.apps.messaging as it has never connected
E/Icing   ( 5452): Aborting indexing of corpus messagesCorpus
I/Icing   ( 5452): Not indexing corpus from package com.google.android.apps.messaging as it has never connected
E/Icing   ( 5452): Aborting indexing of corpus participantsCorpus
I/Icing   ( 5452): Indexing 37CAF1DD096EBA1346D0004D1B70177E33DE9430 from com.google.android.gms
,I/Icing   ( 5452): Indexing done 37CAF1DD096EBA1346D0004D1B70177E33DE9430
,I/Icing   ( 5452): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_5646/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.SearchQuery$Provider: pid=6185 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.828ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.117ms
,D/CAR.SERVICE( 6118): mConnectedToCar = false, abort
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 19.989ms
,E/ActivityThread( 6118): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@16bcb8a6 that was originally bound here
E/ActivityThread( 6118): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@16bcb8a6 that was originally bound here
E/ActivityThread( 6118): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 6118): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
,E/ActivityThread( 6118): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 6118): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 6118): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6118): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6118): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6118): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 6118): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 6118): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 6118): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 6118): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 6118): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 6118): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 6118): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 6118): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 6118): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6118): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6118): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 6118): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6118): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6118): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 6118): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 6118): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c98d039 that was originally bound here
E/ActivityThread( 6118): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c98d039 that was originally bound here
E/ActivityThread( 6118): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 6118): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 6118): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 6118): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 6118): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6118): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 6118): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 6118): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 6118): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 6118): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 6118): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 6118): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 6118): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 6118): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 6118): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 6118): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6118): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6118): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 6118): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6118): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6118): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 6118): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ActivityManager(  885): Unbind failed: could not find connection for android.os.BinderProxy@e28e623
,I/GAv4    ( 6147): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6147):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6147):   adb logcat -s GAv4
,I/Gmail   ( 6185): getAccountsCursor
,W/GAv4    ( 6147): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 6185): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/GAv4    ( 6147): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6147): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6147): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/ActivityManager(  885): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6214 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 6147): (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,W/GAV2    ( 6185): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6147): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6248 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  885): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/SQLiteLog( 6185): (283) recovered 46 frames from WAL file /data/user/0/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 6214): EasService.onCreate
,I/Exchange( 6214): RestartPingTask
,I/ActivityManager(  885): Killing 6033:com.motorola.context/u0a8 (adj 15): empty #7
,V/JNIHelp ( 6147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Gmail   ( 6185): Observing account changes for notifications
,I/Gmail   ( 6185): notifyAccountChanged
I/Gmail   ( 6185): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6185): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6185): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6185): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/System  ( 6147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6147): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6033/cgroup.procs: No such file or directory
,I/Gmail   ( 6185): getAccountsCursor
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 6214): RestartPingsTask did not start any pings.
I/Exchange( 6214): PSS stopIfIdle
I/Exchange( 6214): PSS has no active accounts; stopping service.
,W/ResourcesManager( 6248): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Exchange( 6214): onDestroy
,I/ActivityManager(  885): Killing 5770:android.process.acore/u0a7 (adj 15): empty #7
,I/Icing   ( 5452): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,I/Icing   ( 5452): Indexing 346450671AD4EC90E40EFFA60B87477CADDF794C from com.google.android.videos
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_5770/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 6052:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/ActivityManager(  885): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=6280 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_6052/cgroup.procs: No such file or directory
,W/ResourcesManager( 6280): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6185): getAccountsCursor
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6185): getAccountsCursor
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6309 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6341 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 6309): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     ( 5494): Explicit concurrent mark sweep GC freed 2610(104KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 365us total 26.330ms
,I/art     (  885): Explicit concurrent mark sweep GC freed 12516(637KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.635ms total 131.328ms
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6361 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6075:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_6075/cgroup.procs: No such file or directory
,W/ResourcesManager( 6361): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6361): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Finsky  ( 6341): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/PlayMovies( 6280): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6280): 
,E/SQLiteLog( 6280): (284) automatic index on sqlite_sq_B897E730(video_id)
,D/Finsky  ( 6341): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6341): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6341): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Icing   ( 5452): Indexing done 346450671AD4EC90E40EFFA60B87477CADDF794C
,W/PlayMovies( 6280): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6280): 
I/ActivityManager(  885): Killing 6147:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/Icing   ( 5452): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6147/cgroup.procs: No such file or directory
,D/PlayMovies( 6280): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 6280): 
,D/PlayMovies( 6280): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 6280): 
,D/Ads     ( 6341): Skipping gmscore version check
,D/Finsky  ( 6341): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6341): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6341): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6341): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 6341): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 6341): [739] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Finsky  ( 6341): [739] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,D/WearableService( 1750): callingUid 10016, callindPid: 1750
,D/LocationInitializer( 5452): Restart initialization of location
I/ActivityManager(  885): Killing 6118:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/VideoCapabilities( 6280): Unrecognized profile 2130706433 for video/avc
E/MDM     ( 1750): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.videos/files/Movies/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6280): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,W/AudioCapabilities( 6280): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6280): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6280): Unsupported profile 4 for video/mp4v-es
,W/MediaCodecUtil( 6280): MediaCodecList API didn't list secure decoder for: video/avc. Assuming: OMX.qcom.video.decoder.avc.secure
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6118/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1750): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::QueryStatus
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6426 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7634818, idLength=0xb55ef998
W/GCoreFlp( 1750): No location to return for getLastLocation()
W/FusedLocationProvider( 1750): location=null
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: starts! keyData=0xb55ef964, keyDataLength=0xb55ef95c
,D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: starts! keyData=0xb55ef964, keyDataLength=0xb55ef95c
,D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/ResourcesManager( 6426): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 6185:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_6185/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): done {1cc88c76, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [23941ms]
,I/ActivityManager(  885): Killing 6214:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,E/SQLiteLog( 6361): (284) automatic index on view_events(_id)
,D/Icing   ( 5452): Loaded CLD2 Version V2.0 - 20141016
,W/libprocessgroup(  885): failed to open /acct/uid_10060/pid_6214/cgroup.procs: No such file or directory
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.22 rxSuccessRate=11.98 targetRoamBSSID=any RSSI=-42
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=1457713698851 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=1457713698851 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  885): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
,E/WifiStateMachine(  885): [1,457,713,698,852 ms] noteScanstart no scan source
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,I/CalendarProvider2( 6361): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6361): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6445 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  885): done {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10508ms]
,I/ActivityManager(  885): Killing 5752:com.google.android.talk/u0a70 (adj 15): empty #7
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  885): [1,457,713,698,922 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@36c18b63 sup_state=COMPLETED debouncing=false
,I/Icing   ( 5452): Indexing CAB1456BE3B211EBC307C171B72F719E92FCECCC from com.google.android.gms
,I/Icing   ( 5452): Indexing done CAB1456BE3B211EBC307C171B72F719E92FCECCC
,I/Icing   ( 5452): Indexing F89A5A554A34155FDE8136238C97721890582172 from com.google.android.music
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_5752/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6463 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6445): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/Gmail   ( 6445): getAccountsCursor
,I/ActivityManager(  885): Killing 6248:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6248/cgroup.procs: No such file or directory
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6490 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6463): Database version: 120
,W/GAV2    ( 6445): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  885): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6445): Observing account changes for notifications
,I/Exchange( 6490): EasService.onCreate
,I/Exchange( 6490): RestartPingTask
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6463): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/Exchange( 6490): RestartPingsTask did not start any pings.
,I/Exchange( 6490): PSS stopIfIdle
I/Exchange( 6490): PSS has no active accounts; stopping service.
,I/Gmail   ( 6445): getAccountsCursor
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Exchange( 6490): onDestroy
,D/3CDM.DeviceAdminSetupReceiver( 2715): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2715): time to show notification
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6463): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 1292): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,W/ContextImpl( 6463): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/MDM     ( 1750): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  885): Killing 6309:android.process.acore/u0a7 (adj 15): empty #7
,E/SQLiteLog( 6445): (283) recovered 47 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:39000 mC
,I/Gmail   ( 6445): notifyAccountChanged
,I/Gmail   ( 6445): getAccountsCursor
,I/Gmail   ( 6445): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6445): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6445): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6445): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_6309/cgroup.procs: No such file or directory
,D/LocationInitializer( 5452): Restart initialization of location
,V/AlarmManager(  885): send {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM}
,W/ResourcesManager( 6463): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6463): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6463): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  885): Explicit concurrent mark sweep GC freed 13210(617KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.793ms total 133.617ms
,D/AuthorizationBluetoothService( 1750): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivatableNotificationView( 1292):  oops Width=0 ActualHeight=128
,V/AlarmManager(  885): done {30a5427e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8408ms]
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): done {3bb872f4, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [7036ms]
,W/GCoreFlp( 1750): No location to return for getLastLocation()
W/FusedLocationProvider( 1750): location=null
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 6463): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6463): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3514a0eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6463): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6463): GMSCore installation verified
,D/Finsky  ( 6341): [765] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/Icing   ( 5452): Indexing done F89A5A554A34155FDE8136238C97721890582172
,I/Icing   ( 5452): Indexing C4E2C5CC550D05661E7AD615FD9F7900AE32897E from com.google.android.googlequicksearchbox
I/ConfigStore( 6463): Config Database version: 1
,E/MDM     ( 1750): [200] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5452): Restart initialization of location
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthorizationBluetoothService( 1750): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1750): No location to return for getLastLocation()
W/FusedLocationProvider( 1750): location=null
,E/SQLiteLog( 6101): (284) automatic index on contacts(contact_id)
,I/Icing   ( 5452): Indexing done C4E2C5CC550D05661E7AD615FD9F7900AE32897E
I/Icing   ( 5452): Indexing B38ECE6979252B6258324BDB4A6CBA7FE716FBF6 from com.google.android.music
,I/MediaRouter( 6463): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6463): type=WIFI subType= reason=null isConnected=true
,V/AlarmManager(  885): done {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM} [508ms]
,I/Icing   ( 5452): Indexing done B38ECE6979252B6258324BDB4A6CBA7FE716FBF6
I/Icing   ( 5452): Indexing D2B9966BFA31E94C2E19CD89CAAF0DABB369A465 from com.google.android.gms
,I/Gmail   ( 6445): getAccountsCursor
,I/Icing   ( 5452): Indexing done D2B9966BFA31E94C2E19CD89CAAF0DABB369A465
,I/Icing   ( 5452): Indexing 3FCCFCF7A9CBB53DD847A445F260A1713A23D74F from com.google.android.gms
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NetworkMonitor( 6463): type=WIFI subType= reason=null isConnected=true
,I/Icing   ( 5452): Indexing done 3FCCFCF7A9CBB53DD847A445F260A1713A23D74F
,I/Icing   ( 5452): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/GHttpClientFactory( 6463): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6463): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6280:com.google.android.videos/u0a98 (adj 15): empty #7
,I/Icing   ( 5452): Indexing 35EEF8AB756C109C4A9E0B05D40C0D1BC827283E from com.google.android.googlequicksearchbox
,I/art     ( 1750): Explicit concurrent mark sweep GC freed 35627(2MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 13MB/22MB, paused 949us total 89.668ms
,W/libprocessgroup(  885): failed to open /acct/uid_10098/pid_6280/cgroup.procs: No such file or directory
,E/SQLiteLog( 6101): (284) automatic index on postals(data_id)
,I/Icing   ( 5452): Indexing done 35EEF8AB756C109C4A9E0B05D40C0D1BC827283E
,I/Icing   ( 5452): Indexing EEE3E0FF4DADAE4CB4C7878F0618998FF68C443F from com.google.android.gms
,I/Icing   ( 5452): Indexing done EEE3E0FF4DADAE4CB4C7878F0618998FF68C443F
,I/Icing   ( 5452): Indexing F31C33A9C165C418DC665D5D5CCC2C59547B796D from com.google.android.apps.books
,W/ActivityManager(  885): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{1386a9f7 5452:com.google.android.gms/u0a16} (pid=5452, uid=10016) that is not exported from uid 10046
,E/Icing   ( 5452): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{1386a9f7 5452:com.google.android.gms/u0a16} (pid=5452, uid=10016) that is not exported from uid 10046
,I/Icing   ( 5452): Indexing done F31C33A9C165C418DC665D5D5CCC2C59547B796D
E/Icing   ( 5452): Aborting indexing of corpus volumes__id
,I/Icing   ( 5452): Indexing AD155643591D3539F6A352C4DB59513CA6893D4B from com.google.android.music
,I/Icing   ( 5452): Indexing done AD155643591D3539F6A352C4DB59513CA6893D4B
,I/Icing   ( 5452): Indexing 4EDDE6AB8EB8EAD44D177EBA476C0D4D5DBE54AF from com.google.android.music
,I/Icing   ( 5452): Indexing done 4EDDE6AB8EB8EAD44D177EBA476C0D4D5DBE54AF
,I/Icing   ( 5452): Indexing E4D473B56BA677AE6825C925C78E1DD1A496197B from com.google.android.videos
,I/ActivityManager(  885): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=6570 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.601ms
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (35:359 vsyncs) (37:1136)
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.407ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 22.253ms
,W/ResourcesManager( 6570): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 6490:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,E/SQLiteLog( 6570): (284) automatic index on sqlite_sq_B897C7D0(show_id)
,I/Icing   ( 5452): Indexing done E4D473B56BA677AE6825C925C78E1DD1A496197B
,I/Icing   ( 5452): Not indexing corpus from package com.google.android.apps.messaging as it has never connected
E/Icing   ( 5452): Aborting indexing of corpus partsCorpus
,W/libprocessgroup(  885): failed to open /acct/uid_10060/pid_6490/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 6341:com.android.vending/u0a32 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6341/cgroup.procs: No such file or directory
,I/Icing   ( 5452): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
I/UpdateIcingCorporaServi( 6101): UpdateCorporaTask done [took 5251 ms] updated apps [took 5251 ms] 
,I/art     ( 5494): Explicit concurrent mark sweep GC freed 2984(116KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 502us total 37.677ms
,I/Icing   ( 5452): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/ActivityManager(  885): Killing 6426:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6426/cgroup.procs: No such file or directory
,W/PlayMovies( 6570): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6570): 
,I/ActivityManager(  885): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6617 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/PlayMovies( 6570): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6570): 
,D/PlayMovies( 6570): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 6570): 
,D/PlayMovies( 6570): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 6570): 
,W/VideoCapabilities( 6570): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6570): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6570): Unsupported mime video/mpeg2
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6570): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,D/WVCdm   (  295): Instantiating CDM.
,D/Finsky  ( 6617): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/WVCdm   (  295): CdmEngine::QueryStatus
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/VideoCapabilities( 6570): Unsupported profile 4 for video/mp4v-es
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,W/MediaCodecUtil( 6570): MediaCodecList API didn't list secure decoder for: video/avc. Assuming: OMX.qcom.video.decoder.avc.secure
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7634818, idLength=0xbecce518
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: starts! keyData=0xbecce4e4, keyDataLength=0xbecce4dc
,D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: starts! keyData=0xbecce4e4, keyDataLength=0xbecce4dc
,D/DrmWidevineDash(  295): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,D/Finsky  ( 6617): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6617): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6617): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6617): [775] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
,D/Finsky  ( 6617): [775] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,I/ActivityManager(  885): Killing 6445:com.google.android.gm/u0a63 (adj 15): empty #7
,D/Ads     ( 6617): Skipping gmscore version check
,D/Finsky  ( 6617): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6617): [1] Libraries$2.run: Finished loading 1 libraries.
,W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_6445/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Finsky  ( 6617): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6617): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5452): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 5452): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/Icing   ( 5452): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/Icing   ( 5452): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{2130b44e u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/SFPerfTracer(  279):      triggers: (rate: 10:541) (compose: 0:1) (post: 0:1) (render: 0:2) (38:1031 frames) (39:1137)
D/SFPerfTracer(  279):        layers: (3:10) (FocusedStackFrame (0xb85171c0): 0:16)* (DimLayer (0xb84bc5e0): 0:9)* (StatusBar (0xb85310d0): 39:186) (NavigationBar (0xb8532de8): 0:48) (com.android.systemui.ImageWallpaper (0xb8537598): 0:34)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb853e2d8): 0:90)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb853ce70): 0:30) 
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/jxcore-log( 5471): Platform android
W/jxcore-log( 5471): 
W/jxcore-log( 5471): Process ARCH arm
W/jxcore-log( 5471): 
,I/jxcore-log( 5471): JXcore Cordova bridge is ready!
I/jxcore-log( 5471): 
,W/jxcore-log( 5471): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5471): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WearableService( 1750): callingUid 10016, callindPid: 1750
,E/GmsUtils( 6463): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 6463): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6463): Stop autocaching.
,E/GmsUtils( 6463): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:39000 mC
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/io.jxcore.node.JXcoreExtension( 5471): isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,I/jxcore-log( 5471): WARN testUtils BLE multiple advertisement issue: null
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): INFO testUtils Toggling radios to: true
I/jxcore-log( 5471): 
,D/BluetoothAdapter( 5471): enable(): BT is already enabled..!
,I/jxcore-log( 5471): Unit Test app is loaded
I/jxcore-log( 5471): 
,D/WifiService(  885): setWifiEnabled: true pid=5471, uid=10572
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 5471): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
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
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  885): InitialState.processMessage what=4
,E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
,D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,V/NativeCrypto( 1750): Read error: ssl=0xb8a19230: I/O error during system call, Connection timed out
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiMetrics(  885): connected time updated 44808
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6702 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6702): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/art     (  885): Explicit concurrent mark sweep GC freed 31410(1714KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 2.573ms total 197.724ms
,E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,V/NativeCrypto( 1750): SSL shutdown failed: ssl=0xb8a19230: I/O error during system call, Broken pipe
,E/GCM     ( 1750): Wifi connection closed with errorCode 20
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6730 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6361:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_6361/cgroup.procs: No such file or directory
,W/ResourcesManager( 6730): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 25 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 26 
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 26 
D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  885): [1,457,713,711,751 ms] noteScanEnd no scan source
I/wpa_supplicant( 1416): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1416): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@f8f68de sup_state=SCANNING debouncing=false
,I/Babel_SMS( 6730): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6730): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6730): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6730): MmsConfig.loadFromDatabase
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/Babel_SMS( 6730): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6730): MmsConfig.loadFromResources
,E/Babel_SMS( 6730): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6730): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6730): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6730): startup - clean
,I/Babel   ( 6730): deleted: false for 0
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 180 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1416): wlan0: Associated with f4:f2:6d:22:99:3e
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with f4:f2:6d
D/MDMCTBK (  293): Event received = Associated with f4:f2:6d
,D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  885): ApnList is empty for checkDunConfigured()
I/wpa_supplicant( 1416): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2422, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2422
I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2422
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202557488
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18,
E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
,E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  885): Start Dhcp Watchdog 2
,E/WifiStateMachine(  885): calculateWifiScore() report new score 60
D/ConnectivityService(  885): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  885): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3dc3f756 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3dc3f756 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6730): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6730): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6730): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6730): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6730): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6730): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6730): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6730): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6570:com.google.android.videos/u0a98 (adj 15): empty #7
,E/DHCPCD  ( 6771): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6771): version 5.5.6 starting
,E/DHCPCD  ( 6771): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6771): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6771): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  885): failed to open /acct/uid_10098/pid_6570/cgroup.procs: No such file or directory
,I/vclib   ( 6730): onServiceConnected
W/Babel   ( 6730): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6771): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6771): wlan0: rebinding lease of 192.168.1.112
D/DHCPCD  ( 6771): wlan0: sending REQUEST (xid 0xab9d89dc), next in 4.00 seconds
,I/DHCPCD  ( 6771): wlan0: acknowledged 192.168.1.112 from 192.168.1.1
,I/DHCPCD  ( 6771): wlan0: leased 192.168.1.112 for 172800 seconds
D/DHCPCD  ( 6771): wlan0: adding IP address 192.168.1.112/24
,D/DHCPCD  ( 6771): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6771): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6771): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
D/TCMD    (  480): Listening for incoming client connection request
,D/DHCPCD  ( 6771): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.112
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Mar 2016 16:28:32 GMT], X-Android-Received-Millis=[1457713712910], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457713712864]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1535): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6827 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6827): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6827): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,V/AlarmManager(  885): send {27f5c7ae, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  885): send {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  885): done {27f5c7ae, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [4ms]
,V/AlarmManager(  885): done {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN} [6ms]
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=150.00 rxSuccessRate=139.00 targetRoamBSSID=any RSSI=-42
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=1457713713185 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=1457713713185 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=150.00 rx=139.00
,D/Finsky  ( 6617): [795] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6617): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/CalendarProvider2( 6827): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6827): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Killing 6101:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_6101/cgroup.procs: No such file or directory
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6463): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1469): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/NetworkMonitor( 6463): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2715): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/MusicLeanback( 6463): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2715): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2715): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2715): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2715): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2715): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2715): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2715): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2715): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2715): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2715): [debug] > CusSM.onRadioDown
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6861 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6879 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/ActivityThread( 5452): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  885): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 183703, reason: UserStart
,V/Mms     ( 6861): mnc/mcc: 
V/Mms     ( 6861): tag: int value: recipientLimit - 20
V/Mms     ( 6861): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6861): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6861): tag: int value: maxSubjectLength - 80
V/Mms     ( 6861): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6861): tag: bool value: enableGroupMms - false
,V/Mms     ( 6861):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  885): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=6901 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6861): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6928 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6730:com.google.android.talk/u0a70 (adj 15): empty #7
,D/PhoneMonitor( 6928): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6730/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6928): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6617:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6617/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,I/GAv4    ( 6879): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6879):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6879):   adb logcat -s GAv4
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinService( 5452): Disabling old GoogleServicesFramework version
,W/GAv4    ( 6879): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinService( 5452): Checking schedule, now: 1457713715030 next: 1457713709559
,I/CheckinService( 5452): active receiver: enabled
,I/iu.SyncManager( 5452): SYNC; picasa accounts
,W/GAv4    ( 6879): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinService( 5452): Preparing to send checkin request
I/EventLogService( 5452): Accumulating logs since 1457713670081
,D/NetworkLogImpl( 5452): Loaded NetworkSpeedPredictor
W/GAv4    ( 6879): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/iu.Environment( 5452): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/AnalyticsTrackerProxyImpl( 6879): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
I/iu.UploadsManager( 5452): num queued entries: 0
,I/iu.UploadsManager( 5452): num updated entries: 0
,I/iu.SyncManager( 5452): NEXT; no task
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6961 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6879): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6879): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6879): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6879): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6879): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6879): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 5452): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
E/ActivityThread( 5452): Failed to find provider info for com.google.android.wearable.settings
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=345, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310812, SEQNUM=4416, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-71, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/GAv4    ( 6901): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6901):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6901):   adb logcat -s GAv4
,W/GAv4    ( 6901): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/System  ( 6879): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6879): Installed default security provider GmsCore_OpenSSL
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,W/GAv4    ( 6901): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6901): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6901): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,I/ActivityManager(  885): Killing 6702:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6702/cgroup.procs: No such file or directory
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2715): now: 122530 ,futureTime: 9223372036854775807
D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2715): now: 122530 ,futureTime: 9223372036854775807
D/PollingManager( 2715): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2715): now: 122531 ,futureTime: 9223372036854775807
D/OtaApp  ( 2715): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524295
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/OtaApp  ( 2715): [debug] > PollingManagerService, now: 122554 ,futureTime: 81658207
I/NetworkMonitor( 6463): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2715): [debug] > Polling alarm set to expire at: 81658207 Current Time: 122554
,D/Central_PollingManager( 1469): now: 122557 ,futureTime: 86482910
D/Central_PollingManager( 1469): Polling alarm set to expire at: 86482910 Current Time: 122557
,D/OtaApp  ( 2715): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2715): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2715): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2715): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2715): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2715): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2715): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2715): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2715): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     (  885): Explicit concurrent mark sweep GC freed 46732(2MB) AllocSpace objects, 4(162KB) LOS objects, 33% free, 21MB/32MB, paused 1.940ms total 157.704ms
,D/MMApiProvisionService( 2715): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2715): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2715): createDeviceIdOrLogin update_device
,D/Checkin ( 2715): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2715): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2715): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7012 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6827:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/CCE     ( 2715): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2715): createDeviceIdOrLogin update_device
,D/Checkin ( 2715): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2715): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2715): set mOutstandingReq to true.
I/ Nonce  ( 2715):  Nonce getNonce 
I/ Nonce  ( 2715):  Nonce Request 
I/ Nonce  ( 2715):  Nonce execute Request 
,D/MMApiWebService( 2715): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2715): isDeviceProvisioned: deviceId = 2072049230914535424
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_6827/cgroup.procs: No such file or directory
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 22149(1250KB) AllocSpace objects, 16(520KB) LOS objects, 39% free, 7MB/12MB, paused 920us total 40.238ms
,D/CCE     ( 2715): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2715): createDeviceIdOrLogin update_device
D/Checkin ( 2715): publish the event [tag = MOT_CCE event name = LOG]
W/ResourcesManager( 7012): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/MMApiProvisionService( 2715): Not proxy app, so login/provision not allowed
,I/ActivityManager(  885): Killing 6463:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/MMApiWebService( 2715): generating token using payload instead of using session token
,D/ Nonce  ( 2715):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2715): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2715): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6463/cgroup.procs: No such file or directory
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  885): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@928a5e9}
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 5471): My device name is: motorola-XT1072
I/jxcore-log( 5471): 
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 6901): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7042 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.718ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 19.342ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.275ms
,W/ResourcesManager( 7042): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7042): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 7012): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7012): MmsConfig.loadMmsSettings
I/Babel_SMS( 7012): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7012): MmsConfig.loadFromDatabase
,I/MultiDex( 7042): VM with version 2.1.0 has multidex support
I/MultiDex( 7042): install
I/MultiDex( 7042): VM has multidex support, MultiDex support library is disabled.
,E/Babel_SMS( 7012): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7012): MmsConfig.loadFromResources
,E/Babel_SMS( 7012): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7012): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Flag    ( 6901): Duration spec must be at least 2 characters long
,V/JNIHelp ( 7042): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 7012): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ActivityThread( 7042): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7042): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7042): Installed default security provider GmsCore_OpenSSL
,I/Babel_Crash( 7012): startup - clean
,I/Babel   ( 7012): deleted: false for 0
,I/art     ( 7042): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7042): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7074 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 7012): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7012): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7012): Unsupported mime video/mpeg2
,D/NativeLibraryUtils( 7042): Install completed successfully. count=14 extracted=0
,I/VideoCapabilities( 7012): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7012): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7012): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7012): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7012): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7012): onServiceConnected
,W/Babel   ( 7012): Attempted to change video mute state without an active call.
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbecce4e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb75d9618, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75e9038, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/art     ( 7042): Suspending all threads took: 5.981ms
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7634918, idLength=0xb1405730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=4067988393
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb754f8e0
D/DrmWidevineDash(  295): message_length=1591, signature=0xb75e7c68, signature_length=2973783828
,I/Babel   ( 7012): connection state changed from UNKNOWN to CONNECTED
,I/ Nonce  ( 2715):  Nonce Reponse 
D/        ( 2715): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"403622f2-be66-481f-a98f-707a95b6799c"}
D/MMApiWSBase( 2715): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2715):  Nonce Handle Reponse 
D/MMApiProvisionService( 2715): mOutstandingReq set to false
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7074): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7074): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7074):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7074):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7074): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7074): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7074): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7074): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/MMApiProvisionService( 2715):  pTime 1457707094197 sExp 172742 cTime 1457713717192 tTime 1457879836197
D/MMApiProvisionService( 2715):  No login Required 
,W/GAv4    ( 7074): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7074): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7074): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/DataUsage( 2715): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2715): publish the event [tag = MOT_CCE event name = LOG]
,I/LibraryLoader( 7074): Time to load native libraries: 1 ms (timestamps 4414-4415)
I/LibraryLoader( 7074): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7074): Binding Chromium to main looper Looper (main, tid 1) {206bb932}
,I/LibraryLoader( 7074): Expected native library version number "",actual native library version number ""
,I/chromium( 7074): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7074): Initializing chromium process, singleProcess=true
W/art     ( 7074): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7074): ApplicationContext is null in ApplicationStatus
,W/chromium( 7074): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7074): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7074): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7074): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7074): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7074): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7074): Local Branch: 
I/Adreno-EGL( 7074): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7074): Local Patches: NONE
I/Adreno-EGL( 7074): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7074): Requires BLUETOOTH permission
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/NSApplication( 7074): Starting up...
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb54ef960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb75d9558, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75e9038, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7144 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6861:com.android.mms/u0a23 (adj 15): empty #7
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7634938, idLength=0xb55ef730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2284453437
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb754f8e0
D/DrmWidevineDash(  295): message_length=1622, signature=0xb74e28d8, signature_length=3042899732
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6861/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/art     (  885): Explicit concurrent mark sweep GC freed 16080(775KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 1.530ms total 130.184ms
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7166 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7166): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7184 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6928:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6928/cgroup.procs: No such file or directory
,I/CalendarProvider2( 7166): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,W/ResourcesManager( 7184): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/WifiService(  885): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@928a5e9}
,I/ActivityManager(  885): Killing 6961:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6961/cgroup.procs: No such file or directory
,W/JsonManifestFetcher( 6901): Failed to fetch manifest, reverting to local copy.
W/JsonManifestFetcher( 6901): java.io.IOException: stream was reset: CANCEL
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.internal.spdy.aa.b(PG:145)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.internal.http.u.b(PG:104)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.internal.http.h.d(PG:917)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.internal.http.h.a(PG:95)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.internal.http.h$a.a(PG:902)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.e.a(PG:50089)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.e$a.a(PG:230)
W/JsonManifestFetcher( 6901): 	at com.squareup.okhttp.e.a(PG:3201)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.net.okhttp.a.a(PG:156)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.executors.b.a(PG:47)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.executors.a.a(PG:22)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.executors.c.a(PG:69)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.issuers.c.b(PG:96)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.issuers.c.a(PG:84)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.issuers.a.b(PG:6140)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.issuers.a.a(PG:2096)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.http.issuers.a.a(PG:1062)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.editors.shared.jsbinarysyncer.o.a(PG:96)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.editors.shared.bulksyncer.e.b(PG:496)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.editors.shared.bulksyncer.e.a(PG:421)
W/JsonManifestFetcher( 6901): 	at com.google.android.apps.docs.editors.shared.offline.f.run(PG:206)
E/DefaultHttpIssuer( 6901): Attempt to close HttpIssuer when no request is executing.
E/OfflineSyncerImpl( 6901): additionalData field absent in syncapp serverManifest, aborting
W/EditorsOfflineSyncManagerImpl( 6901): Failed to sync offline metadata.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7220 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6879:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6879/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7012:com.google.android.talk/u0a70 (adj 15): empty #7
,I/dex2oat ( 7240): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7012/cgroup.procs: No such file or directory
,I/ContactLocale( 7220): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7257 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 7240): dex2oat took 168.686ms (threads: 4)
,I/Adreno-EGL( 7042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7042): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7042): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7042): Local Branch: 
I/Adreno-EGL( 7042): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7042): Local Patches: NONE
I/Adreno-EGL( 7042): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CalendarProvider2( 7166): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7166): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Killing 7074:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/Adreno-EGL( 7042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7042): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7042): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7042): Local Branch: 
I/Adreno-EGL( 7042): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7042): Local Patches: NONE
I/Adreno-EGL( 7042): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/MusicStore( 7257): Database version: 120
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:39000 mC
,E/libprocessgroup(  885): failed to kill 1 processes for processgroup 7074
,I/Adreno-EGL( 7042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7042): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7042): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7042): Local Branch: 
I/Adreno-EGL( 7042): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7042): Local Patches: NONE
I/Adreno-EGL( 7042): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/Adreno-EGL( 7042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7042): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7042): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7042): Local Branch: 
I/Adreno-EGL( 7042): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7042): Local Patches: NONE
I/Adreno-EGL( 7042): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7257): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7257): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5452): Classify the device as Phone.
,V/JNIHelp ( 7257): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7257): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7257): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@237ac765: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7257): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7257): GMSCore installation verified
,I/ConfigStore( 7257): Config Database version: 1
,I/MediaRouter( 7257): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7257): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7257): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7257): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7302 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7257): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7257): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 7144:com.android.chrome/u0a52 (adj 15): empty #7
,I/CheckinTask( 5452): Sending checkin request (9646 bytes)
,V/Mms     ( 7302): mnc/mcc: 
V/Mms     ( 7302): tag: int value: recipientLimit - 20
V/Mms     ( 7302): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7302): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7302): tag: int value: maxSubjectLength - 80
V/Mms     ( 7302): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7302): tag: bool value: enableGroupMms - false
V/Mms     ( 7302):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7144/cgroup.procs: No such file or directory
,W/ResourcesManager( 7302): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7333 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7166:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/PhoneMonitor( 7333): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_7166/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7333): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7333): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6901:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,I/CheckinRequestBuilder( 5452): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5452): Failed to find provider info for com.google.android.wearable.settings
W/libprocessgroup(  885): failed to open /acct/uid_10105/pid_6901/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7354 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5494): Explicit concurrent mark sweep GC freed 2179(86KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 355us total 39.535ms
,I/CheckinRequestBuilder( 5452): Classify the device as Phone.
,I/CheckinTask( 5452): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5452): Checking schedule, now: 1457713721444 next: 1458314858439
I/CheckinService( 5452): active receiver: disabled
,I/CheckinService( 5452): Checking schedule, now: 1457713721471 next: 1458314858439
I/CheckinService( 5452): active receiver: disabled
,D/CheckinService( 5452): Recording last checkin time for package unspecified as 1457713721474
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7379 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7184:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7184/cgroup.procs: No such file or directory
,W/ResourcesManager( 7379): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  885): Explicit concurrent mark sweep GC freed 11804(565KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.631ms total 125.136ms
,I/Babel_SMS( 7379): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7379): MmsConfig.loadMmsSettings
I/Babel_SMS( 7379): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7379): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7379): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7379): MmsConfig.loadFromResources
E/Babel_SMS( 7379): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7379): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7379): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7379): startup - clean
,I/Babel   ( 7379): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7422 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.723ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 19.109ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.629ms
,W/VideoCapabilities( 7379): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7379): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7379): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7379): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7379): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7379): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7379): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7379): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7379): onServiceConnected
,W/Babel   ( 7379): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7422): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7422): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7422):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7422):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7422): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7422): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7422): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7422): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7422): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7422): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7379): connection state changed from UNKNOWN to CONNECTED
,I/WebViewFactory( 7422): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7422): Time to load native libraries: 1 ms (timestamps 9758-9759)
I/LibraryLoader( 7422): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7422): Binding Chromium to main looper Looper (main, tid 1) {206bb932}
I/LibraryLoader( 7422): Expected native library version number "",actual native library version number ""
,I/chromium( 7422): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7422): Initializing chromium process, singleProcess=true
,W/art     ( 7422): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7422): ApplicationContext is null in ApplicationStatus
,W/chromium( 7422): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7422): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7422): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7422): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7422): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7422): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7422): Local Branch: 
I/Adreno-EGL( 7422): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7422): Local Patches: NONE
I/Adreno-EGL( 7422): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7422): Requires BLUETOOTH permission
,I/NSApplication( 7422): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7486 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7257:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7220:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7257/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7220/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7508 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7302:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7302/cgroup.procs: No such file or directory
,W/ResourcesManager( 7508): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7532 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7545 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7354:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7532): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7333:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7354/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7333/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/EmailService.MarketingOptInSetter( 2715): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2715): bindWebServices(): registering our AIDL callback...
W/ResourcesManager( 7545): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/SundryService( 2715): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2715): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2715): onServiceConnected()
D/GetNotificationsWS( 2715): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2715): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7574 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 7545): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,I/PushService( 2715): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  885): Killing 7422:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/MusicStore( 7574): Database version: 120
,E/libprocessgroup(  885): failed to kill 1 processes for processgroup 7422
I/ActivityManager(  885): Killing 7379:com.google.android.talk/u0a70 (adj 15): empty #8
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Killing 5385:com.google.android.calendar/u0a49 (adj 15): empty #9
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7379/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10049/pid_5385/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7574): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7574): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,V/JNIHelp ( 7574): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7574): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7574): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@237ac765: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7574): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7574): GMSCore installation verified
,I/ConfigStore( 7574): Config Database version: 1
,I/GCoreNlp( 1750): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/CalendarProvider2( 7545): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7545): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/MediaRouter( 7574): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7574): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20f6e4ea
,I/Launcher( 1572): Deferring update until onResume
,I/NetworkMonitor( 7574): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Killing 7042:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_7042/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7574): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7628 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7574): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7574): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 7486:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7628): mnc/mcc: 
V/Mms     ( 7628): tag: int value: recipientLimit - 20
V/Mms     ( 7628): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7628): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7628): tag: int value: maxSubjectLength - 80
V/Mms     ( 7628): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7628): tag: bool value: enableGroupMms - false
V/Mms     ( 7628):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7486/cgroup.procs: No such file or directory
,W/ResourcesManager( 7628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7654 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  885): Explicit concurrent mark sweep GC freed 17931(905KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.999ms total 121.243ms
,I/ActivityManager(  885): Killing 7508:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7654): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7508/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7654): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7654): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 5452): Checking schedule, now: 1457713726112 next: 1457713751439
,I/CheckinService( 5452): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7678 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5452): Checking schedule, now: 1457713726154 next: 1457713751439
I/CheckinService( 5452): active receiver: disabled
,I/ActivityManager(  885): Killing 7532:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7532/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  885): Skipping unknown process pid 7613
W/ProcessCpuTracker(  885): Skipping unknown process pid 7614
W/ProcessCpuTracker(  885): Skipping unknown process pid 7620
W/ProcessCpuTracker(  885): Skipping unknown process pid 7695
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7698 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7545:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_7545/cgroup.procs: No such file or directory
,W/ResourcesManager( 7698): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7698): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7698): MmsConfig.loadMmsSettings
I/Babel_SMS( 7698): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7698): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7698): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7698): MmsConfig.loadFromResources
E/Babel_SMS( 7698): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7698): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received,
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 7698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7698): startup - clean
,I/Babel   ( 7698): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7733 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7698): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7698): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7698): Unsupported mime video/mpeg2
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7733): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/VideoCapabilities( 7698): Unsupported profile 4 for video/mp4v-es
,I/GAv4    ( 7733): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7733):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7733):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7733): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 7698): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7733): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 7698): Unrecognized profile 2130706433 for video/avc
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/VideoCapabilities( 7698): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7733): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7733): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/VideoCapabilities( 7698): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7698): onServiceConnected
W/Babel   ( 7698): Attempted to change video mute state without an active call.
,W/GAv4    ( 7733): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7733): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel   ( 7698): connection state changed from UNKNOWN to CONNECTED
,I/WebViewFactory( 7733): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7733): Time to load native libraries: 1 ms (timestamps 4580-4581)
,I/LibraryLoader( 7733): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7733): Binding Chromium to main looper Looper (main, tid 1) {206bb932}
I/LibraryLoader( 7733): Expected native library version number "",actual native library version number ""
I/chromium( 7733): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7733): Initializing chromium process, singleProcess=true
,W/art     ( 7733): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7733): ApplicationContext is null in ApplicationStatus
,W/chromium( 7733): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7733): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7733): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7733): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7733): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7733): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7733): Local Branch: 
I/Adreno-EGL( 7733): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7733): Local Patches: NONE
I/Adreno-EGL( 7733): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7733): Requires BLUETOOTH permission
,I/NSApplication( 7733): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7794 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7628:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 21.078ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.381ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.184ms
,I/ActivityManager(  885): Killing 7574:com.google.android.music:main/u0a80 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7628/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7574/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7819 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7654:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7654/cgroup.procs: No such file or directory
,W/ResourcesManager( 7819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7841 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7678:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7698:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7678/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7698/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2715): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2715): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2715): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2715): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2715): onServiceConnected()
,D/GetNotificationsWS( 2715): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2715): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2715): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
I/PushService( 2715): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2715): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2715): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7876 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2715): [debug] > DownloadActivity, FormattedText
,I/ContactLocale( 7841): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/OtaApp  ( 2715): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2715): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2715): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2715): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2715): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:39000 mC
,D/WearableService( 1750): callingUid 10016, callindPid: 1750
,E/MDM     ( 1750): [224] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1750): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5452): Restart initialization of location
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7904 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/GCoreFlp( 1750): No location to return for getLastLocation()
,W/FusedLocationProvider( 1750): location=null
,W/ResourcesManager( 7904): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=7924 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  885): send {1fca6161, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,I/ActivityManager(  885): Killing 7733:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/libprocessgroup(  885): failed to kill 1 processes for processgroup 7733
,E/SQLiteLog( 7924): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,V/AlarmManager(  885): send {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM}
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7950 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7950): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7950): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,I/AnalyticsLogBase( 7924): PlayLogger.onLoggerConnected
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7980 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/PhoneMonitor( 7980): Register our PhoneStateListener
,V/SetupWizard( 7980): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 7794:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7794/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8004 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/GCM     ( 1750): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  885): Explicit concurrent mark sweep GC freed 17136(833KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.611ms total 127.157ms
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8037 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/CalendarProvider2( 7950): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7950): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8050 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7819:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7819/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7841:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7904:com.motorola.context/u0a8 (adj 15): empty #7
,W/ResourcesManager( 8050): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7841/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_7904/cgroup.procs: No such file or directory
,I/Babel_SMS( 8050): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8050): MmsConfig.loadMmsSettings
I/Babel_SMS( 8050): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8050): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8050): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8050): MmsConfig.loadFromResources
,E/Babel_SMS( 8050): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8050): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8050): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8050): startup - clean
,I/Babel   ( 8050): deleted: false for 0
,W/art     ( 8050): Suspending all threads took: 10.597ms
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8088 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.365ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 18.839ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.170ms
,W/VideoCapabilities( 8050): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8050): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8050): Unsupported mime video/mpeg2
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8108 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7950:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/ContactLocale( 8088): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/VideoCapabilities( 8050): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8050): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8050): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8050): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8050): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_7950/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,W/asset   ( 8108): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8108): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8108): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8108): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8004): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd8233b new=com.google.android.velvet.VelvetApplication@3bd8233b
,D/PkgBroadcastIntentOp( 5452): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 5452): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8134 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WearableController( 5452): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/vclib   ( 8050): onServiceConnected
,W/Babel   ( 8050): Attempted to change video mute state without an active call.
,I/Icing   ( 5452): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8050): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8050): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8134): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8050): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 8004): UpdateCorporaTask done [took 182 ms] updated apps [took 182 ms] 
,I/ActivityManager(  885): Killing 7980:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  ( 8050): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8050): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7980/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8166 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7876:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7876/cgroup.procs: No such file or directory
,D/Finsky  ( 8166): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8166): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8166): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8166): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8166): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8166): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8166): Skipping gmscore version check
,D/Finsky  ( 8166): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8166): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=8212 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8037:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8037/cgroup.procs: No such file or directory
,W/ResourcesManager( 8212): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8233 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8108:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Icing   ( 5452): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_8108/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8233): Register our PhoneStateListener
,I/ActivityManager(  885): Killing 8004:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Icing   ( 5452): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8004/cgroup.procs: No such file or directory
,D/GCM     ( 1750): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8252 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5452): Checking schedule, now: 1457713734578 next: 1457713751439
I/CheckinService( 5452): active receiver: disabled
,V/AlarmManager(  885): done {1fca6161, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [4862ms]
,V/AlarmManager(  885): done {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM} [4739ms]
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=8278 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8088:android.process.acore/u0a7 (adj 15): empty #7
,I/CheckinService( 5452): Done disabling old GoogleServicesFramework version
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_8088/cgroup.procs: No such file or directory
,W/ResourcesManager( 8278): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.15 rxSuccessRate=8.91 targetRoamBSSID=any RSSI=-42
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=1457713735284 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=1457713735284 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  885): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  885): done {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN} [2461ms]
E/WifiStateMachine(  885): [1,457,713,735,290 ms] noteScanstart no scan source
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 32 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 32 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  885): [1,457,713,735,352 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@36c18b63 sup_state=COMPLETED debouncing=false
,I/CalendarProvider2( 8278): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,I/art     ( 5452): Explicit concurrent mark sweep GC freed 36840(2MB) AllocSpace objects, 23(368KB) LOS objects, 24% free, 13MB/18MB, paused 1.003ms total 167.548ms
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=348, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4306115, SEQNUM=4466, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-86, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
W/ContextImpl( 7924): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,D/GCM     ( 1750): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 7924): Thread[GAThread,5,main]: No campaign data found.
,I/VacuumService( 1750): Vacuum at: now=1457713735440 tag=VacuumService
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,I/art     (  885): Explicit concurrent mark sweep GC freed 17795(823KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.488ms total 119.951ms
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 5452): 0 accounts found with uca feature
I/GamesSyncAdapter( 5452): Starting sync for 3a3529a
,W/InstanceID/Rpc( 5452): Found 10016
,I/GamesSyncAdapter( 5452): Sync duration for 3a3529a: 18
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PhenotypeConfigurator( 1750): Scheduling Phenotype for one-off execution 2768 seconds from now (1457713736249)
,I/PhenotypeFlagCommitter( 1750): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1750): Using platform SSLCertificateSocketFactory
,I/CalendarProvider2( 8278): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 8278): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Killing 8134:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8134/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Killing 8166:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_8166/cgroup.procs: No such file or directory
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:39000 mC
,W/SQLiteConnectionPool( 5452): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/AlarmManager(  885): send {c9b5dea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {c9b5dea, *alarm*:android.intent.action.TIME_TICK} [24ms]
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log( 5471): 
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 5471): 
,I/io.jxcore.node.ConnectivityInfo( 5471): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5471):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5471):     - is Bluetooth LE multiple advertisement supported: false
I/io.jxcore.node.ConnectivityInfo( 5471):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5471):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 5471):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5471):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5471):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5471):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 5471): notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 5471): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 5471): 
I/jxcore-log( 5471): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 5471): 
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/BackupManagerService(  885): Timeout restoring application @pm@
,W/BackupManagerService(  885): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1750): Restore processing aborted, no more packages
,E/BackupManagerService(  885): Failure getting next package name
,E/BackupManagerService(  885): Duplicate finish
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{15481312 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
,I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ConfigService( 1750): onCreate
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:38000 mC
,I/ActivityManager(  885): Killing 8050:com.google.android.talk/u0a70 (adj 13): empty #7
,I/ActivityManager(  885): Killing 8252:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8050/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8252/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): send {d64f092, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
V/AlarmManager(  885): send {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  885): done {d64f092, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [9ms]
V/AlarmManager(  885): done {208a4a2c, *alarm*:com.android.server.WifiManager.action.START_SCAN} [9ms]
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.13 rxSuccessRate=1.45 targetRoamBSSID=any RSSI=-42
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=1457713752838 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=1457713752838 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN bump interval =30000
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  885): [1,457,713,752,840 ms] noteScanstart no scan source
,I/CheckinService( 5452): Checking schedule, now: 1457713752875 next: 1457713751439
I/CheckinService( 5452): active receiver: enabled
,I/CheckinService( 5452): Preparing to send checkin request
I/EventLogService( 5452): Accumulating logs since 1457713715254
,I/CheckinRequestBuilder( 5452): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5452): Failed to find provider info for com.google.android.wearable.settings
,I/ConfigService( 1750): onDestroy
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LaunchCheckinHandler(  885): cleanup(): cleared. Last call was 18263 ms ago
I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8401 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8401): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8401): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8401): VM with version 2.1.0 has multidex support
I/MultiDex( 8401): install
I/MultiDex( 8401): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8401): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 33 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 33 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 34 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 34 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 35 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 35 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 36 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 36 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/WifiStateMachine(  885): [1,457,713,753,304 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@36c18b63 sup_state=COMPLETED debouncing=false
,W/ActivityThread( 8401): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8401): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8401): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1750): callingUid 10016, callindPid: 1750
,E/MDM     ( 1750): [200] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1750): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5452): Restart initialization of location
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1750): No location to return for getLastLocation()
W/FusedLocationProvider( 1750): location=null
,I/art     ( 8401): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8401): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8401): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55ef960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7555950, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75e9038, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb76348f8, idLength=0xb1405730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1684907964
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb754f8e0
D/DrmWidevineDash(  295): message_length=1591, signature=0xb754f058, signature_length=2973783828
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb54ef960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb754f3d0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75e9038, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7634938, idLength=0xb1405730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  295): PrepareKeyRequest: nonce=4153422291
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb754f8e0
D/DrmWidevineDash(  295): message_length=1622, signature=0xb75e7d70, signature_length=2973783828
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8439): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8439): dex2oat took 102.731ms (threads: 4)
I/Adreno-EGL( 8401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8401): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8401): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8401): Local Branch: 
I/Adreno-EGL( 8401): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8401): Local Patches: NONE
I/Adreno-EGL( 8401): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8401): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8401): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8401): Local Branch: 
I/Adreno-EGL( 8401): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8401): Local Patches: NONE
I/Adreno-EGL( 8401): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8401): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8401): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8401): Local Branch: 
I/Adreno-EGL( 8401): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8401): Local Patches: NONE
I/Adreno-EGL( 8401): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8401): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8401): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8401): Local Branch: 
I/Adreno-EGL( 8401): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8401): Local Patches: NONE
I/Adreno-EGL( 8401): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 5452): Classify the device as Phone.
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=342, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310926, SEQNUM=4483, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-97, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,I/CheckinTask( 5452): Sending checkin request (9646 bytes)
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinRequestBuilder( 5452): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5452): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5452): Classify the device as Phone.
,I/CheckinTask( 5452): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5452): Checking schedule, now: 1457713756354 next: 1458314893345
I/CheckinService( 5452): active receiver: disabled
,D/CheckinService( 5452): Recording last checkin time for package unspecified as 1457713756366
,V/SetupWizard( 8233): Connected to Gservices successfully
,D/GCM     ( 1750): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PowerManagerService(  885): Nap time (uid 1000)...
,I/PowerManagerService(  885): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  885): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  885): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  885): Build Date: 10/28/14 Tue
I/Adreno-EGL(  885): Local Branch: 
I/Adreno-EGL(  885): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  885): Local Patches: NONE
I/Adreno-EGL(  885): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/        (  885): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  885): BstSensorExt: id=1598182242, en=0
,D/        (  885): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 226
,D/        (  885): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  885): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  885): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb8403550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  288): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7009820
I/rmt_storage(  288): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  288): wakelock acquired: 1, error no: 42
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1224697720)
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1224697720) wakelock released: 1, error no: 0
I/rmt_storage(  288): 
,I/rmt_storage(  288): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7009820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  885): Excessive delay in setPowerMode(): 324ms
,I/PowerManagerService(  885): Sleeping (uid 1000)...
,I/WindowManager(  885): AOD feature not enabled!
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WifiStateMachine(  885): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  885): do suspend false
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,D/        (  885): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  885): <BST> disable accel, orig state: 1
I/        (  885): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/Keyboard.Facilitator( 1421): onFinishInput()
,D/WifiStateMachine(  885): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  885): do suspend true
,I/ActivityManager(  885): Killing 8212:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_8212/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:38000 mC
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8496 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  885): Explicit concurrent mark sweep GC freed 44113(2MB) AllocSpace objects, 4(265KB) LOS objects, 33% free, 21MB/32MB, paused 1.723ms total 157.773ms
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/AlarmManager(  885): send {313c63fe, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@38ab3e44
,I/GCoreNlp( 1750): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8529 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8535 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8278:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 21.584ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.367ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.253ms
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_8278/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7924:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10049/pid_7924/cgroup.procs: No such file or directory
,W/ResourcesManager( 8535): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8535): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8535): MmsConfig.loadMmsSettings
I/Babel_SMS( 8535): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8535): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8535): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8535): MmsConfig.loadFromResources
,E/Babel_SMS( 8535): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8535): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8535): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8535): startup - clean
,I/Babel   ( 8535): deleted: false for 0
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8583 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8535): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8535): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8535): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8535): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8535): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8535): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8535): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8535): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 8583): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8604 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8233:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8233/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM}
,I/vclib   ( 8535): onServiceConnected
W/Babel   ( 8535): Attempted to change video mute state without an active call.
,W/asset   ( 8604): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8604): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8604): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8604): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 8535): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8535): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8535): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 8496): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd8233b new=com.google.android.velvet.VelvetApplication@3bd8233b
,D/PkgBroadcastIntentOp( 5452): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 5452): Null package name or gms related package.  Ignoreing.
,W/System  ( 8535): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8535): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8644 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 5452): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 5452): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8644): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8496): UpdateCorporaTask done [took 239 ms] updated apps [took 239 ms] 
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8675 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8401:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_8401/cgroup.procs: No such file or directory
,D/Finsky  ( 8675): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8675): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8675): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8675): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8675): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8675): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8675): Skipping gmscore version check
,D/Finsky  ( 8675): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8675): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/AlarmManager(  885): done {313c63fe, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [2770ms]
,V/AlarmManager(  885): done {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM} [1133ms]
,I/ActivityManager(  885): Killing 8529:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8529/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=8720 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 5452): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 5452): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/GAv4    ( 8720): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8720):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8720):   adb logcat -s GAv4
,W/GAv4    ( 8720): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8720): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8720): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 8720): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,E/SQLiteLog( 8720): (283) recovered 2 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5471): 
,I/ActivityManager(  885): Killing 8604:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_8604/cgroup.procs: No such file or directory
,V/GLSActivity( 1750): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 8720): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8720): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8720): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 5471): 
,I/ProviderInstaller( 8720): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 5471): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:37000 mC
,I/ActivityManager(  885): Killing 8535:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8535/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 8496:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8496/cgroup.procs: No such file or directory
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=333, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310897, SEQNUM=4507, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-110, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:36000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  885): send {366fdcd2, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {366fdcd2, *walarm*:com.google.android.intent.action.SEND_IDLE} [81ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:35000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310335, SEQNUM=4509, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-126, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,E/global frequency( 2715): no tags to log
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2715): Explicit concurrent mark sweep GC freed 30430(1706KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.297ms total 79.584ms
,V/AlarmManager(  885): send {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {2e103cf6, *walarm*:android.content.syncmanager.SYNC_ALARM} [1ms]
,I/art     (  885): Explicit concurrent mark sweep GC freed 22481(1162KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.442ms total 118.252ms
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 43498(2MB) AllocSpace objects, 20(777KB) LOS objects, 40% free, 7MB/12MB, paused 682us total 46.028ms
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2715): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2715): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2715): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2715): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2715): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2715): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2715): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2715): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  885): send {c9b5dea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {1b4af41e, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8779 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): done {c9b5dea, *alarm*:android.intent.action.TIME_TICK} [92ms]
,I/GAv4    ( 8779): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8779):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8779):   adb logcat -s GAv4
,W/GAv4    ( 8779): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8779): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8779): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {1b4af41e, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [292ms]
,I/ActivityManager(  885): Killing 8583:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_8583/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1750): disconnect managed GoogleApiClient
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  885): send {227f44ff, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  885): done {227f44ff, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [8ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
,I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ConfigService( 1750): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311369, SEQNUM=4515, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13020, POWER_SUPPLY_CHARGE_COUNTER=-158, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2610): Disconnected process message: 10, size: 0
,I/ConfigService( 1750): onDestroy
,I/jxcore-log( 5471): Reconnected to the test server
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): --= Surplus to requirements =--
I/jxcore-log( 5471): 
,I/jxcore-log( 5471): ****TEST TOOK:  ms ****
I/jxcore-log( 5471): 
I/jxcore-log( 5471): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5471): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,D/AndroidRuntime( 8818): 
D/AndroidRuntime( 8818): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8818): CheckJNI is OFF
,D/AndroidRuntime( 8818): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10572 user=-1: uninstall pkg
,I/ActivityManager(  885): Killing 5471:com.test.thalitest/u0a572 (adj 7): stop com.test.thalitest
,W/PackageSettings(  885): Skipping PackageSetting{1eb878b6 com.example.hello/10568} due to missing metadata
,I/WindowState(  885): WIN DEATH: Window{1df3295 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  885): Client connection lost with reason: 4
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{2802f09a u0 com.test.thalitest/.MainActivity t9}
,W/ActivityManager(  885): Spurious death for ProcessRecord{340d321b 5471:com.test.thalitest/u0a572}, curProc for 5471: null
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10572 user=0: pkg removed
,I/art     ( 5452): WaitForGcToComplete blocked for 8.030ms for cause Explicit
,I/art     ( 3177): Explicit concurrent mark sweep GC freed 9827(2MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 7MB/12MB, paused 772us total 47.412ms
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1750): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1421): resetDictionaries() : en_US
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8846 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Keyboard.Facilitator.DecoderInitializer( 1421): run()
I/art     ( 1572): Explicit concurrent mark sweep GC freed 6556(439KB) AllocSpace objects, 5(240KB) LOS objects, 24% free, 13MB/17MB, paused 471us total 94.523ms
,I/Decoder ( 1421): createOrResetDecoder
,I/art     ( 5452): Explicit concurrent mark sweep GC freed 17836(1048KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/18MB, paused 3.386ms total 172.201ms
,I/art     (  885): Explicit concurrent mark sweep GC freed 10313(741KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 3.124ms total 180.074ms
I/ConfigService( 1750): onCreate
,I/art     (  885): WaitForGcToComplete blocked for 70.174ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): run()
,D/VoicemailCleanupService( 8846): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = contacts
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8869 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = history
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = user
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task.xml
,D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/ContactLocale( 8846): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  885): Explicit concurrent mark sweep GC freed 4727(246KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.799ms total 183.819ms
,I/ActivityManager(  885): Killing 8644:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1421): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1421): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1421): run()
,I/StatsUtilsManager( 1421): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1421): shouldRecordStats() = Too Soon
,D/AndroidRuntime( 8818): Shutting down VM
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8644/cgroup.procs: No such file or directory
,W/asset   ( 8869): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8869): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8869): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8869): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8890 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5494:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/ContextImpl( 8890): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_5494/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8916 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8675:com.android.vending/u0a32 (adj 15): empty #7
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_8675/cgroup.procs: No such file or directory

```
