#### Test 503880196ac79ce_thali03_LGE-LG-D855 Logs


```--------- beginning of system
11-17 18:31:15.561  1031  1758 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4293 uid=10043 gids={50043, 9997, 1028, 3003} abi=armeabi-v7a
--------- beginning of main
11-17 18:31:15.571  4271  4271 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:15.571  4271  4271 D LgDataFeature: LgDataFeature() Constructor Done, null
11-17 18:31:15.592  4271  4271 E MPT MptOnPowerWatcher: MptOnPowerWatcher
11-17 18:31:15.605  4271  4271 E dbFlushManager: Handler is not ready.
11-17 18:31:15.605  4271  4271 E dbFlushManager: It's going to sleep routine until the message handler is generated.
11-17 18:31:15.632  4271  4271 E MPT MptOnPowerWatcher: startListen
,11-17 18:31:15.694  1031  1703 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4317 uid=10050 gids={50050, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
11-17 18:31:15.696  1031  1703 I ActivityManager: Killing 3809:com.google.android.partnersetup/u0a8 (adj 15): empty #17
11-17 18:31:15.718   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 20.996ms
11-17 18:31:15.740   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 21.630ms
11-17 18:31:15.769   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 20.183ms
11-17 18:31:15.812  1031  2024 W libprocessgroup: failed to open /acct/uid_10008/pid_3809/cgroup.procs: No such file or directory
11-17 18:31:15.956  4333  4333 D AndroidRuntime: 
11-17 18:31:15.956  4333  4333 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:31:15.960  4333  4333 D AndroidRuntime: CheckJNI is OFF
11-17 18:31:16.010  1031  1759 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4342 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
11-17 18:31:16.027  1031  1046 D LocationManagerService: getProviders()=[passive]
11-17 18:31:16.130  4317  4378 I ContactAccountLoggerTas: canRun() : Opted Out
11-17 18:31:16.148  1031  2560 I ActivityManager: Killing 3843:com.lge.clock/u0a10 (adj 15): empty #17
11-17 18:31:16.168  4333  4333 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:31:16.182  1031  2080 W libprocessgroup: failed to open /acct/uid_10010/pid_3843/cgroup.procs: No such file or directory
11-17 18:31:16.185  1031  2085 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:31:16.193  1973  1989 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
11-17 18:31:16.197  1031  2085 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
11-17 18:31:16.198  1031  2085 V ActivityStackEx: create ActivityStackEx
11-17 18:31:16.218  1413  1413 D LgeAbsQuickCoverView: mCoverXPos: 0 ,mCoverYPos: 0
11-17 18:31:16.218  1413  1413 D LgeAbsQuickCoverView: mCoverWidth: 0 ,mCoverHeight: 0
11-17 18:31:16.222  1031  2085 D ActivityManager: setTaskToReturnTo : TaskRecord{20325298 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:31:16.222  1031  2085 D ActivityManager: setTaskToReturnTo : TaskRecord{20325298 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:31:16.229  1031  2085 D WindowStateEx: AppWindowTokenEx init.. 
11-17 18:31:16.230  1031  1108 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
11-17 18:31:16.231  1413  1413 D QuickStatusbarLayout: Notification difference=198
11-17 18:31:16.231  1413  1413 D QuickStatusbarLayout: child = android.widget.LinearLayout{33f5ea7b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
11-17 18:31:16.235   337   352 E GBMv2   : DFP En is all cleared set to be enabled
11-17 18:31:16.236  2090  2090 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
11-17 18:31:16.236  1973  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
11-17 18:31:16.237  1973  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13337c5 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
11-17 18:31:16.242  1031  1108 D SplitWindow: check instance of lgWin Window{1a7b052d u0 Starting com.example.hello}
11-17 18:31:16.261  1031  1399 D WifiService: New client listening to asynchronous messages
11-17 18:31:16.268  1031  2061 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
11-17 18:31:16.268  4333  4333 D AndroidRuntime: Shutting down VM
11-17 18:31:16.268  1929  1929 D ActionManagerService: notifyUserLog: 1000004
11-17 18:31:16.269  3566  4193 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
11-17 18:31:16.270   312   312 V AudioPolicyService: registerClient() client 0xb14275e0, uid 10003
11-17 18:31:16.270  3566  4190 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: , create_time: 1430558575574
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: , expire_time: 0
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: , display: false
11-17 18:31:16.275  2090  2090 I GBoardWebViewUtils: , animation: false }
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , create_time: 1430558575600
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , expire_time: 0
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , display: false
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , animation: false }
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447331016048
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , create_time: 1447331016852
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , expire_time: 0
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1447331016048&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , display: false
11-17 18:31:16.276  2090  2090 I GBoardWebViewUtils: , animation: false }
11-17 18:31:16.313  1031  1758 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4390 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:31:16.318  4317  4317 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:16.318  4317  4317 D LgDataFeature: LgDataFeature() Constructor Done, null
11-17 18:31:16.334  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:266:writeCacheBitmap()]writeCacheBitmap()
11-17 18:31:16.354  1031  2085 I WindowStateAnimator: Starting window displayed
11-17 18:31:16.360  1031  1106 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
11-17 18:31:16.361  1031  1106 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:31:16.361  1031  1106 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:31:16.361  1031  1106 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:31:16.361  1031  1106 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2be92f9e,  pkg=WindowManager.LayoutParams
11-17 18:31:16.361  1031  1106 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:31:16.370  1973  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
11-17 18:31:16.373  1468  1468 D PhoneStatusBar: setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
11-17 18:31:16.374  1973  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{52af51a co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
11-17 18:31:16.374  1468  1468 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
11-17 18:31:16.374  1468  1468 I [SystemUI]NavigationThemeResource:  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:31:16.374  1468  1468 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:31:16.385  4317  4317 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
11-17 18:31:16.412  4390  4390 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
11-17 18:31:16.419  4317  4317 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
11-17 18:31:16.420  4317  4317 I ContactLabelSupplier: get() : Execute runnable (UI thread)
11-17 18:31:16.422  4317  4378 I ContactLabelSupplier: get() : OptedIn = false
,11-17 18:31:16.481  2025  2025 D WiseScreenService: [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
11-17 18:31:16.485  2025  2025 D WiseScreenService: [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
11-17 18:31:16.486  2025  2025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1763 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2586 
11-17 18:31:16.497  1031  1031 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
11-17 18:31:16.497  1031  1031 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
11-17 18:31:16.529  4390  4390 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
11-17 18:31:16.533  1031  1031 I ActivityManager: Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4409 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:31:16.545  4390  4390 I LibraryLoader: Loading: webviewchromium
11-17 18:31:16.548  4390  4390 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7476-7478)
11-17 18:31:16.548  4390  4390 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:31:16.572  4390  4390 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b90996d}
11-17 18:31:16.573  4390  4390 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:31:16.573  4390  4390 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:31:16.577  1031  1052 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
11-17 18:31:16.577  1031  1052 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
11-17 18:31:16.577  1031  1052 D sensors_hal_Time: tsOffsetIs: Apps: 47507528943; DSPS: 1698207; Offset : -4334142257
11-17 18:31:16.585  4390  4390 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:31:16.586  4390  4390 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:31:16.592  4390  4429 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
11-17 18:31:16.602   312  1675 V AudioPolicyService: registerClient() client 0xb14276a0, uid 10318
11-17 18:31:16.605  1031  1107 D BluetoothManagerService: Message: 20
11-17 18:31:16.606  1031  1107 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7fee80e:true
11-17 18:31:16.606  4390  4433 D BluetoothAdapter: 580827554: getState() :  mService = null. Returning STATE_OFF
11-17 18:31:16.608  2090  2090 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
11-17 18:31:16.614  4390  4390 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
11-17 18:31:16.614  4390  4390 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
11-17 18:31:16.615  4390  4390 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
11-17 18:31:16.627  4390  4390 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
11-17 18:31:16.627  4390  4390 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
11-17 18:31:16.627  4390  4390 I Adreno-EGL: Build Date: 12/12/14 금
11-17 18:31:16.627  4390  4390 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
11-17 18:31:16.627  4390  4390 I Adreno-EGL: Remote Branch: 
11-17 18:31:16.627  4390  4390 I Adreno-EGL: Local Patches: 
11-17 18:31:16.627  4390  4390 I Adreno-EGL: Reconstruct Branch: 
11-17 18:31:16.705  4390  4439 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
11-17 18:31:16.710  4390  4390 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
11-17 18:31:16.727  4390  4390 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:31:16.733  4390  4390 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:31:16.737  4409  4409 V CloudHub: [DATABASE][DBConnection|open] open database
11-17 18:31:16.739  4409  4409 E CloudHub: [DATABASE][DBConnection|getUserId] User id: 0
11-17 18:31:16.740  4409  4409 E CloudHub: [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
11-17 18:31:16.754  4390  4390 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
11-17 18:31:16.761  4409  4409 V CloudHub: [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
11-17 18:31:16.766  3329  3344 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='197' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
11-17 18:31:16.767  3329  3344 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f0cde4 on behalf of 4409
11-17 18:31:16.770  4409  4409 V CloudHub: [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
11-17 18:31:16.815  1031  2061 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4447 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
11-17 18:31:16.817  1031  2061 I ActivityManager: Killing 3928:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #17
11-17 18:31:16.869  1031  1703 W libprocessgroup: failed to open /acct/uid_10011/pid_3928/cgroup.procs: No such file or directory
11-17 18:31:16.880  4390  4390 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:31:16.880  4390  4390 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:31:16.915  4390  4471 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:31:16.915  4390  4471 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:31:16.922  4390  4471 D OpenGLRenderer: Enabling debug mode 0
11-17 18:31:16.931  4390  4390 D Atlas   : Validating map...
11-17 18:31:16.936  1031  2024 D SplitWindow: check instance of lgWin Window{2d485758 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:31:16.962  4390  4466 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:16.962  4390  4466 D LgDataFeature: LgDataFeature() Constructor Done, null
11-17 18:31:16.977  4447  4447 E UpdateRequestReceiver: ignoring update request
11-17 18:31:16.982  4447  4447 E UpdateRequestReceiver: ignoring update request
11-17 18:31:16.988  4447  4447 E UpdateRequestReceiver: ignoring update request
11-17 18:31:16.997  4447  4447 E UpdateRequestReceiver: ignoring update request
11-17 18:31:17.002  4447  4447 E UpdateRequestReceiver: ignoring update request
11-17 18:31:17.006  4447  4447 E UpdateRequestReceiver: ignoring update request
11-17 18:31:17.068  1031  1972 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4489 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
11-17 18:31:17.071  1031  1972 I ActivityManager: Killing 3947:com.lge.appbox.client/u0a11 (adj 15): empty #17
11-17 18:31:17.110  1031  1430 W libprocessgroup: failed to open /acct/uid_10011/pid_3947/cgroup.procs: No such file or directory
11-17 18:31:17.140  4390  4390 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@50ccf52 time:48071
11-17 18:31:17.152  1031  1108 I ActivityManager: Displayed com.example.hello/.MainActivity: +874ms
11-17 18:31:17.152  1031  1108 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{427aaf1 u0 com.example.hello/.MainActivity t2} time:48083
11-17 18:31:17.171  4390  4390 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:31:17.177  4390  4506 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:31:17.199  4489  4489 V DrmBroadcastReceiver: Receive ACTION_BOOT_COMPLETED
11-17 18:31:17.208  4489  4489 V DrmService: Service onCreate
11-17 18:31:17.208  4489  4489 D DrmService: Received new request = 4
11-17 18:31:17.223  4489  4489 D DrmServiceHandler: updateDrmPushNotification() : No notification
11-17 18:31:17.224  4489  4489 D DrmService: Completed !! request = 4
11-17 18:31:17.224  4489  4489 D DrmService: Request count = 0
11-17 18:31:17.249  4390  4390 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:31:17.256  1031  1748 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4509 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:31:17.269  4489  4489 V DrmService: Service onDestroy
11-17 18:31:17.273  1031  2024 I ActivityManager: Killing 3971:com.android.browser/u0a12 (adj 15): empty #17
11-17 18:31:17.300  4390  4466 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
11-17 18:31:17.300  4390  4466 I chromium: 
11-17 18:31:17.340  1031  1704 W libprocessgroup: failed to open /acct/uid_10012/pid_3971/cgroup.procs: No such file or directory
11-17 18:31:17.385  4390  4507 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:31:17.385  4390  4507 I chromium: 
11-17 18:31:17.530  4390  4527 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1653115520
,11-17 18:31:17.539  4390  4527 D JX-Cordova: jxcore cordova android initializing
11-17 18:31:17.623  4390  4390 W jxcore-log: Initializing JXcore engine
11-17 18:31:17.623  4390  4390 W jxcore-log: JXcore engine is ready
,11-17 18:31:17.630  4390  4390 W jxcore-log: Starting JXcore engine
11-17 18:31:17.702  4390  4390 W m.example.hello: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7492]" dev="sockfs" ino=7492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,11-17 18:31:17.702  4390  4390 W m.example.hello: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
11-17 18:31:17.702  4390  4390 W m.example.hello: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7637]" dev="sockfs" ino=7637 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
11-17 18:31:17.712  4390  4390 W m.example.hello: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
11-17 18:31:17.712  4390  4390 W m.example.hello: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[22901]" dev="sockfs" ino=22901 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
11-17 18:31:17.725  1031  2080 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:31:17.798  4509  4543 I Gmail   : getAccountsCursor
,11-17 18:31:17.815  2134  2134 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:31:17.823  1031  1430 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:31:17.826  1031  1759 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,11-17 18:31:17.833  4509  4546 I Gmail   : Observing account changes for notifications
11-17 18:31:17.840   337   354 E GBMv2   : DFP En is all cleared set to be enabled
11-17 18:31:17.840   337   354 E GBMv2   : Set value is all cleared set the max
11-17 18:31:17.840   337   354 I GBMv2   : DFP Enabled. Ignore VFP set
,11-17 18:31:17.843  4509  4509 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
11-17 18:31:17.885  4390  4390 W jxcore-log: Platform android
11-17 18:31:17.885  4390  4390 W jxcore-log: 
11-17 18:31:17.885  4390  4390 W jxcore-log: Process ARCH arm
11-17 18:31:17.885  4390  4390 W jxcore-log: 
,11-17 18:31:17.903  1031  1990 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:31:17.936  2134  2134 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,11-17 18:31:17.939  2134  2134 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,11-17 18:31:17.957  4390  4390 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:31:17.957  4390  4390 I jxcore-log: 
11-17 18:31:17.957  4390  4390 W jxcore-log: JXcore engine is started
,11-17 18:31:17.974  1031  2085 I art     : Explicit concurrent mark sweep GC freed 18039(973KB) AllocSpace objects, 5(939KB) LOS objects, 33% free, 43MB/65MB, paused 2.053ms total 129.103ms
,11-17 18:31:18.000  4509  4551 E Gmail   : Error finding the version of the Email provider.....
11-17 18:31:18.000  4509  4551 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
11-17 18:31:18.000  4509  4551 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
11-17 18:31:18.000  4509  4551 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
11-17 18:31:18.000  4509  4551 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
11-17 18:31:18.000  4509  4551 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:31:18.000  4509  4551 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:31:18.000  4509  4551 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
11-17 18:31:18.000  4509  4551 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:31:18.000  4509  4551 W EmailMigration: We do not support migrating this version of the Email provider.
11-17 18:31:18.006  4509  4543 I Gmail   : getAccountsCursor
11-17 18:31:18.013  2134  2134 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:31:18.023  2134  2134 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:31:18.025  4390  4390 E jxcore-log: >> LGE-LG-D855
11-17 18:31:18.025  4390  4390 E jxcore-log: 
11-17 18:31:18.028  4390  4390 I jxcore-log: Total memory 2995761152
11-17 18:31:18.028  4390  4390 I jxcore-log: 
11-17 18:31:18.028  4390  4390 I jxcore-log: Free memory 878206976
11-17 18:31:18.028  4390  4390 I jxcore-log: 
11-17 18:31:18.028  4390  4390 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:31:18.028  4390  4390 I jxcore-log: 
11-17 18:31:18.028  4390  4390 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:31:18.028  4390  4390 I jxcore-log: 
11-17 18:31:18.033  4390  4390 I jxcore-log: userPath [ 'www' ]
11-17 18:31:18.033  4390  4390 I jxcore-log: 
11-17 18:31:18.034  4390  4390 I jxcore-log: Size 1440 2392
11-17 18:31:18.034  4390  4390 I jxcore-log: 
11-17 18:31:18.035  4390  4390 I jxcore-log: Screen Brightness 50
11-17 18:31:18.035  4390  4390 I jxcore-log: 
,11-17 18:31:18.035  4390  4390 E jxcore-log: Dummy Error Log.
11-17 18:31:18.035  4390  4390 E jxcore-log: 
11-17 18:31:18.066  1031  1990 I ActivityManager: Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4555 uid=10065 gids={50065, 9997, 1028, 1015} abi=armeabi-v7a
,11-17 18:31:18.067  1031  1704 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
11-17 18:31:18.082  1031  2024 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,11-17 18:31:18.095  4509  4509 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@139dc88b that was originally bound here
11-17 18:31:18.095  4509  4509 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@139dc88b that was originally bound here
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:31:18.095  4509  4509 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:31:18.097  1031  2024 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@165bf8fc
11-17 18:31:18.117  4509  4553 E SQLiteLog: (283) recovered 347 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,11-17 18:31:18.133  4555  4555 D AirTest : Set airtest_enable to false
11-17 18:31:18.145  2134  4576 I GoogleHttpClient: GMS http client unavailable, use old client
,11-17 18:31:18.173  1031  1758 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4579 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
11-17 18:31:18.193  1031  2080 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
11-17 18:31:18.198  2346  4575 I Icing   : Storage manager: low false usage 1.99MB avail 19.92GB capacity 21.67GB
,11-17 18:31:18.204  4509  4544 I Gmail   : getAccountsCursor
11-17 18:31:18.207  4509  4569 I Gmail   : notifyAccountChanged
,11-17 18:31:18.211  2134  2134 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:31:18.212  1031  2024 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
11-17 18:31:18.220  4509  4569 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
11-17 18:31:18.231  4579  4579 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,11-17 18:31:18.231  3566  3566 D ConciergeFeature: Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
11-17 18:31:18.233  3566  3566 D ConciergeFeature: concierge_reconnect_old_contact  : true
11-17 18:31:18.233  3566  3566 D ConciergeFeature: concierge_add_contact_proposal  : true
11-17 18:31:18.233  3566  3566 D ConciergeFeature: concierge_redial_recommend  : true
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_notify_birthday  : true
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_qmemo  : true
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_weather_newsflash  : false
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_spring_cleaning  : true
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_my_guide  : true
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_my_wellness  : true
11-17 18:31:18.234  3566  3566 D ConciergeFeature: concierge_isai_keyword_update  : false
11-17 18:31:18.234  3566  3566 I LIA_Informant_ConciergeCardManager: availability of concierge_reconnect_old_contact: true
11-17 18:31:18.234  3566  3566 D LIA_Informant_FlowManagerPlant: FAVORITENUM_RECOMMENDER
11-17 18:31:18.236  3566  3566 D LIA_Informant_FavoriteNumScheduler: start!
11-17 18:31:18.236  3566  3566 I LIA_Informant_ActionManagerMessageHandler: registerListener = concierge_reconnect_old_contact
11-17 18:31:18.236  3566  3566 I LIA_Informant_ActionManagerMessageHandler: after add numListener = 6
11-17 18:31:18.238  3566  3566 D LIA_Informant_FavoriteNumScheduler: curentDate : 20151117
11-17 18:31:18.243  3566  3566 D LIA_Informant_FavoriteNumScheduler: AlarmReceivedDate : 20151117
11-17 18:31:18.243  3566  3566 D InformantAlarmUtil: getFirstAlarm
11-17 18:31:18.244  3566  3566 D LIA_Informant_InformantCalendarUtil: getDay()
11-17 18:31:18.244  3566  3566 D InformantAlarmUtil: getAlarmListOfDay: day = 4
11-17 18:31:18.247  4509  4569 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,11-17 18:31:18.256  4509  4569 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
11-17 18:31:18.256  4509  4569 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
11-17 18:31:18.277  1031  2061 I ActivityManager: Start proc com.lge.clock for content provider com.lge.clock/.alarmclock.ALProvider: pid=4601 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,11-17 18:31:18.278  4509  4553 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
11-17 18:31:18.281  4509  4553 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
11-17 18:31:18.285  4509  4553 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
11-17 18:31:18.293  1031  1748 I ActivityManager: Killing 3993:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #17
,11-17 18:31:18.383  1031  2024 W libprocessgroup: failed to open /acct/uid_10016/pid_3993/cgroup.procs: No such file or directory
,11-17 18:31:18.406  4509  4538 I Gmail   : getAccountsCursor
,11-17 18:31:18.413  2134  2134 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:31:18.457  4579  4579 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:18.457  4579  4579 D LgDataFeature: LgDataFeature() Constructor Done, null
,11-17 18:31:18.466  3566  3566 D LIA_Informant_FavoriteNumScheduler: setAlarm
11-17 18:31:18.466  3566  3566 D LIA_Informant_FavoriteNumScheduler: Date : Tue Nov 17 08:00:00 GMT+01:00 2015
11-17 18:31:18.470  3566  3566 D ConciergeFeature: Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
11-17 18:31:18.472  3566  3566 D ConciergeFeature: concierge_reconnect_old_contact  : true
11-17 18:31:18.472  3566  3566 D ConciergeFeature: concierge_add_contact_proposal  : true
11-17 18:31:18.472  3566  3566 D ConciergeFeature: concierge_redial_recommend  : true
11-17 18:31:18.472  3566  3566 D ConciergeFeature: concierge_notify_birthday  : true
11-17 18:31:18.472  3566  3566 D ConciergeFeature: concierge_qmemo  : true
11-17 18:31:18.472  3566  3566 D ConciergeFeature: concierge_weather_newsflash  : false
11-17 18:31:18.473  3566  3566 D ConciergeFeature: concierge_spring_cleaning  : true
11-17 18:31:18.473  3566  3566 D ConciergeFeature: concierge_my_guide  : true
11-17 18:31:18.473  3566  3566 D ConciergeFeature: concierge_my_wellness  : true
11-17 18:31:18.473  3566  3566 D ConciergeFeature: concierge_isai_keyword_update  : false
11-17 18:31:18.473  3566  3566 I LIA_Informant_ConciergeCardManager: availability of concierge_notify_birthday: true
11-17 18:31:18.473  3566  3566 D LIA_Informant_FlowManagerPlant: BIRTHDAY_NOTI
11-17 18:31:18.474  3566  3566 D LIA_Informant_AnniversaryRequester: AnniversaryRequester
11-17 18:31:18.474  3566  3566 D LIA_Informant_AnniversaryMessageGenerator: AnniversaryMessageGenerator
11-17 18:31:18.475  3566  3566 D LIA_Informant_DailyScheduler: AlarmCheckingScheduler = 0
11-17 18:31:18.475  3566  3566 D LIA_Informant_DailyScheduler: start!
11-17 18:31:18.476  3566  3566 D LIA_Informant_DailyScheduler: curentDate : 20151117
,11-17 18:31:18.479  3566  3566 D LIA_Informant_DailyScheduler: excutedDate : 20151117
11-17 18:31:18.482  3566  3566 I LIA_Informant_ConciergeCardManager: after add event [4]
11-17 18:31:18.484  3566  3566 D LIA_S4URecommender_LIARemoteService: onStartCommand() : LIARemoteService started! - (Id :3), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
11-17 18:31:18.485  3566  3566 D LIA_Informant_ConnectionProxy: onServiceConnected() : com.lge.ia.task.s4urecommender
11-17 18:31:18.485  3566  3566 D LIA_S4URecommender_LIARemoteManager: getProperties()
11-17 18:31:18.485  3566  3566 D LIA_S4URecommender_TaskLauncher: getTaskPropertyList() - main launcher : false
11-17 18:31:18.485  3566  3566 I LIA_Informant_ConnectionProxy: Checking activation option of S4URecommender
11-17 18:31:18.486  3566  3566 I LIA_Informant_ConnectionProxy: Task Property : S4URecommender, true
11-17 18:31:18.486  3566  3566 I LIA_Informant_ConnectionProxy: Task activation property : S4URecommender, true
11-17 18:31:18.486  3566  3566 I LIA_Informant_ConnectionProxyHandler: ConnectionProxyListener - onConnected : 
11-17 18:31:18.486  3566  3566 V LIA_Informant_ConnectionProxyHandler: S4URecommender Task Property: Activation:true, AutoExecution:true
11-17 18:31:18.486  3566  3566 D LIA_Informant_ConnectionProxy: getTaskConnector(S4URecommender / com.lge.ia.task.s4urecommender) : Thread(1)
11-17 18:31:18.486  3566  3566 D LIA_S4URecommender_LIARemoteManager: getTask() : S4URecommender
11-17 18:31:18.486  3566  3566 D LIA_S4URecommender_TaskLauncher: getTask() : S4URecommender (main launcher : false)
,11-17 18:31:18.488  3566  3566 I LIA_S4URecommender_TaskContext: getNewAppSession() : App session is added - com.lge.ia.manager.session.AppSession@287348e6
11-17 18:31:18.490  3566  3566 I LIA_Informant_ConnectionProxyHandler: setTaskConnectorIntoTask - Success
11-17 18:31:18.490  3566  3566 I LIA_Informant_ConnectionProxyHandler: stopTimeoutTimer
11-17 18:31:18.491  3566  4270 I LIA_Informant_LGIntelligentAgent: tryConnecting : onTryConnectionSuccess - com.lge.ia.LIAS4URecommender@21304e27
11-17 18:31:18.491  3566  4270 I LIA_Informant_LGIntelligentAgent: tryConnecting onTryConnectionSuccess : map remove - 0
11-17 18:31:18.491  3566  4270 D LIA_Informant_RedialManager: S4URecommender onConnected!
11-17 18:31:18.493  1031  2061 I ActivityManager: Killing 3154:com.android.contacts/u0a19 (adj 15): empty #17
11-17 18:31:18.553  1031  1990 W libprocessgroup: failed to open /acct/uid_10019/pid_3154/cgroup.procs: No such file or directory
,11-17 18:31:18.555  4390  4390 I jxcore-log: getBuffer is called!!!!
11-17 18:31:18.555  4390  4390 I jxcore-log: 
11-17 18:31:18.557  1031  1430 I ActivityManager: Killing 2527:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
11-17 18:31:18.593  2346  4575 I Icing   : updateResources: need to parse f{com.google.android.gms}
,11-17 18:31:18.595  4041  4123 D UEI.SmartControl: Internal timer expired: 1
11-17 18:31:18.596  4041  4123 D UEI.SmartControl: unbind internal service
11-17 18:31:18.644  4041  4120 D serial_port: close(fd = 25)
,11-17 18:31:18.649  4041  4120 I UEI.SmartControl: Serial port is closed.
11-17 18:31:18.662  1031  1748 W libprocessgroup: failed to open /acct/uid_10005/pid_2527/cgroup.procs: No such file or directory
,11-17 18:31:18.667  4041  4041 D UEI.SmartControl: Service.onUnbind: IControl
11-17 18:31:18.668  4041  4041 D UEI.SmartControl: Service.onDestroy
11-17 18:31:18.668  4041  4041 D UEI.SmartControl: Lock is in USE false
11-17 18:31:18.668  4041  4041 D UEI.SmartControl: unbind internal service
11-17 18:31:18.668  4041  4041 I UEI.SmartControl: Serial port is closed.
11-17 18:31:18.668  4041  4041 I UEI.SmartControl: Serial port is closed.
11-17 18:31:18.668  4041  4041 D UEI.SmartControl: Blaster closed
11-17 18:31:18.669  4041  4041 D UEI.SmartControl: Shut down QS...
11-17 18:31:18.669  4041  4041 D UEI.SmartControl: Stopping QS lib
11-17 18:31:18.670  4041  4041 D UEI.SmartControl: QS lib stop result = true
11-17 18:31:18.670  4041  4041 D UEI.SmartControl: Stopped QS lib
11-17 18:31:18.670  4041  4041 D UEI.SmartControl: Stopped file observer...
11-17 18:31:18.670  4041  4041 D UEI.SmartControl: QS shutdown complete
,11-17 18:31:18.735  4579  4630 I Babel   : MmsConfig: mnc/mcc: 0/0
11-17 18:31:18.735  4579  4630 I Babel   : MmsConfig.loadMmsSettings
11-17 18:31:18.741  4579  4630 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
11-17 18:31:18.741  4579  4630 I Babel   : MmsConfig.loadFromDatabase
11-17 18:31:18.745  1031  1088 I ActivityManager: Waited long enough for: ServiceRecord{28943bb8 u0 com.android.mms/.service.SwitchedService}
,11-17 18:31:18.755  4579  4630 E Babel   : canonicalizeMccMnc: invalid mccmnc 
11-17 18:31:18.755  4579  4630 I Babel   : MmsConfig.loadFromResources
11-17 18:31:18.756  4579  4630 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
11-17 18:31:18.757  4579  4630 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,11-17 18:31:18.758  2346  4575 I Icing   : Internal init done: storage state 0
11-17 18:31:18.774  4579  4579 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 18:31:18.778  4579  4628 W AudioCapabilities: Unsupported mime audio/evrc
11-17 18:31:18.790  4579  4628 W AudioCapabilities: Unsupported mime audio/qcelp
,11-17 18:31:18.800  4579  4628 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,11-17 18:31:18.804  2346  4575 I Icing   : Post-init done
11-17 18:31:18.823  4579  4628 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
11-17 18:31:18.825  4579  4628 W AudioCapabilities: Unsupported mime audio/qcelp
,11-17 18:31:18.831  4579  4628 W AudioCapabilities: Unsupported mime audio/evrc
11-17 18:31:18.834  4579  4579 V Babel   : babel boot account: SMS
11-17 18:31:18.834  4579  4579 V Babel   : babel boot account: thalitester@gmail.com
11-17 18:31:18.846  4579  4628 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,11-17 18:31:18.848  4579  4628 W VideoCapabilities: Unsupported mime video/divx
11-17 18:31:18.860  4579  4628 W VideoCapabilities: Unsupported mime video/divx311
,11-17 18:31:18.862  4579  4628 W VideoCapabilities: Unsupported mime video/divx4
11-17 18:31:18.874  4579  4628 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,11-17 18:31:18.881  1031  1758 I ActivityManager: Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.lgodm.LGODMReceiver: pid=4636 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
11-17 18:31:18.882  1031  1758 I ActivityManager: Killing 4041:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
11-17 18:31:18.910  4579  4628 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,11-17 18:31:18.915  4579  4628 W AudioCapabilities: Unsupported mime audio/eac3
11-17 18:31:18.917  4579  4628 W AudioCapabilities: Unsupported mime audio/ac3
11-17 18:31:18.918  4579  4628 W AudioCapabilities: Unsupported mime audio/g726
11-17 18:31:18.919  4579  4628 W AudioCapabilities: Unsupported mime audio/wma-voice
11-17 18:31:18.920  4579  4628 W AudioCapabilities: Unsupported mime audio/x-ms-wma
11-17 18:31:18.921  4579  4628 W AudioCapabilities: Unsupported mime audio/adpcm
11-17 18:31:18.924  4579  4628 W VideoCapabilities: Unsupported mime video/theora
,11-17 18:31:18.926  4579  4628 W VideoCapabilities: Unsupported mime video/mjpg
11-17 18:31:18.984   321   433 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,11-17 18:31:19.041  1031  1759 W libprocessgroup: failed to open /acct/uid_1000/pid_4041/cgroup.procs: No such file or directory
,11-17 18:31:19.048  1031  1375 V AlarmManager: ELAPSED_WAKEUP set : Alarm{36db57cf type 2 when 49955 com.google.android.talk} when 49955
11-17 18:31:19.051  1031  2085 I ActivityManager: Killing 4076:com.lge.email/u0a23 (adj 15): empty #17
11-17 18:31:19.065  4636  4636 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:31:19.148  1031  2085 I ActivityManager: Killing 3651:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,11-17 18:31:19.253  1868  1868 V LGSC    : [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,11-17 18:31:19.333  1031  1704 I ActivityManager: Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4655 uid=10073 gids={50073, 9997} abi=armeabi-v7a
,11-17 18:31:19.340  1031  1990 W libprocessgroup: failed to open /acct/uid_10023/pid_4076/cgroup.procs: No such file or directory
11-17 18:31:19.345  1031  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_3651/cgroup.procs: No such file or directory
11-17 18:31:19.351  1031  1375 V AlarmManager: ELAPSED_WAKEUP set : Alarm{293fa55c type 2 when 50259 com.google.android.talk} when 50259
,11-17 18:31:19.364   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.161ms total 30.573ms
,11-17 18:31:19.387   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 675us total 22.326ms
11-17 18:31:19.408   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 508us total 20.138ms
,11-17 18:31:19.426  4655  4655 I InsertAccount: The account already exists
,11-17 18:31:19.471  1031  2080 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4674 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
11-17 18:31:19.471  1031  2080 I ActivityManager: Killing 4159:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,11-17 18:31:19.562  1031  1758 W libprocessgroup: failed to open /acct/uid_10080/pid_4159/cgroup.procs: No such file or directory
,11-17 18:31:19.593  4655  4673 I InsertAccount: The account info in contact DB already exists
,11-17 18:31:19.617  4674  4674 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:31:19.648  4674  4674 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] ACTION_BOOT_COMPLETED : reset connected device information
,11-17 18:31:19.681  1031  1758 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4692 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,11-17 18:31:19.737  1031  2061 I ActivityManager: Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4712 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,11-17 18:31:19.744  1031  2080 I ActivityManager: Killing 4207:com.android.settings/1000 (adj 15): empty #17
11-17 18:31:19.799  1031  2080 I ActivityManager: Killing 4133:com.lge.lifetracker/u0a37 (adj 15): empty #18
,11-17 18:31:19.876  1031  1430 W libprocessgroup: failed to open /acct/uid_1000/pid_4207/cgroup.procs: No such file or directory
,11-17 18:31:19.900  1031  1704 W libprocessgroup: failed to open /acct/uid_10037/pid_4133/cgroup.procs: No such file or directory
,11-17 18:31:19.911  4692  4692 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
11-17 18:31:19.928  4712  4712 D TARGETVALIDLATION_RECEIVER: TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
11-17 18:31:19.928  4712  4712 D TARGETVALIDLATION_RECEIVER: updateFlag = new File(TARGET_FLAG_PATH)
,11-17 18:31:19.928  4712  4712 D TARGETVALIDLATION_RECEIVER: Do Not display result dialog. it is not used Update Tool!!
11-17 18:31:19.957  4692  4692 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@28e07b31
,11-17 18:31:19.984  1031  2024 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4729 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
11-17 18:31:19.985  1031  2024 I ActivityManager: Killing 4246:com.lge.voicerecorder/u0a42 (adj 15): empty #17
,11-17 18:31:20.030  1031  1759 W libprocessgroup: failed to open /acct/uid_10042/pid_4246/cgroup.procs: No such file or directory
,11-17 18:31:20.032  4692  4692 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
11-17 18:31:20.037  4692  4692 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@229eb9a2(com.android.providers.calendar.CalendarProvider2@28e07b31)
11-17 18:31:20.050  4655  4673 I InsertAccount: The account info in calendar DB already exists
,11-17 18:31:20.057  4655  4673 I Process : Sending signal. PID: 4655 SIG: 9
11-17 18:31:20.079  4729  4729 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,11-17 18:31:20.109  1031  1990 I ActivityManager: Process com.lge.defaultaccount (pid 4655) has died
,11-17 18:31:20.113  4729  4729 I LockScreenSettings: Received Broadcast : android.intent.action.BOOT_COMPLETED
11-17 18:31:20.126  2227  2227 V LGSC    : [104] 401
,11-17 18:31:20.205  1031  1430 I ActivityManager: Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4754 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
11-17 18:31:20.207  1031  1703 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,11-17 18:31:20.324  4754  4754 D BootCompleteReceiver: hasclipTray = true
11-17 18:31:20.328  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2586 
,11-17 18:31:20.401  1031  1430 I ActivityManager: Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4777 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,11-17 18:31:20.404  1031  2560 I ActivityManager: Killing 4293:com.android.managedprovisioning/u0a43 (adj 15): empty #17
11-17 18:31:20.450  1031  2560 V SIM_STK : Menu title from STK is T-Mobile
,11-17 18:31:20.450  1031  2560 V SIM_STK : Menu title from STK is T-Mobile
11-17 18:31:20.453  1031  1704 W libprocessgroup: failed to open /acct/uid_10043/pid_4293/cgroup.procs: No such file or directory
11-17 18:31:20.457  1031  1972 V SIM_STK : Menu title from STK is T-Mobile
11-17 18:31:20.466  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
11-17 18:31:20.466  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
,11-17 18:31:20.504  1031  1430 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=4795 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:31:20.518  4777  4777 V AppCleanupService: registerAlarm
,11-17 18:31:20.557  4777  4777 D AppCleanupService: noticeInterval = 2591999994
11-17 18:31:20.557  4777  4777 D AppCleanupService: notiDateStr = 2015-11-24 08:57:26
11-17 18:31:20.560  4777  4777 D AppCleanupService: noticeStart = 2015-11-24 08:57:26
11-17 18:31:20.560  4777  4777 D AppCleanupService: noticeStart = 1448351846000
11-17 18:31:20.584  4795  4795 I art     : Almond Protected OAT
,11-17 18:31:20.586  4777  4777 D AppUsageDbAdapter: initPreloadedAppToTheDB() : row count = 90
11-17 18:31:20.636  4795  4795 D WeatherApplication: removeAccount
,11-17 18:31:20.638  4795  4795 D WeatherApplication: Account.length = 0
11-17 18:31:20.638  4795  4795 E WeatherApplication: OPERATOR:OPEN
11-17 18:31:20.644  4795  4795 D WeatherAncestor: 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:31:20
11-17 18:31:20.647  4795  4795 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
11-17 18:31:20.647  4795  4795 D Weather.Utils: 2 : All the weather widget is gone.
11-17 18:31:20.649  4795  4795 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,11-17 18:31:20.668  4795  4795 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,11-17 18:31:20.686  4795  4795 D ForecastDataCache: 2 : lastUpdatedTime: 1430558561343
,11-17 18:31:20.686  4795  4795 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
11-17 18:31:20.686  4795  4795 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,11-17 18:31:20.712  4795  4795 D Weather_cast: 2 : set auto-update time : 11/17 21:31
,11-17 18:31:20.713  4795  4795 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:31:20
,11-17 18:31:20.771  1031  2061 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4821 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
11-17 18:31:20.774  1031  2061 I ActivityManager: Killing 4342:com.google.android.partnersetup/u0a8 (adj 15): empty #17
11-17 18:31:20.813  1031  1046 W libprocessgroup: failed to open /acct/uid_10008/pid_4342/cgroup.procs: No such file or directory
,11-17 18:31:20.869  4821  4821 D SIMObserver: action:android.intent.action.BOOT_COMPLETED
11-17 18:31:20.869  4821  4821 D SIMObserver: handle ACTION_BOOT_COMPLETED
,11-17 18:31:20.925  4821  4821 D LgDataFeature: LgDataFeature() Constructor: none
,11-17 18:31:20.925  4821  4821 D LgDataFeature: LgDataFeature() Constructor Done, null
11-17 18:31:20.971  1031  1990 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=4841 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:31:20.973  1031  1990 I ActivityManager: Killing 4101:com.lge.formmanager/u0a26 (adj 15): empty #17
11-17 18:31:21.029  1031  1703 W libprocessgroup: failed to open /acct/uid_10026/pid_4101/cgroup.procs: No such file or directory
,11-17 18:31:21.301  4841  4858 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:31:21.301  4841  4858 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:31:21.354  4841  4858 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,11-17 18:31:21.441  2134  2150 I art     : Explicit concurrent mark sweep GC freed 30786(1842KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 698us total 50.412ms
,11-17 18:31:21.458  4841  4858 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/app/YouTube/YouTube.apk"],nativeLibraryDirectories=[/system/app/YouTube/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,11-17 18:31:21.459  4841  4858 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:31:21.520   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
11-17 18:31:21.520   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
11-17 18:31:21.520   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,11-17 18:31:21.521  4841  4841 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
11-17 18:31:21.597  4841  4841 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:21.597  4841  4841 D LgDataFeature: LgDataFeature() Constructor Done, null
11-17 18:31:21.598  4409  4420 W CursorWrapperInner: Cursor finalized without prior close()
,11-17 18:31:21.665  1468  1468 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
11-17 18:31:21.665  1468  1468 I [SystemUI]LGPowerUI: On Skip Timer : true
,11-17 18:31:21.802  1031  2061 I ActivityManager: Killing 4409:com.lge.cloudhub/u0a58 (adj 15): empty #17
,11-17 18:31:21.862  1031  1704 W libprocessgroup: failed to open /acct/uid_10058/pid_4409/cgroup.procs: No such file or directory
,11-17 18:31:21.917  4841  4841 E YouTube : apps.youtube.app.YouTubeApplication.e:196 YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-17 18:31:22.130  1031  1972 I art     : Explicit concurrent mark sweep GC freed 13842(695KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.526ms total 130.854ms
,11-17 18:31:22.193  1031  2560 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,11-17 18:31:22.224   308  4885 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,11-17 18:31:22.226  1031  1105 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
11-17 18:31:22.228  4841  4880 E GoogleConversionPing: Error sending ping
11-17 18:31:22.232   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
11-17 18:31:22.232   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
11-17 18:31:22.232   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:31:22.233  4841  4841 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
11-17 18:31:22.235   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
11-17 18:31:22.235   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
11-17 18:31:22.235   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
,11-17 18:31:22.239  4841  4841 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
11-17 18:31:22.241   278   376 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
11-17 18:31:22.241   278   376 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
11-17 18:31:22.241   278   376 W Vold    : Returning OperationFailed - no handler for errno 0
11-17 18:31:22.243  4841  4841 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
11-17 18:31:22.311  3227  3227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2586 
,11-17 18:31:22.312  3227  3227 E AtFwd AutoBoot: AtFwd Auto Boot Started Successfully
11-17 18:31:22.396  1991  1991 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:2586 
,11-17 18:31:22.402  1991  4910 D SecUISvc: Thread created.
11-17 18:31:22.403  1991  1991 D SecUISvc: Service started flags 0 startId 1
11-17 18:31:22.404  2414  2414 D QcrilMsgTunnelAutoboot: ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
11-17 18:31:22.448  1031  1704 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4913 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,11-17 18:31:22.454  1991  4910 D SecUISvc.WfdReceiver: WfdReceiver(), wfdActive=true
11-17 18:31:22.454  1991  4910 D SecUISvc.WfdReceiver: Creating service, binding to WFD
11-17 18:31:22.455  1991  4910 D SecUISvc.WfdReceiver: service: ComponentInfo{com.qualcomm.wfd.service/com.qualcomm.wfd.service.WfdService}
11-17 18:31:22.456  1991  4910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.qualcomm.qti.services.secureui.WfdReceiver.<init>:48 com.qualcomm.qti.services.secureui.SecureUIService.run:95 java.lang.Thread.run:818 
11-17 18:31:22.505  1031  1972 I ActivityManager: Start proc com.qualcomm.wfd.service:wfd_service for service com.qualcomm.wfd.service/.WfdService: pid=4930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
11-17 18:31:22.506  1991  4910 D SecUISvc.WfdReceiver: WfdService binding has started
,11-17 18:31:22.517  1031  1759 I ActivityManager: Killing 4447:com.google.android.configupdater/u0a59 (adj 15): empty #17
11-17 18:31:22.529   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 21.125ms
,11-17 18:31:22.549   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 20.208ms
,11-17 18:31:22.561  1991  4910 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:22.561  1991  4910 D LgDataFeature: LgDataFeature() Constructor Done, null
,11-17 18:31:22.568   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 18.484ms
,11-17 18:31:22.598  1031  1704 W libprocessgroup: failed to open /acct/uid_10059/pid_4447/cgroup.procs: No such file or directory
11-17 18:31:22.646  4930  4930 D WfdService: onBind()
11-17 18:31:22.647  4930  4930 D WfdService: Creating SessionManagerService with context:android.app.Application@6039216
,11-17 18:31:22.656  4930  4930 D SessionManagerService: SessionManagerService ctor
11-17 18:31:22.678  4930  4930 D SessionManagerService: Reinitializing callback list
11-17 18:31:22.679  4930  4930 D SessionManagerService: Reinitializing HID callback list
,11-17 18:31:22.683  4930  4930 D SessionManagerService: WFD_CmdHdlr setup successfully
11-17 18:31:22.684  4930  4930 D SessionManagerService: teardown()
11-17 18:31:22.684  4930  4930 D SessionManagerService: Teardown session, broadcast intents first
11-17 18:31:22.684  4930  4930 D SessionManagerService: broadcastWifiDisplayAudioIntent() - flag: false
11-17 18:31:22.684  4930  4930 E SessionManagerService: Calling Audio System Proxy disable
11-17 18:31:22.686   312   312 V AudioPolicyManager: setDeviceConnectionState() device: 2000000, state 0, address 
11-17 18:31:22.686   312   312 W AudioPolicyManager: setDeviceConnectionState() device not connected: 2000000
11-17 18:31:22.686  4930  4930 D SessionManagerService: broadcastWifiDisplayVideoEnabled() - flag: false
11-17 18:31:22.687  4930  4930 D SessionManagerService: Broadcasting WFD video intent: Intent { act=org.codeaurora.intent.action.WIFI_DISPLAY_VIDEO (has extras) }
11-17 18:31:22.687  4930  4930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.qualcomm.wfd.service.SessionManagerService.broadcastWifiDisplayVideoEnabled:1221 com.qualcomm.wfd.service.SessionManagerService.teardown:1053 com.qualcomm.wfd.service.SessionManagerService.<init>:159 
11-17 18:31:22.688  4930  4930 D SessionManagerService: No session in progress
11-17 18:31:22.690  4930  4930 D SessionManagerService: Cleanup any existing sessions. ret: 0
,11-17 18:31:22.697  4930  4930 D WFDNative: try to load libwfdrtsp.so
11-17 18:31:22.783  4930  4930 D WFDNative: libwfdrtsp.so loaded.
,11-17 18:31:22.783  4930  4930 D WFDNative: try to load libwfdnative.so
11-17 18:31:22.791  4930  4930 W linker  : libaudioeffectsole.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
11-17 18:31:22.820  4913  4913 V [BNRBootReceiver]: boot receiver action = android.intent.action.BOOT_COMPLETED
,11-17 18:31:22.822  4913  4913 V [BNRBootReceiver]: set property sys.lge.bnrd = 1
11-17 18:31:22.823  4913  4913 V [BNRBootReceiver]: End of BootComplted IF
11-17 18:31:22.824  4913  4913 V [BNRBootReceiver]: Boot Receiver Return
11-17 18:31:22.829  4692  4692 D CalendarReceiver: [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
11-17 18:31:22.830  4913  4949 V [BNRBootCompletedThread]: run
11-17 18:31:22.830  4692  4692 D CalendarReceiver: [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
11-17 18:31:22.831  4692  4692 D CalendarReceiver: [onReceive] WakeLock acquire : CalendarReceiver_Provider
11-17 18:31:22.833  4692  4951 D CalendarReceiver: [onReceive] android.intent.action.BOOT_COMPLETED
11-17 18:31:22.834  4692  4951 D CalendarProvider2: Scheduling check of next Alarm
,11-17 18:31:22.838  4692  4951 D CalendarProvider2: SCHEDULE_ALARM_REMOVE
11-17 18:31:22.842  4692  4951 D CalendarReceiver: [onReceive] WakeLock release : CalendarReceiver_Provider
11-17 18:31:22.843  4509  4545 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
11-17 18:31:22.870  4913  4949 V [BNRBootCompletedThread]: End of BNRProcess
,11-17 18:31:22.875  4913  4949 V [BNRBootCompletedThread]: End of BNRViaWifiProcess
11-17 18:31:22.879  1031  1990 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4955 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
11-17 18:31:22.882  4913  4949 V [BNRBootCompletedThread]: End of SpriteProcess
11-17 18:31:22.883  4913  4949 V [BNRBootCompletedThread]: exit
,11-17 18:31:22.896  4930  4930 E WFDNative_CPP: JNI_OnLoad called
,11-17 18:31:22.897  4930  4930 E WFDNative_CPP: Unable to find field 
11-17 18:31:22.898  4930  4930 E WFDNative_CPP: Unable to find field 
11-17 18:31:22.898  4930  4930 E UIBCManager: HID payload is null, ignore callback
11-17 18:31:22.898  4930  4930 E UIBCManager: HIDCListener is null, ignore callback
11-17 18:31:22.898  4930  4930 D WFDNative: libwfdnative.so loaded.
11-17 18:31:22.898  4930  4930 D WFDNative: eventCallback triggered
11-17 18:31:22.898  4930  4930 D WFDNative: No event info, ignore.
11-17 18:31:22.900  1991  1991 D SecUISvc.WfdReceiver: Connection object created
11-17 18:31:22.900  4930  4930 D SessionManagerService: Received intent: #Intent;action=android.intent.action.HDMI_PLUGGED;launchFlags=0x44000010;B.state=false;end
11-17 18:31:22.903  4930  4946 D SessionManagerService: init()
11-17 18:31:22.903  4930  4946 E SessionManagerService: listener != null
11-17 18:31:22.903  4930  4946 E SessionManagerService: WfdDevice arg can not be null
,11-17 18:31:22.953  4955  4955 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:31:22.986   321   433 E ThermalEngine: [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,11-17 18:31:23.014  4955  4955 D CalendarApplication: CalendarApplication.onCreate()
,11-17 18:31:23.039  4955  4955 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,11-17 18:31:23.040  4955  4955 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@390c1797, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@f203d84, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1b90996d, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@229eb9a2, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@f709633, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3f25adf0, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@15aa5f69, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@16d2cdee, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2694628f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2ccfb91c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@26808925, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@621dafa, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@47e98ab, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3bad4b08, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@5d592a1, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1822acc6, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3e8c1487, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@37500fb4, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@b17b7dd, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@50ccf52, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@390b7223, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@30b87320, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1c5cf4d9, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1f048e9e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@4990d7f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@681a14c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@111f0595, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2426f6aa, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@353b029b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3cd8638, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@4b76611, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2555d376, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@f3d2d77, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1f0cde4, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@149b524d, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@dc3b102, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@25cd2a13, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@38dee450, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@657c649, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@173fdb4e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@756546f, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2a,55f57c, lg_p
11-17 18:31:23.044  1031  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
11-17 18:31:23.044  1031  1990 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
11-17 18:31:23.045  1031  1107 D BluetoothManagerService: Message: 2
11-17 18:31:23.051  4955  4955 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
11-17 18:31:23.054  1031  1399 D WifiService: New client listening to asynchronous messages
11-17 18:31:23.056  1031  1703 D WifiServiceImplEx: setWifiEnabled: false pid=4390, uid=10318, package= com.example.hello, App Lable : HelloWorld
11-17 18:31:23.056  1031  1703 D WifiService: setWifiEnabled: false pid=4390, uid=10318
11-17 18:31:23.056  1031  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:31:23.058  4390  4390 I jxcore-log: ****TEST TOOK:  5038  ms ****
11-17 18:31:23.058  4390  4390 I jxcore-log: 
11-17 18:31:23.058  4390  4390 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:31:23.058  4390  4390 I jxcore-log: 
11-17 18:31:23.066  4955  4955 D Config  : [init]
11-17 18:31:23.067  4955  4955 I Config  : LGCalendar ver.4.40.16
11-17 18:31:23.067  4955  4955 I Config  : start check model
11-17 18:31:23.067  4955  4955 I Config  : start check native_ca
11-17 18:31:23.068  4955  4955 I Config  : Config Operator=OPEN, Country=EU
11-17 18:31:23.069  4955  4955 D Config  : [setDefaultValuesToPref]
11-17 18:31:23.069  4955  4955 D Config  : [parseProfiles]
11-17 18:31:23.074  4955  4955 D ProfilesParser: [debug_displayParseInfos] profile.country = null
11-17 18:31:23.074  4955  4955 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
11-17 18:31:23.074  4955  4955 D Config  : [updateProfiletoCountryInfo]
11-17 18:31:23.075  4955  4955 D GeneralPreference: [checkAndMigrateOldPreference]
11-17 18:31:23.083  4955  4955 D AlertReceiver: onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
,11-17 18:31:23.092  4955  4982 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
11-17 18:31:23.098  4955  4982 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,11-17 18:31:23.141  1031  1430 I ActivityManager: Start proc com.nuance.voicemate for broadcast com.nuance.voicemate/com.nuance.androidcore.manifest.receivers.UploadServiceBootStart: pid=4983 uid=10117 gids={50117, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi
,11-17 18:31:23.165  4955  4982 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,11-17 18:31:23.172  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
11-17 18:31:23.176  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,11-17 18:31:23.183  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
11-17 18:31:23.188  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
11-17 18:31:23.200  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,11-17 18:31:23.206  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
11-17 18:31:23.210  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
11-17 18:31:23.215  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,11-17 18:31:23.220  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
11-17 18:31:23.224  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
11-17 18:31:23.228  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,11-17 18:31:23.234  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
11-17 18:31:23.237  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
11-17 18:31:23.243  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,11-17 18:31:23.247  4955  4982 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
11-17 18:31:23.247  4955  4982 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
11-17 18:31:23.250  4955  4982 I AlertUtils: set default noti to content://media/internal/audio/media/41
11-17 18:31:23.263  4955  4982 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,11-17 18:31:23.273  4955  5005 W HolidayIntentService: onHandleIntent
11-17 18:31:23.274  4955  5005 D HolidayDataLoader: readJsonAsset : holiday.json
,11-17 18:31:23.292  4955  5006 D AlertService: 0 Action = android.intent.action.BOOT_COMPLETED
,11-17 18:31:23.309  4955  5006 D AlertService: [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
11-17 18:31:23.310  4955  5006 D Feature : MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
11-17 18:31:23.329  4955  5006 D AlertService: [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
11-17 18:31:23.331  4955  5005 E HolidayIntentService: onHandleIntent:holiday data empty
,11-17 18:31:23.332  4955  5006 D AlertService: [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
11-17 18:31:23.337  4955  5006 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
11-17 18:31:23.347  4955  5006 D AlarmScheduler: No events found starting within 1 week.
,11-17 18:31:23.416  5000  5000 D AndroidRuntime: 
11-17 18:31:23.416  5000  5000 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:31:23.422  5000  5000 D AndroidRuntime: CheckJNI is OFF
11-17 18:31:23.484  4983  4983 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:23.484  4983  4983 D LgDataFeature: LgDataFeature() Constructor Done, null
,11-17 18:31:23.508  4821  4836 I LicenseContentProvider: start selecting data
11-17 18:31:23.509  4821  4836 D EULA::SimManager: SimManager getInstance.
11-17 18:31:23.511  4821  4836 I EULA::SimManager: LGMSimTelephonyManager will be used!
11-17 18:31:23.511  4821  4836 I EULA::SimManager: sSimInstance : com.lge.telephony.msim.LGMSimTelephonyManager@6039216
11-17 18:31:23.512  4821  4836 I EULA::SimManager: sIsMultiSimEnabled : false
11-17 18:31:23.512  4821  4836 I EULA::SimManager: sSIMCount : 1
11-17 18:31:23.512  4821  4836 I EULA::SimManager: LGMSimTelephonyManager will be used!
11-17 18:31:23.512  4821  4836 I EULA::SimManager: sSimInstance : com.lge.telephony.msim.LGMSimTelephonyManager@6039216
11-17 18:31:23.512  4821  4836 I EULA::SimManager: sIsMultiSimEnabled : false
11-17 18:31:23.512  4821  4836 I EULA::SimManager: sSIMCount : 1
11-17 18:31:23.514  4821  4836 D SIMObserver: simInfo1
11-17 18:31:23.587  1031  1703 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=5021 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:31:23.592  1031  2560 I ActivityManager: Killing 4489:com.lge.drmservice/u0a62 (adj 15): empty #17
11-17 18:31:23.622  5000  5000 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:31:23.633  1031  2024 W libprocessgroup: failed to open /acct/uid_10062/pid_4489/cgroup.procs: No such file or directory
,11-17 18:31:23.672  1031  1122 W PackageSettings: Skipping PackageSetting{30fe5b68 com.test.thalitest/10311} due to missing metadata
,11-17 18:31:23.695  1031  1088 I ActivityManager: Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
11-17 18:31:23.696  1031  1088 I ActivityManager: Killing 4390:com.example.hello/u0a318 (adj 0): stop com.example.hello
11-17 18:31:23.749  1031  2024 I WindowState: WIN DEATH: Window{2d485758 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:31:23.750  1031  1399 D WifiService: Client connection lost with reason: 4
,11-17 18:31:23.754  1031  2024 D InputDispatcher: Window went away: Window{2d485758 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:31:23.842  4692  4692 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,11-17 18:31:23.843  4692  4692 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
11-17 18:31:23.850  1031  1088 W ActivityManager: Force removing ActivityRecord{427aaf1 u0 com.example.hello/.MainActivity t2}: app died, no saved state
11-17 18:31:23.851  1031  1088 D SplitWindowManager: removeStackAndNeedHomeResume ActivityStack{3daf7695 stackId=1, 0 tasks}
,11-17 18:31:23.865   337   352 E GBMv2   : DFP En is all cleared set to be enabled
,11-17 18:31:23.866  1031  1122 I ActivityManager: Force stopping com.example.hello appid=10318 user=0: pkg removed
11-17 18:31:23.890  1031  1703 W ActivityManager: Spurious death for ProcessRecord{61513aa 4390:com.example.hello/u0a318}, curProc for 4390: null
,11-17 18:31:23.894  2090  2090 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
11-17 18:31:23.895  2090  2090 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
11-17 18:31:23.898  1973  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
11-17 18:31:23.899  1973  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3614784b co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
11-17 18:31:23.904  1973  4386 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
11-17 18:31:23.905  1973  4386 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18604228 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
,11-17 18:31:23.909  1468  1468 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
11-17 18:31:23.917  1031  1377 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:31:23.923  2044  2044 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
11-17 18:31:23.927  1833  2475 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 18:31:23.932  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,11-17 18:31:23.934  1929  1929 D ActionManagerService: notifyUserLog: 1000003
11-17 18:31:23.934  3566  4193 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
11-17 18:31:23.936  3566  3566 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
11-17 18:31:23.938  2090  2090 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
11-17 18:31:23.939  2090  2090 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
11-17 18:31:23.941  1468  1468 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
11-17 18:31:23.960  2090  5044 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,11-17 18:31:23.973  4271  4271 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.example.hello
11-17 18:31:23.974  1468  1575 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:31:23.974  1468  1575 D KeyguardModel: createShortcutInfo...
11-17 18:31:23.975  4271  4271 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
11-17 18:31:23.975  4271  4271 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
11-17 18:31:23.975  4271  4271 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
11-17 18:31:23.975  4271  4271 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:31:23.975  4271  4271 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:31:23.975  4271  4271 W System.err: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:31:23.975  4271  4271 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
11-17 18:31:23.976  4271  4271 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:31:23.976  4271  4271 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:31:23.976  4271  4271 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
11-17 18:31:23.976  4271  4271 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
11-17 18:31:23.980  1468  1468 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
11-17 18:31:23.980  1468  1468 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
11-17 18:31:23.981  1468  1575 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:31:23.981  1468  1575 D KeyguardModel: createShortcutInfo...
,11-17 18:31:23.983  1031  1031 D administrator: Handling package changes for user 0
11-17 18:31:23.996  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
11-17 18:31:23.997  1468  1575 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:31:23.997  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
11-17 18:31:23.998  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,11-17 18:31:24.006  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:31:24.007  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
11-17 18:31:24.009  1468  1575 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:31:24.009  1468  1575 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:31:24.012  1468  1575 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:31:24.012  1468  1575 D KeyguardModel: createShortcutInfo...
,11-17 18:31:24.024  1031  1972 V SIM_STK : Menu title from STK is T-Mobile
11-17 18:31:24.047  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
11-17 18:31:24.048  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:31:24.049  1468  1575 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:31:24.049  1468  1575 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:31:24.060  1468  1575 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:31:24.060  1468  1575 D KeyguardModel: createShortcutInfo...
11-17 18:31:24.066  1468  1575 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:31:24.066  1468  1575 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:31:24.067  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,11-17 18:31:24.067  1468  1575 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
11-17 18:31:24.071  1468  1575 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:31:24.071  1468  1575 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:31:24.072  1885  1885 D SplitUIManager: split_name #11 / not available #0
11-17 18:31:24.073  1885  1885 D SplitUIService: removed split : 
11-17 18:31:24.087  1468  1575 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:31:24.087  1468  1575 D KeyguardModel: createShortcutInfo...
,11-17 18:31:24.094  1468  1468 D KeyguardModel: handleShortcutListChanged...
11-17 18:31:24.097  1468  1575 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:31:24.097  1468  1575 D KeyguardModel: createShortcutInfo...
11-17 18:31:24.108  1031  1117 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=30000 (25039 ms ago)
,11-17 18:31:24.130  1468  1575 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:31:24.130  1468  1575 D KeyguardModel: createShortcutInfo...
,11-17 18:31:24.134  1468  1575 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:31:24.134  1468  1575 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:31:24.137  1468  1575 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:31:24.137  1468  1575 D KeyguardModel: createShortcutInfo...
11-17 18:31:24.141  1468  1575 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:31:24.141  1468  1575 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:31:24.146  1885  1885 D SplitUIManager: split_name #11 / not available #0
11-17 18:31:24.147  1885  1885 I SplitUIService: split app #11
11-17 18:31:24.148  1468  1575 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,11-17 18:31:24.148  1468  1575 D KeyguardModel: createShortcutInfo...
11-17 18:31:24.150  1468  1575 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:31:24.150  1468  1575 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:31:24.159  1468  1575 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:31:24.159  1468  1575 D KeyguardModel: createShortcutInfo...
,11-17 18:31:24.166  1031  1703 I ActivityManager: Killing 4509:com.google.android.gm/u0a64 (adj 15): empty #17
11-17 18:31:24.191  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,11-17 18:31:24.192  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:31:24.192  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:31:24.201  2090  2090 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b4b1e12 time:55132
11-17 18:31:24.210  1031  1106 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,11-17 18:31:24.210  1031  1106 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:31:24.211  1031  1106 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:31:24.211  1031  1106 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:31:24.211  1031  1106 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2be92f9e,  pkg=WindowManager.LayoutParams
11-17 18:31:24.211  1031  1106 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:31:24.220  1031  1990 V SIM_STK : Menu title from STK is T-Mobile
11-17 18:31:24.246  1031  1122 I art     : Explicit concurrent mark sweep GC freed 17239(1199KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.537ms total 354.125ms
,11-17 18:31:24.273  5000  5000 D AndroidRuntime: Shutting down VM
,11-17 18:31:24.290  1031  2085 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
11-17 18:31:24.290  1468  1468 D KeyguardModel: handleShortcutListChanged...
,11-17 18:31:24.291  1468  1468 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
11-17 18:31:24.293  1468  1468 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
11-17 18:31:24.293  1468  1468 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:31:24.293  1468  1468 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:31:24.293  1031  1047 W libprocessgroup: failed to open /acct/uid_10064/pid_4509/cgroup.procs: No such file or directory
11-17 18:31:24.300  1031  1375 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2c190ff8 type 2 when 49736 com.google.android.talk} when 49736
11-17 18:31:24.300  1031  1432 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
11-17 18:31:24.300  1031  1375 V AlarmManager: RTC_WAKEUP set : Alarm{3b598cd1 type 0 when 1447781484208 com.lge.ia.task.mrgdblogger} when 1447781484208
11-17 18:31:24.303  1031  1375 V AlarmManager: RTC_WAKEUP set : Alarm{88e9237 type 0 when 1447781484249 com.google.android.gms} when 1447781484249
,11-17 18:31:24.323  1031  1046 W ActivityManager: getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,11-17 18:31:24.327  3566  4182 D LIA_MrGDBLogger_LoggerThread: [dreamwood]App Usage Logging
11-17 18:31:24.378  2346  5056 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 69 ms
,11-17 18:31:24.379  5021  5021 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
11-17 18:31:24.437  5021  5021 D LgDataFeature: LgDataFeature() Constructor: none
11-17 18:31:24.437  5021  5021 D LgDataFeature: LgDataFeature() Constructor Done, null
,11-17 18:31:24.453  1031  1087 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:31:24.459  1031  1087 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
11-17 18:31:24.468  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,11-17 18:31:24.545  1031  1108 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{89c1de6 u0 com.lge.launcher2/.Launcher t1} time:55476
,11-17 18:31:24.575  5021  5021 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,11-17 18:31:24.649  1031  2024 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5077 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,11-17 18:31:24.682  5021  5021 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:31:24.683  5021  5021 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,11-17 18:31:24.926   279   798 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
```
