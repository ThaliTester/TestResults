#### Test 63008475d624ed8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-16 12:21:20.600  5582  5582 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
--------- beginning of system
03-16 12:21:20.634   882  1223 V AlarmManager: send {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN}
03-16 12:21:20.645  5582  5582 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7042-7044)
03-16 12:21:20.645  5582  5582 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 12:21:20.654  5582  5582 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ce169e6}
03-16 12:21:20.656  5582  5582 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:21:20.661  5582  5582 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 12:21:20.682   882  1223 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService: pid=5637 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-16 12:21:20.682   882  1223 V AlarmManager: send {137be9df, *alarm*:send_events}
03-16 12:21:20.682   882   882 V AlarmManager: done {137be9df, *alarm*:send_events} [49ms]
03-16 12:21:20.694  5582  5582 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 12:21:20.697  5582  5582 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 12:21:20.700  5582  5582 E SysUtils: ApplicationContext is null in ApplicationStatus
03-16 12:21:20.706   321   321 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 23.624ms
03-16 12:21:20.734   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 26.439ms
03-16 12:21:20.763   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 28.611ms
03-16 12:21:20.842  5582  5582 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-16 12:21:20.849  5582  5582 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 12:21:20.850  5582  5582 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 12:21:20.851  5582  5582 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 12:21:20.851  5582  5582 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 12:21:20.851  5582  5582 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 12:21:20.851  5582  5582 I Adreno-EGL: Local Branch: 
03-16 12:21:20.851  5582  5582 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 12:21:20.851  5582  5582 I Adreno-EGL: Local Patches: NONE
03-16 12:21:20.851  5582  5582 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
03-16 12:21:20.960  5582  5667 W AudioManagerAndroid: Requires BLUETOOTH permission
03-16 12:21:21.003  5582  5582 I NSApplication: Starting up...
03-16 12:21:21.072   882   898 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5677 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:21:21.075   882   898 I ActivityManager: Killing 4480:com.android.defcontainer/u0a10 (adj 15): empty #7
03-16 12:21:21.152   882  1530 W libprocessgroup: failed to open /acct/uid_10010/pid_4480/cgroup.procs: No such file or directory
03-16 12:21:21.152  5653  5653 D AndroidRuntime: 
03-16 12:21:21.152  5653  5653 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 12:21:21.156  5653  5653 D AndroidRuntime: CheckJNI is OFF
03-16 12:21:21.340   882  1586 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5708 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:21:21.343  1962  4557 I CheckinService: Done disabling old GoogleServicesFramework version
03-16 12:21:21.419   882  1431 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5726 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
03-16 12:21:21.457  5708  5708 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-16 12:21:21.469  5653  5653 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 12:21:21.481   882  1605 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-16 12:21:21.500   279   391 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
03-16 12:21:21.519  1482  5148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 12:21:21.531  5653  5653 D AndroidRuntime: Shutting down VM
03-16 12:21:21.542  5708  5708 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@43b6f67(com.android.providers.calendar.CalendarProvider2@39ea0114)
03-16 12:21:21.569   882  1530 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5761 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 12:21:21.592   882  1309 I ActivityManager: Killing 5478:com.android.mms/u0a23 (adj 15): empty #7
03-16 12:21:21.628  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 12:21:21.633   882  1493 W libprocessgroup: failed to open /acct/uid_10023/pid_5478/cgroup.procs: No such file or directory
03-16 12:21:21.638  1482  5148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 12:21:21.708   882  1665 I ActivityManager: Killing 5513:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 12:21:21.752   882   898 W libprocessgroup: failed to open /acct/uid_10035/pid_5513/cgroup.procs: No such file or directory
,03-16 12:21:21.805  3640  3640 D EmailService.MarketingOptInSetter: received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-16 12:21:21.811  3640  3794 I SundryService: onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,03-16 12:21:21.813  3640  3794 E SQLiteLog: (284) automatic index on registration(APP_ID)
,03-16 12:21:21.816  3640  3794 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=1
,03-16 12:21:21.832   882  1253 I ActivityManager: Killing 5204:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 12:21:21.835  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 12:21:21.836  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:21.840  3640  5783 I PushService: started with background data enabled, making sure notification mechanism is enabled
,03-16 12:21:21.911  5761  5761 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 12:21:21.921   882  1253 I ActivityManager: Killing 5544:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,03-16 12:21:21.955   882  1665 W libprocessgroup: failed to open /acct/uid_10070/pid_5204/cgroup.procs: No such file or directory
,03-16 12:21:21.960   882  1605 W libprocessgroup: failed to open /acct/uid_10088/pid_5544/cgroup.procs: No such file or directory
,03-16 12:21:21.993  5761  5761 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 8381-8392)
03-16 12:21:21.994  1482  1482 D Central_PollingManager: wake lock released
,03-16 12:21:21.995  5761  5761 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:21:22.032  5761  5761 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30248fb2}
,03-16 12:21:22.033  5761  5761 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:21:22.033  5761  5761 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 12:21:22.040   882  1253 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5787 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 12:21:22.048  3640  5254 E global frequency: no tags to log
,03-16 12:21:22.053  5761  5761 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 12:21:22.054  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:21:22.055  5761  5761 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 12:21:22.062  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:21:22.078  5761  5761 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 12:21:22.084  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:21:22.087  1561  1578 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 12:21:22.093  5761  5761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 12:21:22.093  5761  5761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 12:21:22.094  5761  5761 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 12:21:22.094  5761  5761 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 12:21:22.094  5761  5761 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 12:21:22.094  5761  5761 I Adreno-EGL: Local Branch: 
03-16 12:21:22.094  5761  5761 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 12:21:22.094  5761  5761 I Adreno-EGL: Local Patches: NONE
03-16 12:21:22.094  5761  5761 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 12:21:22.109  5787  5787 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 12:21:22.143   279   279 I SFPerfTracer:      triggers: (rate: 6:410) (compose: 0:6) (post: 0:2) (render: 0:17) (6:1160 frames) (7:1247)
03-16 12:21:22.143   279   279 D SFPerfTracer:        layers: (5:12) (FocusedStackFrame (0xb7d9a198): 0:12)* (DimLayer (0xb7e3f690): 0:9)* (DimLayer (0xb7da4e30): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7da6b48): 0:34)- (StatusBar (0xb7e19e90): 0:139) (NavigationBar (0xb7e1c280): 0:79) (com.android.systemui.ImageWallpaper (0xb7e1f078): 0:27)* (Starting com.motorola.ccc.ota (0xb7e21170): 0:40)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7e52530): 7:53) (Starting com.test.thalitest (0xb7e57520): 7:11) 
,03-16 12:21:22.168  1482  5411 I art     : Explicit concurrent mark sweep GC freed 4052(171KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 872us total 32.395ms
,03-16 12:21:22.183   882  1118 D BluetoothManagerService: Message: 20
03-16 12:21:22.183   882  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3267b1f2:true
,03-16 12:21:22.237  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:21:22.249   882  1551 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5823 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,03-16 12:21:22.257  3640  3640 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:21:22.284  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:21:22.287  1561  1578 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 12:21:22.308  5823  5823 I System.out: TimeService: Loaded Library 
,03-16 12:21:22.310  5823  5823 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458127282308
03-16 12:21:22.310  5823  5823 D         : TimeServiceNative: User Time to be set is 1458127282310
,03-16 12:21:22.310  5823  5823 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-16 12:21:22.310  5823  5823 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-16 12:21:22.310  5823  5823 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458127282310
,03-16 12:21:22.313  5823  5823 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-16 12:21:22.315   333   831 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-16 12:21:22.316   333  5841 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458127282310
03-16 12:21:22.316   333  5841 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458127282310, operation = 0
03-16 12:21:22.316   333  5841 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/16/116 11:19:32
03-16 12:21:22.317   333  5841 D QC-time-services: Daemon:Value read from RTC seconds = 1458127172000
,03-16 12:21:22.317   333  5841 D QC-time-services: Daemon:new time 1458127282310 
03-16 12:21:22.317   333  5841 D QC-time-services: Daemon: delta 110310 genoff 110310 
03-16 12:21:22.317   333  5841 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 110310 to memory
03-16 12:21:22.317   333  5841 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-16 12:21:22.317   333  5841 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 12:21:22.377   882  1598 I ActivityManager: Killing 5582:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,03-16 12:21:22.379   333  5841 D QC-time-services: Updating the TOD offset
03-16 12:21:22.379   333  5841 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 110310 to memory
03-16 12:21:22.379   333  5841 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-16 12:21:22.379   333  5841 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 12:21:22.417   333  5841 E QC-time-services: Daemon:Update to modem bit set
03-16 12:21:22.417   333  5841 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-16 12:21:22.417   333  5841 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743757744861926
,03-16 12:21:22.417  5823  5823 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-16 12:21:22.421   333   829 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-16 12:21:22.421   333   831 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-16 12:21:22.422  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:21:22.437  5761  5761 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 12:21:22.455  5761  5761 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-16 12:21:22.462   882  1551 I art     : Explicit concurrent mark sweep GC freed 13288(659KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.800ms total 132.642ms
,03-16 12:21:22.495  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:21:22.504  3640  3640 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:21:22.571   882   897 W libprocessgroup: failed to open /acct/uid_10081/pid_5582/cgroup.procs: No such file or directory
,03-16 12:21:22.572  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 12:21:22.572  5761  5761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:21:22.573   882  1598 I ActivityManager: Killing 5637:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 12:21:22.622   882  1431 W libprocessgroup: failed to open /acct/uid_10039/pid_5637/cgroup.procs: No such file or directory
,03-16 12:21:22.629  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:22.639  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:21:22.643  1561  3427 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 12:21:22.661  5708  5708 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 12:21:22.662  5708  5708 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 12:21:22.664  5761  5848 D OpenGLRenderer: Render dirty regions requested: true
,03-16 12:21:22.666   882  1665 I ActivityManager: Killing 5677:com.android.chrome/u0a52 (adj 15): empty #7
,03-16 12:21:22.677  5761  5761 D Atlas   : Validating map...
,03-16 12:21:22.719  1482  1513 I art     : Explicit concurrent mark sweep GC freed 3803(149KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 468us total 29.270ms
,03-16 12:21:22.754   882  1309 W libprocessgroup: failed to open /acct/uid_10052/pid_5677/cgroup.procs: No such file or directory
,03-16 12:21:22.756  5761  5815 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 12:21:22.791   279   724 I SFPerfTracer:      triggers: (rate: 0:1) (0 sw vsyncs) (0 skipped) (20:564 vsyncs) (22:1269)
,03-16 12:21:22.798  5761  5848 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 12:21:22.805  5761  5848 D OpenGLRenderer: Enabling debug mode 0
,03-16 12:21:22.828  3640  3640 I art     : Explicit concurrent mark sweep GC freed 17605(1061KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.454ms total 79.444ms
,03-16 12:21:22.842  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:21:22.860  3640  3640 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:21:22.865  3640  5254 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:21:22.867  1422  1422 I Keyboard.Facilitator: onFinishInput()
,03-16 12:21:22.870  3640  5254 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-16 12:21:22.871  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:21:22.872  3640  5254 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-16 12:21:22.873  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:21:22.875  3640  5254 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-16 12:21:22.878   882  1120 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1345
03-16 12:21:22.878   882  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s345ms
,03-16 12:21:22.897  3640  5254 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-16 12:21:22.932  5761  5854 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 12:21:22.932  5761  5854 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 12:21:22.968  5761  5761 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5761
,03-16 12:21:22.986   882  1431 I ActivityManager: Killing 5726:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 12:21:23.051   882  1530 W libprocessgroup: failed to open /acct/uid_10019/pid_5726/cgroup.procs: No such file or directory
,03-16 12:21:23.109  3640  5254 I global frequency: BcsDSCheckin.events found events 115
,03-16 12:21:23.111  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:21:23.130   882  1586 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5857 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-16 12:21:23.165  5761  5761 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 12:21:23.195  3640  5254 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:21:23.239  3640  5874 D MMApiWebService: doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,03-16 12:21:23.291  3640  5874 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,03-16 12:21:23.293  3640  5874 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 12:21:23.300  5857  5857 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-16 12:21:23.300  5857  5857 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 12:21:23.300  5857  5857 I GAv4    :   adb logcat -s GAv4
,03-16 12:21:23.331  5857  5857 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:21:23.365  5857  5857 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:21:23.372  5857  5878 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:21:23.500   882  1586 I ActivityManager: Killing 5708:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 12:21:23.583  5761  5848 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,03-16 12:21:23.583  5761  5848 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 12:21:23.592   882   898 W libprocessgroup: failed to open /acct/uid_10005/pid_5708/cgroup.procs: No such file or directory
,03-16 12:21:23.609  3640  3640 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,03-16 12:21:23.612  3640  3640 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
,03-16 12:21:23.614  3640  3640 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
,03-16 12:21:23.620   882  1530 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,03-16 12:21:23.643  1482  5148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 12:21:23.651  5761  5852 D jxcore_app_log: JniHelper::setJavaVM(0xb7bf8310), pthread_self() = -1208193472
,03-16 12:21:23.673  5761  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 12:21:23.673  5761  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 12:21:23.673  5761  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 12:21:23.673  5761  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 12:21:23.673  5761  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 12:21:23.673  5761  5852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d35ca5e added. We now have 1 listener(s)
03-16 12:21:23.673   882  1586 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 12:21:23.677  5761  5852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-16 12:21:23.679  5761  5852 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 12:21:23.680  5761  5852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 12:21:23.680  5761  5852 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 12:21:23.680  5761  5852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 12:21:23.693  5761  5852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f4455 added. We now have 1 listener(s)
03-16 12:21:23.693  5761  5852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 12:21:23.701  1962  5892 D LocationInitializer: Restart initialization of location
03-16 12:21:23.702   882  1247 D WifiService: New client listening to asynchronous messages
,03-16 12:21:23.704  1757  1757 D WearableService: callingUid 10016, callindPid: 1757
,03-16 12:21:23.705  5761  5852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-16 12:21:23.708  1757  1757 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 12:21:23.714  5761  5852 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-16 12:21:23.714  5761  5852 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-16 12:21:23.723  5761  5852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 12:21:23.723  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:23.723   882  1605 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-16 12:21:23.724  1757  5890 E MDM     : [209] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 12:21:23.727  5761  5852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 12:21:23.737  5761  5852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 12:21:23.737  5761  5852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 12:21:23.737  5761  5852 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 12:21:23.777   882  1598 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5898 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:23.813  1757  2250 W GCoreFlp: No location to return for getLastLocation()
,03-16 12:21:23.813  1757  5894 W FusedLocationProvider: location=null
,03-16 12:21:23.873  3640  3640 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-16 12:21:23.876  3640  3640 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-16 12:21:23.876  3640  3640 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 12:21:23.878  3640  3640 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
03-16 12:21:23.879  3640  3640 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 12:21:23.882  3640  3640 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 12:21:23.883  3640  3640 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-16 12:21:23.884  3640  3640 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 12:21:23.939  1422  1422 I Keyboard.Facilitator: onFinishInput()
,03-16 12:21:24.077  5898  5919 I Gmail   : getAccountsCursor
03-16 12:21:24.085  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:24.089  5898  5920 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 12:21:24.096  1482  5148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 12:21:24.111   882  1120 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,491
,03-16 12:21:24.115  5761  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 12:21:24.117  5761  5761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 12:21:24.120  5761  5761 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 12:21:24.121  5761  5761 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-16 12:21:24.128  3640  3640 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-16 12:21:24.133  3640  3640 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-16 12:21:24.135  3640  3640 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 12:21:24.137  3640  3640 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 12:21:24.144  3640  3640 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 12:21:24.150  3640  3640 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 12:21:24.153   882  1586 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{c8762eb u0 com.test.thalitest/.MainActivity t9}
,03-16 12:21:24.154  3640  3640 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-16 12:21:24.155  3640  3640 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 12:21:24.224   882  1544 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5922 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:24.510   882  1598 I art     : Explicit concurrent mark sweep GC freed 8748(407KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 3.675ms total 154.671ms
,03-16 12:21:24.518   882  1665 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 12:21:24.527  5898  5942 I Gmail   : Observing account changes for notifications
,03-16 12:21:24.533  5922  5922 I Exchange: EasService.onCreate
,03-16 12:21:24.546  5922  5944 I Exchange: RestartPingTask
,03-16 12:21:24.551  5898  5898 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 12:21:24.563  5922  5922 I Exchange: RestartPingsTask did not start any pings.
03-16 12:21:24.563  5922  5922 I Exchange: PSS stopIfIdle
03-16 12:21:24.563  5922  5922 I Exchange: PSS has no active accounts; stopping service.
,03-16 12:21:24.593   279   279 I SFPerfTracer:      triggers: (rate: 6:412) (compose: 0:6) (post: 0:2) (render: 0:17) (7:1246 frames) (8:1350)
03-16 12:21:24.593   279   279 D SFPerfTracer:        layers: (5:12) (FocusedStackFrame (0xb7d9a198): 0:17)* (DimLayer (0xb7e3f690): 0:9)* (DimLayer (0xb7da4e30): 0:7) (StatusBar (0xb7e19e90): 0:157) (NavigationBar (0xb7e1c280): 0:91) (com.android.systemui.ImageWallpaper (0xb7e1f078): 0:27)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7e52530): 0:55)- (Starting com.test.thalitest (0xb7e57520): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7e558e8): 8:66) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7e66988): 8:22) 
,03-16 12:21:24.612  5922  5922 I Exchange: onDestroy
,03-16 12:21:24.614   882  1605 I ActivityManager: Killing 5281:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 12:21:24.862   882  1530 W libprocessgroup: failed to open /acct/uid_10090/pid_5281/cgroup.procs: No such file or directory
,03-16 12:21:24.870  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:24.871  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:24.880  5898  5949 I Gmail   : getAccountsCursor
,03-16 12:21:24.881  3640  5874 D MMApiWSBase: doRequest(): v1/cs/checkin resp length: 4
03-16 12:21:24.881  5761  5761 E ActivityThread: Performing stop of activity that is not resumed: {com.test.thalitest/com.test.thalitest.MainActivity}
03-16 12:21:24.881  5761  5761 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.test.thalitest/com.test.thalitest.MainActivity}
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-16 12:21:24.881  5761  5761 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-16 12:21:24.884  3640  5874 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,03-16 12:21:24.885  3640  5874 D CCE     : AppWSProxy - sendAIDLWSResponse() sending reponse
,03-16 12:21:24.896  3640  5874 I global frequency: BcsCore.status() called with error code=ERROR_OK
03-16 12:21:24.896  3640  5874 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 12:21:24.898  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:24.923  3640  3794 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
,03-16 12:21:24.923  3640  3794 D WaitableIntentService: setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
03-16 12:21:24.923  3640  3794 D SundryService: onHandleIntent(): isWaitEnabled=false
03-16 12:21:24.923  3640  3794 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-16 12:21:24.929  5787  5959 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
,03-16 12:21:24.930  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 12:21:24.931  3640  3640 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-16 12:21:24.934  3640  3640 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,03-16 12:21:24.934   882  1431 I ActivityManager: Killing 5823:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
03-16 12:21:24.934  3640  3640 D 3CDM.DeviceAdminPushReceiver: Type: null
03-16 12:21:24.934  3640  3640 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-16 12:21:24.942  5761  5897 W jxcore-log: Initializing JXcore engine
03-16 12:21:24.942  5761  5897 W jxcore-log: JXcore engine is ready
,03-16 12:21:24.953   882  4024 D CheckinProvider: 115 events delete 6 left
,03-16 12:21:24.983  3640  5874 I global frequency: BcsDSCheckin.events found events 0
,03-16 12:21:24.984  3640  5874 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:21:24.986  3640  5874 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-16 12:21:24.988  3640  5874 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:21:25.012  5897  5897 W Thread-485: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[7344]" dev="sockfs" ino=7344 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 12:21:25.012  5897  5897 W Thread-485: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 12:21:25.012  5897  5897 W Thread-485: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6842]" dev="sockfs" ino=6842 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 12:21:25.012  5897  5897 W Thread-485: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[21146]" dev="sockfs" ino=21146 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-16 12:21:25.043  5761  5897 W jxcore-log: Starting JXcore engine
,03-16 12:21:25.052   882  1512 W libprocessgroup: failed to open /acct/uid_10096/pid_5823/cgroup.procs: No such file or directory
,03-16 12:21:25.053   882  1091 I ActivityManager: Waited long enough for: ServiceRecord{77fcf7d u0 com.motorola.ccc.checkin/.CheckinService}
03-16 12:21:25.055  3640  3640 I global frequency: BcsTimer.onReceive checkin completed (-664760081:ERROR_OK)
03-16 12:21:25.056  3640  3640 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 12:21:25.059  3640  3790 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 12:21:25.060  3640  3790 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
03-16 12:21:25.060  3640  3790 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-16 12:21:25.060  3640  3790 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-16 12:21:25.060  3640  3790 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-16 12:21:25.060  3640  3790 D 3CDM.Service: blur.service.cred.locationToken = null
03-16 12:21:25.060  3640  3790 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-16 12:21:25.060  3640  3790 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-16 12:21:25.060  3640  3790 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-16 12:21:25.060  3640  3790 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-16 12:21:25.077  3640  3790 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-16 12:21:25.096  5898  5960 E SQLiteLog: (283) recovered 72 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 12:21:25.117   882  1586 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5962 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 12:21:25.161   882   897 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5968 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:25.180   321   321 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 20.689ms
,03-16 12:21:25.200   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 19.615ms
,03-16 12:21:25.221   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.981ms
,03-16 12:21:25.254  5898  5961 I Gmail   : notifyAccountChanged
,03-16 12:21:25.257  4266  4293 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
03-16 12:21:25.258  5898  5950 I Gmail   : getAccountsCursor
,03-16 12:21:25.268  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:25.270  3640  3790 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-16 12:21:25.279  5898  5961 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:21:25.290  5898  5961 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 12:21:25.290  5968  5968 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 12:21:25.298  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 12:21:25.300  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:25.308  5898  5961 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 12:21:25.310  5898  5961 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 12:21:25.328  5761  5897 W jxcore-log: Platform android
03-16 12:21:25.328  5761  5897 W jxcore-log: 
,03-16 12:21:25.329  5761  5897 W jxcore-log: Process ARCH arm
03-16 12:21:25.329  5761  5897 W jxcore-log: 
,03-16 12:21:25.336  5968  5968 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@43b6f67(com.android.providers.calendar.CalendarProvider2@39ea0114)
,03-16 12:21:25.393  3640  3714 W DataUsage: invalid counter update blocked: 'err' by 0
,03-16 12:21:25.395  3640  3714 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 12:21:25.434  4420  4585 I art     : Explicit concurrent mark sweep GC freed 2910(116KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 500us total 28.095ms
,03-16 12:21:25.449  5898  5919 I Gmail   : getAccountsCursor
,03-16 12:21:25.453  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:25.636   882  1253 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6006 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 12:21:25.659  5761  5897 I jxcore-log: JXcore Cordova bridge is ready!
03-16 12:21:25.659  5761  5897 I jxcore-log: 
,03-16 12:21:25.660  5761  5897 W jxcore-log: JXcore engine is started
,03-16 12:21:25.664  5761  5852 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 12:21:25.675  5761  5897 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 12:21:25.675  5761  5897 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 12:21:25.682  5761  5761 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-16 12:21:25.684   882  1493 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6012 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 12:21:25.685   882  1493 I ActivityManager: Killing 5262:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-16 12:21:25.763   882  1309 I ActivityManager: Killing 5857:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-16 12:21:25.841   882   897 W libprocessgroup: failed to open /acct/uid_10016/pid_5262/cgroup.procs: No such file or directory
,03-16 12:21:25.841  5761  5852 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 159ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 12:21:25.850   882  1551 I ActivityManager: Killing 5922:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 12:21:25.885   882  1512 W libprocessgroup: failed to open /acct/uid_10055/pid_5857/cgroup.procs: No such file or directory
,03-16 12:21:25.886   882  1665 W libprocessgroup: failed to open /acct/uid_10060/pid_5922/cgroup.procs: No such file or directory
,03-16 12:21:25.887   882  1091 I ActivityManager: Waited long enough for: ServiceRecord{3139fd30 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-16 12:21:25.915  6012  6012 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:21:25.919  5761  5761 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@18902e6a that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:21:25.919  5761  5761 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@18902e6a that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 12:21:25.919  5761  5761 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 12:21:25.920  5761  5761 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@33843f5b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:21:25.920  5761  5761 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@33843f5b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 12:21:25.920  5761  5761 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 12:21:25.941   279   724 I SFPerfTracer:      triggers: (rate: 0:1) (0 sw vsyncs) (0 skipped) (58:660 vsyncs) (60:1373)
,03-16 12:21:26.099  6012  6050 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 12:21:26.099  6012  6050 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 12:21:26.101  6012  6050 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 12:21:26.101  6012  6050 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 12:21:26.130  6012  6050 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,03-16 12:21:26.130  6012  6050 I Babel_SMS: MmsConfig.loadFromResources
,03-16 12:21:26.132  6012  6050 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 12:21:26.133  6012  6050 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 12:21:26.191  6012  6012 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 12:21:26.200  6012  6012 I Babel_Crash: startup - clean
,03-16 12:21:26.221  6012  6053 I Babel   : deleted: false for 0
,03-16 12:21:26.359   882  1605 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6055 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:26.378  6012  6012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:21:26.379  5968  5968 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 12:21:26.379  5968  5968 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 12:21:26.382   882  1253 I ActivityManager: Killing 5898:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 12:21:26.402  6012  6012 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 12:21:26.406  6012  6012 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 12:21:26.430  6012  6012 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 12:21:26.436  6012  6012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 12:21:26.437  6012  6012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 12:21:26.440  6012  6012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:21:26.444  6012  6012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:21:26.541   882   897 W libprocessgroup: failed to open /acct/uid_10063/pid_5898/cgroup.procs: No such file or directory
,03-16 12:21:26.572  6055  6055 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 12:21:26.572  6055  6055 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 12:21:26.572  6055  6055 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:21:26.573  6055  6055 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 12:21:26.625  6012  6012 I vclib   : onServiceConnected
,03-16 12:21:26.625  6012  6012 W Babel   : Attempted to change video mute state without an active call.
,03-16 12:21:26.632  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:26.643  6012  6012 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-16 12:21:26.644  6012  6012 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 12:21:26.679  6012  6012 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 12:21:26.708  5962  6083 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-16 12:21:26.708  1580  1580 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@13bce45f new=com.google.android.velvet.VelvetApplication@13bce45f
,03-16 12:21:26.743  1962  6087 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 12:21:26.744  6012  6012 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 12:21:26.744  6012  6012 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 12:21:26.745  1962  6087 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 12:21:26.760   882  1309 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6089 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:26.774  1962  6087 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 12:21:26.788  1962  2591 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 12:21:26.809  6089  6089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:21:26.906  5962  6083 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 197 ms] updated apps [took 197 ms] 
,03-16 12:21:26.908   882  1586 I ActivityManager: Killing 5787:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 12:21:27.001   882  1605 W libprocessgroup: failed to open /acct/uid_10008/pid_5787/cgroup.procs: No such file or directory
,03-16 12:21:27.097   882  1598 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6117 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:27.118  1757  5530 I art     : Explicit concurrent mark sweep GC freed 41860(2MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 13MB/22MB, paused 1.065ms total 107.779ms
,03-16 12:21:27.165   882  4024 I ActivityManager: Killing 5968:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 12:21:27.271   882   897 W libprocessgroup: failed to open /acct/uid_10005/pid_5968/cgroup.procs: No such file or directory
,03-16 12:21:27.342   882  1264 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
03-16 12:21:27.342   882  1264 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-16 12:21:27.482   882  1551 I art     : Explicit concurrent mark sweep GC freed 13862(745KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 1.436ms total 131.182ms
,03-16 12:21:27.515  6117  6117 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 12:21:27.626  6117  6117 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 12:21:27.644  6117  6117 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 12:21:27.647  6117  6117 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 12:21:27.693  6117  6117 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 12:21:27.694  6117  6117 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 12:21:27.696  6117  6163 D Ads     : Skipping gmscore version check
,03-16 12:21:27.791   882  1493 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6165 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:27.792   882  1493 I ActivityManager: Killing 5761:com.test.thalitest/u0a109 (adj 15): empty #7
,03-16 12:21:27.831   882  1247 D WifiService: Client connection lost with reason: 4
,03-16 12:21:27.900   882  1544 W libprocessgroup: failed to open /acct/uid_10109/pid_5761/cgroup.procs: No such file or directory
,03-16 12:21:27.903  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:27.903  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:27.917  6117  6117 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 12:21:27.925  6165  6165 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 12:21:27.931  6117  6117 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 12:21:27.959  6165  6165 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@43b6f67(com.android.providers.calendar.CalendarProvider2@39ea0114)
,03-16 12:21:27.969   882   882 V AlarmManager: done {18d44c9d, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [9037ms]
,03-16 12:21:27.975  6165  6193 E SQLiteLog: (284) automatic index on view_events(_id)
,03-16 12:21:28.015   882  1530 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6194 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 12:21:28.062  6194  6194 D PhoneMonitor: Register our PhoneStateListener
,03-16 12:21:28.092  6194  6194 V SetupWizard: Connected to Gservices successfully
,03-16 12:21:28.095   882  4024 I ActivityManager: Killing 6006:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 12:21:28.147  1962  2591 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 12:21:28.163   882  1253 W libprocessgroup: failed to open /acct/uid_10019/pid_6006/cgroup.procs: No such file or directory
,03-16 12:21:28.223   882   898 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6214 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 12:21:28.229  1962  2591 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 12:21:28.235  1757  3449 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 12:21:28.302  5962  6238 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-16 12:21:28.313  1962  6087 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 12:21:28.340  1962  6087 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 12:21:28.389  1962  1962 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-16 12:21:28.569  1962  1962 D AsyncTaskServiceImpl: Submit a task: k
,03-16 12:21:28.609  1962  6245 D k       : Processing package: com.test.thalitest
,03-16 12:21:28.626  1962  6245 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-16 12:21:28.626  1962  6245 D k       : Found info for package com.test.thalitest in db.
,03-16 12:21:28.636  5962  6238 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 335 ms] updated apps [took 335 ms] 
,03-16 12:21:28.645  1962  6243 W BaseAppContext: Using Auth Proxy for data requests.
03-16 12:21:28.645  1962  6243 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 12:21:28.689   882   898 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6248 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-16 12:21:28.704  1962  6243 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 12:21:28.715  1962  6243 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 12:21:28.717   882  1431 I ActivityManager: Killing 6089:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 12:21:28.785   882  1512 W libprocessgroup: failed to open /acct/uid_10090/pid_6089/cgroup.procs: No such file or directory
,03-16 12:21:28.795  1962  6243 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 12:21:28.803  1962  6240 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-16 12:21:28.969  6165  6165 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 12:21:28.969  6165  6165 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 12:21:28.977   882  1512 I ActivityManager: Killing 6117:com.android.vending/u0a32 (adj 15): empty #7
,03-16 12:21:29.032   882  1551 W libprocessgroup: failed to open /acct/uid_10032/pid_6117/cgroup.procs: No such file or directory
,03-16 12:21:29.042   882  1226 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 12:21:29.171   882   882 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-16 12:21:29.172   882   882 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 12:21:29.175   882   882 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 12:21:29.181   882   882 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 12:21:29.182   882   882 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@186369af
,03-16 12:21:29.223  1757  1757 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-16 12:21:29.250  1580  1580 I Launcher: Deferring update until onResume
,03-16 12:21:29.462  6248  6248 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-16 12:21:29.462  6248  6248 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 12:21:29.462  6248  6248 I GAv4    :   adb logcat -s GAv4
,03-16 12:21:29.476  6248  6248 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:21:29.497  6248  6248 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:21:29.501  6248  6290 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:21:29.521  6248  6248 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-16 12:21:29.558   882   897 I ActivityManager: Killing 4336:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-16 12:21:29.634  1962  2591 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-16 12:21:29.644   882  1551 W libprocessgroup: failed to open /acct/uid_10049/pid_4336/cgroup.procs: No such file or directory
,03-16 12:21:29.685   278   383 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-16 12:21:29.685   278   383 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:21:29.687  6248  6298 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-16 12:21:29.710  6248  6299 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 12:21:29.710  6248  6299 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 12:21:29.722   882   897 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6300 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:29.724   882  1431 I ActivityManager: Killing 6165:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 12:21:29.770  6248  6299 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 12:21:29.802   882   898 W libprocessgroup: failed to open /acct/uid_10005/pid_6165/cgroup.procs: No such file or directory
,03-16 12:21:29.814  1962  2591 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,03-16 12:21:29.816  1962  2591 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 12:21:29.821  6300  6300 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:21:29.853  6248  6299 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 12:21:29.853  6248  6299 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 12:21:29.865  1962  2591 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 12:21:29.873  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:30.089   882  1309 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6327 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:30.109   321   321 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.032ms
,03-16 12:21:30.129   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.314ms
,03-16 12:21:30.150   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.178ms
,03-16 12:21:30.167   882  1512 I ActivityManager: Killing 6194:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 12:21:30.241   882  1544 W libprocessgroup: failed to open /acct/uid_10035/pid_6194/cgroup.procs: No such file or directory
,03-16 12:21:30.324  6327  6327 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 12:21:30.424  6327  6327 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 12:21:30.438  6327  6327 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 12:21:30.438  6327  6327 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 12:21:30.450   317   421 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-16 12:21:30.496  6327  6370 D Ads     : Skipping gmscore version check
,03-16 12:21:30.532   882  1253 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6371 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:30.537  6327  6327 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 12:21:30.537  6327  6327 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 12:21:30.546  6327  6327 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 12:21:30.577  6327  6327 D Finsky  : [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,03-16 12:21:30.589  6327  6327 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 12:21:30.591   882  1512 I ActivityManager: Killing 6214:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 12:21:30.691   882   898 W libprocessgroup: failed to open /acct/uid_10019/pid_6214/cgroup.procs: No such file or directory
,03-16 12:21:30.918   882  1530 I art     : Explicit concurrent mark sweep GC freed 20117(986KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.741ms total 130.490ms
,03-16 12:21:30.923  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 12:21:30.923  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:30.929   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.95 rxSuccessRate=6.28 targetRoamBSSID=any RSSI=-49
03-16 12:21:30.929   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=20411 interval=30000 maxinterval=300000
03-16 12:21:30.929   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 12:21:30.929   882  1244 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-16 12:21:30.930  1421  1421 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-16 12:21:30.930   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 12:21:30.930   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 12:21:30.935   882  1244 E WifiStateMachine: [1,458,127,290,935 ms] noteScanstart no scan source
,03-16 12:21:30.973   882   882 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=6391 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:30.974   882   882 V AlarmManager: done {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10340ms]
,03-16 12:21:30.992   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 12:21:30.992   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-16 12:21:30.992   466   510 D TCMD    : NL - Read 56 bytes from update socket.
03-16 12:21:30.992   466   510 D TCMD    : NL - message type is RTM_NEWLINK
03-16 12:21:30.992   466   510 D TCMD    : Listening for incoming client connection request
,03-16 12:21:30.996   882  1244 E WifiStateMachine: [1,458,127,290,996 ms] noteScanEnd no scan source
,03-16 12:21:31.000   882  1244 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@291244df sup_state=COMPLETED debouncing=false
,03-16 12:21:31.037   882  4024 I ActivityManager: Killing 6055:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-16 12:21:31.101   882  1665 W libprocessgroup: failed to open /acct/uid_10027/pid_6055/cgroup.procs: No such file or directory
,03-16 12:21:31.103  6391  6391 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-16 12:21:31.160   882  1551 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6413 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:31.203  6413  6413 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 12:21:31.224  6391  6391 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-16 12:21:31.269   882   898 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6432 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 12:21:31.271   882   898 I ActivityManager: Killing 5962:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 12:21:31.311   882   898 I ActivityManager: Killing 6248:com.google.android.apps.docs/u0a57 (adj 15): empty #8
,03-16 12:21:31.392   882  1493 W libprocessgroup: failed to open /acct/uid_10039/pid_5962/cgroup.procs: No such file or directory
,03-16 12:21:31.402  6413  6413 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@43b6f67(com.android.providers.calendar.CalendarProvider2@39ea0114)
03-16 12:21:31.402   882   897 W libprocessgroup: failed to open /acct/uid_10057/pid_6248/cgroup.procs: No such file or directory
,03-16 12:21:31.420  6432  6432 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 12:21:31.534   882  1586 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6462 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:31.629  6462  6481 I Gmail   : getAccountsCursor
,03-16 12:21:31.630  6462  6482 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 12:21:31.645  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:31.704   882  4024 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6484 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:31.764  6462  6462 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 12:21:31.770   882  4024 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 12:21:31.781  6484  6484 I Exchange: EasService.onCreate
,03-16 12:21:31.788  6462  6505 I Gmail   : Observing account changes for notifications
,03-16 12:21:31.792  6484  6508 I Exchange: RestartPingTask
,03-16 12:21:31.804  6484  6484 I Exchange: RestartPingsTask did not start any pings.
03-16 12:21:31.804  6484  6484 I Exchange: PSS stopIfIdle
03-16 12:21:31.804  6484  6484 I Exchange: PSS has no active accounts; stopping service.
,03-16 12:21:31.822  6462  6510 I Gmail   : getAccountsCursor
,03-16 12:21:31.825  6484  6484 I Exchange: onDestroy
,03-16 12:21:31.830   882   897 I ActivityManager: Killing 6012:com.google.android.talk/u0a70 (adj 15): empty #7
,03-16 12:21:31.832  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:31.860   882  1309 W libprocessgroup: failed to open /acct/uid_10070/pid_6012/cgroup.procs: No such file or directory
,03-16 12:21:31.867  3640  3640 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,03-16 12:21:31.868  3640  3640 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-16 12:21:31.874   882   898 I ActivityManager: Killing 6300:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 12:21:31.994   882  1309 W libprocessgroup: failed to open /acct/uid_10090/pid_6300/cgroup.procs: No such file or directory
,03-16 12:21:32.002  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:32.008  1301  1322 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-16 12:21:32.041  6462  6520 E SQLiteLog: (283) recovered 73 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 12:21:32.081   882  1309 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6524 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 12:21:32.115  6462  6521 I Gmail   : notifyAccountChanged
,03-16 12:21:32.117  6462  6511 I Gmail   : getAccountsCursor
,03-16 12:21:32.120  6462  6521 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:21:32.125  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:32.137  1301  1301 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
03-16 12:21:32.138  6462  6521 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:21:32.152  6462  6521 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 12:21:32.153  6462  6521 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 12:21:32.158  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:32.160  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:32.230  6462  6481 I Gmail   : getAccountsCursor
,03-16 12:21:32.233  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:32.433  6413  6413 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 12:21:32.433  6413  6413 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 12:21:32.481   882   897 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6557 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 12:21:32.484   882  1431 I ActivityManager: Killing 6371:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 12:21:32.521   882  1431 I ActivityManager: Killing 6327:com.android.vending/u0a32 (adj 15): empty #8
,03-16 12:21:32.587   882  1598 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6574 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 12:21:32.588   882  4024 W libprocessgroup: failed to open /acct/uid_10088/pid_6371/cgroup.procs: No such file or directory
,03-16 12:21:32.601   882   898 I ActivityManager: Killing 6413:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 12:21:32.629   882  1665 W libprocessgroup: failed to open /acct/uid_10032/pid_6327/cgroup.procs: No such file or directory
,03-16 12:21:32.631   882  1605 W libprocessgroup: failed to open /acct/uid_10005/pid_6413/cgroup.procs: No such file or directory
,03-16 12:21:32.649  6574  6574 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:21:32.822  6574  6602 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 12:21:32.822  6574  6602 I Babel_SMS: MmsConfig.loadMmsSettings
03-16 12:21:32.823  6574  6602 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 12:21:32.823  6574  6602 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 12:21:32.861  6574  6602 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 12:21:32.861  6574  6602 I Babel_SMS: MmsConfig.loadFromResources
,03-16 12:21:32.863  6574  6602 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 12:21:32.863  6574  6602 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 12:21:32.921  6574  6574 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 12:21:32.933  6574  6574 I Babel_Crash: startup - clean
,03-16 12:21:32.951  6574  6605 I Babel   : deleted: false for 0
,03-16 12:21:33.052   882  1431 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6607 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:33.095  6574  6574 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:21:33.113  6574  6574 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 12:21:33.123  6574  6574 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 12:21:33.146  6574  6574 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 12:21:33.152  6574  6574 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 12:21:33.154  6574  6574 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 12:21:33.156  6574  6574 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:21:33.161  6574  6574 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:21:33.219   882   897 I art     : Explicit concurrent mark sweep GC freed 14359(793KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.595ms total 117.304ms
,03-16 12:21:33.235  6607  6607 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 12:21:33.235  6607  6607 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 12:21:33.235  6607  6607 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 12:21:33.235  6607  6607 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 12:21:33.279  6574  6588 W art     : Suspending all threads took: 22.854ms
,03-16 12:21:33.291  1580  1580 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@13bce45f new=com.google.android.velvet.VelvetApplication@13bce45f
,03-16 12:21:33.296  6524  6630 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-16 12:21:33.297  1962  6087 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-16 12:21:33.297  1962  6087 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 12:21:33.342   882  1551 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6633 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:33.363   321   321 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.573ms
,03-16 12:21:33.388   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 23.677ms
,03-16 12:21:33.407  1962  6087 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-16 12:21:33.407  6574  6574 I vclib   : onServiceConnected
,03-16 12:21:33.412   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 23.771ms
,03-16 12:21:33.413  1962  2591 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 12:21:33.418  6574  6574 W Babel   : Attempted to change video mute state without an active call.
,03-16 12:21:33.443  6574  6574 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 12:21:33.443  6574  6574 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-16 12:21:33.446  6633  6633 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:21:33.465  6524  6630 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 168 ms] updated apps [took 167 ms] 
,03-16 12:21:33.468   882   898 I ActivityManager: Killing 6484:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 12:21:33.476  6574  6574 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 12:21:33.537  6574  6574 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 12:21:33.537  6574  6574 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 12:21:33.602   882  1551 W libprocessgroup: failed to open /acct/uid_10060/pid_6484/cgroup.procs: No such file or directory
,03-16 12:21:33.686   882  1223 V AlarmManager: send {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 12:21:33.687   882  1223 V AlarmManager: send {21e7422, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-16 12:21:33.791   882  1493 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6669 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:33.859  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:33.859  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:33.864   882  1586 I ActivityManager: Killing 6462:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 12:21:33.921   882  1431 W libprocessgroup: failed to open /acct/uid_10063/pid_6462/cgroup.procs: No such file or directory
,03-16 12:21:33.984  6669  6669 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 12:21:34.084  6669  6669 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 12:21:34.096  6669  6669 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 12:21:34.097  6669  6669 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 12:21:34.134  6669  6669 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 12:21:34.134  6669  6669 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 12:21:34.136  6669  6711 D Ads     : Skipping gmscore version check
,03-16 12:21:34.143   882  1605 I ActivityManager: Killing 6432:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 12:21:34.176   882  1598 W libprocessgroup: failed to open /acct/uid_10008/pid_6432/cgroup.procs: No such file or directory
,03-16 12:21:34.178  6669  6669 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 12:21:34.194  6669  6669 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 12:21:34.229   882  1544 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6714 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:34.263   882  1431 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6731 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:34.323  6731  6731 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 12:21:34.352  6731  6731 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@43b6f67(com.android.providers.calendar.CalendarProvider2@39ea0114)
,03-16 12:21:34.392  6714  6757 I Gmail   : getAccountsCursor
,03-16 12:21:34.394  6714  6758 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 12:21:34.405  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:34.469   882  1544 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6760 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:21:34.522   882  1551 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 12:21:34.530  6714  6781 I Gmail   : Observing account changes for notifications
,03-16 12:21:34.542  6760  6760 I Exchange: EasService.onCreate
,03-16 12:21:34.542  6714  6714 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 12:21:34.548  6760  6784 I Exchange: RestartPingTask
,03-16 12:21:34.553   882  1223 V AlarmManager: send {1bbf7291, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-16 12:21:34.558  6760  6760 I Exchange: RestartPingsTask did not start any pings.
03-16 12:21:34.558  6760  6760 I Exchange: PSS stopIfIdle
03-16 12:21:34.558  6760  6760 I Exchange: PSS has no active accounts; stopping service.
,03-16 12:21:34.592  6760  6760 I Exchange: onDestroy
,03-16 12:21:34.592  6714  6788 I Gmail   : getAccountsCursor
03-16 12:21:34.593   882  1598 I ActivityManager: Killing 6557:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 12:21:34.609   882  1605 W libprocessgroup: failed to open /acct/uid_10019/pid_6557/cgroup.procs: No such file or directory
,03-16 12:21:34.612  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:34.637  1962  2591 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 12:21:34.672   882  1493 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6797 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 12:21:34.683   882  1598 I ActivityManager: Killing 6607:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-16 12:21:34.686  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:34.705  1962  2591 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 12:21:34.803   882  1493 W libprocessgroup: failed to open /acct/uid_10027/pid_6607/cgroup.procs: No such file or directory
,03-16 12:21:34.828  6797  6797 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 12:21:34.842  6714  6815 E SQLiteLog: (283) recovered 74 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 12:21:34.865   882   882 V AlarmManager: done {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN} [1178ms]
03-16 12:21:34.865   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.48 rxSuccessRate=3.14 targetRoamBSSID=any RSSI=-50
03-16 12:21:34.865   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=24347 interval=30000 maxinterval=300000
03-16 12:21:34.865   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 12:21:34.866   882  1244 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-16 12:21:34.866   882   882 V AlarmManager: done {21e7422, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [1179ms]
03-16 12:21:34.866  1421  1421 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-16 12:21:34.867   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 12:21:34.867   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 12:21:34.868   882  1244 E WifiStateMachine: [1,458,127,294,868 ms] noteScanstart no scan source
,03-16 12:21:34.873   882  1431 I ActivityManager: Killing 6524:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 12:21:34.913  6714  6817 I Gmail   : notifyAccountChanged
,03-16 12:21:34.915   882  4024 W libprocessgroup: failed to open /acct/uid_10039/pid_6524/cgroup.procs: No such file or directory
,03-16 12:21:34.919  6714  6817 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:21:34.920  6714  6789 I Gmail   : getAccountsCursor
,03-16 12:21:34.923  6714  6817 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:21:34.932   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.932  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 12:21:34.932   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
,03-16 12:21:34.933   466   510 D TCMD    : NL - Read 56 bytes from update socket.
03-16 12:21:34.933   466   510 D TCMD    : NL - message type is RTM_NEWLINK
03-16 12:21:34.933   466   510 D TCMD    : Listening for incoming client connection request
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 8
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 5
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 6
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 7
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:21:34.933   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 12:21:34.933   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-16 12:21:34.938   882  1244 E WifiStateMachine: [1,458,127,294,938 ms] noteScanEnd no scan source
,03-16 12:21:34.939   882  1244 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@291244df sup_state=COMPLETED debouncing=false
,03-16 12:21:34.945  6714  6817 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 12:21:34.946  6714  6817 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 12:21:34.948   882   882 V AlarmManager: done {1bbf7291, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [395ms]
,03-16 12:21:34.955  6731  6822 E SQLiteLog: (284) automatic index on view_events(_id)
,03-16 12:21:34.958  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 12:21:34.959  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:35.010  6714  6757 I Gmail   : getAccountsCursor
,03-16 12:21:35.013  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:35.368  6731  6731 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 12:21:35.368  6731  6731 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 12:21:35.422   882  4024 I ActivityManager: Killing 6633:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 12:21:35.448   882  1665 W libprocessgroup: failed to open /acct/uid_10090/pid_6633/cgroup.procs: No such file or directory
,03-16 12:21:36.148  6391  6412 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-16 12:21:36.282   882  1605 I art     : Explicit concurrent mark sweep GC freed 13750(670KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.794ms total 120.013ms
,03-16 12:21:36.294  6391  6412 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 12:21:36.875  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:36.875  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:38.130  6669  6669 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-16 12:21:38.136   882  1223 V AlarmManager: send {173779a9, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,03-16 12:21:38.141   882   882 V AlarmManager: done {173779a9, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [17ms]
,03-16 12:21:38.168  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:38.643  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:38.664  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:38.778  6669  6697 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-16 12:21:38.778  6669  6697 I qtaguid : Untagging socket 37 failed errno=-22
03-16 12:21:38.778  6669  6697 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-16 12:21:38.799  6669  6669 D Finsky  : [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,03-16 12:21:38.926  6669  6850 I art     : WaitForGcToComplete blocked for 5.547ms for cause DisableMovingGc
,03-16 12:21:38.967   882  1493 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6855 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 12:21:38.974  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:39.026  6855  6855 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 12:21:39.026  6855  6855 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 12:21:39.062  6855  6855 I MultiDex: VM with version 2.1.0 has multidex support
03-16 12:21:39.062  6855  6855 I MultiDex: install
03-16 12:21:39.062  6855  6855 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-16 12:21:39.081  6855  6855 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 12:21:39.133  6855  6855 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 12:21:39.134  6855  6855 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@217ac736: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 12:21:39.134  6855  6855 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 12:21:39.151  6855  6855 D ChimeraCfgMgr: Reading stored module config
,03-16 12:21:39.156  1757  1757 D WearableService: callingUid 10016, callindPid: 1757
,03-16 12:21:39.159  1757  4587 E MDM     : [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 12:21:39.162  1962  6880 D LocationInitializer: Restart initialization of location
03-16 12:21:39.163  1757  1757 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 12:21:39.177  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:39.195  1757  2250 W GCoreFlp: No location to return for getLastLocation()
03-16 12:21:39.195  1757  6881 W FusedLocationProvider: location=null
,03-16 12:21:39.339  6855  6855 D CAR.SERVICE: Connecting to CarCallService...
,03-16 12:21:39.364  6855  6855 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 12:21:39.365  6855  6855 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-16 12:21:39.381  6669  6696 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-16 12:21:39.381  6669  6696 I qtaguid : Untagging socket 37 failed errno=-22
03-16 12:21:39.381  6669  6696 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-16 12:21:39.389  6855  6879 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-16 12:21:39.412  6855  6855 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-16 12:21:39.438  6855  6855 D CAR.TEL.Service: Creating a new CarCallService.
03-16 12:21:39.440  6855  6855 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-16 12:21:39.443   882  1605 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-16 12:21:39.445  6855  6855 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@144a3e72
,03-16 12:21:39.445   882  1665 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-16 12:21:39.446  6855  6855 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-16 12:21:39.446  6855  6855 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-16 12:21:39.558  6855  6870 D CAR.SERVICE: Package validated; name: com.android.vending
,03-16 12:21:39.560  6714  6782 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 12:21:39.583  6669  6669 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,03-16 12:21:39.885  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:39.886  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:40.137  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:40.455   317   421 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-16 12:21:40.595  6669  6697 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-16 12:21:40.595  6669  6697 I qtaguid : Untagging socket 37 failed errno=-22
03-16 12:21:40.595  6669  6697 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-16 12:21:40.670   882  1530 W ActivityManager: getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,03-16 12:21:40.725  6669  6669 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-16 12:21:40.726  6669  6669 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 12:21:40.912  6669  6669 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:21:40.931  6669  6669 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,03-16 12:21:40.936   882  1223 V AlarmManager: send {e673584, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,03-16 12:21:40.959   882   882 V AlarmManager: done {e673584, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [24ms]
,03-16 12:21:40.965  1757  1789 D DeviceConnectionService: client connected with version: 8296000
,03-16 12:21:40.966  6669  6907 D Finsky  : [640] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-16 12:21:40.974  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:21:40.981  6669  6669 D Finsky  : [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 12:21:40.985  6669  6669 D Finsky  : [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,03-16 12:21:41.472   882  1431 I ActivityManager: Killing 6760:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 12:21:41.551   882  1431 I ActivityManager: Killing 6574:com.google.android.talk/u0a70 (adj 15): empty #8
,03-16 12:21:41.611   882  1586 W libprocessgroup: failed to open /acct/uid_10060/pid_6760/cgroup.procs: No such file or directory
,03-16 12:21:41.614   882  1598 W libprocessgroup: failed to open /acct/uid_10070/pid_6574/cgroup.procs: No such file or directory
,03-16 12:21:42.647  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:42.902  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:42.902  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:43.777   882  1223 V AlarmManager: send {391ef0ab, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-16 12:21:43.783   882   882 V AlarmManager: done {391ef0ab, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,03-16 12:21:44.590  6855  6855 D CAR.SERVICE: mConnectedToCar = false, abort
,03-16 12:21:44.606  6855  6855 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3eef3b28 that was originally bound here
03-16 12:21:44.606  6855  6855 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3eef3b28 that was originally bound here
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-16 12:21:44.606  6855  6855 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-16 12:21:44.613  6855  6855 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@176ef7d that was originally bound here
03-16 12:21:44.613  6855  6855 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@176ef7d that was originally bound here
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-16 12:21:44.613  6855  6855 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-16 12:21:44.614   882  1309 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@ec2c308
,03-16 12:21:45.918  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:45.918  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:46.480   882  1091 I ActivityManager: Waited long enough for: ServiceRecord{21f1dd6f u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-16 12:21:48.934  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:48.935  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:50.459   317   421 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-16 12:21:51.948  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:51.948  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:54.964  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:54.965  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:55.006   882  1223 V AlarmManager: send {620e4c6, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
03-16 12:21:55.007   882  1223 V AlarmManager: send {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 12:21:55.009   882   882 V AlarmManager: done {620e4c6, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [12ms]
,03-16 12:21:55.014   882   882 V AlarmManager: done {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN} [17ms]
,03-16 12:21:55.017   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.12 rxSuccessRate=2.65 targetRoamBSSID=any RSSI=-50
03-16 12:21:55.017   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=44499 interval=30000 maxinterval=300000
03-16 12:21:55.017   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=44499 interval=30000 maxinterval=300000
03-16 12:21:55.017   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-16 12:21:55.017   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =45000
03-16 12:21:55.018  1421  1421 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-16 12:21:55.018   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 12:21:55.018   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 12:21:55.021   882  1244 E WifiStateMachine: [1,458,127,315,021 ms] noteScanstart no scan source
,03-16 12:21:55.134  6669  6709 D Finsky  : [630] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,03-16 12:21:55.136  6669  6669 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 15 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 15 
03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 16 
03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 17 
03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 18 
03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 19 
03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 20 
03-16 12:21:55.404   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
03-16 12:21:55.404   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 21 
03-16 12:21:55.405   466   510 D TCMD    : NL - Read 56 bytes from update socket.
03-16 12:21:55.405   466   510 D TCMD    : NL - message type is RTM_NEWLINK
03-16 12:21:55.405   466   510 D TCMD    : Listening for incoming client connection request
,03-16 12:21:55.412   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 12:21:55.412   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS ,
,03-16 12:21:55.414   882  1244 E WifiStateMachine: [1,458,127,315,414 ms] noteScanEnd no scan source
,03-16 12:21:55.419   882  1244 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@291244df sup_state=COMPLETED debouncing=false
,03-16 12:21:55.803   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311576, SEQNUM=4659, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 12:21:55.893  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:21:56.792   882  1530 I ActivityManager: Killing 6797:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 12:21:56.811   882  1530 I ActivityManager: Killing 6714:com.google.android.gm/u0a63 (adj 15): empty #8
,03-16 12:21:56.832   882   897 W libprocessgroup: failed to open /acct/uid_10008/pid_6797/cgroup.procs: No such file or directory
,03-16 12:21:56.835   882  1309 W libprocessgroup: failed to open /acct/uid_10063/pid_6714/cgroup.procs: No such file or directory
,03-16 12:21:57.658  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:57.979  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:21:57.979  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:58.659  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:21:59.136  1482  1482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-16 12:22:00.001   882  1223 V AlarmManager: send {29e4b44f, *alarm*:android.intent.action.TIME_TICK}
,03-16 12:22:00.046   882   882 V AlarmManager: done {29e4b44f, *alarm*:android.intent.action.TIME_TICK} [46ms]
,03-16 12:22:00.464   317   421 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-16 12:22:00.995  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:00.996  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:04.010  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:04.010  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:07.024  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:07.024  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:10.038  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:10.039  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:10.468   317   421 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-16 12:22:13.055  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:13.056  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:13.788   882  1223 V AlarmManager: send {391ef0ab, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-16 12:22:13.792   882   882 V AlarmManager: done {391ef0ab, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,03-16 12:22:13.846  1962  6946 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,03-16 12:22:13.855   882  1090 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 203216, reason: UserStart
,03-16 12:22:14.078   882  1223 V AlarmManager: send {3204eb20, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,03-16 12:22:14.086   882  1223 V AlarmManager: send {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 12:22:14.089   882   882 V AlarmManager: done {3204eb20, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [12ms]
,03-16 12:22:14.090   882   882 V AlarmManager: done {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN} [12ms]
,03-16 12:22:14.093   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.03 rxSuccessRate=0.06 targetRoamBSSID=any RSSI=-49
03-16 12:22:14.094   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=19077 interval=45000 maxinterval=300000
03-16 12:22:14.094   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 12:22:14.094   882  1244 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-16 12:22:14.094  1421  1421 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-16 12:22:14.095   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 12:22:14.095   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 12:22:14.098   882  1244 E WifiStateMachine: [1,458,127,334,098 ms] noteScanstart no scan source
,03-16 12:22:14.162   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 12:22:14.162   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-16 12:22:14.163   466   510 D TCMD    : NL - Read 56 bytes from update socket.
03-16 12:22:14.163   466   510 D TCMD    : NL - message type is RTM_NEWLINK
03-16 12:22:14.163   466   510 D TCMD    : Listening for incoming client connection request
,03-16 12:22:14.167   882  1244 E WifiStateMachine: [1,458,127,334,167 ms] noteScanEnd no scan source
,03-16 12:22:14.171   882  1244 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@291244df sup_state=COMPLETED debouncing=false
,03-16 12:22:14.271  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:22:14.276  1757  6957 I VacuumService: Vacuum at: now=1458127334276 tag=VacuumService,
,03-16 12:22:15.811   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=305, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311374, SEQNUM=4669, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 12:22:15.896  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:22:15.947  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:22:16.068  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:16.069  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:19.086  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:19.087  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:19.563   882  1254 E BackupManagerService: Timeout restoring application @pm@
03-16 12:22:19.564   882  1254 W BackupManagerService: Tried to clear data for @pm@ but not found
,03-16 12:22:19.569  1757  2577 W GmsBackupTransport: Restore processing aborted, no more packages
,03-16 12:22:19.571   882  1254 E BackupManagerService: Failure getting next package name
,03-16 12:22:19.572   882  1254 E BackupManagerService: Duplicate finish
,03-16 12:22:20.473   317   421 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-16 12:22:22.100  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:22.100  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:23.944  1422  1619 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-16 12:22:23.949  1422  1619 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-16 12:22:25.116  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:25.116  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:28.132  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:28.132  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:30.478   317   421 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-16 12:22:30.715   882  1223 V AlarmManager: send {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 12:22:30.720   882   882 V AlarmManager: done {26733cc9, *alarm*:com.android.server.WifiManager.action.START_SCAN} [5ms]
,03-16 12:22:30.726   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
03-16 12:22:30.726   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=35709 interval=45000 maxinterval=300000
03-16 12:22:30.726   882  1244 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 12:22:30.726   882  1244 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-16 12:22:30.727  1421  1421 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-16 12:22:30.728   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 12:22:30.728   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-16 12:22:30.733   882  1244 E WifiStateMachine: [1,458,127,350,733 ms] noteScanstart no scan source
,03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-16 12:22:30.792   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-16 12:22:30.792   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-16 12:22:30.793   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 12:22:30.793   297  1641 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-16 12:22:30.793   466   510 D TCMD    : NL - Read 56 bytes from update socket.
03-16 12:22:30.793   466   510 D TCMD    : NL - message type is RTM_NEWLINK
03-16 12:22:30.793   466   510 D TCMD    : Listening for incoming client connection request
,03-16 12:22:30.798   882  1244 E WifiStateMachine: [1,458,127,350,798 ms] noteScanEnd no scan source
,03-16 12:22:30.800   882  1244 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@291244df sup_state=COMPLETED debouncing=false
,03-16 12:22:31.143  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:31.143  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:34.158  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:34.159  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:37.175  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:37.175  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 12:22:37.175  1301  1301 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
03-16 12:22:37.176  1301  1301 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,03-16 12:22:40.190  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:40.190  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:40.482   317   421 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-16 12:22:43.205  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:43.205  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:43.817   882  1223 V AlarmManager: send {391ef0ab, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-16 12:22:43.821   882   882 V AlarmManager: done {391ef0ab, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,03-16 12:22:45.806   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310397, SEQNUM=4677, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6911, POWER_SUPPLY_CHARGE_COUNTER=-48, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 12:22:45.856  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:22:46.221  1301  1301 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 12:22:46.221  1301  1301 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 12:22:46.230   882  1130 I PowerManagerService: Nap time (uid 1000)...
03-16 12:22:46.230   882  1130 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-16 12:22:46.244   882  1130 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 12:22:46.244   882  1130 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 12:22:46.244   882  1130 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 12:22:46.244   882  1130 I Adreno-EGL: Local Branch: 
03-16 12:22:46.244   882  1130 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 12:22:46.244   882  1130 I Adreno-EGL: Local Patches: NONE
03-16 12:22:46.244   882  1130 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 12:22:46.743   882  1130 D         : activate, handle: 1598182242, enabled: 0, index 2
,03-16 12:22:46.748   882  1130 D         : BstSensorExt: id=1598182242, en=0
03-16 12:22:46.748   882  1130 D         : enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 223
,03-16 12:22:46.753   882  1130 D         : activate, handle: 2, enabled: 0, index 5
,03-16 12:22:46.758   882  1120 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-16 12:22:46.760   882   882 V ActivityManager: Display changed displayId=0
,03-16 12:22:46.781   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb7d18550
,03-16 12:22:46.784   279   279 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-16 12:22:46.920   294   294 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb79a5820
03-16 12:22:46.920   294   294 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
03-16 12:22:46.920   294   294 I rmt_storage: wakelock acquired: 1, error no: 42
,03-16 12:22:46.921   294   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1214622408)
,03-16 12:22:47.030   294   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
03-16 12:22:47.030   294   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
03-16 12:22:47.030   294   820 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1214622408) wakelock released: 1, error no: 0
03-16 12:22:47.030   294   820 I rmt_storage: 
,03-16 12:22:47.033   294   294 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb79a5820
,03-16 12:22:47.093   279   683 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-16 12:22:47.095   279   279 I qdhwcomposer: enable_dcabc: Done setting OFF mode
,03-16 12:22:47.095   279   279 D qdhwcomposer: hwc_blank: Done blanking display: 0
,03-16 12:22:47.097   882  1263 D SurfaceControl: Excessive delay in setPowerMode(): 340ms
,03-16 12:22:47.104   279   279 I SFPerfTracer:       trigger: frame rate (-31.175%)	(41.295 fps)	(24.216 ms) 	(4 drops)	(16 frames)
03-16 12:22:47.104   279   279 I SFPerfTracer:      triggers: (rate: 7:417) (compose: 0:6) (post: 0:3) (render: 0:18) (16:1316 frames) (17:1439)
03-16 12:22:47.104   279   279 D SFPerfTracer:        layers: (4:11) (FocusedStackFrame (0xb7d9a198): 0:19)* (DimLayer (0xb7e3f690): 0:9)* (DimLayer (0xb7da4e30): 0:9)* (StatusBar (0xb7e19e90): 0:201) (NavigationBar (0xb7e1c280): 0:91) (com.android.systemui.ImageWallpaper (0xb7e1f078): 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7e558e8): 0:67)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7e66988): 0:42) (ColorFade (0xb7e558e8): 17:19) 
,03-16 12:22:47.107   882   882 I WindowManager: AOD feature not enabled!
,03-16 12:22:47.123  1482  5148 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 12:22:47.124   882  1130 I PowerManagerService: Sleeping (uid 1000)...
,03-16 12:22:47.166   882  1244 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
03-16 12:22:47.166   882  1244 E WifiStateMachine: handleScreenStateChanged Exit: true
,03-16 12:22:47.169   299   299 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-16 12:22:47.189   299   299 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-16 12:22:47.189   299   299 V msm8974_platform: platform_set_parameters: exit with code(0)
03-16 12:22:47.190   299   299 E msm8974_platform: platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
03-16 12:22:47.190   299   299 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
03-16 12:22:47.191   299   299 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-16 12:22:47.198   882  1244 E WifiStateMachine: setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-16 12:22:47.198   882  1244 E native  : do suspend false
,03-16 12:22:47.305  1422  1422 I Keyboard.Facilitator: onFinishInput()
,03-16 12:22:47.311   882   882 D         : activate, handle: 1598182229, enabled: 0, index 0
03-16 12:22:47.311   882   882 E         : <BST> disable accel, orig state: 1
03-16 12:22:47.311   882   882 I         : <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
03-16 12:22:47.312   299   981 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-16 12:22:47.312   299   981 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-16 12:22:47.312   299   981 V msm8974_platform: platform_set_parameters: exit with code(0)
03-16 12:22:47.312   299   981 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
03-16 12:22:47.312   299   981 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
03-16 12:22:47.313   882  1244 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
03-16 12:22:47.313   882  1244 E WifiStateMachine: handleScreenStateChanged Exit: false
03-16 12:22:47.317   882  1244 E WifiStateMachine: setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,03-16 12:22:47.318   882  1244 E WifiStateMachine: setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-16 12:22:47.318   882  1244 E native  : do suspend true
,03-16 12:22:49.346  1482  1482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-16 12:22:49.487  1482  1482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-16 12:22:50.487   317   421 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-16 12:22:52.143   882  1223 V AlarmManager: send {1aa68213, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,03-16 12:22:52.152   882   882 V AlarmManager: done {1aa68213, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [9ms]
,03-16 12:22:55.811   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311227, SEQNUM=4686, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14022, POWER_SUPPLY_CHARGE_COUNTER=-81, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 12:22:55.926  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:22:55.975  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:23:00.491   317   421 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 12:23:10.496   317   421 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 12:23:17.348   882  1223 V AlarmManager: send {29e4b44f, *alarm*:android.intent.action.TIME_TICK}
03-16 12:23:17.349   882  1223 V AlarmManager: send {2395c50, *walarm*:com.google.android.intent.action.SEND_IDLE}
,03-16 12:23:17.386   882   882 V AlarmManager: done {29e4b44f, *alarm*:android.intent.action.TIME_TICK} [38ms]
,03-16 12:23:17.430   882   882 V AlarmManager: done {2395c50, *walarm*:com.google.android.intent.action.SEND_IDLE} [82ms]
,03-16 12:23:17.497  3640  5254 E global frequency: no tags to log
,03-16 12:23:17.500  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:23:17.513  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:23:17.515  1561  3189 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 12:23:17.701   882  1431 I art     : Explicit concurrent mark sweep GC freed 56420(2MB) AllocSpace objects, 4(338KB) LOS objects, 33% free, 21MB/32MB, paused 1.816ms total 136.666ms
,03-16 12:23:17.706  1757  7037 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 8864 seconds from now (1458127397706)
,03-16 12:23:17.781  1482  1513 I art     : Explicit concurrent mark sweep GC freed 55907(3MB) AllocSpace objects, 35(1221KB) LOS objects, 39% free, 7MB/12MB, paused 810us total 44.502ms
,03-16 12:23:17.790  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:23:17.806  3640  3640 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:23:17.814  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:23:17.816  1561  3427 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 12:23:17.825  1757  7029 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-16 12:23:17.830  1757  7029 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-16 12:23:17.889  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:23:17.901  3640  3640 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:23:17.909  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:23:17.910  1561  1579 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-16 12:23:18.002  1482  5414 I art     : Explicit concurrent mark sweep GC freed 4284(179KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 653us total 31.125ms
,03-16 12:23:18.011  3640  3640 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-16 12:23:18.085  3640  3640 I art     : Explicit concurrent mark sweep GC freed 28802(1724KB) AllocSpace objects, 6(119KB) LOS objects, 40% free, 11MB/19MB, paused 991us total 64.068ms
,03-16 12:23:18.087  3640  3640 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:23:18.090  3640  5254 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 12:23:18.092  3640  5254 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-16 12:23:18.093  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:23:18.094  3640  5254 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
03-16 12:23:18.095  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:23:18.096  3640  5254 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-16 12:23:18.098  3640  5254 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-16 12:23:18.106  3640  5254 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,03-16 12:23:18.107  3640  5254 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 12:23:18.437  1757  7029 I art     : Explicit concurrent mark sweep GC freed 52280(3MB) AllocSpace objects, 13(231KB) LOS objects, 40% free, 13MB/23MB, paused 1.309ms total 104.202ms
,03-16 12:23:18.445  1757  1783 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@336efcb0)
03-16 12:23:18.445  1757  1783 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@175f6729)
,03-16 12:23:18.447  1757  1783 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@37c39aae)
,03-16 12:23:18.448  1757  1783 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27fe104f)
,03-16 12:23:18.449  1757  1783 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c3f33dc)
,03-16 12:23:19.621  1757  3521 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-16 12:23:20.092  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:23:20.094  1757  1757 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:23:20.501   317   421 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 12:23:22.304   882  1223 V AlarmManager: send {1a278a75, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,03-16 12:23:22.309   882  1223 V AlarmManager: send {3a83ca0a, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,03-16 12:23:22.319   882   882 V AlarmManager: done {1a278a75, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [15ms]
,03-16 12:23:22.320   882   882 V AlarmManager: done {3a83ca0a, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [16ms]
,03-16 12:23:22.342  1962  7074 I EventLogService: Aggregate from 1458127273005 (log), 1458125587257 (data)
,03-16 12:23:30.505   317   421 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-16 12:23:40.510   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:23:47.306  1422  1619 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-16 12:23:47.306  1422  1619 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-16 12:23:50.514   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:23:56.798   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311072, SEQNUM=4698, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11217, POWER_SUPPLY_CHARGE_COUNTER=-281, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-16 12:23:56.801   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:23:56.801   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:23:56.801   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:23:56.801   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:23:56.801   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:23:56.801   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:23:56.801   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:23:56.846  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:23:56.887   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:23:56.887   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:23:56.888   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:23:56.888   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:23:56.888   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:23:56.888   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:23:56.888   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:23:56.949  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:24:00.519   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:24:10.524   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:24:20.528   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:24:30.533   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:24:40.538   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:24:50.542   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:25:00.547   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:25:10.551   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:25:14.272   297  1641 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-16 12:25:14.272   297  1641 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
,03-16 12:25:17.798   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310994, SEQNUM=4704, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-535, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-16 12:25:17.800   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:25:17.801   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:25:17.801   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:25:17.801   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:25:17.801   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:25:17.801   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:25:17.801   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:25:17.845  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:25:17.887   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:25:17.887   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:25:17.887   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:25:17.887   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:25:17.887   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:25:17.887   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:25:17.887   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:25:17.939  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:25:20.556   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:25:30.560   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:25:40.565   317   421 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-16 12:25:50.570   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:26:00.574   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:26:10.579   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:26:20.583   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:26:30.588   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:26:40.593   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:26:50.597   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:27:00.001   882  1223 V AlarmManager: send {29e4b44f, *alarm*:android.intent.action.TIME_TICK}
,03-16 12:27:00.035   882   882 V AlarmManager: done {29e4b44f, *alarm*:android.intent.action.TIME_TICK} [35ms]
,03-16 12:27:00.602   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:27:10.606   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:27:20.611   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:27:30.616   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:27:40.620   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:27:50.625   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:28:00.629   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:28:10.634   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:28:20.639   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:28:30.643   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:28:40.648   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:28:50.652   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:29:00.657   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:29:10.661   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:29:20.666   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:29:30.671   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:29:40.675   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:29:50.680   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:30:00.684   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:30:01.001   882  1223 V AlarmManager: send {29e4b44f, *alarm*:android.intent.action.TIME_TICK}
03-16 12:30:01.002   882  1223 V AlarmManager: send {e2e8b57, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,03-16 12:30:01.064   882  1091 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7091 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-16 12:30:01.090   882   882 V AlarmManager: done {29e4b44f, *alarm*:android.intent.action.TIME_TICK} [90ms]
,03-16 12:30:01.216  7091  7091 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-16 12:30:01.216  7091  7091 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 12:30:01.216  7091  7091 I GAv4    :   adb logcat -s GAv4
,03-16 12:30:01.239  7091  7091 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:30:01.270  7091  7091 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:30:01.280  7091  7115 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 12:30:01.285   882   882 V AlarmManager: done {e2e8b57, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [285ms]
03-16 12:30:01.286   882  1253 I ActivityManager: Killing 6731:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 12:30:01.392   882   898 W libprocessgroup: failed to open /acct/uid_10005/pid_6731/cgroup.procs: No such file or directory
,03-16 12:30:10.689   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:30:20.694   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:30:30.698   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:30:40.703   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:30:50.707   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:31:00.712   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:31:10.717   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:31:20.721   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:31:30.726   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:31:40.730   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:31:50.735   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:32:00.740   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:32:10.744   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:32:20.749   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:32:30.753   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:32:40.758   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:32:50.762   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:33:00.767   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:33:10.772   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:33:20.776   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:33:30.781   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:33:34.880   882  1223 V AlarmManager: send {29e4b44f, *alarm*:android.intent.action.TIME_TICK}
,03-16 12:33:34.881   882  1223 V AlarmManager: send {21e7422, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-16 12:33:34.902   882   882 V AlarmManager: done {21e7422, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,03-16 12:33:34.933   882   882 V AlarmManager: done {29e4b44f, *alarm*:android.intent.action.TIME_TICK} [53ms]
,03-16 12:33:40.785   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:33:50.790   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:34:00.795   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:34:10.799   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:34:20.804   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:34:30.808   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:34:40.813   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:34:50.817   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:35:00.822   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:35:10.827   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:35:18.758   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310273, SEQNUM=4708, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-16 12:35:18.760   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:35:18.760   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:35:18.761   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:35:18.761   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:35:18.761   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:35:18.761   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:35:18.761   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:35:18.805  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:35:18.847   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:35:18.847   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:35:18.847   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:35:18.847   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:35:18.847   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:35:18.847   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:35:18.847   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:35:18.926  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:35:20.831   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:35:30.836   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:35:40.840   317   421 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-16 12:35:50.845   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:36:00.850   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:36:10.854   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:36:20.859   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:36:30.863   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:36:40.868   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:36:50.873   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:37:00.877   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:37:10.882   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:37:20.886   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:37:30.891   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:37:40.895   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:37:50.900   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:38:00.905   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:38:10.909   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:38:20.914   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:38:30.918   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:38:40.923   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:38:50.928   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:39:00.932   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:39:10.937   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:39:20.941   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:39:30.946   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:39:40.950   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:39:50.955   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:40:00.960   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:40:10.964   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:40:20.969   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:40:30.022   882  1090 I UsageStatsService: User[0] Flushing usage stats to disk
,03-16 12:40:30.973   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:40:40.978   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:40:50.983   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:41:00.987   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:41:10.366   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311126, SEQNUM=4710, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-174, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-16 12:41:10.368   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:41:10.368   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:41:10.368   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:41:10.368   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:41:10.368   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:41:10.368   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:41:10.368   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:41:10.415  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:41:10.992   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:41:20.996   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:41:31.001   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:41:38.758   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311122, SEQNUM=4711, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-16 12:41:38.761   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:41:38.761   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:41:38.761   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:41:38.761   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:41:38.761   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:41:38.761   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:41:38.761   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:41:38.805  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:41:38.847   297   521 I MDMCTBK : NetlinkHandler, power_supply subsys
03-16 12:41:38.847   297   521 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-16 12:41:38.847   297   521 I MDMCTBK : checkDefaultInst, current pid is = 297
03-16 12:41:38.847   297   521 I MDMCTBK : checkDefaultInst, pid match
03-16 12:41:38.847   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-16 12:41:38.847   297   521 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-16 12:41:38.847   297   521 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-16 12:41:38.899  3493  3598 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 12:41:41.006   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:41:51.010   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:42:01.015   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:42:11.019   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:42:21.024   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:42:31.028   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:42:41.033   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:42:51.038   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:43:01.042   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:43:11.047   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:43:21.051   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:43:31.056   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:43:41.061   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:43:51.065   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:44:01.070   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:44:11.076   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:44:21.080   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:44:31.085   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:44:41.089   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-16 12:44:51.094   317   421 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),03-16 12:44:52.145  7127  7127 D AndroidRuntime: 
03-16 12:44:52.145  7127  7127 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 12:44:52.149  7127  7127 D AndroidRuntime: CheckJNI is OFF
03-16 12:44:52.358  7127  7127 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-16 12:44:52.369   882  1091 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-16 12:44:52.421   882  1142 W PackageSettings: Skipping PackageSetting{28cbce15 com.example.hello/10568} due to missing metadata
03-16 12:44:52.446   882  1142 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
03-16 12:44:52.488  4266  4266 I art     : Explicit concurrent mark sweep GC freed 10790(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 7MB/12MB, paused 876us total 31.163ms
03-16 12:44:52.520  1757  2608 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-16 12:44:52.528   882  1226 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-16 12:44:52.560  1630  7154 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-16 12:44:52.580  1422  1422 I Keyboard.Facilitator: resetDictionaries() : en_US
03-16 12:44:52.588  1422  7157 I Keyboard.Facilitator.DecoderInitializer: run()
03-16 12:44:52.601   882  1512 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7159 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:44:52.623  1422  7157 I Decoder : createOrResetDecoder
03-16 12:44:52.630  1580  1580 I art     : Explicit concurrent mark sweep GC freed 2517(133KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 490us total 138.526ms
03-16 12:44:52.649   882   882 I art     : Explicit concurrent mark sweep GC freed 24441(1566KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 21MB/32MB, paused 4.737ms total 163.159ms
03-16 12:44:52.650   882  1142 I art     : WaitForGcToComplete blocked for 39.551ms for cause Explicit
03-16 12:44:52.658  1962  1973 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-16 12:44:52.660  1962  1962 I art     : Explicit concurrent mark sweep GC freed 3956(252KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/19MB, paused 1.856ms total 186.905ms
03-16 12:44:52.720  7159  7159 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 12:44:52.721  7159  7159 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 12:44:52.721  1422  7157 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-16 12:44:52.721  7159  7159 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 12:44:52.721  7159  7159 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
03-16 12:44:52.761   882   882 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 12:44:52.761   882   882 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 12:44:52.763   882  1264 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-16 12:44:52.763   882  1264 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
03-16 12:44:52.773  1422  7157 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-16 12:44:52.776  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-16 12:44:52.776  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-16 12:44:52.779  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-16 12:44:52.779  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-16 12:44:52.783  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-16 12:44:52.783  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-16 12:44:52.785  1422  7157 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-16 12:44:52.785  1422  7157 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-16 12:44:52.785  1422  7157 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-16 12:44:52.785  1422  7157 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-16 12:44:52.785  1422  7157 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-16 12:44:52.786  1422  7157 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-16 12:44:52.832   882  1551 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7182 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
03-16 12:44:52.864   882  1142 I art     : Explicit concurrent mark sweep GC freed 7712(642KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.416ms total 213.119ms
03-16 12:44:52.871   882  1530 I ActivityManager: Killing 6391:com.google.android.calendar/u0a49 (adj 15): empty #7
03-16 12:44:52.951  7127  7127 D AndroidRuntime: Shutting down VM
03-16 12:44:52.961   882  1431 W libprocessgroup: failed to open /acct/uid_10049/pid_6391/cgroup.procs: No such file or directory
03-16 12:44:52.995  7182  7182 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
03-16 12:44:53.028   882  1142 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7199 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-16 12:44:53.088   882  1309 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7220 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-16 12:44:53.095   882  1544 I ActivityManager: Killing 6855:com.google.android.gms:car/u0a16 (adj 15): empty #7
03-16 12:44:53.116   321   321 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 336us total 25.092ms
03-16 12:44:53.138   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 19.657ms
03-16 12:44:53.161   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 21.018ms
03-16 12:44:53.163   882  1665 W libprocessgroup: failed to open /acct/uid_10016/pid_6855/cgroup.procs: No such file or directory
03-16 12:44:53.169   882  1544 I ActivityManager: Killing 6669:com.android.vending/u0a32 (adj 15): empty #7
03-16 12:44:53.241   882  1253 W libprocessgroup: failed to open /acct/uid_10032/pid_6669/cgroup.procs: No such file or directory
03-16 12:44:53.251  1580  1580 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@13bce45f new=com.google.android.velvet.VelvetApplication@13bce45f
03-16 12:44:53.265  1962  7241 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-16 12:44:53.265  1962  7241 D AccountUtils: Clearing selected account for com.test.thalitest
03-16 12:44:53.331  1757  1757 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-16 12:44:53.331  1757  1757 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
03-16 12:44:53.333  1962  7241 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
03-16 12:44:53.376   882  1493 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7248 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 12:44:53.441  1962  7241 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: Could not unregister android package com.test.thalitest
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at com.google.android.gms.app.service.PackageBroadcastIntentOperation.onHandleIntent(:com.google.android.gms:51)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at com.google.android.chimera.IntentOperation.onHandleIntent(:com.google.android.gms:76)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at com.google.android.chimera.container.l.run(:com.google.android.gms:801)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 12:44:53.441  1962  7241 E PhenotypeInitializer: 	at java.lang.Thread.run(Thread.java:818)
03-16 12:44:53.456  1962  7259 W BaseAppContext: Using Auth Proxy for data requests.
03-16 12:44:53.467  1962  7259 W BaseAppContext: Using Auth Proxy for data requests.
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-16 12:44:53.476  1962  7259 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: Runtime exception while performing operation
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-16 12:44:53.477  1962  7259 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-16 12:44:53.477  1962  7259 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
03-16 12:44:53.488  1962  7241 I GMPM-SVC: App measurement is starting up, version: 8703
03-16 12:44:53.488  1962  7241 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
03-16 12:44:53.496   882  7273 E DropBoxManagerService: Can't write: system_app_wtf
03-16 12:44:53.496   882  7273 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-16 12:44:53.496   882  7273 E DropBoxManagerService: 	... 5 more
03-16 12:44:53.501   279   683 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
