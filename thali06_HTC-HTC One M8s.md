#### Test 63377149f0d5e10_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
03-18 15:48:15.867   970  1565 I ActivityManager: Recipient 3020
,--------- beginning of main
03-18 15:48:15.917  3715  3715 E Personalize.BootComple_: onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
03-18 15:48:15.917  3715  3715 E Personalize.BootComple_: action android.intent.action.BOOT_COMPLETED
03-18 15:48:15.927  3715  3715 E Personalize.Utilities: SimpleLauncher not found: com.htc.simplelauncher
03-18 15:48:15.927   970   990 I PackageManager:  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3715, uid=1000, userID:0
03-18 15:48:15.927  3715  3715 E Personalize.BootComple_: initialize: false
03-18 15:48:15.927   970  1980 I PackageManager:  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3715, uid=1000, userID:0
03-18 15:48:15.927  3715  3715 E Personalize.Utilities: setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
03-18 15:48:15.937  2995  2995 V BootCompletedReceiver: ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
03-18 15:48:15.937  2995  2995 D PeopleYouKnow: receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) }
03-18 15:48:15.967   970   991 D Process : killProcessQuiet, pid=3357
03-18 15:48:15.967   970   991 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3742 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
03-18 15:48:15.967   970   991 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-18 15:48:15.967   970   991 I ActivityManager: Killing 3357:com.futuredial/u0a82 (adj 15): empty #17
03-18 15:48:16.047   970  2014 I ActivityManager: Recipient 3357
03-18 15:48:16.077   970  1975 D Process : killProcessQuiet, pid=3327
03-18 15:48:16.077   970  1975 I ActivityManager: Killing 3327:com.android.keychain/1000 (adj 15): empty #17
03-18 15:48:16.087   970  1975 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-18 15:48:16.127  3742  3742 V HtcDataRoamingWidget.DisableWidgetReceiver: ACTION_BOOT_COMPLETED
03-18 15:48:16.127   970  1565 I PackageManager:  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3742, uid=10040, userID:0
03-18 15:48:16.167   970  2015 I ActivityManager: Recipient 3327
03-18 15:48:16.197   970  1975 D Process : killProcessQuiet, pid=3433
03-18 15:48:16.197   970  1975 I ActivityManager: Killing 3433:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
03-18 15:48:16.197   970  1975 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-18 15:48:16.197  3755  3765 E cutils-trace: Error opening trace file: Permission denied (13)
03-18 15:48:16.207  3742  3742 V HtcDataStripWidget.DisableWidgetReceiver: ACTION_BOOT_COMPLETED
03-18 15:48:16.207   970  1327 I PackageManager:  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3742, uid=10040, userID:0
03-18 15:48:16.247   970   970 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
03-18 15:48:16.247   970  3779 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=40 rxSum=27} preTxRxSum={txSum=31 rxSum=20}
03-18 15:48:16.247   970  3779 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-18 15:48:16.247   970  3779 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
03-18 15:48:16.257  3755  3755 D CustomizationManager: ====startRecUseTime====
03-18 15:48:16.257  3755  3755 D htc.customization.log.level:  is 
03-18 15:48:16.257  3755  3755 W CustomizationLogLevel: Level value is invalid, use default level 2
03-18 15:48:16.317  3755  3755 D CustomizationManager:  Read ACC file spent 0.032 (s)
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__001
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__102
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__032
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__002
03-18 15:48:16.317  3755  3755 D CIDMapFileReader: Parsing tag item name = HTC__031
03-18 15:48:16.317  3755  3755 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-18 15:48:16.317  3755  3755 I CustomizationCIDLoader: Parsing tag category name = system
03-18 15:48:16.317  3755  3755 I CustomizationCIDLoader: Parsing tag category name = application
03-18 15:48:16.317  3755  3755 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-18 15:48:16.317  3755  3755 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-18 15:48:16.317  3755  3755 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: Parsing tag category name = Settings
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: Parsing tag category name = ACC
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 42507
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 21902
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23420
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 22299
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 24002
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23210
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23205
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23806
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23430
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23408
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 27205
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-18 15:48:16.327  3755  3755 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-18 15:48:16.327  3755  3755 D CustomizationManager:  Read CID file spent 0.070 (s)
03-18 15:48:16.327  3755  3755 D CustomizationManager:  All configurations done spent 0.070 (s)
03-18 15:48:16.357   970  2014 I ActivityManager: Recipient 3433
03-18 15:48:16.367  1486  1960 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-18 15:48:16.367  1486  1960 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@763de51 +
03-18 15:48:16.367  1486  1960 I Prism.WidgetManager: onLoadItems() +
03-18 15:48:16.397   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-18 15:48:16.397   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=45
03-18 15:48:16.397   970   970 E WifiTrafficPoller: notifying of data activity 1
03-18 15:48:16.397  1218  1218 D WIFI_ICON: WifiActivity: 1
03-18 15:48:16.397  1218  1218 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-18 15:48:16.407   970  1975 D Process : killProcessQuiet, pid=3497
03-18 15:48:16.407   970  1975 I ActivityManager: Killing 3497:com.htc.calendar/u0a10 (adj 15): empty #17
03-18 15:48:16.407   970  1975 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-18 15:48:16.417  1486  1960 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-18 15:48:16.487   970  1692 I ActivityManager: Recipient 3497
03-18 15:48:16.507  1296  1296 D DotMatrix: [EventReceiver] onReceive, version:1.3
03-18 15:48:16.537   970  1690 I ActivityManager: Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3782 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
03-18 15:48:16.537   970  1695 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 3755 on display 0
03-18 15:48:16.537   970  1062 D PMS     : acquireHCC(19edde78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 970 1000 null
03-18 15:48:16.547   970  1062 D PMS     : acquireHCC(ce07951): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 970 1000 null
03-18 15:48:16.547   970  1695 D PMS     : acquireWL(175e6a24): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
03-18 15:48:16.547  1486  1486 I FeedHostManager: [onPause]
03-18 15:48:16.547  1486  1486 I FeedProviderManager: onPause
03-18 15:48:16.547  1486  1486 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@37aba655
03-18 15:48:16.547  1486  2399 I SocialFeedProvider: +onPause
03-18 15:48:16.547  1486  2399 I SocialFeedProvider: -onPause
03-18 15:48:16.547   970  1045 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/4
03-18 15:48:16.567   970  1566 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-18 15:48:16.567   970  1692 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3801 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-18 15:48:16.597  1486  1960 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-18 15:48:16.657   970  1043 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-18 15:48:16.657   970  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-18 15:48:16.657   970  1043 D StatusBarManagerService: hiding MENU key
03-18 15:48:16.667   970  1690 I ActivityManager: Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3825 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
03-18 15:48:16.667  1486  1486 I TrimMemoryManager: [trimMemory] 20
03-18 15:48:16.697   970  1327 I ActivityManager: Killing 3235:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
03-18 15:48:16.697   970  1327 D Process : killProcessQuiet, pid=3235
03-18 15:48:16.697   970  1327 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-18 15:48:16.717  3825  3825 W ResourcesManager: Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,03-18 15:48:16.787  1486  1960 W asset   : Copying FileAsset 0x55bb795550 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,03-18 15:48:16.787   970  1690 I ActivityManager: Recipient 3235
,03-18 15:48:16.807  3801  3801 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,03-18 15:48:16.817  3825  3825 D MediaSessionHelper: Attempting to get helper with context android.app.ReceiverRestrictedContext@2c1a561d,
,03-18 15:48:16.817   970  1393 D MediaSessionService: Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music
,03-18 15:48:16.827  3825  3825 D MediaSessionHelper: addMediaButtonListener added PendingIntent{3ad0da63: android.os.BinderProxy@4e1b092}
,03-18 15:48:16.837   970  1327 D Process : killProcessQuiet, pid=3410
,03-18 15:48:16.837   970  1327 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3848 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-18 15:48:16.837   970  1327 I ActivityManager: Killing 3410:android.process.media/u0a17 (adj 15): empty #17
03-18 15:48:16.847   970  1327 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-18 15:48:16.857   451   451 I art     : Explicit concurrent mark sweep GC freed 8689(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 247us total 19.098ms,
,03-18 15:48:16.867  3801  3801 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 2702-2713)
,03-18 15:48:16.867  1486  1960 I Prism.WidgetManager: onLoadItems() -,
03-18 15:48:16.867  1486  1960 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@763de51 -
,03-18 15:48:16.867  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-18 15:48:16.877   451   451 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 242us total 16.757ms
,03-18 15:48:16.887  3801  3801 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {81d788c},
03-18 15:48:16.887  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-18 15:48:16.887  3801  3801 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,03-18 15:48:16.897   451   451 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 207us total 13.727ms,
,03-18 15:48:16.907  3801  3801 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,03-18 15:48:16.907  3801  3801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:48:16.917  3801  3801 E SysUtils: ApplicationContext is null in ApplicationStatus,
,03-18 15:48:16.937   970  2015 I ActivityManager: Recipient 3410,
03-18 15:48:16.937  1430  2098 D PhoneApp: EVENT_QUERY_MO_PACKAGES
03-18 15:48:16.937  1430  2098 D PhoneApp: -- N1 =0
,03-18 15:48:16.937  1430  2098 D PhoneApp: -- N2 =0
,03-18 15:48:16.937  1430  2098 D PhoneApp: -- N3 =0
,03-18 15:48:16.977  3801  3801 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,03-18 15:48:16.987  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-18 15:48:16.987  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-18 15:48:16.987  3801  3801 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-18 15:48:16.987  3801  3801 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-18 15:48:16.987  3801  3801 I Adreno-EGL: Build Date: 03/09/15 Mon
03-18 15:48:16.987  3801  3801 I Adreno-EGL: Local Branch: 
03-18 15:48:16.987  3801  3801 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-18 15:48:16.987  3801  3801 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
,03-18 15:48:16.987  3801  3801 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-18 15:48:17.017   970  1692 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
03-18 15:48:17.017   970  1692 D Process : killProcessQuiet, pid=3569
03-18 15:48:17.017   970  1692 I ActivityManager: Killing 3569:com.htc.fm/u0a20 (adj 15): empty #17
03-18 15:48:17.017   970  1692 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-18 15:48:17.037   970  2669 W System.err: java.lang.Throwable: stack dump,
03-18 15:48:17.037   970  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-18 15:48:17.037   970  2669 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-18 15:48:17.037   970  2669 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-18 15:48:17.037   970  2669 W System.err: ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-18 15:48:17.037   970  2669 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-18 15:48:17.037   970  1044 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e4f97a7:true,
03-18 15:48:17.037  3801  3903 D BluetoothAdapter: 616379099: getState(). Returning 12
,03-18 15:48:17.107   970  1980 I ActivityManager: Recipient 3569
,03-18 15:48:17.277  3877  3877 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,03-18 15:48:17.287  3877  3877 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,03-18 15:48:17.297  3877  3909 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,03-18 15:48:17.297  3877  3877 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,03-18 15:48:17.307  3877  3877 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,03-18 15:48:17.317  3877  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 
03-18 15:48:17.317   970  1142 V AlarmManager: sending alarm PendingIntent{32930af0: PendingIntentRecord{3b90f869 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1458312497317, Int=0
,03-18 15:48:17.337  1584  1584 D HtcAppUPService: CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED,
03-18 15:48:17.337  1584  3918 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
03-18 15:48:17.337  1584  1584 D HtcAppUPService: HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@167703b9
,03-18 15:48:17.357  3801  3801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-18 15:48:17.357  1584  3920 I WSP     : [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
03-18 15:48:17.357  1584  2589 D HtcAppUPService: HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
03-18 15:48:17.357  1584  3922 D AutoSetting: receiver - intent: android.intent.action.BOOT_COMPLETED
03-18 15:48:17.367   970  1327 I ActivityManager: Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3923 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
03-18 15:48:17.367  1584  1584 D AutoSetting: service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
03-18 15:48:17.367  1584  1584 D AutoSetting: service - onStartCommand() boot completed, remove cache
03-18 15:48:17.367  1584  2589 D HtcAppUPService: HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
03-18 15:48:17.367  1584  1584 D AutoSetting: service - onStartCommand() REMOVE current location bundle
03-18 15:48:17.367  1584  1803 D AutoSetting: service - handleMessage() removing cache
03-18 15:48:17.367  1584  1803 D AutoSetting: service - AddressCache: clean up all cache
03-18 15:48:17.367  1584  1803 D AutoSetting: service - handleMessage() setting current location null
03-18 15:48:17.367  1584  2589 D HtcAppUPService: HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
03-18 15:48:17.367  1218  2556 D WeatherUtility: Weather sync is On
03-18 15:48:17.367  1218  2556 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-18 15:48:17.377  3801  3801 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-18 15:48:17.387   970  1690 D Process : killProcessQuiet, pid=3047,
03-18 15:48:17.387   970  1690 I ActivityManager: Killing 3047:com.android.settings/1000 (adj 15): empty #17
03-18 15:48:17.387   970  1690 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:17.387  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.387  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.387  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.387  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.387  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.387  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.387  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.387  3801  3801 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
03-18 15:48:17.387  1584  3918 D FeatureList: feature
03-18 15:48:17.387  1584  3918 D FeatureList: type
,03-18 15:48:17.387  1584  3918 D FeatureList: description
03-18 15:48:17.397  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.397  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.397  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.397  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.397  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.397  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.397  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.397  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.397  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.397  1584  3918 W Bundle  : ,	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.397   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-18 15:48:17.397  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.397   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=54
03-18 15:48:17.397  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.397  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
,03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.397  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.407  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.407  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.407  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.407  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.407  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.407  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.407  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.417  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.417  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.417  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.417  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.417  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.417  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.417  1584  3918 W Bundle  : 	,at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.417  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.417  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.417  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.417  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.417  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.417  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.417  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.417  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.417  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.417  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.417  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.417  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.417  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.427  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.427  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.427  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.427  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.427  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.427  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.427  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.427  1584  3918 W Bundle  : 	,at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.437  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.437  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.437  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.437  1584  3918 W Bundle  : ,	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.437  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.437  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.437  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.437  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.447  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.447  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.447  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.447  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.447  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.447  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.447  1584  3918 W Bundle  : ,	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.447  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.447  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.457  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.457  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.457  1584  3918 W Bundle  : 	,at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.457  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,03-18 15:48:17.457  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.457  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61),
,03-18 15:48:17.457  1584  3918 W Bundle  : Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
03-18 15:48:17.457  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.457  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:48:17.457  1584  3918 W Bundle  : Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
03-18 15:48:17.457  1584  3918 W Bundle  : Attempt to cast generated internal exception:
03-18 15:48:17.457  1584  3918 W Bundle  : java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:17.457  1584  3918 W Bundle  : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:48:17.487   970  1393 I ActivityManager: Recipient 3047
,03-18 15:48:17.597  3801  3801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-18 15:48:17.597  3801  3801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:48:17.597  3310  3310 V BluetoothSapService: onUnbind
,03-18 15:48:17.617  1584  3918 D PluginProvider: Begin Apply Batch
,03-18 15:48:17.627  1584  3918 E PluginProvider: conflict when insert feature, ignored
,03-18 15:48:17.657  3923  3923 V BootReceiver: onReceive: android.intent.action.BOOT_COMPLETED
03-18 15:48:17.657  3923  3923 D BootReceiver: boot completed:
03-18 15:48:17.657  3801  3898 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-18 15:48:17.667  3923  3923 D BootReceiver: isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true
03-18 15:48:17.667  3923  3923 D BootReceiver: Valid
03-18 15:48:17.667  3923  3923 D BootReceiver: startService:
,03-18 15:48:17.687   970  1327 I ActivityManager: Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3949 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a,
,03-18 15:48:17.707   970  1692 I ActivityManager: Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3967 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a
,03-18 15:48:17.707   970  1692 D Process : killProcessQuiet, pid=3459
,03-18 15:48:17.707   970  1692 I ActivityManager: Killing 3459:com.htc.widget.hmsproc3/u0a34 (adj 15): empty #17
03-18 15:48:17.707   970  1692 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-18 15:48:17.717  3801  3801 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-18 15:48:17.777  3801  3801 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@286b4754, mServedView=org.apache.cordova.engine.SystemWebView{246126fd VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3becdff2
,03-18 15:48:17.787   970  1393 I InputMethodManagerService: Disable input method client, pid=1486
03-18 15:48:17.787   970  1393 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-18 15:48:17.787   970  1393 I InputMethodManagerService: Enable input method client, pid=3801
,03-18 15:48:17.787  1218  1218 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-18 15:48:17.817   970  1327 I ActivityManager: Recipient 3459,
,03-18 15:48:17.817   970  1692 D PMS     : releaseWL(175e6a24): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,03-18 15:48:17.827   970  1045 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s272ms
,03-18 15:48:17.837  1362  1362 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
03-18 15:48:17.837  1362  1362 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
03-18 15:48:17.837  1362  1362 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
03-18 15:48:17.837  1362  1362 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,03-18 15:48:17.867  3949  3949 D NGFService: onCreate +++
,03-18 15:48:17.867  3949  3949 D SettingUtils: getProcessNormalFlag: true
03-18 15:48:17.867  3949  3949 D NGFService: onCreate last time crash or 1st run=false
03-18 15:48:17.867  3949  3949 D SettingUtils: setProcessNormalFlag: false
03-18 15:48:17.867  3949  3949 D NGFService: getAudioStreamType: ScoOn =false
,03-18 15:48:17.867  3949  3949 D SoundEffects: init +++ 3
,03-18 15:48:17.877  3801  3801 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3801
,03-18 15:48:17.887  3967  4003 W LMW     : [4003][ActionDeviceStorageHandler] onActionBootComplete++,
,03-18 15:48:17.887  3967  4003 W LMW     : [4003][ActionDeviceStorageHandler] onActionBootComplete--,
,03-18 15:48:17.897   970  1161 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4006 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a
,03-18 15:48:17.917   970  1161 I ActivityManager: Killing 1982:com.htc.bgp/u0a11 (adj 15): empty #17
,03-18 15:48:17.917   970  1161 D Process : killProcessQuiet, pid=1982
03-18 15:48:17.917   970  1161 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:17.957  1584  3918 D PluginProvider: apply Batch success
,03-18 15:48:17.967   408  4023 E AudioCache: Heap size overflow! req size: 1058400, max size: 1048576
03-18 15:48:17.967   408  4023 W NuPlayerRenderer: AudioSink write short frame count 0 < 9824
,03-18 15:48:17.997  3801  3801 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-18 15:48:18.007   970  1980 I ActivityManager: Recipient 1982
,03-18 15:48:18.107   970   991 I ActivityManager: Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=4062 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a,
03-18 15:48:18.117   970  2014 I ActivityManager: Killing 3628:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
03-18 15:48:18.117   970  2014 D Process : killProcessQuiet, pid=3628
03-18 15:48:18.117   970  2014 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-18 15:48:18.137   970  1694 I ActivityManager: Recipient 3628
,03-18 15:48:18.157  1584  3918 I [PluginManager]RegisterService: Notify Carousel that a new TabPlugin has been installed!
,03-18 15:48:18.167  3949  3949 D NGFLanguageMgr: LanguageFromSystem: language:en  country:gb,
03-18 15:48:18.167  3949  3949 D NGFLanguageMgr: language package name = preload_package
,03-18 15:48:18.197  3388  3457 I HtcModeClient: handler message = 4011,
03-18 15:48:18.197  3388  3457 E HtcModeClient: Check connection and retry 1 times.
,03-18 15:48:18.317  3949  3949 I NMT     : NMT version: 1.6.1-B006 REL,
,03-18 15:48:18.317  3949  3949 D NGFService: Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
,03-18 15:48:18.327  3949  3949 D NGFService: applyCurrentSystemLanguage +++
03-18 15:48:18.327  3949  3949 D NGFService: grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
03-18 15:48:18.327  3949  3949 D NGFLanguageMgr: LanguageFromSystem: language:en  country:gb
03-18 15:48:18.327  3949  3949 D NGFService: Elvis language uses the language: 2
03-18 15:48:18.327  3949  3949 D NGFService: setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
03-18 15:48:18.327  3949  3949 D NGFService: setCurrentNGFLanguageMgr: set language = British English
03-18 15:48:18.327  3949  3949 D NGFService: bluetoothInitialize +++
,03-18 15:48:18.337   970  1694 W System.err: java.lang.Throwable: stack dump
03-18 15:48:18.337   970  1694 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-18 15:48:18.337   970  1694 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-18 15:48:18.337   970  1694 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-18 15:48:18.337   970  1694 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,03-18 15:48:18.337   970  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-18 15:48:18.337   970  1044 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a3dd876:true
,03-18 15:48:18.347  3949  3949 D BluetoothHeadset: BluetoothHeadset()
03-18 15:48:18.347   970  1980 D BluetoothManagerService: registerStateChangeCallback+
03-18 15:48:18.347   970  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-18 15:48:18.347   970  1044 D BluetoothManagerService: Registered receivers: 7
,03-18 15:48:18.347   970  1393 D BluetoothManagerService: registerStateChangeCallback+
03-18 15:48:18.347   970  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-18 15:48:18.347   970  1044 D BluetoothManagerService: Registered receivers: 8
,03-18 15:48:18.347  3949  3949 D NGFService: cloud_init +++
03-18 15:48:18.347  3949  3949 D NGFLanguageMgr: getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
03-18 15:48:18.347  3801  3994 D jxcore_app_log: JniHelper::setJavaVM(0xaae908f8), pthread_self() = -1407410408
,03-18 15:48:18.357  3801  3994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-18 15:48:18.357  3801  3994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-18 15:48:18.357  3801  3994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-18 15:48:18.357  3801  3994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-18 15:48:18.357  3801  3994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-18 15:48:18.357  3801  3994 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20992d84 added. We now have 1 listener(s)
03-18 15:48:18.357   970  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-18 15:48:18.367  3801  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
03-18 15:48:18.367  3801  3994 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-18 15:48:18.367  3801  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-18 15:48:18.367  3801  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
,03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-18 15:48:18.367  3801  3994 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a324633 added. We now have 1 listener(s)
03-18 15:48:18.367  3801  3994 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-18 15:48:18.377   970  1153 D WifiService: New client listening to asynchronous messages,
03-18 15:48:18.377   970   970 E WifiTrafficPoller: ADD_CLIENT: 6
,03-18 15:48:18.377  3801  3994 D BluetoothAdapter: 616379099: getState(). Returning 12
,03-18 15:48:18.387  3801  3994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-18 15:48:18.387  3801  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-18 15:48:18.387  3801  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-18 15:48:18.387  3801  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-18 15:48:18.387  3801  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-18 15:48:18.397  3949  3949 D NGFService: elvisInitalize +++
,03-18 15:48:18.397  3801  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-18 15:48:18.397   970  1565 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-18 15:48:18.397   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
03-18 15:48:18.397   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=56
03-18 15:48:18.397  3801  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,03-18 15:48:18.407  4062  4062 D MediaProvider: [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,03-18 15:48:18.407  4062  4062 D MediaProvider: [MP][DEBUG] Storage State: mounted
03-18 15:48:18.407  4062  4062 D MediaProvider: [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
03-18 15:48:18.407  4062  4062 D MediaProvider: [MP][DEBUG] Storage State: removed
03-18 15:48:18.407  4062  4062 D MediaProvider: [MP][DEBUG] Sorting: order:2, path:/storage/usb
03-18 15:48:18.407  4062  4062 D MediaProvider: [MP][DEBUG] Storage State: removed
,03-18 15:48:18.407  3949  3949 D NGFService: elvisInitalize lang = British English
03-18 15:48:18.407  3801  3994 D BluetoothAdapter: 616379099: getState(). Returning 12
03-18 15:48:18.407  3949  3949 D NGFService: elvisInitalize: Freq Type:16000
,03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-18 15:48:18.407  3801  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-18 15:48:18.407  3801  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-18 15:48:18.407  3801  3994 D io.jxcore.node.ConnectivityMonitor: start: OK
03-18 15:48:18.407  3949  3949 D NGFService: tts_init +++
03-18 15:48:18.407  3949  3949 D NGFLanguageMgr: getVocalizerFolderName: language = 2, folder name = vocalizer_eng
03-18 15:48:18.407  3801  3994 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-18 15:48:18.427  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-18 15:48:18.437  4062  4105 E SQLiteLog: (283) recovered 86 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal
,03-18 15:48:18.437   970  1152 E WifiStateMachine: handleMessage: E msg.what=131155
03-18 15:48:18.437  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-18 15:48:18.437   970  1152 E WifiStateMachine: processMsg: ConnectedState
,03-18 15:48:18.447   970  1152 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2457 sc=60 link=150 tx=9.8, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:2780] from screen [on:0 period:-1976382189] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
03-18 15:48:18.447   970  1152 E WifiStateMachine: processMsg: L2ConnectedState
,03-18 15:48:18.447   970  1152 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2457 sc=60 link=150 tx=9.8, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1976382186] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-18 15:48:18.447   970  1152 E WifiStateMachine:  get link layer stats 0
03-18 15:48:18.447   970  1152 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-18 15:48:18.447  1385  1385 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-18 15:48:18.457  4062  4062 D MediaScannerReceiver: onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,03-18 15:48:18.457  4062  4062 D MediaProviderUtils: [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
,03-18 15:48:18.457  4062  4062 D MediaProviderUtils: [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED
,03-18 15:48:18.457  1385  1385 I wpa_supplicant: environment dirty rate=0 [0][0][0]
03-18 15:48:18.467   970  1152 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
03-18 15:48:18.467   970  1152 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150
03-18 15:48:18.467   970  1152 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-56 "NG700"WPA_PSK
,03-18 15:48:18.467   970  1152 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.90 txretriesrate=0.00 rxrate=10.69 userTriggerdPenalty0
03-18 15:48:18.467   970  1152 E WifiStateMachine:  good link -> stuck count =0
03-18 15:48:18.467   970  1152 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
,03-18 15:48:18.467   970  1152 E WifiStateMachine:  isHighRSSI       ---> score=61
03-18 15:48:18.467  3801  3801 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-18 15:48:18.467  3949  3949 D NGFLanguageMgr: LanguageFromSystem: language:en  country:gb
03-18 15:48:18.467  3949  3949 D NGFLanguageMgr: language package name = preload_package
03-18 15:48:18.467   970  1170 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
,03-18 15:48:18.467  1218  1218 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-18 15:48:18.467   970  1152 E WifiStateMachine: handleMessage: X
03-18 15:48:18.467  1218  1218 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-18 15:48:18.477  3949  3949 D NGFService: load vocalizer language = British English
,03-18 15:48:18.487  3949  3949 E NGFService: registerObserver
,03-18 15:48:18.497  3949  3949 D NGFService: onCreate: Battery Level Remaining: 100%,
03-18 15:48:18.497  3949  3949 D NGFService: onStartCommand(): service start
03-18 15:48:18.497  3949  3949 D NGFService: onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
03-18 15:48:18.497  3949  3949 D NGFService: QuickCall
03-18 15:48:18.497  3949  3949 D BluetoothHeadset: Proxy object connected
,03-18 15:48:18.497  3949  3949 D NGFService: BluetoothHeadset onServiceConnected: main
,03-18 15:48:18.497  3949  3949 D BluetoothAdapter: 777134519: getState(). Returning 12
,03-18 15:48:18.507  3949  3949 W NGFService: Headset deviceList = 0
,03-18 15:48:18.507  3949  3949 D BluetoothA2dp: Proxy object connected
03-18 15:48:18.507  3949  3949 D NGFService: BluetoothA2dp onServiceConnected: main
03-18 15:48:18.507  3949  3949 D BluetoothAdapter: 777134519: getState(). Returning 12
03-18 15:48:18.507  3949  3949 W NGFService: A2dp deviceList = 0
,03-18 15:48:18.527  3949  3949 D NGFService: Elvis is initialization Success
03-18 15:48:18.527  3949  3949 D NGFService: bElvisInitializeCompleted = true
03-18 15:48:18.527  3949  3949 D NGFService: GrammarState = 0
03-18 15:48:18.527  3949  3949 D NGFService: loadGrammar +++
03-18 15:48:18.527  3949  3949 D NGFService: loadGrammar asr_grammar
,03-18 15:48:18.537  3949  4111 W NMT-OemFile: fopen(): Failed to open file sysdct.dat
,03-18 15:48:18.537  3949  4111 W NMT-OemFile: fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
03-18 15:48:18.537   970  1062 D PMS     : releaseHCC(19edde78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
03-18 15:48:18.537   970  1062 D PMS     : releaseHCC(ce07951): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-18 15:48:18.547  3949  4111 W NMT-OemFile: fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,03-18 15:48:18.547  3949  3949 I NGFService: GrammarDepot contains a valid Elvis Grammar0
03-18 15:48:18.547  3949  3949 D NGFService: loadGrammar from cache
03-18 15:48:18.547  3949  4111 W NMT-OemFile: fopen(): Failed to open file sysdct.dat
03-18 15:48:18.547  3949  4111 W NMT-OemFile: fopen(): Failed to open file sysdct.dat
,03-18 15:48:18.547  3949  4111 W NMT-OemFile: fopen(): Failed to open file clm.dat
,03-18 15:48:18.577  3949  4111 W NMT-OemFile: fopen(): Failed to open file daniel_userdct_eng.dat
,03-18 15:48:18.597  4062  4062 D MediaScannerServiceEx: Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
03-18 15:48:18.597  4062  4062 D MediaScannerServiceEx: Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
,03-18 15:48:18.597   970  1393 D PMS     : acquireWL(3f6d1e80): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4062 10017 null
03-18 15:48:18.597  4062  4062 D MtpReceiver: [MTP][handleUsbStateAsync]+
03-18 15:48:18.597  4062  4062 D MtpReceiver: [MTP][handleUsbStateAsync]1:1-
03-18 15:48:18.597  4062  4115 D MtpReceiver: [MTP][handleUsbState]+
,03-18 15:48:18.617   970  1694 I ActivityManager: Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=4116 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-18 15:48:18.617  4062  4115 D MediaProvider: bindService() MTP Service Connection.
,03-18 15:48:18.627  4062  4115 D MtpReceiver: [MTP][scanExternalVolumeIfNeed] scan external volume,
,03-18 15:48:18.627  4062  4062 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-18 15:48:18.627  4062  4115 D MtpReceiver: [MTP][handleUsbState]-
,03-18 15:48:18.627  4062  4115 D MtpReceiver: [MTP][handleMessage]-
,03-18 15:48:18.627  4062  4062 D MtpService: addStorageInternal without MtpServer
,03-18 15:48:18.637  4062  4062 D MtpService: [MTP][onCreate]-
,03-18 15:48:18.637  4062  4113 D MediaScanner: =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,03-18 15:48:18.637  4062  4062 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,03-18 15:48:18.657  4062  4062 D MtpService: [MTP] startForeground
03-18 15:48:18.667  1296  1319 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,03-18 15:48:18.667  4062  4062 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-18 15:48:18.677  4062  4113 E SQLiteLog: (283) recovered 47 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
,03-18 15:48:18.677   970  1327 I art     : Explicit concurrent mark sweep GC freed 21235(1157KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.955ms total 156.077ms
,03-18 15:48:18.687   970  2014 D PMS     : acquireWL(829ad62): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2201 10024 null
,03-18 15:48:18.687  4062  4062 D MtpDatabase: TotalSize=1886532,MediaCacheLimit=6000
,03-18 15:48:18.697  1218  1218 I RemoteViews: apply : com.android.providers.media 0 17 2 36
,03-18 15:48:18.697  4062  4062 D MtpService: starting MTP server in MTP mode
,03-18 15:48:18.707  4116  4116 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
03-18 15:48:18.707  3949  4114 W NMT     : Fail to open read-stream for file elvisBritish Englishartist.lst
,03-18 15:48:18.707  4116  4116 D MessageFrequencyProvider: onCreate
03-18 15:48:18.707  4062  4062 D MtpService: addStorageInternal 65537 /storage/emulated/0
,03-18 15:48:18.707  1218  1218 I RemoteViews: apply : com.android.providers.media 0 14 1 51
,03-18 15:48:18.717  4116  4116 V GetPrviateResource: GetPrviateResource
,03-18 15:48:18.717  4116  4116 V GetPrviateResource: GetPrviateResource
,03-18 15:48:18.717  4062  4143 D MtpService: [checkStorageState] Storage state - mounted
03-18 15:48:18.717  4062  4143 D MtpDatabase: [MTP][addStorage] iHostType =2
,03-18 15:48:18.717  4062  4143 D MtpService: [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
,03-18 15:48:18.727  4116  4116 D MessageCustFlag: sense_version=6.0,
,03-18 15:48:18.727  4116  4116 D BTAccessoryUtil: createReceiver
,03-18 15:48:18.727  4116  4116 D BTAccessoryUtil: registerReceiver return intent = null
03-18 15:48:18.727  3949  4142 W NMT     : Fail to open read-stream for file elvisBritish Englishalbum.lst
03-18 15:48:18.727  4116  4116 D MessageCustFlag: sku_id=118
,03-18 15:48:18.737  4116  4116 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
,03-18 15:48:18.737  4116  4116 W SystemReader: Cannot find qct_8960_interface, use default value instead
03-18 15:48:18.737  4116  4116 V MmsSystemEventReceiver: Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
,03-18 15:48:18.747   970  1690 D PMS     : releaseWL(22b296d9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,03-18 15:48:18.757  4116  4116 D ExchangePolicystatus: onReceive(),
03-18 15:48:18.757  4116  4116 D ExchangePolicystatus: onReceive(): ACTION_BOOT_COMPLETED
,03-18 15:48:18.757  4116  4116 D MessageUtils: Text messaging allow status = allow
,03-18 15:48:18.757  4116  4116 D Messaging: EAS allow SMS !!!
03-18 15:48:18.757  3949  4148 W NMT     : Fail to open read-stream for file elvisBritish Englishplaylist.lst
,03-18 15:48:18.757  4116  4116 D ExchangePolicystatus: onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
03-18 15:48:18.757  4116  4116 D Messaging: EAS allow SMS !!!
03-18 15:48:18.757  3949  4152 W NMT     : Fail to open read-stream for file generic.lst
03-18 15:48:18.767   970  1142 V AlarmManager: sending alarm PendingIntent{25fe8be5: PendingIntentRecord{141f86ba com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=44609, Int=0
03-18 15:48:18.757  3949  4152 W NMT     : Fail to open read-stream for file elvisBritish Englishgeneric.lst
03-18 15:48:18.767   970  2669 D PMS     : acquireWL(1a55396b): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 4116 10064 null
,03-18 15:48:18.777  3949  4153 W NMT     : Fail to open read-stream for file elvisBritish Englishname.lst
,03-18 15:48:18.777  3949  4155 W NMT     : Fail to open read-stream for file elvisBritish Englishsong.lst,
03-18 15:48:18.777   970  1695 I ActivityManager: Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=4156 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-18 15:48:18.777  2201  4137 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,03-18 15:48:18.787  4116  4116 V SmsReceiverService: onStart: #1, @616379099
,03-18 15:48:18.787  4116  4170 V SmsReceiverService: action: android.intent.action.BOOT_COMPLETED
03-18 15:48:18.787  4116  4170 D SmsReceiverService: isCbm: false
,03-18 15:48:18.787  4116  4170 D SmsReceiverService: isDiscard: false
,03-18 15:48:18.797  4116  4170 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2ecb9bf
,03-18 15:48:18.807  4062  4113 W MediaScanner: Error opening directory '/oem/media/', skipping: No such file or directory.,
,03-18 15:48:18.807  3949  3949 D SettingUtils: setProcessNormalFlag: true
03-18 15:48:18.807  3949  3949 D NGFService: RebuildListener constraintList size 17
03-18 15:48:18.807  3949  3949 D NGFService: RebuildListener: onComplete0
03-18 15:48:18.807  3949  3949 D NGFService: onComplete GRAMMAR_STATE_DEFAULT
03-18 15:48:18.807  3949  3949 D NGFService: switchScenario: htc_screen_140_19
,03-18 15:48:18.807  3949  3949 D NGFService: Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
03-18 15:48:18.807  3949  3949 D NGFService: Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
03-18 15:48:18.807  3949  3949 D NGFService: Loading grammar completed.
03-18 15:48:18.807  3949  3949 D NGFService: update contact cache completed
03-18 15:48:18.807  3949  3949 D SettingUtils: set Updatge Contact Cache: false
03-18 15:48:18.817  4062  4113 W MediaScanner: Error opening directory '/oem/media/', skipping: No such file or directory.
03-18 15:48:18.817  4062  4113 D MediaScanner:  prescan time: 148ms
03-18 15:48:18.817  4062  4113 D MediaScanner:     scan time: 30ms
03-18 15:48:18.817  4062  4113 D MediaScanner: postscan time: 0ms
03-18 15:48:18.817  4062  4113 D MediaScanner:    total time: 178ms
03-18 15:48:18.817  4062  4113 D MediaScanner: -----------------------------------------------------------------
03-18 15:48:18.817  4062  4113 D MediaScanner: firstscan(media) time: 17ms
03-18 15:48:18.817  4062  4113 D MediaScanner: secondscan(non-media) time: 7ms
03-18 15:48:18.817  4062  4113 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:18.817  4062  4113 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:18.817  4062  4113 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:18.817  4062  4113 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 339
03-18 15:48:18.817  4062  4062 E MediaScannerService: [onStartCommand] --- Should not be here, redirect request. ----
03-18 15:48:18.817  4062  4147 E MediaScannerService: [handleMessage] --- Should not be here, ignore request. ----
03-18 15:48:18.817  4116  4170 V SmsReceiverService: handleBootCompleted
,03-18 15:48:18.827  4116  4170 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-18 15:48:18.857  1430  2020 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
,03-18 15:48:18.857  1430  2020 D AccFlag : sku_id=118
,03-18 15:48:18.867  4116  4170 D SmsReceiverService: OutBoxSize = 0
03-18 15:48:18.867  4116  4170 D SmsReceiverService: sendFirstQueuedMessage start: 0
,03-18 15:48:18.867  4116  4170 D MessageCustFlag: sku_id=118
03-18 15:48:18.867  2201  4137 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 87 ms
,03-18 15:48:18.867   970  1565 D PMS     : releaseWL(829ad62): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,03-18 15:48:18.877  1430  2410 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92,
,03-18 15:48:18.877  1430  2410 D AccFlag : sku_id=118
,03-18 15:48:18.887  4116  4170 D MessageCustFlag: sku_id=118
,03-18 15:48:18.887  4116  4170 D SmsReceiverService: sendFirstQueuedMessage end cnt> 0
,03-18 15:48:18.897  4062  4113 D MediaProvider: [delete][75]
,03-18 15:48:18.897  4062  4113 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289),
,03-18 15:48:18.897  4116  4180 D SpaceBufferUtil: > createBufferFile()
,03-18 15:48:18.897  4116  4180 D SpaceBufferUtil: bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
03-18 15:48:18.897  4116  4180 D SpaceBufferUtil: < createBufferFile()
,03-18 15:48:18.907  4062  4113 D MediaProvider: [recoverParentNodes] - 0
,03-18 15:48:18.907  4062  4113 D MediaProvider: [update][16]
03-18 15:48:18.907  4062  4113 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
,03-18 15:48:18.917   970   990 D PMS     : releaseWL(3f6d1e80): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,03-18 15:48:18.917  4062  4113 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
,03-18 15:48:18.917  4062  4113 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
,03-18 15:48:18.917  4062  4113 D MediaScannerServiceEx: [handleExternalVolume] ext storage
,03-18 15:48:18.927  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-18 15:48:18.927  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-18 15:48:18.927  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/usb
03-18 15:48:18.927  4062  4113 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
03-18 15:48:18.927  4062  4113 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
,03-18 15:48:18.937  4062  4113 D MediaProvider: [update][7]#0#
,03-18 15:48:18.937  4062  4113 D MediaProvider: [update][5]#0#
,03-18 15:48:18.947  4062  4113 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,03-18 15:48:18.947  4062  4113 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
,03-18 15:48:18.947  4062  4113 D MediaProvider: [update][8]#1#
03-18 15:48:18.957  4062  4113 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
03-18 15:48:18.957   970  2669 D PMS     : acquireWL(11110161): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4062 10017 null
,03-18 15:48:18.967  4062  4113 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,03-18 15:48:18.987  4181  4181 E cutils-trace: Error opening trace file: Permission denied (13)
,03-18 15:48:18.987  4181  4181 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-18 15:48:18.987  4181  4181 I dex2oat : dex2oat: override thread count:4
,03-18 15:48:19.077   970  2669 D Process : killProcessQuiet, pid=3604
03-18 15:48:19.077   970  2669 I ActivityManager: Killing 3604:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
03-18 15:48:19.077   970  2669 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:19.127   970  2015 I ActivityManager: Recipient 3604
,03-18 15:48:19.237  3801  4107 W jxcore-log: Initializing JXcore engine
,03-18 15:48:19.237  3801  4107 W jxcore-log: JXcore engine is ready
,03-18 15:48:19.307  3801  4107 W jxcore-log: Starting JXcore engine,
,03-18 15:48:19.397   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
,03-18 15:48:19.397   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=56
03-18 15:48:19.397   970   970 E WifiTrafficPoller: notifying of data activity 0
,03-18 15:48:19.407  1218  1218 D WIFI_ICON: WifiActivity: 0
03-18 15:48:19.407  1218  1218 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,03-18 15:48:19.427  3801  4107 W jxcore-log: Platform android
03-18 15:48:19.427  3801  4107 W jxcore-log: 
,03-18 15:48:19.427  3801  4107 W jxcore-log: Process ARCH arm
03-18 15:48:19.427  3801  4107 W jxcore-log: 
,03-18 15:48:19.627  3801  4107 I jxcore-log: JXcore Cordova bridge is ready!
03-18 15:48:19.627  3801  4107 I jxcore-log: 
03-18 15:48:19.627  3801  4107 W jxcore-log: JXcore engine is started
,03-18 15:48:19.637  3801  3994 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-18 15:48:19.637  3801  3801 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-18 15:48:19.657  3801  4107 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-18 15:48:19.657  3801  4107 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-18 15:48:19.667  3801  3801 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-18 15:48:19.667  3801  3801 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-18 15:48:19.707  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-18 15:48:19.707   970  1565 D PMS     : acquireWL(24af5486): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 970 1000 null
03-18 15:48:19.707  3801  3994 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 38ms. Plugin should use CordovaInterface.getThreadPool().
03-18 15:48:19.707  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-18 15:48:19.707   970  1566 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,03-18 15:48:19.737  1486  1486 I FeedHostManager: [onResume]
,03-18 15:48:19.737  1486  1486 I FeedProviderManager: onResume
03-18 15:48:19.737  1486  2399 I SocialFeedProvider: +onResume
03-18 15:48:19.737  1486  2399 I SocialFeedProvider: updateAccounts - Accounts is no change
03-18 15:48:19.737  1486  2399 I SocialFeedProvider: -onResume
,03-18 15:48:19.737   970  1043 D StatusBarManagerService: setSystemUiVisibility(0x8700)
,03-18 15:48:19.737   970  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-18 15:48:19.737   970  1043 D StatusBarManagerService: hiding MENU key
,03-18 15:48:19.747  1486  1486 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-18 15:48:19.747  1486  1486 I ThreadedRenderer: Defer allocateBuffers to drawing time
,03-18 15:48:19.747   970  1565 I InputMethodManagerService: Disable input method client, pid=3801,
03-18 15:48:19.747  3801  3801 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection,
03-18 15:48:19.747   970  1565 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-18 15:48:19.747   970  1565 I InputMethodManagerService: Enable input method client, pid=1486
03-18 15:48:19.757  1218  1218 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-18 15:48:19.777   970   990 D PMS     : releaseWL(24af5486): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,03-18 15:48:19.797   970  1043 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
03-18 15:48:19.797   970  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-18 15:48:19.797   970  1043 D StatusBarManagerService: hiding MENU key
,03-18 15:48:19.807   970  1029 D Process : killProcessQuiet, pid=3665
03-18 15:48:19.807   970  1029 I ActivityManager: Killing 3665:com.htc.video/u0a29 (adj 15): empty #17
03-18 15:48:19.807   970  1029 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,03-18 15:48:19.837  4181  4181 I dex2oat : dex2oat took 855.900ms (threads: 4),
,03-18 15:48:20.007   970  1565 I ActivityManager: Recipient 3665
,03-18 15:48:20.017  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,03-18 15:48:20.027  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
03-18 15:48:20.027  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
03-18 15:48:20.027  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-18 15:48:20.027  3801  3801 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-18 15:48:20.027  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-18 15:48:20.027  3801  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-18 15:48:20.027  3801  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
03-18 15:48:20.027  3801  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20992d84 removed from the list
03-18 15:48:20.027  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-18 15:48:20.027  3801  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a324633 removed from the list
03-18 15:48:20.027  3801  3801 D io.jxcore.node.ConnectivityMonitor: stop
03-18 15:48:20.027  3801  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
03-18 15:48:20.027  3801  3801 I io.jxcore.node.LifeCycleMonitor: stop: OK
,03-18 15:48:20.037  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,03-18 15:48:20.037  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,03-18 15:48:20.037  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): VersionName:             1.2.853019
03-18 15:48:20.037  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): VersionCode:             148001224
,03-18 15:48:20.037  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,03-18 15:48:20.037  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
03-18 15:48:20.047  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,03-18 15:48:20.047  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): Htc_DEBUG_flag:          false
03-18 15:48:20.047  4156  4156 I PushClient: ApplicationMonitor {3a6f9178}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,03-18 15:48:20.047  3388  3457 I HtcModeClient: handler message = 4009
03-18 15:48:20.047  3388  3457 I HtcModeClient: start to setup the connection
,03-18 15:48:20.077   970  1393 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4193 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,03-18 15:48:20.087  4188  4208 E cutils-trace: Error opening trace file: Permission denied (13)
,03-18 15:48:20.087  4156  4191 I PushClient: String {2b182068}: handleBroadcast(): Schedule update on boot completed.
,03-18 15:48:20.107   970  1695 I ActivityManager: Killing 2974:com.google.android.partnersetup/u0a27 (adj 15): empty #17
03-18 15:48:20.107   970  1695 D Process : killProcessQuiet, pid=2974
,03-18 15:48:20.107   970  1695 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:20.157   970  1692 I ActivityManager: Recipient 2974,
,03-18 15:48:20.167  4193  4193 D SMSBackup: Got ACTION_BOOT_COMPLETED event
,03-18 15:48:20.167  4193  4193 D SMSBackup: setCheckAlarm
,03-18 15:48:20.167  4193  4193 D SMSBackup: Next check is scheduled at 60s from now
,03-18 15:48:20.167   970  2669 D Process : killProcessQuiet, pid=3692
03-18 15:48:20.167   970  2669 I ActivityManager: Killing 3692:com.htc.csrecommend/u0a31 (adj 15): empty #17
03-18 15:48:20.167   970  2669 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-18 15:48:20.177  4188  4188 D CustomizationManager: ====startRecUseTime====,
03-18 15:48:20.177  4188  4188 D htc.customization.log.level:  is 
03-18 15:48:20.177  4188  4188 W CustomizationLogLevel: Level value is invalid, use default level 2
,03-18 15:48:20.237  4188  4188 D CustomizationManager:  Read ACC file spent 0.034 (s),
,03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__001
03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__102
03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__032
03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__002
03-18 15:48:20.237  4188  4188 D CIDMapFileReader: Parsing tag item name = HTC__031
,03-18 15:48:20.247  4188  4188 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml,
,03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = system
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = application
,03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = AudioService
,03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = Settings
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: Parsing tag category name = ACC
,03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 42507,
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 21902
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23420
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 22299
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 24002,
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23210
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23205
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23806
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23430
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23408
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 27205
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
,03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
,03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-18 15:48:20.247  4188  4188 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
,03-18 15:48:20.247  4188  4188 D CustomizationManager:  Read CID file spent 0.073 (s)
,03-18 15:48:20.247  4188  4188 D CustomizationManager:  All configurations done spent 0.073 (s)
,03-18 15:48:20.257   970  2014 I ActivityManager: Recipient 3692
,03-18 15:48:20.287   970  1980 I PackageManager:  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1430, uid=1001, userID:0
,03-18 15:48:20.287  1486  1972 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-18 15:48:20.287   970  1565 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=4188, uid=2000 userid=0
,03-18 15:48:20.297   970   991 I ActivityManager: Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=4231 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-18 15:48:20.297   970  1029 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
03-18 15:48:20.297   970  1029 D Process : killProcessQuiet, pid=3801
03-18 15:48:20.297   970  1029 I ActivityManager: Killing 3801:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
03-18 15:48:20.307   970  1029 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,03-18 15:48:20.347   970  1067 W PackageSettings: Skipping PackageSetting{32f344c1 com.example.hello/10374} due to missing metadata
,03-18 15:48:20.407   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6,
03-18 15:48:20.407   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=56,
,03-18 15:48:20.437   970  2669 I ActivityManager: Recipient 3801
,03-18 15:48:20.437  1362  1362 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{31cf71c6 uid 10195 pid 3801} (c)'
03-18 15:48:20.437   970  1153 D WifiService: Client connection lost with reason: 4
,03-18 15:48:20.517   970  1067 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed,
,03-18 15:48:20.527   970  2669 W ActivityManager: Spurious death for ProcessRecord{3c0c04d1 3801:com.test.thalitest/u0a195}, curProc for 3801: null,
,03-18 15:48:20.537  1296  1296 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
03-18 15:48:20.537  1296  1296 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
03-18 15:48:20.537  1296  1296 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,03-18 15:48:20.547   970  1144 W SystemReader: Cannot find grip_rejection_width, use default value instead
,03-18 15:48:20.567   970  1150 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
03-18 15:48:20.567   970  1149 D PMS     : acquireWL(1abe3e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 970 1000 null
03-18 15:48:20.577   970  2015 D PMS     : acquireWL(2a497d09): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1806 10024 WorkSource{10024 com.google.android.gms}
,03-18 15:48:20.577  1806  2238 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-18 15:48:20.577  1696  2091 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
03-18 15:48:20.577   970  2669 D PMS     : releaseWL(2a497d09): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
03-18 15:48:20.597  2995  3040 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
03-18 15:48:20.597  1696  2091 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-18 15:48:20.617  2995  3040 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,03-18 15:48:20.627   970  1028 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,03-18 15:48:20.637  4231  4231 I [AppShowMeDebug]BootCompletedReceiver: received boot complete
,03-18 15:48:20.647   970  1149 D PMS     : releaseWL(1abe3e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
03-18 15:48:20.647   970  1150 V NetworkPolicy: writePolicyLocked()
03-18 15:48:20.647  1486  1486 I art     : Explicit concurrent mark sweep GC freed 38451(2MB) AllocSpace objects, 13(588KB) LOS objects, 34% free, 30MB/46MB, paused 1.304ms total 135.853ms
03-18 15:48:20.657   970  1327 I ActivityManager: Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=4254 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
03-18 15:48:20.657  1486  1960 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,03-18 15:48:20.657  1486  1960 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,03-18 15:48:20.667  1696  2091 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-18 15:48:20.677   970  1150 V NetworkPolicy: updateNetworkEnabledLocked()
03-18 15:48:20.677   970  1150 V NetworkPolicy: updateNotificationsLocked()
03-18 15:48:20.677  4231  4252 I [AppShowMeDebug]BootCompletedReceiver: push flag is false, skip check
,03-18 15:48:20.687  1430  1430 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,03-18 15:48:20.687  2995  3040 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-18 15:48:20.697  1696  2091 E ExternalAccountType: Unsupported attribute readOnly
,03-18 15:48:20.707  2995  3040 E ExternalAccountType: Unsupported attribute readOnly
03-18 15:48:20.727   970   970 W PackageManager: Unable to load service info ResolveInfo{1eb94258 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
03-18 15:48:20.727   970   970 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-18 15:48:20.727   970   970 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-18 15:48:20.727   970   970 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-18 15:48:20.727   970   970 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-18 15:48:20.727   970   970 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-18 15:48:20.727   970   970 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-18 15:48:20.727   970   970 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-18 15:48:20.727   970   970 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-18 15:48:20.727   970   970 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-18 15:48:20.737   970  1028 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-18 15:48:20.737  4116  4116 D Messaging: supportCMAS(SIE)/init? false/true
03-18 15:48:20.737  4116  4116 D MmsConfig: networkCode: 
03-18 15:48:20.737  4116  4116 D MmsConfig: SIE smsPri: null
03-18 15:48:20.737  4116  4116 D MmsConfig: networkCode: 
,03-18 15:48:20.747  4116  4116 D MmsConfig: packageName: com.htc.vvm.att does not exist
,03-18 15:48:20.747  4116  4276 D Messaging: mNeedToUpdateDate2 start
,03-18 15:48:20.747  4116  4116 D ReportIndicatorCache: startAsyncQueryReports ---
03-18 15:48:20.747  1430  1477 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,03-18 15:48:20.747  1430  1477 D MmsSmsV2Provider:  slotId = -1000
03-18 15:48:20.747  1430  1477 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
03-18 15:48:20.757  4116  4139 D MmsAsyncWorkHandler: ,
03-18 15:48:20.757  4116  4139 D MmsAsyncWorkHandler: HM tk = 20001
03-18 15:48:20.757  4116  4139 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
03-18 15:48:20.757  4254  4254 D MyReportAgent: PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
,03-18 15:48:20.757  4116  4278 I Messaging: mccmnc> 
,03-18 15:48:20.757  1430  2410 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
03-18 15:48:20.757  1430  2410 D MmsSmsV2Provider:  slotId = -1000
03-18 15:48:20.757  1430  2410 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null,
,03-18 15:48:20.777  4116  4116 D DraftCache: [DraftCache/1] DraftCache.constructor
03-18 15:48:20.777  4254  4280 D MyReportAgent: DatabaseHelper [DatabaseHelper constructor]
,03-18 15:48:20.777  4254  4280 D MyReportAgent: PolicyStore [Init] Get cached policy bundle
03-18 15:48:20.777  4116  4116 D DraftCache: [DraftCache/1] refresh
,03-18 15:48:20.777  4116  4116 D MmsConfig: networkCode: ,
,03-18 15:48:20.787  4116  4282 D Messaging: ViewCache CreatePreloadOnlyConversationList
,03-18 15:48:20.797   970  1692 I ActivityManager: Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4283 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
,03-18 15:48:20.807  4254  4280 D MyReportAgent: ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
,03-18 15:48:20.807  1430  2020 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
03-18 15:48:20.807  1430  2020 D AccFlag : sku_id=118
03-18 15:48:20.817   450   450 I art     : Explicit concurrent mark sweep GC freed 8658(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 213us total 21.761ms
,03-18 15:48:20.817  4116  4139 D DraftCache: [DraftCache/111] rebuildCache
03-18 15:48:20.817  1430  2410 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
03-18 15:48:20.817  1430  2410 D MmsSmsV2Provider:  slotId = -1000
03-18 15:48:20.817  1430  2410 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
03-18 15:48:20.827  4116  4116 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
03-18 15:48:20.827  4116  4116 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
03-18 15:48:20.827  4116  4116 D PhoneStorageUtil: createReceiver
03-18 15:48:20.827  4254  4280 D MyReportAgent: ReportServiceHandler on boot complete event 
,03-18 15:48:20.827  4116  4282 D MessageCustFlag: sense_version=6.0
03-18 15:48:20.837  1430  1485 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-18 15:48:20.837   970  1067 I art     : Explicit concurrent mark sweep GC freed 28293(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 18MB/27MB, paused 3.180ms total 290.749ms
03-18 15:48:20.837  1430  1485 D MmsSmsV2Provider:  slotId = -1000
,03-18 15:48:20.837  1430  1485 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
03-18 15:48:20.837   450   450 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 173us total 17.472ms
,03-18 15:48:20.837  4116  4277 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,03-18 15:48:20.847  4116  4276 D Messaging: mNeedToUpdateDate2: false
,03-18 15:48:20.847   970  1694 I PackageManager:  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=4254, uid=10083, userID:0
03-18 15:48:20.847  4254  4280 V MyReportAgent: ReportServiceHandler unregister the PowerConnected Listener
03-18 15:48:20.847  1430  1477 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
03-18 15:48:20.847  1430  1477 D Jerry   : URI_DRAFT
,03-18 15:48:20.847  4116  4282 D Jerry   : start to preload cursor >>>>>>>
03-18 15:48:20.847   970  1161 D Process : killProcessQuiet, pid=3715
03-18 15:48:20.847   970  1161 I ActivityManager: Killing 3715:com.htc.home.personalize/1000 (adj 15): empty #17
,03-18 15:48:20.847   970  1161 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:20.857   970   970 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-18 15:48:20.857   450   450 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 195us total 24.431ms,
,03-18 15:48:20.937  4062  4113 D MediaScanner:  prescan time: 884ms,
03-18 15:48:20.937  4062  4113 D MediaScanner:     scan time: 1078ms
03-18 15:48:20.937  4062  4113 D MediaScanner: postscan time: 2ms
03-18 15:48:20.937  4062  4113 D MediaScanner:    total time: 1964ms
03-18 15:48:20.937  4062  4113 D MediaScanner: -----------------------------------------------------------------,
03-18 15:48:20.937  4062  4113 D MediaScanner: firstscan(media) time: 542ms
03-18 15:48:20.937   970  1694 I ActivityManager: Recipient 3715
03-18 15:48:20.937  4062  4113 D MediaScanner: secondscan(non-media) time: 536ms
03-18 15:48:20.937  4062  4113 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:20.937  4062  4113 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:20.937  4062  4113 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:20.937  4062  4113 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
,03-18 15:48:20.947  4062  4113 D MediaProvider: [delete][10],
03-18 15:48:20.947  4062  4113 D MediaProvider: [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,03-18 15:48:20.947  4062  4113 D MediaProvider: [recoverParentNodes] - 0,
03-18 15:48:20.947  4062  4113 D MediaProvider: [update][5]
03-18 15:48:20.947  4062  4113 D MediaScannerServiceEx: [scan] Recover Parent Node is finished!
03-18 15:48:20.947  4062  4113 D MediaScannerServiceEx: [updateImage]+
,03-18 15:48:20.957  1430  1485 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-18 15:48:20.957  1430  1485 V MmsProvider: Update uri=content://mms, match=0
03-18 15:48:20.957  1430  1485 V MmsProvider: selection=st=129 AND m_type!=134
,03-18 15:48:20.957  4116  4139 D DraftCache: hasDraft() = false mNeedNotifyChange = true
03-18 15:48:20.957  4116  4139 D DraftCache: [DraftCache/111] rebuildCache time: 6
03-18 15:48:20.957  1430  2020 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
03-18 15:48:20.957  4116  4139 D MmsAsyncWorkHandler: 
03-18 15:48:20.957  4116  4139 D MmsAsyncWorkHandler: HM tk = 20002
03-18 15:48:20.957  1430  2020 D MmsSmsV2Provider:  slotId = -1000
03-18 15:48:20.967  4116  4306 D Messaging: Reset downloading state: 0
03-18 15:48:20.967  4116  4306 V MmsSystemEventReceiver: TransactionService is going to be woken up.
03-18 15:48:20.967  1430  1477 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
03-18 15:48:20.967  1430  1477 D AccFlag : sku_id=118
03-18 15:48:20.967  4062  4113 D MediaScannerServiceEx: [updateImage]-0
,03-18 15:48:20.967  4283  4283 D UpdaterAPK | UpdaterBootCompleteReceiver: onReceive() - start htcCheckinService
03-18 15:48:20.967  4062  4113 D MediaScannerServiceEx: [2] scan finished
03-18 15:48:20.967   970  1692 D PMS     : releaseWL(11110161): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
03-18 15:48:20.967  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-18 15:48:20.977  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-18 15:48:20.977  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/usb
03-18 15:48:20.977  4062  4113 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
03-18 15:48:20.977  4062  4113 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/ext_sd
03-18 15:48:20.977  4116  4282 D Messaging: ViewCache CreatePreload
03-18 15:48:20.977  4116  4282 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
03-18 15:48:20.977  4116  4116 V TransactionService: 1-Creating TransactionService
03-18 15:48:20.977  4062  4113 D MediaScannerServiceEx: [disAliveExtStorageRows]+131073
03-18 15:48:20.977  1430  1485 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
03-18 15:48:20.977  1430  1485 D AccFlag : sku_id=118
,03-18 15:48:20.987  4116  4282 D Cust_MMSMS: _has_set_default_values_2=true
,03-18 15:48:20.987  4116  4116 V TransactionService: onStartCommand: 1
03-18 15:48:20.987  4116  4116 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,03-18 15:48:20.987  4116  4282 D MsgPreferenceUtils: def_index: 0
,03-18 15:48:20.987  4116  4310 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
03-18 15:48:20.987  4116  4310 V TransactionService: Loading previous transactions.
03-18 15:48:20.987  4116  4282 D MsgPreferenceUtils: globalIndex = 1
,03-18 15:48:20.997  4062  4113 D MediaProvider: [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,03-18 15:48:20.997   970   970 I htcCheckinService: htcCheckinProvider V2.1,
03-18 15:48:20.997   970   970 D htcCheckinService: htcCheckinService() the mIsServiceRunning = true
03-18 15:48:20.997  4062  4113 D MediaProvider: [update][17]#1#
,03-18 15:48:20.997   970   970 I htcCheckinService: Checkin service onCreate()!
,03-18 15:48:20.997   970   991 I ActivityManager: Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4315 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
03-18 15:48:20.997  4116  4282 D MsgPreferenceUtils: phone state: true
03-18 15:48:20.997  4116  4282 D MsgPreferenceUtils: sd state: false
03-18 15:48:20.997  4116  4282 D MsgPreferenceUtils: vIndex = 0
,03-18 15:48:21.007  1430  1477 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
03-18 15:48:21.007  1430  1477 D AccFlag : device_type: 1
,03-18 15:48:21.007   970   970 D htcCheckinService: onStartCommand(),
,03-18 15:48:21.007   970   970 D htcCheckinService: onStartCommand() the action name = null
03-18 15:48:21.007   970   970 D htcCheckinService: ConnectivityReceiver - onReceive() - original mNetworkConnected = false
03-18 15:48:21.007   970   970 D htcCheckinService: ConnectivityReceiver - onReceive() - new mNetworkConnected = true
03-18 15:48:21.017   970  4330 D htcCheckinService: InitThread start
03-18 15:48:21.017  4116  4310 D TransactionService: Force clearing mTransactionList
03-18 15:48:21.017  4116  4310 D TransactionService: Force set service start id to 1
03-18 15:48:21.017  4116  4310 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
03-18 15:48:21.017  4116  4310 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
03-18 15:48:21.017  4116  4310 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
03-18 15:48:21.017  4116  4116 V TransactionService: Destroying TransactionService
03-18 15:48:21.017  4116  4310 V TransactionService: 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,03-18 15:48:21.017  4062  4113 D MediaProvider: [update][23]#0#
,03-18 15:48:21.017  4062  4113 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-18 15:48:21.027  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-18 15:48:21.027  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
,03-18 15:48:21.027  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/usb
03-18 15:48:21.027  4062  4113 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
03-18 15:48:21.027  4062  4113 W MediaScannerServiceEx: Process mounted intent for unmounted storage: /storage/usb
03-18 15:48:21.027   970  1980 I ActivityManager: Killing 2995:com.htc.contacts/u0a38 (adj 15): empty #17
03-18 15:48:21.027   970  1980 D Process : killProcessQuiet, pid=2995
03-18 15:48:21.027   970  1980 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:21.117   970  1393 I ActivityManager: Recipient 2995
,03-18 15:48:21.137  4062  4113 D MediaScannerServiceEx: [disAliveExtStorageRows]+196609
,03-18 15:48:21.137   970  1178 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml,
,03-18 15:48:21.147  4062  4113 D MediaProvider: [sendStorageAddedIfNeed]: /storage/usb : unmounted,
03-18 15:48:21.147  4062  4113 D MediaProvider: [update][10]#1#
,03-18 15:48:21.197   970  1393 D PMS     : acquireWL(ab4a487): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4315 10090 null
,03-18 15:48:21.197  4062  4113 D MediaProvider: [update][51]#0#
,03-18 15:48:21.197  4062  4113 D MediaScannerServiceEx: [disAliveExtStorageRows]--1, 0
,03-18 15:48:21.207  4062  4113 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null
,03-18 15:48:21.207  4062  4113 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
03-18 15:48:21.207  4062  4113 D MediaScannerServiceEx: [handleExternalVolume] ext storage
03-18 15:48:21.217  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
03-18 15:48:21.217  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
03-18 15:48:21.217  4062  4113 D MediaProviderUtils: calcVolumeId: /storage/usb
03-18 15:48:21.217  4062  4113 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
03-18 15:48:21.217  4062  4113 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
,03-18 15:48:21.227  4315  4315 I WorldClock.Global: isHEPDevice = true
,03-18 15:48:21.227  4062  4113 D MediaProvider: [update][10]#0#,
03-18 15:48:21.227   970   970 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-18 15:48:21.227   970   970 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 ,
03-18 15:48:21.227  4062  4113 D MediaProvider: [update][2]#0#,
,03-18 15:48:21.237   970   970 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4353 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a,
,03-18 15:48:21.247   970   970 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-18 15:48:21.247   970  4371 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=40 rxSum=27} preTxRxSum={txSum=40 rxSum=27}
03-18 15:48:21.247   970  4371 D WifiDataStallTracker: updateDataStallInfo: NONE
,03-18 15:48:21.247   970  4371 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
03-18 15:48:21.247  4315  4315 W SystemReader: Cannot find support_china_sense_feature, use default value instead
,03-18 15:48:21.257  4315  4352 W WorldClock.AlarmService: updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
,03-18 15:48:21.257   970  1178 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-18 15:48:21.257  4062  4113 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
03-18 15:48:21.257  4062  4113 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
,03-18 15:48:21.267  4062  4113 D MediaProvider: [update][34]#1#
,03-18 15:48:21.267  4062  4113 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
,03-18 15:48:21.267   970  1694 D PMS     : acquireWL(13fe929b): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4062 10017 null
,03-18 15:48:21.267  4315  4352 I WorldClock.AlarmUtils: Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,03-18 15:48:21.267  4315  4352 I WorldClock.AlarmUtils: Cancel any alarm from alarm manager
,03-18 15:48:21.267  4315  4315 I WorldClock.AlarmUtils: saveSupportOffAlarmInPreference: isSupport = false
,03-18 15:48:21.267  4062  4113 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
03-18 15:48:21.277  4315  4352 I WorldClock.AlarmUtils: broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,03-18 15:48:21.277  1218  1681 I IntentController: receive(android.intent.action.ALARM_CHANGED,1,false)
,03-18 15:48:21.277  4315  4315 I WorldClock.AlarmService: isDeviceEncryptionEnabled = false
,03-18 15:48:21.277   970  1393 D PMS     : releaseWL(ab4a487): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,03-18 15:48:21.287   970  1694 D Process : killProcessQuiet, pid=2278
,03-18 15:48:21.287   970  1694 I ActivityManager: Killing 2278:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
03-18 15:48:21.287   970  1694 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:21.407   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
,03-18 15:48:21.407   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=57
,03-18 15:48:21.407   970   970 E WifiTrafficPoller: notifying of data activity 1
03-18 15:48:21.407  1218  1218 D WIFI_ICON: WifiActivity: 1
03-18 15:48:21.407  1218  1218 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-18 15:48:21.417   970  1393 I ActivityManager: Recipient 2278,
,03-18 15:48:21.467   970  1152 E WifiStateMachine: handleMessage: E msg.what=131155
,03-18 15:48:21.467   970  1152 E WifiStateMachine: processMsg: ConnectedState
03-18 15:48:21.467   970  1152 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2457 sc=60 link=150 tx=4.9, 0.0, 0.0  rx=10.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1976379166] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-18 15:48:21.467   970  1152 E WifiStateMachine: processMsg: L2ConnectedState
03-18 15:48:21.467   970  1152 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2457 sc=60 link=150 tx=4.9, 0.0, 0.0  rx=10.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1976379165] gl hn u24 rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
03-18 15:48:21.467   970  1152 E WifiStateMachine:  get link layer stats 0
03-18 15:48:21.467   970  1152 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
03-18 15:48:21.467  1385  1385 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-18 15:48:21.477  1385  1385 I wpa_supplicant: environment dirty rate=0 [0][0][0],
03-18 15:48:21.477   970  1152 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 150
03-18 15:48:21.477   970  1152 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=150,
03-18 15:48:21.477   970  1152 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-56 "NG700"WPA_PSK
03-18 15:48:21.487   970  1152 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.45 txretriesrate=0.00 rxrate=5.84 userTriggerdPenalty0
03-18 15:48:21.487   970  1152 E WifiStateMachine:  good link -> stuck count =0
03-18 15:48:21.487   970  1152 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
03-18 15:48:21.487   970  1152 E WifiStateMachine:  isHighRSSI       ---> score=61
,03-18 15:48:21.497   970  1152 E WifiStateMachine: handleMessage: X
,03-18 15:48:21.497   970  1170 D WifiWatchdogStateMachine: RSSI current: 3 new: -56, 3
03-18 15:48:21.497  1218  1218 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-18 15:48:21.497  1218  1218 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-18 15:48:21.497  4315  4352 I WorldClock.AlarmUtils: isDeviceEncryptionEnabled = false
,03-18 15:48:21.507  4315  4352 I WorldClock.AlarmUtils: Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,03-18 15:48:21.507  4315  4352 I WorldClock.AlarmService: resetStopwatchToDefault
,03-18 15:48:21.517  4315  4379 I WorldClock.DmdCmd: This version is general off mode alarm function
,03-18 15:48:21.517  4315  4379 W WorldClock.DmdCmd: Conn: fail e = java.io.IOException: No such file or directory
,03-18 15:48:21.527  4353  4353 E UpdateRequestReceiver: ignoring update request
,03-18 15:48:21.527  4315  4352 E SQLiteDatabase: Failed to open database '/data/data/com.htc.android.worldclock/databases/stopwatch.db'.
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at com.htc.android.worldclock.stopwatch.StopwatchProvider.delete(StopwatchProvider.java:61)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at com.htc.android.worldclock.stopwatch.StopwatchUtils.DeleteStopwatchLapData(StopwatchUtils.java:75)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at com.htc.android.worldclock.alarmclock.AlarmService.resetStopwatchToDefault(AlarmService.java:246)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at com.htc.android.worldclock.alarmclock.AlarmService.access$400(AlarmService.java:39)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at com.htc.android.worldclock.alarmclock.AlarmService$2.run(AlarmService.java:160)
03-18 15:48:21.527  4315  4352 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-18 15:48:21.527  4315  4352 W WorldClock.StopwatchUtils: DeleteStopwatchLapData: e = android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:21.527  4315  4352 I WorldClock.AlarmService: resetTimerToDefault
,03-18 15:48:21.537  4353  4353 E UpdateRequestReceiver: ignoring update request
03-18 15:48:21.547  4353  4353 E UpdateRequestReceiver: ignoring update request
03-18 15:48:21.547  4353  4353 E UpdateRequestReceiver: ignoring update request
03-18 15:48:21.557  4353  4353 E UpdateRequestReceiver: ignoring update request
,03-18 15:48:21.567  4353  4353 E UpdateRequestReceiver: ignoring update request,
,03-18 15:48:21.587   970  1393 D Process : killProcessQuiet, pid=3742,
03-18 15:48:21.587   970  1393 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4394 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
03-18 15:48:21.587   970  1393 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-18 15:48:21.587   970  1393 I ActivityManager: Killing 3742:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,03-18 15:48:21.707   970  1695 I ActivityManager: Recipient 3742,
,03-18 15:48:21.857  4394  4394 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4394 dbg=false s=true
,03-18 15:48:21.867  4394  4394 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,03-18 15:48:21.867  4394  4394 I DeviceManagement: WorkflowService: Starting workflow service,
,03-18 15:48:21.877  4394  4416 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@378f2bd5] args=[Bundle[EMPTY_PARCEL]]
,03-18 15:48:21.877  4394  4416 I DeviceManagement: BootCompletedWorkflow: ==================================================,
03-18 15:48:21.877  4394  4416 I DeviceManagement: BootCompletedWorkflow: Boot completed
03-18 15:48:21.877  4394  4416 I DeviceManagement: BootCompletedWorkflow: ==================================================,
03-18 15:48:21.877  4394  4416 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,03-18 15:48:21.887  1834  4417 I GoogleHttpClient: GMS http client unavailable, use old client
,03-18 15:48:21.907   970  1161 I ActivityManager: Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4418 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
,03-18 15:48:21.907  4116  4170 V SmsReceiverService: updateNotificationAndShortcutStatus: 
,03-18 15:48:21.907  4116  4170 D MessagingNotification: New incoming message, can't cancel notification now
03-18 15:48:21.907  4116  4170 D MessagingNotification: newMsgCnt: 0, false
,03-18 15:48:21.917   970  2015 I ActivityManager: Killing 3782:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17,
03-18 15:48:21.917   970  2015 D Process : killProcessQuiet, pid=3782
03-18 15:48:21.917   970  2015 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-18 15:48:21.917  4394  4416 I DeviceManagement: BackgroundController: *** Update after boot...,
03-18 15:48:21.927  4394  4416 I DeviceManagement: SessionStateController: Checking invariants...
,03-18 15:48:21.937  4394  4437 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.cs.dm/shared_prefs/com.htc.cs.dm_state.xml to backup file /data/data/com.htc.cs.dm/shared_prefs/com.htc.cs.dm_state.xml.bak
,03-18 15:48:21.977  4062  4113 D MediaScanner:  prescan time: 89ms,
03-18 15:48:21.987  4062  4113 D MediaScanner:     scan time: 619ms
03-18 15:48:21.987  4062  4113 D MediaScanner: postscan time: 2ms
03-18 15:48:21.987  4062  4113 D MediaScanner:    total time: 710ms
03-18 15:48:21.987  4062  4113 D MediaScanner: -----------------------------------------------------------------,
03-18 15:48:21.987  4062  4113 D MediaScanner: firstscan(media) time: 331ms
03-18 15:48:21.987  4062  4113 D MediaScanner: secondscan(non-media) time: 288ms
03-18 15:48:21.987  4062  4113 D MediaScanner:  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:21.987  4062  4113 D MediaScanner:  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
03-18 15:48:21.987  4062  4113 D MediaScanner:  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0,
03-18 15:48:21.987  4062  4113 D MediaScanner:  [Total]    File(Image+Video+Audio+Others) in database : 1549
,03-18 15:48:21.997   970  1690 I ActivityManager: Recipient 3782,
,03-18 15:48:22.027   970  1327 D PMS     : releaseWL(1a55396b): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null,
,03-18 15:48:22.067  4394  4416 I DeviceManagement: BackgroundController: Invariants are unchanged.,
,03-18 15:48:22.077  4394  4441 I DeviceManagement: SessionStateController: Checking invariants...,
,03-18 15:48:22.137  4394  4441 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
,03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: ,	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: ,	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176),
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:22.137  4394  4441 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-18 15:48:22.137  4394  4441 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
03-18 15:48:22.147  4394  4416 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:22.147  4394  4416 I DeviceManagement: Perf: *** Cache update - start...
,03-18 15:48:22.147  4394  4416 I DeviceManagement: Perf: *** Enabled app cache update - start...
03-18 15:48:22.147  4394  4416 I DeviceManagement: EnabledAppController: *** Updating enabled app database...
,03-18 15:48:22.147  4394  4416 I DeviceManagement: EnabledAppController: Enabled app scan is pending...
03-18 15:48:22.147  4394  4416 I DeviceManagement: Perf: Scan enabled apps - start...
,03-18 15:48:22.157  1486  1960 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
03-18 15:48:22.157  1486  1960 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@763de51 +
03-18 15:48:22.157  1486  1960 I Prism.WidgetManager: onLoadItems() +
03-18 15:48:22.157  4418  4418 I htcbackup-core: ModelRegistry: Loading model meta data from resources...
03-18 15:48:22.167  1584  1802 D AutoSetting: service - mRequestRunnable: screen on delay 10s, request NLP now
03-18 15:48:22.167  1584  1802 D AutoSetting: Util - check NLP state, Allowned:false, Enabled:false
03-18 15:48:22.167  1584  1802 D AutoSetting: service - requestNLP() NetworkLocationProvider not enabled
,03-18 15:48:22.197  1486  1960 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-18 15:48:22.217  4394  4416 I DeviceManagement: EnabledAppBuilder: Examining 269 installed apps for DM enabled apps...
,03-18 15:48:22.237   970  2015 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,03-18 15:48:22.247  4394  4416 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,03-18 15:48:22.257  4394  4414 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
03-18 15:48:22.257  4394  4414 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,03-18 15:48:22.257  4418  4446 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,03-18 15:48:22.257  4394  4465 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,03-18 15:48:22.357  4394  4416 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-18 15:48:22.367  4394  4416 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159,
,03-18 15:48:22.377  1296  1317 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true,
03-18 15:48:22.377  1296  1317 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix,
,03-18 15:48:22.377  1218  1218 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-18 15:48:22.397  1218  1218 I RemoteViews: apply : com.htc.backup 1 18 6 38
,03-18 15:48:22.397  1218  1218 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-18 15:48:22.407   970   970 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 5
03-18 15:48:22.407   970   970 E WifiTrafficPoller:  packet count Tx=54 Rx=57
03-18 15:48:22.407   970   970 E WifiTrafficPoller: notifying of data activity 0
,03-18 15:48:22.417   970  2015 I ActivityManager: Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4474 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
03-18 15:48:22.417   970  2015 D Process : killProcessQuiet, pid=3825
03-18 15:48:22.417   970  2015 I ActivityManager: Killing 3825:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
03-18 15:48:22.417   970  2015 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-18 15:48:22.417  1218  1218 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-18 15:48:22.427  1218  1218 I RemoteViews: apply : com.htc.backup 1 6 3 5
,03-18 15:48:22.427  1218  1218 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)
,03-18 15:48:22.427  4394  4416 I DeviceManagement: EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167,
03-18 15:48:22.427  1218  1218 I RemoteViews: apply : com.htc.backup 0 2 1 5
03-18 15:48:22.427  1218  1218 I RemoteViews: setHTCTheme(com.htc.backup,true,33751145)

```
