#### Test 503880196b4ec73_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/HwEmailTag( 6435): MailAppProvider->onCreate->begin, consuming 1448306461307ms->-prefixstartupperformance-
W/art     ( 6322): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 3733): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3733): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 3733): initAddtionalStyle default
I/HwEmailTag( 6435): MailAppProvider->onCreate->end, consuming 1448306461346ms->-prefixstartupperformance-
I/HwCust  ( 6435): Constructor found for class com.android.email.service.HwCustImapServiceImpl
I/HwCust  ( 6435): Constructor found for class com.android.email.HwCustUtilityImpl
I/art     ( 2969): Explicit concurrent mark sweep GC freed 16620(985KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 27MB/41MB, paused 7.762ms total 210.842ms
I/HwCust  ( 6435): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
I/HwCust  ( 6435): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
I/HwEmailTag( 6435): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6435): HwUtils->initStaticVarsAsync
I/HwEmailTag( 6435): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6435): HwUtils->initStaticVarsAsync
I/HwCust  ( 6435): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
I/HwEmailTag( 6435): EmailContent->init->consuming:32ms->;-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 6435): EmailProvider->INTEGRITY_CHECK_URI != null
I/HwEmailTag( 6435): EmailProvider->onCreate->end, consuming 35ms->-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->onCreate->end, consuming 35ms->-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->resetVisibleLimits->start:1448306461432 ->-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->resetVisibleLimits->start:1448306461434 ->-prefixstartupperformance-
I/HwCust  ( 6435): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
I/HwEmailTag( 6435): HwUtils->initStaticVarsAsync->run:consuming:51ms; bidiFormatter:android.support.v4.text.BidiFormatter@54edbbf;accountsProjSize:42
I/HwEmailTag( 6435): HwUtils->initStaticVarsAsync->run:consuming:47ms; bidiFormatter:android.support.v4.text.BidiFormatter@54edbbf;accountsProjSize:42
I/HwEmailTag( 6435): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6435): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 24ms.
I/HwEmailTag( 6435): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6435): EmailApplication->onCreate->begin, consuming 104ms->-prefixstartupperformance-
I/HwEmailTag( 6435): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
I/HwSystemManager( 4024): HoldService:uid:1000 pid:5607 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:1000,5607
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 1000
I/HwCust  ( 6435): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
W/MediaProcessHandler( 2969): processOp uid 1000 is not concerned!
I/HwCust  ( 6435): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
I/HwEmailTag( 6435): EmailApplication->onCreate->end, consuming 109ms->-prefixstartupperformance-
I/HwEmailTag( 6435): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwEmailTag( 6435): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwEmailTag( 6435): EmailProvider->initBuildCache->start->1448306461527->-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 6435): EmailProvider->initBuildCache->start->1448306461527; consuming:2->-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->resetVisibleLimits->getDatabase, consuming:97ms;-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 6435): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6435): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 12ms.
I/HwEmailTag( 6435): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6435): EmailProvider->resetVisibleLimits->getDatabase, consuming:135ms;-prefixstartupperformance-
I/HwEmailTag( 6435): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 6435): EmailProvider->uiAccounts->start:1448306461569
I/HwEmailTag( 6435): EmailProvider->uiAccounts->start:1448306461569;end,consuming:3
I/HwEmailTag( 6435): EmailProvider->query->1448306461432;end;;consuming:140ms;
I/HwSystemManager( 4024): HoldService:uid:10050 pid:5632 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10050,5632
I/ActivityManager( 2969): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10050
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10050, pid: 5632
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10050, pid: 5632
I/HwCust  ( 6513): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
I/HwCust  ( 6489): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
I/PG Utils( 6489): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 6489): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 6489): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
W/HWContacts( 6513): ProviderFeatureChcker - cootek package not installed
E/TmoMonitor( 6513): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@1753adde
I/HwCust  ( 6489): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/HwCust  ( 6489): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/PG Utils( 6489): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6489): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
E/ContactsProtector( 6489): getHiCloudAccountData query fail
I/PG Utils( 6489): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6513): Constructor found for class com.android.mms.data.HwCustConversationImpl
I/PG Utils( 3527): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
I/EmuiFeatureManager( 6513): loadEmailAnrSupportFlag:true
I/Mms_threadcache( 6513): [RecipientIdCache] fill: begin
I/SimFactoryManager( 6513): Inside init method of SimFactoryManger the combination is:-1
I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6513): isSIM1CardPresent:1
I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:0
E/MmsConfig( 6513): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:1
I/HwCust  ( 6513): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
I/SimFactoryManager( 6513): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6513): isSIM2CardPresent:1
I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:0
I/CalendarProvider2( 6397): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6397): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6513): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
I/HwCust  ( 6513): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
I/art     ( 6513): Can not find class: Lhuawei/android/view/TableLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/TableLayout;
I/HwCust  ( 6489): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
I/art     ( 6513): Can not find class: Lhuawei/android/view/View;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6513): Can not find class: Landroid/widget/View;
I/art     ( 6513): Can not find class: Landroid/webkit/View;
I/art     ( 6513): Can not find class: Landroid/app/View;
I/art     ( 6513): Can not find class: Lhuawei/android/view/TableRow;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/TableRow;
I/art     ( 6513): Can not find class: Lhuawei/android/view/LinearLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/LinearLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/view/ImageButton;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/ImageButton;
I/art     ( 6513): Can not find class: Lhuawei/android/view/TextView;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/TextView;
I/ActivityManager( 2969): filter receiver for action = android.intent.action.PROVIDER_CHANGED
I/HwSystemManager( 4024): HoldService:uid:10001 pid:4994 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10001,4994
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10001
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10001, pid: 4994
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10001, pid: 4994
I/art     ( 6513): Can not find class: Lhuawei/android/view/RelativeLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/RelativeLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/view/ImageView;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/ImageView;
I/HwCust  ( 6489): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/HwSystemManager( 4024): HoldService:uid:10056 pid:5665 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10056,5665
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10056, pid: 5665
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10056, pid: 5665
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10056
E/CSP_RADAR( 6513): Message execute too long time.{ when=-269ms what=1 target=com.huawei.mms.util.HwBackgroundLoader$3 }
I/HwCust  ( 6513): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
I/art     ( 6513): Can not find class: Lhuawei/android/view/ViewStub;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 6513): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6513): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6513): Can not find class: Landroid/app/ViewStub;
I/HwCust  ( 6513): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
I/HwSystemManager( 4024): ContactsObserverHelper:Receive contacts change broadcast
E/CSP_RADAR( 6513): Runnable execute too long time
I/art     ( 6513): Can not find class: Lhuawei/android/view/FrameLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/FrameLayout;
I/art     ( 6513): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 6513): initAddtionalStyle default
I/art     ( 6513): Can not find class: Lhuawei/android/view/ProgressBar;
I/art     ( 6513): Can not find class: Lhuawei/android/widget/ProgressBar;
I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6513): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/HwSystemManager( 4024): HoldService:uid:1000 pid:5687 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:1000,5687
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
W/MediaProcessHandler( 2969): processOp uid 1000 is not concerned!
I/appproc ( 6556): CLASSPATH=/system/framework/am.jar
I/appproc ( 6556): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 6556): app_process:number,5,0
I/AndroidRuntime( 6556): readDownloadBoosterConfig: 'false'
I/HwSystemManager( 4024): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 4024): NotificationManagerReceiver:onReceive, send action to background
I/HwSystemManager( 4024): ProcPolicy:begin get procName.
I/HwSystemManager( 4024): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 4024): ProcPolicy:end get procName.
I/HwSystemManager( 4024): HoldService:uid:10065 pid:5776 died
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 4024): HoldService:oldVersionKey:10065,5776
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10065, pid: 5776
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10065, pid: 5776
I/HwSystemManager( 4024): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@21a15c13
I/HwSystemManager( 4024): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
I/HwSystemManager( 4024): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
I/HwSystemManager( 4024): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
I/HwSystemManager( 4024): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
I/HwSystemManager( 4024): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
I/HwSystemManager( 4024): NmCenterDefValueXmlHelper:getConfigs: Starts
I/HwSystemManager( 4024): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
I/HwSystemManager( 4024): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
I/HwSystemManager( 4024): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 4024): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 4024): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 4024): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 4024): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 4024): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 4024): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 4024): NotificationDBProvider:query starts, matchCode = 1
I/PhoneStatusBar( 3189): notification pkg =com.android.settings
I/PhoneStatusBar( 3189): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3189): notification pkg =android
I/PhoneStatusBar( 3189): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/art     ( 2325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 429us total 28.913ms
I/HwSystemManager( 4024): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 4024): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 4024): HsmIntentService:last work complete! lets stop service.
W/asset   ( 6580): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 371us total 26.364ms
I/HwSystemManager( 6580): SystemManagerApplication:onCreate
I/HwSystemManager( 4024): MainService:on startCommand,flags:0,startId:6
I/System.out( 6580): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 6580): null
I/System.out( 6580): null
I/System.out( 6580): Calling by::className:bkk  MethodName:yw
I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 424us total 21.707ms
I/HwSystemManager( 4024): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@21a15c13
I/HwSystemManager( 4024): LocalService:Received start id 6: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
I/HwSystemManager( 4024): BgPowerManagerService:onStartCommand
I/HwSystemManager( 4024): AppLockService:onStartCommand
I/HwSystemManager( 6580): check push opration, match idx:-1
I/HwSystemManager( 4024): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 6580): HsmStat_info:feature enable:false
I/HwSystemManager( 6580): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, com.test.thalitest]
I/HwSystemManager( 6580): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 6580): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): ProcPolicy:begin get procName.
I/HwSystemManager( 6580): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 6580): ProcPolicy:end get procName.
I/HwSystemManager( 6580): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
I/YhdsEngine( 6580): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
I/HwSystemManager( 6580): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
I/HwSystemManager( 6580): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
I/HwSystemManager( 6580): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 6580): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
I/HwSystemManager( 6580): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 6580): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6580): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6580): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@54edbbf
I/HwSystemManager( 6580): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 6580): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 6580): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
I/YhdsEngine( 6580): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
I/HwSystemManager( 6580): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 6580): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 4024): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 4024): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 4024): AppCleanUpService:msg is 0
I/HwCust  ( 6580): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
I/HwSystemManager( 6580): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
I/HwSystemManager( 6580): HsmPackageManager:begin to scan apks.
I/        ( 6556): power log dlsym ok
I/YhdsEngine( 6580): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
I/HwSystemManager( 6580): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
W/HwSystemManager( 6580): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:3, queue size:0
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6580): anf:packageCanAccessInternet component enable
I/HwSystemManager( 6580): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
I/HwSystemManager( 6580): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/HwSystemManager( 6580): XmlRuleBase:parseAndCacheList black_match :[]
I/YhdsEngine( 6580): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 6580): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6580): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 6580): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
I/HwSystemManager( 6580): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6580): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
I/HwSystemManager( 6580): HsmPackageManager:end to scan apks. size:150 + 0
I/HwSystemManager( 6580): HsmPackageManager:init locale:en_US
I/HwSystemManager( 6580): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 6580): ProtectAppControl:handleMessage:6
I/HwSystemManager( 6580): ProtectAppControl:begin install app inner:com.example.hello
I/HwSystemManager( 6580): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
I/HwSystemManager( 6580): PermissionDBAdapter:DBAdapter created!
W/HwSystemManager( 6580): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
I/HwSystemManager( 6580): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
I/HwSystemManager( 6580): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6580): PermissionDBAdapter:appcationsList size:150
W/HwSystemManager( 6580): ProtectAppControl:com.example.hello already exist!
E/android_hardware_fm.cpp( 6556): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6556): ========64bit long size = 8
E/FM_HAL  ( 6556): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6556): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6556): 
I/fm_hisi ( 6556): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6556): 
I/fm_hisi ( 6556): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6556): 
E/android_hardware_fm.cpp( 6556): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2969): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2969): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2969): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2969): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3733): Launcher onPause()
I/HwLauncher( 3733): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3733): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 2969): Can not find class: Landroid/widget/ViewStub;
I/art     ( 2969): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 2969): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3733): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3733): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/art     ( 2969): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwLauncher( 3733): Launcher onStop()
I/HwSystemManager( 4024): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 4024): AppLockService:applock password not initial or function is closed
I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/HwSystemManager( 4024): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/GAV2    ( 6116): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 5974): Google Analytics 8.3.01 is starting up.
W/PGApi_client( 3607): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@2cd1d8fd actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3607): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3607): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@e019ab6, action = com.huawei.pgmng.PGAction@2cd1d8fd actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3607): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@2cd1d8fd actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3607): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3607): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3607): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3607): return for smartPAOn and mLowAudioEffectEnable both = false
I/PhoneStatusBar( 3189): shouldTranslucent:true
I/PhoneStatusBar( 3189): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/HwSystemManager( 6580): PermissionDBAdapter:DBAdapter refreshAllCachedData!
I/HwSystemManager( 6580): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6580): PermissionDBAdapter:appcationsList size:150
I/HwLauncher( 3733): Launcher dismissDialog
I/HwLauncher( 3733): Launcher dynamicIconsUnregister
I/HwLauncher( 3733): DynamicUpdater unregisterReceiver
I/HwLauncher( 3733): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3733): DynamicUpdater unregisterReceiver
I/HwLauncher( 3733): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3733): DynamicUpdater unregisterReceiver
I/HwLauncher( 3733): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3733): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3733): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3733): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3733): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3733): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwEmailTag( 6435): EmailProvider->query->1448306463439;end;;consuming:2ms;
I/HwSystemManager( 6580): PermissionDBAdapter:DBAdapter refreshAllCachedData!
I/HwSystemManager( 6580): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6580): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6580): HsmIntentService:last work complete! lets stop service.
I/HwEmailTag( 6435): EmailApplication->handleMessage->startService CleanRecipientAddressService
I/HwEmailTag( 6435): Device->updateDeviceIdIfNeeded
I/HwEmailTag( 6435): CleanRecipient->onCreate
I/HwSystemManager( 6580): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@54edbbf
I/HwEmailTag( 6435): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 6435): AccountReconciler->reconcileAccountsInternal->consuming:81ms
I/HwEmailTag( 6435): Device->getDeviceId->
I/HwEmailTag( 6435): Device->getDeviceIdInternal->isUpdate:false
I/HwEmailTag( 6435): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 6435): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 6435): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 6435): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
I/HwEmailTag( 6435): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
I/HwEmailTag( 6435): CleanRecipient->onDestroy
I/WebViewFactory( 6665): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/HwSystemManager( 4024): HoldService:uid:1050 pid:5800 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:1050,5800
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 1050
W/MediaProcessHandler( 2969): processOp uid 1050 is not concerned!
I/LibraryLoader( 6665): Loading: webviewchromium
I/LibraryLoader( 6665): Time to load native libraries: 45 ms (timestamps 8223-8268)
I/LibraryLoader( 6665): Expected native library version number "",actual native library version number ""
I/HwCust  ( 6715): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
I/HwEmailTag( 6715): EmailContent->init->consuming:15ms->;-prefixstartupperformance-
I/HwEmailTag( 6715): Exchange->onCreate
I/PG Utils( 6715): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 6665): Expected native library version number "",actual native library version number ""
I/chromium( 6665): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/PG Utils( 6715): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
I/HwEmailTag( 6435): EmailProvider->query->1448306463796;end;;consuming:2ms;
I/HwEmailTag( 6715): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
I/BrowserStartupController( 6665): Initializing chromium process, renderers=0
W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6665): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6665): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6665): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
,I/chromium( 6665): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
,I/GAv4    ( 6634): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6634):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6634):   adb logcat -s GAv4
,I/StagefrightMediaScannerEx( 3215): StagefrightMediaScanner destructor
I/StagefrightMediaScannerEx( 3215): StagefrightMediaScanner destructor
,I/HwSystemManager( 4024): HoldService:uid:10090 pid:5844 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10090,5844
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10090
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10090, pid: 5844
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10090, pid: 5844
,W/GAv4    ( 6634): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/HwSystemManager( 4024): HoldService:uid:10092 pid:5875 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10092,5875
,I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10092
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10092, pid: 5875
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10092, pid: 5875
,I/ContactsAppilcation( 6513): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,W/GAv4    ( 6634): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/CommonUtilMethods( 6513): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6513): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,W/GAv4    ( 6634): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CommonUtilMethods( 6513): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6513): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,W/AnalyticsTrackerProxyImpl( 6634): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,W/chromium( 6665): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6665): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6665): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ContextImpl( 6634): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/HwSystemManager( 6580): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6580): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6580): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6665): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 6665): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 6665): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6665): Can not find class: Landroid/app/ViewStub;
,I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 4024): HoldService:uid:10095 pid:5897 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10095,5897
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10095, pid: 5897
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10095, pid: 5897
,W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/GmsModuleInitializer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/app/GmsApplicationContext;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue;
,I/HwSystemManager( 6580): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6580): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6580): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/art     ( 5974): Can not find class: Lcom/google/android/flib/pref/PreferenceFile;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/PlatformVersion;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils$1;
,I/art     ( 5974): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 6634): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 6634): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6634): Installed default security provider GmsCore_OpenSSL
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/Asserts;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReaderImpl;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReader;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/receiver/PlaySystemBroadcastReceiver;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/UserAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/GamesSyncAdapter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/sync/BaseGmsSyncAdapter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/config/G;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesLog;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/VersionUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/GamesSharedPrefs;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$AsyncOperationQueue;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/Preconditions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/AsyncOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$OperationTask;
,I/art     ( 2969): Can not find class: Lcom/android/server/accounts/AccountManagerService$TestFeaturesSession;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService$PooledAsyncOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/WrappedGamesCallbacks;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/quests/AcceptQuestOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractDataHolderOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$Operation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/requests/AcceptRequestOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/AcceptTurnBasedMatchInvitationOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/AcknowledgeNotificationsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/AddNearbyPlayerOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractStatusReportingOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CancelTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/quests/ClaimMilestoneOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/ClearDataOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/ClearNotificationsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/events/ClearPendingEventsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/ApiClientTracker;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveContents;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/CommitSnapshotOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomEnteredCallback;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/ConnectionInfo;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/safeparcel/SafeParcelable;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/CreateRoomOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CreateTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DeclineInvitationOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/DeleteSnapshotOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DismissInvitationOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/DismissTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/DismissPlayerSuggestionOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/requests/DismissRequestOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/multiplayer/ParticipantResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/FinishTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/GetGamesAuthTokenOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/GetInboxActivityCountsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/GetScoreOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$GamesThreadFactory;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/GetTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/AccountsChangedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/PackageModifiedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/PeopleChangedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/PopupManager$PopupLocationInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/IncrementAchievementOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/events/EventIncrementEntry;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/events/IncrementEventsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/InitializeGamesOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/InvalidateAppContentOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/IsGameMutedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/JoinRoomOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/video/VideoConfiguration;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/video/LaunchGameForRecordingOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/client/IPlayGamesCallbacks;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/ClientContext;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomLeftCallback;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveDiagnostics;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FastMapJsonResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FastJsonResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/LeaveRoomOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LeaveTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/video/ListVideosOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsInternalOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AppContentContext;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/LoadAppContentOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractMultiDataHolderOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadCircledPlayersOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameCollectionComparisonOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadConnectedPlayersOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/LoadContactSettingsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsByIdOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/LoadExperimentsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadFirstPartyPlayersOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameFirstPartyOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameInstancesOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameSearchSuggestionsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGamesCollectionOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadInvitablePlayersOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/LoadInvitationsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadLeaderboardsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadMoreScoresOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpStreamOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/acls/LoadNotifyAclOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadPlayGamesRecentlyPlayedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayerOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadScoresOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/stats/LoadPlayerStatsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersInternalOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadProfileSettingsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/quests/LoadQuestsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestSummariesOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/LoadSnapshotsOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LoadTurnBasedMatchesOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpForGameCategoriesOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/NotificationOpenedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/RecordApplicationSessionOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/RecordPlayerSuggestionActionOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/RematchTurnBasedMatchOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$P2pStatusReportCallback;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/ReportP2pStatusOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/ResolveSnapshotConflictOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/UpdateAchievementOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/SearchForGamesOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/SearchForPlayersOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/requests/SendRequestOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/SetAchievementStepsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/SetGameMuteStatusOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/SetIdentitySharingConfirmedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/quests/QuestStateChangedPopupOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/SignOutOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/AndroidUtils;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$OperationAdapter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/video/StopRecordingOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/SubmitScoreOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/UpdateContactSettingsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/acls/UpdateNotifyAclOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/games/UpdatePlayedOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/players/UpdateProfileSettingsOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/UpdateTurnBasedMatchOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/IGmsCallbacks;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/GetServiceRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/ValidatePlayServiceConnectionOperation;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/ValidateServiceConnectionOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/VerifySnapshotFolderOperation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$2;
,I/OpenGLRenderer( 6665): Initialized EGL, version 1.4
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/DataBroker;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Lockable;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PeopleContactsSync( 5974): CP2 sync disabled
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/service/OperationException;
,I/Icing   ( 5974): Storage manager: low false usage 1.72MB avail 7.15GB capacity 8.84GB
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/auth/GoogleAuthException;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Lockable$LockableLock;
,I/HwSystemManager( 6580): HsmStat_info:service connect
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/GamesServer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/AbstractServer;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/auth/appcert/AppCertServiceClient;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/auth/AuthSessionAuthenticator;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/error/ErrorUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/auth/GoogleAuthUtil;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer$DefaultApiaryRetryPolicy;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$1;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$Batch;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FieldMappingDictionary;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/ApiaryRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/VolleyInterruptedError;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/NoResponseRequest;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/ImageRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/GamesRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GamesExperiments;
I/art     ( 5974): Can not find class: Lcom/google/android/play/experiments/PlayExperiments;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/Base64Utils;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/config/GamesOptions;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/error/ErrorInstanceResponse;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/error/GamesException$Builder;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/error/GamesException;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$6;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$1;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$3;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$4;
,I/art     ( 5974): Can not find class: Lcom/google/android/gsf/Gservices;
I/art     ( 5974): Can not find class: Lcom/google/android/gsf/Gservices$1;
I/art     ( 5974): Can not find class: Lcom/google/android/gsf/Gservices$1$1;
W/Icing   ( 5974): Received bad json for section weights override -- ignoring.
I/art     ( 2969): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
W/Icing   ( 5974): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 5974): Received bad json for section weights override -- ignoring.
W/Icing   ( 5974): Received bad json for corpus context scoring override -- ignoring.
,I/chromium( 6665): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6665): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 2969): Explicit concurrent mark sweep GC freed 16590(853KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.832ms total 198.945ms
,I/ActivityManager( 2969): Displayed com.example.hello/.MainActivity: +1s961ms
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExchangeAccountType@74c557 in the cache
,I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:1
,I/HwCust  ( 6513): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExternalAccountType@11855d2d in the cache
,W/ResourceType( 6513): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6513): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,W/ResourceType( 6513): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6513): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExternalAccountType@e165ff3 in the cache
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.GoogleAccountType@39b514b0 in the cache
,E/Icing   ( 5974): Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/GamesServerFactory;
,I/chromium( 6665): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6665): 
,E/ExternalAccountType( 6513): Unsupported attribute readOnly
,I/AccountTypeManager( 6513): AccountManager, account size is: 2
,I/AccountTypeManager( 6513): Loaded meta-data for 5 account types, 3 accounts in 82ms(wall) 51ms(cpu)
,W/BaseAppContext( 5974): Using Auth Proxy for data requests.
W/BaseAppContext( 5974): Using Auth Proxy for data requests.
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/server/PlusServer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/config/G;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/SpamAndAbuseHeaders;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/server/ContainerParam;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/auth/AuthTokenTimeCache;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/server/SocialClient;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 2969): Can not find class: Lcom/android/server/wm/DisplayContentList;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3799): Explicit concurrent mark sweep GC freed 9725(530KB) AllocSpace objects, 2(40KB) LOS objects, 40% free, 17MB/29MB, paused 1.098ms total 67.850ms
,W/BaseAppContext( 5974): Using Auth Proxy for data requests.
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/BaseAppContext( 5974): Using Auth Proxy for data requests.
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/BaseAppContext( 5974): Using Auth Proxy for data requests.
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryServer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/utils/Log;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/G;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$5;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/jxcore-log( 6665): Initializing JXcore engine
W/jxcore-log( 6665): JXcore engine is ready
,W/jxcore-log( 6665): Starting JXcore engine
,W/BaseAppContext( 5974): Using Auth Proxy for data requests.
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/TransientCacheOwner;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/InboxCounter;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$DataType;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/utils/GamesDataUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/DefaultClock;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/Clock;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/BaseApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApi;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AchievementCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Agents$QueryBuilder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementDefinitions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementDefinitionsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/DataHolder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/DataHolder$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Players;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayersColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$1;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementFlushData;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/ApiRateLimitUtil;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/error/ErrorResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementInstances;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementInstancesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/provider/QuerySpec;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/achievement/AchievementBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/AbstractDataBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/DataBuffer;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Releasable;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/achievement/Achievement;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/Freezable;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Agents;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$TypeQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementStepData;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$IncrementQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/ui/popup/AchievementPopup;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/ui/popup/BasePopup;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlayGamesUploadService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/GcmTaskService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinition;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FastContentValuesJsonResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievement;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/GamePlayerCacheKey;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementPendingOps;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementPendingOpsColumns;
,I/PG Utils( 6805): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$PendingOpsQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/AchievementState;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/util/AccountUtils;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/ArrayMap;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/SimpleArrayMap;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementSetStepsAtLeast;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementIncrement;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementUpdateResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementIncrementResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationFetchList;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementGetMultipleResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementSetStepsAtLeastResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUnlockResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AchievementRevealResponse;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/ContainerHelpers;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/ArrayMap$1;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/MapCollections;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/MapCollections$KeySet;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/MapCollections$ArrayIterator;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache$OwnerCache;
,I/art     ( 5974): Can not find class: Landroid/support/v4/util/LruCache;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/BaseGmsContentProvider;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/Objects;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$UriType;
,I/art     ( 5974): Can not find class: Lcom/android/common/content/ProjectionMap;
,I/art     ( 5974): Can not find class: Lcom/android/common/content/ProjectionMap$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/provider/TableJoiner;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerLevels;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerLevelColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerStats;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerStatsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ClientContexts;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ClientContextsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestPendingOps;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestPendingOpsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ApplicationSessions;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ApplicationSessionColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AppContents;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AppContentColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Images;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ImagesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardPendingScores;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Requests;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Matches;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchesPendingOps;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesPendingOpsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesDataStore;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesDatabaseHelper;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/utils/UriUtils;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$ImageCleaner;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$3;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/ImageStore;
,W/jxcore-log( 6665): Platform android
W/jxcore-log( 6665): 
W/jxcore-log( 6665): Process ARCH arm
W/jxcore-log( 6665): 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/ImageStore$Entry;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$GamesProjectionMapBuilder;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameInstances;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameInstancesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventInstances;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventInstancesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventPendingOps;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventPendingOpsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ExperienceEvents;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ExperienceEventColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Invitations;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$InvitationsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Participants;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ParticipantsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardInstances;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardInstancesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardScores;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardScoresColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Notifications;,
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$NotificationsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Milestones;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MilestoneColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestRecipients;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestRecipientsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Snapshots;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$SnapshotColumns;
,I/art     ( 5974): Can not find class: Lcom/android/common/SharedPreferencesCompat;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Games;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GamesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventDefinitions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventDefinitionColumns;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Leaderboards;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardsColumns;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/constants/OfflineMatchAction;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Quests;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$QuestsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$1;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleterAssociatedQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$2;
,I/jxcore-log( 6665): JXcore Cordova bridge is ready!
I/jxcore-log( 6665): 
,W/jxcore-log( 6665): JXcore engine is started
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AppContentsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AppContentSectionAndCardCache;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AppContentBaseCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AppContentActionCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AppContentAnnotationCache;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AppContentConditionCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/AppContentTupleCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$CardImageInsertHelper;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ContentEntry;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Section;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Card;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/CardAnnotation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ImageAsset;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/CardCondition;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/CardAction;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FastParser$ParseException;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/GamesCardScreenFirstPartyResponse;
,E/jxcore-log( 6665): >> HUAWEI-ALE-L21
E/jxcore-log( 6665): 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$ServerCookieQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/constants/DeviceType;
,I/jxcore-log( 6665): Total memory 1949741056
I/jxcore-log( 6665): 
,I/jxcore-log( 6665): Free memory 19132416
I/jxcore-log( 6665): 
I/jxcore-log( 6665): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6665): 
I/jxcore-log( 6665): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6665): 
,I/PG Utils( 6805): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/jxcore-log( 6665): userPath [ 'www' ]
I/jxcore-log( 6665): 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/EventAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/EventResolver;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventsApi;
I/jxcore-log( 6665): Size 720 1184
I/jxcore-log( 6665): 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$WindowInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodRange;
I/jxcore-log( 6665): Screen Brightness 242
I/jxcore-log( 6665): 
E/jxcore-log( 6665): Dummy Error Log.
E/jxcore-log( 6665): 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodUpdate;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$PendingOpsQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$EventDefinitionRefreshInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinition;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinitionListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$UnresolvedException;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEvent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEventListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateRequest;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventRecordRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApi;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApiInternal;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/GameCache;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/GameSearchCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/BaseSearchCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCache;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplication;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Application;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MarketApplication;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MarketBadge;
I/PG Utils( 6805): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ImageConfig;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/converter/ImageUrlBuilder;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MarketInstance;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameBadges;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameBadgesColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Instance;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/InstanceAndroidDetails;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/util/PackageUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Snapshot;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/util/PanoUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationCategory;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/GameBuffer;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/Game;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationList;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchContext;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchList;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetUpdatesMultipleFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsFlushData;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/SessionBatch;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetMultipleFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$FirstPartyGameListProcessor;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationListFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$GameRefreshRecord;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/TransientDataHolder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$VersionQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplicationUpdates;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/constants/AppUpdateType;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/ArrayUtils;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/InvalidId;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCacheKey;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$StoreGamesProcessor;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameSearchSuggestions;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameSearchSuggestionsColumns;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestion;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/DataUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationSearchFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Session;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$InstanceQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApi;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/LeaderboardScoreCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Leaderboard;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScores;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardEntry;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Player;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/LeaderboardCollection;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/TimeSpan;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PageTokensQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheKey;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheOwner;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PendingScoreQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/provider/SelectionArgs;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ScoreSubmission;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreSubmissionList;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScoreListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScore;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScoreRank;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader$Builder;
,I/UpdateIcingCorporaServi( 6322): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GamesDroidGuard;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScore;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData$Result;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/NotificationAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayCommonAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/NonListener;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/PeopleApi;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MetagameApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ExperiencesApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/PlayerCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/PlayerSearchCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/ContactSettingsCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/ProfileSettingsCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/cache/XpEventStreamCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/PlayerBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/Player;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$CircledStateQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/People;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Api;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions$HasOptions;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/ConnectionResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyPlayer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Played;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListFirstPartyResponse;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$PeopleNetworkData;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/PlayerLevel;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Experience;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PeopleFeed;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FastSafeParcelableJsonResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person$Image;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleFeed;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/model/people/Person;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/model/people/Person$Image;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$TrimExperiencesQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ProfileSettings;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleOptions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/internal/PeopleUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/Graph;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/PendingResult;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Result;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleResult;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/People$ReleasableResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Status;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/model/PersonBuffer;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/model/DataBufferWithSyncInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/people/model/Person;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/logging/GamesPlayLogger;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/data/GamesDataChangeUris;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity$ImageEntity;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/images/ImageBroker;
,I/UpdateIcingCorporaServi( 6322): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$LevelQuery;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/GamesStatusCodes;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ContactSettings;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ContactChannelSetting;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/NotificationChannel;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/CategoryListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Category;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MetagameConfig;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLevel;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceSyncFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$SyncNetworkResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AccountMetadata;
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestonesApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Quest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestone;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestCriterion;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestContribution;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/quest/QuestBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/EntityBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/quest/Quest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$QuestsEntities;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/Joiner;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/GameEventListenerRegistry;,
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/ui/popup/QuestPopup;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$SyncNetworkResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$NotifyDataHolder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$MilestoneClaimedQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestListFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataSyncFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/QuestSyncFirstPartyResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RevisionAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RevisionsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyRevisionCheckResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AclAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AclsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMember;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingRoster;
,I/art     ( 5974): Can not find class: Lcom/google/protobuf/micro/MessageMicro;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingTargetId;
,I/art     ( 5974): Can not find class: Lcom/google/protobuf/micro/InvalidProtocolBufferMicroException;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Acl;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMemberConversions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Acls;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AclsColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/AclUpdateRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestSummaryColumns;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/OutboundRequestInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestRecipient;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestEntities;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/request/GameRequestBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/request/GameRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$RequestSummariesData;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/PlayerRef;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/DataBufferRef;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/GameRef;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateList;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdate;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$SyncNetworkResponse;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestEntity;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Request;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyNotification;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/InboundRequestInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$TrimRequestsQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$PendingOpsQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/SendRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/RequestType;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestSyncResponseFirstParty;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResultList;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/service/FilesApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/Drive;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveApi;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveApi$ResourceIdSetResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/MetadataBundle;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/MetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/CustomPropertyKey;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/data/BitmapTeleporter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/Query;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveApi$MetadataBufferResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$ResultPair;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/MetadataBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Api$ClientKey;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/Api$Client;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/GmsClient;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/GmsClientEventManager$GmsClientEventState;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/LogicalFilter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/AbstractFilter;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/Filter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl$6;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/internal/DriveBaseApiMethodImpl;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ApiMethodImpl;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/internal/BasePendingResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ResultHolder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/api/internal/GoogleApiClientImpl$Runner;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/FullTextSearchDetector;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/FilterVisitor;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/Metadata;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveId;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/mdm/DeviceManager;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi$DeviceNameResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$DriveIdQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveIdResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveFile;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveResource;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveResource$MetadataResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$TitleMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/StringMetadataField;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/BaseMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableMetadataField;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/SortableMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$ModifiedMetadataField;
,I/art     ( 2969): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/DateMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/OrderedMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableOrderedMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$MimeTypeMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/internal/model/File;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/postprocessor/PostProcessorHelper;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveContentsResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation$SnapshotOpenData;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Agents$TwoColumnMapper;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/service/PlaySnapshotEventService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/chimera/DriveEventService;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/ImageUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveFolder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/internal/DriveFolderImpl;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/internal/DriveResourceImpl;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFolderResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotListResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFileResult;
I/MusicStore( 6845): Database version: 120
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/Query$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/SearchableField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableCollectionMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/InFilter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/ComparisonFilter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/Operator;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/HasFilter;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/SortOrder$Builder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$CreatedMetadataField;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/internal/FieldWithSortOrder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/drive/query/SortOrder;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/util/IOUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/StatsAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/StatsApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/StatsResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitiesApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchEntities;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyMultiplayerEntity;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/Room;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatch;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/multiplayer/InvitationBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/multiplayer/Invitation;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/multiplayer/Participatable;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/multiplayer/Participant;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$SyncNetworkResponse;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$VersionInfo;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerUtils;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitySyncFirstParty;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/NetworkDiagnostics;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent$RoomCache;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomJoinRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/Capability;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomClientAddress;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomCreateRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomAutoMatchingCriteria;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomP2PStatuses;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/RoomStatus;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApi;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApiInternal;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchResults;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/MatchParticipantResult;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent$PendingOpsQuery;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/server/response/FastParser;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchTurn;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchDataRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchCreateRequest;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedAutoMatchingCriteria;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/internal/constants/TurnBasedMatchStatus;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/multiplayer/turnbased/TurnBasedMatchBuffer;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchRematch;
,I/jxcore-log( 6665): getBuffer is called!!!!
I/jxcore-log( 6665): 
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$CaptureStateCallback;
I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$CaptureOverlayListener;
,I/PG Utils( 6845): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GamesUris;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent$MetadataQuery;
,W/ContextImpl( 6845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Agents$1;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/games/broker/Agents$2;
,I/art     ( 5974): Can not find class: Lcom/google/android/gms/common/internal/ClientContextCreator;
,I/Icing   ( 5974): updateResources: need to parse f{com.google.android.gms}
,W/ContextImpl( 6845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ContextImpl( 6845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 6845): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6845): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@89d585a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6845): Installed default security provider GmsCore_OpenSSL
,I/HwEmailTag( 6435): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 6435): EmailProvider->call->triggerPeroidSync,accountId:-1
,I/HwEmailTag( 6435): EmailProvider->triggerPeroidSync->accountId:-1
,I/ConfigStore( 6845): Config Database version: 1
,I/MediaRouter( 6845): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=6, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/HwEmailTag( 6435): EmailProvider->query->1448306466635;end;;consuming:2ms;
,I/HwEmailTag( 6435): EmailProvider->query->1448306466639;end;;consuming:1ms;
,I/PG Utils( 2969): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Icing   ( 5974): Internal init done: storage state 0
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Icing   ( 5974): Post-init done
,I/PG Utils( 6845): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GHttpClientFactory( 6845): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6845): Using platform SSLCertificateSocketFactory
,W/System.err( 2969): java.lang.SecurityException: WifiService: Neither user 10084 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2969): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2969): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2969): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2969): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2969): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2969): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2969): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6845): WifiServiceMessenger == null
,I/HwEmailTag( 6435): EmailProvider->query->1448306466765;end;;consuming:1ms;
,I/HwEmailTag( 6435): EmailProvider->query->1448306466768;end;;consuming:1ms;
,I/PG Utils( 2969): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,W/StubController( 5749): calendar access!
,I/CalendarSimpleUiPRovider( 5749): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 5749): onConfigurationChanged
,I/CalendarSimpleUiPRovider( 5749): initParams20151123T202106Europe/Warsaw(1,326,3600,0,1448306466)
I/PG Utils( 5749): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 5749): calendar access!
,W/StubController( 5749): calendar access!
,E/SQLiteLog( 6397): (284) automatic index on view_events(_id)
,W/StubController( 6397): calendar access!
,I/PG Utils( 6845): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6845): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,E/MDM     ( 3571): [100] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/PG Utils( 6845): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/MediaStoreImporter( 6845): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager( 2969): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/art     ( 2969): Can not find class: Lcom/android/server/power/Notifier$2;
,I/KeyguardFingerprint.Validation( 3121): start
,E/AuthenticationManager( 3121): AuthenticationManager open failed: the AuthenticationService is null
W/KeyguardFingerprint.Utils( 3121): AuthenticationManager open return null
I/KeyguardFingerprint.Validation( 3121): Fingerprint unlock is not enabled
I/KeyguardViewMediator( 3121): fingerprint validation not started
,W/StubController( 5749): calendar access!
,I/HwSystemManager( 4024): HoldService:uid:10087 pid:5919 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10087,5919
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10087, pid: 5919
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10087, pid: 5919
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10087
,E/WifiStateMachine( 2969):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
W/HwScreenOnProximityLock( 2969): releaseLock: return because sensor listener is held = false
E/WifiStateMachine( 2969):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine( 2969):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state InitialState suppState:UninitializedState
,E/WifiStateMachine( 2969):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine( 2969):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
,E/WifiStateMachine( 2969):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
,E/WifiStateMachine( 2969):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
,W/audio_a2dp_hw( 2585): adev_set_parameters: WARNING: set param called even when stream out is null
,E/WifiStateMachine( 2969):  InitialState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
,I/CalendarSimpleUiPRovider( 5749): loadEvent end update UI0
,E/WifiStateMachine( 2969):  DefaultState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
,E/WifiStateMachine( 2969):  InitialState !CMD_CLEAR_BLACKLIST 0 0
,E/WifiStateMachine( 2969):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
,I/art     ( 2969): Explicit concurrent mark sweep GC freed 13185(698KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 6.719ms total 216.850ms
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2969): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/GCoreFlp( 3571): No location to return for getLastLocation()
W/FusedLocationProvider( 3799): location=null
,I/TimeManager( 3189): receiver action = android.intent.action.SCREEN_ON
,I/TimeManager( 3189): hand message 2
I/TimeManager( 3189): notify time change. size = 2
,I/TimeLayout( 3189): time = 20:21
,I/TimeLayout( 3189): updateDate date = 11/23/2015
,I/TimeLayout( 3189): weekDay = Monday
,E/WifiStateMachine( 2969):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine( 2969):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 2969):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state InitialState suppState:UninitializedState
E/WifiStateMachine( 2969): setScanAlarm false period 10000 initial delay 0
E/WifiStateMachine( 2969):  InitialState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine( 2969):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine( 2969):  InitialState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine( 2969):  DefaultState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,W/audio_a2dp_hw( 2585): adev_set_parameters: WARNING: set param called even when stream out is null
,I/HwLauncher( 3733): Launcher receiver screen off broadcast sendmessage true
,I/TimeManager( 3189): receiver action = android.intent.action.SCREEN_OFF
I/TimeManager( 3189): hand message 3
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/GCoreFlp( 3571): No location to return for getLastLocation()
W/FusedLocationProvider( 3799): location=null
,I/HwSystemManager( 4024): BgPowerManagerService:MSG_SCREEN_OFF Received and mScreenOffTime :1448306467334 mScreenOffBatterylevel :2205
,I/HwSystemManager( 4024): AppLockService:BroadcastReceiver, intent is null or applock function is closed!
,I/art     ( 6085): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6085): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6085): Installed default security provider GmsCore_OpenSSL
,I/art     ( 5974): Explicit concurrent mark sweep GC freed 63857(4MB) AllocSpace objects, 60(1200KB) LOS objects, 39% free, 20MB/33MB, paused 1.357ms total 146.167ms
,I/PG Utils( 5974): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Kids    ( 5974): [KidAccountFixer] No network connection
,I/HwEmailTag( 6435): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/StubController( 5749): calendar access!
,W/StubController( 5749): calendar access!
,I/CalendarSimpleUiPRovider( 5749): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 5749): onConfigurationChanged
I/CalendarSimpleUiPRovider( 5749): initParams20151123T202107Europe/Warsaw(1,326,3600,0,1448306467)
,W/StubController( 5749): calendar access!
,I/PG Utils( 5749): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 5749): calendar access!
,I/CalendarSimpleUiPRovider( 5749): loadEvent end update UI0
,I/HwSystemManager( 4024): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4024): BgPowerManagerService: mTimes = 31956 firstTime = 30694 firstmBatteryCapacity =2205
,I/ActivityManager( 2969): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/HwLauncher( 3733): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwLauncher( 3733): Model replacing = false package = com.google.android.gms
I/HwLauncher( 3733): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.google.android.gms]
,I/HwLauncher( 3733): SimpleLauncherModeaction= android.intent.action.PACKAGE_CHANGEDpackageName = com.google.android.gms
I/HwLauncher( 3733): Model mAllAppsList.updatePackage com.google.android.gms
,I/HwSystemManager( 6580): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwSystemManager( 6580): HsmPackageManager:replacing:false
I/HwSystemManager( 6580): HsmPackageManager:pkgName:com.google.android.gms
I/HwSystemManager( 4024): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwSystemManager( 4024): HsmPackageManager:replacing:false
I/HwSystemManager( 4024): HsmPackageManager:pkgName:com.google.android.gms
,I/HwSystemManager( 4024): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
I/HwLauncher( 3733): AllIdleAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 61
I/HwSystemManager( 6580): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
,I/InputReader( 2969): Reconfiguring input devices.  changes=0x00000010,
I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExchangeAccountType@24f372ae in the cache
,I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:0,
E/RegisteredServicesCache( 3654): invalidateCache set mNeedToastTableFull
,I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:1
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExternalAccountType@92d084f in the cache,
,W/ResourceType( 2969): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,W/ResourceType( 6513): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6513): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6513): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6513): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExternalAccountType@e5204e5 in the cache
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.GoogleAccountType@4880bba in the cache
,I/HwLauncher( 3733): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3733): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = Google Settings
I/HwLauncher( 3733): Model shortcutInfo.title = Google Settings
,I/HwLauncher( 3733): SimpleLauncherModemAllAppsList.updatePackage com.google.android.gms
I/HwLauncher( 3733): Workspace updateShortcuts apps.size() 1
I/HwLauncher( 3733): Launcher.Folder childCount: 9
I/HwLauncher( 3733): Launcher.Folder childCount: 5
I/HwLauncher( 3733): Workspace updateShortcuts shortcutInfo = Google Settings
,I/HwLauncher( 3733): SimpleAllAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 0
,I/HwLauncher( 3733): Launcher.Folder childCount: 7
I/HwLauncher( 3733): Launcher.Folder childCount: 9
I/HwLauncher( 3733): Launcher.Folder childCount: 6
I/HwLauncher( 3733): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3733):  syncPages mCurrentPage = 0
,E/ExternalAccountType( 6513): Unsupported attribute readOnly
,I/AccountTypeManager( 6513): AccountManager, account size is: 2
I/HwLauncher( 3733): SimpleAllAppsList  findAndUpdateInfoInDB : found 0 shortcutInfo for package[com.google.android.gms] in db
I/HwLauncher( 3733): SimpleAllAppsList  updatePackage do not add new SimpleApplicationInfo,It's in normal now. package = com.google.android.gms
W/HwLauncher( 3733): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
,I/AccountTypeManager( 6513): Loaded meta-data for 5 account types, 3 accounts in 62ms(wall) 30ms(cpu)
,E/HideAppsPagedView( 3733):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3733):  createAddIcon count = 0
,I/HwLauncher( 3733):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3733): Launcher Deferring update until onResume
,W/asset   ( 2969): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 209us total 25.254ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 246us total 24.317ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 231us total 25.328ms
,I/YhdsEngine( 6580): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
,I/HwSystemManager( 6580): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_CHANGED, data: package:com.google.android.gms, replacing: false
,I/art     ( 2969): Can not find class: Lcom/android/server/usb/UsbSettingsManager$AccessoryFilter;
,I/HwSystemManager( 6580): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
,I/PackageBroadcastService( 5974): Null package name or gms related package.  Ignoreing.
,I/GCoreNlp( 3571): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/PG Utils( 3571): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Icing   ( 5974): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 6322): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 6322): UpdateCorporaTask done [took 29 ms] updated apps [took 29 ms] 
,I/HwSystemManager( 4024): avl:parsePowerWarningParameter result:{app_show_level=1, dangerous_current_level=30, count_frequency_fg=5, high_level_standard=10, msg_send_interval=240, dangerous_level_standard=25, min_interval_time=3, average_current_fg=350, count_frequency=60}
,I/HwSystemManager( 4024): BgPowerManagerService:MSG_SCREEN_ON Received and mScreenOmTime :1448306470212 mScreenOffTime :1448306467334mCurBatterylevel :2204mScreenOffBatterylevel :2205
,E/Thermal-daemon( 2331): [ap] temp_new :34  temp_old :33
,I/BluetoothAdapter( 6665): Start to disable Bluetooth!
,I/HwSystemManager( 4024): HoldService:checkBeforeShowDialog: uid:10302 pid:6665, permissionType:2097152
I/HwSystemManager( 4024): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2969): allowOpenWifi blocked:false
,I/jxcore-log( 6665): ****TEST TOOK:  5078  ms ****
I/jxcore-log( 6665): 
,I/jxcore-log( 6665): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6665): 
,I/appproc ( 6961): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6961): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6961): app_process:number,5,0
,I/AndroidRuntime( 6961): readDownloadBoosterConfig: 'false'
,I/        ( 6961): power log dlsym ok
,E/android_hardware_fm.cpp( 6961): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6961): ========64bit long size = 8
E/FM_HAL  ( 6961): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 6961): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6961): 
I/fm_hisi ( 6961): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6961): 
I/fm_hisi ( 6961): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6961): 
E/android_hardware_fm.cpp( 6961): register_android_hardware_fm_fmradio, ret is 0
,I/art     ( 2969): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2969): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/HwSystemManager( 4024): HoldService:uid:10302 pid:6665 died
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10302
I/HwSystemManager( 4024): HoldService:oldVersionKey:10302,6665
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10302, pid: 6665
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10302, pid: 6665
,I/ActivityManager( 2969): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2969): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/HwSystemManager( 4024): AppLockService:applock password not initial or function is closed
,I/InputReader( 2969): Reconfiguring input devices.  changes=0x00000010
I/HwLauncher( 3733): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3733): Model replacing = false package = com.example.hello
I/HwLauncher( 3733): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3733): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
,I/HwLauncher( 3733): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3733): Model mAllAppsList.removePackage com.example.hello
,I/HwLauncher( 3733): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
E/HideAppsPagedView( 3733): removeItems begin 
E/HideAppsPagedView( 3733): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3733): removeItems end 
,I/HwLauncher( 3733): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
I/HwLauncher( 3733): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3733): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3733): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3733): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3733): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,W/System.err( 3733): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3733): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3733): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3733): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3733): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3733): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3733): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3733): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3733): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3733): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwSystemManager( 4024): AppManager:getNetAppInfoFromDB cursor lenth = 1
W/System.err( 3733): java.lang.NullPointerException: null receiver
W/System.err( 3733): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3733): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3733): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3733): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3733): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3733): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3733): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3733): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3733): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3733): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3733): CellLayout rearrangeAfterRmItem isAutoAlign = false
I/HwLauncher( 3733): Launcher Deferring update until onResume
,W/GeofencerStateMachine( 3571): Ignoring removeGeofence because network location is disabled.
,I/HwSystemManager( 6580): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 6580): HsmPackageManager:replacing:false
I/HwSystemManager( 6580): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 6580): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExchangeAccountType@266ac9c8 in the cache
,I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6513): Get SIM state from SIM factory manager: 1,For slotId:1
W/System.err( 2969): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 2969): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2969): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2969): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2969): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExternalAccountType@3da30a61 in the cache
,E/RegisteredServicesCache( 3654): invalidateCache set mNeedToastTableFull
,W/ResourceType( 6513): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6513): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6513): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6513): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.ExternalAccountType@139b2986 in the cache
I/AccountTypeManager( 6513): Adding account type = com.android.contacts.model.account.GoogleAccountType@35bb247 in the cache
,E/ExternalAccountType( 6513): Unsupported attribute readOnly
,I/art     ( 6322): Explicit concurrent mark sweep GC freed 15150(1211KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 931us total 85.749ms
,I/AccountTypeManager( 6513): AccountManager, account size is: 2
,I/AccountTypeManager( 6513): Loaded meta-data for 5 account types, 3 accounts in 53ms(wall) 18ms(cpu)
,I/art     ( 4024): Explicit concurrent mark sweep GC freed 92968(6MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 14MB/23MB, paused 6.647ms total 102.687ms
,I/HwSystemManager( 4024): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 4024): HsmPackageManager:replacing:false
I/HwSystemManager( 4024): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 4024): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 4024): ww:deleteLockData:com.example.hello
,I/art     ( 2969): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 2969): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,I/art     ( 2969): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2969): Can not find class: Lcom/huawei/report/ReporterInterface;
,E/ReportTools( 2969): Can't find sReporterClazz
,I/art     ( 2969): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2969): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 2969): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2969): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2969): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2969): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2969): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2969): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2969): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2969): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2969): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2969): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2969): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2969): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2969): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2969): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2969): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2969): This is not beta user build
,I/HwLauncher( 3733): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3733): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3733): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/HwLauncher( 3733): Launcher onStart()
I/HwLauncher( 3733): Launcher dynamicIconsRegister
I/HwLauncher( 3733): DynamicUpdater registerReceiver
,I/HwLauncher( 3733): DynamicUpdater call updateFolder
I/HwLauncher( 3733): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3733): DynamicUpdater registerReceiver
,I/HwLauncher( 3733): DynamicUpdater call updateFolder
I/HwLauncher( 3733): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3733): DynamicUpdater registerReceiver
I/HwLauncher( 3733): DynamicUpdater call updateFolder
I/HwLauncher( 3733): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3733): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
,I/HwLauncher( 3733): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3733): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
E/HideAppsPagedView( 3733): removeHideApps  begin 
E/HideAppsPagedView( 3733): removeHideApps  end 
E/HideAppsPagedView( 3733):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3733):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3733):  createAddIcon count = 0
,I/HwLauncher( 3733):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3733): Launcher  onWindowVisibilityChanged visibility = 0
,I/HwLauncher( 3733): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3733): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/PhoneStatusBar( 3189): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PhoneStatusBar( 3189): shouldTranslucent:true
,I/PhoneStatusBar( 3189): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/ActivityManager( 2969): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,W/asset   ( 7007): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2969): Explicit concurrent mark sweep GC freed 36359(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 2.080ms total 294.819ms
,I/HwCust  ( 7007): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 7007): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,E/Minikin ( 6984): addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,W/GalleryUtils( 6984): the font DroidSanChineseSlim is not exist!
,I/HwLauncher( 3733): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
I/HwLauncher( 3733): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3733):  stringArray[] [unknown]
,I/HwSystemManager( 4024): HoldService:uid:10010 pid:6359 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10010,6359
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10010
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
,I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10010, pid: 6359
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10010, pid: 6359
,I/HwSystemManager( 4024): HoldService:uid:10044 pid:6634 died
I/HwSystemManager( 4024): HoldService:oldVersionKey:10044,6634
I/HwSystemManager( 4024): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 2969): onTransact in code is: 102
I/MediaProcessHandler( 2969): processOp opType: 1, uid: 10044, pid: 6634
W/MediaProcessHandler( 2969): remove target not exist, maybe the UI process: uid: 10044, pid: 6634
,I/HwSystemManager( 4024): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4024): BgPowerManagerService: mTimes = 0 firstTime = 66608 firstmBatteryCapacity =2204
,I/HwSystemManager( 4024): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 4024): NotificationManagerReceiver:onReceive, send action to background
,I/HwSystemManager( 4024): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@3788a214
,I/HwSystemManager( 4024): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 4024): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 6580): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
,E/SQLiteLog( 4024): (3850) statement aborts at 18: [DELETE FROM tbNotificationMgrCfg WHERE packageName = ?] disk I/O error - SQLITE_IOERR_LOCK
,I/HwSystemManager( 6580): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@355845d8
,I/HwSystemManager( 6580): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/HwSystemManager( 6580): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,E/SQLiteLog( 6580): (3850) statement aborts at 18: [DELETE FROM permissionCfg WHERE packageName = ?] disk I/O error - SQLITE_IOERR_LOCK
,E/HwSystemManager( 6580): HsmIntentService:invoke error, InvocationTargetException:java.lang.reflect.InvocationTargetException
I/HwSystemManager( 6580): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
,I/HwSystemManager( 6580): HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6580): HsmIntentService:last work complete! lets stop service.
E/SQLiteDatabase( 7035): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7035): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/SQLiteDatabase( 7035): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/SQLiteDatabase( 7035): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7035): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7035): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 7035): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 7035): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7035): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7035): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7035): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 7035): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7035): Process: com.android.keychain, PID: 7035
E/AndroidRuntime( 7035): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/AndroidRuntime( 7035): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/AndroidRuntime( 7035): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7035): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7035): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7035): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 7035): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 7035): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7035): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7035): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7035): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/HwSystemManager( 6580): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 6580): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 6580): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6580): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 6580): ProtectAppControl:handleMessage:7
I/HwSystemManager( 6580): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6580): HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6580): HsmIntentService:last work complete! lets stop service.
I/HwSystemManager( 6580): ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
I/art     ( 2969): Can not find class: Lcom/android/server/am/ActivityManagerService$21;
I/art     ( 2969): Can not find class: Lcom/android/server/am/AppErrorResult;
I/HwSystemManager( 4024): OptimizeProvider:delete com.example.hello
E/SQLiteLog( 4024): (3850) statement aborts at 18: [DELETE FROM protectedapps WHERE package_name = ?] disk I/O error - SQLITE_IOERR_LOCK
E/DatabaseUtils( 4024): Writing exception to parcel
E/DatabaseUtils( 4024): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/DatabaseUtils( 4024): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DatabaseUtils( 4024): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DatabaseUtils( 4024): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DatabaseUtils( 4024): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DatabaseUtils( 4024): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/DatabaseUtils( 4024): 	at com.huawei.systemmanager.optimize.db.OptimizeProvider.delete(Unknown Source)
E/DatabaseUtils( 4024): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/DatabaseUtils( 4024): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
E/DatabaseUtils( 4024): 	at android.os.Binder.execTransact(Binder.java:446)
E/HwSystemManager( 4024): NotificationDBProvider:delete exception
E/HwSystemManager( 4024): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.db.DBProvider.delete(Unknown Source)
E/HwSystemManager( 4024): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/HwSystemManager( 4024): 	at android.content.ContentResolver.delete(ContentResolver.java:1333)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.db.DBAdapter.at(Unknown Source)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.receiver.Receiver.k(Unknown Source)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.receiver.Receiver.doInBackground(Unknown Source)
E/HwSystemManager( 4024): 	at java.lang.reflect.Method.invoke(Native Method)
E/HwSystemManager( 4024): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/HwSystemManager( 4024): 	at bli.b(Unknown Source)
E/HwSystemManager( 4024): 	at bli.a(Unknown Source)
E/HwSystemManager( 4024): 	at bli.run(Unknown Source)
E/HwSystemManager( 4024): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HwSystemManager( 4024): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HwSystemManager( 4024): 	at java.lang.Thread.run(Thread.java:831)
I/HwSystemManager( 4024): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 4024): AppCleanUpService:onStartCommand() out!
W/System.err( 2969): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
E/SQLiteLog( 4024): (3850) statement aborts at 16: [DELETE FROM tbNotificationMgrLog WHERE packageName = ?] disk I/O error - SQLITE_IOERR_LOCK
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2969): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2969): 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1425)
W/System.err( 2969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2969): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2969): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/ReportTools( 2969): This is not beta user build
I/Process ( 7035): Sending signal. PID: 7035 SIG: 9
E/HwSystemManager( 4024): NotificationDBProvider:delete exception
E/HwSystemManager( 4024): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/HwSystemManager( 4024): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.db.DBProvider.delete(Unknown Source)
E/HwSystemManager( 4024): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/HwSystemManager( 4024): 	at android.content.ContentResolver.delete(ContentResolver.java:1333)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.db.DBAdapter.au(Unknown Source)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.receiver.Receiver.k(Unknown Source)
E/HwSystemManager( 4024): 	at com.huawei.notificationmanager.receiver.Receiver.doInBackground(Unknown Source)
E/HwSystemManager( 4024): 	at java.lang.reflect.Method.invoke(Native Method)
E/HwSystemManager( 4024): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/HwSystemManager( 4024): 	at bli.b(Unknown Source)
E/HwSystemManager( 4024): 	at bli.a(Unknown Source)
E/HwSystemManager( 4024): 	at bli.run(Unknown Source)
E/HwSystemManager( 4024): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HwSystemManager( 4024): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HwSystemManager( 4024): 	at java.lang.Thread.run(Thread.java:831)
E/HwSystemManager( 4024): AppCleanUpService:msg is 1
I/HwSystemManager( 4024): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 4024): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 4024): HsmIntentService:last work complete! lets stop service.
E/SQLiteLog( 4024): (3850) statement aborts at 16: [DELETE FROM rarelyusedapps WHERE PACKAGE_NAME=?] disk I/O error - SQLITE_IOERR_LOCK
E/AndroidRuntime( 4024): FATAL EXCEPTION: main
E/AndroidRuntime( 4024): Process: com.huawei.systemmanager:service, PID: 4024
E/AndroidRuntime( 4024): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/AndroidRuntime( 4024): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4024): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4024): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4024): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4024): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1533)
E/AndroidRuntime( 4024): 	at com.huawei.systemmanager.spaceclean.rarelyusedapp.RarelyUsedAppProvider.delete(Unknown Source)
E/AndroidRuntime( 4024): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 4024): 	at android.content.ContentResolver.delete(ContentResolver.java:1333)
E/AndroidRuntime( 4024): 	at bfv.ba(Unknown Source)
E/AndroidRuntime( 4024): 	at bfw.handleMessage(Unknown Source)
E/AndroidRuntime( 4024): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4024): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4024): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
E/AndroidRuntime( 4024): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4024): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4024): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
E/AndroidRuntime( 4024): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwSystemManager( 6580): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
I/HwSystemManager( 6580): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
W/HwSystemManager( 6580): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6580): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6580): HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6580): HsmIntentService:last work complete! lets stop service.
I/HwSystemManager( 6580): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
I/HwSystemManager( 6580): NetAppListPrepareReceiver:package removed: package:com.example.hello
I/HwSystemManager( 6580): NetAppListPrepareReceiver:replacing?:false
W/System.err( 2969): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2969): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2969): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2969): 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1425)
W/System.err( 2969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2969): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2969): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/ReportTools( 2969): This is not beta user build
I/Process ( 4024): Sending signal. PID: 4024 SIG: 9
E/AndroidRuntime( 6580): FATAL EXCEPTION: handler_thread
E/AndroidRuntime( 6580): Process: com.huawei.systemmanager, PID: 6580
,E/AndroidRuntime( 6580): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/AndroidRuntime( 6580): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 6580): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 6580): 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
E/AndroidRuntime( 6580): 	at android.content.ContentResolver.delete(ContentResolver.java:1333)
E/AndroidRuntime( 6580): 	at arc.o(Unknown Source)
E/AndroidRuntime( 6580): 	at ard.aA(Unknown Source)
E/AndroidRuntime( 6580): 	at aso.cO(Unknown Source)
E/AndroidRuntime( 6580): 	at aso.b(Unknown Source)
E/AndroidRuntime( 6580): 	at asp.handleMessage(Unknown Source)
E/AndroidRuntime( 6580): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6580): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6580): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/art     ( 2969): Can not find class: Lcom/android/server/am/ActivityManagerService$BadProcessInfo;
,E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!,
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 2969): !!! FAILED BINDER TRANSACTION !!!
,I/ServiceManager( 2293): service 'com.huawei.netassistant.service.netassistantservice' died
I/ServiceManager( 2293): service 'com.huawei.systemmanager.rainbow.service' died
I/ServiceManager( 2293): service 'HsmStat' died
I/ServiceManager( 2293): service 'com.huawei.systemmanager.netassistant.netpolicy.NatNetworkPolicyService' died
I/ServiceManager( 2293): service 'com.huawei.systemmanager.netassistant.netnotify.policy.NatTrafficNotifyService' died
I/ServiceManager( 2293): service 'com.huawei.netassistant.binder.notificationcallbackbinder' died
I/ServiceManager( 2293): service 'com.huawei.systemmanager.preventmode.PreventModeService' died
I/ServiceManager( 2293): service 'com.huawei.permissionmanager.service.holdservice' died
I/ServiceManager( 2293): service 'com.huawei.harassmentinterception.service.HarassmentInterceptionService' died

```
