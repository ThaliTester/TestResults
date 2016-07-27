#### Test 78968685da35147_thali06_HTC-HTC One M9 Logs


```
--------- beginning of main,
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: Leak found
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.google.android.volley.a.<init>(SourceFile:218)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.google.android.volley.a.a(SourceFile:186)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(SourceFile:176)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(SourceFile:139)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(SourceFile:112)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(SourceFile:458)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-27 08:53:02.508  7052  7067 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-27 08:53:02.578  3403  4209 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-27 08:53:02.578  3403  4209 D PhoneApp: -- N1 =1
07-27 08:53:02.578  3403  4209 D PhoneApp: -- N2 =0
07-27 08:53:02.578  3403  4209 D PhoneApp: -- N3 =0
07-27 08:53:02.588  3435  3882 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-27 08:53:02.588  3435  3882 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@a12d46a +
07-27 08:53:02.588  3435  3882 I Prism.WidgetManager: onLoadItems() +
07-27 08:53:02.618  7386  7451 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 4
07-27 08:53:02.618  7386  7451 D libc    : [NET] android_getaddrinfofornet-, err=8
--------- beginning of system
07-27 08:53:02.618  3435  3882 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-27 08:53:02.698  7570  7570 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-27 08:53:02.698  7570  7570 W HTCLOG  : mask=0x18
07-27 08:53:02.748  1114  3504 I ActivityManager: Start proc 7577:com.htc.camera/u0a9 for content provider com.htc.camera/.CameraContentProvider
07-27 08:53:02.748  7577  7577 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:02.748  7577  7577 W HTCLOG  : mask=0x18
07-27 08:53:02.808  3435  3882 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 08:53:02.858  7577  7577 V CameraProfiler: [PROFILE] Start timer 'CameraApplication.OnCreate.Start'
07-27 08:53:02.868  7577  7597 W CameraApplication: getCustomizedBundle() - No data
07-27 08:53:02.878  7577  7597 W HTCLOG  : use specified tag [CameraBase], func [0].
07-27 08:53:02.878  7577  7597 W HTCLOG  : mask=0x18
07-27 08:53:02.908  7577  7597 W FeatureConfig: mIsRawPhotoSupported:true
07-27 08:53:02.908  7577  7577 V CameraProfiler: [PROFILE] Start timer 'CameraApplication.OnCreate.End'
07-27 08:53:02.908  7577  7577 V CameraProfiler: [PROFILE][INTERVAL][CameraApplication.OnCreate.Start -> CameraApplication.OnCreate.End] 44.136 ms (44135730 ns)
07-27 08:53:02.948  7342  7569 W MediaManager: [DualLensScanUtil]	mmpCursor count is 0
07-27 08:53:02.948  1114  3438 I ActivityManager: Resuming delayed broadcast
07-27 08:53:02.968  1114  3438 I ActivityManager: Start proc 7599:com.htc.sdm/u0a64 for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver
07-27 08:53:02.968  1114  3504 D Process : killProcessQuiet, pid=6653
07-27 08:53:02.968  1114  3504 I ActivityManager: Killing 6653:com.htc.cs.pns:boot_complete/u0a119 (adj 15): empty #17
07-27 08:53:02.968  1114  3504 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-27 08:53:02.968  3435  3882 W asset   : Copying FileAsset 0xabfb0328 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-27 08:53:02.978  7570  7613 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-27 08:53:02.978  7570  7613 W HTCLOG  : mask=0x18
07-27 08:53:02.978  7599  7599 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:02.978  7599  7599 W HTCLOG  : mask=0x18
07-27 08:53:02.978  7570  7613 E cutils-trace: Error opening trace file: Permission denied (13)
07-27 08:53:03.028  7570  7570 D CustomizationManager: ====startRecUseTime====
07-27 08:53:03.028  7570  7570 D htc.customization.log.level:  is 
07-27 08:53:03.028  7570  7570 W CustomizationLogLevel: Level value is invalid, use default level 2
07-27 08:53:03.048  1114  3761 I ActivityManager: Recipient 6653
07-27 08:53:03.048  3435  3882 I Prism.WidgetManager: onLoadItems() -
07-27 08:53:03.048  3435  3882 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@a12d46a -
07-27 08:53:03.088  7570  7570 D CustomizationManager:  Read ACC file spent 0.031 (s)
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__001
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__002
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__016
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__031
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__032
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__102
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-27 08:53:03.088  7570  7570 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-27 08:53:03.088  7570  7570 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = application
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = system
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = Settings
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = ACC
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 42507
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 21902
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23420
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 22299
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 24002
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23210
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23205
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23806
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23430
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23408
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 27205
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-27 08:53:03.088  7570  7570 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-27 08:53:03.088  7570  7570 D CustomizationManager:  Read CID file spent 0.064 (s)
07-27 08:53:03.088  7570  7570 D CustomizationManager:  All configurations done spent 0.064 (s)
07-27 08:53:03.108  7599  7599 I SoundPicker: SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
07-27 08:53:03.118  7599  7599 I SoundPicker: SoundPickerReceiver [onReceive] startService
07-27 08:53:03.118  1114  2987 I ActivityManager: Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
07-27 08:53:03.128  1114  3761 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 7570 on display 0
07-27 08:53:03.128  7599  7635 I SoundPicker: TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
07-27 08:53:03.128  1114  1183 D PMS     : acquireHCC(3f03e8aa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1114 1000 null
07-27 08:53:03.128  7599  7635 V SoundPicker: TurnFileToMediaUriService fromMediaScanned = true
07-27 08:53:03.128  1114  1183 D PMS     : acquireHCC(230a0c9b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1114 1000 null
07-27 08:53:03.128  7599  7635 I SoundPicker: TurnFileToMediaUriService [turnFileUriIntoMediaUri]
07-27 08:53:03.128  1114  3761 V WindowManager: addAppToken: AppWindowToken{360fe576 token=Token{2ea68011 ActivityRecord{1600c838 u0 com.test.thalitest/.MainActivity t124}}} to stack=1 task=124 at 0
07-27 08:53:03.138  1114  3761 D PMS     : acquireWL(bf2d777): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
07-27 08:53:03.138  7570  7570 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-27 08:53:03.138  7570  7570 W HTCLOG  : mask=0x18
07-27 08:53:03.138  7570  7634 W HTCLOG  : use specified tag [Vector], func [0].
07-27 08:53:03.138  7570  7634 W HTCLOG  : mask=0x18
07-27 08:53:03.138  3435  3435 I FeedHostManager: [onPause]
07-27 08:53:03.138  3435  3435 I FeedProviderManager: onPause
07-27 08:53:03.138  1114  1174 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/5
07-27 08:53:03.138  3435  4851 I SocialFeedProvider: +onPause
07-27 08:53:03.138  3435  3435 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@38092050
07-27 08:53:03.138  3435  4851 I SocialFeedProvider: -onPause
07-27 08:53:03.138  3435  3435 I ContextualWidget: onPause
07-27 08:53:03.138  3435  3435 I ContextualWidget: notifyWidgetDeactive
07-27 08:53:03.138  7599  7635 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_gsm)
07-27 08:53:03.138  1114  1174 V WindowManager: Adding window Window{1eea2d4e u0 Starting com.test.thalitest} at 2 of 7 (after Window{1c1146a7 u0 com.htc.launcher/com.htc.launcher.Launcher})
07-27 08:53:03.158  1114  5169 I ActivityManager: Start proc 7637:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 08:53:03.158  1114  3547 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-27 08:53:03.158  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=1
07-27 08:53:03.158  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-27 08:53:03.158  7599  7635 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_cdma)
07-27 08:53:03.158  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=2
07-27 08:53:03.158  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-27 08:53:03.158  7599  7635 D RingtoneManager: getActualDefaultRingtoneUri(context, 1, mode_wcdma)
07-27 08:53:03.158  7637  7637 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:03.158  7637  7637 W HTCLOG  : mask=0x18
07-27 08:53:03.158  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/132 type=3
07-27 08:53:03.158  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/132
07-27 08:53:03.158  7599  7635 D RingtoneManager: getActualDefaultRingtoneUri(context, 2)
07-27 08:53:03.158  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=4
07-27 08:53:03.158  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-27 08:53:03.158  7599  7635 D RingtoneManager: getActualDefaultRingtoneUri(context, 4)
07-27 08:53:03.158  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/31 type=5
07-27 08:53:03.158  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/31
07-27 08:53:03.168  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/103 type=6
07-27 08:53:03.168  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/103
07-27 08:53:03.168  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/109 type=7
07-27 08:53:03.168  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/109
07-27 08:53:03.168  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=8
07-27 08:53:03.168  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
07-27 08:53:03.168  7599  7635 I SoundPicker: SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/105 type=9
07-27 08:53:03.168  7599  7635 W SoundPicker: TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/105
07-27 08:53:03.168  1114  5169 I ActivityManager: Resuming delayed broadcast
07-27 08:53:03.188  1114  3648 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
07-27 08:53:03.208  1114  1165 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-27 08:53:03.208  1114  1165 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1eea2d4e u0 Starting com.test.thalitest}
07-27 08:53:03.208  1114  1165 D StatusBarManagerService: hiding MENU key
07-27 08:53:03.208  3103  3103 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-27 08:53:03.208  3435  3435 I TrimMemoryManager: [trimMemory] 20
07-27 08:53:03.218  3103  3103 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-27 08:53:03.228  7637  7637 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-27 08:53:03.278  7637  7637 I LibraryLoader: Time to load native libraries: 25 ms (timestamps 31-56)
07-27 08:53:03.278  7637  7637 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:03.288  7637  7637 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35dc4a7}
07-27 08:53:03.288  7637  7637 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:03.298  7637  7637 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:53:03.298  7637  7637 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:53:03.308  7637  7637 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:03.308  7637  7637 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:53:03.328  7637  7662 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-27 08:53:03.338  7637  7666 D BluetoothAdapter: 16895316: getState() :  mService = null. Returning STATE_OFF
07-27 08:53:03.348  7637  7637 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-27 08:53:03.348  7637  7637 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
07-27 08:53:03.348  7637  7637 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
,07-27 08:53:03.358  7637  7637 W HTCLOG  : use specified tag [libEGL], func [3].,
07-27 08:53:03.358  7637  7637 W HTCLOG  : mask=0x18
,07-27 08:53:03.358  7637  7637 W HTCLOG  : use specified tag [libEGL], func [3].,
07-27 08:53:03.358  7637  7637 W HTCLOG  : mask=0x18
07-27 08:53:03.358  7637  7637 I Adreno  : QUALCOMM build                   : 065751b, 
07-27 08:53:03.358  7637  7637 I Adreno  : Build Date                       : 04/15/15
07-27 08:53:03.358  7637  7637 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-27 08:53:03.358  7637  7637 I Adreno  : Local Branch                     : 
07-27 08:53:03.358  7637  7637 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-27 08:53:03.358  7637  7637 I Adreno  : Remote Branch                    : NONE
07-27 08:53:03.358  7637  7637 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,07-27 08:53:03.428  7637  7672 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-27 08:53:03.438  1114  2933 V AlarmManager: sending alarm PendingIntent{29a58b61: PendingIntentRecord{19fa1686 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=46762, Int=0
,07-27 08:53:03.438  1114  2933 V AlarmManager: sending alarm PendingIntent{389477f3: PendingIntentRecord{cb54cb0 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1469602380707, Int=0
,07-27 08:53:03.438  3103  4515 D WeatherUtility: Weather sync is On,
07-27 08:53:03.438  3103  4515 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,07-27 08:53:03.448  7637  7637 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-27 08:53:03.458  7637  7637 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,07-27 08:53:03.468  7637  7637 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,07-27 08:53:03.468  7637  7637 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
07-27 08:53:03.468  7637  7637 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 08:53:03.498  7637  7684 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
07-27 08:53:03.498  7637  7684 W HTCLOG  : mask=0x18
,07-27 08:53:03.498  1114  3504 V WindowManager: Adding window Window{3684f26b u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1eea2d4e u0 Starting com.test.thalitest})
,07-27 08:53:03.538  7637  7637 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-27 08:53:03.538  7637  7637 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-27 08:53:03.538  7637  7637 W HTCLOG  : mask=0x18
07-27 08:53:03.538  7637  7637 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-27 08:53:03.538  7637  7637 W HTCLOG  : mask=0x18
,07-27 08:53:03.538  7471  7685 D Messaging: mNeedToUpdateDate2 start
,07-27 08:53:03.538  7471  7471 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist
,07-27 08:53:03.538  7471  7471 D MessageCustFlag: sku_id=118
07-27 08:53:03.548  7637  7684 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-27 08:53:03.548  7637  7684 W HTCLOG  : mask=0x18
07-27 08:53:03.548  7637  7684 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-27 08:53:03.548  7637  7684 W HTCLOG  : mask=0x18
07-27 08:53:03.548  7637  7684 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-27 08:53:03.548  7637  7684 W HTCLOG  : mask=0x18
07-27 08:53:03.548  7471  7471 D ReportIndicatorCache: startAsyncQueryReports --- , first = true
07-27 08:53:03.548  7471  7505 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
07-27 08:53:03.548  7471  7471 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@aac23f9
,07-27 08:53:03.548  7471  7504 D MmsAsyncWorkHandler: 
07-27 08:53:03.548  7471  7504 D MmsAsyncWorkHandler: HM tk = 20002
07-27 08:53:03.548  7637  7684 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-27 08:53:03.548  7637  7684 W HTCLOG  : mask=0x18
,07-27 08:53:03.558  7471  7471 D DraftCache: [DraftCache/1] DraftCache.constructor
07-27 08:53:03.558  7471  7471 D DraftCache: [DraftCache/1] refresh
,07-27 08:53:03.558  3403  4545 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
07-27 08:53:03.558  3403  4545 D MmsSmsV2Provider:  slotId = -1
07-27 08:53:03.558  3403  4545 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
07-27 08:53:03.558  7637  7684 W HTCLOG  : use specified tag [Surface], func [3].
07-27 08:53:03.558  7637  7684 W HTCLOG  : mask=0x18
07-27 08:53:03.558  7637  7684 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-27 08:53:03.558  7637  7684 W HTCLOG  : mask=0x18
07-27 08:53:03.558  7637  7684 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-27 08:53:03.558  7637  7684 W HTCLOG  : mask=0x18
07-27 08:53:03.558  3403  3441 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
07-27 08:53:03.558  3403  3441 D MmsSmsV2Provider:  slotId = -1
07-27 08:53:03.558  3403  3441 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
07-27 08:53:03.558  7471  7689 D MmsConfig: Start to get Carrier ID
07-27 08:53:03.558  7471  7688 I Messaging: mccmnc> 
,07-27 08:53:03.568  3403  4186 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,07-27 08:53:03.568  7471  7471 D MmsConfig: networkCode: 
,07-27 08:53:03.578  3403  3441 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60,
,07-27 08:53:03.578  3403  3441 D MmsSmsV2Provider:  slotId = -1
,07-27 08:53:03.578  3403  3441 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null,
,07-27 08:53:03.578  7471  7692 D Messaging: ViewCache CreatePreloadOnlyConversationList,
07-27 08:53:03.578  7471  7692 D MessageCustFlag: sense_version=7.0
07-27 08:53:03.578  3403  4545 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
07-27 08:53:03.578  7471  7471 D HfmClient: getIHFMServiceHMSApiLevel: +++
07-27 08:53:03.578  7471  7471 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
,07-27 08:53:03.578  7471  7471 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak,
07-27 08:53:03.578  7471  7692 D Jerry   : start to preload cursor >>>>>>>
07-27 08:53:03.588  3403  3441 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
07-27 08:53:03.588  7471  7471 D HfmClient: getIHFMServiceHMSApiLevel: Level = 1
07-27 08:53:03.588  7471  7471 D HfmClient: HfmServiceHMS API Level = 1
07-27 08:53:03.588  3403  3441 D MmsSmsV2Provider:  slotId = -1
07-27 08:53:03.588  3403  3441 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
07-27 08:53:03.588  3403  3403 D IccSmsInterfaceManager: [IccSmsInterfaceManager] Cannot get carrier id
07-27 08:53:03.588  7471  7689 D MmsConfig: Carrier ID is NULL
07-27 08:53:03.588  3403  4017 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
07-27 08:53:03.588  3403  4017 D MmsSmsV2Provider:  slotId = -1
07-27 08:53:03.588  3403  4017 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
07-27 08:53:03.588  7471  7686 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
07-27 08:53:03.588  7471  7685 D Messaging: mNeedToUpdateDate2: false
07-27 08:53:03.588  3403  4186 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
07-27 08:53:03.598  7471  7504 D DraftCache: [DraftCache/126] rebuildCache
07-27 08:53:03.598  7471  7471 D ew      : createReceiver
07-27 08:53:03.598  7471  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-27 08:53:03.598  1114  3438 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-27 08:53:03.598  3403  4545 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 106
07-27 08:53:03.598  3403  4545 D Jerry   : URI_DRAFT
07-27 08:53:03.598  7471  7697 D ew      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
07-27 08:53:03.608  7471  7504 D DraftCache: hasDraft() = false mNeedNotifyChange = true
07-27 08:53:03.608  7471  7504 D DraftCache: [DraftCache/126] rebuildCache time: 1
07-27 08:53:03.608  7471  7697 D ew      : /storage/emulated/0 : mounted
07-27 08:53:03.608  7471  7471 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
07-27 08:53:03.608  3403  4017 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
07-27 08:53:03.608  3403  4017 V MmsProvider: Update uri=content://mms, match=0
07-27 08:53:03.608  3403  4017 V MmsProvider: selection=st=129 AND m_type!=134
07-27 08:53:03.608  3403  3441 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
07-27 08:53:03.608  3403  3441 D MmsSmsV2Provider:  slotId = -1
07-27 08:53:03.608  7471  7471 W SystemReader: Cannot find support_cw, use default value instead
07-27 08:53:03.608  1114  3761 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-27 08:53:03.608  7471  7471 W SystemReader: Cannot find qct_8960_interface, use default value instead
07-27 08:53:03.608  7471  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-27 08:53:03.608  7471  7700 D Messaging: Reset downloading state: 0
07-27 08:53:03.608  7471  7700 V Messaging: Start TransactionService after 2 minutes from now
07-27 08:53:03.618  7471  7692 D Messaging: ViewCache CreatePreload
07-27 08:53:03.618  7471  7692 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
07-27 08:53:03.618  7471  7692 D Cust_MMSMS: _has_set_default_values_2=true
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size57
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size48
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size0
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size57
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size66
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size74
07-27 08:53:03.618  7471  7692 D TextSizeManager: [get_list_body_TextSize]__size83
,07-27 08:53:03.618  7471  7692 D MsgPreferenceUtils: def_index: 0
,07-27 08:53:03.628  1114  5242 I art     : Explicit concurrent mark sweep GC freed 20563(1102KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.631ms total 133.974ms
07-27 08:53:03.628  7637  7637 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@14756f1c, mServedView=org.apache.cordova.engine.SystemWebView{9830725 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@249580fa
07-27 08:53:03.628  7471  7692 D MsgPreferenceUtils: globalIndex = 2
,07-27 08:53:03.628  1114  5169 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-27 08:53:03.628  7471  7692 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
07-27 08:53:03.628  1114  3761 I InputMethodManagerService: Disable input method client, pid=3435
07-27 08:53:03.628  1114  3761 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-27 08:53:03.628  1114  3761 I InputMethodManagerService: Enable input method client, pid=7637
07-27 08:53:03.628  3103  3103 I PhoneStatusBar: setImeWindowStatus(false,false)
07-27 08:53:03.628  1114  1174 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +489ms
,07-27 08:53:03.628  1114  3504 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
07-27 08:53:03.628  7471  7692 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,07-27 08:53:03.638  7471  7692 D MsgPreferenceUtils: phone state: true
07-27 08:53:03.638  7471  7692 D MsgPreferenceUtils: sd state: false
07-27 08:53:03.638  7471  7692 D MsgPreferenceUtils: vIndex = 1
,07-27 08:53:03.638  1114  3226 D PMS     : releaseWL(bf2d777): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-27 08:53:03.658  7471  7717 D RcsWorkingHandler: handler msg:{ when=0 what=1 target=com.htc.sense.mms.rcschat.bo }
,07-27 08:53:03.658  7471  7717 D RcsWorkingHandler: not support Rcs, return
07-27 08:53:03.658  7471  7692 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
07-27 08:53:03.658  7471  7692 D PersonalizeUtils: isHTCThemeChange_full isChange= false
07-27 08:53:03.658  7471  7692 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
07-27 08:53:03.658  7471  7692 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
07-27 08:53:03.658  7471  7692 D PersonalizeUtils: isHTCThemeChange_CC equal time= 1440293058,old=1440293058
07-27 08:53:03.658  7471  7692 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,07-27 08:53:03.678  7637  7637 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7637
,07-27 08:53:03.688  1114  3648 I ActivityManager: Resuming delayed broadcast
,07-27 08:53:03.698  1114  3761 I ActivityManager: Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,07-27 08:53:03.698  1114  1134 I ActivityManager: Resuming delayed broadcast
,07-27 08:53:03.718  1114  1134 I ActivityManager: Start proc 7721:com.htc.updater/u0a68 for broadcast com.htc.updater/.UpdaterReceiver
,07-27 08:53:03.718  7721  7721 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:03.718  1114  5194 I ActivityManager: Killing 6702:tv.peel.app/u0a123 (adj 15): empty #17
07-27 08:53:03.718  7721  7721 W HTCLOG  : mask=0x18
07-27 08:53:03.718  1114  5194 D Process : killProcessQuiet, pid=6702
07-27 08:53:03.718  1114  5194 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-27 08:53:03.768  7637  7637 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:53:03.808  1114  5169 I ActivityManager: Recipient 6702
,07-27 08:53:03.858  7637  7704 D jxcore_app_log: JniHelper::setJavaVM(0xaabaeb70), pthread_self() = -1414199496
,07-27 08:53:03.858  7637  7704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:53:03.858  7637  7704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:53:03.858  7637  7704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
,07-27 08:53:03.858  7637  7704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:53:03.858  7637  7704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:53:03.858  7637  7704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3447549e added. We now have 1 listener(s)
07-27 08:53:03.858  1114  3504 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,07-27 08:53:03.858  7637  7704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
,07-27 08:53:03.858  7637  7704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
,07-27 08:53:03.858  7637  7704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:53:03.858  7637  7704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true,
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 08:53:03.868  7637  7704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10bd0395 added. We now have 1 listener(s)
07-27 08:53:03.868  7637  7704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:53:03.868  1114  1133 I ActivityManager: Delay finish: com.htc.updater/.UpdaterReceiver
,07-27 08:53:03.868  7637  7704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:53:03.868  1114  2947 D WifiService: New client listening to asynchronous messages
07-27 08:53:03.868  7637  7704 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-27 08:53:03.868  7637  7704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:53:03.868  7637  7704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:53:03.868  7637  7704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:53:03.868  7637  7704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 08:53:03.878  7721  7744 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-27 08:53:03.878  7721  7744 W HTCLOG  : mask=0x18
,07-27 08:53:03.878  7637  7704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:53:03.878  1114  3777 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-27 08:53:03.878  7637  7704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
,07-27 08:53:03.878  7637  7704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:53:03.878  7637  7704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:53:03.878  7637  7704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-27 08:53:03.878  7637  7704 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:53:03.878  7721  7721 V UpdaterAPK | DownloadService: Service onStart
07-27 08:53:03.878  7637  7704 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:53:03.878  7721  7746 V UpdaterAPK | DownloadService: Updating for startId 1
,07-27 08:53:03.888  7721  7746 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,07-27 08:53:03.888  7721  7746 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@9d75f3e on behalf of 7721
,07-27 08:53:03.898  7721  7744 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection[0] is status; selection is update_type=?; selectionArgs[0] is FOTA; sort is null.
,07-27 08:53:03.898  7721  7744 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@37aca19f on behalf of 7721
07-27 08:53:03.898  1114  3664 I ActivityManager: Resuming delayed broadcast
07-27 08:53:03.898  7721  7746 V UpdaterAPK | DownloadService: Nothing left; stopped
07-27 08:53:03.898  7721  7721 V UpdaterAPK | DownloadService: Service onDestroy
07-27 08:53:03.898  1114  5169 D PMS     : acquireWL(2796bf72): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 7124 10008 null
07-27 08:53:03.898  7637  7637 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-27 08:53:03.898  1114  3504 I ActivityManager: Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,07-27 08:53:03.908  7124  7749 E SQLiteLog: (284) automatic index on view_events(_id)
,07-27 08:53:03.908  1114  5194 I ActivityManager: Delaying start of: ServiceRecord{9ff3040 u0 com.htc.updater/.service.UpdaterCheckIntranetService}
,07-27 08:53:03.918  1114  5169 D PMS     : releaseWL(2796bf72): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,07-27 08:53:04.078  7721  7750 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(0)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: ,	at android.graphics.Color.parseColor(Color.java:216)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.setAlternativeColor(HtcThemeUtils.java:611)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.checkResourceSrc(HtcThemeUtils.java:534)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.createResourceInstance(HtcThemeUtils.java:486)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.init(HtcThemeUtils.java:476)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils$CommonCategoryResources.access$600(HtcThemeUtils.java:451)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcThemeUtils.init(HtcThemeUtils.java:390)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.lib1.cc.util.HtcCommonUtil.initTheme(HtcCommonUtil.java:315)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.updater.util.NotificationUtil.getNotificationThemeColor(NotificationUtil.java:472)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.updater.util.NotificationUtil.notifyDownload(NotificationUtil.java:152)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:259)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:71)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:04.078  7721  7750 W HtcThemeUtils: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:04.078  7721  7750 W HTCLOG  : use specified tag [asset], func [0].
07-27 08:53:04.078  7721  7750 W HTCLOG  : mask=0x18
07-27 08:53:04.078  7721  7750 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
07-27 08:53:04.078  7721  7750 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
07-27 08:53:04.088  1114  1114 D ValidateNoPeople: setContact(com.htc.updater,0.0,false)
07-27 08:53:04.088  1114  1114 D PMS     : acquireWL(2f20451f): PARTIAL_WAKE_LOCK  *vibrator* 0x1 1114 1000 WorkSource{10068}
07-27 08:53:04.098  3184  3210 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837684, tag: null, isClearable: false, isForDotMatrix: false
07-27 08:53:04.108  1114  3438 I ActivityManager: Resuming delayed broadcast
,07-27 08:53:04.108  3103  3103 I RemoteViews: apply:com.htc.updater 1 7 2 37
,07-27 08:53:04.118  3103  3103 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,07-27 08:53:04.118  1114  3438 I ActivityManager: Start proc 7755:com.htc.autobot/u0a27 for broadcast com.htc.autobot/.AlarmReceiver
07-27 08:53:04.118  1114  3777 D Process : killProcessQuiet, pid=6764,
,07-27 08:53:04.118  1114  3777 I ActivityManager: Killing 6764:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
07-27 08:53:04.118  1114  3777 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-27 08:53:04.138  7755  7755 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:04.138  7755  7755 W HTCLOG  : mask=0x18
,07-27 08:53:04.188  1114  3648 I ActivityManager: Recipient 6764
,07-27 08:53:04.228  1114  1183 D PMS     : releaseHCC(3f03e8aa): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-27 08:53:04.228  1114  1183 D PMS     : releaseHCC(230a0c9b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-27 08:53:04.248  7755  7755 D AlarmReceiver: ACTION_RESTART_INTENT,
,07-27 08:53:04.248  1114  3761 I ActivityManager: Delay finish: com.htc.autobot/.AlarmReceiver
,07-27 08:53:04.248  7755  7755 D LocalBluetoothProfile: getPriorityOnValue = 100
,07-27 08:53:04.248  7755  7755 D LocalBluetoothProfile: getPriorityOffValue = 0
,07-27 08:53:04.258  7755  7755 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,07-27 08:53:04.258  7755  7755 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1),
,07-27 08:53:04.278  7755  7780 D HtcModeClient: start the htcmodeservice thread,
07-27 08:53:04.278  7755  7780 D HtcModeClient: initCanAgent
07-27 08:53:04.278  7755  7780 I CANMesgAgentLocalSocket: CANAgent Id = 0
,07-27 08:53:04.278  7755  7780 D HtcModeClient: sense info: version = none, id = 2
,07-27 08:53:04.288  7755  7780 D HtcModeClient: display info: width = 1080, height = 1776
07-27 08:53:04.288  7755  7780 D HtcModeClient: display info: mode = 10
,07-27 08:53:04.378  7755  7755 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,07-27 08:53:04.378  7755  7755 D HtcModeClient: connectState: BT_TURNON_BYME = false,
,07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: CONNECTION_READY = false
07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: PHONE_PULGIN = false
07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: Force_AWAKE = false
07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: PHONE_PULGIN = true
07-27 08:53:04.388  7755  7755 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,07-27 08:53:04.448  1114  7754 D PMS     : releaseWL(2f20451f): PARTIAL_WAKE_LOCK  *vibrator* 0x1 WorkSource{10068}
,07-27 08:53:04.638  7637  7748 W jxcore-log: Initializing JXcore engine,
07-27 08:53:04.638  7637  7748 W jxcore-log: JXcore engine is ready
,07-27 08:53:04.678  7637  7748 W jxcore-log: Starting JXcore engine,
,07-27 08:53:04.748  7637  7748 W jxcore-log: Platform android
07-27 08:53:04.748  7637  7748 W jxcore-log: 
07-27 08:53:04.748  7637  7748 W jxcore-log: Process ARCH arm
07-27 08:53:04.748  7637  7748 W jxcore-log: 
,07-27 08:53:04.858  7637  7748 I jxcore-log: JXcore Cordova bridge is ready!,
07-27 08:53:04.858  7637  7748 I jxcore-log: 
07-27 08:53:04.858  7637  7748 W jxcore-log: JXcore engine is started,
,07-27 08:53:04.868  7637  7704 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 08:53:04.868  7637  7637 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:53:04.878  7637  7748 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-27 08:53:04.878  7637  7748 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-27 08:53:04.898  7637  7637 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
07-27 08:53:04.898  7637  7637 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-27 08:53:04.938  1114  3226 D PMS     : acquireWL(9510104): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1114 1000 null
07-27 08:53:04.938  7637  7704 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
,07-27 08:53:04.948  7637  7637 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
07-27 08:53:04.948  7637  7637 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-27 08:53:04.958  1114  3547 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
,07-27 08:53:04.968  3435  3435 I FeedHostManager: [onResume],
07-27 08:53:04.968  3435  3435 I FeedProviderManager: onResume
07-27 08:53:04.968  3435  4851 I SocialFeedProvider: +onResume
07-27 08:53:04.968  3435  4851 I SocialFeedProvider: updateAccounts - Accounts is no change
07-27 08:53:04.968  3435  4851 I SocialFeedProvider: -onResume
07-27 08:53:04.968  3435  3435 I ConnectivityHelper: [getCurrentConnectionType] no network connection
,07-27 08:53:04.968  3435  3435 I ContextualWidget: onResume,
07-27 08:53:04.968  3435  3435 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-27 08:53:04.968  3435  3435 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-27 08:53:04.968  3435  3435 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-27 08:53:04.968  3435  4005 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
,07-27 08:53:04.968  3435  4005 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-27 08:53:04.968  1114  3504 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:53:04.978  1114  3777 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:53:04.978  1114  3226 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-27 08:53:04.978  1114  1133 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-27 08:53:04.978  1114  1165 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-27 08:53:04.978  3103  3103 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-27 08:53:04.978  1114  1165 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1c1146a7 u0 com.htc.launcher/com.htc.launcher.Launcher}
07-27 08:53:04.978  3103  3103 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-27 08:53:04.978  1114  1165 D StatusBarManagerService: hiding MENU key
,07-27 08:53:04.988  3435  3435 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-27 08:53:04.988  3435  3435 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-27 08:53:04.988  3103  3103 I PhoneStatusBar: setImeWindowStatus(false,false)
07-27 08:53:04.988  1114  3504 I InputMethodManagerService: Disable input method client, pid=7637
07-27 08:53:04.988  1114  3504 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-27 08:53:04.998  7637  7637 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
07-27 08:53:04.988  1114  3504 I InputMethodManagerService: Enable input method client, pid=3435
,07-27 08:53:05.018  1114  3777 D PMS     : releaseWL(9510104): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-27 08:53:05.028  3103  3103 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-27 08:53:05.028  1114  1165 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-27 08:53:05.028  3103  3103 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false,
07-27 08:53:05.028  1114  1165 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1c1146a7 u0 com.htc.launcher/com.htc.launcher.Launcher}
07-27 08:53:05.028  1114  1165 D StatusBarManagerService: hiding MENU key
,07-27 08:53:05.038  1114  1164 D Process : killProcessQuiet, pid=6786,
07-27 08:53:05.038  1114  1164 I ActivityManager: Killing 6786:com.android.smith/1000 (adj 15): empty #17
07-27 08:53:05.048  1114  1164 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,07-27 08:53:05.058  3435  7785 D HtcTelephonyManager: wrong phone slot in non-dual projects
,07-27 08:53:05.108  3435  7785 D HtcTelephonyManager: wrong phone slot in non-dual projects,
,07-27 08:53:05.118  7783  7783 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-27 08:53:05.118  7783  7783 W HTCLOG  : mask=0x18
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfofornet-, err=8
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024,
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfo_proxy+
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-27 08:53:05.118   549  7787 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-27 08:53:05.118   549  7787 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-27 08:53:05.118   549  7787 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-27 08:53:05.118   549  7787 D libc    : [NET] android_getaddrinfofornet-, err=7
07-27 08:53:05.118  3435  7785 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,07-27 08:53:05.118  3435  7785 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-27 08:53:05.118  3435  7785 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-27 08:53:05.118  3435  7785 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:05.118  3435  7785 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:05.118  3435  7785 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:05.118  3435  7785 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:05.118  3435  7785 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-27 08:53:05.118  3435  7785 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-27 08:53:05.118  3435  7785 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-27 08:53:05.118  3435  7785 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29),
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-27 08:53:05.118  3435  7785 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
07-27 08:53:05.118  3435  7785 W System.err: 	... 9 more
07-27 08:53:05.148  1114  3504 I ActivityManager: Recipient 6786
,07-27 08:53:05.258  7637  7637 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
07-27 08:53:05.258  7637  7637 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-27 08:53:05.258  7637  7637 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 08:53:05.258  7637  7637 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-27 08:53:05.258  7637  7637 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 08:53:05.258  7637  7637 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 08:53:05.258  7637  7637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 08:53:05.258  7637  7637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 08:53:05.258  7637  7637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3447549e removed from the list
07-27 08:53:05.258  7637  7637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 08:53:05.258  7637  7637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10bd0395 removed from the list
07-27 08:53:05.258  7637  7637 D io.jxcore.node.ConnectivityMonitor: stop
07-27 08:53:05.258  7637  7637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-27 08:53:05.258  7637  7637 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 08:53:05.308  7637  7637 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7637
,07-27 08:53:05.378  7783  7790 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-27 08:53:05.378  7783  7790 W HTCLOG  : mask=0x18
07-27 08:53:05.378  7783  7790 E cutils-trace: Error opening trace file: Permission denied (13),
,07-27 08:53:05.418  7783  7783 D CustomizationManager: ====startRecUseTime====,
07-27 08:53:05.418  7783  7783 D htc.customization.log.level:  is 
07-27 08:53:05.418  7783  7783 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-27 08:53:05.478  7783  7783 D CustomizationManager:  Read ACC file spent 0.033 (s)
,07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__001
,07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__002
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__016
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__031
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__032
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__102
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__A07
,07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-27 08:53:05.488  7783  7783 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-27 08:53:05.488  7783  7783 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = application
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = system
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = Settings,
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 42507
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 21902
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23420
,07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 22299
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 24002
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23210
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23205
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23806
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23430
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23408
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 27205
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-27 08:53:05.488  7783  7783 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-27 08:53:05.488  7783  7783 D CustomizationManager:  Read CID file spent 0.070 (s)
07-27 08:53:05.488  7783  7783 D CustomizationManager:  All configurations done spent 0.070 (s)
,07-27 08:53:05.518  3435  4157 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-27 08:53:05.528  1114  3761 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=7783, uid=2000
,07-27 08:53:05.528  1114  1164 D Process : killProcessQuiet, pid=7637
07-27 08:53:05.528  1114  1164 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-27 08:53:05.528  1114  1164 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
07-27 08:53:05.528  1114  1164 I ActivityManager: Killing 7637:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-27 08:53:05.568  1114  1185 W PackageSettings: Skipping PackageSetting{e8dce2 com.example.hello/10193} due to missing metadata
,07-27 08:53:05.588   572   572 W HTCLOG  : use specified tag [Vector], func [0].
07-27 08:53:05.588   572   572 W HTCLOG  : mask=0x18
,07-27 08:53:05.618  1114  3777 I ActivityManager: Recipient 7637
07-27 08:53:05.618  1114  2947 D WifiService: Client connection lost with reason: 4
07-27 08:53:05.618  3240  3240 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-27 08:53:05.618  3240  3240 W HTCLOG  : mask=0x18
07-27 08:53:05.618  3240  3240 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{d24e310 uid 10000 pid 7637} (c)'
,07-27 08:53:05.638  1114  3777 W ActivityManager: Spurious death for ProcessRecord{2928822b 7637:com.test.thalitest/u0a0}, curProc for 7637: null
,07-27 08:53:05.638  1114  1185 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-27 08:53:05.678  1114  2943 D PMS     : acquireWL(362ab688): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1114 1000 null
07-27 08:53:05.688  3184  3184 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
07-27 08:53:05.688  3184  3184 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-27 08:53:05.688  1114  2944 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
07-27 08:53:05.688  5022  5022 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-27 08:53:05.688  5022  5022 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-27 08:53:05.688  5022  5022 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
07-27 08:53:05.688  5022  5022 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
07-27 08:53:05.698  1114  3664 D PMS     : acquireWL(f3ec446): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4222 10020 WorkSource{10020 com.google.android.gms}
,07-27 08:53:05.698  5022  5022 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
07-27 08:53:05.698  4222  4601 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 08:53:05.698  1114  2936 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-27 08:53:05.698  5022  5022 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-27 08:53:05.698  1114  3442 D PMS     : releaseWL(f3ec446): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-27 08:53:05.698  5022  5022 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-27 08:53:05.698  5022  5022 D [MirrorLinkServer]d: onApplicationRemoved
07-27 08:53:05.698  5022  5022 I [MirrorLinkServer]d: Package name found : com.test.thalitest
07-27 08:53:05.698  5022  7805 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-27 08:53:05.698  5022  5022 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
,07-27 08:53:05.698  5022  5022 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-27 08:53:05.698  5022  5022 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-27 08:53:05.698  5022  5022 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-27 08:53:05.698  5022  5022 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
07-27 08:53:05.698  3687  4140 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-27 08:53:05.708  3687  4140 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-27 08:53:05.718  3687  4140 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,07-27 08:53:05.718  1114  2943 D PMS     : releaseWL(362ab688): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-27 08:53:05.718  3687  4140 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-27 08:53:05.718  1114  2944 V NetworkPolicy: writePolicyLocked()
,07-27 08:53:05.728  1114  1163 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-27 08:53:05.738  1114  2944 D NetworkPolicy: notifyPoliciesChangeLocked: no change,
07-27 08:53:05.738  1114  2944 V NetworkPolicy: updateNetworkEnabledLocked()
07-27 08:53:05.738  3687  4140 E ExternalAccountType: Unsupported attribute readOnly
07-27 08:53:05.738  1114  2944 V NetworkPolicy: updateNotificationsLocked()
07-27 08:53:05.738  3403  3403 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,07-27 08:53:05.748  1114  1163 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-27 08:53:05.818  1114  1114 W PackageManager: Unable to load service info ResolveInfo{b5c23e7 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-27 08:53:05.818  1114  1114 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-27 08:53:05.818  1114  1114 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-27 08:53:05.828  3374  3374 D Nfc-Utils: isNxpCodebase: isNxp=false
,07-27 08:53:05.848  1114  1185 I art     : Explicit concurrent mark sweep GC freed 24578(1896KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 1.814ms total 177.530ms
,07-27 08:53:05.858  7783  7783 I art     : System.exit called, status: 0,
07-27 08:53:05.858  7783  7783 W HTCLOG  : use specified tag [Vector], func [0].
07-27 08:53:05.858  7783  7783 W HTCLOG  : mask=0x18
,07-27 08:53:05.898  1114  2933 V AlarmManager: sending alarm PendingIntent{1cc11b53: PendingIntentRecord{9be1c90 android broadcastIntent}}, i=NextAlarmTracker.trigger, t=0, cnt=1, w=1469602385913, Int=0,
,07-27 08:53:05.908  1114  1164 I ActivityManager: Waited long enough for: ServiceRecord{a5a8fe9 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
07-27 08:53:05.908  1114  1164 I ActivityManager: Resuming delayed broadcast
,07-27 08:53:05.928  1114  1164 I ActivityManager: Start proc 7808:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
,07-27 08:53:05.948   590   590 I art     : Explicit concurrent mark sweep GC freed 8660(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 110us total 19.963ms,
,07-27 08:53:05.948  7808  7808 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:05.948  7808  7808 W HTCLOG  : mask=0x18
,07-27 08:53:05.968   590   590 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 131us total 19.019ms
,07-27 08:53:05.978   590   590 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 68us total 15.842ms
07-27 08:53:05.978  1114  1114 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 08:53:05.978  1114  1114 D PMS     : acquireWL(dffe6a2): PARTIAL_WAKE_LOCK  NextAlarmTracker 0x1 1114 1000 null
07-27 08:53:05.988  7808  7808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
07-27 08:53:05.988  1114  1134 I ActivityManager: Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,07-27 08:53:05.988  3435  3882 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-27 08:53:05.988  3435  3882 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-27 08:53:05.988  7808  7830 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-27 08:53:05.988  7808  7830 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-27 08:53:05.998  7808  7830 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,07-27 08:53:06.008  7808  7830 D PowerUsageService: repeat time = 1469603286021,
,07-27 08:53:06.098  7808  7830 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8
,07-27 08:53:06.118  7808  7830 D PowerUtils: getUserIdOfProcess, curUserId = 0,
,07-27 08:53:06.118  7808  7830 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-27 08:53:06.128  7808  7830 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-27 08:53:06.128  1114  3761 E SQLiteLog: (3850) statement aborts at 36: [INSERT INTO secure(name,value) VALUES (?,?)] disk I/O error
07-27 08:53:06.128  1114  3761 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-27 08:53:06.128  1114  3761 W HTCLOG  : mask=0x18
07-27 08:53:06.128  1114  3761 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.settings/databases/settings.db, handle: 0x5573ab2bf0,
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: Error inserting ...
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1425),
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at com.android.providers.settings.SettingsProvider.insertForUser(SettingsProvider.java:1528)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:847)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:319)
07-27 08:53:06.128  1114  3761 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
,07-27 08:53:06.138  7808  7830 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-27 08:53:06.138  7808  7830 W HTCLOG  : mask=0x18
,07-27 08:53:06.138  7808  7830 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.query(SmartSyncProvider.java:172)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.queryData(PowerUsageHelper.java:1994)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.genScreenOffList(PowerUsageHelper.java:1213)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.calcPower(PowerUsageService.java:260)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: ,	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:134)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:06.138  7808  7830 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:06.148  7808  7830 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:339)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:261)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1333)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:1900)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.calcPower(PowerUsageService.java:312)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:134)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:06.148  7808  7830 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: bulkInsertData(), Exception: 
,07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:339)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:261)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1333)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:1900)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at com.htc.htcpowermanager.battery.PowerUsageService.calcPower(PowerUsageService.java:312)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:134)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:06.148  7808  7830 E PowerUsageList:PowerUsageHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:06.148  1114  2987 I ActivityManager: Resuming delayed broadcast
07-27 08:53:06.148  7808  7830 E PowerUsageService: bulk insert error
07-27 08:53:06.158  1114  2987 I ActivityManager: Start proc 7831:com.google.android.gm/u0a95 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
07-27 08:53:06.168  7831  7831 W HTCLOG  : use specified tag [FDManager], func [0].
07-27 08:53:06.168  7831  7831 W HTCLOG  : mask=0x18
,07-27 08:53:06.258  7831  7856 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider,
,07-27 08:53:06.258  7831  7855 I Gmail   : getAccountsCursor
,07-27 08:53:06.268  4222  4222 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:53:06.308  1114  3777 I ActivityManager: Start proc 7858:com.google.android.gm.exchange/u0a156 for service com.google.android.gm.exchange/com.android.exchange.service.EasService,
,07-27 08:53:06.308  1114  3438 D Process : killProcessQuiet, pid=6681
07-27 08:53:06.308  1114  3438 I ActivityManager: Killing 6681:com.htc.cs.pns/u0a119 (adj 15): empty #17
07-27 08:53:06.308  1114  3438 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-27 08:53:06.318  7858  7858 W HTCLOG  : use specified tag [FDManager], func [0].,
07-27 08:53:06.318  7858  7858 W HTCLOG  : mask=0x18
,07-27 08:53:06.408  7755  7780 I HtcModeClient: handler message = 4011
,07-27 08:53:06.408  7755  7780 D HtcModeClient: getConnectionCheckCount first 0
07-27 08:53:06.408  7755  7780 D HtcModeClient: getConnectionCheckCount count = 1
07-27 08:53:06.408  7755  7780 E HtcModeClient: Check connection and retry 2 times.,
,07-27 08:53:06.408  7755  7780 D HtcModeClient: setConnectionCheckCount count = 2
07-27 08:53:06.408  7755  7780 D HtcModeClient: setupRestart delayedTime = 3000
,07-27 08:53:06.408  7755  7782 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,07-27 08:53:06.468  1114  5194 I ActivityManager: Recipient 6681,
,07-27 08:53:06.528  7831  7864 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-27 08:53:06.538  1114  2933 V AlarmManager: sending alarm PendingIntent{1779ed87: PendingIntentRecord{22b374b4 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1469602386380, Int=0,
07-27 08:53:06.548  7831  7872 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider,
,07-27 08:53:06.568  7831  7881 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-27 08:53:06.568  7831  7881 W HTCLOG  : mask=0x18
,07-27 08:53:06.568  7831  7881 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	,at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.568  7831  7881 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.578  7755  7755 D HtcModeClient: setBtPriority priority = on
07-27 08:53:06.578  7755  7755 D HtcModeClient: unbindBlueToothService
,07-27 08:53:06.578  7755  7755 D HtcModeClient: Don't start project servcice
07-27 08:53:06.578  7755  7755 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
07-27 08:53:06.578  7755  7755 D HtcModeClient: connectState: CONNECTION_READY = false
07-27 08:53:06.578  7755  7755 D SilentMusic: call stop
07-27 08:53:06.578  7755  7755 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
07-27 08:53:06.578  7755  7781 W CANMesgAgentLocalSocket: read the terminate packet, so break
,07-27 08:53:06.578  7831  7856 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	a,t com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:64)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:42)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoader.java:312)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:57)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.578  7831  7856 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:53:06.578  7831  7881 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #5
07-27 08:53:06.578  7831  7881 E AndroidRuntime: Process: com.google.android.gm, PID: 7831
07-27 08:53:06.578  7831  7881 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	,at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.578  7831  7881 E AndroidRuntime: 	... 3 more
07-27 08:53:06.588  7755  7755 D HtcModeClient: onDestroy
07-27 08:53:06.588  1114  5194 I ActivityManager: Killing 6871:com.htc.usage/1000 (adj 15): empty #17
07-27 08:53:06.588  1114  5194 D Process : killProcessQuiet, pid=6871
,07-27 08:53:06.588  1114  5194 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-27 08:53:06.598  7831  7872 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	,at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.598  7831  7872 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:53:06.598  7831  7885 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	a,t com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.598  7831  7885 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.598  7831  7882 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: crash in the same process: AsyncTask #4
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.598  7831  7872 E AndroidRuntime_3_crash: 	... 3 more
,07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: crash in the same process: AsyncTask #2
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	,at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:64)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.CursorLoader.loadInBackground(CursorLoader.java:42)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.AsyncTaskLoader.onLoadInBackground(AsyncTaskLoade,r.java:312)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:69)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.content.AsyncTaskLoader$LoadTask.doInBackground(AsyncTaskLoader.java:57)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.598  7831  7856 E AndroidRuntime_2_crash: 	... 3 more
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.608  7831  7884 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:53:06.608  7831  7855 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	a,t com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: ,	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.608  7831  7855 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: crash in the same process: AsyncTask #9
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304),
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.608  7831  7885 E AndroidRuntime_4_crash: 	... 3 more
,07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: crash in the same process: AsyncTask #6
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.608  7831  7882 E AndroidRuntime_5_crash: 	... 3 more
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.618  7831  7886 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: crash in the same process: AsyncTask #8
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.608  7831  7884 E AndroidRuntime_6_crash: 	... 3 more
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: crash in the same process: AsyncTask #1
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.618  7831  7855 E AndroidRuntime_7_crash: 	... 3 more
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: crash in the same process: AsyncTask #10
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.email.provider.b.E(SourceFile:80)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.email.provider.b.F(SourceFile:114)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.email.provider.k.run(SourceFile:395)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:06.618  7831  7886 E AndroidRuntime_8_crash: 	... 3 more
,07-27 08:53:06.738  1114  2987 I ActivityManager: Recipient 6871
,07-27 08:53:06.798  1114  3777 E ActivityManager: App crashed! Process: com.google.android.gm,
07-27 08:53:06.818  1114  2987 I ActivityManager: Killing 6923:com.htc.WifiRouter/u0a134 (adj 15): empty #17
07-27 08:53:06.818  1114  2987 D Process : killProcessQuiet, pid=6923,
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: Can't write: system_app_crash
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system),
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	,at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 08:53:06.818  1114  7895 E DropBoxManagerService: 	... 5 more
07-27 08:53:06.818  1114  2987 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.appDiedLocked:4970 
,07-27 08:53:06.848  1114  3438 I ActivityManager: Recipient 6923,
07-27 08:53:06.848  1114  2947 D WifiService: Client connection lost with reason: 4
,07-27 08:53:07.038   502   502 E TPD     : [TPD][ERR] can't open /proc/6923/status...,
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:07.048  7831  7864 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: crash in the same process: AsyncTask #3
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: java.lang.RuntimeException: An error occured while executing doInBackground()
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
,07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at com.android.email.provider.EmailProvider.query(SourceFile:1300)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at com.android.email.provider.EmailProvider.J(SourceFile:6350)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at com.android.email.provider.r.run(SourceFile:6330)
07-27 08:53:07.048  7831  7,864 E AndroidRuntime_9_crash: 	at com.android.emailcommon.b.h.au(SourceFile:247)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at com.android.emailcommon.b.i.doInBackground(SourceFile:121)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:53:07.048  7831  7864 E AndroidRuntime_9_crash: 	... 3 more
,07-27 08:53:07.088  7831  7851 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/EmailProvider.db'.
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at com.android.email.provider.EmailProvider.call(SourceFile:2300)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:319)
07-27 08:53:07.088  7831  7851 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
07-27 08:53:07.088  4222  4222 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:53:07.088  7831  7851 E DatabaseUtils: Writing exception to parcel
07-27 08:53:07.088  7831  7851 E DatabaseUtils: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at com.android.email.provider.EmailProvider.G(SourceFile:488)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at com.android.email.provider.EmailProvider.call(SourceFile:2300)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:319)
07-27 08:53:07.088  7831  7851 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:454)
07-27 08:53:07.088  4222  4222 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:53:07.088  7858  7858 E AndroidRuntime: FATAL EXCEPTION: main
07-27 08:53:07.088  7858  7858 E AndroidRuntime: Process: com.google.android.gm.exchange, PID: 7858
07-27 08:53:07.088  7858  7858 E AndroidRuntime: java.lang.RuntimeException: Unable to create application com.android.exchange.Exchange: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4962)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.content.ContentProviderProxy.call(ContentProviderNative.java:699)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at com.android.exchange.Exchange.onCreate(Exchange.java:35)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-27 08:53:07.088  7858  7858 E AndroidRuntime: 	... 9 more
07-27 08:53:07.088  1114  3442 E ActivityManager: App crashed! Process: com.google.android.gm.exchange
,07-27 08:53:07.098  1114  7900 E DropBoxManagerService: Can't write: system_app_crash
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:456)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method),
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 08:53:07.098  1114  7900 E DropBoxManagerService: 	... 5 more
,07-27 08:53:07.108  7831  7831 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-27 08:53:07.108  1114  1165 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
07-27 08:53:07.108  1114  1165 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2acedf05 u0 Application Error: com.google.android.gm}
07-27 08:53:07.108  1114  1165 D StatusBarManagerService: hiding MENU key
,07-27 08:53:07.108  3103  3103 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-27 08:53:07.108  3103  3103 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-27 08:53:07.158  7831  7904 E Gmail   : Error finding the version of the Email provider.....
07-27 08:53:07.158  7831  7904 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-27 08:53:07.158  7831  7904 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-27 08:53:07.158  7831  7904 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
07-27 08:53:07.158  7831  7904 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
07-27 08:53:07.158  7831  7904 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:07.158  7831  7904 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:07.158  7831  7904 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.158  7831  7904 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:07.158  7831  7904 W EmailMigration: We do not support migrating this version of the Email provider.
,07-27 08:53:07.168  7831  7888 I Gmail   : getAccountsCursor
,07-27 08:53:07.178  4222  4222 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:53:07.178  7458  7458 D DFPI.PIReciver: onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,07-27 08:53:07.188  1114  1134 I ActivityManager: Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,07-27 08:53:07.188  7458  7906 I DFPI.ApkInstallService: onHandleIntent
,07-27 08:53:07.188  7458  7906 I DFPI.ApkInstallService: Media Scan Finished Case 
,07-27 08:53:07.198  7831  7905 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:07.198  7831  7905 E Gmail   : Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
07-27 08:53:07.198  7831  7905 E Gmail   : android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.198  7831  7905 E Gmail   : 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:07.198  7831  7887 I Gmail   : getAccountsCursor
,07-27 08:53:07.198  7831  7905 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.198  7831  7905 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:07.198  7831  7905 E Gmail   : Error handling intent Intent { act=com.android.mail.action.update_notification typ=application/gmail-ls flg=0x10 cmp=com.google.android.gm/.GmailIntentService (has extras) }
07-27 08:53:07.198  7831  7905 E Gmail   : android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-27 08:53:07.198  7831  7905 E Gmail   : 	,at com.google.android.gm.provider.MailEngine.W(SourceFile:999)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:98)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.198  7831  7905 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:53:07.208  1114  3761 I ActivityManager: Resuming delayed broadcast
07-27 08:53:07.208  4222  4222 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:53:07.208  1114  3761 I ActivityManager: Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874),
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at com.google.android.gm.provider.ax.run(SourceFile:1023)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.208  7831  7907 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: crash in the same process: MailEngine creation
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at com.google.android.gm.provider.MailEngine.<init>(SourceFile:1257)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at com.google.android.gm.provider.MailEngine.V(SourceFile:966)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at com.google.android.gm.provider.ax.run(SourceFile:1023)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.os.Looper.loop(Looper.java:155)
07-27 08:53:07.208  7831  7907 E AndroidRuntime_10_crash: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:53:07.208  7831  7907 W GAV2    : Thread[MailEngine creation,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-27 08:53:07.218  7831  7890 I Gmail   : get,AccountsCursor
07-27 08:53:07.218  4222  4222 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
,07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108,
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
,07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0,
07-27 08:53:07.258   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=8
07-27 08:53:07.258   499   499 E qdoverlay: src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
07-27 08:53:07.258   499   499 E qdoverlay: src_rect mdp_rect x=540 y=0 w=1080 h=1920
07-27 08:53:07.258   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
,07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x0 id=8
07-27 08:53:07.258   499   499 E qdoverlay: src msmfb_img w=2176 h=1920 format=15 MDP_RGBX_8888
07-27 08:53:07.258   499   499 E qdoverlay: src_rect mdp_rect x=540 y=75 w=1080 h=1701
07-27 08:53:07.258   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=75 w=1080 h=1701
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=8
07-27 08:53:07.258   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-27 08:53:07.258   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-27 08:53:07.258   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: Cant open device /dev/graphics/fb0 err=108
07-27 08:53:07.258   499   499 E qdoverlay: Ctrl failed to init fbnum=0
07-27 08:53:07.258   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8
,07-27 08:53:07.258   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-27 08:53:07.258   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-27 08:53:07.258   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-27 08:53:07.258   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
07-27 08:53:07.258   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-27 08:53:07.258   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-27 08:53:07.258   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-27 08:53:07.258   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   499 E qdoverlay: MdpCtrl close error in unset
07-27 08:53:07.258   499   832 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Cannot send after transport endpoint shutdown
07-27 08:53:07.258   499   832 E SurfaceFlinger: eventControl(0, 1) failed Cannot send after transport endpoint shutdown

```
