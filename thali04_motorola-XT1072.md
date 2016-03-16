#### Test 630369953a3bebd_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-16 11:17:58.353  4306  4306 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-16 11:17:58.353  4306  4306 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 11:17:58.353  4306  4306 I GAv4    :   adb logcat -s GAv4
03-16 11:17:58.374  4306  4306 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
--------- beginning of system
03-16 11:17:58.382   885  1226 V AlarmManager: send {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN}
03-16 11:17:58.402  4306  4306 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-16 11:17:58.418  4306  4341 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-16 11:17:58.424   885  1226 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService: pid=4342 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-16 11:17:58.427   885  1226 V AlarmManager: send {2d7ef8f3, *alarm*:send_events}
03-16 11:17:58.428   885   885 V AlarmManager: done {2d7ef8f3, *alarm*:send_events} [47ms]
03-16 11:17:58.451   308   308 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 544us total 27.289ms
,03-16 11:17:58.475   308   308 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 22.169ms
03-16 11:17:58.497   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.990ms
03-16 11:17:58.868  4306  4306 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-16 11:17:58.920  4371  4371 D AndroidRuntime: 
03-16 11:17:58.920  4371  4371 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 11:17:58.924  4371  4371 D AndroidRuntime: CheckJNI is OFF
03-16 11:17:58.940  4306  4306 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 73-86)
03-16 11:17:58.941  4306  4306 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 11:17:58.957  4306  4306 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34eb602c}
03-16 11:17:58.958  4306  4306 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 11:17:58.958  4306  4306 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 11:17:58.973  4306  4306 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 11:17:58.977  4306  4306 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:17:58.981  4306  4306 E SysUtils: ApplicationContext is null in ApplicationStatus
03-16 11:17:59.083   885  1505 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4410 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
03-16 11:17:59.181  4306  4306 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-16 11:17:59.201  4306  4306 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:17:59.201  4306  4306 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:17:59.208  4306  4306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:17:59.208  4306  4306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:17:59.208  4306  4306 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:17:59.208  4306  4306 I Adreno-EGL: Local Branch: 
03-16 11:17:59.208  4306  4306 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:17:59.208  4306  4306 I Adreno-EGL: Local Patches: NONE
03-16 11:17:59.208  4306  4306 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
03-16 11:17:59.253  1961  3265 I CheckinService: Done disabling old GoogleServicesFramework version
03-16 11:17:59.277  4371  4371 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 11:17:59.286   310   310 I Atfwd_Daemon: result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
03-16 11:17:59.286   310   310 I Atfwd_Daemon: ATFWD --> QMI Port : rmnet1
03-16 11:17:59.287   885  1505 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-16 11:17:59.293   428   831 E QC-QMI  : qmi_ctl_rx_msg.c Can't find txn info for txn_id = 13
03-16 11:17:59.294   310   310 I Atfwd_Daemon: qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
03-16 11:17:59.294   310   310 I Atfwd_Daemon: Trying to register 8 commands:
03-16 11:17:59.294   310   310 I Atfwd_Daemon: cmd0: +CKPD
03-16 11:17:59.297   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.297   310   310 I Atfwd_Daemon: cmd1: +CTSA
03-16 11:17:59.299   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.299   310   310 I Atfwd_Daemon: cmd2: +CFUN
03-16 11:17:59.301   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.301   310   310 I Atfwd_Daemon: cmd3: +CMAR
03-16 11:17:59.304  4306  4453 W AudioManagerAndroid: Requires BLUETOOTH permission
03-16 11:17:59.304   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.304   310   310 I Atfwd_Daemon: cmd4: +CDIS
03-16 11:17:59.304   279   640 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (241 us)
03-16 11:17:59.306   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.306   310   310 I Atfwd_Daemon: cmd5: +CRSL
03-16 11:17:59.310   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.310   310   310 I Atfwd_Daemon: cmd6: +CSS
03-16 11:17:59.313   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.313   310   310 I Atfwd_Daemon: cmd7: +CSO
03-16 11:17:59.316   310   310 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 11:17:59.316   310   310 I Atfwd_Daemon: Registered AT Commands event handler
03-16 11:17:59.319  1474  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 11:17:59.332  4371  4371 D AndroidRuntime: Shutting down VM
03-16 11:17:59.375   885  1564 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4458 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 11:17:59.404  1474  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 11:17:59.423  4306  4306 I NSApplication: Starting up...
03-16 11:17:59.490   885  1520 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4477 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:17:59.492   885  1520 I ActivityManager: Killing 4212:com.android.mms/u0a23 (adj 15): empty #7
,03-16 11:17:59.580   885  1520 I ActivityManager: Killing 4175:com.google.android.music:main/u0a80 (adj 15): empty #8
,03-16 11:17:59.635   885  1520 I ActivityManager: Killing 4242:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 11:17:59.694  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:17:59.704   885  1248 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4496 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:59.706   885   901 W libprocessgroup: failed to open /acct/uid_10023/pid_4212/cgroup.procs: No such file or directory
,03-16 11:17:59.749   885  1487 W libprocessgroup: failed to open /acct/uid_10080/pid_4175/cgroup.procs: No such file or directory
,03-16 11:17:59.762   885  1564 W libprocessgroup: failed to open /acct/uid_10035/pid_4242/cgroup.procs: No such file or directory
,03-16 11:17:59.765   279   279 I SFPerfTracer:      triggers: (rate: 15:287) (compose: 0:2) (post: 0:1) (render: 0:3) (16:1019 frames) (17:1086)
03-16 11:17:59.765   279   279 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb74c8348): 1:11)* (DimLayer (0xb74168a0): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7491198): 0:28)- (StatusBar (0xb7494300): 17:124) (NavigationBar (0xb7497730): 11:33) (com.android.systemui.ImageWallpaper (0xb749d9d0): 0:5)* (Starting com.motorola.ccc.ota (0xb747f7b0): 0:39)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb74634c8): 16:46) (Starting com.test.thalitest (0xb747f7b0): 1:4)* 
,03-16 11:17:59.817  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:17:59.817  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:17:59.820   885  1540 I ActivityManager: Killing 4268:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 11:17:59.833  4496  4496 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:17:59.899  4458  4458 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 11:17:59.905   885   901 W libprocessgroup: failed to open /acct/uid_10088/pid_4268/cgroup.procs: No such file or directory
,03-16 11:17:59.909  4496  4496 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:17:59.934  4458  4458 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 1072-1080)
,03-16 11:17:59.935  4458  4458 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:59.963  4458  4458 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {182c8e58}
03-16 11:17:59.964  4458  4458 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:59.964  4458  4458 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 11:17:59.985  4458  4458 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 11:17:59.986  4458  4458 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:17:59.987  4458  4458 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 11:18:00.000   885  1226 V AlarmManager: send {17422fed, *alarm*:android.intent.action.TIME_TICK}
,03-16 11:18:00.015  4458  4458 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 11:18:00.022  4458  4458 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:18:00.022  4458  4458 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 11:18:00.023  4458  4458 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:00.023  4458  4458 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:00.023  4458  4458 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:00.023  4458  4458 I Adreno-EGL: Local Branch: 
03-16 11:18:00.023  4458  4458 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:00.023  4458  4458 I Adreno-EGL: Local Patches: NONE
03-16 11:18:00.023  4458  4458 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:00.035   885   885 V AlarmManager: done {17422fed, *alarm*:android.intent.action.TIME_TICK} [35ms]
,03-16 11:18:00.090   885  1656 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=4528 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 11:18:00.091   885  1656 I ActivityManager: Killing 3902:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 11:18:00.119   885  1132 D BluetoothManagerService: Message: 20
03-16 11:18:00.119   885  1132 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28f7aa6e:true
,03-16 11:18:00.144   885  1594 W libprocessgroup: failed to open /acct/uid_10070/pid_3902/cgroup.procs: No such file or directory
,03-16 11:18:00.189  4528  4528 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:00.267   885  1487 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4557 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,03-16 11:18:00.322  4557  4557 I System.out: TimeService: Loaded Library 
03-16 11:18:00.323  4557  4557 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458123480322
,03-16 11:18:00.326  4557  4557 D         : TimeServiceNative: User Time to be set is 1458123480323
03-16 11:18:00.326  4557  4557 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-16 11:18:00.326  4557  4557 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-16 11:18:00.326  4557  4557 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458123480323
03-16 11:18:00.326  4557  4557 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-16 11:18:00.328   315   830 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-16 11:18:00.328   315  4579 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458123480323
03-16 11:18:00.328   315  4579 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458123480323, operation = 0
03-16 11:18:00.328   315  4579 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/16/116 10:16:11
,03-16 11:18:00.329   315  4579 D QC-time-services: Daemon:Value read from RTC seconds = 1458123371000
03-16 11:18:00.329   315  4579 D QC-time-services: Daemon:new time 1458123480323 
03-16 11:18:00.329   315  4579 D QC-time-services: Daemon: delta 109323 genoff 109323 
03-16 11:18:00.329   315  4579 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 109323 to memory
03-16 11:18:00.329   315  4579 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-16 11:18:00.329   315  4579 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 11:18:00.330  4458  4458 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:18:00.346  4458  4458 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 11:18:00.352   315  4579 D QC-time-services: Updating the TOD offset
03-16 11:18:00.352   315  4579 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 109323 to memory
03-16 11:18:00.352   315  4579 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-16 11:18:00.352   315  4579 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 11:18:00.365  4458  4458 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-16 11:18:00.371   315  4579 E QC-time-services: Daemon:Update to modem bit set
03-16 11:18:00.371   315  4579 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-16 11:18:00.371   315  4579 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743757744860939
03-16 11:18:00.371  4557  4557 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-16 11:18:00.372   885   900 I ActivityManager: Killing 4306:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-16 11:18:00.374   315   828 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-16 11:18:00.374   315   830 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-16 11:18:00.375  4458  4458 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:18:00.375  4458  4458 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:18:00.527   885  1540 W libprocessgroup: failed to open /acct/uid_10081/pid_4306/cgroup.procs: No such file or directory
,03-16 11:18:00.550  4458  4585 D OpenGLRenderer: Render dirty regions requested: true
,03-16 11:18:00.562  4458  4458 D Atlas   : Validating map...
,03-16 11:18:00.570  4458  4537 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 11:18:00.572   885  1520 I ActivityManager: Killing 4342:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 11:18:00.607   885  1518 W libprocessgroup: failed to open /acct/uid_10039/pid_4342/cgroup.procs: No such file or directory
,03-16 11:18:00.650  4458  4585 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 11:18:00.657  4458  4585 D OpenGLRenderer: Enabling debug mode 0
,03-16 11:18:00.695  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:00.727   279   735 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:199 vsyncs) (1:1114)
,03-16 11:18:00.729   885  1133 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1396
03-16 11:18:00.729   885  1133 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s396ms
03-16 11:18:00.733  1420  1420 I Keyboard.Facilitator: onFinishInput()
03-16 11:18:00.751  4458  4589 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 11:18:00.751  4458  4589 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 11:18:00.788  4458  4458 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4458
,03-16 11:18:00.810   885  1657 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=4594 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-16 11:18:00.838   885  1656 I ActivityManager: Killing 4410:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 11:18:00.927  4496  4496 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:00.928  4496  4496 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:00.937   885  1564 W libprocessgroup: failed to open /acct/uid_10019/pid_4410/cgroup.procs: No such file or directory
,03-16 11:18:00.943   885  1505 I ActivityManager: Killing 4477:com.android.chrome/u0a52 (adj 15): empty #7
,03-16 11:18:00.975  4458  4458 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 11:18:01.004   885  1520 W libprocessgroup: failed to open /acct/uid_10052/pid_4477/cgroup.procs: No such file or directory
,03-16 11:18:01.052  4594  4594 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-16 11:18:01.052  4594  4594 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 11:18:01.052  4594  4594 I GAv4    :   adb logcat -s GAv4
,03-16 11:18:01.077  4594  4594 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:01.110  4594  4594 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:01.118  4594  4614 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:01.125  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:18:01.134   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=326, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310241, SEQNUM=4330, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14222, POWER_SUPPLY_CHARGE_COUNTER=-88, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:18:01.292   885  1518 I ActivityManager: Killing 4496:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:01.389  1961  1976 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-16 11:18:01.402  4458  4585 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 11:18:01.402  4458  4585 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 11:18:01.415   885  1248 W libprocessgroup: failed to open /acct/uid_10005/pid_4496/cgroup.procs: No such file or directory
,03-16 11:18:01.417  2548  2548 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-16 11:18:01.423  2548  2548 D GetNotificationsWS: bindWebServices(): registering our AIDL callback...
,03-16 11:18:01.426  2548  4621 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
03-16 11:18:01.427  2548  4621 E SQLiteLog: (284) automatic index on registration(APP_ID)
,03-16 11:18:01.428  2548  4621 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-16 11:18:01.431  2548  2548 D GetNotificationsWS: onServiceConnected()
03-16 11:18:01.431  2548  2548 D GetNotificationsWS: onServiceConnected(): Registered for remote service callbacks...
,03-16 11:18:01.435  2548  2548 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-16 11:18:01.437  2548  4623 I PushService: started with background data enabled, making sure notification mechanism is enabled
,03-16 11:18:01.443  1474  1474 D Central_PollingManager: wake lock released
,03-16 11:18:01.479  4458  4588 D jxcore_app_log: JniHelper::setJavaVM(0xb84cd310), pthread_self() = -1199157248
,03-16 11:18:01.491  4458  4588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 11:18:01.491  4458  4588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 11:18:01.491  4458  4588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 11:18:01.491  4458  4588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 11:18:01.491  4458  4588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 11:18:01.491  4458  4588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b680864 added. We now have 1 listener(s)
03-16 11:18:01.492   885  1248 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 11:18:01.496  4458  4588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-16 11:18:01.497  4458  4588 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-16 11:18:01.498  4458  4588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-16 11:18:01.499  4458  4588 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 11:18:01.499  4458  4588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 11:18:01.502  2548  2548 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-16 11:18:01.504  2548  2548 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
03-16 11:18:01.505  2548  2548 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 11:18:01.506  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 11:18:01.507  4458  4588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@268f8693 added. We now have 1 listener(s)
03-16 11:18:01.507  4458  4588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 11:18:01.512   885  1304 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-16 11:18:01.517   885  1240 D WifiService: New client listening to asynchronous messages
,03-16 11:18:01.518  4458  4588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-16 11:18:01.521  4458  4588 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-16 11:18:01.521  4458  4588 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-16 11:18:01.537  1474  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 11:18:01.541  4458  4588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 11:18:01.544  2548  3942 E global frequency: no tags to log
,03-16 11:18:01.544  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:18:01.583   885  1564 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4627 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:18:01.584   885  1593 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 11:18:01.633  4458  4588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 11:18:01.641  4458  4588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 11:18:01.641  4458  4588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 11:18:01.641  4458  4588 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 11:18:01.647  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:18:01.649  1558  1575 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 11:18:01.695  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:01.727  1474  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 11:18:01.734  4458  4458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:18:01.739  4458  4458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 11:18:01.740  4458  4458 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 11:18:01.820   885  1656 I art     : Explicit concurrent mark sweep GC freed 17976(901KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 2.124ms total 150.752ms
,03-16 11:18:01.922  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:18:01.941  2548  2548 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:18:01.959  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-16 11:18:01.961  1558  1574 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 11:18:02.043  4627  4647 I Gmail   : getAccountsCursor
,03-16 11:18:02.044  4627  4648 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 11:18:02.080  2548  2548 I art     : Explicit concurrent mark sweep GC freed 17725(1132KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.168ms total 90.103ms
,03-16 11:18:02.105  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:02.143   885  1818 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4650 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:02.166  1474  2594 I art     : Explicit concurrent mark sweep GC freed 4792(212KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 625us total 29.352ms
,03-16 11:18:02.229  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:18:02.244  2548  2548 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:18:02.261  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:18:02.266  1558  1953 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 11:18:02.278   885  1100 I ActivityManager: Waited long enough for: ServiceRecord{66587f4 u0 com.motorola.ccc.checkin/.CheckinService}
,03-16 11:18:02.281   885  1487 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 11:18:02.295  4627  4627 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-16 11:18:02.291  4650  4650 I Exchange: EasService.onCreate
,03-16 11:18:02.300  4627  4672 I Gmail   : Observing account changes for notifications
,03-16 11:18:02.307  4650  4674 I Exchange: RestartPingTask
,03-16 11:18:02.337  4650  4650 I Exchange: RestartPingsTask did not start any pings.
03-16 11:18:02.337  4650  4650 I Exchange: PSS stopIfIdle
,03-16 11:18:02.337  4650  4650 I Exchange: PSS has no active accounts; stopping service.
,03-16 11:18:02.372  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:18:02.378  4627  4648 I Gmail   : getAccountsCursor
,03-16 11:18:02.384  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:02.389  4650  4650 I Exchange: onDestroy
,03-16 11:18:02.390   885  1539 I ActivityManager: Killing 3953:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 11:18:02.394  2548  2548 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:18:02.636   885  1594 W libprocessgroup: failed to open /acct/uid_10090/pid_3953/cgroup.procs: No such file or directory
,03-16 11:18:02.641   885  1656 I ActivityManager: Killing 4528:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:18:02.696  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:02.742  4458  4637 W jxcore-log: Initializing JXcore engine
,03-16 11:18:02.742  4458  4637 W jxcore-log: JXcore engine is ready
,03-16 11:18:02.756  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:02.757  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:02.759   885  1564 W libprocessgroup: failed to open /acct/uid_10008/pid_4528/cgroup.procs: No such file or directory
,03-16 11:18:02.765  1742  1742 D WearableService: callingUid 10016, callindPid: 1742
,03-16 11:18:02.770  2548  2548 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-16 11:18:02.772  2548  2548 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-16 11:18:02.773  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 11:18:02.775  2548  2548 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
03-16 11:18:02.776  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 11:18:02.781  2548  2548 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-16 11:18:02.782  2548  2548 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-16 11:18:02.783  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 11:18:02.783  1742  4685 E MDM     : [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 11:18:02.796  2548  2548 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-16 11:18:02.799  2548  2548 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-16 11:18:02.800  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 11:18:02.802  2548  2548 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 11:18:02.802  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 11:18:02.803  1961  4686 D LocationInitializer: Restart initialization of location
,03-16 11:18:02.805  2548  2548 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 11:18:02.806  2548  2548 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-16 11:18:02.807  1742  1742 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 11:18:02.807  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 11:18:02.814   885  1593 I art     : Explicit concurrent mark sweep GC freed 8868(429KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 2.004ms total 164.584ms
,03-16 11:18:02.827  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:02.829  2548  3942 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:18:02.835  2548  3942 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-16 11:18:02.837  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:02.840  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 11:18:02.841  2548  3942 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-16 11:18:02.847  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:18:02.849  2548  3942 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-16 11:18:02.879  2548  3942 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-16 11:18:02.881  1420  1420 I Keyboard.Facilitator: onFinishInput()
,03-16 11:18:02.885   885  1657 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1722fa51 (uid=10109 pid=4458)
,03-16 11:18:02.887  4458  4458 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 11:18:02.893  1742  2011 W GCoreFlp: No location to return for getLastLocation()
03-16 11:18:02.893  1742  4687 W FusedLocationProvider: location=null
,03-16 11:18:02.898  2548  3942 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
03-16 11:18:02.899  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:18:02.904  4637  4637 W Thread-475: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5612]" dev="sockfs" ino=5612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 11:18:02.904  4637  4637 W Thread-475: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 11:18:02.904  4637  4637 W Thread-475: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6586]" dev="sockfs" ino=6586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 11:18:02.904  4637  4637 W Thread-475: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[19155]" dev="sockfs" ino=19155 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-16 11:18:02.925   885  1133 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,1413
,03-16 11:18:02.939  4458  4637 W jxcore-log: Starting JXcore engine
,03-16 11:18:02.943  4627  4690 E SQLiteLog: (283) recovered 60 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 11:18:02.994   885  1564 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=4695 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 11:18:03.065  4627  4691 I Gmail   : notifyAccountChanged
,03-16 11:18:03.074  4627  4647 I Gmail   : getAccountsCursor
,03-16 11:18:03.082  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:03.088  4627  4691 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:03.091  4695  4695 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:03.098  4627  4691 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:03.104  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:03.107  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:03.114  4627  4691 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:03.132  4627  4691 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:03.173  4458  4637 W jxcore-log: Platform android
03-16 11:18:03.173  4458  4637 W jxcore-log: 
03-16 11:18:03.173  4458  4637 W jxcore-log: Process ARCH arm
03-16 11:18:03.173  4458  4637 W jxcore-log: 
,03-16 11:18:03.192  4695  4713 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
,03-16 11:18:03.200   885  1657 I ActivityManager: Killing 4557:com.qualcomm.timeservice/u0a96 (adj 13): empty #7
,03-16 11:18:03.264   279   279 I SFPerfTracer:      triggers: (rate: 15:289) (compose: 0:2) (post: 0:1) (render: 0:3) (15:1111 frames) (16:1198)
03-16 11:18:03.264   279   279 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb74c8348): 0:15)* (DimLayer (0xb74168a0): 0:7) (StatusBar (0xb7494300): 16:144) (NavigationBar (0xb7497730): 9:44) (com.android.systemui.ImageWallpaper (0xb749d9d0): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb74634c8): 0:55)- (Starting com.test.thalitest (0xb747f7b0): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7491b78): 16:76) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb747f7b0): 1:7)* 
,03-16 11:18:03.295   885  1594 W libprocessgroup: failed to open /acct/uid_10096/pid_4557/cgroup.procs: No such file or directory
,03-16 11:18:03.315  2548  2548 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 11:18:03.315  2548  2548 D 3CDM.DeviceAdminPushReceiver: Type: null
03-16 11:18:03.315  2548  2548 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-16 11:18:03.318  2548  2609 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 11:18:03.319  2548  2609 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
03-16 11:18:03.319  2548  2609 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-16 11:18:03.319  2548  2609 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-16 11:18:03.319  2548  2609 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-16 11:18:03.319  2548  2609 D 3CDM.Service: blur.service.cred.locationToken = null
03-16 11:18:03.319  2548  2609 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-16 11:18:03.319  2548  2609 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-16 11:18:03.319  2548  2609 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-16 11:18:03.319  2548  2609 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-16 11:18:03.323  2548  2609 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-16 11:18:03.371   885  1487 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4714 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 11:18:03.392   308   308 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.384ms
,03-16 11:18:03.413   308   308 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 19.567ms
,03-16 11:18:03.433   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.612ms
,03-16 11:18:03.446  2548  2609 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-16 11:18:03.449  4627  4678 I Gmail   : getAccountsCursor
,03-16 11:18:03.453  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:03.505  2985  3005 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-16 11:18:03.583  4458  4637 I jxcore-log: JXcore Cordova bridge is ready!
03-16 11:18:03.583  4458  4637 I jxcore-log: 
03-16 11:18:03.584  4458  4637 W jxcore-log: JXcore engine is started
,03-16 11:18:03.585   885  1100 I ActivityManager: Waited long enough for: ServiceRecord{28f17736 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-16 11:18:03.589  4458  4588 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 11:18:03.698  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:03.859   885  1818 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4739 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:03.906   885  1248 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=4747 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 11:18:03.908   885  1248 I ActivityManager: Killing 4000:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-16 11:18:03.995   885  1593 W libprocessgroup: failed to open /acct/uid_10016/pid_4000/cgroup.procs: No such file or directory
,03-16 11:18:03.998   885  1656 I ActivityManager: Killing 4594:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-16 11:18:04.230   885  1505 W libprocessgroup: failed to open /acct/uid_10055/pid_4594/cgroup.procs: No such file or directory
,03-16 11:18:04.252  4747  4747 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:04.299  3136  3273 I art     : Explicit concurrent mark sweep GC freed 2889(115KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 384us total 30.301ms
,03-16 11:18:04.524  4747  4787 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 11:18:04.525  4747  4787 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 11:18:04.526  4747  4787 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 11:18:04.526  4747  4787 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 11:18:04.557  4747  4787 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 11:18:04.557  4747  4787 I Babel_SMS: MmsConfig.loadFromResources
,03-16 11:18:04.561  4747  4787 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 11:18:04.562  4747  4787 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:04.659  4747  4747 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:18:04.670  4747  4747 I Babel_Crash: startup - clean
,03-16 11:18:04.683  4747  4795 I Babel   : deleted: false for 0
,03-16 11:18:04.785  4747  4747 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:04.792   885   901 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4798 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:04.794   885  1259 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-16 11:18:04.794   885  1259 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-16 11:18:04.868  4747  4747 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 11:18:04.874  4747  4747 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 11:18:04.920  4747  4747 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 11:18:04.928  4747  4747 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:04.930  4747  4747 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:04.932  4747  4747 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:04.947  4747  4747 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:05.024   885   901 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4819 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:05.026  4747  4770 W art     : Suspending all threads took: 44.603ms
,03-16 11:18:05.031  4798  4816 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:18:05.074  4747  4747 I vclib   : onServiceConnected
,03-16 11:18:05.104  4747  4747 W Babel   : Attempted to change video mute state without an active call.
,03-16 11:18:05.113   885  1520 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4837 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:05.115   885  1520 I ActivityManager: Killing 4650:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 11:18:05.168  4747  4747 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:05.169  4747  4747 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:05.246   885  1656 W libprocessgroup: failed to open /acct/uid_10060/pid_4650/cgroup.procs: No such file or directory
,03-16 11:18:05.260  4819  4819 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:05.290  4837  4837 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 11:18:05.290  4837  4837 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-16 11:18:05.290  4837  4837 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:05.292  4837  4837 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 11:18:05.301  4819  4819 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:05.306  4747  4747 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:05.360   303   388 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-16 11:18:05.379  4747  4747 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:18:05.380  4747  4747 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:05.462  4714  4860 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-16 11:18:05.470  1576  1576 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@25a941ed new=com.google.android.velvet.VelvetApplication@25a941ed
,03-16 11:18:05.507  1961  4864 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 11:18:05.511  1961  4864 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 11:18:05.522   885  1818 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4865 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:05.574  1961  4864 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 11:18:05.589  1961  2035 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 11:18:05.607  4865  4865 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:05.657  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:05.657  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:05.711   279   735 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (13:292 vsyncs) (15:1221)
,03-16 11:18:05.721  4714  4860 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 257 ms] updated apps [took 257 ms] 
,03-16 11:18:05.836   885  1505 I ActivityManager: Killing 4627:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 11:18:05.975   885  1304 W libprocessgroup: failed to open /acct/uid_10063/pid_4627/cgroup.procs: No such file or directory
,03-16 11:18:06.258   885  1540 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4897 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:06.313  4819  4819 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:06.313  4819  4819 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:06.320   885  1594 I ActivityManager: Killing 4695:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:18:06.434   885  1304 W libprocessgroup: failed to open /acct/uid_10008/pid_4695/cgroup.procs: No such file or directory
,03-16 11:18:06.438   885  1505 I ActivityManager: Killing 4739:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 11:18:06.636   885  1593 W libprocessgroup: failed to open /acct/uid_10019/pid_4739/cgroup.procs: No such file or directory
,03-16 11:18:06.742  4897  4897 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 11:18:06.877  4897  4897 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 11:18:06.895  4897  4897 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:06.896  4897  4897 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:07.049  1961  2035 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 11:18:07.057   885  1593 I art     : Explicit concurrent mark sweep GC freed 12652(644KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.626ms total 120.228ms
,03-16 11:18:07.075  4897  4944 D Ads     : Skipping gmscore version check
,03-16 11:18:07.077  4897  4897 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 11:18:07.077  4897  4897 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 11:18:07.097   885  1540 I ActivityManager: Killing 4819:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:07.129  1961  2035 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-16 11:18:07.166  1961  2035 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 11:18:07.255   885  1520 W libprocessgroup: failed to open /acct/uid_10005/pid_4819/cgroup.procs: No such file or directory
,03-16 11:18:07.265  4897  4897 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 11:18:07.302   885  1818 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4946 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:07.351  4897  4897 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 11:18:07.367  4946  4946 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:07.396  4946  4946 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:07.407   885   885 V AlarmManager: done {18d50a19, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [10834ms]
,03-16 11:18:07.419  4946  4967 E SQLiteLog: (284) automatic index on view_events(_id)
,03-16 11:18:07.452   885  1520 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4969 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:07.570  1961  4864 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
03-16 11:18:07.571  4714  4989 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-16 11:18:07.578   885  1228 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 11:18:07.605  1961  4864 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 11:18:07.665  1961  1961 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-16 11:18:07.748  1742  1768 I art     : Explicit concurrent mark sweep GC freed 41164(2MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 13MB/22MB, paused 1.159ms total 133.783ms
,03-16 11:18:07.767   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-16 11:18:07.767   885   885 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 11:18:07.776   885   885 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 11:18:07.783   885   885 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 11:18:07.784   885   885 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@7dabed2
,03-16 11:18:07.820  1742  1742 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-16 11:18:07.820   885   901 I ActivityManager: Killing 4865:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 11:18:07.824  1576  1576 I Launcher: Deferring update until onResume
,03-16 11:18:07.966   885  1520 W libprocessgroup: failed to open /acct/uid_10090/pid_4865/cgroup.procs: No such file or directory
,03-16 11:18:08.011  1961  1961 D AsyncTaskServiceImpl: Submit a task: k
,03-16 11:18:08.039  1961  5003 D k       : Processing package: com.test.thalitest
,03-16 11:18:08.055  1961  5003 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-16 11:18:08.055  1961  5003 D k       : Found info for package com.test.thalitest in db.
,03-16 11:18:08.080  1961  5002 W BaseAppContext: Using Auth Proxy for data requests.
03-16 11:18:08.080  1961  5002 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 11:18:08.083  1961  5002 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 11:18:08.095  1961  5002 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 11:18:08.112  1961  5002 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 11:18:08.166  4714  4989 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 595 ms] updated apps [took 595 ms] 
,03-16 11:18:08.169   885   900 I ActivityManager: Killing 3047:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-16 11:18:08.374   885  1520 W libprocessgroup: failed to open /acct/uid_10049/pid_3047/cgroup.procs: No such file or directory
,03-16 11:18:08.420   885   900 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5015 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-16 11:18:08.467  4946  4946 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:08.467  4946  4946 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:08.477   885  1520 I ActivityManager: Killing 4897:com.android.vending/u0a32 (adj 15): empty #7
,03-16 11:18:08.480  1961  4999 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-16 11:18:08.664   885   900 W libprocessgroup: failed to open /acct/uid_10032/pid_4897/cgroup.procs: No such file or directory
,03-16 11:18:08.670  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:08.671  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:09.175  1961  2035 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-16 11:18:09.425  1961  2035 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,03-16 11:18:09.461  5015  5015 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-16 11:18:09.461  5015  5015 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 11:18:09.461  5015  5015 I GAv4    :   adb logcat -s GAv4
,03-16 11:18:09.477  5015  5015 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:09.495  1961  2035 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 11:18:09.504  5015  5015 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:09.508  5015  5050 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:09.531  5015  5015 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-16 11:18:09.545  1961  2035 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 11:18:09.707   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-16 11:18:09.707   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:09.707  5015  5056 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-16 11:18:09.738  5015  5057 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:09.739  5015  5057 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:09.754   885  1248 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5058 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-16 11:18:09.755   885  1248 I ActivityManager: Killing 4798:android.process.acore/u0a7 (adj 15): empty #7
,03-16 11:18:09.776   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.589ms
,03-16 11:18:09.798   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.104ms
,03-16 11:18:09.818   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.960ms
,03-16 11:18:09.917   885  1818 W libprocessgroup: failed to open /acct/uid_10007/pid_4798/cgroup.procs: No such file or directory
,03-16 11:18:09.948  5058  5058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:10.000  5015  5057 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:10.060  5015  5057 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:18:10.060  5015  5057 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:10.081  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:10.206   885  1594 I ActivityManager: Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5083 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:10.367   885  1248 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5104 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:10.426   885  1539 I ActivityManager: Killing 4747:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 11:18:10.483  5083  5103 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:18:10.578   885  1520 W libprocessgroup: failed to open /acct/uid_10070/pid_4747/cgroup.procs: No such file or directory
,03-16 11:18:10.580   885  1304 I ActivityManager: Killing 4969:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 11:18:10.781   885  1304 I ActivityManager: Killing 4946:com.android.providers.calendar/u0a5 (adj 15): empty #8
,03-16 11:18:11.034   885  1505 W libprocessgroup: failed to open /acct/uid_10019/pid_4969/cgroup.procs: No such file or directory
,03-16 11:18:11.036   885  1657 W libprocessgroup: failed to open /acct/uid_10005/pid_4946/cgroup.procs: No such file or directory
,03-16 11:18:11.104  5104  5104 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 11:18:11.227  5104  5104 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 11:18:11.241  5104  5104 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:11.254  5104  5104 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:11.317  5104  5153 D Ads     : Skipping gmscore version check
,03-16 11:18:11.359   885  1505 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5155 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:11.416  5104  5104 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 11:18:11.417  5104  5104 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 11:18:11.432  5104  5104 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 11:18:11.442  5104  5104 D Finsky  : [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,03-16 11:18:11.462  5104  5104 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 11:18:11.462  5155  5155 D PhoneMonitor: Register our PhoneStateListener
,03-16 11:18:11.464   885  1518 I ActivityManager: Killing 4837:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-16 11:18:11.584   885  1304 W libprocessgroup: failed to open /acct/uid_10027/pid_4837/cgroup.procs: No such file or directory
,03-16 11:18:11.625  5155  5155 V SetupWizard: Connected to Gservices successfully
,03-16 11:18:11.628   885  1593 I ActivityManager: Killing 4714:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 11:18:11.739   885  1518 W libprocessgroup: failed to open /acct/uid_10039/pid_4714/cgroup.procs: No such file or directory
,03-16 11:18:11.745  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:11.745  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:11.793   885  1564 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5179 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:11.820  1742  2336 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 11:18:12.401   885  1564 I art     : Explicit concurrent mark sweep GC freed 20210(996KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.617ms total 117.290ms
,03-16 11:18:12.537   885   901 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5213 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 11:18:12.602   885   900 I ActivityManager: Killing 5015:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-16 11:18:12.610  5213  5213 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:12.774   885  1248 W libprocessgroup: failed to open /acct/uid_10057/pid_5015/cgroup.procs: No such file or directory
,03-16 11:18:12.776   885  1226 V AlarmManager: send {501113a, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-16 11:18:12.894  5213  5242 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 11:18:12.894  5213  5242 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 11:18:12.894  5213  5242 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 11:18:12.894  5213  5242 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 11:18:12.917  5213  5242 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,03-16 11:18:12.917  5213  5242 I Babel_SMS: MmsConfig.loadFromResources
,03-16 11:18:12.918  5213  5242 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 11:18:12.919  5213  5242 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:13.030  5213  5213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:18:13.036  5213  5213 I Babel_Crash: startup - clean
,03-16 11:18:13.062  5213  5249 I Babel   : deleted: false for 0
,03-16 11:18:13.074  5213  5228 W art     : Suspending all threads took: 6.346ms
,03-16 11:18:13.125   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.43 rxSuccessRate=2.09 targetRoamBSSID=any RSSI=-48
03-16 11:18:13.125   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458123493125 interval=20000 maxinterval=300000
03-16 11:18:13.125   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458123493125 interval=20000 maxinterval=300000
03-16 11:18:13.125   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-16 11:18:13.125   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =30000
,03-16 11:18:13.126  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-16 11:18:13.127   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 11:18:13.127   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 11:18:13.128   885  1237 E WifiStateMachine: [1,458,123,493,128 ms] noteScanstart no scan source
,03-16 11:18:13.171   885   885 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=5252 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:18:13.172   885   885 V AlarmManager: done {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [14790ms]
,03-16 11:18:13.315  5213  5213 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:13.324  5213  5213 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 11:18:13.327  5213  5213 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 11:18:13.353  5213  5213 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-16 11:18:13.359  5213  5213 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 11:18:13.361  5213  5213 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:13.364  5213  5213 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:13.373  5213  5213 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:13.378   885  1304 I ActivityManager: Killing 5058:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 11:18:13.389  5252  5252 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-16 11:18:13.525   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
03-16 11:18:13.525   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 16 
03-16 11:18:13.525   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
03-16 11:18:13.525   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 17 
03-16 11:18:13.525   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 11:18:13.525   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-16 11:18:13.526   481   509 D TCMD    : NL - Read 56 bytes from update socket.
03-16 11:18:13.526   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:13.526   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:13.527   885  1237 E WifiStateMachine: [1,458,123,493,527 ms] noteScanEnd no scan source
03-16 11:18:13.530   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@c2ec98c sup_state=COMPLETED debouncing=false
,03-16 11:18:13.554   885   900 W libprocessgroup: failed to open /acct/uid_10090/pid_5058/cgroup.procs: No such file or directory
03-16 11:18:13.557  5213  5213 I vclib   : onServiceConnected
03-16 11:18:13.557  5213  5213 W Babel   : Attempted to change video mute state without an active call.
,03-16 11:18:13.620   885  1564 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5275 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:13.700  5275  5275 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:13.718  5252  5252 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-16 11:18:13.759   885  1487 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5297 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
03-16 11:18:13.760   885  1487 I ActivityManager: Killing 5104:com.android.vending/u0a32 (adj 15): empty #7
,03-16 11:18:13.854   885  1487 I ActivityManager: Killing 5083:android.process.acore/u0a7 (adj 15): empty #8
,03-16 11:18:14.024   885   900 W libprocessgroup: failed to open /acct/uid_10032/pid_5104/cgroup.procs: No such file or directory
,03-16 11:18:14.026  5275  5275 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:14.030   885  1594 W libprocessgroup: failed to open /acct/uid_10007/pid_5083/cgroup.procs: No such file or directory
,03-16 11:18:14.064  5297  5297 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:14.174   885  1304 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5329 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:14.331  5329  5348 I Gmail   : getAccountsCursor
03-16 11:18:14.333  5329  5349 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-16 11:18:14.347  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:14.361  4458  4637 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-16 11:18:14.372  4458  4637 I jxcore-log: WARN testUtils BLE multiple advertisement issue: null
03-16 11:18:14.372  4458  4637 I jxcore-log: 
,03-16 11:18:14.405   885  1518 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5352 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:14.500  5329  5329 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 11:18:14.513   885  1540 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-16 11:18:14.516  5352  5352 I Exchange: EasService.onCreate
,03-16 11:18:14.519  5329  5373 I Gmail   : Observing account changes for notifications
,03-16 11:18:14.531  5352  5375 I Exchange: RestartPingTask
,03-16 11:18:14.558  5352  5352 I Exchange: RestartPingsTask did not start any pings.
03-16 11:18:14.558  5352  5352 I Exchange: PSS stopIfIdle
03-16 11:18:14.558  5352  5352 I Exchange: PSS has no active accounts; stopping service.
,03-16 11:18:14.568  4458  4637 I jxcore-log: INFO testUtils Toggling radios to: true
03-16 11:18:14.568  4458  4637 I jxcore-log: 
,03-16 11:18:14.571  5329  5348 I Gmail   : getAccountsCursor
,03-16 11:18:14.572  4458  4637 D BluetoothAdapter: enable(): BT is already enabled..!
,03-16 11:18:14.577  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:14.577  5352  5352 I Exchange: onDestroy
,03-16 11:18:14.578  4458  4637 I jxcore-log: Unit Test app is loaded
03-16 11:18:14.578  4458  4637 I jxcore-log: 
,03-16 11:18:14.591   885  1487 D WifiService: setWifiEnabled: true pid=4458, uid=10109
,03-16 11:18:14.591   885  1487 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
03-16 11:18:14.592  2548  2548 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,03-16 11:18:14.595  2548  2548 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-16 11:18:14.599   885  1656 I ActivityManager: Killing 5155:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 11:18:14.600  4458  4458 I chromium: [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,03-16 11:18:14.629   481   509 D TCMD    : NL - Read 1004 bytes from update socket.
03-16 11:18:14.629   481   509 D TCMD    : NL - message type is RTM_NEWLINK
,03-16 11:18:14.629   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.629  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
03-16 11:18:14.629   481   509 D TCMD    : NL - Read 68 bytes from update socket.
03-16 11:18:14.629   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.630   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.630   481   509 D TCMD    : NL - Read 68 bytes from update socket.
03-16 11:18:14.630   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.630   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.630   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
03-16 11:18:14.630   292  1669 D MDMCTBK : Event received = CTRL-EVENT-DISCONNECTED 
03-16 11:18:14.630   292  1669 D MDMCTBK :  STA Disconnected !!
03-16 11:18:14.630   292  1669 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:18:14.630   292  1669 I MDMCTBK : checkDefaultInst, pid match
03-16 11:18:14.630   292  1669 I MDMCTBK : get_property_value, Enter
03-16 11:18:14.630   292  1669 I MDMCTBK : get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
03-16 11:18:14.630   292  1669 I MDMCTBK : get_property_value, Exit
03-16 11:18:14.630   292  1669 I MDMCTBK : MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
03-16 11:18:14.630   292  1669 I MDMCTBK : MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
03-16 11:18:14.630   292  1669 I MDMCTBK : set_property_value, Enter
03-16 11:18:14.630   292  1669 I MDMCTBK : set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,03-16 11:18:14.631   292  1669 I MDMCTBK : set_property_value, Values updated in the property file Successfully
03-16 11:18:14.631   292  1669 I MDMCTBK : set_property_value, Exit
03-16 11:18:14.631   292  1669 I MDMCTBK : MdmCutbackHndler, setWifiCutback, No Wifi
03-16 11:18:14.631   292  1669 I MDMCTBK : MdmCutbackHndler,Wifi disconnected !!!
03-16 11:18:14.631   292  1669 I MDMCTBK : MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
03-16 11:18:14.631   292  1669 I MDMCTBK : set_property_value, Enter
03-16 11:18:14.631   292  1669 I MDMCTBK : set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
03-16 11:18:14.632   292  1669 I MDMCTBK : set_property_value, Values updated in the property file Successfully
03-16 11:18:14.632   292  1669 I MDMCTBK : set_property_value, Exit
03-16 11:18:14.632   292  1669 E MDMCTBK : MdmCutbackHndler,Airplane Mode Enabled !! =1
03-16 11:18:14.632  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
03-16 11:18:14.632   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.632   292  1669 D MDMCTBK : Event received = CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.632   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
03-16 11:18:14.632   292  1669 D MDMCTBK : Event received = CTRL-EVENT-REGDOM-CHANGE
03-16 11:18:14.633   885  1237 E WifiStateMachine: WifiStateMachine: Leaving Connected state
03-16 11:18:14.633   885  1132 D Tethering: InitialState.processMessage what=4
03-16 11:18:14.637  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
03-16 11:18:14.637   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
03-16 11:18:14.637   292  1669 D MDMCTBK : Event received = CTRL-EVENT-REGDOM-CHANGE
03-16 11:18:14.640   885  1132 W Settings: Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 11:18:14.641   885  1132 E Tethering: ApnList is empty for checkDunConfigured()
03-16 11:18:14.641   885  1132 D Tethering:  upstream interface types: 
03-16 11:18:14.641   885  1132 D Tethering:  1
03-16 11:18:14.641   885  1132 D Tethering:  5
03-16 11:18:14.641   885  1132 D Tethering:  7
03-16 11:18:14.642   885  1132 D Tethering:  0
03-16 11:18:14.642   885  1237 E WifiStateMachine: handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
03-16 11:18:14.642   885  1237 E WifiStateMachine: handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
03-16 11:18:14.642   885  1237 E WifiStateMachine: handleNetworkDisconnect "NG700" nid=0
03-16 11:18:14.642   885  1237 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-16 11:18:14.645   885  1518 W libprocessgroup: failed to open /acct/uid_10035/pid_5155/cgroup.procs: No such file or directory
03-16 11:18:14.647   885  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
03-16 11:18:14.648   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
03-16 11:18:14.650   885   900 I ActivityManager: Killing 1961:com.google.android.gms/u0a16 (adj 15): empty #7
03-16 11:18:14.650   885  1236 D WifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.650   885  1236 D WifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.654  1431  1431 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
03-16 11:18:14.654   289   818 D CommandListener: Clearing all IP addresses on wlan0
03-16 11:18:14.655   481   509 D TCMD    : NL - Read 60 bytes from update socket.
,03-16 11:18:14.655   481   509 D TCMD    : NL - ignore NL message, type = 21
03-16 11:18:14.655   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.664  1742  4303 V NativeCrypto: Read error: ssl=0xb8743908: I/O error during system call, Connection timed out
03-16 11:18:14.667  1742  4303 V NativeCrypto: SSL shutdown failed: ssl=0xb8743908: I/O error during system call, Broken pipe
03-16 11:18:14.670  1742  4303 E GCM     : Wifi connection closed with errorCode 20
03-16 11:18:14.671   885  1540 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
03-16 11:18:14.672   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.672   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.672   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
03-16 11:18:14.672   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.672   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
03-16 11:18:14.681   885  1237 E WifiStateMachine: setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
03-16 11:18:14.681   885  1237 E WifiStateMachine: setDetailed state send new extra info<unknown ssid>
03-16 11:18:14.683   885  1818 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3abe1097)
03-16 11:18:14.683   885  1240 D WifiService: Client connection lost with reason: 4
03-16 11:18:14.684   885  1241 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-16 11:18:14.685   885  1241 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-16 11:18:14.688   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,03-16 11:18:14.718   885  1540 W libprocessgroup: failed to open /acct/uid_10016/pid_1961/cgroup.procs: No such file or directory
,03-16 11:18:14.720  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.721  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.722  1296  1815 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-16 11:18:14.723   885  1237 D WifiMetrics: connected time updated 26264
03-16 11:18:14.723   885  1241 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,03-16 11:18:14.725   885  1241 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
03-16 11:18:14.725   885  5394 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,03-16 11:18:14.730  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,03-16 11:18:14.730  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:14.750   885  5398 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,03-16 11:18:14.754  1431  1431 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,03-16 11:18:14.757   885  1237 E WifiStateMachine: Start Disconnecting Watchdog 1
03-16 11:18:14.758  1431  1431 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
03-16 11:18:14.758   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
03-16 11:18:14.758   292  1669 D MDMCTBK : Event received = Trying to associate with
,03-16 11:18:14.759   885  1511 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
03-16 11:18:14.759   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.759   292  1669 D MDMCTBK : Event received = CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.760  1431  1431 E wpa_supplicant: DSDS: eapol_sm_notify_config config->sim_num = 1
,03-16 11:18:14.765   885  1237 E WifiStateMachine: ConnectModeState: Network connection lost 
03-16 11:18:14.765   885  5400 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
03-16 11:18:14.766   885  1237 E WifiStateMachine: handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,03-16 11:18:14.767   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,03-16 11:18:14.770   885  1236 D WifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.770   885  1236 D WifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,03-16 11:18:14.771  1431  1431 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,03-16 11:18:14.773  5329  5397 E SQLiteLog: (283) recovered 61 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 11:18:14.809   289   818 D CommandListener: Clearing all IP addresses on wlan0
03-16 11:18:14.809   885  1241 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,03-16 11:18:14.810   885  1241 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,03-16 11:18:14.810   885  1241 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-16 11:18:14.811   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.811   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:14.811   885  3701 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
03-16 11:18:14.811  1296  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,03-16 11:18:14.812   885  1237 E WifiStateMachine: setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,03-16 11:18:14.813   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-16 11:18:14.821   885  1520 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5404 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-16 11:18:14.822   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-16 11:18:14.825   885  1241 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-16 11:18:14.834   885  1241 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,03-16 11:18:14.842   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.099ms
,03-16 11:18:14.862   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.183ms
,03-16 11:18:14.866  1541  1541 I ModemStatsDSDetect: onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,03-16 11:18:14.867  1541  1541 I ModemStatsDSDetect: INET_CONDITION=0 ,activeNet=null
,03-16 11:18:14.872  1541  1541 I ModemStatsDSDetect: onReceive() - done, currentInetCondition=0
03-16 11:18:14.872  1541  1541 I ModemStatsDSDetect: onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
03-16 11:18:14.872  1541  1541 I ModemStatsDSDetect: INET_CONDITION=0 ,activeNet=null
03-16 11:18:14.872  1541  1541 I ModemStatsDSDetect: onReceive() - done, currentInetCondition=0
,03-16 11:18:14.874  5329  5399 I Gmail   : notifyAccountChanged
,03-16 11:18:14.876   481   509 D TCMD    : NL - Read 244 bytes from update socket.
03-16 11:18:14.876   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.876   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.877   481   509 D TCMD    : NL - Read 68 bytes from update socket.
03-16 11:18:14.877   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.877   481   509 D TCMD    : Listening for incoming client connection request
,03-16 11:18:14.877   481   509 D TCMD    : NL - Read 1004 bytes from update socket.
03-16 11:18:14.877   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.877   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.878   481   509 D TCMD    : NL - Read 80 bytes from update socket.
03-16 11:18:14.878   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.878   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.878   481   509 D TCMD    : NL - Read 80 bytes from update socket.
03-16 11:18:14.878   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.878   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.878   481   509 D TCMD    : NL - Read 68 bytes from update socket.
03-16 11:18:14.878   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.878   481   509 D TCMD    : Listening for incoming client connection request
,03-16 11:18:14.879  1431  1431 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
03-16 11:18:14.879   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.879   292  1669 D MDMCTBK : Event received = CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.879   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with f4:f2:6d
03-16 11:18:14.879   292  1669 D MDMCTBK : Event received = Associated with f4:f2:6d
,03-16 11:18:14.882   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.882   292  1669 D MDMCTBK : Event received = CTRL-EVENT-STATE-CHANGE 
,03-16 11:18:14.884   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.631ms
03-16 11:18:14.885   885  1132 D Tethering: exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,03-16 11:18:14.885   885  1132 W Settings: Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 11:18:14.885   885  1132 E Tethering: ApnList is empty for checkDunConfigured()
03-16 11:18:14.885   885  1132 D Tethering:  upstream interface types: 
03-16 11:18:14.885   885  1132 D Tethering:  0
03-16 11:18:14.885   885  1132 D Tethering:  1
03-16 11:18:14.885   885  1132 D Tethering:  5
03-16 11:18:14.885   885  1132 D Tethering:  7
03-16 11:18:14.886   885  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,03-16 11:18:14.890   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.890   292  1669 D MDMCTBK : Event received = CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.890  1431  1431 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-16 11:18:14.890   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
03-16 11:18:14.890   292  1669 D MDMCTBK : Event received = WPA: Key negotiation com
03-16 11:18:14.891  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
03-16 11:18:14.891   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
03-16 11:18:14.891   292  1669 D MDMCTBK : Event received = CTRL-EVENT-CONNECTED - C
03-16 11:18:14.891   292  1669 D MDMCTBK :  STA Connected !!
03-16 11:18:14.891   481   509 D TCMD    : NL - Read 1004 bytes from update socket.
03-16 11:18:14.891   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:14.891   481   509 D TCMD    : Listening for incoming client connection request
03-16 11:18:14.892   292  1669 E MDMCTBK : cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2457, reply_len: 4, ret: 0
03-16 11:18:14.892   292  1669 D MDMCTBK : get_freq !!, resp=2457
03-16 11:18:14.892   292  1669 I MDMCTBK : get_freq !!, Strip data
03-16 11:18:14.892   292  1669 I MDMCTBK : get_freq !!, band = 2, freq = 2457
03-16 11:18:14.892   292  1669 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:18:14.892   292  1669 I MDMCTBK : checkDefaultInst, pid match
03-16 11:18:14.892   292  1669 I MDMCTBK : get_property_value, Enter
03-16 11:18:14.892   292  1669 I MDMCTBK : get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
03-16 11:18:14.892   292  1669 I MDMCTBK : get_property_value, Exit
03-16 11:18:14.892   292  1669 I MDMCTBK : MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
03-16 11:18:14.892   292  1669 I MDMCTBK : MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
03-16 11:18:14.892   292  1669 I MDMCTBK : MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
03-16 11:18:14.892   292  1669 I MDMCTBK : set_property_value, Enter
03-16 11:18:14.892   292  1669 I MDMCTBK : set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
03-16 11:18:14.893   292  1669 I MDMCTBK : set_property_value, Values updated in the property file Successfully
03-16 11:18:14.893   292  1669 I MDMCTBK : set_property_value, Exit
03-16 11:18:14.893   292  1669 I MDMCTBK : MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
03-16 11:18:14.893   292  1669 I MDMCTBK : MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
03-16 11:18:14.893   292  1669 I MDMCTBK : MdmCutbackHndler, set WIFI TX pwr !!
03-16 11:18:14.893   292  1669 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:18:14.893   292  1669 I MDMCTBK : checkDefaultInst, pid match
03-16 11:18:14.893   292  1669 I MDMCTBK : get_property_value, Enter
03-16 11:18:14.893   292  1669 I MDMCTBK : get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
03-16 11:18:14.893   292  1669 I MDMCTBK : get_property_value, Exit
03-16 11:18:14.893   292  1669 I MDMCTBK : create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213506128
03-16 11:18:14.893   292  1669 I MDMCTBK : return from set_get_from_wpa_supplicant
03-16 11:18:14.893   292  1669 I MDMCTBK : MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,03-16 11:18:14.893   292  1669 I MDMCTBK : set_property_value, Enter,
03-16 11:18:14.893   292  1669 I MDMCTBK : set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
03-16 11:18:14.893   292  5422 D MDMCTBK : wifi_set_tx_pwr: SETTXPOWER = 18
,03-16 11:18:14.894   292  1669 I MDMCTBK : set_property_value, Values updated in the property file Successfully
03-16 11:18:14.894   292  5422 E MDMCTBK : cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
03-16 11:18:14.894   292  5422 E MDMCTBK : , reply_len: 3, ret: 0
03-16 11:18:14.894   292  1669 I MDMCTBK : set_property_value, Exit
03-16 11:18:14.894   292  5422 E MDMCTBK : MdmCutbackHndler, resp=OK
03-16 11:18:14.894   292  5422 E MDMCTBK : 
03-16 11:18:14.894   292  1669 E MDMCTBK : MdmCutbackHndler,Airplane Mode Enabled !! =1
03-16 11:18:14.894   292  5422 D MDMCTBK : wifi_set_tx_pwr: Exit
03-16 11:18:14.894   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,03-16 11:18:14.894   292  1669 D MDMCTBK : Event received = CTRL-EVENT-STATE-CHANGE 
03-16 11:18:14.896   885  1237 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
03-16 11:18:14.897   885  1237 E WifiStateMachine: setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,03-16 11:18:14.906   885  5416 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
03-16 11:18:14.909   885  1237 E WifiStateMachine: Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
03-16 11:18:14.909   885  1237 E WifiStateMachine: updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,03-16 11:18:14.911   885  1237 E WifiStateMachine: Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
03-16 11:18:14.911   885  1237 E WifiStateMachine: updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,03-16 11:18:14.913   885  1237 E WifiStateMachine: Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
03-16 11:18:14.913   885  1237 E WifiStateMachine: updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,03-16 11:18:14.913   885  1237 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
03-16 11:18:14.915   885  1237 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
03-16 11:18:14.915   885  1237 E WifiStateMachine: setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
03-16 11:18:14.915   885  1237 E WifiStateMachine: setDetailed state send new extra info"NG700"
,03-16 11:18:14.919  5329  5384 I Gmail   : getAccountsCursor
,03-16 11:18:14.928  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:14.929   885  5425 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
03-16 11:18:14.929  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:14.929  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.932  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
03-16 11:18:14.932  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.933  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.933  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.934  1296  1296 I SBar.MotoNetworkCtrlr: updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
03-16 11:18:14.934  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.935  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.935  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.937   885  1237 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
03-16 11:18:14.937   885  1237 E WifiStateMachine: setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
03-16 11:18:14.937  5329  5399 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 11:18:14.937   885  1237 E WifiStateMachine: setDetailed state send new extra info0x
,03-16 11:18:14.938  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.939  1296  1296 I SBar.MotoNetworkCtrlr: updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
03-16 11:18:14.940  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.940  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.941  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.941  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.942  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.946  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 11:18:14.947   885  1237 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
03-16 11:18:14.947   885  1237 E WifiStateMachine: setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
03-16 11:18:14.948   885  1237 E WifiStateMachine: setDetailed state send new extra info"NG700"
03-16 11:18:14.950  1296  1296 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
03-16 11:18:14.951  1558  1953 I art     : Explicit concurrent mark sweep GC freed 28473(1827KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.196ms total 82.973ms
03-16 11:18:14.951  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:14.953  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:14.954  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.954  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:14.954  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.955  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.955  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.963  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.963  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.964  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.964  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.966  5329  5399 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:14.970   885  1237 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
03-16 11:18:14.970   885  1237 E WifiStateMachine: setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,03-16 11:18:14.972   885  1237 E WifiStateMachine: Network connection established
03-16 11:18:14.972   885  1237 E WifiStateMachine: setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,03-16 11:18:14.974  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:14.974  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.977  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.978  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:14.982   885  1237 E WifiStateMachine: setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,03-16 11:18:14.986  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:14.987  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:14.988  5329  5399 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:14.990  5329  5399 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:14.990   885  1237 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
03-16 11:18:14.991   885  1237 E WifiStateMachine: L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,03-16 11:18:14.991   885  1237 E WifiStateMachine: L2ConnectedState "NG700" nid=0
03-16 11:18:14.991   885  1237 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-16 11:18:14.991   885  1241 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-16 11:18:14.993   885  1237 E WifiStateMachine: enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
03-16 11:18:14.993   885  1237 E WifiStateMachine: ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
03-16 11:18:14.993   885  1237 E WifiStateMachine: ObtainingIpAddress "NG700" nid=0
03-16 11:18:14.993   885  1237 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-16 11:18:14.999   289   818 D CommandListener: Setting iface cfg
,03-16 11:18:15.001   885  1237 E WifiStateMachine: Start Dhcp Watchdog 2
,03-16 11:18:15.010   885  1237 E WifiStateMachine: calculateWifiScore() report new score 60
,03-16 11:18:15.013  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:15.013  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.015   885  1241 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,03-16 11:18:15.017   885  1237 E WifiStateMachine: Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,03-16 11:18:15.017   885  1237 E WifiStateMachine: updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,03-16 11:18:15.019   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,03-16 11:18:15.019   885  1237 E native  : do suspend false
,03-16 11:18:15.026  1431  1431 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,03-16 11:18:15.026   885  1237 E WifiStateMachine: Unexpected BatchedScanResults :null
03-16 11:18:15.026  1431  1431 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
03-16 11:18:15.027   885  1236 D WifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2658a316 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:15.027   885  1236 D WifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2658a316 target=com.android.internal.util.StateMachine$SmHandler }
,03-16 11:18:15.040  5329  5349 I Gmail   : getAccountsCursor
,03-16 11:18:15.044  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:15.083  5275  5275 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:15.083  5275  5275 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:15.086   885   901 I ActivityManager: Killing 5179:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 11:18:15.204   885  1304 W libprocessgroup: failed to open /acct/uid_10088/pid_5179/cgroup.procs: No such file or directory
,03-16 11:18:15.237  5430  5430 E DHCPCD  : fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,03-16 11:18:15.238  5430  5430 I DHCPCD  : version 5.5.6 starting
,03-16 11:18:15.239  5430  5430 E DHCPCD  : fopen `/system/etc/dhcpcd/dhcpcd.conf': m
03-16 11:18:15.239  5430  5430 D DHCPCD  : wlan0: using ClientID 01:44:80:eb:7b:5a:06
,03-16 11:18:15.239  5430  5430 D DHCPCD  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,03-16 11:18:15.308   885  1100 W ProcessCpuTracker: Skipping unknown process pid 5377
,03-16 11:18:15.315   885  1100 W ProcessCpuTracker: Skipping unknown process pid 5380
03-16 11:18:15.317   885  1100 W ProcessCpuTracker: Skipping unknown process pid 5434
03-16 11:18:15.318   885  1100 W ProcessCpuTracker: Skipping unknown process pid 5436
03-16 11:18:15.318   885  1100 W ProcessCpuTracker: Skipping unknown process pid 5437
,03-16 11:18:15.352  5430  5430 D DHCPCD  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,03-16 11:18:15.352  5430  5430 I DHCPCD  : wlan0: rebinding lease of 192.168.1.112
03-16 11:18:15.352  5430  5430 D DHCPCD  : wlan0: sending REQUEST (xid 0x8f73b517), next in 3.16 seconds
,03-16 11:18:15.364   303   388 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-16 11:18:15.370   885  1520 I art     : Explicit concurrent mark sweep GC freed 39637(2033KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.996ms total 150.485ms
,03-16 11:18:15.384  5430  5430 I DHCPCD  : wlan0: acknowledged 192.168.1.112 from 192.168.1.1
,03-16 11:18:15.414  5430  5430 I DHCPCD  : wlan0: leased 192.168.1.112 for 172800 seconds
03-16 11:18:15.414  5430  5430 D DHCPCD  : wlan0: adding IP address 192.168.1.112/24
,03-16 11:18:15.414  5430  5430 D DHCPCD  : wlan0: adding route to 192.168.1.0/24
03-16 11:18:15.414   481   509 D TCMD    : NL - Read 60 bytes from update socket.
03-16 11:18:15.414   481   509 D TCMD    : NL - ignore NL message, type = 20
03-16 11:18:15.414   481   509 D TCMD    : Listening for incoming client connection request
,03-16 11:18:15.414  5430  5430 D DHCPCD  : wlan0: adding default route via 192.168.1.1
03-16 11:18:15.414  5430  5430 D DHCPCD  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,03-16 11:18:15.416  5430  5430 D DHCPCD  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,03-16 11:18:15.421   885  1237 E WifiStateMachine: Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
03-16 11:18:15.421   885  1237 E WifiStateMachine: updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,03-16 11:18:15.462   885  1518 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5454 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:15.529   885   900 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5479 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:15.557   885  1818 I ActivityManager: Killing 5275:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:15.616   885  1539 W libprocessgroup: failed to open /acct/uid_10005/pid_5275/cgroup.procs: No such file or directory
,03-16 11:18:15.636  5213  5213 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:15.636  5213  5213 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:15.688  5213  5213 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:15.743   885  1248 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5514 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:15.744   885  1248 I ActivityManager: Killing 5352:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 11:18:15.753  5479  5513 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
03-16 11:18:15.754  5213  5213 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 11:18:15.754  5213  5213 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:15.814   885  1656 W libprocessgroup: failed to open /acct/uid_10060/pid_5352/cgroup.procs: No such file or directory
,03-16 11:18:15.827  5514  5514 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 11:18:15.827  5514  5514 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 11:18:15.828  5514  5514 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 11:18:15.828  5514  5514 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 11:18:15.832   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,03-16 11:18:15.844   885  1236 D WifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,03-16 11:18:15.844   885  1236 D WifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,03-16 11:18:15.846   885  1237 E WifiStateMachine: WifiStateMachine DHCP successful
,03-16 11:18:15.847   885  1237 E WifiStateMachine: Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,03-16 11:18:15.847   885  1237 E WifiStateMachine: updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,03-16 11:18:15.848   885  1237 E WifiStateMachine: Calling ARP set with IP = 192.168.1.112
,03-16 11:18:15.851   885  1237 E WifiStateMachine: setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,03-16 11:18:15.853  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:15.854  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.857  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,03-16 11:18:15.858  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.859   885  1237 E WifiStateMachine: setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
03-16 11:18:15.860   885  1241 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-16 11:18:15.862   885  1241 D ConnectivityService: Adding iface wlan0 to network 101
03-16 11:18:15.862  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:15.863  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.864  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
03-16 11:18:15.865  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.868   885  5534 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,03-16 11:18:15.874   885  1237 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
03-16 11:18:15.873   885  5536 D Checkin : publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,03-16 11:18:15.880  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
03-16 11:18:15.881  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.881  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.886   885  1241 E ConnectivityService: Unexpected mtu value: 0, wlan0
03-16 11:18:15.886   885  1241 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,03-16 11:18:15.888   885  1237 E WifiStateMachine: ConnectedState Enter  mScreenOn=true scanperiod=20000
,03-16 11:18:15.889   885  1241 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,03-16 11:18:15.891   885  1241 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,03-16 11:18:15.893   885  1241 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,03-16 11:18:15.894   885  1241 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
03-16 11:18:15.894   885  1241 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
03-16 11:18:15.894   885  1241 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
03-16 11:18:15.894   885  1241 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,03-16 11:18:15.894   885  1241 D ConnectivityService:    accepting network in place of null
03-16 11:18:15.894   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:15.894   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
03-16 11:18:15.894   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-16 11:18:15.894   885  1241 D ConnectivityService: UpdateTcpBufferSizes: same sizes as current, ignore operation
03-16 11:18:15.894   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,03-16 11:18:15.899   885  1241 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,03-16 11:18:15.899   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-16 11:18:15.904   885  1241 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,03-16 11:18:15.905   885  1241 D ConnectivityService: UpdateTcpBufferSizes: same sizes as current, ignore operation
,03-16 11:18:15.905   885  1241 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,03-16 11:18:15.906  1296  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-16 11:18:15.907  1541  1541 I ModemStatsDSDetect: onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
03-16 11:18:15.907  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.912  1541  1541 I ModemStatsDSDetect: INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:15.912  1541  1541 I ModemStatsDSDetect: onReceive() - done, currentInetCondition=0
,03-16 11:18:15.914  1296  1296 I SBar.MotoNetworkCtrlr: updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,03-16 11:18:15.914  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:15.914  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.915  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:15.924  1576  1576 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@25a941ed new=com.google.android.velvet.VelvetApplication@25a941ed
,03-16 11:18:15.926  5404  5543 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-16 11:18:15.969   885  1487 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.chimera.GmsIntentOperationService: pid=5545 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 11:18:16.096   885  1656 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5562 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:16.099  5404  5543 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,03-16 11:18:16.115   885  1520 I ActivityManager: Killing 5329:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 11:18:16.129  5545  5545 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:16.129  5545  5545 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:16.170  5545  5545 I MultiDex: VM with version 2.1.0 has multidex support
03-16 11:18:16.170  5545  5545 I MultiDex: install
03-16 11:18:16.170  5545  5545 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-16 11:18:16.187   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Mar 2016 10:18:16 GMT], X-Android-Received-Millis=[1458123496187], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458123496123]}
,03-16 11:18:16.187   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
03-16 11:18:16.187   885  5426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
03-16 11:18:16.187   885  1241 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
03-16 11:18:16.187   885  1241 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
03-16 11:18:16.187   885  1241 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
03-16 11:18:16.188   885  1241 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
03-16 11:18:16.188   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
03-16 11:18:16.189  1296  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-16 11:18:16.204   885  1656 W libprocessgroup: failed to open /acct/uid_10063/pid_5329/cgroup.procs: No such file or directory
,03-16 11:18:16.211  1541  1541 I ModemStatsDSDetect: onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,03-16 11:18:16.212  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:16.213  1541  1541 I ModemStatsDSDetect: INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:16.213  1541  1541 I ModemStatsDSDetect: Inetcondition changed, white->blue
03-16 11:18:16.213  1541  1541 I ModemStatsDSDetect: onReceive() - done, currentInetCondition=100
,03-16 11:18:16.213  1296  1296 I SBar.MotoNetworkCtrlr: updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
03-16 11:18:16.214  1296  1296 I SBar.MotoNetworkCtrlr: updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,03-16 11:18:16.214  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:16.214  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 11:18:16.215  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
03-16 11:18:16.216  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:16.234  5562  5562 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:16.303  5545  5545 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:16.356  5545  5545 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 11:18:16.357  5545  5545 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38f116e2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:18:16.357  5545  5545 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:16.367  5545  5545 D ChimeraCfgMgr: Reading stored module config
,03-16 11:18:16.417  5545  5589 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-16 11:18:16.417  5545  5589 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 11:18:16.470  5545  5589 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 11:18:16.530   885  1656 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5600 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:16.601  5545  5587 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-16 11:18:16.624   885   901 I ActivityManager: Killing 5297:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:18:16.724   885  1593 W libprocessgroup: failed to open /acct/uid_10008/pid_5297/cgroup.procs: No such file or directory
,03-16 11:18:16.741  5545  5612 I Icing   : Storage manager: low false usage 1.72MB avail 3.10GB capacity 4.85GB
,03-16 11:18:16.786  5545  5545 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 11:18:16.787  5545  5545 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 11:18:16.825  5600  5600 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 11:18:16.828  5545  5559 W art     : Suspending all threads took: 40.066ms
,03-16 11:18:16.848   885  1226 V AlarmManager: send {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN}
03-16 11:18:16.848   885  1226 V AlarmManager: send {3c6e6b12, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-16 11:18:16.871  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:16.881   885  1226 V AlarmManager: send {2ef2d4e0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
03-16 11:18:16.882   885   885 V AlarmManager: done {2ef2d4e0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [1ms]
,03-16 11:18:16.906   885  1241 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,03-16 11:18:16.947  5600  5600 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 11:18:16.959  5600  5600 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:16.960  5600  5600 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:17.015  5600  5600 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-16 11:18:17.017  5600  5657 D Ads     : Skipping gmscore version check
,03-16 11:18:17.027  5600  5600 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 11:18:17.027  5600  5600 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 11:18:17.037  5600  5600 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
03-16 11:18:17.038  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:17.048  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:17.050  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:17.060  5600  5600 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 11:18:17.099   885   901 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5661 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 11:18:17.159  5661  5661 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:17.201   885  1564 I ActivityManager: Killing 5454:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 11:18:17.214   885  1539 W libprocessgroup: failed to open /acct/uid_10019/pid_5454/cgroup.procs: No such file or directory
,03-16 11:18:17.222  5545  5612 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 11:18:17.258   885  1564 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5681 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:17.292  5681  5681 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:17.322  5681  5681 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:17.329   885   885 V AlarmManager: done {501113a, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [4620ms]
,03-16 11:18:17.341  5681  5699 E SQLiteLog: (284) automatic index on view_events(_id)
,03-16 11:18:17.378   885  1656 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5700 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:17.398  5545  5612 I Icing   : Internal init done: storage state 0
,03-16 11:18:17.421  5545  5612 I Icing   : Post-init done
,03-16 11:18:17.423  5545  5612 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 11:18:17.513  5700  5723 I Gmail   : getAccountsCursor
,03-16 11:18:17.514  5700  5724 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 11:18:17.521  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:17.576   885  1594 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5726 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:17.718   885   900 I art     : Explicit concurrent mark sweep GC freed 18263(945KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.531ms total 119.321ms
,03-16 11:18:17.722   885  1657 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 11:18:17.735  5700  5746 I Gmail   : Observing account changes for notifications
,03-16 11:18:17.761  5726  5726 I Exchange: EasService.onCreate
,03-16 11:18:17.768  5726  5749 I Exchange: RestartPingTask
,03-16 11:18:17.770  5700  5700 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 11:18:17.775  5726  5726 I Exchange: RestartPingsTask did not start any pings.
03-16 11:18:17.775  5726  5726 I Exchange: PSS stopIfIdle
03-16 11:18:17.775  5726  5726 I Exchange: PSS has no active accounts; stopping service.
,03-16 11:18:17.817  5726  5726 I Exchange: onDestroy
,03-16 11:18:17.819   885  1818 I ActivityManager: Killing 5514:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
03-16 11:18:17.819  5700  5753 I Gmail   : getAccountsCursor
,03-16 11:18:17.823   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-16 11:18:17.867   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-16 11:18:17.867   885   901 W libprocessgroup: failed to open /acct/uid_10027/pid_5514/cgroup.procs: No such file or directory
,03-16 11:18:17.868  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:17.870   885  1132 D Tethering: MasterInitialState.processMessage what=3
,03-16 11:18:17.871  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.872  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.874  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.878  2548  2548 D OtaApp  : [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:17.878  1474  1474 D Central_PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.879  1474  1474 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,03-16 11:18:17.882   885  1132 D Tethering: MasterInitialState.processMessage what=3
,03-16 11:18:17.890  4458  4458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:18:17.892  1474  1474 D Central_PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.894  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.894  2548  2548 D PollingManager: not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
03-16 11:18:17.894  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:17.895  2548  2548 D PollingManager: not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
03-16 11:18:17.895  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:17.895  2548  2548 D PollingManager: not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,03-16 11:18:17.895  1474  1474 D Central_PollingManager: not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
03-16 11:18:17.896  2548  2548 D OtaApp  : [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:17.897  2548  2548 D OtaApp  : [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,03-16 11:18:17.897  2548  2548 D CCE     : Registering with Alarm Manager to restart CCE
,03-16 11:18:17.902  4458  4458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:18:17.904  2548  2548 D CCE     : Registering with Alarm Manager to restart CCE
,03-16 11:18:17.910  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:17.912  2548  2548 D CCE     : Registering with Alarm Manager to restart CCE
,03-16 11:18:17.916  2548  2652 D OtaApp  : [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,03-16 11:18:17.920  2548  2652 D OtaApp  : [debug] > CusSM.onRadioDown
,03-16 11:18:17.941  5700  5762 E SQLiteLog: (283) recovered 62 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 11:18:17.975   885  1656 I ActivityManager: Killing 5404:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 11:18:18.013  5700  5764 I Gmail   : notifyAccountChanged
,03-16 11:18:18.015  5700  5754 I Gmail   : getAccountsCursor
03-16 11:18:18.015   885  1594 W libprocessgroup: failed to open /acct/uid_10039/pid_5404/cgroup.procs: No such file or directory
,03-16 11:18:18.020  5700  5764 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:18.022  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:18.023  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:18.024  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:18.025  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,03-16 11:18:18.028  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:18.028  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:18.031  5700  5764 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:18.036  5600  5640 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
,03-16 11:18:18.036  5600  5640 I qtaguid : Untagging socket 37 failed errno=-22
,03-16 11:18:18.036  5600  5640 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
03-16 11:18:18.038  1742  1742 D WearableService: callingUid 10016, callindPid: 1742
,03-16 11:18:18.043  1742  2382 E MDM     : [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 11:18:18.044  5600  5600 D Finsky  : [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,03-16 11:18:18.054  5545  5769 D LocationInitializer: Restart initialization of location
03-16 11:18:18.055  5700  5764 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:18.057  5700  5764 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:18.064  1742  1742 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 11:18:18.077  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:18.085   885   885 V AlarmManager: done {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [1238ms]
,03-16 11:18:18.086   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=42.50 rxSuccessRate=36.00 targetRoamBSSID=any RSSI=-43
03-16 11:18:18.086   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=4961 interval=20000 maxinterval=300000
03-16 11:18:18.086   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-16 11:18:18.087   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=42.50 rx=36.00
,03-16 11:18:18.089   885   885 V AlarmManager: done {3c6e6b12, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [1241ms]
,03-16 11:18:18.121  1742  2011 W GCoreFlp: No location to return for getLastLocation()
03-16 11:18:18.121  1742  5770 W FusedLocationProvider: location=null
,03-16 11:18:18.136  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:18.185   885  1594 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5781 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 11:18:18.206   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.233ms
,03-16 11:18:18.226   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.432ms
,03-16 11:18:18.246   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.692ms
,03-16 11:18:18.286   885  1540 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5799 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:18.321  5781  5781 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:18.321  5781  5781 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:18.336   885  1226 V AlarmManager: send {14353000, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,03-16 11:18:18.339  5545  5777 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-16 11:18:18.344  5681  5681 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 11:18:18.345  5681  5681 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:18.349   885   900 I ActivityManager: Killing 5562:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,03-16 11:18:18.380  5781  5781 I MultiDex: VM with version 2.1.0 has multidex support
03-16 11:18:18.380  5781  5781 I MultiDex: install
03-16 11:18:18.380  5781  5781 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-16 11:18:18.409  5799  5799 I MusicStore: Database version: 120
,03-16 11:18:18.414   885  1304 W libprocessgroup: failed to open /acct/uid_10090/pid_5562/cgroup.procs: No such file or directory
,03-16 11:18:18.421  5700  5723 I Gmail   : getAccountsCursor
,03-16 11:18:18.425  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:18.438  5781  5781 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:18.460   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:18.460   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:18.461  5799  5799 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:18.495  5781  5781 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 11:18:18.495  5545  5612 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
03-16 11:18:18.496  5781  5781 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f29fffc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:18:18.496  5781  5781 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:18.507  5781  5781 D ChimeraCfgMgr: Reading stored module config
,03-16 11:18:18.524   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:18.524   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:18.525  5799  5799 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
03-16 11:18:18.527   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:18.527   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:18.527  5799  5799 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:18.555  5545  5612 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-16 11:18:18.558  5799  5799 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:18.559  5799  5799 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:18.580  5545  5559 W art     : Suspending all threads took: 7.708ms
,03-16 11:18:18.585  5545  5612 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 11:18:18.593  5545  5559 I art     : Background sticky concurrent mark sweep GC freed 25331(1827KB) AllocSpace objects, 18(288KB) LOS objects, 16% free, 11MB/13MB, paused 10.994ms total 54.450ms
03-16 11:18:18.593  5252  5274 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-16 11:18:18.602  5252  5274 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 11:18:18.608  5545  5545 I GAv4-SVC: Google Analytics 8.7.03 is starting up.
,03-16 11:18:18.611  5799  5799 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:18.624  5600  5641 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
,03-16 11:18:18.624  5600  5641 I qtaguid : Untagging socket 37 failed errno=-22
03-16 11:18:18.624  5600  5641 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-16 11:18:18.645  5781  5826 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-16 11:18:18.679  5799  5799 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 11:18:18.679  5799  5799 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@292d14c7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 11:18:18.679  5799  5799 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 11:18:18.680  5799  5799 D AndroidMusic: GMSCore installation verified
,03-16 11:18:18.686  5799  5799 I ConfigStore: Config Database version: 1
,03-16 11:18:18.704  5781  5781 D CAR.SERVICE: Connecting to CarCallService...
,03-16 11:18:18.724  5781  5781 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 11:18:18.725  5781  5781 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 11:18:18.760  3136  3152 I art     : Explicit concurrent mark sweep GC freed 2259(87KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 368us total 23.568ms
,03-16 11:18:18.787  5781  5781 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-16 11:18:18.812  5781  5781 D CAR.TEL.Service: Creating a new CarCallService.
03-16 11:18:18.814  5781  5781 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-16 11:18:18.817   885  1540 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-16 11:18:18.817  5781  5781 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@7c45318
,03-16 11:18:18.818   885  1657 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-16 11:18:18.820  5781  5781 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-16 11:18:18.820  5781  5781 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-16 11:18:18.824  5799  5799 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-16 11:18:18.851  5799  5799 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-16 11:18:18.858  5799  5799 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:18.904   885  1241 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-16 11:18:18.933  5781  5798 D CAR.SERVICE: Package validated; name: com.android.vending
,03-16 11:18:19.007   885  1564 I art     : Explicit concurrent mark sweep GC freed 14133(648KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.521ms total 118.798ms
,03-16 11:18:19.009   885  1132 D Tethering: MasterInitialState.processMessage what=3
,03-16 11:18:19.011  1474  1474 D Central_PollingManager: connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:19.012  1474  1474 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
03-16 11:18:19.012  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:19.012  2548  2548 D PollingManager: now: 100149 ,futureTime: 9223372036854775807
03-16 11:18:19.012  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:19.012  2548  2548 D PollingManager: now: 100150 ,futureTime: 9223372036854775807
03-16 11:18:19.013  2548  2548 D PollingManager: connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-16 11:18:19.013  2548  2548 D PollingManager: now: 100150 ,futureTime: 9223372036854775807
,03-16 11:18:19.013  2548  2548 D OtaApp  : [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-16 11:18:19.017  1474  1474 D Central_PollingManager: now: 100154 ,futureTime: 86476981
03-16 11:18:19.017  1474  1474 D Central_PollingManager: Polling alarm set to expire at: 86476981 Current Time: 100155
,03-16 11:18:19.018  2548  2548 D OtaApp  : [debug] > PollingManagerService, now: 100155 ,futureTime: 83232820
,03-16 11:18:19.019  2548  2548 D OtaApp  : [debug] > Polling alarm set to expire at: 83232820 Current Time: 100156
,03-16 11:18:19.023  4458  4458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:18:19.033  5799  5799 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:19.042  2548  2548 D MMApiProvisionService: isDeviceProvisioned: deviceId = 2072049230914535424
,03-16 11:18:19.051  2548  2548 D CCE     : trying to auto login since I haven't yet and the radio is up now
03-16 11:18:19.051  2548  2548 I MMApiProvisionService: createDeviceIdOrLogin update_device
,03-16 11:18:19.052  2548  2548 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 11:18:19.053  2548  2548 D MMApiProvisionService: Not proxy app, so login/provision not allowed
,03-16 11:18:19.066  2548  2548 D MMApiProvisionService: isDeviceProvisioned: deviceId = 2072049230914535424
,03-16 11:18:19.078   885   901 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5845 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:19.099  1474  1504 I art     : Explicit concurrent mark sweep GC freed 4677(197KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 664us total 32.019ms
,03-16 11:18:19.131  5799  5799 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-16 11:18:19.138  2548  2548 D CCE     : trying to auto login since I haven't yet and the radio is up now
03-16 11:18:19.138  2548  2548 I MMApiProvisionService: createDeviceIdOrLogin update_device
,03-16 11:18:19.140  2548  2548 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 11:18:19.141  5600  5600 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
03-16 11:18:19.143  5799  5799 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-16 11:18:19.152  2548  2548 D MMApiProvisionService: isDeviceProvisioned: deviceId = 2072049230914535424
,03-16 11:18:19.165  2548  2548 D MMApiProvisionService: set mOutstandingReq to true.
03-16 11:18:19.165  2548  2548 I  Nonce  :  Nonce getNonce 
03-16 11:18:19.165  2548  2548 I  Nonce  :  Nonce Request 
03-16 11:18:19.165  2548  2548 I  Nonce  :  Nonce execute Request 
,03-16 11:18:19.172  2548  2604 D MMApiWebService: doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,03-16 11:18:19.190  2548  2548 D MMApiProvisionService: isDeviceProvisioned: deviceId = 2072049230914535424
,03-16 11:18:19.207  2548  2548 D CCE     : trying to auto login since I haven't yet and the radio is up now
03-16 11:18:19.207  2548  2548 I MMApiProvisionService: createDeviceIdOrLogin update_device
03-16 11:18:19.208  2548  2548 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
03-16 11:18:19.209  2548  2548 D MMApiProvisionService: Not proxy app, so login/provision not allowed
03-16 11:18:19.210  2548  2656 D OtaApp  : [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
03-16 11:18:19.210  2548  2656 D OtaApp  : [debug] > CusSM.onRadioUp
,03-16 11:18:19.214  2548  2656 D OtaApp  : [debug] > CusSM.sendUpgradeStatus: no unlogged events.
03-16 11:18:19.220  2548  2656 D OtaApp  : [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
03-16 11:18:19.220  2548  2656 I OtaApp  : [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,03-16 11:18:19.223  2548  2656 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 11:18:19.227  2548  2656 D OtaApp  : [debug] > CusSM.runStateMachine: server told to :continue
03-16 11:18:19.228  2548  2656 D OtaApp  : [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
03-16 11:18:19.228  2548  2656 D OtaApp  : [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
03-16 11:18:19.232  2548  2656 D OtaApp  : [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,03-16 11:18:19.241  5799  5799 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:19.274   885  1520 I ActivityManager: Killing 5726:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 11:18:19.280  5845  5845 V Mms     : mnc/mcc: 
,03-16 11:18:19.283  2548  2604 D MMApiWebService: generating token using payload instead of using session token
03-16 11:18:19.283  5845  5845 V Mms     : tag: int value: recipientLimit - 20
03-16 11:18:19.284  5845  5845 V Mms     : tag: int value: smsToMmsTextThreshold - 6
03-16 11:18:19.284  5845  5845 V Mms     : tag: int value: emergencySmsTimeout - 30
03-16 11:18:19.284  5845  5845 V Mms     : tag: int value: maxSubjectLength - 80
03-16 11:18:19.284  5845  5845 V Mms     : tag: bool value: smsForceShowEncodingMenu - true
03-16 11:18:19.284  5845  5845 V Mms     : tag: bool value: enableGroupMms - false
03-16 11:18:19.285  5845  5845 V Mms     :  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:19.314  2548  2604 D  Nonce  :  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,03-16 11:18:19.320  2548  2604 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,03-16 11:18:19.321  2548  2604 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 11:18:19.384   885  1540 W libprocessgroup: failed to open /acct/uid_10060/pid_5726/cgroup.procs: No such file or directory
,03-16 11:18:19.447  5845  5873 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:19.486   885   901 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5874 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:19.526   885  1518 I ActivityManager: Killing 5661:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:18:19.538  5874  5874 D PhoneMonitor: Register our PhoneStateListener
,03-16 11:18:19.581  4458  4637 I jxcore-log: My device name is: motorola-XT1072
03-16 11:18:19.581  4458  4637 I jxcore-log: 
,03-16 11:18:19.585   885  1657 W libprocessgroup: failed to open /acct/uid_10008/pid_5661/cgroup.procs: No such file or directory
,03-16 11:18:19.593  5874  5874 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,03-16 11:18:19.595  5874  5874 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,03-16 11:18:19.598   885  1505 I ActivityManager: Killing 5681:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:19.599  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:19.685   885  1520 W libprocessgroup: failed to open /acct/uid_10005/pid_5681/cgroup.procs: No such file or directory
,03-16 11:18:19.748  5545  5895 I CheckinService: Disabling old GoogleServicesFramework version
,03-16 11:18:19.761  5545  5896 I CheckinService: Checking schedule, now: 1458123499761 next: 1458123507415
03-16 11:18:19.761  5545  5896 I CheckinService: active receiver: disabled
,03-16 11:18:19.808  5545  5901 I iu.SyncManager: SYNC; picasa accounts
,03-16 11:18:19.818  5545  5545 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-16 11:18:19.823  5545  5545 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-16 11:18:19.834  5545  5901 I iu.UploadsManager: num queued entries: 0
,03-16 11:18:19.838  5545  5901 I iu.UploadsManager: num updated entries: 0
,03-16 11:18:19.844  5545  5901 I iu.SyncManager: NEXT; no task
,03-16 11:18:19.913   885  1564 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5902 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:20.222   885  1594 I ActivityManager: Killing 5700:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 11:18:20.297  5600  5640 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-16 11:18:20.297  5600  5640 I qtaguid : Untagging socket 37 failed errno=-22
03-16 11:18:20.297  5600  5640 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-16 11:18:20.300  2548  2604 I  Nonce  :  Nonce Reponse 
03-16 11:18:20.300  2548  2604 D         : ProvisionWS.Response: processing response data: {"error":"OK","nonce":"5617f255-3860-4304-96c0-e55398a46874"}
,03-16 11:18:20.300  2548  2604 D MMApiWSBase: doRequest(): /v1/gdi/nonce.json resp length: 61
03-16 11:18:20.304  2548  2604 I  Nonce  :  Nonce Handle Reponse 
03-16 11:18:20.304  2548  2604 D MMApiProvisionService: mOutstandingReq set to false
,03-16 11:18:20.375   885  1564 W libprocessgroup: failed to open /acct/uid_10063/pid_5700/cgroup.procs: No such file or directory
,03-16 11:18:20.379   885  1656 W ActivityManager: getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,03-16 11:18:20.389   885  1237 E WifiStateMachine: Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
03-16 11:18:20.390   885  1237 E WifiStateMachine: updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
03-16 11:18:20.390   885  1241 D ConnectivityService: UpdateTcpBufferSizes: same sizes as current, ignore operation
03-16 11:18:20.390   885  1241 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
03-16 11:18:20.390   885  1241 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,03-16 11:18:20.391  1296  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,03-16 11:18:20.426   885   900 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5921 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:20.517  2548  2604 D MMApiProvisionService:  pTime 1458065539450 sExp 172742 cTime 1458123500517 tTime 1458238281450
03-16 11:18:20.517  2548  2604 D MMApiProvisionService:  No login Required 
,03-16 11:18:20.533  5600  5600 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:20.533  5600  5600 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:20.630  5213  5920 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-16 11:18:20.738  5600  5600 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:20.761  5600  5600 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,03-16 11:18:20.771   885  1226 V AlarmManager: send {23e2f57f, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,03-16 11:18:20.800  1742  4174 D DeviceConnectionService: client connected with version: 8296000
,03-16 11:18:20.817  5600  5600 D Finsky  : [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-16 11:18:20.817  5600  5600 D Finsky  : [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,03-16 11:18:20.833   885  1594 I ActivityManager: Killing 5479:android.process.acore/u0a7 (adj 15): empty #7
,03-16 11:18:20.861  2548  2582 W DataUsage: invalid counter update blocked: 'err' by 0
03-16 11:18:20.862  2548  2582 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 11:18:21.022   885  1594 I ActivityManager: Killing 5845:com.android.mms/u0a23 (adj 15): empty #7
,03-16 11:18:21.065   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=330, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310567, SEQNUM=4366, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-154, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:18:21.104   885  1594 I ActivityManager: Killing 5799:com.google.android.music:main/u0a80 (adj 15): empty #8
,03-16 11:18:21.276   885   900 W libprocessgroup: failed to open /acct/uid_10007/pid_5479/cgroup.procs: No such file or directory
,03-16 11:18:21.279   885  1657 W libprocessgroup: failed to open /acct/uid_10023/pid_5845/cgroup.procs: No such file or directory
,03-16 11:18:21.283   885  1564 W libprocessgroup: failed to open /acct/uid_10080/pid_5799/cgroup.procs: No such file or directory
,03-16 11:18:21.288  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:21.288  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:21.294  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:18:21.322   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 11:18:21.322   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:21.327  5921  5947 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 11:18:21.333   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 11:18:21.333   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:21.335  5921  5947 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 11:18:21.350  5921  5921 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-16 11:18:21.350  5921  5921 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 11:18:21.350  5921  5921 I GAv4    :   adb logcat -s GAv4
,03-16 11:18:21.368   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 11:18:21.368   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:21.372  5921  5948 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 11:18:21.395   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 11:18:21.395   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:21.396  5921  5948 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 11:18:21.496   885  1520 I art     : Explicit concurrent mark sweep GC freed 17008(819KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.529ms total 119.250ms
,03-16 11:18:21.498  5921  5921 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:21.519  5921  5921 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:21.523  5921  5954 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:21.588   885  1226 V AlarmManager: send {1688308b, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-16 11:18:21.802  5921  5921 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 11:18:21.821  5921  5921 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2966-2968)
,03-16 11:18:21.822  5921  5921 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:18:21.829  5921  5921 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34eb602c}
,03-16 11:18:21.829  5921  5921 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 11:18:21.830  5921  5921 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 11:18:21.843  5921  5921 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 11:18:21.844  5921  5921 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:18:21.846  5921  5921 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 11:18:21.864  5921  5921 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 11:18:21.869  5921  5921 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:18:21.869  5921  5921 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 11:18:21.870  5921  5921 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:21.870  5921  5921 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:21.870  5921  5921 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:21.870  5921  5921 I Adreno-EGL: Local Branch: 
03-16 11:18:21.870  5921  5921 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:21.870  5921  5921 I Adreno-EGL: Local Patches: NONE
03-16 11:18:21.870  5921  5921 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:21.877  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:21.938  5921  5982 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-16 11:18:21.952  5921  5921 I NSApplication: Starting up...
,03-16 11:18:22.004   885   900 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5987 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:22.005   885   900 I ActivityManager: Killing 5874:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 11:18:22.128   885  1594 W libprocessgroup: failed to open /acct/uid_10035/pid_5874/cgroup.procs: No such file or directory
,03-16 11:18:22.513   885  1520 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6009 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-16 11:18:22.514   885  1520 I ActivityManager: Killing 5902:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 11:18:22.626   885  1657 W libprocessgroup: failed to open /acct/uid_10088/pid_5902/cgroup.procs: No such file or directory
,03-16 11:18:22.645  6009  6009 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:22.889   885  1520 I ActivityManager: Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6033 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:23.044   885  1594 I ActivityManager: Killing 5781:com.google.android.gms:car/u0a16 (adj 15): empty #7
,03-16 11:18:23.099  6033  6054 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:18:23.159   885  1594 I ActivityManager: Killing 5213:com.google.android.talk/u0a70 (adj 15): empty #8
,03-16 11:18:23.305   885   900 W libprocessgroup: failed to open /acct/uid_10016/pid_5781/cgroup.procs: No such file or directory
,03-16 11:18:23.308   885   900 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,03-16 11:18:23.309   885  1564 W libprocessgroup: failed to open /acct/uid_10070/pid_5213/cgroup.procs: No such file or directory
,03-16 11:18:23.361   885  1657 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6057 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:23.496  6057  6057 I MusicStore: Database version: 120
,03-16 11:18:23.539   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:23.539   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:23.540  6057  6057 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:23.592   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:23.592   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:23.594  6057  6057 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:23.596   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,03-16 11:18:23.596   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:23.597  6057  6057 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:23.620  6057  6057 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:23.620  6057  6057 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:23.649  6057  6057 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:23.702  6057  6057 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 11:18:23.703  6057  6057 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@292d14c7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 11:18:23.703  6057  6057 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:23.703  6057  6057 D AndroidMusic: GMSCore installation verified
,03-16 11:18:23.709  6057  6057 I ConfigStore: Config Database version: 1
,03-16 11:18:23.786  6057  6057 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-16 11:18:23.789  6057  6057 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-16 11:18:23.796  6057  6057 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:23.826  6057  6057 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:23.869   885  1505 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6086 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:23.887  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:23.895  6057  6057 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-16 11:18:23.901  6057  6057 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-16 11:18:23.952   885  1818 I ActivityManager: Killing 5921:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-16 11:18:23.965  6086  6086 V Mms     : mnc/mcc: 
03-16 11:18:23.966  6086  6086 V Mms     : tag: int value: recipientLimit - 20
,03-16 11:18:23.967  6086  6086 V Mms     : tag: int value: smsToMmsTextThreshold - 6
03-16 11:18:23.967  6086  6086 V Mms     : tag: int value: emergencySmsTimeout - 30
03-16 11:18:23.967  6086  6086 V Mms     : tag: int value: maxSubjectLength - 80
03-16 11:18:23.967  6086  6086 V Mms     : tag: bool value: smsForceShowEncodingMenu - true
03-16 11:18:23.967  6086  6086 V Mms     : tag: bool value: enableGroupMms - false
03-16 11:18:23.968  6086  6086 V Mms     :  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:24.159   885  1818 E libprocessgroup: failed to kill 1 processes for processgroup 5921
,03-16 11:18:24.164  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:18:24.164  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:24.364  6086  6118 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:24.404   885  1818 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6119 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:24.426   308   308 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.403ms
,03-16 11:18:24.446   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.355ms
,03-16 11:18:24.467   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.271ms
,03-16 11:18:24.508   885  1520 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6136 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:24.591   885  1656 I ActivityManager: Killing 5600:com.android.vending/u0a32 (adj 15): empty #7
,03-16 11:18:24.599  6136  6136 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:24.618  6119  6119 D PhoneMonitor: Register our PhoneStateListener
,03-16 11:18:24.874   885   900 W libprocessgroup: failed to open /acct/uid_10032/pid_5600/cgroup.procs: No such file or directory
,03-16 11:18:24.884  6136  6136 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:24.890  6119  6119 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
03-16 11:18:24.891  6119  6119 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,03-16 11:18:24.895   885  1505 I ActivityManager: Killing 5987:com.android.chrome/u0a52 (adj 15): empty #7
,03-16 11:18:24.986   885   901 W libprocessgroup: failed to open /acct/uid_10052/pid_5987/cgroup.procs: No such file or directory
,03-16 11:18:25.056   885  1593 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6160 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:25.076  5545  6159 I CheckinService: Checking schedule, now: 1458123505076 next: 1458123507415
03-16 11:18:25.076  5545  6159 I CheckinService: active receiver: disabled
,03-16 11:18:25.360   885  1540 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6185 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 11:18:25.361   885  1540 I ActivityManager: Killing 6009:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 11:18:25.369   303   388 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-16 11:18:25.504   885  1564 W libprocessgroup: failed to open /acct/uid_10090/pid_6009/cgroup.procs: No such file or directory
,03-16 11:18:25.526  6185  6185 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:25.539   885  1100 W ProcessCpuTracker: Skipping unknown process pid 6167
03-16 11:18:25.539   885  1100 W ProcessCpuTracker: Skipping unknown process pid 6168
03-16 11:18:25.540   885  1100 W ProcessCpuTracker: Skipping unknown process pid 6206
,03-16 11:18:25.782  6185  6218 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 11:18:25.783  6185  6218 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 11:18:25.792  6185  6218 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 11:18:25.793  6185  6218 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 11:18:25.825  6185  6218 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 11:18:25.825  6185  6218 I Babel_SMS: MmsConfig.loadFromResources
,03-16 11:18:25.841  6185  6218 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-16 11:18:25.842  6185  6218 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:25.880  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:25.905  6185  6185 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:18:25.914  6185  6185 I Babel_Crash: startup - clean
,03-16 11:18:25.930  6185  6226 I Babel   : deleted: false for 0
,03-16 11:18:26.004  6136  6136 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:26.004  6136  6136 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:26.010   885   901 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6228 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:26.086   885  1304 I ActivityManager: Killing 6033:android.process.acore/u0a7 (adj 15): empty #7
,03-16 11:18:26.116  6185  6185 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 11:18:26.123  6185  6185 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 11:18:26.128  6185  6185 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 11:18:26.153  6185  6185 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 11:18:26.160  6185  6185 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 11:18:26.161  6185  6185 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:26.165  6185  6185 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:26.169  6185  6185 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:26.264   885  1248 W libprocessgroup: failed to open /acct/uid_10007/pid_6033/cgroup.procs: No such file or directory
,03-16 11:18:26.379   885  1539 I art     : Explicit concurrent mark sweep GC freed 10962(530KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.516ms total 112.863ms
,03-16 11:18:26.393  6185  6185 I vclib   : onServiceConnected
,03-16 11:18:26.393  6185  6185 W Babel   : Attempted to change video mute state without an active call.
,03-16 11:18:26.484   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 11:18:26.484   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:26.486  6228  6253 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 11:18:26.489   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 11:18:26.489   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:26.490  6228  6253 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 11:18:26.498  6228  6228 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-16 11:18:26.498  6228  6228 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 11:18:26.498  6228  6228 I GAv4    :   adb logcat -s GAv4
,03-16 11:18:26.502   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 11:18:26.502   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:26.502  6228  6254 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 11:18:26.506   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,03-16 11:18:26.506   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:26.506  6228  6254 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 11:18:26.514  6228  6228 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:26.536  6228  6228 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:26.545  6228  6256 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:26.559  6185  6246 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-16 11:18:26.562   885   901 I ActivityManager: Killing 6057:com.google.android.music:main/u0a80 (adj 15): empty #7
,03-16 11:18:26.784   885  1564 W libprocessgroup: failed to open /acct/uid_10080/pid_6057/cgroup.procs: No such file or directory
,03-16 11:18:26.881  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:26.950  6228  6228 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 11:18:26.970  6228  6228 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8115-8116)
,03-16 11:18:26.970  6228  6228 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:18:26.976  6228  6228 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34eb602c}
,03-16 11:18:26.977  6228  6228 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:18:26.977  6228  6228 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 11:18:26.990  6228  6228 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 11:18:26.991  6228  6228 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:18:26.992  6228  6228 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 11:18:27.009  6228  6228 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 11:18:27.014  6228  6228 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:18:27.014  6228  6228 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 11:18:27.015  6228  6228 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:27.015  6228  6228 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:27.015  6228  6228 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:27.015  6228  6228 I Adreno-EGL: Local Branch: 
03-16 11:18:27.015  6228  6228 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:27.015  6228  6228 I Adreno-EGL: Local Patches: NONE
03-16 11:18:27.015  6228  6228 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:27.060  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:27.061  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:27.079  6228  6228 I NSApplication: Starting up...
,03-16 11:18:27.086  6228  6287 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-16 11:18:27.130   885  1818 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6292 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:18:27.131   885  1818 I ActivityManager: Killing 6086:com.android.mms/u0a23 (adj 15): empty #7
,03-16 11:18:27.244   885  1540 W libprocessgroup: failed to open /acct/uid_10023/pid_6086/cgroup.procs: No such file or directory
,03-16 11:18:27.346   885  1593 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6311 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:27.347   885  1593 I ActivityManager: Killing 6119:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 11:18:27.454   885  1248 W libprocessgroup: failed to open /acct/uid_10035/pid_6119/cgroup.procs: No such file or directory
,03-16 11:18:27.471  6311  6311 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:27.694   885  1487 I ActivityManager: Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6331 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:27.767   885  1520 I ActivityManager: Killing 6160:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 11:18:27.852  6331  6351 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:18:27.882  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:27.929  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-16 11:18:27.929  4458  4637 I jxcore-log: 
,03-16 11:18:27.934   885  1520 I ActivityManager: Killing 6136:com.android.providers.calendar/u0a5 (adj 15): empty #8
,03-16 11:18:28.173   885   900 W libprocessgroup: failed to open /acct/uid_10088/pid_6160/cgroup.procs: No such file or directory
,03-16 11:18:28.177   885  1818 W libprocessgroup: failed to open /acct/uid_10005/pid_6136/cgroup.procs: No such file or directory
,03-16 11:18:28.180  2548  2548 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-16 11:18:28.273  2548  2548 I art     : Explicit concurrent mark sweep GC freed 24666(1399KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/18MB, paused 1.055ms total 78.817ms
,03-16 11:18:28.274  2548  2548 D GetNotificationsWS: bindWebServices(): registering our AIDL callback...
03-16 11:18:28.282  2548  6364 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
03-16 11:18:28.282  2548  6364 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-16 11:18:28.286  2548  2548 D GetNotificationsWS: onServiceConnected()
03-16 11:18:28.286  2548  2548 D GetNotificationsWS: onServiceConnected(): Registered for remote service callbacks...
,03-16 11:18:28.287  2548  2548 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-16 11:18:28.319   885   901 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6365 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:28.389  2548  6371 I PushService: started with background data enabled, making sure notification mechanism is enabled
,03-16 11:18:28.514  6365  6386 I Gmail   : getAccountsCursor
03-16 11:18:28.516  6365  6387 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 11:18:28.537  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:28.591   885  1818 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6393 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:28.692  6365  6365 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 11:18:28.714   885  1564 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 11:18:28.722  6393  6393 I Exchange: EasService.onCreate
,03-16 11:18:28.729  6393  6419 I Exchange: RestartPingTask
,03-16 11:18:28.765  6365  6415 I Gmail   : Observing account changes for notifications
,03-16 11:18:28.810   885  1593 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6427 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:28.812  6393  6393 I Exchange: RestartPingsTask did not start any pings.
03-16 11:18:28.812  6393  6393 I Exchange: PSS stopIfIdle
,03-16 11:18:28.812  6393  6393 I Exchange: PSS has no active accounts; stopping service.
,03-16 11:18:28.849  6365  6447 I Gmail   : getAccountsCursor
,03-16 11:18:28.857   885   885 V AlarmManager: done {14353000, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10521ms]
,03-16 11:18:28.862  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:28.883  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:28.903   885  1518 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6453 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 11:18:28.926   308   308 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.135ms
,03-16 11:18:28.947   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.964ms
,03-16 11:18:28.968   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.530ms
,03-16 11:18:28.994   885  1657 I ActivityManager: Killing 6228:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,03-16 11:18:29.014  6427  6427 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:29.284   885  1657 I ActivityManager: Killing 6185:com.google.android.talk/u0a70 (adj 15): empty #8
,03-16 11:18:29.404   885  1100 I ActivityManager: Waited long enough for: ServiceRecord{1b50fc90 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-16 11:18:29.409   885   900 W libprocessgroup: failed to open /acct/uid_10081/pid_6228/cgroup.procs: No such file or directory
,03-16 11:18:29.411   885  1818 W libprocessgroup: failed to open /acct/uid_10070/pid_6185/cgroup.procs: No such file or directory
,03-16 11:18:29.415  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:29.432  6393  6393 I Exchange: onDestroy
,03-16 11:18:29.438  6427  6427 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:29.462  6365  6478 E SQLiteLog: (283) recovered 63 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 11:18:29.467  6453  6453 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:29.551  6365  6480 I Gmail   : notifyAccountChanged
03-16 11:18:29.551   885  1248 I ActivityManager: Killing 6292:com.android.chrome/u0a52 (adj 13): empty #7
,03-16 11:18:29.554  6365  6386 I Gmail   : getAccountsCursor
,03-16 11:18:29.559  6365  6480 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:29.564  6365  6480 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:29.571  6365  6480 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:29.572  6365  6480 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:29.753   885  1539 W libprocessgroup: failed to open /acct/uid_10052/pid_6292/cgroup.procs: No such file or directory
,03-16 11:18:29.757  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:29.764  1742  1742 D WearableService: callingUid 10016, callindPid: 1742
,03-16 11:18:29.770  1742  3287 E MDM     : [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 11:18:29.772  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:29.774  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:29.777  5545  6493 D LocationInitializer: Restart initialization of location
,03-16 11:18:29.788  1742  1742 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 11:18:29.800  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:29.846   885  1520 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6497 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:29.877  1742  2011 W GCoreFlp: No location to return for getLastLocation()
,03-16 11:18:29.878  1742  6494 W FusedLocationProvider: location=null
,03-16 11:18:29.884  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:29.915  6365  6387 I Gmail   : getAccountsCursor
,03-16 11:18:29.918  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:30.038   885  1539 I art     : Explicit concurrent mark sweep GC freed 13358(634KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.488ms total 114.096ms
,03-16 11:18:30.053  6497  6497 I MusicStore: Database version: 120
,03-16 11:18:30.076  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:30.076  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:30.102   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:30.102   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:30.104  6497  6497 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:30.165   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:30.165   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:30.166  6497  6497 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:30.170   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 11:18:30.170   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:30.171  6497  6497 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 11:18:30.194  6497  6497 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:30.195  6497  6497 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:30.223  6497  6497 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:30.277  6497  6497 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 11:18:30.277  6497  6497 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@292d14c7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 11:18:30.277  6497  6497 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 11:18:30.277  6497  6497 D AndroidMusic: GMSCore installation verified
,03-16 11:18:30.283  6497  6497 I ConfigStore: Config Database version: 1
,03-16 11:18:30.359  6497  6497 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-16 11:18:30.362  6497  6497 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-16 11:18:30.369  6497  6497 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:30.397  6497  6497 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:18:30.442   885  1518 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6537 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:30.507  6427  6427 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:30.507  6427  6427 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:30.512  6497  6497 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-16 11:18:30.521  6497  6497 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-16 11:18:30.553   885  1657 I ActivityManager: Killing 6331:android.process.acore/u0a7 (adj 15): empty #7
,03-16 11:18:30.586  6537  6537 V Mms     : mnc/mcc: 
03-16 11:18:30.586  6537  6537 V Mms     : tag: int value: recipientLimit - 20
03-16 11:18:30.587  6537  6537 V Mms     : tag: int value: smsToMmsTextThreshold - 6
03-16 11:18:30.587  6537  6537 V Mms     : tag: int value: emergencySmsTimeout - 30
03-16 11:18:30.587  6537  6537 V Mms     : tag: int value: maxSubjectLength - 80
03-16 11:18:30.587  6537  6537 V Mms     : tag: bool value: smsForceShowEncodingMenu - true
03-16 11:18:30.587  6537  6537 V Mms     : tag: bool value: enableGroupMms - false
03-16 11:18:30.588  6537  6537 V Mms     :  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:30.697  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-16 11:18:30.697  4458  4637 I jxcore-log: 
,03-16 11:18:30.706  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-16 11:18:30.706  4458  4637 I jxcore-log: 
,03-16 11:18:30.724   885  1657 I ActivityManager: Killing 6311:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,03-16 11:18:30.780  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-16 11:18:30.780  4458  4637 I jxcore-log: 
,03-16 11:18:30.814  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-16 11:18:30.814  4458  4637 I jxcore-log: 
,03-16 11:18:30.820  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-16 11:18:30.820  4458  4637 I jxcore-log: 
,03-16 11:18:30.875   885  1594 W libprocessgroup: failed to open /acct/uid_10007/pid_6331/cgroup.procs: No such file or directory
,03-16 11:18:30.879   885  1564 W libprocessgroup: failed to open /acct/uid_10090/pid_6311/cgroup.procs: No such file or directory
,03-16 11:18:30.895  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:30.915  4458  4637 I jxcore-log: INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
03-16 11:18:30.915  4458  4637 I jxcore-log: 
03-16 11:18:30.917  4458  4637 I jxcore-log: INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-16 11:18:30.917  4458  4637 I jxcore-log: 
,03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 11:18:30.924  4458  4637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-16 11:18:30.929  4458  4637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-16 11:18:30.933  4458  4637 I jxcore-log: INFO thaliMobileNativeWrapper Method networkChanged registered to native
03-16 11:18:30.933  4458  4637 I jxcore-log: 
,03-16 11:18:30.935  4458  4637 I jxcore-log: INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
03-16 11:18:30.935  4458  4637 I jxcore-log: 
03-16 11:18:30.941  6537  6573 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:30.969   885  1518 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6574 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:31.026   885  1818 I ActivityManager: Killing 6393:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 11:18:31.224   885  1487 W libprocessgroup: failed to open /acct/uid_10060/pid_6393/cgroup.procs: No such file or directory
,03-16 11:18:31.249  6574  6574 D PhoneMonitor: Register our PhoneStateListener
,03-16 11:18:31.258  6574  6574 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,03-16 11:18:31.259  6574  6574 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,03-16 11:18:31.262   885  1505 I ActivityManager: Killing 6365:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 11:18:31.527   885   901 W libprocessgroup: failed to open /acct/uid_10063/pid_6365/cgroup.procs: No such file or directory
,03-16 11:18:31.607   885   900 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6601 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:31.609  5545  6600 I CheckinService: Checking schedule, now: 1458123511609 next: 1458123507415
03-16 11:18:31.609  5545  6600 I CheckinService: active receiver: enabled
,03-16 11:18:31.648  5545  6600 I CheckinService: Preparing to send checkin request
,03-16 11:18:31.673  5545  6600 I EventLogService: Accumulating logs since 1458123471812
,03-16 11:18:31.847  5545  6600 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-16 11:18:31.851   885  1240 D WifiService: New client listening to asynchronous messages
,03-16 11:18:31.852  5545  6600 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-16 11:18:31.993   885  1520 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6626 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 11:18:32.062   885  1539 I ActivityManager: Killing 6427:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:32.079  6626  6626 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:32.326   885  1656 W libprocessgroup: failed to open /acct/uid_10005/pid_6427/cgroup.procs: No such file or directory
,03-16 11:18:32.519  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:32.522  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:32.525  6626  6661 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 11:18:32.525  6626  6661 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 11:18:32.525  6626  6661 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 11:18:32.525  6626  6661 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 11:18:32.548  6626  6661 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,03-16 11:18:32.548  6626  6661 I Babel_SMS: MmsConfig.loadFromResources
,03-16 11:18:32.552  6626  6661 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-16 11:18:32.552  6626  6661 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:32.622  6626  6626 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:18:32.635  6626  6626 I Babel_Crash: startup - clean
,03-16 11:18:32.653  6626  6666 I Babel   : deleted: false for 0
,03-16 11:18:32.677   885  1487 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6668 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 11:18:32.797  6668  6668 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-16 11:18:32.798  6668  6668 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:32.843  6626  6626 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:32.848   885  1505 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6685 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:32.886  6668  6668 I MultiDex: VM with version 2.1.0 has multidex support
03-16 11:18:32.886  6668  6668 I MultiDex: install
03-16 11:18:32.886  6668  6668 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-16 11:18:32.897  6626  6626 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 11:18:32.904  6626  6626 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 11:18:32.915  6668  6668 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:32.940  6626  6626 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 11:18:32.958  6626  6626 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:32.974  6668  6668 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 11:18:32.975  6668  6668 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f29fffc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:18:32.975  6668  6668 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:32.980  6626  6626 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:32.996  6626  6626 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:33.001  6626  6626 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:33.020  6626  6626 I vclib   : onServiceConnected
,03-16 11:18:33.021  6626  6626 W Babel   : Attempted to change video mute state without an active call.
,03-16 11:18:33.040  6668  6668 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-16 11:18:33.041  6668  6668 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 11:18:33.083  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:18:33.083  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:33.121  6668  6704 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-16 11:18:33.147   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 11:18:33.148   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:33.148  6685  6712 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 11:18:33.151   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 11:18:33.151   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:33.153  6685  6712 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 11:18:33.156  6685  6685 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-16 11:18:33.156  6685  6685 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 11:18:33.156  6685  6685 I GAv4    :   adb logcat -s GAv4
,03-16 11:18:33.171   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 11:18:33.171   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 11:18:33.171  6685  6713 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 11:18:33.174   278   395 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 11:18:33.175   278   395 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:18:33.175  6685  6713 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 11:18:33.178  6685  6685 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:33.198  6685  6685 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:33.203  6685  6715 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 11:18:33.220  6626  6705 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-16 11:18:33.227   885  1656 I ActivityManager: Killing 6453:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:18:33.261   295  1246 D WVCdm   : Instantiating CDM.
,03-16 11:18:33.261   295   295 I WVCdm   : CdmEngine::OpenSession
03-16 11:18:33.262   295   295 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-16 11:18:33.277   295   295 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-16 11:18:33.304   295   295 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-16 11:18:33.304   295   295 D DrmWidevineDash: Service_Initialize: starts!
,03-16 11:18:33.304   295   295 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 11:18:33.304   295   295 D QSEECOMAPI: : App is not loaded in QSEE
03-16 11:18:33.304   295   295 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-16 11:18:33.304   295   295 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 11:18:33.304   295   295 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 11:18:33.304   295   295 D QSEECOMAPI: : App is not loaded in QSEE
03-16 11:18:33.304   295   295 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-16 11:18:33.304   295   295 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 11:18:33.305   295   295 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 11:18:33.305   295   295 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 11:18:33.334   295   295 D QSEECOMAPI: : Loaded image: APP id = 3
,03-16 11:18:33.335   295   295 D DrmWidevineDash: Service_Initialize: ends! returns 0
,03-16 11:18:33.335   295   295 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
03-16 11:18:33.335   295   295 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,03-16 11:18:33.343   295   295 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,03-16 11:18:33.343   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,03-16 11:18:33.344   295   295 D DrmWidevineDash: hlos api version =  9
03-16 11:18:33.344   295   295 D DrmWidevineDash: tz api version =  8
03-16 11:18:33.344   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 11:18:33.344   295   295 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-16 11:18:33.346   885   901 W libprocessgroup: failed to open /acct/uid_10008/pid_6453/cgroup.procs: No such file or directory
,03-16 11:18:33.365   295   295 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-16 11:18:33.365   295   295 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,03-16 11:18:33.365   295   295 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbefe44e0
03-16 11:18:33.365   295   295 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-16 11:18:33.366   295   295 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-16 11:18:33.366   295   295 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8038608, dataLength=8
03-16 11:18:33.366   295   295 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-16 11:18:33.367   295   295 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb803a800, wrapped_rsa_key_length=1280
,03-16 11:18:33.370   295   295 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-16 11:18:33.370   295   295 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-16 11:18:33.371   295   984 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,03-16 11:18:33.371   295   984 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-16 11:18:33.371   295   984 I WVCdm   : CdmEngine::GenerateKeyRequest
03-16 11:18:33.371   295   984 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8180dc0, idLength=0xb5449730
,03-16 11:18:33.381   295   984 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-16 11:18:33.381   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 11:18:33.382   295   984 D DrmWidevineDash: hlos api version =  9
03-16 11:18:33.382   295   984 D DrmWidevineDash: tz api version =  8
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 11:18:33.382   295   984 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-16 11:18:33.383   295   984 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-16 11:18:33.383   295   984 D WVCdm   : PrepareKeyRequest: nonce=3467770520
03-16 11:18:33.383   295   984 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81354d0
03-16 11:18:33.383   295   984 D DrmWidevineDash: message_length=1591, signature=0xb80b9938, signature_length=3041171220
,03-16 11:18:33.574   295   984 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-16 11:18:33.590   295  1246 I WVCdm   : CdmEngine::CloseSession
03-16 11:18:33.591   295  1246 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,03-16 11:18:33.591   295  1246 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-16 11:18:33.591   295  1246 I WVCdm   : L3 Terminate.
,03-16 11:18:33.591   295  1246 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-16 11:18:33.591   295  1246 D DrmWidevineDash: Service_Uninitialize: starts!
03-16 11:18:33.591   295  1246 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 11:18:33.591   295  1246 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-16 11:18:33.592   295  1246 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-16 11:18:33.592   295  1246 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-16 11:18:33.602  6685  6685 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 11:18:33.627  6685  6685 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4771-4773)
03-16 11:18:33.628  6685  6685 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:18:33.636  6685  6685 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34eb602c}
,03-16 11:18:33.637  6685  6685 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 11:18:33.637  6685  6685 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 11:18:33.650  6685  6685 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 11:18:33.651  6685  6685 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:18:33.652  6685  6685 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 11:18:33.669  6685  6685 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 11:18:33.674  6685  6685 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:18:33.674  6685  6685 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:18:33.675  6685  6685 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:33.675  6685  6685 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:33.675  6685  6685 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:33.675  6685  6685 I Adreno-EGL: Local Branch: 
03-16 11:18:33.675  6685  6685 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:33.675  6685  6685 I Adreno-EGL: Local Patches: NONE
03-16 11:18:33.675  6685  6685 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:33.734  6685  6746 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-16 11:18:33.822   295   983 I WVCdm   : CdmEngine::OpenSession
03-16 11:18:33.822   295   983 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-16 11:18:33.824   295   983 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-16 11:18:33.843   295   983 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,03-16 11:18:33.843   295   983 D DrmWidevineDash: Service_Initialize: starts!
03-16 11:18:33.843   295   983 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 11:18:33.843   295   983 D QSEECOMAPI: : App is not loaded in QSEE
03-16 11:18:33.843   295   983 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-16 11:18:33.843   295   983 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 11:18:33.843   295   983 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 11:18:33.843   295   983 D QSEECOMAPI: : App is not loaded in QSEE
03-16 11:18:33.843   295   983 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-16 11:18:33.843   295   983 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 11:18:33.843   295   983 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 11:18:33.844   295   983 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 11:18:33.855   885  1593 I art     : Explicit concurrent mark sweep GC freed 12479(630KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.761ms total 118.985ms
,03-16 11:18:33.864  6685  6685 I NSApplication: Starting up...
,03-16 11:18:33.878   295   983 D QSEECOMAPI: : Loaded image: APP id = 3
,03-16 11:18:33.880   295   983 D DrmWidevineDash: Service_Initialize: ends! returns 0
,03-16 11:18:33.880   295   983 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
03-16 11:18:33.880   295   983 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,03-16 11:18:33.887   295   983 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,03-16 11:18:33.887   295   983 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 11:18:33.887   295   983 D DrmWidevineDash: hlos api version =  9
03-16 11:18:33.887   295   983 D DrmWidevineDash: tz api version =  8
03-16 11:18:33.887   295   983 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 11:18:33.887   295   983 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-16 11:18:33.894   295   983 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,03-16 11:18:33.894   295   983 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-16 11:18:33.894   295   983 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb5549960
03-16 11:18:33.895   295   983 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-16 11:18:33.895   295   983 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-16 11:18:33.895   295   983 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8051808, dataLength=8
03-16 11:18:33.895   295   983 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,03-16 11:18:33.896   295   983 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb803a800, wrapped_rsa_key_length=1280
,03-16 11:18:33.899   295   983 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-16 11:18:33.899   295   983 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-16 11:18:33.899  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:33.903   295   295 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-16 11:18:33.903   295   295 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-16 11:18:33.903   295   295 I WVCdm   : CdmEngine::GenerateKeyRequest
03-16 11:18:33.903   295   295 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8180de0, idLength=0xbefe42b0
,03-16 11:18:33.910   295   295 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-16 11:18:33.910   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
,03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 11:18:33.911   295   295 D DrmWidevineDash: hlos api version =  9
03-16 11:18:33.911   295   295 D DrmWidevineDash: tz api version =  8
03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,03-16 11:18:33.911   295   295 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-16 11:18:33.912   295   295 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-16 11:18:33.912   295   295 D WVCdm   : PrepareKeyRequest: nonce=1910092229
03-16 11:18:33.912   295   295 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81354d0
03-16 11:18:33.912   295   295 D DrmWidevineDash: message_length=1622, signature=0xb80b9958, signature_length=3204334228
,03-16 11:18:33.924   885  1564 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6754 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:33.926   885  1564 I ActivityManager: Killing 6497:com.google.android.music:main/u0a80 (adj 15): empty #7
,03-16 11:18:34.094   885  1304 W libprocessgroup: failed to open /acct/uid_10080/pid_6497/cgroup.procs: No such file or directory
,03-16 11:18:34.102   295   295 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-16 11:18:34.105   295   984 I WVCdm   : CdmEngine::CloseSession
03-16 11:18:34.105   295   984 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-16 11:18:34.105   295   984 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-16 11:18:34.105   295   984 I WVCdm   : L3 Terminate.
03-16 11:18:34.105   295   984 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-16 11:18:34.105   295   984 D DrmWidevineDash: Service_Uninitialize: starts!
03-16 11:18:34.105   295   984 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 11:18:34.105   295   984 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-16 11:18:34.106   295   984 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-16 11:18:34.106   295   984 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-16 11:18:34.209  6773  6773 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-16 11:18:34.221   885  1818 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6776 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-16 11:18:34.222   885  1818 I ActivityManager: Killing 6537:com.android.mms/u0a23 (adj 15): empty #7
,03-16 11:18:34.294   885  1248 W libprocessgroup: failed to open /acct/uid_10023/pid_6537/cgroup.procs: No such file or directory
,03-16 11:18:34.311  6776  6776 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:34.313  6773  6773 I dex2oat : dex2oat took 104.399ms (threads: 4)
,03-16 11:18:34.330  6668  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:34.330  6668  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:34.330  6668  6717 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:34.330  6668  6717 I Adreno-EGL: Local Branch: 
03-16 11:18:34.330  6668  6717 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:34.330  6668  6717 I Adreno-EGL: Local Patches: NONE
03-16 11:18:34.330  6668  6717 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:34.411   885  1226 V AlarmManager: send {21506058, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,03-16 11:18:34.436  6668  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:34.436  6668  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:34.436  6668  6717 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:34.436  6668  6717 I Adreno-EGL: Local Branch: 
03-16 11:18:34.436  6668  6717 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:34.436  6668  6717 I Adreno-EGL: Local Patches: NONE
03-16 11:18:34.436  6668  6717 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:34.457   885  1226 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6799 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:18:34.457   885  1226 V AlarmManager: send {8a405b1, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
03-16 11:18:34.457   885   885 V AlarmManager: done {8a405b1, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [47ms]
,03-16 11:18:34.606   885  1593 I ActivityManager: Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6817 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:34.628   308   308 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 22.261ms
,03-16 11:18:34.649   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 19.820ms
,03-16 11:18:34.670   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.687ms
,03-16 11:18:34.679  6668  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:34.679  6668  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:34.679  6668  6717 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:34.679  6668  6717 I Adreno-EGL: Local Branch: 
03-16 11:18:34.679  6668  6717 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:34.679  6668  6717 I Adreno-EGL: Local Patches: NONE
03-16 11:18:34.679  6668  6717 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:34.702   885  1818 I ActivityManager: Killing 6574:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 11:18:34.751  6668  6717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:18:34.751  6668  6717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:18:34.751  6668  6717 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:18:34.751  6668  6717 I Adreno-EGL: Local Branch: 
03-16 11:18:34.751  6668  6717 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:18:34.751  6668  6717 I Adreno-EGL: Local Patches: NONE
03-16 11:18:34.751  6668  6717 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:18:34.817  6817  6840 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:18:34.900  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:34.905   885   901 W libprocessgroup: failed to open /acct/uid_10035/pid_6574/cgroup.procs: No such file or directory
,03-16 11:18:34.910  2548  2548 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-16 11:18:34.928  2548  2548 D GetNotificationsWS: bindWebServices(): registering our AIDL callback...
,03-16 11:18:34.931  2548  6844 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
03-16 11:18:34.932  2548  6844 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-16 11:18:34.933  2548  2548 D GetNotificationsWS: onServiceConnected()
03-16 11:18:34.933  2548  2548 D GetNotificationsWS: onServiceConnected(): Registered for remote service callbacks...
,03-16 11:18:34.937  2548  2548 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
03-16 11:18:34.938  2548  6845 I PushService: started with background data enabled, making sure notification mechanism is enabled
03-16 11:18:34.939  2548  2548 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-16 11:18:34.941  2548  2548 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
03-16 11:18:34.941  2548  2548 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-16 11:18:34.945   885   900 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-16 11:18:34.953  2548  2548 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-16 11:18:34.955  6799  6799 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 11:18:34.962  2548  2548 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-16 11:18:34.963  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 11:18:34.965  2548  2548 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 11:18:34.966  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 11:18:35.003   885  1487 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6850 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:35.004  2548  2548 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 11:18:35.057  2548  2548 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-16 11:18:35.058  2548  2548 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 11:18:35.143  6850  6850 D PhoneMonitor: Register our PhoneStateListener
03-16 11:18:35.144  6799  6799 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 11:18:35.165  6799  6799 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:35.194  6799  6799 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:35.200   885  1818 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6880 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:18:35.201   885  1518 I ActivityManager: Killing 6601:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 11:18:35.293  5545  6600 I CheckinRequestBuilder: Classify the device as Phone.
,03-16 11:18:35.326   885  1304 W libprocessgroup: failed to open /acct/uid_10088/pid_6601/cgroup.procs: No such file or directory
,03-16 11:18:35.354  6880  6880 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:35.364  6799  6799 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 11:18:35.364  6799  6799 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 11:18:35.373  1742  3892 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 11:18:35.374   303   388 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-16 11:18:35.376  6799  6799 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
03-16 11:18:35.377  6799  6901 D Ads     : Skipping gmscore version check
,03-16 11:18:35.415   885  1518 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6903 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:35.422  6880  6880 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:35.491   885  1539 I ActivityManager: Killing 6626:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 11:18:35.513  6799  6799 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 11:18:35.585   885  1593 W libprocessgroup: failed to open /acct/uid_10070/pid_6626/cgroup.procs: No such file or directory
,03-16 11:18:35.688  6799  6879 D Finsky  : [840] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,03-16 11:18:35.691  6799  6799 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,03-16 11:18:35.694   885  1248 I ActivityManager: Killing 6685:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-16 11:18:35.797  5545  6600 I CheckinTask: Sending checkin request (9673 bytes)
,03-16 11:18:35.901  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:35.994   885   900 W libprocessgroup: failed to open /acct/uid_10081/pid_6685/cgroup.procs: No such file or directory
,03-16 11:18:36.069   885   885 V AlarmManager: done {23e2f57f, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [15300ms]
03-16 11:18:36.071   885   885 V AlarmManager: done {1688308b, *walarm*:android.content.syncmanager.SYNC_ALARM} [14483ms]
,03-16 11:18:36.086  1742  4685 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 11:18:36.088   885  1226 V AlarmManager: send {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 11:18:36.090  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:36.091  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:36.098  6799  6931 D Finsky  : [845] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-16 11:18:36.137   885  1487 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6935 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 11:18:36.150  5545  6600 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-16 11:18:36.168  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:36.204  5545  6600 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-16 11:18:36.226  6935  6935 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:36.272  3136  3273 I art     : Explicit concurrent mark sweep GC freed 2624(102KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 375us total 51.775ms,
,03-16 11:18:36.332   885  1594 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6962 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:36.442  5545  6971 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,03-16 11:18:36.460   885  1096 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 182471, reason: UserStart
,03-16 11:18:36.467   885  1594 I ActivityManager: Killing 6754:com.android.chrome/u0a52 (adj 15): empty #7
,03-16 11:18:36.542  6962  6982 I Gmail   : getAccountsCursor
,03-16 11:18:36.586   885  1564 W libprocessgroup: failed to open /acct/uid_10052/pid_6754/cgroup.procs: No such file or directory
,03-16 11:18:36.589  6962  6983 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-16 11:18:36.593  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:36.597  6880  6880 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 11:18:36.598  6880  6880 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:36.634   885  1248 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6985 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:36.651   885  1505 I ActivityManager: Killing 6776:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 11:18:36.776   885  1564 W libprocessgroup: failed to open /acct/uid_10090/pid_6776/cgroup.procs: No such file or directory
,03-16 11:18:36.794   885  1518 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 11:18:36.801  6962  7009 I Gmail   : Observing account changes for notifications
,03-16 11:18:36.940   885  1505 I art     : Explicit concurrent mark sweep GC freed 13253(590KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.415ms total 112.927ms
,03-16 11:18:36.956  6985  6985 I Exchange: EasService.onCreate
,03-16 11:18:36.962  6985  7014 I Exchange: RestartPingTask
,03-16 11:18:36.965  6962  6962 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 11:18:36.980  6985  6985 I Exchange: RestartPingsTask did not start any pings.
03-16 11:18:36.980  6985  6985 I Exchange: PSS stopIfIdle
03-16 11:18:36.980  6985  6985 I Exchange: PSS has no active accounts; stopping service.
,03-16 11:18:37.013   885  1657 I ActivityManager: Killing 6817:android.process.acore/u0a7 (adj 15): empty #7
,03-16 11:18:37.020  5545  6600 I CheckinRequestBuilder: Classify the device as Phone.
,03-16 11:18:37.184   885  1304 W libprocessgroup: failed to open /acct/uid_10007/pid_6817/cgroup.procs: No such file or directory
,03-16 11:18:37.194  5545  6600 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
03-16 11:18:37.196  6985  6985 I Exchange: onDestroy
,03-16 11:18:37.199   885   900 I ActivityManager: Killing 6880:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:37.386  6962  7018 I Gmail   : getAccountsCursor
,03-16 11:18:37.387   885  1564 W libprocessgroup: failed to open /acct/uid_10005/pid_6880/cgroup.procs: No such file or directory
,03-16 11:18:37.390  5545  6600 I CheckinService: Checking schedule, now: 1458123517390 next: 1458724654195
03-16 11:18:37.390  5545  6600 I CheckinService: active receiver: disabled
,03-16 11:18:37.415  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:37.467   885  1518 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7032 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 11:18:37.471  5545  7030 I CheckinService: Checking schedule, now: 1458123517471 next: 1458724654195
03-16 11:18:37.471  5545  7030 I CheckinService: active receiver: disabled
,03-16 11:18:37.497  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:37.502   885  1657 I ActivityManager: Killing 6799:com.android.vending/u0a32 (adj 15): empty #7
,03-16 11:18:37.505  5545  5545 D CheckinService: Recording last checkin time for package unspecified as 1458123517505
,03-16 11:18:37.528  6962  7042 E SQLiteLog: (283) recovered 64 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 11:18:37.584  6962  7050 I Gmail   : notifyAccountChanged
,03-16 11:18:37.586  6962  7021 I Gmail   : getAccountsCursor
,03-16 11:18:37.588  6962  7050 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:37.592  6962  7050 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:18:37.599  6962  7050 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:37.600  6962  7050 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:18:37.737   885  1656 W libprocessgroup: failed to open /acct/uid_10032/pid_6799/cgroup.procs: No such file or directory
,03-16 11:18:37.742  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:37.758  7032  7032 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:37.820  6962  7021 I Gmail   : getAccountsCursor
,03-16 11:18:37.825  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:37.944  7032  7061 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 11:18:37.945  7032  7061 I Babel_SMS: MmsConfig.loadMmsSettings
03-16 11:18:37.945  7032  7061 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 11:18:37.945  7032  7061 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 11:18:37.966  7032  7061 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 11:18:37.966  7032  7061 I Babel_SMS: MmsConfig.loadFromResources
,03-16 11:18:37.968  7032  7061 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 11:18:37.969  7032  7061 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:38.044  7032  7032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:18:38.048  7032  7032 I Babel_Crash: startup - clean
,03-16 11:18:38.064  7032  7065 I Babel   : deleted: false for 0
,03-16 11:18:38.163  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:38.171  7032  7032 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 11:18:38.176   885  1564 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7067 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:38.222  7032  7032 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 11:18:38.254  7067  7067 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:38.255  1742  1742 D WearableService: callingUid 10016, callindPid: 1742
,03-16 11:18:38.260  1742  2336 E MDM     : [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 11:18:38.268  1742  1742 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
03-16 11:18:38.268  5545  7086 D LocationInitializer: Restart initialization of location
,03-16 11:18:38.282  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:38.299   885   885 V AlarmManager: done {21506058, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [3889ms]
03-16 11:18:38.301   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=12.93 rxSuccessRate=9.89 targetRoamBSSID=any RSSI=-48
03-16 11:18:38.301   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=25176 interval=20000 maxinterval=300000
03-16 11:18:38.301   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=25176 interval=20000 maxinterval=300000
03-16 11:18:38.301   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-16 11:18:38.301   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 11:18:38.301   885  1237 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-16 11:18:38.302  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-16 11:18:38.302   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 11:18:38.303   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 11:18:38.304   885  1237 E WifiStateMachine: [1,458,123,518,304 ms] noteScanstart no scan source
,03-16 11:18:38.305   885   885 V AlarmManager: done {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [2218ms]
,03-16 11:18:38.316  7067  7067 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:38.335  7032  7032 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 11:18:38.344  5545  7089 I CheckinService: Checking schedule, now: 1458123518344 next: 1458724654195
03-16 11:18:38.344  5545  7089 I CheckinService: active receiver: disabled
03-16 11:18:38.352  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:38.365   481   509 D TCMD    : NL - Read 56 bytes from update socket.
03-16 11:18:38.366   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:38.366   481   509 D TCMD    : Listening for incoming client connection request
,03-16 11:18:38.366   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:38.366   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:38.366   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
03-16 11:18:38.366   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 7
03-16 11:18:38.366   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 11:18:38.366   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-16 11:18:38.368   885  1237 E WifiStateMachine: [1,458,123,518,368 ms] noteScanEnd no scan source
,03-16 11:18:38.372   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@c2ec98c sup_state=COMPLETED debouncing=false
03-16 11:18:38.378  1742  1768 I art     : Explicit concurrent mark sweep GC freed 28174(1734KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 13MB/22MB, paused 1.302ms total 88.891ms
,03-16 11:18:38.385  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:38.399  1742  2011 W GCoreFlp: No location to return for getLastLocation()
03-16 11:18:38.400  1742  7087 W FusedLocationProvider: location=null
,03-16 11:18:38.416  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:38.421  6850  6850 V SetupWizard: Connected to Gservices successfully
,03-16 11:18:38.435  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:38.440  1474  1474 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-16 11:18:38.497  1742  2382 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 11:18:38.499  7032  7032 I vclib   : onServiceConnected
03-16 11:18:38.499  7032  7032 W Babel   : Attempted to change video mute state without an active call.
,03-16 11:18:38.530   885  1818 I ActivityManager: Killing 6985:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 11:18:38.726   885  1505 W libprocessgroup: failed to open /acct/uid_10060/pid_6985/cgroup.procs: No such file or directory
,03-16 11:18:38.729  1742  3287 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 11:18:38.904  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:39.100  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:39.100  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:39.436  7067  7067 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 11:18:39.437  7067  7067 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:39.456   885  1540 I ActivityManager: Killing 7032:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 11:18:39.685   885  1304 W libprocessgroup: failed to open /acct/uid_10070/pid_7032/cgroup.procs: No such file or directory
,03-16 11:18:39.752  5545  5895 I CheckinService: Done disabling old GoogleServicesFramework version
,03-16 11:18:40.293   885  1520 I ActivityManager: Killing 6903:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 11:18:40.384   885  1518 W libprocessgroup: failed to open /acct/uid_10088/pid_6903/cgroup.procs: No such file or directory
,03-16 11:18:41.716  1558  1558 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 11:18:41.718   885  1228 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 11:18:41.761   885  1100 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7108 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 11:18:41.919   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-16 11:18:41.919   885   885 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 11:18:41.921   885   885 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 11:18:41.929   885   885 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 11:18:41.931   885   885 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@e12f6ae
,03-16 11:18:41.982  1742  1742 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-16 11:18:41.984  6962  7012 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 11:18:42.014  1576  1576 I Launcher: Deferring update until onResume
,03-16 11:18:42.115  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:42.116  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:42.176   885  1248 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7142 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 11:18:42.190  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-16 11:18:42.190  4458  4637 I jxcore-log: 
,03-16 11:18:42.199  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-16 11:18:42.199  4458  4637 I jxcore-log: 
,03-16 11:18:42.207  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-16 11:18:42.207  4458  4637 I jxcore-log: 
,03-16 11:18:42.220   885  1818 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7159 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-16 11:18:42.221   885  1818 I ActivityManager: Killing 6962:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 11:18:42.241   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.333ms
,03-16 11:18:42.260   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 18.993ms
,03-16 11:18:42.280   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.756ms
,03-16 11:18:42.366   885  1564 I ActivityManager: Killing 6850:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 11:18:42.399  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-16 11:18:42.399  4458  4637 I jxcore-log: 
,03-16 11:18:42.575   885  1304 W libprocessgroup: failed to open /acct/uid_10063/pid_6962/cgroup.procs: No such file or directory
,03-16 11:18:42.584   885  1594 W libprocessgroup: failed to open /acct/uid_10035/pid_6850/cgroup.procs: No such file or directory
,03-16 11:18:42.601  7159  7159 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:18:42.742  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-16 11:18:42.742  4458  4637 I jxcore-log: 
,03-16 11:18:42.823  7159  7189 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 11:18:42.823  7159  7189 I Babel_SMS: MmsConfig.loadMmsSettings
03-16 11:18:42.823  7159  7189 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 11:18:42.823  7159  7189 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 11:18:42.871  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-16 11:18:42.871  4458  4637 I jxcore-log: 
,03-16 11:18:42.927  7159  7189 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,03-16 11:18:42.927  7159  7189 I Babel_SMS: MmsConfig.loadFromResources
,03-16 11:18:42.934   885  1657 I art     : Explicit concurrent mark sweep GC freed 23146(1184KB) AllocSpace objects, 2(120KB) LOS objects, 33% free, 21MB/32MB, paused 1.633ms total 134.050ms
,03-16 11:18:42.942  7159  7189 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-16 11:18:42.942  7159  7189 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 11:18:42.968  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-16 11:18:42.968  4458  4637 I jxcore-log: 
,03-16 11:18:43.008  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-16 11:18:43.008  4458  4637 I jxcore-log: 
,03-16 11:18:43.028  7159  7159 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:18:43.036  7159  7159 I Babel_Crash: startup - clean
,03-16 11:18:43.044  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-16 11:18:43.044  4458  4637 I jxcore-log: 
03-16 11:18:43.045  7159  7201 I Babel   : deleted: false for 0
,03-16 11:18:43.108   885  1564 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7203 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:18:43.202  7159  7159 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:43.219  7159  7159 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 11:18:43.234  7159  7159 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 11:18:43.244  7159  7173 W art     : Suspending all threads took: 8.738ms
,03-16 11:18:43.285  7159  7159 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-16 11:18:43.292  7159  7159 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 11:18:43.294  7159  7159 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 11:18:43.297  7159  7159 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 11:18:43.297  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-16 11:18:43.297  4458  4637 I jxcore-log: 
,03-16 11:18:43.303  7159  7159 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:18:43.311  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-16 11:18:43.311  4458  4637 I jxcore-log: 
,03-16 11:18:43.345   885  1594 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7222 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:18:43.346   885  1594 I ActivityManager: Killing 7067:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:18:43.375  4458  4637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-16 11:18:43.375  4458  4637 I jxcore-log: 
03-16 11:18:43.382  7203  7221 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:18:43.489  4458  4637 I jxcore-log: INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-16 11:18:43.489  4458  4637 I jxcore-log: 
,03-16 11:18:43.544   885  1657 W libprocessgroup: failed to open /acct/uid_10005/pid_7067/cgroup.procs: No such file or directory
,03-16 11:18:43.557  7222  7222 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 11:18:43.557  7222  7222 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 11:18:43.557  7222  7222 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 11:18:43.558  7222  7222 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 11:18:43.620  7159  7159 I vclib   : onServiceConnected
03-16 11:18:43.620  7159  7159 W Babel   : Attempted to change video mute state without an active call.
,03-16 11:18:43.630  1576  1576 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@25a941ed new=com.google.android.velvet.VelvetApplication@25a941ed
03-16 11:18:43.630  7108  7246 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-16 11:18:43.642  5545  7249 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-16 11:18:43.642  5545  7249 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 11:18:43.645  7159  7159 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:18:43.645  7159  7159 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:18:43.679   885  1657 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7251 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:43.709  5545  7249 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 11:18:43.726  5545  5612 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 11:18:43.746  7159  7159 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:18:43.756  7251  7251 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:18:43.758  7108  7246 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 128 ms] updated apps [took 127 ms] 
,03-16 11:18:43.761   885  1505 I ActivityManager: Killing 6935:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:18:43.819  7159  7159 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:18:43.819  7159  7159 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:18:43.824   885  1593 W libprocessgroup: failed to open /acct/uid_10008/pid_6935/cgroup.procs: No such file or directory
,03-16 11:18:43.926  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:44.009   885  1304 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7280 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:44.062   885  1657 I ActivityManager: Killing 6668:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-16 11:18:44.097   885  1540 W libprocessgroup: failed to open /acct/uid_10016/pid_6668/cgroup.procs: No such file or directory
,03-16 11:18:44.161  7280  7280 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 11:18:44.264  7280  7280 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 11:18:44.277  7280  7280 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:44.278  7280  7280 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:18:44.317  7280  7280 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 11:18:44.317  7280  7280 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 11:18:44.320  7280  7322 D Ads     : Skipping gmscore version check
,03-16 11:18:44.330   885   900 I ActivityManager: Killing 7142:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 11:18:44.350   885  1248 W libprocessgroup: failed to open /acct/uid_10019/pid_7142/cgroup.procs: No such file or directory
,03-16 11:18:44.355  7280  7280 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 11:18:44.380  7280  7280 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 11:18:44.860  5545  5612 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 11:18:44.917  5545  5612 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 11:18:45.130  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:18:45.130  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:45.378   303   388 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-16 11:18:45.752   885  1593 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7331 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:18:45.790  7331  7331 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:18:45.821  7331  7331 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@17b92135(com.android.providers.calendar.CalendarProvider2@25ef79ca)
,03-16 11:18:45.928  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:46.091   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:18:46.091   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:18:46.091   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
,03-16 11:18:46.091   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:18:46.091   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:18:46.091   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:18:46.091   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:18:46.091   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:18:46.091   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
,03-16 11:18:46.091   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:18:46.091   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:18:46.091   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:18:46.091   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:18:46.091   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:18:46.844  7331  7331 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 11:18:46.846  7331  7331 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 11:18:46.896   885  1100 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7358 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 11:18:46.915   885  1505 I ActivityManager: Killing 7222:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-16 11:18:46.930  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:47.048   885  1818 W libprocessgroup: failed to open /acct/uid_10027/pid_7222/cgroup.procs: No such file or directory
,03-16 11:18:47.056  7358  7358 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 11:18:47.109   885  1656 I ActivityManager: Killing 7108:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 11:18:47.184   885  1594 W libprocessgroup: failed to open /acct/uid_10039/pid_7108/cgroup.procs: No such file or directory
,03-16 11:18:47.931  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:48.143  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:18:48.144  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:48.645  5545  5556 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-16 11:18:48.845   885  1304 I ActivityManager: Killing 7159:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 11:18:48.885   885  1505 W libprocessgroup: failed to open /acct/uid_10070/pid_7159/cgroup.procs: No such file or directory
,03-16 11:18:50.935  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:51.154  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:18:51.155  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:51.934  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:52.090   885  1226 V AlarmManager: send {305e2659, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,03-16 11:18:52.096   885   885 V AlarmManager: done {305e2659, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,03-16 11:18:52.278  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:52.286  1742  7406 I VacuumService: Vacuum at: now=1458123532286 tag=VacuumService
,03-16 11:18:52.308  5545  7401 W InstanceID/Rpc: Found 10016
,03-16 11:18:52.750  1742  7412 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 1721 seconds from now (1458123532750)
,03-16 11:18:52.862  1742  7410 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-16 11:18:52.876  1742  7410 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-16 11:18:53.935  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:54.166  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:54.167  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:55.383   303   388 I ThermalEngine: Sensor:xo_therm_pu2:36000 mC
,03-16 11:18:55.790  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:55.793  1742  1742 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:18:56.088   885  1226 V AlarmManager: send {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 11:18:56.091   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.95 rxSuccessRate=4.39 targetRoamBSSID=any RSSI=-48
03-16 11:18:56.091   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=42966 interval=20000 maxinterval=300000
03-16 11:18:56.091   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=42966 interval=20000 maxinterval=300000
03-16 11:18:56.091   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
,03-16 11:18:56.091   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =30000
03-16 11:18:56.092  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-16 11:18:56.092   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 11:18:56.092   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 11:18:56.097   885   885 V AlarmManager: done {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [9ms]
,03-16 11:18:56.099   885  1237 E WifiStateMachine: [1,458,123,536,099 ms] noteScanstart no scan source
,03-16 11:18:56.507   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
,03-16 11:18:56.507   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 18 
,03-16 11:18:56.507   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
03-16 11:18:56.507   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 19 
03-16 11:18:56.507   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
03-16 11:18:56.507   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 20 
,03-16 11:18:56.508   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
03-16 11:18:56.508   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 21 
03-16 11:18:56.508   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:56.508   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:56.508   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,03-16 11:18:56.508   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:56.508   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:56.508   292  1669 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 11:18:56.508   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 11:18:56.508   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-16 11:18:56.508   481   509 D TCMD    : NL - Read 56 bytes from update socket.
03-16 11:18:56.508   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:18:56.508   481   509 D TCMD    : Listening for incoming client connection request,
,03-16 11:18:56.519   885  1237 E WifiStateMachine: [1,458,123,536,519 ms] noteScanEnd no scan source
,03-16 11:18:56.523   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@c2ec98c sup_state=COMPLETED debouncing=false
,03-16 11:18:57.171  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:18:57.171  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:18:57.444   885  1249 E BackupManagerService: Timeout restoring application @pm@
,03-16 11:18:57.448   885  1249 W BackupManagerService: Tried to clear data for @pm@ but not found
,03-16 11:18:57.456  1742  1773 W GmsBackupTransport: Restore processing aborted, no more packages
,03-16 11:18:57.458   885  1249 E BackupManagerService: Failure getting next package name
03-16 11:18:57.458   885  1249 E BackupManagerService: Duplicate finish
,03-16 11:18:58.943  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:00.000   885  1226 V AlarmManager: send {17422fed, *alarm*:android.intent.action.TIME_TICK}
,03-16 11:19:00.033   885   885 V AlarmManager: done {17422fed, *alarm*:android.intent.action.TIME_TICK} [34ms]
,03-16 11:19:00.184  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:19:00.184  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:00.944  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:01.084   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=318, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310140, SEQNUM=4437, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-272, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:19:01.141  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:19:01.945  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:02.890  1420  1613 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-16 11:19:02.901  1420  1613 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-16 11:19:02.960  1742  1742 I ConfigService: onCreate
,03-16 11:19:03.198  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:19:03.198  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:05.388   303   388 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-16 11:19:05.947  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:06.207   885  1226 V AlarmManager: send {1688308b, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-16 11:19:06.209   885   885 V AlarmManager: done {1688308b, *walarm*:android.content.syncmanager.SYNC_ALARM} [2ms]
,03-16 11:19:06.209   885  1487 I art     : Explicit concurrent mark sweep GC freed 34078(1596KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.430ms total 142.489ms
,03-16 11:19:06.214  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:19:06.214  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:06.244   885   901 I ActivityManager: Killing 7251:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 11:19:06.274   885   901 I ActivityManager: Killing 7203:android.process.acore/u0a7 (adj 15): empty #8
,03-16 11:19:06.355   885  1505 W libprocessgroup: failed to open /acct/uid_10090/pid_7251/cgroup.procs: No such file or directory
,03-16 11:19:06.358   885  1487 W libprocessgroup: failed to open /acct/uid_10007/pid_7203/cgroup.procs: No such file or directory
,03-16 11:19:06.948  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:08.017  1742  1742 I ConfigService: onDestroy
,03-16 11:19:09.228  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:19:09.228  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:10.950  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:11.951  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:12.243  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:19:12.243  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:12.952  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:15.256  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:19:15.256  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:15.392   303   388 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-16 11:19:16.089   885  1226 V AlarmManager: send {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 11:19:16.095   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.62 rxSuccessRate=0.52 targetRoamBSSID=any RSSI=-47
,03-16 11:19:16.095   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=20004 interval=30000 maxinterval=300000
03-16 11:19:16.095   885  1237 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 11:19:16.095   885  1237 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-16 11:19:16.096  1431  1431 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-16 11:19:16.097   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,03-16 11:19:16.097   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 11:19:16.105   885   885 V AlarmManager: done {cb4ca8e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [16ms]
,03-16 11:19:16.106   885  1237 E WifiStateMachine: [1,458,123,556,106 ms] noteScanstart no scan source
,03-16 11:19:16.155   292  1669 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 11:19:16.155   292  1669 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-16 11:19:16.155   481   509 D TCMD    : NL - Read 56 bytes from update socket.
03-16 11:19:16.155   481   509 D TCMD    : NL - message type is RTM_NEWLINK
03-16 11:19:16.155   481   509 D TCMD    : Listening for incoming client connection request
,03-16 11:19:16.159   885  1237 E WifiStateMachine: [1,458,123,556,159 ms] noteScanEnd no scan source
,03-16 11:19:16.163   885  1237 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@c2ec98c sup_state=COMPLETED debouncing=false
,03-16 11:19:16.955  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:17.956  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:18.101   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:19:18.101   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:19:18.101   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:19:18.101   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:19:18.101   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:19:18.101   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:19:18.101   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:19:18.101   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:19:18.101   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:19:18.101   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:19:18.101   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:19:18.101   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:19:18.102   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:19:18.102   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:19:18.269  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 11:19:18.270  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:21.125   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=304, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310487, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-319, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:19:21.168  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:19:21.212  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:19:21.272  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 11:19:21.272  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:21.284  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
03-16 11:19:21.284  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,03-16 11:19:21.958  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:22.752   885  1136 I PowerManagerService: Nap time (uid 1000)...
,03-16 11:19:22.753   885  1136 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-16 11:19:22.781   885  1136 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 11:19:22.781   885  1136 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 11:19:22.781   885  1136 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 11:19:22.781   885  1136 I Adreno-EGL: Local Branch: 
03-16 11:19:22.781   885  1136 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 11:19:22.781   885  1136 I Adreno-EGL: Local Patches: NONE
03-16 11:19:22.781   885  1136 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 11:19:22.959  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 11:19:23.279   885  1136 D         : activate, handle: 1598182242, enabled: 0, index 2
,03-16 11:19:23.279   885  1136 D         : BstSensorExt: id=1598182242, en=0
03-16 11:19:23.279   885  1136 D         : enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 224
,03-16 11:19:23.285   885  1136 D         : activate, handle: 2, enabled: 0, index 5
,03-16 11:19:23.291   885  1133 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-16 11:19:23.292   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb7389550
,03-16 11:19:23.296   885   885 V ActivityManager: Display changed displayId=0
,03-16 11:19:23.297   279   279 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-16 11:19:23.436   288   288 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7fc2820
,03-16 11:19:23.437   288   288 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,03-16 11:19:23.437   288   288 I rmt_storage: wakelock acquired: 1, error no: 42
03-16 11:19:23.437   288   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1208212168)
,03-16 11:19:23.547   288   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,03-16 11:19:23.547   288   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
03-16 11:19:23.547   288   819 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1208212168) wakelock released: 1, error no: 0
03-16 11:19:23.547   288   819 I rmt_storage: 
,03-16 11:19:23.550   288   288 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7fc2820
,03-16 11:19:23.613   279   709 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-16 11:19:23.614   279   279 I qdhwcomposer: enable_dcabc: Done setting OFF mode
,03-16 11:19:23.614   279   279 D qdhwcomposer: hwc_blank: Done blanking display: 0
03-16 11:19:23.615   279   279 I SFPerfTracer:      triggers: (rate: 15:290) (compose: 0:2) (post: 0:1) (render: 0:3) (21:1187 frames) (22:1298)
,03-16 11:19:23.615   279   279 D SFPerfTracer:        layers: (4:11) (FocusedStackFrame (0xb74c8348): 0:16)* (DimLayer (0xb74168a0): 0:9)* (StatusBar (0xb7494300): 0:191) (NavigationBar (0xb7497730): 0:44) (com.android.systemui.ImageWallpaper (0xb749d9d0): 0:5)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7491b78): 0:85)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb747f7b0): 0:30) (ColorFade (0xb7491198): 22:24) 
03-16 11:19:23.616   885  1258 D SurfaceControl: Excessive delay in setPowerMode(): 325ms
,03-16 11:19:23.621   885   885 I WindowManager: AOD feature not enabled!
,03-16 11:19:23.622   885  1136 I PowerManagerService: Sleeping (uid 1000)...
,03-16 11:19:23.636   885  1520 I LaunchCheckinHandler: cleanup(): cleared. Last call was 36740 ms ago
03-16 11:19:23.637  1474  3841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 11:19:23.655   885  1237 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
03-16 11:19:23.655   885  1237 E WifiStateMachine: handleScreenStateChanged Exit: true
,03-16 11:19:23.658   295   295 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-16 11:19:23.660   295   295 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-16 11:19:23.660   295   295 V msm8974_platform: platform_set_parameters: exit with code(0)
03-16 11:19:23.660   295   295 E msm8974_platform: platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
03-16 11:19:23.660   295   295 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
,03-16 11:19:23.662   295   295 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-16 11:19:23.675   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-16 11:19:23.675   885  1237 E native  : do suspend false
,03-16 11:19:23.896  1420  1420 I Keyboard.Facilitator: onFinishInput()
,03-16 11:19:23.899   885   885 D         : activate, handle: 1598182229, enabled: 0, index 0
03-16 11:19:23.899   885   885 E         : <BST> disable accel, orig state: 1
03-16 11:19:23.899   885   885 I         : <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,03-16 11:19:23.901   295  1246 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-16 11:19:23.901   295  1246 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-16 11:19:23.901   295  1246 V msm8974_platform: platform_set_parameters: exit with code(0)
03-16 11:19:23.901   295  1246 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
03-16 11:19:23.901   295  1246 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-16 11:19:23.907   885  1237 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
03-16 11:19:23.907   885  1237 E WifiStateMachine: handleScreenStateChanged Exit: false
03-16 11:19:23.909   885  1237 E WifiStateMachine: setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-16 11:19:23.910   885  1237 E WifiStateMachine: setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-16 11:19:23.910   885  1237 E native  : do suspend true
,03-16 11:19:25.397   303   388 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-16 11:19:25.954  1474  1474 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-16 11:19:26.098  1474  1474 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-16 11:19:28.647   885  1226 V AlarmManager: send {30a444df, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,03-16 11:19:28.653   885   885 V AlarmManager: done {30a444df, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,03-16 11:19:35.401   303   388 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-16 11:19:41.113   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310055, SEQNUM=4458, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-389, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:19:41.181  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:19:41.224  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:19:45.406   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:19:53.936   885  1226 V AlarmManager: send {2667752c, *walarm*:com.google.android.intent.action.SEND_IDLE}
,03-16 11:19:54.006   885   885 V AlarmManager: done {2667752c, *walarm*:com.google.android.intent.action.SEND_IDLE} [70ms]
,03-16 11:19:55.410   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:19:55.876  2548  3942 E global frequency: no tags to log
,03-16 11:19:55.880  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:19:55.896  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:19:55.901  1558  2328 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 11:19:55.992  1474  4116 I art     : Explicit concurrent mark sweep GC freed 55193(3MB) AllocSpace objects, 35(1214KB) LOS objects, 39% free, 7MB/12MB, paused 991us total 45.682ms
,03-16 11:19:56.025  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:19:56.038  2548  2548 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:19:56.046  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:19:56.047  1558  2328 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 11:19:56.106  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:19:56.120  2548  2548 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:19:56.130  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:19:56.133  1558  2328 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 11:19:56.214  1474  2594 I art     : Explicit concurrent mark sweep GC freed 4200(175KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 590us total 38.406ms
,03-16 11:19:56.250  2548  2548 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 11:19:56.261  2548  2548 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:19:56.265  2548  3942 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 11:19:56.266  2548  3942 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-16 11:19:56.267  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:19:56.268  2548  3942 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-16 11:19:56.269  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:19:56.270  2548  3942 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-16 11:19:56.272  2548  3942 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-16 11:19:56.283  2548  3942 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,03-16 11:19:56.284  2548  3942 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 11:19:57.522  1742  2384 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-16 11:20:00.200   885  1226 V AlarmManager: send {17422fed, *alarm*:android.intent.action.TIME_TICK}
,03-16 11:20:00.200   885  1226 V AlarmManager: send {1d6cb818, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,03-16 11:20:00.210   885   885 V AlarmManager: done {1d6cb818, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [10ms]
,03-16 11:20:00.246   885   885 V AlarmManager: done {17422fed, *alarm*:android.intent.action.TIME_TICK} [46ms]
,03-16 11:20:05.415   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:20:15.420   303   388 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 11:20:21.114   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310194, SEQNUM=4464, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-505, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:20:21.155  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:20:23.897  1420  1613 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-16 11:20:23.897  1420  1613 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-16 11:20:23.917  1742  1742 I ConfigService: onCreate
,03-16 11:20:25.424   303   388 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 11:20:28.121   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-16 11:20:28.121   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:28.121   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:28.121   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:28.121   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:28.121   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:28.121   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:20:28.121   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:20:28.121   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:28.121   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:28.121   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:28.121   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:28.121   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:28.121   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:20:28.969  1742  1742 I ConfigService: onDestroy
,03-16 11:20:32.122   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:20:32.122   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:32.122   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:32.122   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:32.122   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:32.123   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:32.123   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:20:32.123   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:20:32.123   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:32.123   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:32.123   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:32.123   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:32.123   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:32.123   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:20:35.429   303   388 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 11:20:38.131  4458  4637 I jxcore-log: Reconnected to the test server
03-16 11:20:38.131  4458  4637 I jxcore-log: 
,03-16 11:20:38.822  4458  4637 I jxcore-log: TAP version 13
03-16 11:20:38.822  4458  4637 I jxcore-log: 
,03-16 11:20:38.826  4458  4637 I jxcore-log: # setup
03-16 11:20:38.826  4458  4637 I jxcore-log: 
,03-16 11:20:38.828  4458  4637 I jxcore-log: # 1. calling createNativeListener directly rejects
03-16 11:20:38.828  4458  4637 I jxcore-log: 
,03-16 11:20:39.520  4458  4637 I jxcore-log: # teardown
03-16 11:20:39.520  4458  4637 I jxcore-log: 
,03-16 11:20:39.737  4458  4637 I jxcore-log: ok 1 Should throw
03-16 11:20:39.737  4458  4637 I jxcore-log: 
03-16 11:20:39.740  4458  4637 I jxcore-log: # setup
03-16 11:20:39.740  4458  4637 I jxcore-log: 
,03-16 11:20:39.939  4458  4637 I jxcore-log: # 2. emits incomingConnectionState
03-16 11:20:39.939  4458  4637 I jxcore-log: 
,03-16 11:20:40.337  4458  4637 I jxcore-log: # teardown
03-16 11:20:40.337  4458  4637 I jxcore-log: 
,03-16 11:20:40.459  4458  4637 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-16 11:20:40.459  4458  4637 I jxcore-log: 
,03-16 11:20:40.481  4458  4637 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-16 11:20:40.481  4458  4637 I jxcore-log: 
,03-16 11:20:40.492  4458  4637 I jxcore-log: # setup
03-16 11:20:40.492  4458  4637 I jxcore-log: 
,03-16 11:20:40.614  4458  4637 I jxcore-log: # 3. emits routerPortConnectionFailed
03-16 11:20:40.614  4458  4637 I jxcore-log: 
,03-16 11:20:40.743  4458  4637 I jxcore-log: # teardown
03-16 11:20:40.743  4458  4637 I jxcore-log: 
,03-16 11:20:40.896  4458  4637 I jxcore-log: ok 4 routerPortConnectionFailed is emitted
03-16 11:20:40.896  4458  4637 I jxcore-log: 
,03-16 11:20:40.907  4458  4637 I jxcore-log: # setup
03-16 11:20:40.907  4458  4637 I jxcore-log: 
,03-16 11:20:41.029  4458  4637 I jxcore-log: # 4. native server connections all up
03-16 11:20:41.029  4458  4637 I jxcore-log: 
,03-16 11:20:41.119  4458  4637 I jxcore-log: # teardown
03-16 11:20:41.119  4458  4637 I jxcore-log: 
,03-16 11:20:41.443  4458  4637 I jxcore-log: ok 5 Send/recvd #1 should be equal length
03-16 11:20:41.443  4458  4637 I jxcore-log: 
03-16 11:20:41.443  4458  4637 I jxcore-log: ok 6 Send/recvd #1 should be same
03-16 11:20:41.443  4458  4637 I jxcore-log: 
,03-16 11:20:41.448  4458  4637 I jxcore-log: ok 7 Send/recvd #2 should be equal length
03-16 11:20:41.448  4458  4637 I jxcore-log: 
03-16 11:20:41.448  4458  4637 I jxcore-log: ok 8 Send/recvd #2 should be same
03-16 11:20:41.448  4458  4637 I jxcore-log: 
03-16 11:20:41.449  4458  4637 I jxcore-log: ok 9 Should be exactly 2 client sockets
03-16 11:20:41.449  4458  4637 I jxcore-log: 
,03-16 11:20:41.459  4458  4637 I jxcore-log: # setup
03-16 11:20:41.459  4458  4637 I jxcore-log: 
,03-16 11:20:41.545  4458  4637 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-16 11:20:41.545  4458  4637 I jxcore-log: 
,03-16 11:20:41.643  4458  4637 I jxcore-log: # teardown
03-16 11:20:41.643  4458  4637 I jxcore-log: 
,03-16 11:20:41.815  4458  4637 I jxcore-log: ok 10 socket shouldn't close until after stream
03-16 11:20:41.815  4458  4637 I jxcore-log: 
03-16 11:20:41.819  4458  4637 I jxcore-log: ok 11 incoming remains open
03-16 11:20:41.819  4458  4637 I jxcore-log: 
,03-16 11:20:41.827  4458  4637 I jxcore-log: # setup
03-16 11:20:41.827  4458  4637 I jxcore-log: 
,03-16 11:20:41.955  4458  4637 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-16 11:20:41.955  4458  4637 I jxcore-log: 
,03-16 11:20:42.055  4458  4637 I jxcore-log: # teardown
03-16 11:20:42.055  4458  4637 I jxcore-log: 
,03-16 11:20:42.181  4458  4637 I jxcore-log: ok 12 we should not have gotten an error
03-16 11:20:42.181  4458  4637 I jxcore-log: 
,03-16 11:20:42.206  4458  4637 I jxcore-log: ok 13 socket shouldn't close until after incoming
03-16 11:20:42.206  4458  4637 I jxcore-log: 
03-16 11:20:42.209  4458  4637 I jxcore-log: ok 14 incoming is cleaned up
03-16 11:20:42.209  4458  4637 I jxcore-log: 
,03-16 11:20:42.217  4458  4637 I jxcore-log: # setup
03-16 11:20:42.217  4458  4637 I jxcore-log: 
,03-16 11:20:42.356  4458  4637 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-16 11:20:42.356  4458  4637 I jxcore-log: 
,03-16 11:20:42.432  4458  4637 I jxcore-log: # teardown
03-16 11:20:42.432  4458  4637 I jxcore-log: 
,03-16 11:20:42.564  4458  4637 I jxcore-log: ok 15 stream was closed
03-16 11:20:42.564  4458  4637 I jxcore-log: 
03-16 11:20:42.564  4458  4637 I jxcore-log: ok 16 incoming should survive
03-16 11:20:42.564  4458  4637 I jxcore-log: 
03-16 11:20:42.565  4458  4637 I jxcore-log: ok 17 mux should have no streams
03-16 11:20:42.565  4458  4637 I jxcore-log: 
,03-16 11:20:42.574  4458  4637 I jxcore-log: # setup
03-16 11:20:42.574  4458  4637 I jxcore-log: 
,03-16 11:20:42.686  4458  4637 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-16 11:20:42.686  4458  4637 I jxcore-log: 
,03-16 11:20:42.772  4458  4637 I jxcore-log: # teardown
03-16 11:20:42.772  4458  4637 I jxcore-log: 
,03-16 11:20:42.908  4458  4637 I jxcore-log: ok 18 we should not have gotten an error
03-16 11:20:42.908  4458  4637 I jxcore-log: 
,03-16 11:20:42.927  4458  4637 I jxcore-log: ok 19 Buffers are identical
03-16 11:20:42.927  4458  4637 I jxcore-log: 
03-16 11:20:42.933  4458  4637 I jxcore-log: ok 20 native server is nulled out
03-16 11:20:42.933  4458  4637 I jxcore-log: 
03-16 11:20:42.933  4458  4637 I jxcore-log: ok 21 native server should be closed
03-16 11:20:42.933  4458  4637 I jxcore-log: 
,03-16 11:20:42.936  4458  4637 I jxcore-log: ok 22 incoming has been removed
03-16 11:20:42.936  4458  4637 I jxcore-log: 
03-16 11:20:42.936  4458  4637 I jxcore-log: ok 23 Incoming should be done
03-16 11:20:42.936  4458  4637 I jxcore-log: 
,03-16 11:20:42.938  4458  4637 I jxcore-log: ok 24 The mux object should be closed
03-16 11:20:42.938  4458  4637 I jxcore-log: 
03-16 11:20:42.939  4458  4637 I jxcore-log: ok 25 The mux stream should be closed
03-16 11:20:42.939  4458  4637 I jxcore-log: 
,03-16 11:20:42.956  4458  4637 I jxcore-log: # setup
03-16 11:20:42.956  4458  4637 I jxcore-log: 
,03-16 11:20:43.079  4458  4637 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-16 11:20:43.079  4458  4637 I jxcore-log: 
,03-16 11:20:43.207  4458  4637 I jxcore-log: # teardown
03-16 11:20:43.207  4458  4637 I jxcore-log: 
,03-16 11:20:43.815  4458  4637 I jxcore-log: ok 26 native server is nulled out
03-16 11:20:43.815  4458  4637 I jxcore-log: 
,03-16 11:20:43.816  4458  4637 I jxcore-log: ok 27 native server should be closed
03-16 11:20:43.816  4458  4637 I jxcore-log: 
,03-16 11:20:43.816  4458  4637 I jxcore-log: ok 28 incoming has been removed
03-16 11:20:43.816  4458  4637 I jxcore-log: 
,03-16 11:20:43.954  4458  4637 I jxcore-log: # setup
03-16 11:20:43.954  4458  4637 I jxcore-log: 
,03-16 11:20:44.078  4458  4637 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-16 11:20:44.078  4458  4637 I jxcore-log: 
,03-16 11:20:44.127   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:20:44.127   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:44.127   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:44.127   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:44.127   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:44.127   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
,03-16 11:20:44.127   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:20:44.127   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:20:44.127   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:44.127   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:44.127   292   516 I MDMCTBK : checkDefaultInst, pid match
,03-16 11:20:44.127   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:44.127   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:44.128   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:20:44.723  4458  4637 I jxcore-log: # teardown,
03-16 11:20:44.723  4458  4637 I jxcore-log: 
,03-16 11:20:44.939  4458  4637 I jxcore-log: ok 29 we should not have gotten an error
03-16 11:20:44.939  4458  4637 I jxcore-log: 
,03-16 11:20:44.954  4458  4637 I jxcore-log: ok 30 Buffers are identical
03-16 11:20:44.954  4458  4637 I jxcore-log: 
,03-16 11:20:44.975  4458  4637 I jxcore-log: ok 31 server should be fine
03-16 11:20:44.975  4458  4637 I jxcore-log: 
03-16 11:20:44.975  4458  4637 I jxcore-log: ok 32 server should be open
03-16 11:20:44.975  4458  4637 I jxcore-log: 
03-16 11:20:44.976  4458  4637 I jxcore-log: ok 33 incoming has been removed
03-16 11:20:44.976  4458  4637 I jxcore-log: 
03-16 11:20:44.976  4458  4637 I jxcore-log: ok 34 The mux object should be closed
03-16 11:20:44.976  4458  4637 I jxcore-log: 
03-16 11:20:44.976  4458  4637 I jxcore-log: ok 35 The mux stream should be closed
03-16 11:20:44.976  4458  4637 I jxcore-log: 
,03-16 11:20:44.986  4458  4637 I jxcore-log: # setup
03-16 11:20:44.986  4458  4637 I jxcore-log: 
,03-16 11:20:45.281  4458  4637 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-16 11:20:45.281  4458  4637 I jxcore-log: 
,03-16 11:20:45.433   303   388 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 11:20:45.570  4458  4637 I jxcore-log: # teardown
03-16 11:20:45.570  4458  4637 I jxcore-log: 
,03-16 11:20:45.789  4458  4637 I jxcore-log: ok 36 we should not have gotten an error
03-16 11:20:45.789  4458  4637 I jxcore-log: 
,03-16 11:20:45.800  4458  4637 I jxcore-log: ok 37 Buffers are identical
03-16 11:20:45.800  4458  4637 I jxcore-log: 
,03-16 11:20:45.812  4458  4637 I jxcore-log: ok 38 server should be fine
03-16 11:20:45.812  4458  4637 I jxcore-log: 
03-16 11:20:45.813  4458  4637 I jxcore-log: ok 39 server should be open
03-16 11:20:45.813  4458  4637 I jxcore-log: 
,03-16 11:20:45.815  4458  4637 I jxcore-log: ok 40 incoming has been removed
03-16 11:20:45.815  4458  4637 I jxcore-log: 
03-16 11:20:45.816  4458  4637 I jxcore-log: ok 41 The mux object should be closed
03-16 11:20:45.816  4458  4637 I jxcore-log: 
,03-16 11:20:45.817  4458  4637 I jxcore-log: ok 42 The mux stream should be closed
03-16 11:20:45.817  4458  4637 I jxcore-log: 
,03-16 11:20:45.828  4458  4637 I jxcore-log: # setup
03-16 11:20:45.828  4458  4637 I jxcore-log: 
,03-16 11:20:45.931  4458  4637 I jxcore-log: # 12. closeAll can close even when connections open
03-16 11:20:45.931  4458  4637 I jxcore-log: 
,03-16 11:20:46.026  4458  4637 I jxcore-log: # teardown
03-16 11:20:46.026  4458  4637 I jxcore-log: 
,03-16 11:20:46.156  4458  4637 I jxcore-log: ok 43 not possible to connect to the server anymore
03-16 11:20:46.156  4458  4637 I jxcore-log: 
,03-16 11:20:46.166  4458  4637 I jxcore-log: # setup
03-16 11:20:46.166  4458  4637 I jxcore-log: 
,03-16 11:20:46.259  4458  4637 I jxcore-log: # 13. closeAll with promise
03-16 11:20:46.259  4458  4637 I jxcore-log: 
,03-16 11:20:46.385  4458  4637 I jxcore-log: # teardown
03-16 11:20:46.385  4458  4637 I jxcore-log: 
,03-16 11:20:46.552  4458  4637 I jxcore-log: ok 44 not possible to connect to the server anymore
03-16 11:20:46.552  4458  4637 I jxcore-log: 
,03-16 11:20:46.559  4458  4637 I jxcore-log: # setup
03-16 11:20:46.559  4458  4637 I jxcore-log: 
,03-16 11:20:46.688  4458  4637 I jxcore-log: # 14. multiplex can send data
03-16 11:20:46.688  4458  4637 I jxcore-log: 
,03-16 11:20:46.864  4458  4637 I jxcore-log: # teardown
03-16 11:20:46.864  4458  4637 I jxcore-log: 
,03-16 11:20:47.027  4458  4637 I jxcore-log: ok 45 String should be length:200
03-16 11:20:47.027  4458  4637 I jxcore-log: 
,03-16 11:20:47.041  4458  4637 I jxcore-log: # setup
03-16 11:20:47.041  4458  4637 I jxcore-log: 
,03-16 11:20:47.121  4458  4637 I jxcore-log: # 15. enqueue and run in order
03-16 11:20:47.121  4458  4637 I jxcore-log: 
,03-16 11:20:47.278  4458  4637 I jxcore-log: # teardown
03-16 11:20:47.278  4458  4637 I jxcore-log: 
,03-16 11:20:47.478  4458  4637 I jxcore-log: ok 46 firstPromise setTimeout
03-16 11:20:47.478  4458  4637 I jxcore-log: 
,03-16 11:20:47.479  4458  4637 I jxcore-log: ok 47 firstPromise result
03-16 11:20:47.479  4458  4637 I jxcore-log: 
03-16 11:20:47.480  4458  4637 I jxcore-log: ok 48 firstPromise testValue
03-16 11:20:47.480  4458  4637 I jxcore-log: 
,03-16 11:20:47.581  4458  4637 I jxcore-log: ok 49 secondPromise setTimeout
03-16 11:20:47.581  4458  4637 I jxcore-log: 
,03-16 11:20:47.583  4458  4637 I jxcore-log: ok 50 secondPromise result
03-16 11:20:47.583  4458  4637 I jxcore-log: 
,03-16 11:20:47.587  4458  4637 I jxcore-log: ok 51 secondPromise testValue
03-16 11:20:47.587  4458  4637 I jxcore-log: 
,03-16 11:20:47.592  4458  4637 I jxcore-log: ok 52 thirdPromise in promise
03-16 11:20:47.592  4458  4637 I jxcore-log: 
,03-16 11:20:47.595  4458  4637 I jxcore-log: ok 53 thirdPromise result
03-16 11:20:47.595  4458  4637 I jxcore-log: 
,03-16 11:20:47.596  4458  4637 I jxcore-log: ok 54 thirdPromise testValue
03-16 11:20:47.596  4458  4637 I jxcore-log: 
,03-16 11:20:47.606  4458  4637 I jxcore-log: # setup
03-16 11:20:47.606  4458  4637 I jxcore-log: 
,03-16 11:20:47.726  4458  4637 I jxcore-log: # 16. enqueueAtTop and run backwards
03-16 11:20:47.726  4458  4637 I jxcore-log: 
,03-16 11:20:48.129   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-16 11:20:48.129   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:48.129   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:48.129   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:48.129   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:48.129   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:48.129   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:20:48.130   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:20:48.130   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:20:48.130   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:20:48.130   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:20:48.130   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:20:48.130   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:20:48.130   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:20:48.407  4458  4637 I jxcore-log: # teardown
03-16 11:20:48.407  4458  4637 I jxcore-log: 
,03-16 11:20:48.553  4458  4637 I jxcore-log: ok 55 thirdPromise - first to run
03-16 11:20:48.553  4458  4637 I jxcore-log: 
03-16 11:20:48.555  4458  4637 I jxcore-log: ok 56 thirdPromise - in resolve
03-16 11:20:48.555  4458  4637 I jxcore-log: 
03-16 11:20:48.556  4458  4637 I jxcore-log: ok 57 secondPromise - second to run
03-16 11:20:48.556  4458  4637 I jxcore-log: 
03-16 11:20:48.557  4458  4637 I jxcore-log: ok 58 secondPromise - in catch
03-16 11:20:48.557  4458  4637 I jxcore-log: 
03-16 11:20:48.559  4458  4637 I jxcore-log: ok 59 firstPromise - third to run
03-16 11:20:48.559  4458  4637 I jxcore-log: 
03-16 11:20:48.560  4458  4637 I jxcore-log: ok 60 firstPromise - in then
03-16 11:20:48.560  4458  4637 I jxcore-log: 
03-16 11:20:48.561  4458  4637 I jxcore-log: ok 61 testing promises
03-16 11:20:48.561  4458  4637 I jxcore-log: 
,03-16 11:20:48.567  4458  4637 I jxcore-log: # setup
03-16 11:20:48.567  4458  4637 I jxcore-log: 
,03-16 11:20:49.327  4458  4637 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-16 11:20:49.327  4458  4637 I jxcore-log: 
,03-16 11:20:49.487  4458  4637 I jxcore-log: # teardown
03-16 11:20:49.487  4458  4637 I jxcore-log: 
,03-16 11:20:49.575  4458  4637 I jxcore-log: ok 62 fourth
03-16 11:20:49.575  4458  4637 I jxcore-log: 
,03-16 11:20:49.576  4458  4637 I jxcore-log: ok 63 fourth
03-16 11:20:49.576  4458  4637 I jxcore-log: 
03-16 11:20:49.577  4458  4637 I jxcore-log: ok 64 second
03-16 11:20:49.577  4458  4637 I jxcore-log: 
03-16 11:20:49.577  4458  4637 I jxcore-log: ok 65 secondPromise - in then
03-16 11:20:49.577  4458  4637 I jxcore-log: 
,03-16 11:20:49.680  4458  4637 I jxcore-log: ok 66 first
03-16 11:20:49.680  4458  4637 I jxcore-log: 
,03-16 11:20:49.682  4458  4637 I jxcore-log: ok 67 firstPromise - in catch
03-16 11:20:49.682  4458  4637 I jxcore-log: 
03-16 11:20:49.682  4458  4637 I jxcore-log: ok 68 third
03-16 11:20:49.682  4458  4637 I jxcore-log: 
,03-16 11:20:49.686  4458  4637 I jxcore-log: ok 69 thirdPromise - in then
03-16 11:20:49.686  4458  4637 I jxcore-log: 
,03-16 11:20:49.690  4458  4637 I jxcore-log: ok 70 testingPromises
03-16 11:20:49.690  4458  4637 I jxcore-log: 
,03-16 11:20:49.699  4458  4637 I jxcore-log: # setup
03-16 11:20:49.699  4458  4637 I jxcore-log: 
,03-16 11:20:49.885  4458  4637 I jxcore-log: # 18. queues handled independently
03-16 11:20:49.885  4458  4637 I jxcore-log: 
,03-16 11:20:50.172  4458  4637 I jxcore-log: # teardown
03-16 11:20:50.172  4458  4637 I jxcore-log: 
,03-16 11:20:50.289  4458  4637 I jxcore-log: ok 71 all short operations completed before the long resolves
03-16 11:20:50.289  4458  4637 I jxcore-log: 
,03-16 11:20:50.299  4458  4637 I jxcore-log: # setup
03-16 11:20:50.299  4458  4637 I jxcore-log: 
,03-16 11:20:50.376  4458  4637 I jxcore-log: # 19. basic
03-16 11:20:50.376  4458  4637 I jxcore-log: 
,03-16 11:20:50.503  4458  4637 I jxcore-log: # teardown
03-16 11:20:50.503  4458  4637 I jxcore-log: 
,03-16 11:20:50.597  4458  4637 I jxcore-log: ok 72 sane
03-16 11:20:50.597  4458  4637 I jxcore-log: 
,03-16 11:20:50.600  4458  4637 I jxcore-log: # setup
03-16 11:20:50.600  4458  4637 I jxcore-log: 
,03-16 11:20:50.712  4458  4637 I jxcore-log: # 20. another
03-16 11:20:50.712  4458  4637 I jxcore-log: 
,03-16 11:20:50.824  4458  4637 I jxcore-log: # teardown
03-16 11:20:50.824  4458  4637 I jxcore-log: 
,03-16 11:20:50.949  4458  4637 I jxcore-log: ok 73 sane
03-16 11:20:50.949  4458  4637 I jxcore-log: 
,03-16 11:20:50.952  4458  4637 I jxcore-log: # setup
03-16 11:20:50.952  4458  4637 I jxcore-log: 
,03-16 11:20:51.082  4458  4637 I jxcore-log: # 21. #startListeningForAdvertisements should fail if start not called
03-16 11:20:51.082  4458  4637 I jxcore-log: 
,03-16 11:20:51.173  4458  4637 I jxcore-log: # teardown
03-16 11:20:51.173  4458  4637 I jxcore-log: 
,03-16 11:20:51.311  4458  4637 I jxcore-log: ok 74 specific error should be returned
03-16 11:20:51.311  4458  4637 I jxcore-log: 
,03-16 11:20:51.317  4458  4637 I jxcore-log: # setup
03-16 11:20:51.317  4458  4637 I jxcore-log: 
,03-16 11:20:51.477  4458  4637 I jxcore-log: ok 75 error should be null
03-16 11:20:51.477  4458  4637 I jxcore-log: 
,03-16 11:20:51.478  4458  4637 I jxcore-log: ok 76 error should be null
03-16 11:20:51.478  4458  4637 I jxcore-log: 
03-16 11:20:51.480  4458  4637 I jxcore-log: # 22. #startUpdateAdvertisingAndListening should fail if start not called
03-16 11:20:51.480  4458  4637 I jxcore-log: 
,03-16 11:20:51.794  4458  4637 I jxcore-log: # teardown
03-16 11:20:51.794  4458  4637 I jxcore-log: 
,03-16 11:20:52.317  4458  4637 I jxcore-log: ok 77 specific error should be returned
03-16 11:20:52.317  4458  4637 I jxcore-log: 
,03-16 11:20:52.319  4458  4637 I jxcore-log: # setup
03-16 11:20:52.319  4458  4637 I jxcore-log: 
,03-16 11:20:52.536  4458  4637 I jxcore-log: ok 78 error should be null
03-16 11:20:52.536  4458  4637 I jxcore-log: 
,03-16 11:20:52.537  4458  4637 I jxcore-log: ok 79 error should be null
03-16 11:20:52.537  4458  4637 I jxcore-log: 
03-16 11:20:52.539  4458  4637 I jxcore-log: # 23. should be able to call #stopListeningForAdvertisements many times
03-16 11:20:52.539  4458  4637 I jxcore-log: 
,03-16 11:20:53.014  4458  4637 I jxcore-log: # teardown
03-16 11:20:53.014  4458  4637 I jxcore-log: 
,03-16 11:20:53.158  4458  4637 I jxcore-log: ok 80 error should be null
03-16 11:20:53.158  4458  4637 I jxcore-log: 
03-16 11:20:53.159  4458  4637 I jxcore-log: ok 81 error should be null
03-16 11:20:53.159  4458  4637 I jxcore-log: 
03-16 11:20:53.161  4458  4637 I jxcore-log: ok 82 error should be null
03-16 11:20:53.161  4458  4637 I jxcore-log: 
03-16 11:20:53.162  4458  4637 I jxcore-log: ok 83 error should be null
03-16 11:20:53.162  4458  4637 I jxcore-log: 
,03-16 11:20:53.168  4458  4637 I jxcore-log: # setup
03-16 11:20:53.168  4458  4637 I jxcore-log: 
,03-16 11:20:53.290  4458  4637 I jxcore-log: ok 84 error should be null
03-16 11:20:53.290  4458  4637 I jxcore-log: 
03-16 11:20:53.291  4458  4637 I jxcore-log: ok 85 error should be null
03-16 11:20:53.291  4458  4637 I jxcore-log: 
03-16 11:20:53.292  4458  4637 I jxcore-log: # 24. should be able to call #startListeningForAdvertisements many times
03-16 11:20:53.292  4458  4637 I jxcore-log: 
,03-16 11:20:53.456  4458  4637 I jxcore-log: # teardown
03-16 11:20:53.456  4458  4637 I jxcore-log: 
,03-16 11:20:53.571  4458  4637 I jxcore-log: ok 86 error should be null
03-16 11:20:53.571  4458  4637 I jxcore-log: 
,03-16 11:20:53.575  4458  4637 I jxcore-log: ok 87 error should be null
03-16 11:20:53.575  4458  4637 I jxcore-log: 
,03-16 11:20:53.579  4458  4637 I jxcore-log: ok 88 error should be null
03-16 11:20:53.579  4458  4637 I jxcore-log: 
03-16 11:20:53.580  4458  4637 I jxcore-log: ok 89 error should be null
03-16 11:20:53.580  4458  4637 I jxcore-log: 
03-16 11:20:53.582  4458  4637 I jxcore-log: # setup
03-16 11:20:53.582  4458  4637 I jxcore-log: 
,03-16 11:20:53.793  4458  4637 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-16 11:20:53.793  4458  4637 I jxcore-log: 
,03-16 11:20:53.800  4458  4637 I jxcore-log: ok 90 error should be null
03-16 11:20:53.800  4458  4637 I jxcore-log: 
03-16 11:20:53.801  4458  4637 I jxcore-log: ok 91 error should be null
03-16 11:20:53.801  4458  4637 I jxcore-log: 
03-16 11:20:53.803  4458  4637 I jxcore-log: # 25. should be able to call #startUpdateAdvertisingAndListening many times
03-16 11:20:53.803  4458  4637 I jxcore-log: 
,03-16 11:20:53.959  4458  4637 I jxcore-log: # teardown
03-16 11:20:53.959  4458  4637 I jxcore-log: 
,03-16 11:20:54.132  4458  4637 I jxcore-log: ok 92 error should be null
03-16 11:20:54.132  4458  4637 I jxcore-log: 
03-16 11:20:54.133  4458  4637 I jxcore-log: ok 93 error should be null
03-16 11:20:54.133  4458  4637 I jxcore-log: 
,03-16 11:20:54.151  4458  4637 I jxcore-log: ok 94 error should be null
03-16 11:20:54.151  4458  4637 I jxcore-log: 
,03-16 11:20:54.154  4458  4637 I jxcore-log: ok 95 error should be null
03-16 11:20:54.154  4458  4637 I jxcore-log: 
,03-16 11:20:54.163  4458  4637 I jxcore-log: # setup
03-16 11:20:54.163  4458  4637 I jxcore-log: 
,03-16 11:20:54.282  4458  4637 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-16 11:20:54.282  4458  4637 I jxcore-log: 
,03-16 11:20:54.287  4458  4637 I jxcore-log: ok 96 error should be null
03-16 11:20:54.287  4458  4637 I jxcore-log: 
03-16 11:20:54.288  4458  4637 I jxcore-log: ok 97 error should be null
03-16 11:20:54.288  4458  4637 I jxcore-log: 
,03-16 11:20:54.295  4458  4637 I jxcore-log: # 26. should be able to call #stopAdvertisingAndListening many times
03-16 11:20:54.295  4458  4637 I jxcore-log: 
,03-16 11:20:54.477  4458  4637 I jxcore-log: # teardown
03-16 11:20:54.477  4458  4637 I jxcore-log: 
,03-16 11:20:54.866  4458  4637 I jxcore-log: ok 98 error should be null
03-16 11:20:54.866  4458  4637 I jxcore-log: 
,03-16 11:20:54.867  4458  4637 I jxcore-log: ok 99 error should be null
03-16 11:20:54.867  4458  4637 I jxcore-log: 
03-16 11:20:54.870  4458  4637 I jxcore-log: ok 100 error should be null
03-16 11:20:54.870  4458  4637 I jxcore-log: 
03-16 11:20:54.871  4458  4637 I jxcore-log: ok 101 error should be null
03-16 11:20:54.871  4458  4637 I jxcore-log: 
03-16 11:20:54.873  4458  4637 I jxcore-log: # setup
03-16 11:20:54.873  4458  4637 I jxcore-log: 
,03-16 11:20:55.042  4458  4637 I jxcore-log: ok 102 error should be null
03-16 11:20:55.042  4458  4637 I jxcore-log: 
,03-16 11:20:55.046  4458  4637 I jxcore-log: ok 103 error should be null
03-16 11:20:55.046  4458  4637 I jxcore-log: 
,03-16 11:20:55.051  4458  4637 I jxcore-log: # 27. #start should fail if called twice in a row
03-16 11:20:55.051  4458  4637 I jxcore-log: 
,03-16 11:20:55.245  4458  4637 I jxcore-log: # teardown
03-16 11:20:55.245  4458  4637 I jxcore-log: 
,03-16 11:20:55.406  4458  4637 I jxcore-log: ok 104 first call should succeed
03-16 11:20:55.406  4458  4637 I jxcore-log: 
,03-16 11:20:55.407  4458  4637 I jxcore-log: ok 105 first call should succeed
03-16 11:20:55.407  4458  4637 I jxcore-log: 
03-16 11:20:55.410  4458  4637 I jxcore-log: ok 106 specific error should be returned
03-16 11:20:55.410  4458  4637 I jxcore-log: 
03-16 11:20:55.413  4458  4637 I jxcore-log: # setup
03-16 11:20:55.413  4458  4637 I jxcore-log: 
,03-16 11:20:55.438   303   388 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 11:20:55.617  4458  4637 I jxcore-log: ok 107 error should be null
03-16 11:20:55.617  4458  4637 I jxcore-log: 
,03-16 11:20:55.618  4458  4637 I jxcore-log: ok 108 error should be null
03-16 11:20:55.618  4458  4637 I jxcore-log: 
03-16 11:20:55.620  4458  4637 I jxcore-log: # 28. does not emit duplicate discoveryAdvertisingStateUpdate
03-16 11:20:55.620  4458  4637 I jxcore-log: 
,03-16 11:20:55.910  4458  4637 I jxcore-log: # teardown
03-16 11:20:55.910  4458  4637 I jxcore-log: 
,03-16 11:20:56.430  4458  4637 I jxcore-log: ok 109 called only once
03-16 11:20:56.430  4458  4637 I jxcore-log: 
03-16 11:20:56.431  4458  4637 I jxcore-log: ok 110 discovery state matches
03-16 11:20:56.431  4458  4637 I jxcore-log: 
03-16 11:20:56.431  4458  4637 I jxcore-log: ok 111 advertising state matches
03-16 11:20:56.431  4458  4637 I jxcore-log: 
03-16 11:20:56.433  4458  4637 I jxcore-log: # setup
03-16 11:20:56.433  4458  4637 I jxcore-log: 
,03-16 11:20:56.551  4458  4637 I jxcore-log: INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-16 11:20:56.551  4458  4637 I jxcore-log: 
,03-16 11:20:56.552  4458  4637 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-16 11:20:56.552  4458  4637 I jxcore-log: 
,03-16 11:20:56.566  4458  4637 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-16 11:20:56.566  4458  4637 I jxcore-log: 
,03-16 11:20:56.569  4458  4637 I jxcore-log: ok 112 error should be null
03-16 11:20:56.569  4458  4637 I jxcore-log: 
03-16 11:20:56.570  4458  4637 I jxcore-log: ok 113 error should be null
03-16 11:20:56.570  4458  4637 I jxcore-log: 
,03-16 11:20:56.576  4458  4637 I jxcore-log: # 29. does not send duplicate availability changes
03-16 11:20:56.576  4458  4637 I jxcore-log: 
,03-16 11:20:57.010  4458  4637 I jxcore-log: # teardown
03-16 11:20:57.010  4458  4637 I jxcore-log: 
,03-16 11:20:57.151  4458  4637 I jxcore-log: ok 114 should be called once
03-16 11:20:57.151  4458  4637 I jxcore-log: 
,03-16 11:20:57.153  4458  4637 I jxcore-log: ok 115 should not have been called more than once
03-16 11:20:57.153  4458  4637 I jxcore-log: 
,03-16 11:20:57.160  4458  4637 I jxcore-log: # setup
03-16 11:20:57.160  4458  4637 I jxcore-log: 
,03-16 11:20:57.378  4458  4637 I jxcore-log: ok 116 error should be null
03-16 11:20:57.378  4458  4637 I jxcore-log: 
,03-16 11:20:57.379  4458  4637 I jxcore-log: ok 117 error should be null
03-16 11:20:57.379  4458  4637 I jxcore-log: 
03-16 11:20:57.381  4458  4637 I jxcore-log: # 30. can get the network status
03-16 11:20:57.381  4458  4637 I jxcore-log: 
,03-16 11:20:57.497  4458  4637 I jxcore-log: # teardown
03-16 11:20:57.497  4458  4637 I jxcore-log: 
,03-16 11:20:57.614  4458  4637 I jxcore-log: ok 118 network status should have certain non-empty properties
03-16 11:20:57.614  4458  4637 I jxcore-log: 
,03-16 11:20:57.616  4458  4637 I jxcore-log: # setup
03-16 11:20:57.616  4458  4637 I jxcore-log: 
,03-16 11:20:57.777  4458  4637 I jxcore-log: ok 119 error should be null
03-16 11:20:57.777  4458  4637 I jxcore-log: 
,03-16 11:20:57.778  4458  4637 I jxcore-log: ok 120 error should be null
03-16 11:20:57.778  4458  4637 I jxcore-log: 
03-16 11:20:57.780  4458  4637 I jxcore-log: # 31. wifi peer is marked unavailable if announcements stop
03-16 11:20:57.780  4458  4637 I jxcore-log: 
,03-16 11:20:57.924  4458  4637 I jxcore-log: # teardown
03-16 11:20:57.924  4458  4637 I jxcore-log: 
,03-16 11:20:58.083  4458  4637 I jxcore-log: ok 121 host address should match
03-16 11:20:58.083  4458  4637 I jxcore-log: 
,03-16 11:20:58.085  4458  4637 I jxcore-log: ok 122 port should match
03-16 11:20:58.085  4458  4637 I jxcore-log: 
,03-16 11:20:59.055  4458  4637 I jxcore-log: ok 123 host address should be null
03-16 11:20:59.055  4458  4637 I jxcore-log: 
,03-16 11:20:59.056  4458  4637 I jxcore-log: ok 124 port should should be null
03-16 11:20:59.056  4458  4637 I jxcore-log: 
,03-16 11:20:59.070  4458  4637 I jxcore-log: # setup
03-16 11:20:59.070  4458  4637 I jxcore-log: 
,03-16 11:20:59.246  4458  4637 I jxcore-log: INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-16 11:20:59.246  4458  4637 I jxcore-log: 
03-16 11:20:59.248  4458  4637 I jxcore-log: ok 125 error should be null
03-16 11:20:59.248  4458  4637 I jxcore-log: 
03-16 11:20:59.248  4458  4637 I jxcore-log: ok 126 error should be null
03-16 11:20:59.248  4458  4637 I jxcore-log: 
03-16 11:20:59.250  4458  4637 I jxcore-log: # 32. can get the network status before starting
03-16 11:20:59.250  4458  4637 I jxcore-log: 
,03-16 11:20:59.359  4458  4637 I jxcore-log: # teardown
03-16 11:20:59.359  4458  4637 I jxcore-log: 
,03-16 11:20:59.487  4458  4637 I jxcore-log: ok 127 network status should have certain non-empty properties
03-16 11:20:59.487  4458  4637 I jxcore-log: 
,03-16 11:20:59.489  4458  4637 I jxcore-log: # setup
03-16 11:20:59.489  4458  4637 I jxcore-log: 
,03-16 11:20:59.775  4458  4637 I jxcore-log: # 33. #generatePreambleAndBeacons bad args
03-16 11:20:59.775  4458  4637 I jxcore-log: 
,03-16 11:20:59.902  4458  4637 I jxcore-log: # teardown
03-16 11:20:59.902  4458  4637 I jxcore-log: 
,03-16 11:21:00.081  4458  4637 I jxcore-log: ok 128 publicKeysToNotify cannot be null
03-16 11:21:00.081  4458  4637 I jxcore-log: 
03-16 11:21:00.083  4458  4637 I jxcore-log: ok 129 ecdh for local device cannot be null
03-16 11:21:00.083  4458  4637 I jxcore-log: 
,03-16 11:21:00.088  4458  4637 I jxcore-log: ok 130 milliseconds cannot be less than 0
03-16 11:21:00.088  4458  4637 I jxcore-log: 
03-16 11:21:00.089  4458  4637 I jxcore-log: ok 131 milliseconds cannot be 0
03-16 11:21:00.089  4458  4637 I jxcore-log: 
03-16 11:21:00.091  4458  4637 I jxcore-log: ok 132 milliseconds cannot be greater than one_day
03-16 11:21:00.091  4458  4637 I jxcore-log: 
03-16 11:21:00.093  4458  4637 I jxcore-log: # setup
03-16 11:21:00.093  4458  4637 I jxcore-log: 
,03-16 11:21:00.256  4458  4637 I jxcore-log: # 34. #generatePreambleAndBeacons empty keys to notify
03-16 11:21:00.256  4458  4637 I jxcore-log: 
,03-16 11:21:00.360  4458  4637 I jxcore-log: # teardown
03-16 11:21:00.360  4458  4637 I jxcore-log: 
,03-16 11:21:00.549  4458  4637 I jxcore-log: ok 133 should be equal
03-16 11:21:00.549  4458  4637 I jxcore-log: 
03-16 11:21:00.551  4458  4637 I jxcore-log: # setup
03-16 11:21:00.551  4458  4637 I jxcore-log: 
,03-16 11:21:00.677  4458  4637 I jxcore-log: # 35. #generatePreambleAndBeacons multiple keys to notify
03-16 11:21:00.677  4458  4637 I jxcore-log: 
,03-16 11:21:00.754  4458  4637 I jxcore-log: # teardown
03-16 11:21:00.754  4458  4637 I jxcore-log: 
,03-16 11:21:01.039  4458  4637 I jxcore-log: ok 134 should be equal
03-16 11:21:01.039  4458  4637 I jxcore-log: 
,03-16 11:21:01.039  4458  4637 I jxcore-log: ok 135 should be equal
03-16 11:21:01.039  4458  4637 I jxcore-log: 
,03-16 11:21:01.040  4458  4637 I jxcore-log: ok 136 (unnamed assert)
03-16 11:21:01.040  4458  4637 I jxcore-log: 
03-16 11:21:01.040  4458  4637 I jxcore-log: ok 137 should be equal
03-16 11:21:01.040  4458  4637 I jxcore-log: 
03-16 11:21:01.042  4458  4637 I jxcore-log: # setup
03-16 11:21:01.042  4458  4637 I jxcore-log: 
,03-16 11:21:01.105  4458  4637 I jxcore-log: # 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-16 11:21:01.105  4458  4637 I jxcore-log: 
,03-16 11:21:01.183  4458  4637 I jxcore-log: # teardown
03-16 11:21:01.183  4458  4637 I jxcore-log: 
,03-16 11:21:01.322  4458  4637 I jxcore-log: ok 138 should throw
03-16 11:21:01.322  4458  4637 I jxcore-log: 
,03-16 11:21:01.325  4458  4637 I jxcore-log: # setup
03-16 11:21:01.325  4458  4637 I jxcore-log: 
,03-16 11:21:01.411  4458  4637 I jxcore-log: # 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-16 11:21:01.411  4458  4637 I jxcore-log: 
,03-16 11:21:01.542  4458  4637 I jxcore-log: # teardown
03-16 11:21:01.542  4458  4637 I jxcore-log: 
,03-16 11:21:01.759  4458  4637 I jxcore-log: ok 139 Preamble expiration must be a 64 bit integer
03-16 11:21:01.759  4458  4637 I jxcore-log: 
03-16 11:21:01.761  4458  4637 I jxcore-log: # setup
03-16 11:21:01.761  4458  4637 I jxcore-log: 
,03-16 11:21:01.856  4458  4637 I jxcore-log: # 38. #parseBeacons expiration out of range lower
03-16 11:21:01.856  4458  4637 I jxcore-log: 
,03-16 11:21:01.999  4458  4637 I jxcore-log: # teardown
03-16 11:21:01.999  4458  4637 I jxcore-log: 
,03-16 11:21:02.094  4458  4637 I jxcore-log: ok 140 Expiration out of range
03-16 11:21:02.094  4458  4637 I jxcore-log: 
03-16 11:21:02.096  4458  4637 I jxcore-log: # setup
03-16 11:21:02.096  4458  4637 I jxcore-log: 
,03-16 11:21:02.173  4458  4637 I jxcore-log: # 39. #parseBeacons expiration out of range lower
03-16 11:21:02.173  4458  4637 I jxcore-log: 
,03-16 11:21:02.272  4458  4637 I jxcore-log: # teardown
03-16 11:21:02.272  4458  4637 I jxcore-log: 
,03-16 11:21:02.395  4458  4637 I jxcore-log: ok 141 Expiration out of range
03-16 11:21:02.395  4458  4637 I jxcore-log: 
03-16 11:21:02.397  4458  4637 I jxcore-log: # setup
03-16 11:21:02.397  4458  4637 I jxcore-log: 
,03-16 11:21:02.480  4458  4637 I jxcore-log: # 40. #parseBeacons no beacons returns null
03-16 11:21:02.480  4458  4637 I jxcore-log: 
,03-16 11:21:02.597  4458  4637 I jxcore-log: # teardown
03-16 11:21:02.597  4458  4637 I jxcore-log: 
,03-16 11:21:02.755  4458  4637 I jxcore-log: ok 142 should be equal
03-16 11:21:02.755  4458  4637 I jxcore-log: 
03-16 11:21:02.758  4458  4637 I jxcore-log: # setup
03-16 11:21:02.758  4458  4637 I jxcore-log: 
,03-16 11:21:02.899  4458  4637 I jxcore-log: # 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-16 11:21:02.899  4458  4637 I jxcore-log: 
,03-16 11:21:03.020  4458  4637 I jxcore-log: # teardown
03-16 11:21:03.020  4458  4637 I jxcore-log: 
,03-16 11:21:03.133  4458  4637 I jxcore-log: ok 143 Malformed encrypted beacon key ID
03-16 11:21:03.133  4458  4637 I jxcore-log: 
,03-16 11:21:03.138  4458  4637 I jxcore-log: # setup
03-16 11:21:03.138  4458  4637 I jxcore-log: 
,03-16 11:21:03.244  4458  4637 I jxcore-log: # 42. #parseBeacons addressBookCallback fails decrypt
03-16 11:21:03.244  4458  4637 I jxcore-log: 
,03-16 11:21:03.380  4458  4637 I jxcore-log: # teardown
03-16 11:21:03.380  4458  4637 I jxcore-log: 
,03-16 11:21:03.700  4458  4637 I jxcore-log: ok 144 should be equal
03-16 11:21:03.700  4458  4637 I jxcore-log: 
,03-16 11:21:03.702  4458  4637 I jxcore-log: # setup
03-16 11:21:03.702  4458  4637 I jxcore-log: 
,03-16 11:21:03.815  4458  4637 I jxcore-log: # 43. #parseBeacons addressBookCallback returns no matches
03-16 11:21:03.815  4458  4637 I jxcore-log: 
,03-16 11:21:03.999  4458  4637 I jxcore-log: # teardown
03-16 11:21:03.999  4458  4637 I jxcore-log: 
,03-16 11:21:04.327  4458  4637 I jxcore-log: ok 145 should be equal
03-16 11:21:04.327  4458  4637 I jxcore-log: 
,03-16 11:21:04.327  4458  4637 I jxcore-log: ok 146 should be equal
03-16 11:21:04.327  4458  4637 I jxcore-log: 
,03-16 11:21:04.329  4458  4637 I jxcore-log: # setup
03-16 11:21:04.329  4458  4637 I jxcore-log: 
,03-16 11:21:04.481  4458  4637 I jxcore-log: # 44. #parseBeacons addressBookCallback returns spurious match
03-16 11:21:04.481  4458  4637 I jxcore-log: 
,03-16 11:21:04.603  4458  4637 I jxcore-log: # teardown
03-16 11:21:04.603  4458  4637 I jxcore-log: 
,03-16 11:21:04.961  4458  4637 I jxcore-log: ok 147 should be equal
03-16 11:21:04.961  4458  4637 I jxcore-log: 
,03-16 11:21:04.961  4458  4637 I jxcore-log: ok 148 should be equal
03-16 11:21:04.961  4458  4637 I jxcore-log: 
,03-16 11:21:04.963  4458  4637 I jxcore-log: # setup
03-16 11:21:04.963  4458  4637 I jxcore-log: 
,03-16 11:21:05.075  4458  4637 I jxcore-log: # 45. #parseBeacons addressBookCallback returns public key
03-16 11:21:05.075  4458  4637 I jxcore-log: 
,03-16 11:21:05.220  4458  4637 I jxcore-log: # teardown
03-16 11:21:05.220  4458  4637 I jxcore-log: 
,03-16 11:21:05.443   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:21:05.538  4458  4637 I jxcore-log: ok 149 should be equal
03-16 11:21:05.538  4458  4637 I jxcore-log: 
,03-16 11:21:05.538  4458  4637 I jxcore-log: ok 150 (unnamed assert)
03-16 11:21:05.538  4458  4637 I jxcore-log: 
,03-16 11:21:05.540  4458  4637 I jxcore-log: # setup
03-16 11:21:05.540  4458  4637 I jxcore-log: 
,03-16 11:21:05.612  4458  4637 I jxcore-log: # 46. #parseBeacons with beacons both for and not for the user
03-16 11:21:05.612  4458  4637 I jxcore-log: 
,03-16 11:21:05.703  4458  4637 I jxcore-log: # teardown
03-16 11:21:05.703  4458  4637 I jxcore-log: 
,03-16 11:21:06.003  4458  4637 I jxcore-log: ok 151 should be equal
03-16 11:21:06.003  4458  4637 I jxcore-log: 
,03-16 11:21:06.004  4458  4637 I jxcore-log: ok 152 (unnamed assert)
03-16 11:21:06.004  4458  4637 I jxcore-log: 
,03-16 11:21:06.006  4458  4637 I jxcore-log: # setup
03-16 11:21:06.006  4458  4637 I jxcore-log: 
,03-16 11:21:06.056  4458  4637 I jxcore-log: # 47. Start and stop ThaliNotificationServer
03-16 11:21:06.056  4458  4637 I jxcore-log: 
,03-16 11:21:06.209  4458  4637 I jxcore-log: # teardown
03-16 11:21:06.209  4458  4637 I jxcore-log: 
,03-16 11:21:06.448  4458  4637 I jxcore-log: ok 153 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-16 11:21:06.448  4458  4637 I jxcore-log: 
03-16 11:21:06.448  4458  4637 I jxcore-log: ok 154 ThaliMobile.StopAdvertisingAndListening should be called once
03-16 11:21:06.448  4458  4637 I jxcore-log: 
03-16 11:21:06.450  4458  4637 I jxcore-log: # setup
03-16 11:21:06.450  4458  4637 I jxcore-log: 
,03-16 11:21:06.568  4458  4637 I jxcore-log: # 48. Pass an empty array to ThaliNotificationServer.start
03-16 11:21:06.568  4458  4637 I jxcore-log: 
,03-16 11:21:06.759  4458  4637 I jxcore-log: # teardown
03-16 11:21:06.759  4458  4637 I jxcore-log: 
,03-16 11:21:06.880  4458  4637 I jxcore-log: ok 155 StartUpdateAdvertisingAndListening should not be called
03-16 11:21:06.880  4458  4637 I jxcore-log: 
,03-16 11:21:06.907  4458  4637 I jxcore-log: ok 156 ThaliMobile.StopAdvertisingAndListening should be called once
03-16 11:21:06.907  4458  4637 I jxcore-log: 
,03-16 11:21:06.965  4458  4637 I jxcore-log: ok 157 no error
03-16 11:21:06.965  4458  4637 I jxcore-log: 
03-16 11:21:06.965  4458  4637 I jxcore-log: ok 158 should be 204
03-16 11:21:06.965  4458  4637 I jxcore-log: 
,03-16 11:21:06.972  4458  4637 I jxcore-log: # setup
03-16 11:21:06.972  4458  4637 I jxcore-log: 
,03-16 11:21:07.305  4458  4637 I jxcore-log: # 49. Pass a string to ThaliNotificationServer.start
03-16 11:21:07.305  4458  4637 I jxcore-log: 
,03-16 11:21:07.540  4458  4637 I jxcore-log: # teardown
03-16 11:21:07.540  4458  4637 I jxcore-log: 
,03-16 11:21:08.069  4458  4637 I jxcore-log: ok 159 StartUpdateAdvertisingAndListening should not be called
03-16 11:21:08.069  4458  4637 I jxcore-log: 
,03-16 11:21:08.072  4458  4637 I jxcore-log: # setup
03-16 11:21:08.072  4458  4637 I jxcore-log: 
,03-16 11:21:08.204  4458  4637 I jxcore-log: # 50. Pass an empty parameter to ThaliNotificationServer.start
03-16 11:21:08.204  4458  4637 I jxcore-log: 
,03-16 11:21:08.381  4458  4637 I jxcore-log: # teardown
03-16 11:21:08.381  4458  4637 I jxcore-log: 
,03-16 11:21:08.548  4458  4637 I jxcore-log: ok 160 StartUpdateAdvertisingAndListening should not be called
03-16 11:21:08.548  4458  4637 I jxcore-log: 
,03-16 11:21:08.551  4458  4637 I jxcore-log: # setup
03-16 11:21:08.551  4458  4637 I jxcore-log: 
,03-16 11:21:08.662  4458  4637 I jxcore-log: # 51. Make an HTTP request to /NotificationBeacons
03-16 11:21:08.662  4458  4637 I jxcore-log: 
,03-16 11:21:08.813  4458  4637 I jxcore-log: # teardown
03-16 11:21:08.813  4458  4637 I jxcore-log: 
,03-16 11:21:09.035  4458  4637 I jxcore-log: ok 161 no error
03-16 11:21:09.035  4458  4637 I jxcore-log: 
03-16 11:21:09.035  4458  4637 I jxcore-log: ok 162 should be 200
03-16 11:21:09.035  4458  4637 I jxcore-log: 
03-16 11:21:09.036  4458  4637 I jxcore-log: ok 163 should be equal
03-16 11:21:09.036  4458  4637 I jxcore-log: 
03-16 11:21:09.036  4458  4637 I jxcore-log: ok 164 should be equal
03-16 11:21:09.036  4458  4637 I jxcore-log: 
,03-16 11:21:09.075  4458  4637 I jxcore-log: ok 165 (unnamed assert)
03-16 11:21:09.075  4458  4637 I jxcore-log: 
,03-16 11:21:09.102  4458  4637 I jxcore-log: ok 166 no error
03-16 11:21:09.102  4458  4637 I jxcore-log: 
03-16 11:21:09.103  4458  4637 I jxcore-log: ok 167 should be 204
03-16 11:21:09.103  4458  4637 I jxcore-log: 
,03-16 11:21:09.108  4458  4637 I jxcore-log: # setup
03-16 11:21:09.108  4458  4637 I jxcore-log: 
,03-16 11:21:09.187  4458  4637 I jxcore-log: # 52. Make an HTTP request to /NotificationBeacons (no keys)
03-16 11:21:09.187  4458  4637 I jxcore-log: 
,03-16 11:21:09.320  4458  4637 I jxcore-log: # teardown
03-16 11:21:09.320  4458  4637 I jxcore-log: 
,03-16 11:21:09.425  4458  4637 I jxcore-log: ok 168 error should be null
03-16 11:21:09.425  4458  4637 I jxcore-log: 
03-16 11:21:09.426  4458  4637 I jxcore-log: ok 169 should be 204
03-16 11:21:09.426  4458  4637 I jxcore-log: 
,03-16 11:21:09.433  4458  4637 I jxcore-log: # setup
03-16 11:21:09.433  4458  4637 I jxcore-log: 
,03-16 11:21:09.484  4458  4637 I jxcore-log: # 53. Make an HTTP request to /NotificationBeacons before calling start
03-16 11:21:09.484  4458  4637 I jxcore-log: 
,03-16 11:21:09.645  4458  4637 I jxcore-log: # teardown
03-16 11:21:09.645  4458  4637 I jxcore-log: 
,03-16 11:21:09.786  4458  4637 I jxcore-log: ok 170 should be 404
03-16 11:21:09.786  4458  4637 I jxcore-log: 
,03-16 11:21:09.793  4458  4637 I jxcore-log: # setup
03-16 11:21:09.793  4458  4637 I jxcore-log: 
,03-16 11:21:09.889  4458  4637 I jxcore-log: # 54. #testThaliPeerAction - test getters
03-16 11:21:09.889  4458  4637 I jxcore-log: 
,03-16 11:21:09.966  4458  4637 I jxcore-log: # teardown
03-16 11:21:09.966  4458  4637 I jxcore-log: 
,03-16 11:21:10.073  4458  4637 I jxcore-log: ok 171 getPeerIdentifier
03-16 11:21:10.073  4458  4637 I jxcore-log: 
,03-16 11:21:10.076  4458  4637 I jxcore-log: ok 172 getConnectionType
03-16 11:21:10.076  4458  4637 I jxcore-log: 
,03-16 11:21:10.079  4458  4637 I jxcore-log: ok 173 getActionType
03-16 11:21:10.079  4458  4637 I jxcore-log: 
,03-16 11:21:10.082  4458  4637 I jxcore-log: ok 174 getActionState
03-16 11:21:10.082  4458  4637 I jxcore-log: 
,03-16 11:21:10.087  4458  4637 I jxcore-log: # setup
03-16 11:21:10.087  4458  4637 I jxcore-log: 
,03-16 11:21:10.394  4458  4637 I jxcore-log: # 55. #testThaliPeerAction - start and kill
03-16 11:21:10.394  4458  4637 I jxcore-log: 
,03-16 11:21:10.472  4458  4637 I jxcore-log: # teardown
03-16 11:21:10.472  4458  4637 I jxcore-log: 
,03-16 11:21:10.661  4458  4637 I jxcore-log: ok 175 initial state
03-16 11:21:10.661  4458  4637 I jxcore-log: 
,03-16 11:21:10.666  4458  4637 I jxcore-log: ok 176 after start
03-16 11:21:10.666  4458  4637 I jxcore-log: 
,03-16 11:21:10.670  4458  4637 I jxcore-log: ok 177 after kill
03-16 11:21:10.670  4458  4637 I jxcore-log: 
,03-16 11:21:10.672  4458  4637 I jxcore-log: # setup
03-16 11:21:10.672  4458  4637 I jxcore-log: 
,03-16 11:21:10.804  4458  4637 I jxcore-log: # 56. #testThaliPeerAction - double start
03-16 11:21:10.804  4458  4637 I jxcore-log: 
,03-16 11:21:10.953  4458  4637 I jxcore-log: # teardown
03-16 11:21:10.953  4458  4637 I jxcore-log: 
,03-16 11:21:11.078  4458  4637 I jxcore-log: ok 178 should be equal
03-16 11:21:11.078  4458  4637 I jxcore-log: 
,03-16 11:21:11.081  4458  4637 I jxcore-log: # setup
03-16 11:21:11.081  4458  4637 I jxcore-log: 
,03-16 11:21:11.189  4458  4637 I jxcore-log: # 57. #testThaliPeerAction - start after kill
03-16 11:21:11.189  4458  4637 I jxcore-log: 
,03-16 11:21:11.329  4458  4637 I jxcore-log: # teardown
03-16 11:21:11.329  4458  4637 I jxcore-log: 
,03-16 11:21:11.484  4458  4637 I jxcore-log: ok 179 clean kill
03-16 11:21:11.484  4458  4637 I jxcore-log: 
,03-16 11:21:11.487  4458  4637 I jxcore-log: ok 180 should be equal
03-16 11:21:11.487  4458  4637 I jxcore-log: 
03-16 11:21:11.489  4458  4637 I jxcore-log: # setup
03-16 11:21:11.489  4458  4637 I jxcore-log: 
,03-16 11:21:11.617  4458  4637 I jxcore-log: # 58. #testThaliPeerAction - make sure ids are unique
03-16 11:21:11.617  4458  4637 I jxcore-log: 
,03-16 11:21:11.756  4458  4637 I jxcore-log: # teardown
03-16 11:21:11.756  4458  4637 I jxcore-log: 
,03-16 11:21:11.908  4458  4637 I jxcore-log: ok 181 should not be equal
03-16 11:21:11.908  4458  4637 I jxcore-log: 
,03-16 11:21:11.911  4458  4637 I jxcore-log: # setup
03-16 11:21:11.911  4458  4637 I jxcore-log: 
,03-16 11:21:12.055  4458  4637 I jxcore-log: # 59. Test PeerConnectionInformation basics
03-16 11:21:12.055  4458  4637 I jxcore-log: 
,03-16 11:21:12.168  4458  4637 I jxcore-log: # teardown
03-16 11:21:12.168  4458  4637 I jxcore-log: 
,03-16 11:21:12.300  4458  4637 I jxcore-log: ok 182 getHostAddress works
03-16 11:21:12.300  4458  4637 I jxcore-log: 
,03-16 11:21:12.302  4458  4637 I jxcore-log: ok 183 getPortNumber works
03-16 11:21:12.302  4458  4637 I jxcore-log: 
03-16 11:21:12.303  4458  4637 I jxcore-log: ok 184 getSuggestedTCPTimeout works
03-16 11:21:12.303  4458  4637 I jxcore-log: 
,03-16 11:21:12.310  4458  4637 I jxcore-log: # setup
03-16 11:21:12.310  4458  4637 I jxcore-log: 
,03-16 11:21:12.386  4458  4637 I jxcore-log: # 60. Test PeerDictionary basic functionality
03-16 11:21:12.386  4458  4637 I jxcore-log: 
,03-16 11:21:12.498  4458  4637 I jxcore-log: # teardown
03-16 11:21:12.498  4458  4637 I jxcore-log: 
,03-16 11:21:12.688  4458  4637 I jxcore-log: ok 185 Entry counter must be 1
03-16 11:21:12.688  4458  4637 I jxcore-log: 
03-16 11:21:12.688  4458  4637 I jxcore-log: ok 186 Size must be 1
03-16 11:21:12.688  4458  4637 I jxcore-log: 
03-16 11:21:12.689  4458  4637 I jxcore-log: ok 187 Entry counter must be 2
03-16 11:21:12.689  4458  4637 I jxcore-log: 
03-16 11:21:12.689  4458  4637 I jxcore-log: ok 188 Size must be 2
03-16 11:21:12.689  4458  4637 I jxcore-log: 
,03-16 11:21:12.696  4458  4637 I jxcore-log: ok 189 Entry2 should not be found
03-16 11:21:12.696  4458  4637 I jxcore-log: 
,03-16 11:21:12.698  4458  4637 I jxcore-log: ok 190 Size must be 1
03-16 11:21:12.698  4458  4637 I jxcore-log: 
03-16 11:21:12.698  4458  4637 I jxcore-log: ok 191 Size must be 0
03-16 11:21:12.698  4458  4637 I jxcore-log: 
,03-16 11:21:12.704  4458  4637 I jxcore-log: ok 192 entry not found must be thrown
03-16 11:21:12.704  4458  4637 I jxcore-log: 
,03-16 11:21:12.707  4458  4637 I jxcore-log: # setup
03-16 11:21:12.707  4458  4637 I jxcore-log: 
,03-16 11:21:12.832  4458  4637 I jxcore-log: # 61. Test PeerDictionary with multiple entries.
03-16 11:21:12.832  4458  4637 I jxcore-log: 
,03-16 11:21:12.915  4458  4637 I jxcore-log: # teardown
03-16 11:21:12.915  4458  4637 I jxcore-log: 
,03-16 11:21:14.654  4458  4637 I jxcore-log: ok 193 Size must be100
03-16 11:21:14.654  4458  4637 I jxcore-log: 
,03-16 11:21:14.658  4458  4637 I jxcore-log: ok 194 Entries between 20 and MAXSIZE + 20 should exist
03-16 11:21:14.658  4458  4637 I jxcore-log: 
,03-16 11:21:15.447   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:21:16.252  4458  4637 I jxcore-log: ok 195 WAITING state entry should not be removed
03-16 11:21:16.252  4458  4637 I jxcore-log: 
,03-16 11:21:16.254  4458  4637 I jxcore-log: # setup
03-16 11:21:16.254  4458  4637 I jxcore-log: 
,03-16 11:21:16.351  4458  4637 I jxcore-log: # 62. RESOLVED entries are removed before WAITING state entry.
03-16 11:21:16.351  4458  4637 I jxcore-log: 
,03-16 11:21:16.670  4458  4637 I jxcore-log: # teardown
03-16 11:21:16.670  4458  4637 I jxcore-log: 
,03-16 11:21:18.218  4458  4637 I jxcore-log: ok 196 Entries between 6 and MAXSIZE + 4 should exist
03-16 11:21:18.218  4458  4637 I jxcore-log: 
,03-16 11:21:18.218  4458  4637 I jxcore-log: ok 197 Size should be MAXSIZE
03-16 11:21:18.218  4458  4637 I jxcore-log: 
,03-16 11:21:18.219  4458  4637 I jxcore-log: ok 198 Size should be MAXSIZE+6
03-16 11:21:18.219  4458  4637 I jxcore-log: 
03-16 11:21:18.221  4458  4637 I jxcore-log: # setup
03-16 11:21:18.221  4458  4637 I jxcore-log: 
,03-16 11:21:18.287  4458  4637 I jxcore-log: # 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-16 11:21:18.287  4458  4637 I jxcore-log: 
,03-16 11:21:18.821  4458  4637 I jxcore-log: # teardown
03-16 11:21:18.821  4458  4637 I jxcore-log: 
,03-16 11:21:20.319  4458  4637 I jxcore-log: ok 199 WAITING state entry should not be removed
03-16 11:21:20.319  4458  4637 I jxcore-log: 
,03-16 11:21:20.321  4458  4637 I jxcore-log: ok 200 Waiting entries between 6 and MAXSIZE + 4 should exist
03-16 11:21:20.321  4458  4637 I jxcore-log: 
,03-16 11:21:20.321  4458  4637 I jxcore-log: ok 201 Size should be MAXSIZE
03-16 11:21:20.321  4458  4637 I jxcore-log: 
,03-16 11:21:20.322  4458  4637 I jxcore-log: ok 202 entryCounter should be MAXSIZE+6
03-16 11:21:20.322  4458  4637 I jxcore-log: 
03-16 11:21:20.324  4458  4637 I jxcore-log: # setup
03-16 11:21:20.324  4458  4637 I jxcore-log: 
,03-16 11:21:20.438  4458  4637 I jxcore-log: # 64. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-16 11:21:20.438  4458  4637 I jxcore-log: 
,03-16 11:21:20.565  4458  4637 I jxcore-log: # teardown
03-16 11:21:20.565  4458  4637 I jxcore-log: 
,03-16 11:21:21.055   885  1222 D BatteryService: uevent={POWER_SUPPLY_TEMP=288, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310362, SEQNUM=4493, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-658, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 11:21:21.124  2413  2501 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 11:21:22.150  4458  4637 I jxcore-log: ok 203 Kill should be called once
03-16 11:21:22.150  4458  4637 I jxcore-log: 
,03-16 11:21:22.150  4458  4637 I jxcore-log: ok 204 Size should be 100
03-16 11:21:22.150  4458  4637 I jxcore-log: 
,03-16 11:21:22.153  4458  4637 I jxcore-log: # setup
03-16 11:21:22.153  4458  4637 I jxcore-log: 
,03-16 11:21:22.215  4458  4637 I jxcore-log: # 65. #ThaliPeerPoolInterface - bad enqueues
03-16 11:21:22.215  4458  4637 I jxcore-log: 
,03-16 11:21:22.815  4458  4637 I jxcore-log: # teardown
03-16 11:21:22.815  4458  4637 I jxcore-log: 
,03-16 11:21:22.920  4458  4637 I jxcore-log: ok 205 null arg
03-16 11:21:22.920  4458  4637 I jxcore-log: 
,03-16 11:21:22.922  4458  4637 I jxcore-log: ok 206 wrong arg type
03-16 11:21:22.922  4458  4637 I jxcore-log: 
,03-16 11:21:22.928  4458  4637 I jxcore-log: ok 207 wrong state
03-16 11:21:22.928  4458  4637 I jxcore-log: 
,03-16 11:21:22.934  4458  4637 I jxcore-log: # setup
03-16 11:21:22.934  4458  4637 I jxcore-log: 
,03-16 11:21:23.428  4458  4637 I jxcore-log: # 66. #ThaliPeerPoolInterface - do not allow same object type
03-16 11:21:23.428  4458  4637 I jxcore-log: 
,03-16 11:21:23.499  4458  4637 I jxcore-log: # teardown
03-16 11:21:23.499  4458  4637 I jxcore-log: 
,03-16 11:21:23.648  4458  4637 I jxcore-log: ok 208 good enqueue
03-16 11:21:23.648  4458  4637 I jxcore-log: 
,03-16 11:21:23.651  4458  4637 I jxcore-log: ok 209 should be equal
03-16 11:21:23.651  4458  4637 I jxcore-log: 
,03-16 11:21:23.657  4458  4637 I jxcore-log: # setup
03-16 11:21:23.657  4458  4637 I jxcore-log: 
,03-16 11:21:23.749  4458  4637 I jxcore-log: # 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-16 11:21:23.749  4458  4637 I jxcore-log: 
,03-16 11:21:23.832  4458  4637 I jxcore-log: # teardown
03-16 11:21:23.832  4458  4637 I jxcore-log: 
,03-16 11:21:23.927  4458  4637 I jxcore-log: ok 210 good enqueue
03-16 11:21:23.927  4458  4637 I jxcore-log: 
03-16 11:21:23.928  4458  4637 I jxcore-log: ok 211 2nd good enqueue
03-16 11:21:23.928  4458  4637 I jxcore-log: 
03-16 11:21:23.928  4458  4637 I jxcore-log: ok 212 we are in the pool
03-16 11:21:23.928  4458  4637 I jxcore-log: 
,03-16 11:21:23.937  4458  4637 I jxcore-log: ok 213 We are out of the pool
03-16 11:21:23.937  4458  4637 I jxcore-log: 
03-16 11:21:23.938  4458  4637 I jxcore-log: ok 214 Action was killed
03-16 11:21:23.938  4458  4637 I jxcore-log: 
03-16 11:21:23.938  4458  4637 I jxcore-log: ok 215 The original kill was called too
03-16 11:21:23.938  4458  4637 I jxcore-log: 
03-16 11:21:23.939  4458  4637 I jxcore-log: ok 216 second item is still in queue
03-16 11:21:23.939  4458  4637 I jxcore-log: 
03-16 11:21:23.941  4458  4637 I jxcore-log: # setup
03-16 11:21:23.941  4458  4637 I jxcore-log: 
,03-16 11:21:24.065  4458  4637 I jxcore-log: # 68. compareBufferArrays
03-16 11:21:24.065  4458  4637 I jxcore-log: 
,03-16 11:21:24.194  4458  4637 I jxcore-log: # teardown
03-16 11:21:24.194  4458  4637 I jxcore-log: 
,03-16 11:21:24.332  4458  4637 I jxcore-log: ok 217 should throw
03-16 11:21:24.332  4458  4637 I jxcore-log: 
,03-16 11:21:24.338  4458  4637 I jxcore-log: ok 218 should throw
03-16 11:21:24.338  4458  4637 I jxcore-log: 
,03-16 11:21:24.339  4458  4637 I jxcore-log: ok 219 (unnamed assert)
03-16 11:21:24.339  4458  4637 I jxcore-log: 
03-16 11:21:24.340  4458  4637 I jxcore-log: ok 220 (unnamed assert)
03-16 11:21:24.340  4458  4637 I jxcore-log: 
03-16 11:21:24.340  4458  4637 I jxcore-log: ok 221 (unnamed assert)
03-16 11:21:24.340  4458  4637 I jxcore-log: 
03-16 11:21:24.341  4458  4637 I jxcore-log: ok 222 (unnamed assert)
03-16 11:21:24.341  4458  4637 I jxcore-log: 
03-16 11:21:24.342  4458  4637 I jxcore-log: ok 223 (unnamed assert)
03-16 11:21:24.342  4458  4637 I jxcore-log: 
,03-16 11:21:24.350  4458  4637 I jxcore-log: # setup
03-16 11:21:24.350  4458  4637 I jxcore-log: 
,03-16 11:21:24.446  4458  4637 I jxcore-log: # 69. Call start twice and get error
03-16 11:21:24.446  4458  4637 I jxcore-log: 
,03-16 11:21:24.557  4458  4637 I jxcore-log: # teardown
03-16 11:21:24.557  4458  4637 I jxcore-log: 
,03-16 11:21:24.644   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-16 11:21:24.644   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:21:24.644   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:21:24.644   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:21:24.644   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:21:24.644   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:21:24.644   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-16 11:21:24.645   292   516 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 11:21:24.645   292   516 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 11:21:24.645   292   516 I MDMCTBK : checkDefaultInst, current pid is = 292
03-16 11:21:24.645   292   516 I MDMCTBK : checkDefaultInst, pid match
03-16 11:21:24.645   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 11:21:24.645   292   516 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 11:21:24.645   292   516 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 11:21:24.669  4458  4637 I jxcore-log: ok 224 should throw
03-16 11:21:24.669  4458  4637 I jxcore-log: 
,03-16 11:21:24.672  4458  4637 I jxcore-log: # setup
03-16 11:21:24.672  4458  4637 I jxcore-log: 
,03-16 11:21:24.786  4458  4637 I jxcore-log: # 70. Start and make sure it runs
03-16 11:21:24.786  4458  4637 I jxcore-log: 
,03-16 11:21:24.910  4458  4637 I jxcore-log: # teardown
03-16 11:21:24.910  4458  4637 I jxcore-log: 
,03-16 11:21:25.036  4458  4637 I jxcore-log: # setup
03-16 11:21:25.036  4458  4637 I jxcore-log: 
,03-16 11:21:25.127  4458  4637 I jxcore-log: # 71. Make sure getTimeWhenRun is right after start
03-16 11:21:25.127  4458  4637 I jxcore-log: 
,03-16 11:21:25.233  4458  4637 I jxcore-log: # teardown
03-16 11:21:25.233  4458  4637 I jxcore-log: 
,03-16 11:21:25.314  4458  4637 I jxcore-log: ok 225 (unnamed assert)
03-16 11:21:25.314  4458  4637 I jxcore-log: 
,03-16 11:21:25.317  4458  4637 I jxcore-log: # setup
03-16 11:21:25.317  4458  4637 I jxcore-log: 
,03-16 11:21:25.397  4458  4637 I jxcore-log: # 72. Make sure getTimeWhenRun is -1 after function is called
03-16 11:21:25.397  4458  4637 I jxcore-log: 
,03-16 11:21:25.452   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:21:25.484  4458  4637 I jxcore-log: # teardown
03-16 11:21:25.484  4458  4637 I jxcore-log: 
,03-16 11:21:25.612  4458  4637 I jxcore-log: ok 226 should be equal
03-16 11:21:25.612  4458  4637 I jxcore-log: 
,03-16 11:21:25.622  4458  4637 I jxcore-log: # setup
03-16 11:21:25.622  4458  4637 I jxcore-log: 
,03-16 11:21:25.716  4458  4637 I jxcore-log: # 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-16 11:21:25.716  4458  4637 I jxcore-log: 
,03-16 11:21:25.869  4458  4637 I jxcore-log: # teardown
03-16 11:21:25.869  4458  4637 I jxcore-log: 
,03-16 11:21:26.073  4458  4637 I jxcore-log: ok 227 should be equal
03-16 11:21:26.073  4458  4637 I jxcore-log: 
,03-16 11:21:26.077  4458  4637 I jxcore-log: ok 228 should be equal
03-16 11:21:26.077  4458  4637 I jxcore-log: 
,03-16 11:21:26.082  4458  4637 I jxcore-log: ok 229 should throw
03-16 11:21:26.082  4458  4637 I jxcore-log: 
,03-16 11:21:26.088  4458  4637 I jxcore-log: # setup
03-16 11:21:26.088  4458  4637 I jxcore-log: 
,03-16 11:21:26.248  4458  4637 I jxcore-log: # 74. Test TransientState
03-16 11:21:26.248  4458  4637 I jxcore-log: 
,03-16 11:21:26.373  4458  4637 I jxcore-log: # teardown
03-16 11:21:26.373  4458  4637 I jxcore-log: 
,03-16 11:21:26.505  4458  4637 I jxcore-log: ok 230 should throw
03-16 11:21:26.505  4458  4637 I jxcore-log: 
,03-16 11:21:26.511  4458  4637 I jxcore-log: ok 231 should throw
03-16 11:21:26.511  4458  4637 I jxcore-log: 
,03-16 11:21:26.512  4458  4637 I jxcore-log: ok 232 should be equal
03-16 11:21:26.512  4458  4637 I jxcore-log: 
,03-16 11:21:26.516  4458  4637 I jxcore-log: ok 233 should be equal
03-16 11:21:26.516  4458  4637 I jxcore-log: 
,03-16 11:21:26.518  4458  4637 I jxcore-log: ok 234 should be equal
03-16 11:21:26.518  4458  4637 I jxcore-log: 
,03-16 11:21:26.519  4458  4637 I jxcore-log: ok 235 should be equal
03-16 11:21:26.519  4458  4637 I jxcore-log: 
,03-16 11:21:26.522  4458  4637 I jxcore-log: ok 236 (unnamed assert)
03-16 11:21:26.522  4458  4637 I jxcore-log: 
03-16 11:21:26.522  4458  4637 I jxcore-log: ok 237 (unnamed assert)
03-16 11:21:26.522  4458  4637 I jxcore-log: 
,03-16 11:21:26.527  4458  4637 I jxcore-log: # setup
03-16 11:21:26.527  4458  4637 I jxcore-log: 
,03-16 11:21:26.622  4458  4637 I jxcore-log: # 75. No peers and empty database
03-16 11:21:26.622  4458  4637 I jxcore-log: 
,03-16 11:21:26.721  4458  4637 I jxcore-log: # teardown
03-16 11:21:26.721  4458  4637 I jxcore-log: 
,03-16 11:21:26.964  4458  4637 I jxcore-log: ok 238 verify failed
03-16 11:21:26.964  4458  4637 I jxcore-log: 
,03-16 11:21:26.964  4458  4637 I jxcore-log: ok 239 constructor called once
03-16 11:21:26.964  4458  4637 I jxcore-log: 
,03-16 11:21:26.967  4458  4637 I jxcore-log: ok 240 constructor called with right args
03-16 11:21:26.967  4458  4637 I jxcore-log: 
,03-16 11:21:26.968  4458  4637 I jxcore-log: ok 241 match start arg
03-16 11:21:26.968  4458  4637 I jxcore-log: 
,03-16 11:21:26.969  4458  4637 I jxcore-log: ok 242 start called once
03-16 11:21:26.969  4458  4637 I jxcore-log: 
,03-16 11:21:26.969  4458  4637 I jxcore-log: ok 243 stop called once
03-16 11:21:26.969  4458  4637 I jxcore-log: 
,03-16 11:21:26.970  4458  4637 I jxcore-log: ok 244 stop after start
03-16 11:21:26.970  4458  4637 I jxcore-log: 
,03-16 11:21:26.976  4458  4637 I jxcore-log: # setup
03-16 11:21:26.976  4458  4637 I jxcore-log: 
,03-16 11:21:27.167  4458  4637 I jxcore-log: # 76. One peer and empty DB
03-16 11:21:27.167  4458  4637 I jxcore-log: 
,03-16 11:21:27.253  4458  4637 I jxcore-log: # teardown
03-16 11:21:27.253  4458  4637 I jxcore-log: 
,03-16 11:21:27.567  4458  4637 I jxcore-log: ok 245 verify failed
03-16 11:21:27.567  4458  4637 I jxcore-log: 
,03-16 11:21:27.568  4458  4637 I jxcore-log: ok 246 constructor called once
03-16 11:21:27.568  4458  4637 I jxcore-log: 
,03-16 11:21:27.569  4458  4637 I jxcore-log: ok 247 constructor called with right args
03-16 11:21:27.569  4458  4637 I jxcore-log: 
03-16 11:21:27.571  4458  4637 I jxcore-log: ok 248 match start arg
03-16 11:21:27.571  4458  4637 I jxcore-log: 
03-16 11:21:27.571  4458  4637 I jxcore-log: ok 249 start called once
03-16 11:21:27.571  4458  4637 I jxcore-log: 
03-16 11:21:27.571  4458  4637 I jxcore-log: ok 250 stop called once
03-16 11:21:27.571  4458  4637 I jxcore-log: 
03-16 11:21:27.572  4458  4637 I jxcore-log: ok 251 stop after start
03-16 11:21:27.572  4458  4637 I jxcore-log: 
,03-16 11:21:27.578  4458  4637 I jxcore-log: # setup
03-16 11:21:27.578  4458  4637 I jxcore-log: 
,03-16 11:21:27.660  4458  4637 I jxcore-log: # 77. One peer with _Local set behind current seq
03-16 11:21:27.660  4458  4637 I jxcore-log: 
,03-16 11:21:27.791  4458  4637 I jxcore-log: # teardown
03-16 11:21:27.791  4458  4637 I jxcore-log: 
,03-16 11:21:28.165  4458  4637 I jxcore-log: ok 252 verify failed
03-16 11:21:28.165  4458  4637 I jxcore-log: 
03-16 11:21:28.166  4458  4637 I jxcore-log: ok 253 constructor called once
03-16 11:21:28.166  4458  4637 I jxcore-log: 
03-16 11:21:28.167  4458  4637 I jxcore-log: ok 254 constructor called with right args
03-16 11:21:28.167  4458  4637 I jxcore-log: 
03-16 11:21:28.168  4458  4637 I jxcore-log: ok 255 match start arg
03-16 11:21:28.168  4458  4637 I jxcore-log: 
03-16 11:21:28.168  4458  4637 I jxcore-log: ok 256 start called once
03-16 11:21:28.168  4458  4637 I jxcore-log: 
03-16 11:21:28.168  4458  4637 I jxcore-log: ok 257 stop called once
03-16 11:21:28.168  4458  4637 I jxcore-log: 
03-16 11:21:28.169  4458  4637 I jxcore-log: ok 258 stop after start
03-16 11:21:28.169  4458  4637 I jxcore-log: 
,03-16 11:21:28.174  4458  4637 I jxcore-log: # setup
03-16 11:21:28.174  4458  4637 I jxcore-log: 
,03-16 11:21:28.371  4458  4637 I jxcore-log: # 78. One peer with _Local set equal to current seq
03-16 11:21:28.371  4458  4637 I jxcore-log: 
,03-16 11:21:28.957  4458  4637 I jxcore-log: # teardown
03-16 11:21:28.957  4458  4637 I jxcore-log: 
,03-16 11:21:29.317  4458  4637 I jxcore-log: ok 259 verify failed
03-16 11:21:29.317  4458  4637 I jxcore-log: 
,03-16 11:21:29.317  4458  4637 I jxcore-log: ok 260 constructor called once
03-16 11:21:29.317  4458  4637 I jxcore-log: 
,03-16 11:21:29.318  4458  4637 I jxcore-log: ok 261 constructor called with right args
03-16 11:21:29.318  4458  4637 I jxcore-log: 
03-16 11:21:29.319  4458  4637 I jxcore-log: ok 262 match start arg
03-16 11:21:29.319  4458  4637 I jxcore-log: 
03-16 11:21:29.319  4458  4637 I jxcore-log: ok 263 start called once
03-16 11:21:29.319  4458  4637 I jxcore-log: 
03-16 11:21:29.320  4458  4637 I jxcore-log: ok 264 stop called once
03-16 11:21:29.320  4458  4637 I jxcore-log: 
03-16 11:21:29.323  4458  4637 I jxcore-log: ok 265 stop after start
03-16 11:21:29.323  4458  4637 I jxcore-log: 
,03-16 11:21:29.328  4458  4637 I jxcore-log: # setup
03-16 11:21:29.328  4458  4637 I jxcore-log: 
,03-16 11:21:29.567  4458  4637 I jxcore-log: # 79. One peer with _Local set ahead of current seq (and no this should not happen)
03-16 11:21:29.567  4458  4637 I jxcore-log: 
,03-16 11:21:29.680  4458  4637 I jxcore-log: # teardown
03-16 11:21:29.680  4458  4637 I jxcore-log: 
,03-16 11:21:30.038  4458  4637 I jxcore-log: ok 266 verify failed
03-16 11:21:30.038  4458  4637 I jxcore-log: 
,03-16 11:21:30.039  4458  4637 I jxcore-log: ok 267 constructor called once
03-16 11:21:30.039  4458  4637 I jxcore-log: 
,03-16 11:21:30.039  4458  4637 I jxcore-log: ok 268 constructor called with right args
03-16 11:21:30.039  4458  4637 I jxcore-log: 
03-16 11:21:30.040  4458  4637 I jxcore-log: ok 269 match start arg
03-16 11:21:30.040  4458  4637 I jxcore-log: 
03-16 11:21:30.041  4458  4637 I jxcore-log: ok 270 start called once
03-16 11:21:30.041  4458  4637 I jxcore-log: 
03-16 11:21:30.041  4458  4637 I jxcore-log: ok 271 stop called once
03-16 11:21:30.041  4458  4637 I jxcore-log: 
03-16 11:21:30.041  4458  4637 I jxcore-log: ok 272 stop after start
03-16 11:21:30.041  4458  4637 I jxcore-log: 
,03-16 11:21:30.047  4458  4637 I jxcore-log: # setup
03-16 11:21:30.047  4458  4637 I jxcore-log: 
,03-16 11:21:30.182  4458  4637 I jxcore-log: # 80. Three peers, one not in DB, one behind and one ahead
03-16 11:21:30.182  4458  4637 I jxcore-log: 
,03-16 11:21:30.388  4458  4637 I jxcore-log: # teardown
03-16 11:21:30.388  4458  4637 I jxcore-log: 
,03-16 11:21:30.980  4458  4637 I jxcore-log: ok 273 verify failed
03-16 11:21:30.980  4458  4637 I jxcore-log: 
,03-16 11:21:30.981  4458  4637 I jxcore-log: ok 274 constructor called once
03-16 11:21:30.981  4458  4637 I jxcore-log: 
,03-16 11:21:30.982  4458  4637 I jxcore-log: ok 275 constructor called with right args
03-16 11:21:30.982  4458  4637 I jxcore-log: 
03-16 11:21:30.983  4458  4637 I jxcore-log: ok 276 match start arg
03-16 11:21:30.983  4458  4637 I jxcore-log: 
03-16 11:21:30.983  4458  4637 I jxcore-log: ok 277 start called once
03-16 11:21:30.983  4458  4637 I jxcore-log: 
,03-16 11:21:30.984  4458  4637 I jxcore-log: ok 278 stop called once
03-16 11:21:30.984  4458  4637 I jxcore-log: 
,03-16 11:21:30.984  4458  4637 I jxcore-log: ok 279 stop after start
03-16 11:21:30.984  4458  4637 I jxcore-log: 
03-16 11:21:30.990  4458  4637 I jxcore-log: # setup
03-16 11:21:30.990  4458  4637 I jxcore-log: 
,03-16 11:21:31.079  4458  4637 I jxcore-log: # 81. More than maximum peers, make sure we only send maximum allowed
03-16 11:21:31.079  4458  4637 I jxcore-log: 
,03-16 11:21:31.212  4458  4637 I jxcore-log: # teardown
03-16 11:21:31.212  4458  4637 I jxcore-log: 
,03-16 11:21:32.639  4458  4637 I jxcore-log: ok 280 verify failed
03-16 11:21:32.639  4458  4637 I jxcore-log: 
,03-16 11:21:32.640  4458  4637 I jxcore-log: ok 281 constructor called once
03-16 11:21:32.640  4458  4637 I jxcore-log: 
,03-16 11:21:32.640  4458  4637 I jxcore-log: ok 282 constructor called with right args
03-16 11:21:32.640  4458  4637 I jxcore-log: 
,03-16 11:21:32.641  4458  4637 I jxcore-log: ok 283 match start arg
03-16 11:21:32.641  4458  4637 I jxcore-log: 
03-16 11:21:32.642  4458  4637 I jxcore-log: ok 284 start called once
03-16 11:21:32.642  4458  4637 I jxcore-log: 
03-16 11:21:32.642  4458  4637 I jxcore-log: ok 285 stop called once
03-16 11:21:32.642  4458  4637 I jxcore-log: 
03-16 11:21:32.642  4458  4637 I jxcore-log: ok 286 stop after start
03-16 11:21:32.642  4458  4637 I jxcore-log: 
,03-16 11:21:32.648  4458  4637 I jxcore-log: # setup
03-16 11:21:32.648  4458  4637 I jxcore-log: 
,03-16 11:21:32.724  4458  4637 I jxcore-log: # 82. two peers with empty DB, update the doc
03-16 11:21:32.724  4458  4637 I jxcore-log: 
,03-16 11:21:32.866  4458  4637 I jxcore-log: # teardown
03-16 11:21:32.866  4458  4637 I jxcore-log: 
,03-16 11:21:33.265  4458  4637 I jxcore-log: ok 287 verify failed
03-16 11:21:33.265  4458  4637 I jxcore-log: 
03-16 11:21:33.266  4458  4637 I jxcore-log: ok 288 constructor called once
03-16 11:21:33.266  4458  4637 I jxcore-log: 
03-16 11:21:33.266  4458  4637 I jxcore-log: ok 289 constructor called with right args
03-16 11:21:33.266  4458  4637 I jxcore-log: 
03-16 11:21:33.267  4458  4637 I jxcore-log: ok 290 last start before stop
03-16 11:21:33.267  4458  4637 I jxcore-log: 
03-16 11:21:33.267  4458  4637 I jxcore-log: ok 291 empty first start
03-16 11:21:33.267  4458  4637 I jxcore-log: 
03-16 11:21:33.269  4458  4637 I jxcore-log: ok 292 full second start
03-16 11:21:33.269  4458  4637 I jxcore-log: 
03-16 11:21:33.269  4458  4637 I jxcore-log: ok 293 only 2 timers
03-16 11:21:33.269  4458  4637 I jxcore-log: 
,03-16 11:21:33.273  4458  4637 I jxcore-log: # setup
03-16 11:21:33.273  4458  4637 I jxcore-log: 
,03-16 11:21:33.382  4458  4637 I jxcore-log: # 83. add doc and make sure tokens refresh when they expire
03-16 11:21:33.382  4458  4637 I jxcore-log: 
,03-16 11:21:33.877  4458  4637 I jxcore-log: # teardown
03-16 11:21:33.877  4458  4637 I jxcore-log: 
,03-16 11:21:34.543  4458  4637 I jxcore-log: ok 294 verify failed
03-16 11:21:34.543  4458  4637 I jxcore-log: 
03-16 11:21:34.544  4458  4637 I jxcore-log: ok 295 constructor called once
03-16 11:21:34.544  4458  4637 I jxcore-log: 
03-16 11:21:34.545  4458  4637 I jxcore-log: ok 296 constructor called with right args
03-16 11:21:34.545  4458  4637 I jxcore-log: 
03-16 11:21:34.546  4458  4637 I jxcore-log: ok 297 start before stop
03-16 11:21:34.546  4458  4637 I jxcore-log: 
03-16 11:21:34.546  4458  4637 I jxcore-log: ok 298 We got at least 3 calls to start
03-16 11:21:34.546  4458  4637 I jxcore-log: 
03-16 11:21:34.547  4458  4637 I jxcore-log: ok 299 at least 3
03-16 11:21:34.547  4458  4637 I jxcore-log: 
03-16 11:21:34.547  4458  4637 I jxcore-log: ok 300 default 1
03-16 11:21:34.547  4458  4637 I jxcore-log: 
03-16 11:21:34.548  4458  4637 I jxcore-log: ok 301 1 run
03-16 11:21:34.548  4458  4637 I jxcore-log: 
03-16 11:21:34.548  4458  4637 I jxcore-log: ok 302 default 2
03-16 11:21:34.548  4458  4637 I jxcore-log: 
03-16 11:21:34.549  4458  4637 I jxcore-log: ok 303 2 run
03-16 11:21:34.549  4458  4637 I jxcore-log: 
03-16 11:21:34.550  4458  4637 I jxcore-log: ok 304 default 3
03-16 11:21:34.550  4458  4637 I jxcore-log: 
,03-16 11:21:34.561  4458  4637 I jxcore-log: # setup
03-16 11:21:34.561  4458  4637 I jxcore-log: 
,03-16 11:21:34.797  4458  4637 I jxcore-log: # 84. start and stop and start and stop
03-16 11:21:34.797  4458  4637 I jxcore-log: 
,03-16 11:21:34.851  4458  4637 I jxcore-log: # teardown
03-16 11:21:34.851  4458  4637 I jxcore-log: 
,03-16 11:21:35.188  4458  4637 I jxcore-log: ok 305 start out null
03-16 11:21:35.188  4458  4637 I jxcore-log: 
,03-16 11:21:35.222  4458  4637 I jxcore-log: ok 306 back to null
03-16 11:21:35.222  4458  4637 I jxcore-log: 
,03-16 11:21:35.254  4458  4637 I jxcore-log: ok 307 still null
03-16 11:21:35.254  4458  4637 I jxcore-log: 
,03-16 11:21:35.256  4458  4637 I jxcore-log: ok 308 verify failed
03-16 11:21:35.256  4458  4637 I jxcore-log: 
,03-16 11:21:35.257  4458  4637 I jxcore-log: ok 309 constructor called once
03-16 11:21:35.257  4458  4637 I jxcore-log: 
,03-16 11:21:35.258  4458  4637 I jxcore-log: ok 310 constructor called with right args
03-16 11:21:35.258  4458  4637 I jxcore-log: 
03-16 11:21:35.258  4458  4637 I jxcore-log: ok 311 first start before first stop
03-16 11:21:35.258  4458  4637 I jxcore-log: 
03-16 11:21:35.259  4458  4637 I jxcore-log: ok 312 first stop before second start
03-16 11:21:35.259  4458  4637 I jxcore-log: 
03-16 11:21:35.259  4458  4637 I jxcore-log: ok 313 second start before second stop
03-16 11:21:35.259  4458  4637 I jxcore-log: 
,03-16 11:21:35.269  4458  4637 I jxcore-log: # setup
03-16 11:21:35.269  4458  4637 I jxcore-log: 
,03-16 11:21:35.432  4458  4637 I jxcore-log: # 85. two identical starts in a row
03-16 11:21:35.432  4458  4637 I jxcore-log: 
,03-16 11:21:35.458   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:21:35.587  4458  4637 I jxcore-log: # teardown
03-16 11:21:35.587  4458  4637 I jxcore-log: 
,03-16 11:21:36.013  4458  4637 I jxcore-log: ok 314 verify failed
03-16 11:21:36.013  4458  4637 I jxcore-log: 
,03-16 11:21:36.014  4458  4637 I jxcore-log: ok 315 constructor called once
03-16 11:21:36.014  4458  4637 I jxcore-log: 
,03-16 11:21:36.015  4458  4637 I jxcore-log: ok 316 constructor called with right args
03-16 11:21:36.015  4458  4637 I jxcore-log: 
,03-16 11:21:36.015  4458  4637 I jxcore-log: ok 317 (unnamed assert)
03-16 11:21:36.015  4458  4637 I jxcore-log: 
,03-16 11:21:36.021  4458  4637 I jxcore-log: # setup
03-16 11:21:36.021  4458  4637 I jxcore-log: 
,03-16 11:21:36.094  4458  4637 I jxcore-log: # 86. two different starts in a row
03-16 11:21:36.094  4458  4637 I jxcore-log: 
,03-16 11:21:36.214  4458  4637 I jxcore-log: # teardown
03-16 11:21:36.214  4458  4637 I jxcore-log: 
,03-16 11:21:36.565  4458  4637 I jxcore-log: ok 318 verify failed
03-16 11:21:36.565  4458  4637 I jxcore-log: 
03-16 11:21:36.565  4458  4637 I jxcore-log: ok 319 constructor called once
03-16 11:21:36.565  4458  4637 I jxcore-log: 
03-16 11:21:36.566  4458  4637 I jxcore-log: ok 320 constructor called with right args
03-16 11:21:36.566  4458  4637 I jxcore-log: 
03-16 11:21:36.566  4458  4637 I jxcore-log: ok 321 (unnamed assert)
03-16 11:21:36.566  4458  4637 I jxcore-log: 
03-16 11:21:36.567  4458  4637 I jxcore-log: ok 322 (unnamed assert)
03-16 11:21:36.567  4458  4637 I jxcore-log: 
,03-16 11:21:36.571  4458  4637 I jxcore-log: # setup
03-16 11:21:36.571  4458  4637 I jxcore-log: 
,03-16 11:21:36.676  4458  4637 I jxcore-log: # 87. two stops and a start and two stops
03-16 11:21:36.676  4458  4637 I jxcore-log: 
,03-16 11:21:36.849  4458  4637 I jxcore-log: # teardown
03-16 11:21:36.849  4458  4637 I jxcore-log: 
,03-16 11:21:37.256  4458  4637 I jxcore-log: ok 323 verify failed
03-16 11:21:37.256  4458  4637 I jxcore-log: 
03-16 11:21:37.257  4458  4637 I jxcore-log: ok 324 constructor called once
03-16 11:21:37.257  4458  4637 I jxcore-log: 
03-16 11:21:37.257  4458  4637 I jxcore-log: ok 325 constructor called with right args
03-16 11:21:37.257  4458  4637 I jxcore-log: 
03-16 11:21:37.258  4458  4637 I jxcore-log: ok 326 start before stop
03-16 11:21:37.258  4458  4637 I jxcore-log: 
,03-16 11:21:37.264  4458  4637 I jxcore-log: # setup
03-16 11:21:37.264  4458  4637 I jxcore-log: 
,03-16 11:21:37.431  4458  4637 I jxcore-log: # 88. we properly enqueue requests so no then needed
03-16 11:21:37.431  4458  4637 I jxcore-log: 
,03-16 11:21:37.540  4458  4637 I jxcore-log: # teardown
03-16 11:21:37.540  4458  4637 I jxcore-log: 
,03-16 11:21:37.907  4458  4637 I jxcore-log: ok 327 verify failed
03-16 11:21:37.907  4458  4637 I jxcore-log: 
,03-16 11:21:37.908  4458  4637 I jxcore-log: ok 328 constructor called once
03-16 11:21:37.908  4458  4637 I jxcore-log: 
,03-16 11:21:37.908  4458  4637 I jxcore-log: ok 329 constructor called with right args
03-16 11:21:37.908  4458  4637 I jxcore-log: 
,03-16 11:21:37.909  4458  4637 I jxcore-log: ok 330 start before stop
03-16 11:21:37.909  4458  4637 I jxcore-log: 
03-16 11:21:37.914  4458  4637 I jxcore-log: # setup
03-16 11:21:37.914  4458  4637 I jxcore-log: 
,03-16 11:21:38.062  4458  4637 I jxcore-log: # 89. test calculateSeqPointKeyId
03-16 11:21:38.062  4458  4637 I jxcore-log: 
,03-16 11:21:38.189  4458  4637 I jxcore-log: # teardown
03-16 11:21:38.189  4458  4637 I jxcore-log: 
,03-16 11:21:38.386  4458  4637 I jxcore-log: ok 331 should be equal
03-16 11:21:38.386  4458  4637 I jxcore-log: 
03-16 11:21:38.387  4458  4637 I jxcore-log: ok 332 should be equal
03-16 11:21:38.387  4458  4637 I jxcore-log: 
03-16 11:21:38.389  4458  4637 I jxcore-log: # setup
03-16 11:21:38.389  4458  4637 I jxcore-log: 
,03-16 11:21:38.510  4458  4637 I jxcore-log: # 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-16 11:21:38.510  4458  4637 I jxcore-log: 
,03-16 11:21:38.622  4458  4637 I jxcore-log: ok 333 should be in started state
03-16 11:21:38.622  4458  4637 I jxcore-log: 
,03-16 11:21:38.629  4458  4637 I jxcore-log: # teardown
03-16 11:21:38.629  4458  4637 I jxcore-log: 
,03-16 11:21:38.782  4458  4637 I jxcore-log: ok 334 peer identifier should match
03-16 11:21:38.782  4458  4637 I jxcore-log: 
03-16 11:21:38.783  4458  4637 I jxcore-log: ok 335 host address should match
03-16 11:21:38.783  4458  4637 I jxcore-log: 
03-16 11:21:38.783  4458  4637 I jxcore-log: ok 336 port should match
03-16 11:21:38.783  4458  4637 I jxcore-log: 
,03-16 11:21:38.791  4458  4637 I jxcore-log: ok 337 host address should be null
03-16 11:21:38.791  4458  4637 I jxcore-log: 
03-16 11:21:38.791  4458  4637 I jxcore-log: ok 338 port should should be null
03-16 11:21:38.791  4458  4637 I jxcore-log: 
,03-16 11:21:38.799  4458  4637 I jxcore-log: # setup
03-16 11:21:38.799  4458  4637 I jxcore-log: 
,03-16 11:21:38.915  4458  4637 I jxcore-log: ok 339 should not be in started state
03-16 11:21:38.915  4458  4637 I jxcore-log: 
,03-16 11:21:38.920  4458  4637 I jxcore-log: # 91. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-16 11:21:38.920  4458  4637 I jxcore-log: 
,03-16 11:21:39.031  4458  4637 I jxcore-log: ok 340 should be in started state
03-16 11:21:39.031  4458  4637 I jxcore-log: 
,03-16 11:21:39.037  4458  4637 I jxcore-log: # teardown
03-16 11:21:39.037  4458  4637 I jxcore-log: 
,03-16 11:21:39.439  4458  4637 I jxcore-log: ok 341 USN should have changed from the first one
03-16 11:21:39.439  4458  4637 I jxcore-log: 
,03-16 11:21:39.447  4458  4637 I jxcore-log: ok 342 when receiving the second byebye, the first USN should be already set
03-16 11:21:39.447  4458  4637 I jxcore-log: 
,03-16 11:21:39.460  4458  4637 I jxcore-log: # setup
03-16 11:21:39.460  4458  4637 I jxcore-log: 
,03-16 11:21:39.597  4458  4637 I jxcore-log: ok 343 should not be in started state
03-16 11:21:39.597  4458  4637 I jxcore-log: 
,03-16 11:21:39.599  4458  4637 I jxcore-log: # 92. messages with invalid location or USN should be ignored
03-16 11:21:39.599  4458  4637 I jxcore-log: 
,03-16 11:21:40.017  4458  4637 I jxcore-log: ok 344 should be in started state
03-16 11:21:40.017  4458  4637 I jxcore-log: 
,03-16 11:21:40.020  4458  4637 I jxcore-log: # teardown
03-16 11:21:40.020  4458  4637 I jxcore-log: 
,03-16 11:21:40.110  4458  4637 I jxcore-log: WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
03-16 11:21:40.110  4458  4637 I jxcore-log: 
,03-16 11:21:40.111  4458  4637 I jxcore-log: ok 345 should not have emitted with invalid port
03-16 11:21:40.111  4458  4637 I jxcore-log: 
,03-16 11:21:40.118  4458  4637 I jxcore-log: WARN thaliWifiInfrastructure Received an invalid USN value: 
03-16 11:21:40.118  4458  4637 I jxcore-log: 
,03-16 11:21:40.121  4458  4637 I jxcore-log: ok 346 should not have emitted with invalid USN
03-16 11:21:40.121  4458  4637 I jxcore-log: 
,03-16 11:21:40.127  4458  4637 I jxcore-log: # setup
03-16 11:21:40.127  4458  4637 I jxcore-log: 
,03-16 11:21:40.292  4458  4637 I jxcore-log: ok 347 should not be in started state
03-16 11:21:40.292  4458  4637 I jxcore-log: 
,03-16 11:21:40.298  4458  4637 I jxcore-log: # 93. verify that Thali-specific messages are filtered correctly
03-16 11:21:40.298  4458  4637 I jxcore-log: 
,03-16 11:21:40.406  4458  4637 I jxcore-log: ok 348 should be in started state
03-16 11:21:40.406  4458  4637 I jxcore-log: 
,03-16 11:21:40.408  4458  4637 I jxcore-log: # teardown
03-16 11:21:40.408  4458  4637 I jxcore-log: 
,03-16 11:21:40.629  4458  4637 I jxcore-log: ok 349 irrelevant messages should be ignored
03-16 11:21:40.629  4458  4637 I jxcore-log: 
,03-16 11:21:40.630  4458  4637 I jxcore-log: ok 350 relevant messages should not be ignored
03-16 11:21:40.630  4458  4637 I jxcore-log: 
03-16 11:21:40.630  4458  4637 I jxcore-log: ok 351 messages from this device should be ignored
03-16 11:21:40.630  4458  4637 I jxcore-log: 
03-16 11:21:40.633  4458  4637 I jxcore-log: # setup
03-16 11:21:40.633  4458  4637 I jxcore-log: 
,03-16 11:21:40.814  4458  4637 I jxcore-log: ok 352 should not be in started state
03-16 11:21:40.814  4458  4637 I jxcore-log: 
,03-16 11:21:40.817  4458  4637 I jxcore-log: # 94. #startListeningForAdvertisements should fail if start not called
03-16 11:21:40.817  4458  4637 I jxcore-log: 
,03-16 11:21:41.215  4458  4637 I jxcore-log: ok 353 should be in started state
03-16 11:21:41.215  4458  4637 I jxcore-log: 
,03-16 11:21:41.222  4458  4637 I jxcore-log: # teardown
03-16 11:21:41.222  4458  4637 I jxcore-log: 
,03-16 11:21:41.381  4458  4637 I jxcore-log: ok 354 specific error should be returned
03-16 11:21:41.381  4458  4637 I jxcore-log: 
,03-16 11:21:41.387  4458  4637 I jxcore-log: # setup
03-16 11:21:41.387  4458  4637 I jxcore-log: 
,03-16 11:21:41.859  4458  4637 I jxcore-log: ok 355 should not be in started state
03-16 11:21:41.859  4458  4637 I jxcore-log: 
,03-16 11:21:41.862  4458  4637 I jxcore-log: # 95. #startUpdateAdvertisingAndListening should fail if start not called
03-16 11:21:41.862  4458  4637 I jxcore-log: 
,03-16 11:21:41.929  4458  4637 I jxcore-log: ok 356 should be in started state
03-16 11:21:41.929  4458  4637 I jxcore-log: 
03-16 11:21:41.931  4458  4637 I jxcore-log: # teardown
03-16 11:21:41.931  4458  4637 I jxcore-log: 
,03-16 11:21:42.062  4458  4637 I jxcore-log: ok 357 specific error should be returned
03-16 11:21:42.062  4458  4637 I jxcore-log: 
,03-16 11:21:42.068  4458  4637 I jxcore-log: # setup
03-16 11:21:42.068  4458  4637 I jxcore-log: 
,03-16 11:21:42.122  4458  4637 I jxcore-log: ok 358 should not be in started state
03-16 11:21:42.122  4458  4637 I jxcore-log: 
,03-16 11:21:42.126  4458  4637 I jxcore-log: # 96. #start should fail if called twice in a row
03-16 11:21:42.126  4458  4637 I jxcore-log: 
,03-16 11:21:42.198  4458  4637 I jxcore-log: ok 359 should be in started state
03-16 11:21:42.198  4458  4637 I jxcore-log: 
03-16 11:21:42.200  4458  4637 I jxcore-log: # teardown
03-16 11:21:42.200  4458  4637 I jxcore-log: 
,03-16 11:21:42.347  4458  4637 I jxcore-log: ok 360 specific error should be received
03-16 11:21:42.347  4458  4637 I jxcore-log: 
,03-16 11:21:42.349  4458  4637 I jxcore-log: # setup
03-16 11:21:42.349  4458  4637 I jxcore-log: 
,03-16 11:21:42.530  4458  4637 I jxcore-log: ok 361 should not be in started state
03-16 11:21:42.530  4458  4637 I jxcore-log: 
,03-16 11:21:42.532  4458  4637 I jxcore-log: # 97. should not be started after stop is called
03-16 11:21:42.532  4458  4637 I jxcore-log: 
,03-16 11:21:42.727  4458  4637 I jxcore-log: ok 362 should be in started state
03-16 11:21:42.727  4458  4637 I jxcore-log: 
,03-16 11:21:42.730  4458  4637 I jxcore-log: # teardown
03-16 11:21:42.730  4458  4637 I jxcore-log: 
,03-16 11:21:42.816  4458  4637 I jxcore-log: ok 363 should not be started
03-16 11:21:42.816  4458  4637 I jxcore-log: 
,03-16 11:21:42.817  4458  4637 I jxcore-log: ok 364 should not be listening
03-16 11:21:42.817  4458  4637 I jxcore-log: 
03-16 11:21:42.817  4458  4637 I jxcore-log: ok 365 should not target listening
03-16 11:21:42.817  4458  4637 I jxcore-log: 
03-16 11:21:42.818  4458  4637 I jxcore-log: ok 366 should not be advertising
03-16 11:21:42.818  4458  4637 I jxcore-log: 
03-16 11:21:42.818  4458  4637 I jxcore-log: ok 367 should not target advertising
03-16 11:21:42.818  4458  4637 I jxcore-log: 
03-16 11:21:42.821  4458  4637 I jxcore-log: # setup
03-16 11:21:42.821  4458  4637 I jxcore-log: 
,03-16 11:21:42.927  4458  4637 I jxcore-log: ok 368 should not be in started state
03-16 11:21:42.927  4458  4637 I jxcore-log: 
,03-16 11:21:42.930  4458  4637 I jxcore-log: # 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-16 11:21:42.930  4458  4637 I jxcore-log: 
,03-16 11:21:43.030  4458  4637 I jxcore-log: ok 369 should be in started state
03-16 11:21:43.030  4458  4637 I jxcore-log: 
03-16 11:21:43.033  4458  4637 I jxcore-log: # teardown
03-16 11:21:43.033  4458  4637 I jxcore-log: 
,03-16 11:21:43.141  4458  4637 E jxcore-log: ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-16 11:21:43.141  4458  4637 E jxcore-log: 
03-16 11:21:43.143  4458  4637 I jxcore-log: ok 370 specific error should be received
03-16 11:21:43.143  4458  4637 I jxcore-log: 
,03-16 11:21:43.147  4458  4637 I jxcore-log: # setup
03-16 11:21:43.147  4458  4637 I jxcore-log: 
,03-16 11:21:43.240  4458  4637 I jxcore-log: ok 371 should not be in started state
03-16 11:21:43.240  4458  4637 I jxcore-log: 
,03-16 11:21:43.243  4458  4637 I jxcore-log: # 99. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-16 11:21:43.243  4458  4637 I jxcore-log: 
,03-16 11:21:43.370  4458  4637 I jxcore-log: ok 372 should be in started state
03-16 11:21:43.370  4458  4637 I jxcore-log: 
,03-16 11:21:43.372  4458  4637 I jxcore-log: # teardown
03-16 11:21:43.372  4458  4637 I jxcore-log: 
,03-16 11:21:43.525  4458  4637 E jxcore-log: ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
03-16 11:21:43.525  4458  4637 E jxcore-log: 
,03-16 11:21:43.528  4458  4637 I jxcore-log: ok 373 specific error expected
03-16 11:21:43.528  4458  4637 I jxcore-log: 
,03-16 11:21:43.530  4458  4637 I jxcore-log: # setup
03-16 11:21:43.530  4458  4637 I jxcore-log: 
,03-16 11:21:43.672  4458  4637 I jxcore-log: ok 374 should not be in started state
03-16 11:21:43.672  4458  4637 I jxcore-log: 
,03-16 11:21:43.678  4458  4637 I jxcore-log: # 100. #startUpdateAdvertisingAndListening should start hosting given router object
03-16 11:21:43.678  4458  4637 I jxcore-log: 
,03-16 11:21:43.792  4458  4637 I jxcore-log: ok 375 should be in started state
03-16 11:21:43.792  4458  4637 I jxcore-log: 
,03-16 11:21:43.798  4458  4637 I jxcore-log: # teardown
03-16 11:21:43.798  4458  4637 I jxcore-log: 
,03-16 11:21:44.021  4458  4637 I jxcore-log: ok 376 server should respond with code 200
03-16 11:21:44.021  4458  4637 I jxcore-log: 
,03-16 11:21:44.029  4458  4637 I jxcore-log: # setup
03-16 11:21:44.029  4458  4637 I jxcore-log: 
,03-16 11:21:44.147  4458  4637 I jxcore-log: ok 377 should not be in started state
03-16 11:21:44.147  4458  4637 I jxcore-log: 
,03-16 11:21:44.158  4458  4637 I jxcore-log: # 101. #stop can be called multiple times in a row
03-16 11:21:44.158  4458  4637 I jxcore-log: 
,03-16 11:21:44.263  4458  4637 I jxcore-log: ok 378 should be in started state
03-16 11:21:44.263  4458  4637 I jxcore-log: 
,03-16 11:21:44.269  4458  4637 I jxcore-log: # teardown
03-16 11:21:44.269  4458  4637 I jxcore-log: 
,03-16 11:21:44.458  4458  4637 I jxcore-log: ok 379 should be in stopped state
03-16 11:21:44.458  4458  4637 I jxcore-log: 
03-16 11:21:44.459  4458  4637 I jxcore-log: ok 380 should still be in stopped state
03-16 11:21:44.459  4458  4637 I jxcore-log: 
03-16 11:21:44.461  4458  4637 I jxcore-log: # setup
03-16 11:21:44.461  4458  4637 I jxcore-log: 
,03-16 11:21:44.595  4458  4637 I jxcore-log: ok 381 should not be in started state
03-16 11:21:44.595  4458  4637 I jxcore-log: 
,03-16 11:21:44.598  4458  4637 I jxcore-log: # 102. #startListeningForAdvertisements can be called multiple times in a row
03-16 11:21:44.598  4458  4637 I jxcore-log: 
,03-16 11:21:44.691  4458  4637 I jxcore-log: ok 382 should be in started state
03-16 11:21:44.691  4458  4637 I jxcore-log: 
,03-16 11:21:44.696  4458  4637 I jxcore-log: # teardown
03-16 11:21:44.696  4458  4637 I jxcore-log: 
,03-16 11:21:44.828  4458  4637 I jxcore-log: ok 383 should be in listening state
03-16 11:21:44.828  4458  4637 I jxcore-log: 
03-16 11:21:44.830  4458  4637 I jxcore-log: ok 384 should still be in listening state
03-16 11:21:44.830  4458  4637 I jxcore-log: 
03-16 11:21:44.833  4458  4637 I jxcore-log: # setup
03-16 11:21:44.833  4458  4637 I jxcore-log: 
,03-16 11:21:45.002  4458  4637 I jxcore-log: ok 385 should not be in started state
03-16 11:21:45.002  4458  4637 I jxcore-log: 
,03-16 11:21:45.011  4458  4637 I jxcore-log: # 103. #stopListeningForAdvertisements can be called multiple times in a row
03-16 11:21:45.011  4458  4637 I jxcore-log: 
,03-16 11:21:45.156  4458  4637 I jxcore-log: ok 386 should be in started state
03-16 11:21:45.156  4458  4637 I jxcore-log: 
,03-16 11:21:45.158  4458  4637 I jxcore-log: # teardown
03-16 11:21:45.158  4458  4637 I jxcore-log: 
,03-16 11:21:45.269  4458  4637 I jxcore-log: ok 387 should not be in listening state
03-16 11:21:45.269  4458  4637 I jxcore-log: 
,03-16 11:21:45.271  4458  4637 I jxcore-log: ok 388 should still not be in listening state
03-16 11:21:45.271  4458  4637 I jxcore-log: 
,03-16 11:21:45.277  4458  4637 I jxcore-log: # setup
03-16 11:21:45.277  4458  4637 I jxcore-log: 
,03-16 11:21:45.388  4458  4637 I jxcore-log: ok 389 should not be in started state
03-16 11:21:45.388  4458  4637 I jxcore-log: 
,03-16 11:21:45.390  4458  4637 I jxcore-log: # 104. #stopAdvertisingAndListening can be called multiple times in a row
03-16 11:21:45.390  4458  4637 I jxcore-log: 
,03-16 11:21:45.462   303   388 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 11:21:45.538  4458  4637 I jxcore-log: ok 390 should be in started state
03-16 11:21:45.538  4458  4637 I jxcore-log: 
,03-16 11:21:45.540  4458  4637 I jxcore-log: # teardown
03-16 11:21:45.540  4458  4637 I jxcore-log: 
,03-16 11:21:45.719  4458  4637 I jxcore-log: ok 391 should not be in advertising state
03-16 11:21:45.719  4458  4637 I jxcore-log: 
,03-16 11:21:45.721  4458  4637 I jxcore-log: ok 392 should still not be in advertising state
03-16 11:21:45.721  4458  4637 I jxcore-log: 
,03-16 11:21:45.727  4458  4637 I jxcore-log: # setup
03-16 11:21:45.727  4458  4637 I jxcore-log: 
,03-16 11:21:46.064  4458  4637 I jxcore-log: ok 393 should not be in started state
03-16 11:21:46.064  4458  4637 I jxcore-log: 
,03-16 11:21:46.067  4458  4637 I jxcore-log: # 105. functions are run from a queue in the right order
03-16 11:21:46.067  4458  4637 I jxcore-log: 
,03-16 11:21:46.169  4458  4637 I jxcore-log: ok 394 should be in started state
03-16 11:21:46.169  4458  4637 I jxcore-log: 
,03-16 11:21:46.184  4458  4637 I jxcore-log: # teardown
03-16 11:21:46.184  4458  4637 I jxcore-log: 
,03-16 11:21:46.312  4458  4637 I jxcore-log: ok 395 call order must match
03-16 11:21:46.312  4458  4637 I jxcore-log: 
,03-16 11:21:46.320  4458  4637 I jxcore-log: # setup
03-16 11:21:46.320  4458  4637 I jxcore-log: 
,03-16 11:21:46.416  4458  4637 I jxcore-log: ok 396 should not be in started state
03-16 11:21:46.416  4458  4637 I jxcore-log: 
,03-16 11:21:46.419  4458  4637 I jxcore-log: # 106. #ThaliPeerPoolDefault - single action
03-16 11:21:46.419  4458  4637 I jxcore-log: 
,03-16 11:21:46.535  4458  4637 I jxcore-log: # teardown
03-16 11:21:46.535  4458  4637 I jxcore-log: 
,03-16 11:21:46.667  4458  4637 I jxcore-log: ok 397 is an agent
03-16 11:21:46.667  4458  4637 I jxcore-log: 
,03-16 11:21:46.668  4458  4637 I jxcore-log: ok 398 enqueue is fine
03-16 11:21:46.668  4458  4637 I jxcore-log: 
03-16 11:21:46.672  4458  4637 I jxcore-log: ok 399 Everything should be off the queue
03-16 11:21:46.672  4458  4637 I jxcore-log: 
,03-16 11:21:46.679  4458  4637 I jxcore-log: # setup
03-16 11:21:46.679  4458  4637 I jxcore-log: 
,03-16 11:21:46.766  4458  4637 I jxcore-log: # 107. #ThaliPeerPoolDefault - multiple actions
03-16 11:21:46.766  4458  4637 I jxcore-log: 
,03-16 11:21:46.900  4458  4637 I jxcore-log: # teardown
03-16 11:21:46.900  4458  4637 I jxcore-log: 
,03-16 11:21:47.036  4458  4637 I jxcore-log: ok 400 is an agent
03-16 11:21:47.036  4458  4637 I jxcore-log: 
,03-16 11:21:47.037  4458  4637 I jxcore-log: ok 401 first enqueue is fine
03-16 11:21:47.037  4458  4637 I jxcore-log: 
03-16 11:21:47.038  4458  4637 I jxcore-log: ok 402 is an agent
03-16 11:21:47.038  4458  4637 I jxcore-log: 
03-16 11:21:47.039  4458  4637 I jxcore-log: ok 403 second enqueue is fine
03-16 11:21:47.039  4458  4637 I jxcore-log: 
03-16 11:21:47.042  4458  4637 I jxcore-log: ok 404 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-16 11:21:47.042  4458  4637 I jxcore-log: 
03-16 11:21:47.042  4458  4637 I jxcore-log: ok 405 Queue is empty
03-16 11:21:47.042  4458  4637 I jxcore-log: 
,03-16 11:21:47.050  4458  4637 I jxcore-log: Tests Complete
03-16 11:21:47.050  4458  4637 I jxcore-log: 
,03-16 11:21:47.364  4458  4458 I chromium: [INFO:CONSOLE(78)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (78)
,03-16 11:21:47.371  4458  4637 I jxcore-log: Total: 0	Passed: 0	Failed: 0
03-16 11:21:47.371  4458  4637 I jxcore-log: 
,03-16 11:21:47.379  4458  4458 I chromium: [INFO:CONSOLE(78)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (78)
,03-16 11:21:47.381  4458  4637 I jxcore-log: ****TEST TOOK:  ms ****
03-16 11:21:47.381  4458  4637 I jxcore-log: 
03-16 11:21:47.381  4458  4637 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-16 11:21:47.381  4458  4637 I jxcore-log: 
,03-16 11:21:47.407  4458  4637 I jxcore-log: Disconnected from the test server
03-16 11:21:47.407  4458  4637 I jxcore-log: 
,03-16 11:21:47.899  7758  7758 D AndroidRuntime: 
03-16 11:21:47.899  7758  7758 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 11:21:47.904  7758  7758 D AndroidRuntime: CheckJNI is OFF
,03-16 11:21:48.199  7758  7758 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 11:21:48.210   885  1100 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-16 11:21:48.211   885  1100 I ActivityManager: Killing 4458:com.test.thalitest/u0a109 (adj 7): stop com.test.thalitest
,03-16 11:21:48.278   885  1148 W PackageSettings: Skipping PackageSetting{1ff77e53 com.example.hello/10568} due to missing metadata
,03-16 11:21:48.284   885  1593 I WindowState: WIN DEATH: Window{2722ee64 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-16 11:21:48.284   885  1240 D WifiService: Client connection lost with reason: 4
,03-16 11:21:48.422   885  1100 I ActivityManager:   Force finishing activity ActivityRecord{20b52709 u0 com.test.thalitest/.MainActivity t9}
,03-16 11:21:48.424   885  1657 W ActivityManager: Spurious death for ProcessRecord{1a813dc4 4458:com.test.thalitest/u0a109}, curProc for 4458: null
,03-16 11:21:48.430   885  1148 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-16 11:21:48.481   885  1228 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 11:21:48.484  1742  2031 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 11:21:48.488  2985  2985 I art     : Explicit concurrent mark sweep GC freed 8959(2MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 7MB/12MB, paused 743us total 52.556ms
,03-16 11:21:48.503  1420  1420 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-16 11:21:48.513  1420  7781 I Keyboard.Facilitator.DecoderInitializer: run()
,03-16 11:21:48.525   885  1100 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7782 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 11:21:48.557  1576  1576 I art     : Explicit concurrent mark sweep GC freed 2834(148KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 471us total 104.790ms
,03-16 11:21:48.570  1420  7781 I Decoder : createOrResetDecoder
,03-16 11:21:48.613  1742  1742 I ConfigService: onCreate
,03-16 11:21:48.669  1420  7781 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-16 11:21:48.676   885   885 I art     : Explicit concurrent mark sweep GC freed 35644(2MB) AllocSpace objects, 5(260KB) LOS objects, 33% free, 21MB/32MB, paused 9.162ms total 204.814ms
,03-16 11:21:48.679   885  1148 I art     : WaitForGcToComplete blocked for 145.499ms for cause Explicit
,03-16 11:21:48.717  7782  7810 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-16 11:21:48.724  1420  7781 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-16 11:21:48.728  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,03-16 11:21:48.728  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-16 11:21:48.735  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-16 11:21:48.735  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-16 11:21:48.739  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-16 11:21:48.739  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-16 11:21:48.742  1420  7781 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-16 11:21:48.745  1420  7781 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-16 11:21:48.745  1420  7781 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-16 11:21:48.746  1420  7781 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-16 11:21:48.746  1420  7781 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-16 11:21:48.746  1420  7781 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-16 11:21:48.753   885  1593 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7811 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:21:48.767  7782  7808 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 11:21:48.782   885  1818 I ActivityManager: Killing 7280:com.android.vending/u0a32 (adj 15): empty #7
,03-16 11:21:48.805   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-16 11:21:48.805   885   885 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-16 11:21:48.867   885  1148 I art     : Explicit concurrent mark sweep GC freed 6009(306KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.836ms total 188.247ms
,03-16 11:21:48.945  7758  7758 D AndroidRuntime: Shutting down VM
,03-16 11:21:48.950   885  1304 W libprocessgroup: failed to open /acct/uid_10032/pid_7280/cgroup.procs: No such file or directory
,03-16 11:21:48.952   885  1259 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-16 11:21:48.953   885  1259 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-16 11:21:48.962  7811  7811 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,03-16 11:21:48.962  7811  7811 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 11:21:48.962  7811  7811 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 11:21:48.962  7811  7811 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 11:21:48.977  1576  1576 I Launcher: Deferring update until onResume
,03-16 11:21:48.998   885  1148 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7829 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-16 11:21:49.052   885  1539 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7849 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,03-16 11:21:49.122  7849  7849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,03-16 11:21:49.127   885  1594 I ActivityManager: Killing 7358:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 11:21:49.212   885  1248 W libprocessgroup: failed to open /acct/uid_10008/pid_7358/cgroup.procs: No such file or directory
,03-16 11:21:49.274   885  1594 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7873 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 11:21:49.295   885  1594 I ActivityManager: Killing 7331:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 11:21:49.301   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 318us total 27.040ms
,03-16 11:21:49.323   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 21.339ms
,03-16 11:21:49.344   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.454ms
,03-16 11:21:49.357   279   709 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
