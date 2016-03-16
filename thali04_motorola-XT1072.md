#### Test 62509094c3ee53f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-16 10:39:12.019  1288  1288 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 10:39:12.020  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
--------- beginning of system
03-16 10:39:12.049  4515  4515 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 10:39:12.130   879   894 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4539 uid=10096 gids={50096, 9997} abi=armeabi-v7a
03-16 10:39:12.134  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 10:39:12.135   879  1502 I ActivityManager: Killing 3932:com.google.android.talk/u0a70 (adj 15): empty #7
03-16 10:39:12.193   879  1240 W libprocessgroup: failed to open /acct/uid_10070/pid_3932/cgroup.procs: No such file or directory
03-16 10:39:12.217  4539  4539 I System.out: TimeService: Loaded Library 
03-16 10:39:12.218  4539  4539 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458121152218
03-16 10:39:12.218  4539  4539 D         : TimeServiceNative: User Time to be set is 1458121152218
03-16 10:39:12.218  4539  4539 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-16 10:39:12.218  4539  4539 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-16 10:39:12.218  4539  4539 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458121152218
03-16 10:39:12.219  4539  4539 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-16 10:39:12.220   331   828 D QC-time-services: Daemon: Connection accepted:time_genoff
03-16 10:39:12.221   331  4558 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458121152218
03-16 10:39:12.221   331  4558 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458121152218, operation = 0
03-16 10:39:12.221   331  4558 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/16/116 9:37:22
03-16 10:39:12.222   331  4558 D QC-time-services: Daemon:Value read from RTC seconds = 1458121042000
03-16 10:39:12.222   331  4558 D QC-time-services: Daemon:new time 1458121152218 
03-16 10:39:12.222   331  4558 D QC-time-services: Daemon: delta 110218 genoff 110218 
03-16 10:39:12.222   331  4558 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 110218 to memory
03-16 10:39:12.222   331  4558 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-16 10:39:12.222   331  4558 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-16 10:39:12.246  2527  3970 E global frequency: no tags to log
03-16 10:39:12.246   331  4558 D QC-time-services: Updating the TOD offset
03-16 10:39:12.246   331  4558 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 110218 to memory
03-16 10:39:12.246   331  4558 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-16 10:39:12.246   331  4558 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-16 10:39:12.248  2527  3970 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 10:39:12.248   331  4558 E QC-time-services: Daemon:Update to modem bit set
03-16 10:39:12.248   331  4558 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-16 10:39:12.248   331  4558 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743757744861834
03-16 10:39:12.249  4539  4539 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-16 10:39:12.252   331   826 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-16 10:39:12.252   331   828 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-16 10:39:12.252   879  1498 I ActivityManager: Killing 3331:com.android.defcontainer/u0a10 (adj 15): empty #7
03-16 10:39:12.325   879  1498 I ActivityManager: Killing 4392:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
03-16 10:39:12.373   879  1498 I ActivityManager: Killing 4317:com.google.android.apps.magazines/u0a81 (adj 15): empty #8
03-16 10:39:12.487  4556  4556 D AndroidRuntime: 
03-16 10:39:12.487  4556  4556 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 10:39:12.491  4556  4556 D AndroidRuntime: CheckJNI is OFF
03-16 10:39:12.583   879   894 W libprocessgroup: failed to open /acct/uid_10010/pid_3331/cgroup.procs: No such file or directory
03-16 10:39:12.587   879  1592 W libprocessgroup: failed to open /acct/uid_10039/pid_4392/cgroup.procs: No such file or directory
03-16 10:39:12.589   879  1521 W libprocessgroup: failed to open /acct/uid_10081/pid_4317/cgroup.procs: No such file or directory
03-16 10:39:12.621  2527  2527 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-16 10:39:12.634  1551  1959 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
03-16 10:39:12.735  1467  4130 I art     : Explicit concurrent mark sweep GC freed 3631(143KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 610us total 27.142ms
03-16 10:39:12.746  4556  4556 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 10:39:12.758   879  1592 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=4585 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
03-16 10:39:12.786   879   894 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-16 10:39:12.817   278  1962 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (180 us)
03-16 10:39:12.818  2527  2527 I art     : Explicit concurrent mark sweep GC freed 19728(1295KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/19MB, paused 1.291ms total 66.725ms
03-16 10:39:12.841  2527  2527 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-16 10:39:12.852  1467  3870 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 10:39:12.860  2527  2527 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-16 10:39:12.867  4556  4556 D AndroidRuntime: Shutting down VM
03-16 10:39:12.911   879  1539 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4602 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 10:39:12.928  2527  2527 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-16 10:39:12.931  1551  1959 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
03-16 10:39:12.943  1467  3870 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 10:39:13.014  4487  4487 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 10:39:13.017  4487  4487 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
03-16 10:39:13.022   879  1569 I ActivityManager: Killing 4434:com.android.chrome/u0a52 (adj 15): empty #7
03-16 10:39:13.036  2527  2527 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-16 10:39:13.058  2527  2527 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-16 10:39:13.068  4585  4585 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-16 10:39:13.068  4585  4585 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 10:39:13.068  4585  4585 I GAv4    :   adb logcat -s GAv4
,03-16 10:39:13.103   879  1649 W libprocessgroup: failed to open /acct/uid_10052/pid_4434/cgroup.procs: No such file or directory
,03-16 10:39:13.135  4585  4585 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 10:39:13.144  2527  2527 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 10:39:13.149  1551  2321 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 10:39:13.153  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:13.176  4585  4585 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 10:39:13.187  4585  4626 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 10:39:13.231  4602  4602 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 10:39:13.262  4602  4602 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 655-659)
03-16 10:39:13.263  4602  4602 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 10:39:13.301  4602  4602 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2168ec85}
03-16 10:39:13.302  4602  4602 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 10:39:13.302  4602  4602 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 10:39:13.326   879  1419 I art     : Explicit concurrent mark sweep GC freed 15335(789KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 2.777ms total 170.512ms
,03-16 10:39:13.331  4602  4602 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 10:39:13.332  4602  4602 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 10:39:13.335  4602  4602 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 10:39:13.362  4602  4602 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 10:39:13.370  4602  4602 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 10:39:13.370  4602  4602 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 10:39:13.371  4602  4602 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 10:39:13.371  4602  4602 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 10:39:13.371  4602  4602 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 10:39:13.371  4602  4602 I Adreno-EGL: Local Branch: 
03-16 10:39:13.371  4602  4602 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 10:39:13.371  4602  4602 I Adreno-EGL: Local Patches: NONE
03-16 10:39:13.371  4602  4602 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
03-16 10:39:13.372   879  1091 W ActivityManager: Activity pause timeout for ActivityRecord{8d5dd3b u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,03-16 10:39:13.409  1953  1966 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-16 10:39:13.443  1467  1499 I art     : Explicit concurrent mark sweep GC freed 3727(158KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 618us total 29.194ms
,03-16 10:39:13.472  2527  2527 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 10:39:13.479   879  1419 I ActivityManager: Killing 4464:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 10:39:13.482   879  1123 D BluetoothManagerService: Message: 20
,03-16 10:39:13.482   879  1123 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4718:true
,03-16 10:39:13.494  2527  2527 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 10:39:13.517   879  1240 W libprocessgroup: failed to open /acct/uid_10019/pid_4464/cgroup.procs: No such file or directory
,03-16 10:39:13.552  2527  3970 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-16 10:39:13.552  2527  2527 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-16 10:39:13.554  2527  2527 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
03-16 10:39:13.555  2527  2527 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-16 10:39:13.558   879  1521 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-16 10:39:13.558  2527  3970 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-16 10:39:13.559  2527  3970 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 10:39:13.559  2527  3970 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-16 10:39:13.560  2527  3970 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 10:39:13.563  2527  3970 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-16 10:39:13.590  2527  3970 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-16 10:39:13.635   879   879 V AlarmManager: done {d56866f, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8605ms]
,03-16 10:39:13.675  4602  4602 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 10:39:13.683   879  1539 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4650 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:13.695  1467  3870 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 10:39:13.699   879  1568 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{8d5dd3b u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,03-16 10:39:13.708  4602  4602 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 10:39:13.710   278   731 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (3:199 vsyncs) (5:1015)
,03-16 10:39:13.728   278   278 I SFPerfTracer:      triggers: (rate: 14:442) (compose: 0:1) (post: 0:1) (render: 0:2) (4:944 frames) (5:1016)
03-16 10:39:13.728   278   278 D SFPerfTracer:        layers: (3:12) (FocusedStackFrame (0xb7f96300): 0:11)* (DimLayer (0xb801d248): 0:4)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8020be0): 0:35)- (StatusBar (0xb7f9f548): 0:128) (NavigationBar (0xb7fa2578): 0:36) (com.android.systemui.ImageWallpaper (0xb803d3c0): 0:31)* (Starting com.motorola.ccc.ota (0xb80430d8): 0:30)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8044368): 0:51)* (Starting com.test.thalitest (0xb80430d8): 5:27) 
03-16 10:39:13.729  4602  4602 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-16 10:39:13.739  2527  2527 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-16 10:39:13.739  4602  4602 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 10:39:13.739  4602  4602 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 10:39:13.741  2527  2527 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-16 10:39:13.744  2527  2527 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 10:39:13.746  2527  2527 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 10:39:13.750  2527  2527 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 10:39:13.753  2527  2527 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-16 10:39:13.754  2527  2527 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-16 10:39:13.755  2527  2527 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 10:39:13.779   879  1240 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@38a058eb attribute=null, token = android.os.BinderProxy@7fa0bd2
,03-16 10:39:13.789  2527  3970 I global frequency: BcsDSCheckin.events found events 91
,03-16 10:39:13.790  2527  3970 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 10:39:13.819  4602  4672 D OpenGLRenderer: Render dirty regions requested: true
,03-16 10:39:13.832  4602  4602 D Atlas   : Validating map...
,03-16 10:39:13.838  4602  4641 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 10:39:13.847  1467  3870 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 10:39:13.858   879  1125 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,301
,03-16 10:39:13.870  2527  2527 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-16 10:39:13.873  2527  2527 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-16 10:39:13.874  2527  2527 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 10:39:13.878  2527  2527 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
03-16 10:39:13.880  2527  2527 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 10:39:13.890  2527  2527 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-16 10:39:13.891  2527  2527 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-16 10:39:13.892  2527  2527 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 10:39:13.905   879  1513 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{96cd5ce u0 com.test.thalitest/.MainActivity t9}
,03-16 10:39:13.921  4650  4676 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 10:39:13.924  2527  3970 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 10:39:13.926  4650  4675 I Gmail   : getAccountsCursor
,03-16 10:39:13.947  1803  1803 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 10:39:14.004  2527  4678 D MMApiWebService: doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,03-16 10:39:14.023   879  2288 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4680 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:14.131  4602  4700 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 10:39:14.131  4602  4700 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 10:39:14.135  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:14.173  4602  4602 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4602
,03-16 10:39:14.184  4650  4650 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 10:39:14.209   879   894 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 10:39:14.236  4650  4705 I Gmail   : Observing account changes for notifications
,03-16 10:39:14.255  4680  4680 I Exchange: EasService.onCreate
,03-16 10:39:14.268  4680  4710 I Exchange: RestartPingTask
,03-16 10:39:14.287  4680  4680 I Exchange: RestartPingsTask did not start any pings.
03-16 10:39:14.287  4680  4680 I Exchange: PSS stopIfIdle
03-16 10:39:14.287  4680  4680 I Exchange: PSS has no active accounts; stopping service.
,03-16 10:39:14.297  2527  4678 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,03-16 10:39:14.299  2527  4678 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 10:39:14.328  4650  4716 I Gmail   : getAccountsCursor
,03-16 10:39:14.342  1803  1803 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 10:39:14.354  4680  4680 I Exchange: onDestroy
,03-16 10:39:14.357   879  3940 I ActivityManager: Killing 4029:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 10:39:14.386  4602  4602 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 10:39:14.515  4602  4679 D jxcore_app_log: JniHelper::setJavaVM(0xb87c9310), pthread_self() = -1196567224
,03-16 10:39:14.521  4602  4679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 10:39:14.521  4602  4679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 10:39:14.521  4602  4679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 10:39:14.521  4602  4679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 10:39:14.521  4602  4679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 10:39:14.522  4602  4679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10cea048 added. We now have 1 listener(s)
,03-16 10:39:14.573   879   894 W libprocessgroup: failed to open /acct/uid_10090/pid_4029/cgroup.procs: No such file or directory
,03-16 10:39:14.578   879  1592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 10:39:14.584  4602  4679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-16 10:39:14.584  1803  1803 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 10:39:14.589  4602  4679 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 10:39:14.590  4515  4722 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
03-16 10:39:14.590  4602  4679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-16 10:39:14.590  4602  4679 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 10:39:14.591  4602  4679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 10:39:14.595   879  1502 I ActivityManager: Killing 4487:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 10:39:14.599  4602  4679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f85ac7 added. We now have 1 listener(s)
03-16 10:39:14.600  4602  4679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 10:39:14.606   879  1234 D WifiService: New client listening to asynchronous messages
,03-16 10:39:14.608  4602  4679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-16 10:39:14.615  4602  4679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-16 10:39:14.615  4602  4679 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-16 10:39:14.626  4650  4723 E SQLiteLog: (283) recovered 54 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 10:39:14.673   879  1539 W libprocessgroup: failed to open /acct/uid_10005/pid_4487/cgroup.procs: No such file or directory
,03-16 10:39:14.675   879  1091 I ActivityManager: Waited long enough for: ServiceRecord{2eb44a69 u0 com.motorola.ccc.checkin/.CheckinService}
03-16 10:39:14.675  4602  4679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 10:39:14.679   879  2288 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 10:39:14.679  4602  4679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-16 10:39:14.682  2527  2527 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 10:39:14.682  2527  2527 D 3CDM.DeviceAdminPushReceiver: Type: null
03-16 10:39:14.682  2527  2527 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-16 10:39:14.685  2527  2590 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 10:39:14.685  2527  2590 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
,03-16 10:39:14.685  2527  2590 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-16 10:39:14.685  2527  2590 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-16 10:39:14.685  2527  2590 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-16 10:39:14.685  2527  2590 D 3CDM.Service: blur.service.cred.locationToken = null
03-16 10:39:14.685  2527  2590 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-16 10:39:14.685  2527  2590 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-16 10:39:14.685  2527  2590 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-16 10:39:14.685  2527  2590 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 10:39:14.686  4602  4679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 10:39:14.686  4602  4679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 10:39:14.686  4602  4679 D io.jxcore.node.ConnectivityMonitor: start: OK
03-16 10:39:14.688  4602  4602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 10:39:14.690  4602  4602 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 10:39:14.690  4602  4602 E ActivityThread: Performing stop of activity that is not resumed: {com.test.thalitest/com.test.thalitest.MainActivity}
03-16 10:39:14.690  4602  4602 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.test.thalitest/com.test.thalitest.MainActivity}
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-16 10:39:14.690  4602  4602 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-16 10:39:14.692  2527  2590 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
03-16 10:39:14.692  4650  4725 I Gmail   : notifyAccountChanged
,03-16 10:39:14.701  4650  4675 I Gmail   : getAccountsCursor
,03-16 10:39:14.705  4650  4725 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 10:39:14.709  4650  4725 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 10:39:14.719  4650  4725 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 10:39:14.720  4650  4725 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 10:39:14.827  2955  2992 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-16 10:39:14.844   879  1592 I art     : Explicit concurrent mark sweep GC freed 9722(473KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 2.228ms total 135.403ms
,03-16 10:39:14.850  1803  1803 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 10:39:14.865  2527  2590 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-16 10:39:14.871  1953  4729 D LocationInitializer: Restart initialization of location
,03-16 10:39:14.876  1803  1803 D WearableService: callingUid 10016, callindPid: 1803
03-16 10:39:14.877  2399  2472 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-16 10:39:14.884   879  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=330, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4305648, SEQNUM=4327, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1616, POWER_SUPPLY_CHARGE_COUNTER=-128, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 10:39:14.891  1803  1803 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 10:39:14.901  1803  4728 E MDM     : [220] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 10:39:14.907  1803  1803 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 10:39:14.923  1803  2013 W GCoreFlp: No location to return for getLastLocation()
03-16 10:39:14.923  1803  4730 W FusedLocationProvider: location=null
,03-16 10:39:14.964   879  1513 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4733 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:14.976  2399  2472 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 10:39:14.995  1288  1288 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 10:39:14.995  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:15.014  4650  4676 I Gmail   : getAccountsCursor
,03-16 10:39:15.018  1803  1803 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 10:39:15.026  4733  4733 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 10:39:15.047  4602  4602 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 10:39:15.057  4733  4733 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@35091fce(com.android.providers.calendar.CalendarProvider2@3e77eef)
,03-16 10:39:15.065   879   879 V AlarmManager: done {3b69f9c4, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [6022ms]
,03-16 10:39:15.076  4733  4752 E SQLiteLog: (284) automatic index on view_events(_id)
,03-16 10:39:15.108   879  1498 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4753 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 10:39:15.130   326   326 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.832ms
,03-16 10:39:15.135  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:15.140   879  1569 I ActivityManager: Killing 4539:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,03-16 10:39:15.153   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 22.292ms
,03-16 10:39:15.174   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.244ms
,03-16 10:39:15.224   879  1649 W libprocessgroup: failed to open /acct/uid_10096/pid_4539/cgroup.procs: No such file or directory
,03-16 10:39:15.242  4753  4753 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 10:39:15.415  4753  4779 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 10:39:15.416  4753  4779 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 10:39:15.418  4753  4779 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 10:39:15.418  4753  4779 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 10:39:15.436  4753  4779 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 10:39:15.436  4753  4779 I Babel_SMS: MmsConfig.loadFromResources
,03-16 10:39:15.444  4753  4779 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-16 10:39:15.445  4753  4779 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 10:39:15.552  4753  4753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 10:39:15.562  4753  4753 I Babel_Crash: startup - clean
,03-16 10:39:15.580  4753  4786 I Babel   : deleted: false for 0
,03-16 10:39:15.741   879  1592 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4788 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:15.839  4753  4753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 10:39:15.854  4753  4753 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 10:39:15.866  4753  4753 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 10:39:15.937  4753  4753 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 10:39:15.944  4753  4753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 10:39:15.946  4753  4753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 10:39:15.951  4753  4753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 10:39:15.954  4602  4727 W jxcore-log: Initializing JXcore engine
03-16 10:39:15.954  4602  4727 W jxcore-log: JXcore engine is ready
,03-16 10:39:15.958  4753  4753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 10:39:15.962   879  2288 I ActivityManager: Killing 4585:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-16 10:39:16.024  4727  4727 W Thread-499: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5883]" dev="sockfs" ino=5883 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-16 10:39:16.034  4727  4727 W Thread-499: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 10:39:16.034  4727  4727 W Thread-499: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9483]" dev="sockfs" ino=9483 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-16 10:39:16.034  4727  4727 W Thread-499: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[20847]" dev="sockfs" ino=20847 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-16 10:39:16.058  4602  4727 W jxcore-log: Starting JXcore engine
,03-16 10:39:16.073   879  1498 W libprocessgroup: failed to open /acct/uid_10055/pid_4585/cgroup.procs: No such file or directory
,03-16 10:39:16.078  4753  4753 I vclib   : onServiceConnected
,03-16 10:39:16.078  4753  4753 W Babel   : Attempted to change video mute state without an active call.
,03-16 10:39:16.091   879  1091 I ActivityManager: Waited long enough for: ServiceRecord{3106bb59 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-16 10:39:16.113  4733  4733 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 10:39:16.113  4733  4733 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 10:39:16.117   879  1568 I ActivityManager: Killing 4650:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 10:39:16.137  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:16.197  2527  4678 D MMApiWSBase: doRequest(): v1/cs/checkin resp length: 4
,03-16 10:39:16.199  2527  4678 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
03-16 10:39:16.200  2527  4678 D CCE     : AppWSProxy - sendAIDLWSResponse() sending reponse
,03-16 10:39:16.209  2527  4678 I global frequency: BcsCore.status() called with error code=ERROR_OK
,03-16 10:39:16.210  2527  4678 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 10:39:16.223  4602  4727 W jxcore-log: Platform android
03-16 10:39:16.223  4602  4727 W jxcore-log: 
03-16 10:39:16.223  4602  4727 W jxcore-log: Process ARCH arm
03-16 10:39:16.223  4602  4727 W jxcore-log: 
,03-16 10:39:16.233   879  1649 W libprocessgroup: failed to open /acct/uid_10063/pid_4650/cgroup.procs: No such file or directory
,03-16 10:39:16.243   879  1510 D CheckinProvider: 91 events delete 6 left
,03-16 10:39:16.272   879  2288 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4814 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 10:39:16.344   879  1649 I ActivityManager: Killing 4680:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 10:39:16.373  2527  4678 I global frequency: BcsDSCheckin.events found events 0
03-16 10:39:16.374  2527  4678 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 10:39:16.394  2527  4678 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 10:39:16.396  2527  4678 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 10:39:16.483   879  1513 W libprocessgroup: failed to open /acct/uid_10060/pid_4680/cgroup.procs: No such file or directory
,03-16 10:39:16.485  2527  2527 I global frequency: BcsTimer.onReceive checkin completed (1694199910:ERROR_OK)
,03-16 10:39:16.486  2527  2527 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 10:39:16.587  4602  4727 I jxcore-log: JXcore Cordova bridge is ready!
03-16 10:39:16.587  4602  4727 I jxcore-log: 
03-16 10:39:16.588  4602  4727 W jxcore-log: JXcore engine is started
,03-16 10:39:16.594  4602  4679 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 10:39:16.596  4602  4602 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 10:39:16.604  4602  4727 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 10:39:16.604  4602  4727 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 10:39:16.611  4602  4602 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 10:39:16.611  4602  4602 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 10:39:16.614   879  1419 I ActivityManager: Killing 4515:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 10:39:16.704   879   895 W libprocessgroup: failed to open /acct/uid_10008/pid_4515/cgroup.procs: No such file or directory
03-16 10:39:16.704  4602  4679 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 92ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 10:39:16.711  2527  2547 W DataUsage: invalid counter update blocked: 'err' by 0
,03-16 10:39:16.714  2527  2547 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 10:39:16.731  4602  4602 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1143081d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:39:16.731  4602  4602 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1143081d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 10:39:16.731  4602  4602 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 10:39:16.733  4602  4602 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@275178f4 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:39:16.733  4602  4602 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@275178f4 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 10:39:16.733  4602  4602 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 10:39:16.818   879  1521 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4852 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 10:39:16.926   879  1419 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4872 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 10:39:16.953  4844  4844 D AndroidRuntime: 
03-16 10:39:16.953  4844  4844 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 10:39:16.957   879  1569 I ActivityManager: Killing 4733:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 10:39:16.957  4844  4844 D AndroidRuntime: CheckJNI is OFF
,03-16 10:39:17.074   879  1502 W libprocessgroup: failed to open /acct/uid_10005/pid_4733/cgroup.procs: No such file or directory
,03-16 10:39:17.095  4753  4753 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 10:39:17.095  4753  4753 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 10:39:17.111  4844  4844 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 10:39:17.125   879  2288 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4902 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:17.127   879  1091 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-16 10:39:17.127   879  1091 I ActivityManager: Killing 4602:com.test.thalitest/u0a109 (adj 11): stop com.test.thalitest
,03-16 10:39:17.160  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:17.162   879  1234 D WifiService: Client connection lost with reason: 4
,03-16 10:39:17.178   879  1142 W PackageSettings: Skipping PackageSetting{232339b4 com.example.hello/10568} due to missing metadata
,03-16 10:39:17.204  4753  4753 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 10:39:17.223  4872  4910 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 10:39:17.261  4753  4753 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 10:39:17.262  4753  4753 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 10:39:17.337   879  1568 W ActivityManager: Spurious death for ProcessRecord{20a7c3fe 4602:com.test.thalitest/u0a109}, curProc for 4602: null
,03-16 10:39:17.340   879  1142 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-16 10:39:17.354  4902  4902 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 10:39:17.360  1412  1412 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-16 10:39:17.369   879  1223 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 10:39:17.380  1412  4924 I Keyboard.Facilitator.DecoderInitializer: run()
03-16 10:39:17.390  1412  4924 I Decoder : createOrResetDecoder
,03-16 10:39:17.395  1803  2031 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 10:39:17.403  2955  2955 I art     : Explicit concurrent mark sweep GC freed 9832(1651KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/12MB, paused 950us total 50.426ms
,03-16 10:39:17.440  1570  1570 I art     : Explicit concurrent mark sweep GC freed 2162(117KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 609us total 84.838ms
,03-16 10:39:17.457   879  3940 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4926 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:17.475  4902  4902 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@35091fce(com.android.providers.calendar.CalendarProvider2@3e77eef)
,03-16 10:39:17.479  1803  1803 I ConfigService: onCreate
,03-16 10:39:17.515   879  1498 I ActivityManager: Killing 4141:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-16 10:39:17.549  4926  4926 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 10:39:17.549  4926  4926 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 10:39:17.549  4926  4926 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 10:39:17.550   879   879 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 10:39:17.550   879   879 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 10:39:17.550  4926  4926 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 10:39:17.551  1412  4924 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-16 10:39:17.610  1412  4924 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-16 10:39:17.613  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-16 10:39:17.613  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-16 10:39:17.651   879  1142 I art     : Explicit concurrent mark sweep GC freed 24919(1758KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 1.675ms total 188.309ms
,03-16 10:39:17.688  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-16 10:39:17.688  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-16 10:39:17.699  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-16 10:39:17.699  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-16 10:39:17.701  1412  4924 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-16 10:39:17.703  1412  4924 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-16 10:39:17.703  1412  4924 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-16 10:39:17.704  1412  4924 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-16 10:39:17.704  1412  4924 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-16 10:39:17.704  1412  4924 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-16 10:39:17.743  4844  4844 D AndroidRuntime: Shutting down VM
,03-16 10:39:17.747   879  1521 W libprocessgroup: failed to open /acct/uid_10016/pid_4141/cgroup.procs: No such file or directory
,03-16 10:39:17.754  1570  1570 I Launcher: Deferring update until onResume
,03-16 10:39:17.792   879  1142 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4948 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-16 10:39:17.818  4814  4963 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-16 10:39:17.821  1570  1570 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1cd55aa6 new=com.google.android.velvet.VelvetApplication@1cd55aa6
,03-16 10:39:17.873  1953  4972 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 10:39:17.877  1953  4972 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 10:39:17.881   879  1502 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4973 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:17.966  1953  4972 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 10:39:17.981  1953  2029 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 10:39:17.998  1288  1288 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 10:39:17.998  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 10:39:18.013  4973  4973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 10:39:18.079  4814  4963 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 260 ms] updated apps [took 260 ms] 
,03-16 10:39:18.081   879  3940 I ActivityManager: Killing 4788:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 10:39:18.103   879  1569 W libprocessgroup: failed to open /acct/uid_10088/pid_4788/cgroup.procs: No such file or directory
,03-16 10:39:18.358   879  1251 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
,03-16 10:39:18.437   879  1251 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-16 10:39:18.449   879  1251 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
03-16 10:39:18.449   879  1251 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-16 10:39:18.477   879  1498 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5007 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 10:39:18.583   879  1240 I ActivityManager: Killing 3104:com.google.process.gapps/u0a16 (adj 15): empty #7
,03-16 10:39:18.662  1803  1827 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5570797)
,03-16 10:39:18.663  1803  1827 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@286d84)
,03-16 10:39:18.664  1803  1832 I art     : Explicit concurrent mark sweep GC freed 43553(2MB) AllocSpace objects, 34(544KB) LOS objects, 40% free, 13MB/22MB, paused 1.022ms total 98.242ms
,03-16 10:39:18.668  1803  1827 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d7a8633)
03-16 10:39:18.669  1803  1827 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3080ddf0)
,03-16 10:39:18.669  1803  1827 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21dcf69)
,03-16 10:39:18.671  1803  1827 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10197dee)
,03-16 10:39:18.673   879  1539 W libprocessgroup: failed to open /acct/uid_10016/pid_3104/cgroup.procs: No such file or directory
,03-16 10:39:18.690  1412  4924 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-16 10:39:18.690  1412  4924 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-16 10:39:18.699  1412  4924 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-16 10:39:18.699  1412  4924 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-16 10:39:18.708  1412  4924 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-16 10:39:18.708  1412  4924 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-16 10:39:18.708  1412  4924 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-16 10:39:18.708  1412  4924 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-16 10:39:18.747  4902  4902 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 10:39:18.747  4902  4902 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 10:39:18.763   879  1521 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5031 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 10:39:18.774   879  1592 I ActivityManager: Killing 4852:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 10:39:18.783   879  1569 W libprocessgroup: failed to open /acct/uid_10019/pid_4852/cgroup.procs: No such file or directory
,03-16 10:39:19.047   278   696 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
