#### Test 50242285e132180_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/HwSystemManager( 3865): HoldService:uid:10040 pid:5250 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10040
I/HwSystemManager( 3865): HoldService:oldVersionKey:10040,5250
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10040, pid: 5250
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10040, pid: 5250
I/LibraryLoader( 5926): Loading: webviewchromium
I/LibraryLoader( 5926): Time to load native libraries: 3 ms (timestamps 2677-2680)
I/LibraryLoader( 5926): Expected native library version number "",actual native library version number ""
W/art     ( 5926): Attempt to remove local handle scope entry from IRT, ignoring
I/PG Utils( 5926): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5992): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/art     ( 5926): Attempt to remove local handle scope entry from IRT, ignoring
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 3865): HoldService:uid:10052 pid:5279 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10052,5279
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10052, pid: 5279
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10052, pid: 5279
W/System.err( 2985): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2985): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2985): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2985): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2985): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2985): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2985): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2985): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 5992): WifiServiceMessenger == null
W/Settings( 5992): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5992): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PG Utils( 5992): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5992): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10104
I/HwSystemManager( 3865): HoldService:uid:10104 pid:4874 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10104,4874
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10104, pid: 4874
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10104, pid: 4874
W/StubController( 6051): calendar access!
,I/PG Utils( 6051): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
W/StubController( 6076): calendar access!
W/StubController( 6051): calendar access!
I/PG Utils( 6051): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
W/StubController( 6051): calendar access!
I/CalendarSimpleUiPRovider( 6051): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6051): onConfigurationChanged
I/CalendarSimpleUiPRovider( 6051): initParams20151207T161144Europe/Warsaw(1,340,3600,0,1449501104)
W/StubController( 6051): calendar access!
E/        ( 2985): open /proc/4874/smaps fail errno 2
E/        ( 2985): open /proc/5218/smaps fail errno 2
E/        ( 2985): open /proc/5250/smaps fail errno 2
E/        ( 2985): open /proc/5279/smaps fail errno 2
W/StubController( 6051): calendar access!
I/HwSystemManager( 3865): HoldService:uid:1000 pid:5308 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3865): HoldService:oldVersionKey:1000,5308
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
W/MediaProcessHandler( 2985): processOp uid 1000 is not concerned!
W/StubController( 6051): calendar access!
I/ActivityManager( 2985): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
I/CalendarSimpleUiPRovider( 6051): loadEvent end update UI0
I/appproc ( 6097): CLASSPATH=/system/framework/am.jar
I/appproc ( 6097): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 6097): app_process:number,5,0
I/AndroidRuntime( 6097): readDownloadBoosterConfig: 'false'
I/HwCust  ( 6102): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
I/PG Utils( 6102): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 6102): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 6102): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6102): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/HwCust  ( 6102): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/PG Utils( 6102): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6102): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
E/ContactsProtector( 6102): getHiCloudAccountData query fail
I/PG Utils( 6102): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 3485): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6102): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
I/        ( 6097): power log dlsym ok
I/HwLauncher( 3655): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
I/HwLauncher( 3655): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
I/HwSystemManager( 3865): HoldService:uid:10050 pid:5331 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10050,5331
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10050
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10050, pid: 5331
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10050, pid: 5331
I/HwCust  ( 6102): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
E/android_hardware_fm.cpp( 6097): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6097): ========64bit long size = 8
E/FM_HAL  ( 6097): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6097): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6097): 
I/fm_hisi ( 6097): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6097): 
I/fm_hisi ( 6097): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6097): 
E/android_hardware_fm.cpp( 6097): register_android_hardware_fm_fmradio, ret is 0
I/HwLauncher( 3655): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3655): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3655): Model STK reName intent is received.
I/HwLauncher( 3655): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3655): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3655): Model STK reName intent is received.
I/HwLauncher( 3655): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3655): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwLauncher( 3655): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3655): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3655): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3655): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3655): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3655): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3655): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3655): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3655): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3655): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3655): Launcher.Folder childCount: 5
I/HwLauncher( 3655): Launcher.Folder childCount: 5
I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwLauncher( 3655): Launcher.Folder childCount: 6
I/HwLauncher( 3655): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3655): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwLauncher( 3655): Launcher.Folder childCount: 6
I/HwLauncher( 3655): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3655): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3655): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3655): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwLauncher( 3655): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3655):  syncPages mCurrentPage = 0
E/HideAppsPagedView( 3655):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3655):  createAddIcon count = 0
I/HwSystemManager( 3865): ContactsObserverHelper:Receive contacts change broadcast
I/HwLauncher( 3655):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/art     ( 2985): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2985): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2985): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2985): Can not find class: Lcom/android/server/wm/StartingData;
I/art     ( 2985): Can not find class: Landroid/widget/ViewStub;
I/HwLauncher( 3655): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/art     ( 2985): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 2985): Can not find class: Landroid/app/ViewStub;
I/HwLauncher( 3655): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3655): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3655): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3655): Model shortcutInfo.title = SIM Toolkit
I/art     ( 3655): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3655): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 3655): initAddtionalStyle default
I/HwLauncher( 3655): Launcher onPause()
I/HwLauncher( 3655): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3655): Launcher.MotionManager stopMotionAppsReco 403
W/HwLauncher( 3655): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3655): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/art     ( 2985): Explicit concurrent mark sweep GC freed 18439(1071KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.759ms total 188.972ms
I/HwEmailTag( 6149): MailAppProvider->onCreate->begin, consuming 1449501104797ms->-prefixstartupperformance-
I/HwEmailTag( 6149): MailAppProvider->onCreate->end, consuming 1449501104828ms->-prefixstartupperformance-
I/HwLauncher( 3655): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3655): Launcher.Folder childCount: 5
I/HwLauncher( 3655): Launcher.Folder childCount: 5
I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwCust  ( 6149): Constructor found for class com.android.email.service.HwCustImapServiceImpl
I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwLauncher( 3655): Launcher.Folder childCount: 6
I/HwLauncher( 3655): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwCust  ( 6149): Constructor found for class com.android.email.HwCustUtilityImpl
I/HwLauncher( 3655): Launcher.Folder childCount: 6
I/HwLauncher( 3655): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwLauncher( 3655): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3655):  syncPages mCurrentPage = 0
I/art     ( 2985): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwCust  ( 6149): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
I/HwCust  ( 6149): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
I/HwEmailTag( 6149): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6149): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6149): HwUtils->initStaticVarsAsync
I/HwEmailTag( 6149): HwUtils->initStaticVarsAsync
E/HideAppsPagedView( 3655):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3655):  createAddIcon count = 0
I/HwLauncher( 3655):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/HwCust  ( 6149): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
I/HwLauncher( 3655): Launcher onStop()
I/HwLauncher( 3655): Launcher dismissDialog
I/HwLauncher( 3655): Launcher dynamicIconsUnregister
I/HwLauncher( 3655): DynamicUpdater unregisterReceiver
I/HwEmailTag( 6149): EmailContent->init->consuming:13ms->;-prefixstartupperformance-
I/PhoneStatusBar( 3194): shouldTranslucent:true
I/PhoneStatusBar( 3194): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwEmailTag( 6149): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 6149): EmailProvider->INTEGRITY_CHECK_URI != null
I/HwEmailTag( 6149): EmailProvider->onCreate->end, consuming 26ms->-prefixstartupperformance-
I/HwLauncher( 3655): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3655): DynamicUpdater unregisterReceiver
I/HwSystemManager( 3865): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3865): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3655): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3655): DynamicUpdater unregisterReceiver
I/HwEmailTag( 6149): EmailProvider->onCreate->end, consuming 35ms->-prefixstartupperformance-
I/HwLauncher( 3655): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwEmailTag( 6149): EmailProvider->resetVisibleLimits->start:1449501104896 ->-prefixstartupperformance-
I/HwLauncher( 3655): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3655): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3655): Launcher Deferring update until onResume
I/HwCust  ( 6149): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
I/HwLauncher( 3655): Launcher  onWindowVisibilityChanged visibility = 8
I/HwEmailTag( 6149): EmailProvider->resetVisibleLimits->start:1449501104902 ->-prefixstartupperformance-
I/HwLauncher( 3655): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwEmailTag( 6149): HwUtils->initStaticVarsAsync->run:consuming:49ms; bidiFormatter:android.support.v4.text.BidiFormatter@15b50bdc;accountsProjSize:42
I/HwLauncher( 3655): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwEmailTag( 6149): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6149): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 26ms.
I/HwEmailTag( 6149): EmailApplication->onCreate->begin, consuming 68ms->-prefixstartupperformance-
I/HwEmailTag( 6149): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
I/HwCust  ( 6149): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
I/HwCust  ( 6149): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
I/HwEmailTag( 6149): EmailApplication->onCreate->end, consuming 74ms->-prefixstartupperformance-
I/HwEmailTag( 6149): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6149): HwUtils->initStaticVarsAsync->run:consuming:83ms; bidiFormatter:android.support.v4.text.BidiFormatter@15b50bdc;accountsProjSize:42
I/HwEmailTag( 6149): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwEmailTag( 6149): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
W/PGApi_client( 3545): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@6de13d3 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3545): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3545): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@2fb4fa74, action = com.huawei.pgmng.PGAction@6de13d3 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3545): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@6de13d3 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3545): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3545): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3545): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3545): return for smartPAOn and mLowAudioEffectEnable both = false
I/HwEmailTag( 6149): EmailProvider->initBuildCache->start->1449501104977->-prefixstartupperformance-
I/HwEmailTag( 6149): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 6149): EmailProvider->initBuildCache->start->1449501104977; consuming:2->-prefixstartupperformance-
I/HwEmailTag( 6149): EmailProvider->uiAccounts->start:1449501104979
I/HwEmailTag( 6149): EmailProvider->resetVisibleLimits->getDatabase, consuming:83ms;-prefixstartupperformance-
I/HwEmailTag( 6149): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 6149): DBHelper->onOpen-> EmailProvider.db
I/CalendarProvider2( 6076): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6076): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/HwEmailTag( 6149): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 14ms.
I/HwEmailTag( 6149): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6149): EmailProvider->resetVisibleLimits->getDatabase, consuming:124ms;-prefixstartupperformance-
I/HwEmailTag( 6149): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 6149): EmailProvider->uiAccounts->start:1449501104979;end,consuming:50
I/HwEmailTag( 6149): EmailProvider->query->1449501104895;end;;consuming:134ms;
I/WebViewFactory( 6180): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/ActivityManager( 2985): filter receiver for action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager( 2985): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwSystemManager( 3865): HoldService:uid:10056 pid:5368 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10056
I/HwSystemManager( 3865): HoldService:oldVersionKey:10056,5368
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10056, pid: 5368
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10056, pid: 5368
I/LibraryLoader( 6180): Loading: webviewchromium
I/LibraryLoader( 6180): Time to load native libraries: 4 ms (timestamps 4700-4704)
I/LibraryLoader( 6180): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6180): Expected native library version number "",actual native library version number ""
I/chromium( 6180): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6180): Initializing chromium process, renderers=0
W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6180): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6180): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6180): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6180): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
I/HwSystemManager( 3865): HoldService:uid:1000 pid:5394 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:1000,5394
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
W/MediaProcessHandler( 2985): processOp uid 1000 is not concerned!
W/chromium( 6180): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6180): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6180): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/HwCust  ( 6237): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
W/HWContacts( 6237): ProviderFeatureChcker - cootek package not installed
E/TmoMonitor( 6237): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@15b50bdc
I/HwCust  ( 6237): Constructor found for class com.android.mms.data.HwCustConversationImpl
I/EmuiFeatureManager( 6237): loadEmailAnrSupportFlag:true
I/Mms_threadcache( 6237): [RecipientIdCache] fill: begin
I/SimFactoryManager( 6237): Inside init method of SimFactoryManger the combination is:-1
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6237): isSIM1CardPresent:1
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:1
E/MmsConfig( 6237): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
I/SimFactoryManager( 6237): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6237): isSIM2CardPresent:1
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6237): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
I/HwCust  ( 6237): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
I/HwCust  ( 6237): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
I/art     ( 6237): Can not find class: Lhuawei/android/view/TableLayout;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/TableLayout;
I/art     ( 6237): Can not find class: Lhuawei/android/view/View;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6237): Can not find class: Landroid/widget/View;
I/art     ( 6237): Can not find class: Landroid/webkit/View;
I/art     ( 6237): Can not find class: Landroid/app/View;
I/art     ( 6237): Can not find class: Lhuawei/android/view/TableRow;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/TableRow;
I/HwCust  ( 6237): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
I/art     ( 6237): Can not find class: Lhuawei/android/view/LinearLayout;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/LinearLayout;
I/HwCust  ( 6237): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
I/art     ( 6237): Can not find class: Lhuawei/android/view/ImageButton;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/ImageButton;
I/art     ( 6237): Can not find class: Lhuawei/android/view/TextView;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/TextView;
W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6180): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 6237): Can not find class: Lhuawei/android/view/RelativeLayout;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/RelativeLayout;
I/art     ( 6180): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6180): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6180): Can not find class: Landroid/app/ViewStub;
I/art     ( 6237): Can not find class: Lhuawei/android/view/ImageView;
I/art     ( 6237): Can not find class: Lhuawei/android/widget/ImageView;
W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 6237): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 6237): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 6237): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 6237): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6237): Can not find class: Landroid/app/ViewStub;
,I/art     ( 6237): Can not find class: Lhuawei/android/view/FrameLayout;
,I/art     ( 6237): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 6237): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 6237): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 6237): initAddtionalStyle default
,I/art     ( 6237): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 6237): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6237): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/OpenGLRenderer( 6180): Initialized EGL, version 1.4
,I/art     ( 2985): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
,I/chromium( 6180): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6180): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager( 2985): Displayed com.example.hello/.MainActivity: +1s207ms
,I/HwSystemManager( 3865): HoldService:uid:10065 pid:5433 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3865): HoldService:oldVersionKey:10065,5433
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10065, pid: 5433
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10065, pid: 5433
,I/chromium( 6180): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6180): 
,I/art     ( 2985): Can not find class: Lcom/android/server/wm/DisplayContentList;
,I/HwSystemManager( 3865): HoldService:uid:1050 pid:5457 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:1050,5457
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 1050
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
W/MediaProcessHandler( 2985): processOp uid 1050 is not concerned!
,I/HwSystemManager( 3865): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 3865): NotificationManagerReceiver:onReceive, send action to background
I/HwSystemManager( 3865): ProcPolicy:begin get procName.
,I/HwSystemManager( 3865): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 3865): ProcPolicy:end get procName.
,I/HwSystemManager( 3865): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@25d866ff
,I/HwSystemManager( 3865): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3865): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3865): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
I/HwSystemManager( 3865): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
,I/HwSystemManager( 3865): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
,I/HwSystemManager( 3865): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 3865): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
,I/HwSystemManager( 3865): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/HwSystemManager( 3865): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3865): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3865): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3865): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3865): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3865): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3865): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3865): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 3865): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3865): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3865): HsmIntentService:last work complete! lets stop service.
I/PhoneStatusBar( 3194): notification pkg =com.android.settings
I/PhoneStatusBar( 3194): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3194): notification pkg =android
I/PhoneStatusBar( 3194): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,W/jxcore-log( 6180): Initializing JXcore engine
W/jxcore-log( 6180): JXcore engine is ready
,W/jxcore-log( 6180): Starting JXcore engine
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 422us total 22.338ms
,W/asset   ( 6324): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 412us total 21.223ms
,I/HwSystemManager( 3865): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@25d866ff
,I/HwSystemManager( 6324): SystemManagerApplication:onCreate
,I/HwSystemManager( 3865): MainService:on startCommand,flags:0,startId:6
,I/System.out( 6324): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 471us total 20.693ms
I/System.out( 6324): null
I/System.out( 6324): null
,I/System.out( 6324): Calling by::className:bkk  MethodName:yw
,I/HwSystemManager( 3865): LocalService:Received start id 6: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
,I/HwSystemManager( 3865): BgPowerManagerService:onStartCommand
,I/GAV2    ( 5827): Thread[GAThread,5,main]: No campaign data found.
,I/HwSystemManager( 3865): AppLockService:onStartCommand
,I/HwSystemManager( 3865): AppCleanUpService:onStartCommand() in!
,I/HwSystemManager( 6324): check push opration, match idx:-1
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 6324): HsmStat_info:feature enable:false
I/GAv4-SVC( 5626): Google Analytics 8.3.01 is starting up.
,I/HwSystemManager( 6324): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 6324): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.test.thalitest, com.example.hello]
,I/HwSystemManager( 6324): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): ProcPolicy:begin get procName.
,I/HwSystemManager( 6324): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 6324): ProcPolicy:end get procName.
,I/HwSystemManager( 6324): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/YhdsEngine( 6324): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
,I/HwSystemManager( 6324): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6324): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
,I/HwSystemManager( 6324): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 6324): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6324): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 6324): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6324): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/HwSystemManager( 6324): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@1d784bba
,I/HwSystemManager( 6324): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/HwSystemManager( 6324): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/YhdsEngine( 6324): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 6324): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 6324): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 6324): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 3865): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3865): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 3865): AppCleanUpService:msg is 0
,I/HwCust  ( 6324): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
,I/YhdsEngine( 6324): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 6324): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
I/HwSystemManager( 6324): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): HsmPackageManager:begin to scan apks.
I/HwSystemManager( 6324): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
W/HwSystemManager( 6324): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:3, queue size:0
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match,[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6324): anf:packageCanAccessInternet component enable
W/jxcore-log( 6180): Platform android
W/jxcore-log( 6180): 
W/jxcore-log( 6180): Process ARCH arm
W/jxcore-log( 6180): 
I/HwSystemManager( 6324): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/YhdsEngine( 6324): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 6324): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
I/HwSystemManager( 6324): XmlRuleBase:parseAndCacheList black_match :[]
I/HwSystemManager( 6324): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6324): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
I/HwSystemManager( 6324): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 6324): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
I/HwSystemManager( 6324): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
,I/jxcore-log( 6180): JXcore Cordova bridge is ready!
I/jxcore-log( 6180): 
,W/jxcore-log( 6180): JXcore engine is started
,I/HwSystemManager( 6324): HsmPackageManager:end to scan apks. size:150 + 0
,I/HwSystemManager( 6324): HsmPackageManager:init locale:en_US
,I/HwSystemManager( 6324): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 6324): ProtectAppControl:handleMessage:6
I/HwSystemManager( 6324): ProtectAppControl:begin install app inner:com.example.hello
,I/HwSystemManager( 6324): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
,I/HwSystemManager( 6324): PermissionDBAdapter:DBAdapter created!
,I/HwSystemManager( 6324): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
,I/HwSystemManager( 6324): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6324): PermissionDBAdapter:appcationsList size:150
,W/HwSystemManager( 6324): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
,W/HwSystemManager( 6324): ProtectAppControl:com.example.hello already exist!
,E/jxcore-log( 6180): >> HUAWEI-ALE-L21
E/jxcore-log( 6180): 
,I/jxcore-log( 6180): Total memory 1949741056
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): Free memory 18513920
I/jxcore-log( 6180): 
I/jxcore-log( 6180): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): userPath [ 'www' ]
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): Size 720 1184
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): Screen Brightness 242
I/jxcore-log( 6180): 
,E/jxcore-log( 6180): Dummy Error Log.
E/jxcore-log( 6180): 
,I/HwSystemManager( 6324): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6324): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6324): PermissionDBAdapter:appcationsList size:150
,I/HwEmailTag( 6149): EmailProvider->query->1449501106887;end;;consuming:2ms;
,I/HwSystemManager( 6324): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6324): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6324): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6324): HsmIntentService:last work complete! lets stop service.
,I/HwEmailTag( 6149): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwEmailTag( 6149): Device->updateDeviceIdIfNeeded
,I/HwSystemManager( 6324): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@1d784bba
,I/HwEmailTag( 6149): Device->updateDeviceIdIfNeeded->doInBackground
,I/HwEmailTag( 6149): Device->getDeviceId->
I/HwEmailTag( 6149): CleanRecipient->onCreate
,I/HwEmailTag( 6149): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 6149): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 6149): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 6149): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 6149): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/HwEmailTag( 6149): AccountReconciler->reconcileAccountsInternal->consuming:73ms
,I/HwEmailTag( 6149): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 6149): CleanRecipient->onDestroy
,I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10090
I/HwSystemManager( 3865): HoldService:uid:10090 pid:5500 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10090,5500
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10090, pid: 5500
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10090, pid: 5500
,I/HwCust  ( 6394): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6394): EmailContent->init->consuming:16ms->;-prefixstartupperformance-
,I/HwEmailTag( 6394): Exchange->onCreate
,I/jxcore-log( 6180): getBuffer is called!!!!
I/jxcore-log( 6180): 
,I/PG Utils( 6394): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6394): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6149): EmailProvider->query->1449501107151;end;;consuming:1ms;
,I/HwEmailTag( 6394): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/GAv4    ( 6368): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6368):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6368):   adb logcat -s GAv4
,W/GAv4    ( 6368): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/HwSystemManager( 3865): HoldService:uid:10092 pid:5529 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10092
I/HwSystemManager( 3865): HoldService:oldVersionKey:10092,5529
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 3865): HoldService:uid:10095 pid:5553 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10095,5553
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10092, pid: 5529
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10092, pid: 5529
,E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10095, pid: 5553
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10095, pid: 5553
,W/GAv4    ( 6368): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6368): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6368): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,I/ContactsAppilcation( 6237): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/CommonUtilMethods( 6237): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6237): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,I/CommonUtilMethods( 6237): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6237): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,W/ContextImpl( 6368): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/art     ( 2985): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/HwSystemManager( 3865): HoldService:uid:10001 pid:4846 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10001,4846
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10001
,E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10001, pid: 4846
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10001, pid: 4846
,I/HwSystemManager( 6324): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6324): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6324): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/art     ( 6368): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6368): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6368): Installed default security provider GmsCore_OpenSSL
,I/art     ( 2985): Can not find class: Lcom/android/server/accounts/AccountManagerService$TestFeaturesSession;
,I/HwSystemManager( 6324): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6324): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6324): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/PG Utils( 6436): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6436): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6436): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 6324): HsmStat_info:service connect
,I/HwSystemManager( 3865): HoldService:uid:10087 pid:5575 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10087
I/HwSystemManager( 3865): HoldService:oldVersionKey:10087,5575
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10087, pid: 5575
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10087, pid: 5575
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/GmsModuleInitializer;
,I/art     ( 2985): Explicit concurrent mark sweep GC freed 14319(746KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.100ms total 188.177ms
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/app/GmsApplicationContext;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue;
,I/art     ( 5626): Can not find class: Lcom/google/android/flib/pref/PreferenceFile;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/PlatformVersion;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils$1;
,I/art     ( 5626): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/Asserts;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReaderImpl;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReader;
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExchangeAccountType@1f7aae3d in the cache
,I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:0
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/receiver/PlaySystemBroadcastReceiver;
,I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:1
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/UserAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/GamesSyncAdapter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/sync/BaseGmsSyncAdapter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/config/G;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesLog;
,I/HwCust  ( 6237): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/VersionUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/GamesSharedPrefs;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$AsyncOperationQueue;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/Preconditions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/AsyncOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$OperationTask;
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExternalAccountType@6983f83 in the cache
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService$PooledAsyncOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/WrappedGamesCallbacks;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/quests/AcceptQuestOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractDataHolderOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$Operation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/requests/AcceptRequestOperation;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/AcceptTurnBasedMatchInvitationOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/AcknowledgeNotificationsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/AddNearbyPlayerOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractStatusReportingOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CancelTurnBasedMatchOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/quests/ClaimMilestoneOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/ClearDataOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/ClearNotificationsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/events/ClearPendingEventsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/ApiClientTracker;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveContents;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/CommitSnapshotOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomEnteredCallback;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/ConnectionInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/safeparcel/SafeParcelable;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/CreateRoomOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CreateTurnBasedMatchOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DeclineInvitationOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/DeleteSnapshotOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DismissInvitationOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/DismissTurnBasedMatchOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/DismissPlayerSuggestionOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/requests/DismissRequestOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/multiplayer/ParticipantResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/FinishTurnBasedMatchOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/GetGamesAuthTokenOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/GetInboxActivityCountsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/GetScoreOperation;
,W/ResourceType( 6237): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6237): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$GamesThreadFactory;
W/ResourceType( 6237): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6237): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExternalAccountType@1568f139 in the cache
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/GetTurnBasedMatchOperation;
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.GoogleAccountType@2244437e in the cache
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/AccountsChangedOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/PackageModifiedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/PeopleChangedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/PopupManager$PopupLocationInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/IncrementAchievementOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/events/EventIncrementEntry;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/events/IncrementEventsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/InitializeGamesOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/InvalidateAppContentOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/IsGameMutedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/JoinRoomOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/video/VideoConfiguration;
,E/ExternalAccountType( 6237): Unsupported attribute readOnly
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/video/LaunchGameForRecordingOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/client/IPlayGamesCallbacks;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/ClientContext;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomLeftCallback;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveDiagnostics;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FastMapJsonResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FastJsonResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/LeaveRoomOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LeaveTurnBasedMatchOperation;
,I/AccountTypeManager( 6237): AccountManager, account size is: 2
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/video/ListVideosOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsInternalOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AppContentContext;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/LoadAppContentOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractMultiDataHolderOperation;
I/AccountTypeManager( 6237): Loaded meta-data for 5 account types, 3 accounts in 85ms(wall) 59ms(cpu)
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadCircledPlayersOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameCollectionComparisonOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadConnectedPlayersOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/LoadContactSettingsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsByIdOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/LoadExperimentsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadFirstPartyPlayersOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameFirstPartyOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameInstancesOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameSearchSuggestionsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGamesCollectionOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadInvitablePlayersOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/LoadInvitationsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadLeaderboardsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadMoreScoresOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpStreamOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/acls/LoadNotifyAclOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadPlayGamesRecentlyPlayedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayerOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadScoresOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/stats/LoadPlayerStatsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersInternalOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadProfileSettingsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/quests/LoadQuestsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestSummariesOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/LoadSnapshotsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LoadTurnBasedMatchesOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpForGameCategoriesOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/NotificationOpenedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/RecordApplicationSessionOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/RecordPlayerSuggestionActionOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/RematchTurnBasedMatchOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$P2pStatusReportCallback;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/ReportP2pStatusOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/ResolveSnapshotConflictOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/UpdateAchievementOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/SearchForGamesOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/SearchForPlayersOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/requests/SendRequestOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/SetAchievementStepsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/SetGameMuteStatusOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/SetIdentitySharingConfirmedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/quests/QuestStateChangedPopupOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/SignOutOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/AndroidUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$OperationAdapter;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/video/StopRecordingOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/SubmitScoreOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/UpdateContactSettingsOperation;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/acls/UpdateNotifyAclOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/games/UpdatePlayedOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/players/UpdateProfileSettingsOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/UpdateTurnBasedMatchOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/IGmsCallbacks;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/GetServiceRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/ValidatePlayServiceConnectionOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/ValidateServiceConnectionOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/VerifySnapshotFolderOperation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$2;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/DataBroker;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Lockable;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/service/OperationException;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/auth/GoogleAuthException;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Lockable$LockableLock;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/GamesServer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/AbstractServer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/auth/appcert/AppCertServiceClient;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/auth/AuthSessionAuthenticator;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/error/ErrorUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/auth/GoogleAuthUtil;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer$DefaultApiaryRetryPolicy;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$1;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$Batch;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FieldMappingDictionary;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/ApiaryRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/VolleyInterruptedError;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/NoResponseRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/ImageRequest;
,I/PeopleContactsSync( 5626): CP2 sync disabled
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/GamesRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GamesExperiments;
,I/art     ( 5626): Can not find class: Lcom/google/android/play/experiments/PlayExperiments;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/Base64Utils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/config/GamesOptions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/error/ErrorInstanceResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/error/GamesException$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/error/GamesException;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$6;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$1;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$3;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$4;
,I/art     ( 5626): Can not find class: Lcom/google/android/gsf/Gservices;
,I/art     ( 5626): Can not find class: Lcom/google/android/gsf/Gservices$1;
,I/Icing   ( 5626): Storage manager: low false usage 1.44MB avail 7.15GB capacity 8.84GB
,I/art     ( 5626): Can not find class: Lcom/google/android/gsf/Gservices$1$1;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/GamesServerFactory;
,W/BaseAppContext( 5626): Using Auth Proxy for data requests.
W/BaseAppContext( 5626): Using Auth Proxy for data requests.
I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/server/PlusServer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/config/G;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/SpamAndAbuseHeaders;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/server/ContainerParam;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/auth/AuthTokenTimeCache;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/server/SocialClient;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/BaseAppContext( 5626): Using Auth Proxy for data requests.
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/Icing   ( 5626): Received bad json for section weights override -- ignoring.
,W/Icing   ( 5626): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 5626): Received bad json for section weights override -- ignoring.
W/Icing   ( 5626): Received bad json for corpus context scoring override -- ignoring.
,I/UpdateIcingCorporaServi( 5926): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/BaseAppContext( 5626): Using Auth Proxy for data requests.
,I/art     ( 2321): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 239us total 29.250ms
,W/BaseAppContext( 5626): Using Auth Proxy for data requests.
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryServer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/utils/Log;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/G;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$5;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/BaseAppContext( 5626): Using Auth Proxy for data requests.
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/TransientCacheOwner;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/InboxCounter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$Builder;
I/art     ( 2321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 247us total 28.585ms
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$DataType;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/utils/GamesDataUtils;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/DefaultClock;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/Clock;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/BaseApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AchievementCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Agents$QueryBuilder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementDefinitions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementDefinitionsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/DataHolder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/DataHolder$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Players;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayersColumns;
,I/art     ( 2321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 209us total 27.235ms
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$1;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementFlushData;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleRequest;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/ApiRateLimitUtil;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/error/ErrorResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementInstances;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementInstancesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/provider/QuerySpec;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/achievement/AchievementBuffer;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/AbstractDataBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/DataBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Releasable;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/achievement/Achievement;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/Freezable;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Agents;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$TypeQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementStepData;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$IncrementQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/ui/popup/AchievementPopup;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/ui/popup/BasePopup;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlayGamesUploadService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/GcmTaskService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinition;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FastContentValuesJsonResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievement;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/GamePlayerCacheKey;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementPendingOps;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementPendingOpsColumns;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$PendingOpsQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/AchievementState;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/util/AccountUtils;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/ArrayMap;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/SimpleArrayMap;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementSetStepsAtLeast;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementIncrement;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementUpdateResult;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementIncrementResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationFetchList;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementGetMultipleResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementListResponse;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementSetStepsAtLeastResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUnlockResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AchievementRevealResponse;
,E/Icing   ( 5626): Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/ContainerHelpers;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/ArrayMap$1;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/MapCollections;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/MapCollections$KeySet;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/MapCollections$ArrayIterator;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache$OwnerCache;
,I/art     ( 5626): Can not find class: Landroid/support/v4/util/LruCache;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/BaseGmsContentProvider;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/Objects;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$UriType;
,I/art     ( 5626): Can not find class: Lcom/android/common/content/ProjectionMap;
,I/art     ( 5626): Can not find class: Lcom/android/common/content/ProjectionMap$Builder;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/provider/TableJoiner;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerLevels;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerLevelColumns;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerStats;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerStatsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ClientContexts;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ClientContextsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestPendingOps;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestPendingOpsColumns;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ApplicationSessions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ApplicationSessionColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AppContents;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AppContentColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Images;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ImagesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardPendingScores;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Requests;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Matches;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchesPendingOps;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesPendingOpsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesDataStore;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesDatabaseHelper;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/utils/UriUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$ImageCleaner;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$3;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/ImageStore;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/ImageStore$Entry;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$GamesProjectionMapBuilder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameInstances;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameInstancesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventInstances;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventInstancesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventPendingOps;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventPendingOpsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ExperienceEvents;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ExperienceEventColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Invitations;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$InvitationsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Participants;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ParticipantsColumns;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardInstances;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardInstancesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardScores;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardScoresColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Notifications;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$NotificationsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Milestones;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MilestoneColumns;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestRecipients;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestRecipientsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Snapshots;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$SnapshotColumns;
,I/art     ( 5626): Can not find class: Lcom/android/common/SharedPreferencesCompat;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Games;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GamesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventDefinitions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventDefinitionColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Leaderboards;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/constants/OfflineMatchAction;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Quests;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$QuestsColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$1;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleterAssociatedQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$2;
,I/MusicStore( 6479): Database version: 120
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AppContentsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AppContentSectionAndCardCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AppContentBaseCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AppContentActionCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AppContentAnnotationCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AppContentConditionCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/AppContentTupleCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$CardImageInsertHelper;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ContentEntry;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Section;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Card;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/CardAnnotation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ImageAsset;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/CardCondition;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/CardAction;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FastParser$ParseException;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/GamesCardScreenFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$ServerCookieQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/constants/DeviceType;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/EventAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/EventResolver;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$WindowInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodRange;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodUpdate;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$PendingOpsQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$EventDefinitionRefreshInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinition;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinitionListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$UnresolvedException;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEvent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEventListResponse;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateRequest;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventRecordRequest;,
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/GameCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/GameSearchCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/BaseSearchCache;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplication;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Application;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MarketApplication;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MarketBadge;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ImageConfig;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/converter/ImageUrlBuilder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MarketInstance;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameBadges;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameBadgesColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Instance;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/InstanceAndroidDetails;
I/art     ( 2985): Can not find class: Lcom/android/server/power/Notifier$2;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/util/PackageUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Snapshot;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/util/PanoUtils;,
I/KeyguardFingerprint.Validation( 3127): start
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationCategory;
E/AuthenticationManager( 3127): AuthenticationManager open failed: the AuthenticationService is null
W/KeyguardFingerprint.Utils( 3127): AuthenticationManager open return null
I/KeyguardFingerprint.Validation( 3127): Fingerprint unlock is not enabled
I/KeyguardViewMediator( 3127): fingerprint validation not started
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/GameBuffer;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/Game;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationList;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchContext;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchList;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetUpdatesMultipleFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsFlushData;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/SessionBatch;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetMultipleFirstPartyResponse;
,E/WifiStateMachine( 2985):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine( 2985):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 2985):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state InitialState suppState:UninitializedState
,E/WifiStateMachine( 2985):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine( 2985):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$FirstPartyGameListProcessor;
E/WifiStateMachine( 2985):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine( 2985):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationListFirstPartyResponse;
E/WifiStateMachine( 2985):  InitialState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
,E/WifiStateMachine( 2985):  DefaultState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
,E/WifiStateMachine( 2985):  InitialState !CMD_CLEAR_BLACKLIST 0 0
,E/WifiStateMachine( 2985):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$GameRefreshRecord;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/TransientDataHolder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$VersionQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplicationUpdates;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/constants/AppUpdateType;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/ArrayUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/InvalidId;
W/audio_a2dp_hw( 2590): adev_set_parameters: WARNING: set param called even when stream out is null
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCacheKey;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$StoreGamesProcessor;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameSearchSuggestions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameSearchSuggestionsColumns;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestion;
,W/HwScreenOnProximityLock( 2985): releaseLock: return because sensor listener is held = false
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/DataUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationSearchFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Session;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$InstanceQuery;
,I/PG Utils( 6479): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/LeaderboardScoreCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Leaderboard;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScores;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardEntry;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Player;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/LeaderboardCollection;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/TimeSpan;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PageTokensQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheKey;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheOwner;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PendingScoreQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/provider/SelectionArgs;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ScoreSubmission;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreSubmissionList;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScoreListResponse;
I/TimeManager( 3194): receiver action = android.intent.action.SCREEN_ON
I/TimeManager( 3194): hand message 2
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScore;
I/TimeManager( 3194): notify time change. size = 2
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScoreRank;
I/TimeLayout( 3194): time = 16:11
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader$Builder;
,I/TimeLayout( 3194): updateDate date = 12/7/2015
I/TimeLayout( 3194): weekDay = Monday,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GamesDroidGuard;,
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScore;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData$Result;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3704): Explicit concurrent mark sweep GC freed 8265(450KB) AllocSpace objects, 2(40KB) LOS objects, 40% free, 17MB/29MB, paused 990us total 79.005ms
,E/WifiStateMachine( 2985):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0,
,E/WifiStateMachine( 2985):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 2985):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state InitialState suppState:UninitializedState
,E/WifiStateMachine( 2985): setScanAlarm false period 10000 initial delay 0
,E/WifiStateMachine( 2985):  InitialState CMD_ENABLE_RSSI_POLL 0 0
,E/WifiStateMachine( 2985):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine( 2985):  InitialState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,E/WifiStateMachine( 2985):  DefaultState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/NotificationAgent;,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayCommonAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/NonListener;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApiInternal;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/PeopleApi;
W/audio_a2dp_hw( 2590): adev_set_parameters: WARNING: set param called even when stream out is null
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MetagameApiInternal;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ExperiencesApiInternal;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/PlayerCache;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/PlayerSearchCache;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/ContactSettingsCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/ProfileSettingsCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/cache/XpEventStreamCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/PlayerBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/Player;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$CircledStateQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/People;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Api;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions$HasOptions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/ConnectionResult;
,W/ContextImpl( 6479): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyPlayer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Played;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$PeopleNetworkData;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListResponse;
,I/HwLauncher( 3655): Launcher receiver screen off broadcast sendmessage true
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/PlayerLevel;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Experience;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PeopleFeed;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FastSafeParcelableJsonResponse;
I/TimeManager( 3194): receiver action = android.intent.action.SCREEN_OFF
,I/TimeManager( 3194): hand message 3
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person$Image;
I/HwSystemManager( 3865): BgPowerManagerService:MSG_SCREEN_OFF Received and mScreenOffTime :1449501109547 mScreenOffBatterylevel :2205
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleFeed;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/model/people/Person;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/model/people/Person$Image;
I/HwSystemManager( 3865): AppLockService:BroadcastReceiver, intent is null or applock function is closed!
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$TrimExperiencesQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ProfileSettings;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleOptions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/internal/PeopleUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/Graph;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/PendingResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Result;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleResult;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/People$ReleasableResult;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Status;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/model/PersonBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/model/DataBufferWithSyncInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/people/model/Person;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/logging/GamesPlayLogger;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/data/GamesDataChangeUris;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity$ImageEntity;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/images/ImageBroker;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$LevelQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/GamesStatusCodes;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ContactSettings;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ContactChannelSetting;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/NotificationChannel;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/CategoryListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Category;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MetagameConfig;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLevel;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceSyncFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$SyncNetworkResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AccountMetadata;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestonesApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Quest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestone;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestCriterion;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestContribution;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/quest/QuestBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/EntityBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/quest/Quest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$QuestsEntities;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/Joiner;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/GameEventListenerRegistry;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/ui/popup/QuestPopup;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$SyncNetworkResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$NotifyDataHolder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$MilestoneClaimedQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestListFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataSyncFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/QuestSyncFirstPartyResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RevisionAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RevisionsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyRevisionCheckResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AclAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AclsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMember;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingRoster;
W/ContextImpl( 6479): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 5626): Can not find class: Lcom/google/protobuf/micro/MessageMicro;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingTargetId;
,I/art     ( 5626): Can not find class: Lcom/google/protobuf/micro/InvalidProtocolBufferMicroException;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Acl;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMemberConversions;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Acls;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AclsColumns;
,W/ContextImpl( 6479): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/AclUpdateRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestSummaryColumns;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/OutboundRequestInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestRecipient;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestEntities;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/request/GameRequestBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/request/GameRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$RequestSummariesData;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/PlayerRef;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/DataBufferRef;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/GameRef;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateList;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdate;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$SyncNetworkResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestEntity;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Request;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyNotification;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/InboundRequestInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$TrimRequestsQuery;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$PendingOpsQuery;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/SendRequest;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/RequestType;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestSyncResponseFirstParty;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes$Builder;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResultList;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResult;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApi;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/service/FilesApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/Drive;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveApi;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveApi$ResourceIdSetResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/MetadataBundle;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/MetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/CustomPropertyKey;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/data/BitmapTeleporter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/Query;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveApi$MetadataBufferResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$ResultPair;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/MetadataBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Api$ClientKey;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/Api$Client;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/GmsClient;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/GmsClientEventManager$GmsClientEventState;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/LogicalFilter;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/AbstractFilter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/Filter;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl$6;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/internal/DriveBaseApiMethodImpl;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ApiMethodImpl;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/internal/BasePendingResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ResultHolder;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/api/internal/GoogleApiClientImpl$Runner;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/FullTextSearchDetector;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/FilterVisitor;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/Metadata;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveId;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/mdm/DeviceManager;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi$DeviceNameResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$DriveIdQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveIdResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveFile;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveResource;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveResource$MetadataResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$TitleMetadataField;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/StringMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/BaseMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableMetadataField;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/SortableMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$ModifiedMetadataField;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/DateMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/OrderedMetadataField;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableOrderedMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$MimeTypeMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/internal/model/File;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/postprocessor/PostProcessorHelper;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveContentsResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation$SnapshotOpenData;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Agents$TwoColumnMapper;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/service/PlaySnapshotEventService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/chimera/DriveEventService;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions$Builder;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/ImageUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveFolder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/internal/DriveFolderImpl;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/internal/DriveResourceImpl;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFolderResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotListResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFileResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/Query$Builder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/SearchableField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableCollectionMetadataField;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/InFilter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/ComparisonFilter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/Operator;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/HasFilter;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/SortOrder$Builder;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$CreatedMetadataField;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/internal/FieldWithSortOrder;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/drive/query/SortOrder;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/util/IOUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/StatsAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/StatsApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/StatsResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitiesApiInternal;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchEntities;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyMultiplayerEntity;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/Room;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatch;
,I/art     ( 6479): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/multiplayer/InvitationBuffer;
W/System  ( 6479): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a91d9b8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6479): Installed default security provider GmsCore_OpenSSL
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/multiplayer/Invitation;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/multiplayer/Participatable;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/multiplayer/Participant;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$SyncNetworkResponse;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$VersionInfo;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerUtils;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitySyncFirstParty;
,I/ConfigStore( 6479): Config Database version: 1,
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApi;,
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApiInternal;
,I/Icing   ( 5626): updateResources: need to parse f{com.google.android.gms}
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/NetworkDiagnostics;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent$RoomCache;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomJoinRequest;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/Capability;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomClientAddress;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomCreateRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomAutoMatchingCriteria;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomP2PStatuses;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/RoomStatus;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApi;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApiInternal;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchResults;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/MatchParticipantResult;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent$PendingOpsQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/server/response/FastParser;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchTurn;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchDataRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchCreateRequest;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedAutoMatchingCriteria;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/internal/constants/TurnBasedMatchStatus;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/multiplayer/turnbased/TurnBasedMatchBuffer;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchRematch;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$CaptureStateCallback;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$CaptureOverlayListener;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GamesUris;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent$MetadataQuery;
,I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Agents$1;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/games/broker/Agents$2;
I/art     ( 5626): Can not find class: Lcom/google/android/gms/common/internal/ClientContextCreator;
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6149): HwUtils->triggerPeriodSync->
I/HwEmailTag( 6149): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 6149): EmailProvider->triggerPeroidSync->accountId:-1
,I/MediaRouter( 6479): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=6, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/HwEmailTag( 6149): EmailProvider->query->1449501109967;end;;consuming:1ms;
,I/HwEmailTag( 6149): EmailProvider->query->1449501109972;end;;consuming:6ms;
,I/PG Utils( 2985): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6479): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GHttpClientFactory( 6479): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6479): Using platform SSLCertificateSocketFactory
,W/System.err( 2985): java.lang.SecurityException: WifiService: Neither user 10084 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2985): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2985): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2985): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2985): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2985): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2985): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2985): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 6479): WifiServiceMessenger == null
,I/HwEmailTag( 6149): EmailProvider->query->1449501110107;end;;consuming:1ms;
,I/HwEmailTag( 6149): EmailProvider->query->1449501110111;end;;consuming:1ms;
,I/PG Utils( 2985): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,W/StubController( 6051): calendar access!
,W/StubController( 6051): calendar access!
,I/CalendarSimpleUiPRovider( 6051): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6051): onConfigurationChanged
,I/CalendarSimpleUiPRovider( 6051): initParams20151207T161150Europe/Warsaw(1,340,3600,0,1449501110)
,W/StubController( 6051): calendar access!
I/PG Utils( 6051): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6479): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,E/SQLiteLog( 6076): (284) automatic index on view_events(_id)
W/StubController( 6076): calendar access!
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/MDM     ( 3515): [100] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PG Utils( 6479): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6479): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,W/StubController( 6051): calendar access!
,I/CalendarSimpleUiPRovider( 6051): loadEvent end update UI0
,I/Icing   ( 5626): Internal init done: storage state 0
,I/Icing   ( 5626): Post-init done
,I/art     ( 2985): Explicit concurrent mark sweep GC freed 16329(879KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.741ms total 194.476ms
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6479): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2985): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/MediaStoreImporter( 6479): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/UpdateIcingCorporaServi( 5926): UpdateCorporaTask done [took 1678 ms] updated apps [took 1678 ms] 
,W/GCoreFlp( 3515): No location to return for getLastLocation()
,W/FusedLocationProvider( 3704): location=null
,I/ActivityManager( 2985): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Kids    ( 5626): [KidAccountFixer] No network connection
,W/GCoreFlp( 3515): No location to return for getLastLocation()
W/FusedLocationProvider( 3704): location=null
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5735): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 5735): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5735): Installed default security provider GmsCore_OpenSSL
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/StubController( 6051): calendar access!
,W/StubController( 6051): calendar access!
,I/CalendarSimpleUiPRovider( 6051): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6051): onConfigurationChanged
,I/CalendarSimpleUiPRovider( 6051): initParams20151207T161150Europe/Warsaw(1,340,3600,0,1449501110)
,W/StubController( 6051): calendar access!
,I/PG Utils( 6051): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6149): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/StubController( 6051): calendar access!
,I/CalendarSimpleUiPRovider( 6051): loadEvent end update UI0
,I/Icing   ( 5626): Indexing 48E0B8513D016F528E09274BED3370D7722E57CB from com.google.android.googlequicksearchbox
,I/BluetoothAdapter( 6180): Start to disable Bluetooth!
,I/HwSystemManager( 3865): HoldService:checkBeforeShowDialog: uid:10302 pid:6180, permissionType:2097152
I/HwSystemManager( 3865): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2985): allowOpenWifi blocked:false
,I/jxcore-log( 6180): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6180): 
,I/art     ( 5626): Explicit concurrent mark sweep GC freed 65073(5MB) AllocSpace objects, 56(1120KB) LOS objects, 40% free, 20MB/33MB, paused 1.668ms total 123.256ms
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.googlequicksearchbox] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5626): acquire_providerpkg:[com.google.android.googlequicksearchbox] pid:[]  maybe timeout , send to PG
,I/Icing   ( 5626): Indexing done 48E0B8513D016F528E09274BED3370D7722E57CB
,I/appproc ( 6561): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6561): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6561): app_process:number,5,0
,I/AndroidRuntime( 6561): readDownloadBoosterConfig: 'false'
,I/        ( 6561): power log dlsym ok
,I/ActivityManager( 2985): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/HwLauncher( 3655): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwLauncher( 3655): Model replacing = false package = com.google.android.gms
I/HwSystemManager( 3865): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwSystemManager( 3865): HsmPackageManager:replacing:false
I/HwSystemManager( 3865): HsmPackageManager:pkgName:com.google.android.gms
,I/HwLauncher( 3655): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.google.android.gms]
I/HwLauncher( 3655): SimpleLauncherModeaction= android.intent.action.PACKAGE_CHANGEDpackageName = com.google.android.gms
I/HwLauncher( 3655): Model mAllAppsList.updatePackage com.google.android.gms
I/HwSystemManager( 6324): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwSystemManager( 6324): HsmPackageManager:replacing:false
I/HwSystemManager( 6324): HsmPackageManager:pkgName:com.google.android.gms
I/HwSystemManager( 3865): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExchangeAccountType@2431912c in the cache
,W/ResourceType( 2985): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:0
,I/HwLauncher( 3655): AllIdleAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 61
,I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:1
,I/InputReader( 2985): Reconfiguring input devices.  changes=0x00000010
,I/HwSystemManager( 6324): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
E/RegisteredServicesCache( 3588): invalidateCache set mNeedToastTableFull
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExternalAccountType@375e67f5 in the cache
,I/HwLauncher( 3655): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3655): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = Google Settings
,I/HwLauncher( 3655): Model shortcutInfo.title = Google Settings
I/HwLauncher( 3655): Workspace updateShortcuts apps.size() 1
I/HwLauncher( 3655): Launcher.Folder childCount: 9
I/HwLauncher( 3655): SimpleLauncherModemAllAppsList.updatePackage com.google.android.gms
I/HwLauncher( 3655): Launcher.Folder childCount: 5
,I/HwLauncher( 3655): Workspace updateShortcuts shortcutInfo = Google Settings
,I/HwLauncher( 3655): SimpleAllAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 0
,I/HwLauncher( 3655): Launcher.Folder childCount: 7
I/HwLauncher( 3655): Launcher.Folder childCount: 9
I/HwLauncher( 3655): Launcher.Folder childCount: 6
I/HwLauncher( 3655): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3655):  syncPages mCurrentPage = 0
I/HwLauncher( 3655): SimpleAllAppsList  findAndUpdateInfoInDB : found 0 shortcutInfo for package[com.google.android.gms] in db
I/HwLauncher( 3655): SimpleAllAppsList  updatePackage do not add new SimpleApplicationInfo,It's in normal now. package = com.google.android.gms
W/HwLauncher( 3655): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
W/asset   ( 2985): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
E/HideAppsPagedView( 3655):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3655):  createAddIcon count = 0
,W/ResourceType( 6237): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6237): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6237): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6237): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/HwLauncher( 3655):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExternalAccountType@7281bfb in the cache
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.GoogleAccountType@23bc9418 in the cache
I/HwLauncher( 3655): Launcher Deferring update until onResume
,E/android_hardware_fm.cpp( 6561): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6561): ========64bit long size = 8
E/FM_HAL  ( 6561): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 6561): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6561): 
I/fm_hisi ( 6561): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6561): 
I/fm_hisi ( 6561): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6561): 
,E/ExternalAccountType( 6237): Unsupported attribute readOnly
,E/android_hardware_fm.cpp( 6561): register_android_hardware_fm_fmradio, ret is 0
,I/AccountTypeManager( 6237): AccountManager, account size is: 2
,I/AccountTypeManager( 6237): Loaded meta-data for 5 account types, 3 accounts in 86ms(wall) 36ms(cpu)
,I/art     ( 2985): Can not find class: Lcom/android/server/usb/UsbSettingsManager$AccessoryFilter;
,I/art     ( 2985): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2985): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/GCoreNlp( 3515): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/HwSystemManager( 3865): avl:parsePowerWarningParameter result:{app_show_level=1, dangerous_current_level=30, count_frequency_fg=5, high_level_standard=10, msg_send_interval=240, dangerous_level_standard=25, min_interval_time=3, average_current_fg=350, count_frequency=60}
,I/HwSystemManager( 3865): BgPowerManagerService:MSG_SCREEN_ON Received and mScreenOmTime :1449501112442 mScreenOffTime :1449501109547mCurBatterylevel :2205mScreenOffBatterylevel :2205
,I/HwSystemManager( 3865): HoldService:uid:10302 pid:6180 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10302,6180
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10302
,E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10302, pid: 6180
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10302, pid: 6180
,I/ActivityManager( 2985): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/PG Utils( 3515): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2985): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/HwSystemManager( 3865): AppLockService:applock password not initial or function is closed
,I/InputReader( 2985): Reconfiguring input devices.  changes=0x00000010
I/HwLauncher( 3655): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3655): Model replacing = false package = com.example.hello
I/HwLauncher( 3655): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3655): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
I/HwLauncher( 3655): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3655): Model mAllAppsList.removePackage com.example.hello
,I/HwLauncher( 3655): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
E/HideAppsPagedView( 3655): removeItems begin 
E/HideAppsPagedView( 3655): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3655): removeItems end 
,I/HwLauncher( 3655): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
I/HwLauncher( 3655): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3655): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3655): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3655): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3655): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
I/HwSystemManager( 6324): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 6324): HsmPackageManager:replacing:false
I/HwSystemManager( 6324): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 6324): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 3865): AppManager:getNetAppInfoFromDB cursor lenth = 1
W/System.err( 3655): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3655): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3655): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3655): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3655): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3655): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3655): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3655): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3655): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3655): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3655): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3655): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3655): java.lang.NullPointerException: null receiver
W/System.err( 3655): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3655): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3655): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3655): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3655): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3655): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3655): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3655): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3655): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3655): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3655): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3655): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3655): CellLayout rearrangeAfterRmItem isAutoAlign = false
I/HwLauncher( 3655): Launcher Deferring update until onResume
W/System.err( 2985): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExchangeAccountType@147b4456 in the cache
,I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:0,
I/SimFactoryManager( 6237): Get SIM state from SIM factory manager: 1,For slotId:1
,I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExternalAccountType@37d27cd7 in the cache
,W/System.err( 2985): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
,W/System.err( 2985): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
,W/System.err( 2985): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2985): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2985): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2985): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/YhdsEngine( 6324): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 6324): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_CHANGED, data: package:com.google.android.gms, replacing: false
,E/RegisteredServicesCache( 3588): invalidateCache set mNeedToastTableFull
,W/ResourceType( 6237): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,W/ResourceType( 6237): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6237): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6237): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.ExternalAccountType@bf2d9c4 in the cache
I/AccountTypeManager( 6237): Adding account type = com.android.contacts.model.account.GoogleAccountType@658a0ad in the cache
,I/HwSystemManager( 6324): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
,I/art     ( 2985): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
I/art     ( 2985): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
I/art     ( 2985): Can not find class: Lhuawei/com/android/server/util/ReportTool;
E/ExternalAccountType( 6237): Unsupported attribute readOnly
I/art     ( 2985): Can not find class: Lcom/huawei/report/ReporterInterface;
E/ReportTools( 2985): Can't find sReporterClazz
,I/art     ( 3865): Explicit concurrent mark sweep GC freed 91278(6MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 14MB/23MB, paused 8.126ms total 94.108ms
I/HwSystemManager( 3865): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/HwSystemManager( 3865): HsmPackageManager:replacing:false
I/HwSystemManager( 3865): HsmPackageManager:pkgName:com.example.hello
,I/art     ( 2985): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/HwSystemManager( 3865): HsmPackageManager:doAppRemoved, remove:com.example.hello
I/AccountTypeManager( 6237): AccountManager, account size is: 2
I/art     ( 2985): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 2985): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,I/HwSystemManager( 3865): ww:deleteLockData:com.example.hello
I/AccountTypeManager( 6237): Loaded meta-data for 5 account types, 3 accounts in 71ms(wall) 19ms(cpu)
,W/System.err( 2985): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2985): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2985): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2985): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2985): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2985): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2985): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2985): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2985): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2985): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2985): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2985): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2985): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2985): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2985): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2985): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2985): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2985): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2985): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2985): This is not beta user build
,W/GeofencerStateMachine( 3515): Ignoring removeGeofence because network location is disabled.
,I/PackageBroadcastService( 5626): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 5926): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 5626): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 5926): UpdateCorporaTask done [took 42 ms] updated apps [took 41 ms] 
,I/HwLauncher( 3655): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3655): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3655): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/HwLauncher( 3655): Launcher onStart()
I/HwLauncher( 3655): Launcher dynamicIconsRegister
I/HwLauncher( 3655): DynamicUpdater registerReceiver
,I/HwLauncher( 3655): DynamicUpdater call updateFolder
I/HwLauncher( 3655): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3655): DynamicUpdater registerReceiver
,I/HwLauncher( 3655): DynamicUpdater call updateFolder
I/HwLauncher( 3655): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3655): DynamicUpdater registerReceiver
,I/HwLauncher( 3655): DynamicUpdater call updateFolder
I/HwLauncher( 3655): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/HwLauncher( 3655): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3655): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3655): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
E/HideAppsPagedView( 3655): removeHideApps  begin 
E/HideAppsPagedView( 3655): removeHideApps  end 
E/HideAppsPagedView( 3655):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3655):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3655):  createAddIcon count = 0
,I/HwLauncher( 3655):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3655): Launcher  onWindowVisibilityChanged visibility = 0
,I/HwLauncher( 3655): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3655): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/PhoneStatusBar( 3194): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PhoneStatusBar( 3194): shouldTranslucent:true
I/PhoneStatusBar( 3194): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/art     ( 2985): Explicit concurrent mark sweep GC freed 34586(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 2.270ms total 332.288ms
,W/asset   ( 6640): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,E/Minikin ( 6618): addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,W/GalleryUtils( 6618): the font DroidSanChineseSlim is not exist!
,I/HwCust  ( 6640): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 6640): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/HwLauncher( 3655): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,I/HwLauncher( 3655): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3655):  stringArray[] [unknown]
,I/HwSystemManager( 3865): HoldService:uid:10010 pid:5955 died
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3865): HoldService:oldVersionKey:10010,5955
,E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10010, pid: 5955
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10010, pid: 5955
,I/HwSystemManager( 3865): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3865): BgPowerManagerService: mTimes = 0 firstTime = 62857 firstmBatteryCapacity =2205
,I/HwSystemManager( 3865): HoldService:uid:10044 pid:6368 died
I/HwSystemManager( 3865): HoldService:oldVersionKey:10044,6368
I/HwSystemManager( 3865): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 2985): onTransact in code is: 102
I/MediaProcessHandler( 2985): processOp opType: 1, uid: 10044, pid: 6368
W/MediaProcessHandler( 2985): remove target not exist, maybe the UI process: uid: 10044, pid: 6368
,I/HwSystemManager( 3865): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 3865): NotificationManagerReceiver:onReceive, send action to background
,I/HwSystemManager( 3865): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@f66d964
,I/HwSystemManager( 3865): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3865): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 6324): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
,E/SQLiteLog( 3865): (3850) statement aborts at 18: [DELETE FROM tbNotificationMgrCfg WHERE packageName = ?] disk I/O error - SQLITE_IOERR_LOCK
,I/HwSystemManager( 6324): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@28ef2027
I/HwSystemManager( 6324): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
E/HwSystemManager( 3865): NotificationDBProvider:delete exception
E/HwSystemManager( 3865): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.db.DBProvider.delete(Unknown Source)
E/HwSystemManager( 3865): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/HwSystemManager( 3865): 	at android.content.ContentResolver.delete(ContentResolver.java:1333)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.db.DBAdapter.at(Unknown Source)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.receiver.Receiver.k(Unknown Source)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.receiver.Receiver.doInBackground(Unknown Source)
E/HwSystemManager( 3865): 	at java.lang.reflect.Method.invoke(Native Method)
E/HwSystemManager( 3865): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/HwSystemManager( 3865): 	at bli.b(Unknown Source)
E/HwSystemManager( 3865): 	at bli.a(Unknown Source)
E/HwSystemManager( 3865): 	at bli.run(Unknown Source)
E/HwSystemManager( 3865): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HwSystemManager( 3865): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HwSystemManager( 3865): 	at java.lang.Thread.run(Thread.java:831)
I/HwSystemManager( 6324): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,E/SQLiteLog( 3865): (3850) statement aborts at 16: [DELETE FROM tbNotificationMgrLog WHERE packageName = ?] disk I/O error - SQLITE_IOERR_LOCK
,E/HwSystemManager( 3865): NotificationDBProvider:delete exception
E/HwSystemManager( 3865): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/HwSystemManager( 3865): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.db.DBProvider.delete(Unknown Source)
E/HwSystemManager( 3865): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/HwSystemManager( 3865): 	at android.content.ContentResolver.delete(ContentResolver.java:1333)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.db.DBAdapter.au(Unknown Source)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.receiver.Receiver.k(Unknown Source)
E/HwSystemManager( 3865): 	at com.huawei.notificationmanager.receiver.Receiver.doInBackground(Unknown Source)
E/HwSystemManager( 3865): 	at java.lang.reflect.Method.invoke(Native Method)
E/HwSystemManager( 3865): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/HwSystemManager( 3865): 	at bli.b(Unknown Source)
E/HwSystemManager( 3865): 	at bli.a(Unknown Source)
E/HwSystemManager( 3865): 	at bli.run(Unknown Source)
E/HwSystemManager( 3865): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HwSystemManager( 3865): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HwSystemManager( 3865): 	at java.lang.Thread.run(Thread.java:831)
I/HwSystemManager( 6324): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,E/SQLiteLog( 6324): (3850) statement aborts at 18: [DELETE FROM permissionCfg WHERE packageName = ?] disk I/O error - SQLITE_IOERR_LOCK
I/HwSystemManager( 3865): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 3865): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3865): HsmIntentService:last work complete! lets stop service.
,E/HwSystemManager( 6324): HsmIntentService:invoke error, InvocationTargetException:java.lang.reflect.InvocationTargetException
I/HwSystemManager( 6324): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6324): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 6324): HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 6324): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
,I/HwSystemManager( 6324): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 6324): ProtectAppControl:handleMessage:7
I/HwSystemManager( 6324): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6324): HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6324): HsmIntentService:last work complete! lets stop service.
,I/HwSystemManager( 6324): ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
,I/HwSystemManager( 3865): OptimizeProvider:delete com.example.hello
E/SQLiteLog( 3865): (3850) statement aborts at 18: [DELETE FROM protectedapps WHERE package_name = ?] disk I/O error - SQLITE_IOERR_LOCK
,E/DatabaseUtils( 3865): Writing exception to parcel
E/DatabaseUtils( 3865): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/DatabaseUtils( 3865): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DatabaseUtils( 3865): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DatabaseUtils( 3865): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DatabaseUtils( 3865): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DatabaseUtils( 3865): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/DatabaseUtils( 3865): 	at com.huawei.systemmanager.optimize.db.OptimizeProvider.delete(Unknown Source)
E/DatabaseUtils( 3865): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/DatabaseUtils( 3865): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
E/DatabaseUtils( 3865): 	at android.os.Binder.execTransact(Binder.java:446)
,I/HwSystemManager( 3865): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3865): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 3865): AppCleanUpService:msg is 1
E/SQLiteLog( 3865): (3850) statement aborts at 16: [DELETE FROM rarelyusedapps WHERE PACKAGE_NAME=?] disk I/O error - SQLITE_IOERR_LOCK
,I/HwSystemManager( 6324): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver,
,I/HwSystemManager( 6324): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
W/HwSystemManager( 6324): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6324): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6324): HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6324): HsmIntentService:last work complete! lets stop service.
,I/HwSystemManager( 6324): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6324): NetAppListPrepareReceiver:package removed: package:com.example.hello
I/HwSystemManager( 6324): NetAppListPrepareReceiver:replacing?:false

```
