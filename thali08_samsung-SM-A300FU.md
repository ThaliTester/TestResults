#### Test 6165819876c87fb_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/SBrowserFeatureFlag( 4109): initialized in static block : loadCscFeatureValue() succeed! 
E/        ( 3820): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3820): took 1.020050ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3820): Bitmap=0xb8793200 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb87932a8 counterpartCT=4 counterpartW=80 counterparth=80
I/AMMetaDataParserService( 3820): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
D/ManifestProvider( 4109): onCreate()
,--------- beginning of system
D/SSRM:n  ( 1020): SIOP:: AP = 410
I/ActivityManager( 1020): Killing 3441:com.sec.factory.camera/1000 (adj 15): empty #31
E/        ( 3820): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3820): took 0.639948ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3820): Bitmap=0xb87932a8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb893f5f8 counterpartCT=4 counterpartW=80 counterparth=80
I/AMMetaDataParserService( 3820): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
E/NetworkSettingsReceiver( 4109): onReceive: android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 1836): Explicit concurrent mark sweep GC freed 24913(1880KB) AllocSpace objects, 39(624KB) LOS objects, 39% free, 9MB/15MB, paused 1.277ms total 98.544ms
E/        ( 3820): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3820): took 0.661875ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3820): Bitmap=0xb87932a8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb893daa8 counterpartCT=4 counterpartW=80 counterparth=80
I/AMMetaDataParserService( 3820): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
I/GCoreUlr( 1836): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1836): Unbound from all location providers
I/GCoreUlr( 1836): Place inference reporting - stopped
W/System.err( 4109): java.lang.NoSuchMethodException: isEnabled []
W/System.err( 4109): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4109): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4109): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4109): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4109): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4109): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4109): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4109): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4109): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4109): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4109): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4109): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4109): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4109): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4109): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4109): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4109): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
E/SBrowserFeatureFlag( 4109): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@27412a3f
D/SBrowserFeatureFlag( 4109): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4109): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3441/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
E/Zygote  ( 4146): MountEmulatedStorage()
E/Zygote  ( 4146): v2
I/libpersona( 4146): KNOX_SDCARD checking this for 10131
I/SELinux ( 4146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4146): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/SELinux ( 4146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4146 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3460:com.fmm.ds/1000 (adj 15): empty #31
E/SELinux ( 4146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 4081): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1836): DispatchingService.onDestroy()
I/GCoreUlr( 1836): Stopping handler for UlrDispSvcFast
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
D/TimaKeyStoreProvider( 4146): TimaSignature is unavailable
I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
D/ActivityThread( 4146): Added TimaKeyStore provider
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 4081): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/ResourcesManager( 4146): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 4162): MountEmulatedStorage()
I/libpersona( 4162): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4162): v2
I/libpersona( 4162): KNOX_SDCARD not a persona
I/SELinux ( 4162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
I/SELinux ( 4162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4162): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 3820): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4162 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 3820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3820): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 3820): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
W/ResourcesManager( 3820): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 4081): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/ActivityManager( 1020): Killing 3485:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
I/GCoreUlr( 1836): Unbound from all location providers
I/GCoreUlr( 1836): Place inference reporting - stopped
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
W/GCoreFlp( 1836): No location to return for getLastLocation()
W/FusedLocationProvider( 1836): location=null
W/Auth    ( 1836): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
D/TimaKeyStoreProvider( 4162): TimaSignature is unavailable
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
D/ActivityThread( 4162): Added TimaKeyStore provider
V/GLSActivity( 1836): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1836): No location to return for getLastLocation()
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
W/FusedLocationProvider( 1836): location=null
D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3460/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10095/pid_3485/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3820): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 4081): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 4081): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 4081): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/AMMetaDataParserService( 3820): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 4081): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 4081): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 4081): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 4081): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 4081): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
D/PersistentNotificationBroadcastReceiver( 1836): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/DBG_POLICYDM( 4081): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 4081): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/06/11:32:20
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/DBG_POLICYDM( 4081): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/05/02:37:13
I/DBG_POLICYDM( 4081): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
I/ActivityManager( 1020): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4187 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/Zygote  ( 4187): MountEmulatedStorage()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4187): v2
I/libpersona( 4187): KNOX_SDCARD checking this for 10037
I/libpersona( 4187): KNOX_SDCARD not a persona
I/SELinux ( 4187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4187): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/Zygote  ( 4197): MountEmulatedStorage()
I/libpersona( 4197): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4197): v2
I/libpersona( 4197): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 4081): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/SELinux ( 4197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4197 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 4197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 4197): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4187): TimaSignature is unavailable
D/ActivityThread( 4187): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 4197): TimaSignature is unavailable
D/ActivityThread( 4197): Added TimaKeyStore provider
W/ResourcesManager( 4187): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SMD     (  294): DCD OFF
W/ResourcesManager( 4197): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4197): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4197): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4197): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4197): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4221): MountEmulatedStorage()
E/Zygote  ( 4221): v2
I/libpersona( 4221): KNOX_SDCARD checking this for 10026
I/libpersona( 4221): KNOX_SDCARD not a persona
I/SELinux ( 4221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4221): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4221 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 4141): 
D/AndroidRuntime( 4141): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4141): CheckJNI is OFF
D/AndroidRuntime( 4141): readGMSProperty: start
D/AndroidRuntime( 4141): readGMSProperty: already setted!!
D/AndroidRuntime( 4141): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4141): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4141): readGMSProperty: end
D/AndroidRuntime( 4141): addProductProperty: start
E/SPPClientService( 4162): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4162): [PushClientApplication] Push log off : This is Ship build version
I/Icing   ( 2127): Internal init done: storage state 0
I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
E/SPPClientService( 4162): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
I/AMMetaDataParserService( 3820): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
I/DBG_POLICYDM( 4081): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
I/Icing   ( 2127): Post-init done
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SPPClientService( 4162): PushLog.txt file is not deleted.
D/SPPClientService( 4162): PushLog.txt file is not deleted.
D/SPPClientService( 4162): ============PushLog. stop!
D/TimaKeyStoreProvider( 4221): TimaSignature is unavailable
D/ActivityThread( 4221): Added TimaKeyStore provider
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
I/AMMetaDataParserService( 3820): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
I/CalendarProvider2( 4187): CalendarProvider2.onCreate() called
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
I/AMMetaDataParserService( 3820): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
E/Zygote  ( 4248): MountEmulatedStorage()
E/Zygote  ( 4248): v2
I/libpersona( 4248): KNOX_SDCARD checking this for 10036
I/libpersona( 4248): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3820): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
I/SELinux ( 4248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4248 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4248): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 3507:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4081): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/GAV2    ( 3531): Thread[GAThread,5,main]: No campaign data found.
D/TimaKeyStoreProvider( 4248): TimaSignature is unavailable
D/ActivityThread( 4248): Added TimaKeyStore provider
V/AlarmManager( 1020): waitForAlarm result :8
I/ActivityManager( 1020): Killing 3550:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4266): MountEmulatedStorage()
I/libpersona( 4266): KNOX_SDCARD checking this for 10141
E/Zygote  ( 4266): v2
I/libpersona( 4266): KNOX_SDCARD not a persona
I/SELinux ( 4266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4266 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4266): TimaSignature is unavailable
D/ActivityThread( 4266): Added TimaKeyStore provider
W/ResourcesManager( 4266): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4266): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4266): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4266): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/libprocessgroup( 1020): failed to open /acct/uid_10098/pid_3507/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10055/pid_3550/cgroup.procs: No such file or directory
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
E/Zygote  ( 4294): MountEmulatedStorage()
I/libpersona( 4294): KNOX_SDCARD checking this for 10068
E/Zygote  ( 4294): v2
I/libpersona( 4294): KNOX_SDCARD not a persona
I/SELinux ( 4294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4294): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4294 uid=10068 gids={50068, 9997} abi=armeabi-v7a
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
I/SA      ( 4248): [SSP] onCreated
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4294): TimaSignature is unavailable
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4294): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/Zygote  ( 4313): MountEmulatedStorage()
I/libpersona( 4313): KNOX_SDCARD checking this for 10142
E/Zygote  ( 4313): v2
I/libpersona( 4313): KNOX_SDCARD not a persona
I/SELinux ( 4313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4313 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 3273:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
D/TimaKeyStoreProvider( 4313): TimaSignature is unavailable
D/ActivityThread( 4313): Added TimaKeyStore provider
W/ResourcesManager( 4313): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/BadgeProvider( 4294): onCreate
D/BadgeProvider( 4294): DatabaseHelper
D/BadgeProvider( 4294): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/libprocessgroup( 1020): failed to open /acct/uid_10008/pid_3273/cgroup.procs: No such file or directory
D/Launcher.Model( 1513): reloadBadges entered.
D/BadgeProvider( 4294): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4294): sendNotify, [notify] : null
D/BadgeProvider( 4294): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4294): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4294): update, [UpdateCount] : 1
W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1020): getTasks: caller 10141 does not hold GET_TASKS; limiting output
E/AffinityControl( 4141): AffinityControl: registerfunction enter
I/Process ( 4266): Sending signal. PID: 4266 SIG: 9
D/AndroidRuntime( 4141): Calling main entry com.android.commands.am.Am
I/SA      ( 4248): [TPM] There is no property file
I/SA      ( 4248): [SCU] isHaveSA() - false
I/SA      ( 4248): [TPM] getModelProperty : null
I/SA      ( 4248): [TPM] getCSCProperty : null
D/Finsky  ( 4221): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/SA      ( 4248): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4248): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4248): [DM] TFT FEATURE: false
I/SA      ( 4248): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4248): [DM] init START
I/SA      ( 4248): [DM] This device is not a Vodafone
I/ActivityManager( 1020): Process com.android.email (pid 4266)(adj 9) has died(33,627)
W/ResourceType( 4248): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 4248): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 4248): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4248): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 4248): [SCU] isHaveSA() - false
I/SA      ( 4248): support phone number id : false
I/SA      ( 4248): [DM] Supports Ref Jpn : true
I/SA      ( 4248): [DM] init END
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
I/SA      ( 4248): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4248): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
I/SA      ( 4248): [OR] onReceive END
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SA      ( 4248): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4248): [ODM] queryOpenData(key= GEO_IP )
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1020): mDVFSHelper.acquire()
I/SA      ( 4248): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4248): [LBE] REF_JPN : true
I/SA      ( 4248): [BDC] create
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/Launcher.HomeView( 1513): onPause
I/SA      ( 4248): [DBMV2] getEmailID
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1513
D/AndroidRuntime( 4141): Shutting down VM
I/SA      ( 4248): [DBMV2] getDataV02ForItems
I/SA      ( 4248): [SSP] query invoked
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
D/Launcher( 1513): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/SA      ( 4248): [SCU] get signed id from samsung account2.0 DB.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/SA      ( 4248): [SCU] get signed id from samsung account1.0 DB.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4344): MountEmulatedStorage()
E/Zygote  ( 4344): v2
I/libpersona( 4344): KNOX_SDCARD checking this for 1000
I/SELinux ( 4344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4344): KNOX_SDCARD not a persona
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
I/ActivityManager( 1020): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4344 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/PhoneWindow( 1020): *FMB* installDecor flags : -2122120936
I/SELinux ( 4344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4344): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  260): id=10 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 4344): TimaSignature is unavailable
D/ActivityThread( 4344): Added TimaKeyStore provider
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4367): MountEmulatedStorage()
E/Zygote  ( 4367): v2
I/libpersona( 4367): KNOX_SDCARD checking this for 10167
I/libpersona( 4367): KNOX_SDCARD not a persona
I/SELinux ( 4367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4367 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4367): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3820): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4367): TimaSignature is unavailable
D/ActivityThread( 4367): Added TimaKeyStore provider
I/AMMetaDataParserService( 3820): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
V/ActivityThread( 1513): updateVisibility : ActivityRecord{3f3d6621 token=android.os.BinderProxy@29936a9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Finsky  ( 4221): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/art     (  315): Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 53.667ms
I/AMMetaDataParserService( 3820): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
I/AMMetaDataParserService( 3820): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.704ms
I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
W/Settings( 4221): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4221): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.691ms
E/Zygote  ( 4387): MountEmulatedStorage()
E/Zygote  ( 4387): v2
I/libpersona( 4387): KNOX_SDCARD checking this for 10141
I/libpersona( 4387): KNOX_SDCARD not a persona
I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
I/SELinux ( 4387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4387 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 4387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SA      ( 4248): [BDC] destroy
W/art     ( 4141): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/TimaKeyStoreProvider( 4387): TimaSignature is unavailable
D/ActivityThread( 4387): Added TimaKeyStore provider
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher.HomeView( 1513): onStop
,V/ActivityThread( 1513): updateVisibility : ActivityRecord{3f3d6621 token=android.os.BinderProxy@29936a9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3820): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3820): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1020): Killing 3566:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,D/Launcher( 1513): onTrimMemory. Level: 20
,I/ActivityManager( 1020): Killing 3581:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,I/AMMetaDataParserService( 3820): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/SensorService( 1020): [SO] activate (ident=0xb86c5bd8, enabled=0)
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1020): unregisterListener ::   
,I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1020): [SO] changed settle time [1]
,D/SensorService( 1020): [SO] setDelay [66000000]
D/SensorService( 1020): [SO] activate (ident=0xb86c5bd8, enabled=1)
,D/SensorService( 1020): [SO] AR_init
,I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,W/ResourcesManager( 4387): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4387): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4387): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4387): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/ActivityManager( 1020): Killing 3641:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 3624:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #32
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Volley  ( 4221): [648] DiskBasedCache.clear: Cache cleared.
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,D/Volley  ( 4221): [641] DiskBasedCache.clear: Cache cleared.,
,E/Zygote  ( 4404): MountEmulatedStorage(),
I/libpersona( 4404): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4404): v2
,I/libpersona( 4404): KNOX_SDCARD not a persona
I/SELinux ( 4404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4404 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1020): Killing 3657:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/SELinux ( 4404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4404): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_10013/pid_3566/cgroup.procs: No such file or directory
,V/AlarmManager( 1020): waitForAlarm result :4
,I/AMMetaDataParserService( 3820): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/SensorService( 1020): [SO] -0.383 0.172 9.902
,D/SensorService( 1020): [SO] [100 -> 255]
,D/TimaKeyStoreProvider( 4404): TimaSignature is unavailable
,D/ActivityThread( 4404): Added TimaKeyStore provider
,D/Finsky  ( 4221): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4221): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4221): Skipping gmscore version check
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 30876(1642KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/34MB, paused 5.716ms total 272.910ms
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
,I/AMMetaDataParserService( 3820): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
I/WebViewFactory( 4367): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
I/AMMetaDataParserService( 3820): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3820): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3820): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/LibraryLoader( 4367): Loading: webviewchromium
,W/libprocessgroup( 1020): failed to open /acct/uid_10056/pid_3581/cgroup.procs: No such file or directory
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/SecurityLogAgent( 4404): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4404): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4404): StateMachine : Current State = 1
D/SecurityLogAgent( 4404): BootReceiver : completed task. Failed to return wakelock . 
D/Finsky  ( 4221): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4432): MountEmulatedStorage()
,E/Zygote  ( 4432): v2
I/libpersona( 4432): KNOX_SDCARD checking this for 10148
I/libpersona( 4432): KNOX_SDCARD not a persona
,I/SELinux ( 4432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4432 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,W/libprocessgroup( 1020): failed to open /acct/uid_10020/pid_3641/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10058/pid_3624/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3657/cgroup.procs: No such file or directory
E/SELinux ( 4432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4432): TimaSignature is unavailable
,D/ActivityThread( 4432): Added TimaKeyStore provider
,I/LibraryLoader( 4367): Time to load native libraries: 99 ms (timestamps 4792-4891)
,I/LibraryLoader( 4367): Expected native library version number "",actual native library version number ""
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3820): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SurfaceFlinger(  260): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  260): id=9 Removed Mauncher (-2/8)
,V/WebViewChromiumFactoryProvider( 4367): Binding Chromium to main looper Looper (main, tid 1) {1e266b12}
,I/LibraryLoader( 4367): Expected native library version number "",actual native library version number ""
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
,I/AMMetaDataParserService( 3820): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,I/chromium( 4367): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/BrowserStartupController( 4367): Initializing chromium process, renderers=0
,D/BadgeProvider( 4294): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1020): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/AMMetaDataParserService( 3820): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/art     ( 4367): Attempt to remove local handle scope entry from IRT, ignoring
,E/SQLiteLog( 4432): (284) automatic index on shooting_modes(title_id)
,D/Finsky  ( 4221): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1020): Killing 3676:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/Launcher.Model( 1513): reloadBadges entered.
,I/Process ( 4313): Sending signal. PID: 4313 SIG: 9
,D/BadgeProvider( 4294): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4294): sendNotify, [notify] : null
D/BadgeProvider( 4294): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4294): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4294): update, [UpdateCount] : 1
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3820): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4460): MountEmulatedStorage()
E/Zygote  ( 4460): v2
I/libpersona( 4460): KNOX_SDCARD checking this for 1000
I/libpersona( 4460): KNOX_SDCARD not a persona
,I/SELinux ( 4460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4460 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3820): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{4256584 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/ActivityManager( 1020): Killing 3350:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3676/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4460): TimaSignature is unavailable
,D/ActivityThread( 4460): Added TimaKeyStore provider
,W/chromium( 4367): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/ActivityManager( 1020): Killing 3691:com.wssnps/1000 (adj 15): empty #31
,I/chromium( 4367): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 4367): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3820): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/splitIntent( 1020): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1020): Killing 3710:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
,D/SecurityLogAgent( 4404):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 4404):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,I/AMMetaDataParserService( 3820): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,I/ActivityManager( 1020): Process com.android.exchange (pid 4313)(adj 15) has died(27,642)
,D/SecurityLogAgent( 4404):  SeDenialReceiver : Start file Zipping Service 
,I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/Adreno-EGL( 4367): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4367): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4367): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4367): Local Branch: 
I/Adreno-EGL( 4367): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4367): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4367):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/ContextImpl( 4404): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,I/AMMetaDataParserService( 3820): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SecurityLogAgent( 4404): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 4404): FileZippingService : file path =  /data/misc/audit/audit.old
,D/SecurityLogAgent( 4404): FileZippingService : onPremise disabled. Zipping..  
,D/SecurityLogAgent( 4404): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 4404): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 4404): DenialLogFileZipCreator : Files exceeded the max limit 
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_3350/cgroup.procs: No such file or directory
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3820): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SecurityLogAgent( 4404): DenialLogFileZipCreator File existence : true audit.old file size 1333
D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/SecurityLogAgent( 4404): DenialLogFileZipCreator : denied strings found . Starts zipping . 
D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1827): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/SecurityLogAgent( 4404): ProcessFileZipCreator : File name = denialLog
D/comsamsunglog( 1827): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 1827): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:false, UtilgetIsDay():false
,D/SecurityLogAgent( 4404): ProcessFileZipCreator : Created temp file 
,D/SecurityLogAgent( 4404): ProcessFileZipCreator br.readline() has read  12 lines. 
,D/SecurityLogAgent( 4404): ProcessFileZipCreator denialxxx.txt file file existence : true size after copying : 0
,D/SecurityLogAgent( 4404): ProcessFileZipCreator : Source = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog241742858.txt
,D/SecurityLogAgent( 4404): ProcessFileZipCreator : Destination = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog241742858.txt.zip
,D/SecurityLogAgent( 4404): ProcessFileZipCreator : File compressed.
D/SecurityLogAgent( 4404): ProcessFileZipCreatordenialLog241742858.txt has been deleted after compression. 
,D/SecurityLogAgent( 4404): FileCipher : getKey Called 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/SecureStorage( 4404): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/Hs20UtilService( 1734): Starting #6
,I/Hs20UtilService( 1734): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1734): Starting #7
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1734): Message received 5007
,D/WifiStateMachine( 1020): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SecureStorage( 4404): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  405): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 4404
I/SecureStorage(  405): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 4404): [INFO]: SPID(0x00000000)SS Daemon is running
D/SecurityLogAgent( 4404): FileCipher : Secure Storage Supported 
,I/SecureStorage( 4404): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  405): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 4404
I/SecureStorage(  405): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1020): mCursor = null
D/SecContentProvider2( 1020): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1020): mCursor = null
D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1020): mCursor = null
D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1020): mCursor = null
D/SecContentProvider2( 1020): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1020): mCursor = null
I/AMMetaDataParserService( 3820): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1827): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3820): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/chromium( 4367): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 4367): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3820): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/SurfaceFlinger(  260): id=11 createSurf (1x1),1 flag=4, Uoast
D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131165197
D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1827): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1827): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 1827): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 1827): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:false, UtilgetIsDay():false
W/ResourcesManager( 3820): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3820): getResourceName:com.sec.android.gallery3d:xml/assistant
W/ResourcesManager( 3820): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
W/ResourcesManager( 3820): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/PowerManagerService( 1020): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
W/art     ( 4367): Attempt to remove local handle scope entry from IRT, ignoring
D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
W/AwContents( 4367): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 4367): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4367): *FMB* installDecor flags : -2139027200
,I/AMMetaDataParserService( 3820): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/SystemWebViewEngine( 4367): CordovaWebView is running on device made by: samsung
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/AMMetaDataParserService( 3820): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/art     ( 4367): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4367): Attempt to remove local handle scope entry from IRT, ignoring
,D/SIP     ( 1487): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,D/accuweather( 1766): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,E/File    ( 1487): fail readDirectory() errno=2
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,I/AMMetaDataParserService( 3820): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3691/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3710/cgroup.procs: No such file or directory
,D/accuweather( 1766): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1766): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1766): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1766): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1766): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1766): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1766): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131165197
,I/AMMetaDataParserService( 3820): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,D/OpenGLRenderer( 4367): Render dirty regions requested: true,
D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,D/PhoneWindow( 4367): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4367): *FMB* isFloatingMenuEnabled return false
,D/accuweather( 1766): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1766): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,I/AMMetaDataParserService( 3820): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/accuweather( 1766): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1766): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
D/accuweather( 1766): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1766): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 02 37
,E/accuweather( 1766): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,I/AMMetaDataParserService( 3820): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/SurfaceFlinger(  260): id=12 createSurf (1x1),1 flag=404, NainActivit
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/InputDispatcher( 1020): Focus entered window: 4367
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4367): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4367): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4367): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4367): Enabling debug mode 0
,I/CalendarProvider2( 4187): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1448): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1448): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/accuweather( 1766): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1766): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1766): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,V/HeadsetService( 2618): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/accuweather( 1766): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/HeadsetStateMachine( 2618): Disconnected process message: 10
D/accuweather( 1766): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1766): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +1s517ms
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{157f8aba u0 com.test.thalitest/.MainActivity t11} time:45755
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/PanelView( 1178): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 4367): Timeline: Activity_idle id: android.os.BinderProxy@26391509 time:45777
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1766): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1766): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1766): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1766): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3820): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131165197
,I/AMMetaDataParserService( 3820): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1887): getCurrentCandidateView
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3820): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3820): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/WearableService( 1836): callingUid 10011, callindPid: 1836
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2127): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  260): id=10 Removed uhalitest (7/9)
,I/SurfaceFlinger(  260): id=10 Removed uhalitest (-2/9)
,E/MDM     ( 1836): [237] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3820): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3820): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.wallpaper.preview
,W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
,I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131099648
,E/SMD     (  294): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1487): query,matched:0, calling pid = 2127
,D/TP/SmsProvider( 1487): match 0:Elapsed time : 2.396 ms
,I/SecureStorage(  405): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/TP/MmsProvider( 1487): Query uri=content://mms, match=0, calling pid = 2127
,W/ResourcesManager( 3820): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3820): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,D/TP/SmsProvider( 1487): query,matched:0, calling pid = 2127
,D/TP/SmsProvider( 1487): match 0:Elapsed time : 2.108 ms
,D/TP/MmsProvider( 1487): Query uri=content://mms, match=0, calling pid = 2127
,D/JsMessageQueue( 4367): Set native->JS mode to OnlineEventsBridgeMode
,I/SecureStorage( 4404): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 4404): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 4404): FileCipher : Got the key bytes 
D/SecurityLogAgent( 4404): FileCipher : Saving Key to SecureStorage.  
I/SecureStorage( 4404): [INFO]: SPID(0x00000002)Processing data
,I/SecureStorage(  405): [INFO]: SPID(0x00000002)Credentials: uid 1000, gid 1000, pid 4404
I/SecureStorage(  405): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000104
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/AMMetaDataParserService( 3820): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/SamsungIME( 1887): Dismiss ExpandCandiate
,I/DBG_POLICYDM( 4081): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,W/IcingInternalCorpora( 2127): getNumBytesRead when not calculated.
,I/AMMetaDataParserService( 3820): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/SamsungIME( 1887): getDebugLevel  : 0x4f4c
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,D/PowerManagerService( 1020): [s] UserActivityState : 1 -> 2
,I/chromium( 4367): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4367): 
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:assistant
I/AMMetaDataParserService( 3820): Resource data:2131165220
,W/ResourcesManager( 3820): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 3820): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3820): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3820): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3820): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3820): getResourceName:com.android.settings:xml/assistant
,I/SamsungIME( 1887): getDebugLevel  : 0x4f4c
,I/AMMetaDataParserService( 3820): getResourceTypeNamexml
,I/AMMetaDataParserService( 3820): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,I/AMMetaDataParserService( 3820): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/SamsungIME( 1887): KeybaordView init() : load resources
,I/SamsungIME( 1887): getCurrentKeyboard
,I/SamsungIME( 1887): getTextKeyboard
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1836): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.andr,oid.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataP,arserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
W/ContextImpl( 3820): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
D/SamsungIME( 1887): [SwiftkeyWrapper] currentLangauge : 1701729619
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
,I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParser,Service( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3820): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3820): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3820): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/a       ( 1836): Opening database auth.proximity.permit_store...
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1836): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/GCoreFlp( 1836): No location to return for getLastLocation()
W/FusedLocationProvider( 1836): location=null
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,W/SecureStorage(  405): [WARN]: SPID(0x00000003)Trying update data block to DB
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1827): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/jxcore_app_log( 4367): JniHelper::setJavaVM(0xb8069448), pthread_self() = -1200591104
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1827): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1827): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
I/SecureStorage(  405): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
D/daemonapp( 1827): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1827): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/art     ( 1650): Explicit concurrent mark sweep GC freed 3322(133KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 805us total 26.951ms
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4367): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4367):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4367):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4367):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4367):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4367): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d48536c added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2426733b added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4367): addListener: New listener added - the number of listeners is now 1
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4367): setDiscoveryMode: Discovery mode BLE is supported
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,I/SecureStorage( 4404): [INFO]: SPID(0x00000003)Processing data has been completed
,I/PCWCLIENTTRACE_PushUtil( 3401): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3401): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3401): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3401): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/SecureStorage( 4404): [INFO]: SPID(0x00000003)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 4404): FileCipher : Key loaded. 
D/SecurityLogAgent( 4404): ProcessFileZipCreator : source file  :  file existence : true size after compression : 160
D/SecurityLogAgent( 4404): FileCipher : File ciphering 
D/SecurityLogAgent( 4404): FileCipher : Source file name = denialLog241742858.txt.zip source file size 160
I/splitIntent( 1020): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/splitIntent( 1020): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent( 4404): FileCipher : Destination file name = denialLog-1628077562.zip dest file Size 176
D/SecurityLogAgent( 4404): FileCipher : File ciphered successful 
D/SecurityLogAgent( 4404): ProcessFileZipCreator : source after encryption :  file existence : true file size:176
D/SecurityLogAgent( 4404): ProcessFileZipCreator : File ciphered 
D/SecurityLogAgent( 4404): ProcessFileZipCreatordenialLog241742858.txt.zip has been deleted after encryption. 
D/SecurityLogAgent( 4404): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4404): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4404): StateMachine : Current State = 1
D/SecurityLogAgent( 4404): FileZippingService : completed task. Returning wakelock . 
E/Zygote  ( 4543): MountEmulatedStorage()
E/Zygote  ( 4543): v2
I/libpersona( 4543): KNOX_SDCARD checking this for 10108
I/libpersona( 4543): KNOX_SDCARD not a persona
I/SELinux ( 4543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4543): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4543 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/accuweather( 1766): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Mar 05 02:37:17 GMT+01:00 2016
,I/chromium( 4367): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/TimaKeyStoreProvider( 4543): TimaSignature is unavailable
,D/ActivityThread( 4543): Added TimaKeyStore provider
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/accuweather( 1766): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1766): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1766): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive().END.
D/accuweather( 1766): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1766): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1766): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4559): MountEmulatedStorage()
E/Zygote  ( 4559): v2
I/libpersona( 4559): KNOX_SDCARD checking this for 10077
I/libpersona( 4559): KNOX_SDCARD not a persona
,I/SELinux ( 4559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4559): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4559 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3606): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/TimaKeyStoreProvider( 4559): TimaSignature is unavailable
,D/ActivityThread( 4559): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3606): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/DBG_POLICYDM( 4081): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3606): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3606): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3606): NetworkChangeOperations(): uploadRequestLog().START 
,D/SecurityLogAgent( 4404): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4404): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4404): StateMachine : Current State = 1
,D/SecurityLogAgent( 4404): StateMachine : Changed Current State = 1
,I/KLMS-2.5.123: ( 3606): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3606): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 4081): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4081): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/SPPClientService( 4162): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 4248): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4248): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 4248): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 4081): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4081): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 4081): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 4081): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,I/SA      ( 4248): [SLFUCHKMGR] constructor called
,I/SA      ( 4248): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4248): [OR] == isSIMCardReady false ==
,I/iu.SyncManager( 2127): SYNC; picasa accounts
,I/SA      ( 4248): [SCU] == networkStateCheck == true
,I/SA      ( 4248): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4248): isChinaCountryCode : false
I/SA      ( 4248): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4248): [OR] == networkStateCheck true ==
,I/MusicStore( 4543): Database version: 104
,I/SA      ( 4248): [OR] GetMyCountryZoneTask
,I/SA      ( 4248): [OR] onReceive END
,D/NetworkLogImpl( 2127): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2127): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager( 1020): Killing 3729:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4248): [SRS] prepareGetMyCountryZone
,I/SA      ( 4248): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4248): [SSP] query invoked
,E/Zygote  ( 4588): MountEmulatedStorage()
E/Zygote  ( 4588): v2
I/libpersona( 4588): KNOX_SDCARD checking this for 10009
I/libpersona( 4588): KNOX_SDCARD not a persona
,I/SELinux ( 4588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4588 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4588): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/iu.UploadsManager( 2127): num queued entries: 0
,I/iu.UploadsManager( 2127): num updated entries: 0
I/iu.SyncManager( 2127): NEXT; no task
,V/DownloadManager( 1224): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 4588): TimaSignature is unavailable
,D/ActivityThread( 4588): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10065/pid_3729/cgroup.procs: No such file or directory
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 26948(1576KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 2.881ms total 156.338ms
,I/SA      ( 4248): [TPMU] GetMccFromDB : null
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/SA      ( 4248): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4248): [TPM] isNoProxy(default) : true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/File    ( 4248): fail readDirectory() errno=2
,E/Zygote  ( 4604): MountEmulatedStorage()
E/Zygote  ( 4604): v2
I/libpersona( 4604): KNOX_SDCARD checking this for 10110
I/libpersona( 4604): KNOX_SDCARD not a persona
,I/SELinux ( 4604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4604): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4604 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3531:com.google.android.gm/u0a99 (adj 15): empty #31
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 4604): TimaSignature is unavailable
,D/ActivityThread( 4604): Added TimaKeyStore provider
,D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1020): mCursor = null
,W/libprocessgroup( 1020): failed to open /acct/uid_10099/pid_3531/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 4588): notifyNetworkActivated
,W/jxcore-log( 4367): Initializing JXcore engine
W/jxcore-log( 4367): JXcore engine is ready
,W/ResourcesManager( 4543): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4543): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4543): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 4588): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,E/audit   ( 1903): type=1400 msg=audit(1457141838.453:205): avc:  denied  { ioctl } for  pid=4541 comm="Thread-686" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/ActivityManager( 1020): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
E/audit   ( 1903):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1903): type=1300 msg=audit(1457141838.453:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=930da8f8 items=0 ppid=315 ppcomm=main pid=4541 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-686" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1903): type=1320 msg=audit(1457141838.453:205): 
,W/jxcore-log( 4367): Starting JXcore engine
,W/ActivityThread( 4543): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4543): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17dc2507: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4543): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4543): GMSCore installation verified
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 4543): Config Database version: 1
,I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,W/jxcore-log( 4367): Platform android
W/jxcore-log( 4367): 
,W/jxcore-log( 4367): Process ARCH arm
W/jxcore-log( 4367): 
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4543): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4543): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  259): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  259): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4543): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 0
,I/MediaRouter( 4543): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 4588): AutoUpdateManager:IDLE:execute
,I/NetworkMonitor( 4543): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4648 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4648): MountEmulatedStorage()
I/libpersona( 4648): KNOX_SDCARD checking this for 10001
E/Zygote  ( 4648): v2
I/libpersona( 4648): KNOX_SDCARD not a persona
,I/SELinux ( 4648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InitializeManagerStateMachine( 4588): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4588): exit::IDLE
D/InitializeManagerStateMachine( 4588): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4588): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4588): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4588): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4588): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4588): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4588): entry::SUCCESS
D/hcjo    ( 4588): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/hcjo    ( 4588): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4588): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4588): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/TimaKeyStoreProvider( 4648): TimaSignature is unavailable
,D/ActivityThread( 4648): Added TimaKeyStore provider
D/InitializeManagerStateMachine( 4588): exit::SUCCESS
D/InitializeManagerStateMachine( 4588): entry::IDLE
,I/NetworkMonitor( 4543): type=WIFI subType= reason=null isConnected=true
,I/WebViewFactory( 4604): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 4604): Loading: webviewchromium
,I/ActivityManager( 1020): Killing 3767:com.google.android.talk/u0a102 (adj 15): empty #31
I/LibraryLoader( 4604): Time to load native libraries: 6 ms (timestamps 8731-8737)
,I/LibraryLoader( 4604): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4604): Binding Chromium to main looper Looper (main, tid 1) {1ed88159}
,I/LibraryLoader( 4604): Expected native library version number "",actual native library version number ""
,I/chromium( 4604): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4604): Initializing chromium process, renderers=0
,W/art     ( 4604): Attempt to remove local handle scope entry from IRT, ignoring
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/chromium( 4604): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4604): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 4604): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/PowerManagerService( 1020): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 48838
D/PowerManagerService( 1020): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1020): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
,D/PowerManagerService( 1020): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3434)
,W/AudioManagerAndroid( 4604): Requires BLUETOOTH permission
,W/libprocessgroup( 1020): failed to open /acct/uid_10102/pid_3767/cgroup.procs: No such file or directory
,I/Adreno-EGL( 4604): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4604): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4604): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4604): Local Branch: 
I/Adreno-EGL( 4604): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4604): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4604):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4680): MountEmulatedStorage()
E/Zygote  ( 4680): v2
I/libpersona( 4680): KNOX_SDCARD checking this for 1000
I/libpersona( 4680): KNOX_SDCARD not a persona
I/SELinux ( 4680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/jxcore-log( 4367): JXcore Cordova bridge is ready!
I/jxcore-log( 4367): 
I/ActivityManager( 1020): Killing 3785:com.vlingo.midas/u0a28 (adj 15): empty #31
,W/jxcore-log( 4367): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4367): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/TimaKeyStoreProvider( 4680): TimaSignature is unavailable
,D/ActivityThread( 4680): Added TimaKeyStore provider
,E/Watchdog( 1020): !@Sync 1
,I/NSApplication( 4604): Starting up...
,E/jxcore  ( 4367): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4367): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/ActivityManager( 1020): Killing 3820:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/chromium( 4367): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/FocusedStackFrame( 1020): Set to : 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1020): Focused application set to: xxxx
,D/InputDispatcher( 1020): Focus left window: 4367
D/SettingsProvider( 1020): name = audio_safe_volume_state
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (164 us)
,W/PluginManager( 4367): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 52ms. Plugin should use CordovaInterface.getThreadPool().
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{2666ee4e u0 com.samsung.android.providers.context/.ContextService}
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1513): onRestart, Launcher: 658582079
,D/Launcher( 1513): onStart, Launcher: 658582079
D/Launcher.HomeView( 1513): onStart
,D/Launcher( 1513): onResume, Launcher: 658582079
,D/QuickConnect( 4065): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SettingsProvider( 1020): name = kids_home_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/SensorService( 1020): [SO] activate (ident=0xb86c5bd8, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher.HomeView( 1513): onResume
I/DIAGMON_AGENT( 4680): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/QuickConnect( 4065): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 4065): PeriphStartReceiver.onReceive - no need to start
,D/Launcher( 1513): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/SensorManager( 1020): unregisterListener ::   
,I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1020): [SO] changed settle time [0]
D/SensorService( 1020): [SO] setDelay [200000000]
D/SensorService( 1020): [SO] activate (ident=0xb8877158, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,E/SMD     (  294): DCD OFF
,I/ActivityManager( 1020): Killing 3886:com.samsung.helphub/1000 (adj 15): empty #31
,D/MenuAppsGridFragment( 1513): onResume
,D/ActivityManager( 1020): handle home activity for 0
,W/ContextImpl( 2879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1020): post home show event for user 0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  260): id=13 createSurf (540x960),1 flag=4, Mauncher
,I/DBG_DM  ( 3154): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/DBG_DM  ( 3154): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
I/Process ( 2879): Sending signal. PID: 2879 SIG: 9
,E/DBG_DM  ( 3154): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1020): Focus entered window: 1513
,D/SRIB_DCS( 1513): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,D/Launcher( 1513): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3820/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10028/pid_3785/cgroup.procs: No such file or directory
,D/PanelView( 1178): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 4367): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1887): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3886/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Process com.sec.android.app.sysscope (pid 2879)(adj 0) has died(48,578)
,I/Timeline( 1513): Timeline: Activity_idle id: android.os.BinderProxy@29936a9b time:49179
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,I/ActivityManager( 1020): Displayed Component not be shown by security: +146ms
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{9018286 u0 com.android.settings/.wifi.WifiCredService}
,I/DIAGMON_AGENT( 4680): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4680): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4680): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4680): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4680): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4680): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4081): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4081): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4706): MountEmulatedStorage()
E/Zygote  ( 4706): v2
I/libpersona( 4706): KNOX_SDCARD checking this for 10008
I/libpersona( 4706): KNOX_SDCARD not a persona
,I/SELinux ( 4706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SurfaceFlinger(  260): id=11 Removed Uoast (9/9)
,I/SurfaceFlinger(  260): id=11 Removed Uoast (-2/9),
I/SELinux ( 4706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4706): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4706 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3154): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 3154): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/art     (  315): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 21.203ms
,D/TimaKeyStoreProvider( 4706): TimaSignature is unavailable
,D/ActivityThread( 4706): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.630ms
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 17.168ms
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 3154): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 3154): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/SensorService( 1020): [SO] currT = 49481082000, prevT = 49061077000, diff = 420005000, [-0.402 0.172 9.883]
,D/SensorService( 1020): [SO] -0.402 0.172 9.883
D/SensorService( 1020): [SO] [100 -> 255]
,I/DBG_DM  ( 3154): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3154): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3154): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 3154): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3154): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,I/DBG_DM  ( 3154): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/ActivityManager( 1020): Killing 3906:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/FOTA_Client( 4706): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/FOTA_Client( 4706): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4706): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4706): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1020): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,I/ActivityManager( 1020): Killing 3945:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/splitIntent( 1020): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1020): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/SA      ( 4248): [RC New] Execute method=[GET] start
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,I/DBG_DM  ( 3154): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4723): MountEmulatedStorage()
I/libpersona( 4723): KNOX_SDCARD checking this for 10058
E/Zygote  ( 4723): v2
I/libpersona( 4723): KNOX_SDCARD not a persona
,I/SELinux ( 4723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4723 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/FOTA_Client( 4706): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/SA      ( 4248): [RC New] Security=[true]
,I/System.out( 4248): Thread-645(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false,
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{38ebf2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:49626
,I/System.out( 4248): Thread-645(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4248): Thread-645(ApacheHTTPLog):isShipBuild true
I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
I/System.out( 4248): Thread-645(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4248): Thread-645(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/DBG_DM  ( 3154): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 502 for uid 10036
D/daemonapp( 1827): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1827): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@54679d2
,I/SurfaceFlinger(  260): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  260): id=12 Removed NainActivit (-2/8)
,D/TimaKeyStoreProvider( 4723): TimaSignature is unavailable
,D/ActivityThread( 4723): Added TimaKeyStore provider
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ContextImpl( 3154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,W/ContextImpl( 3154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
I/Timeline( 3154): Timeline: Activity_launch_request id:com.wssyncmldm time:49647
,E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1827): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1827): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1827): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1827): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
I/FOTA_Client( 4706): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1827): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/daemonapp( 1827): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/daemonapp( 1827): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1827): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/daemonapp( 1827): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1020): Set to : 0
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3906/cgroup.procs: No such file or directory
,D/Launcher.HomeView( 1513): onPause
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1020): Focused application set to: xxxx
,D/InputDispatcher( 1020): Focus left window: 1513
,D/Launcher( 1513): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Sat Mar 05 02:37:19 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ScreenOrientationListener( 4367): Removing an inexistent observer!
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,V/AlarmManager( 1020): waitForAlarm result :4
,I/KLMS-2.5.123: ( 3606): KLMSAbstractReciever(): onReceive().END.
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3945/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 4404): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4404): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4404): StateMachine : Current State = 1
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3606): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3606): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3606): StateImplV2(): dateTimeChanged().START : Sat Mar 05 02:37:19 GMT+01:00 2016
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1020): [SO] activate (ident=0xb8877158, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/KLMS-2.5.123: ( 3606): StateImplV2(): dateTimeChanged().END
,I/SA      ( 4248): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ExternalOEMControlProvider( 4723): onCreate
,D/SensorManager( 1020): unregisterListener ::   
I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1020): [SO] changed settle time [1]
,D/SensorService( 1020): [SO] setDelay [66000000]
D/SensorService( 1020): [SO] activate (ident=0xb8877158, enabled=1),
,D/SensorService( 1020): [SO] AR_init
I/libpersona( 4744): KNOX_SDCARD checking this for 10153
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/libpersona( 4744): KNOX_SDCARD not a persona
,E/Zygote  ( 4744): MountEmulatedStorage()
E/Zygote  ( 4744): v2
I/SELinux ( 4744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/comdaemonstockapp( 1827): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1827): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/SELinux ( 4744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4744): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/ActivityManager( 1020): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4744 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3606): KLMSIntentService(): onDestroy()
,D/accuweather( 1766): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1766): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 4744): TimaSignature is unavailable
,D/ActivityThread( 4744): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Zygote  ( 4760): MountEmulatedStorage()
E/Zygote  ( 4760): v2
I/libpersona( 4760): KNOX_SDCARD checking this for 10041
I/libpersona( 4760): KNOX_SDCARD not a persona
,I/SELinux ( 4760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4760 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
I/SELinux ( 4760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4760): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1],
,E/Zygote  ( 4774): MountEmulatedStorage()
E/Zygote  ( 4774): v2
I/libpersona( 4774): KNOX_SDCARD checking this for 10081
I/libpersona( 4774): KNOX_SDCARD not a persona
,I/SELinux ( 4774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 4760): TimaSignature is unavailable
,D/ActivityThread( 4760): Added TimaKeyStore provider
,I/ActivityManager( 1020): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4774 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,E/SELinux ( 4774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CustomFrequencyManagerService( 1020): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,I/ Time Manager ( 4723): Time Difference not stored. TIME_DIFFERENCE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 3960:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,W/ResourcesManager( 4744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,D/TimaKeyStoreProvider( 4774): TimaSignature is unavailable
,D/ActivityThread( 4774): Added TimaKeyStore provider
,W/ResourcesManager( 4760): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23,
,D/SensorService( 1020): [SO] -0.383 0.153 9.902
I/libpersona( 4790): KNOX_SDCARD checking this for 1000
D/SensorService( 1020): [SO] [100 -> 255]
I/libpersona( 4790): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
E/Zygote  ( 4790): MountEmulatedStorage()
E/Zygote  ( 4790): v2
I/SELinux ( 4790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ResourcesManager( 4760): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4760): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4760): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1020): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4790 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ResourcesManager( 4760): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/SELinux ( 4790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 3991:com.sec.android.app.mt/1000 (adj 15): empty #31
I/CheckinService( 2127): Checkin interval check for package: unspecified last checkin: 1456599118758 min interval config: 0 actual interval: 542721378,
E/SELinux ( 4790): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,W/ResourcesManager( 4774): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4774): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4774): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
W/ResourcesManager( 4774): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/Timeline( 3154): Timeline: Activity_launch_request id:com.wssyncmldm time:49919
,E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1020): Focused application set to: xxxx
,D/TimaKeyStoreProvider( 4790): TimaSignature is unavailable
,D/ActivityThread( 4790): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 1403:com.android.defcontainer/u0a3 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3960/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3991/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10003/pid_1403/cgroup.procs: No such file or directory
,D/Mms/MmsApp( 4760): [start]    onCreate() consume time = 0.0
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,D/ActivityManager( 1020): post active user change for 0 fullscreen false record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1020): Target Activity is not fullscreen. We will not show this activity0
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,D/TimeService( 4790): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457141840322
D/        ( 4790): TimeServiceNative: User Time to be set is 1457141840322
D/QC-time-services( 4790): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4790): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4790): Lib:time_genoff_operation: pargs->ts_val = 1457141840322
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/QC-time-services(  340): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4790): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  340): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457141840322
D/QC-time-services(  340): Daemon:genoff_opr: Base = 2, val = 1457141840322, operation = 0
D/QC-time-services(  340): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/31/70 5:14:5
,D/QC-time-services(  340): Daemon:Value read from RTC seconds = 20927645000
D/QC-time-services(  340): Daemon:new time 1457141840322 
D/QC-time-services(  340): Daemon: delta 1436214195322 genoff 1436214195322 
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 1436214195322 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  340): Updating the TOD offset
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 1436214195322 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,E/QC-time-services(  340): Daemon:Update to modem bit set
D/QC-time-services(  340): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 4790): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  340): Daemon: Base = 2, Value being sent to MODEM = 1120249395322
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,E/QC-time-services(  340): Daemon: Time-services: Waiting to acceptconnection
,D/SettingsProvider( 1020): name = next_alarm_formatted
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10081
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,I/ActivityManager( 1020): Killing 4109:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 23
,D/PhoneWindow( 3154): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 3154): *FMB* installDecor flags : -2139029248
,W/art     ( 4760): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 108.374ms
,W/art     ( 4774): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 108.875ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0,
,E/Zygote  ( 4810): MountEmulatedStorage(),
E/Zygote  ( 4810): v2
I/libpersona( 4810): KNOX_SDCARD checking this for 10090,
I/libpersona( 4810): KNOX_SDCARD not a persona
,I/SELinux ( 4810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4810 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 4810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 4197:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,E/SELinux ( 4810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/ArtClassLoader( 4760): init before art
,D/Mms/TelephonyPermission( 4760): start operation mode monitor
,W/ResourcesManager( 4760): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4810): TimaSignature is unavailable
,D/ActivityThread( 4810): Added TimaKeyStore provider
,D/Mms/TelephonyPermission( 4760): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4760): isDefault true
,D/Mms/MmsApp( 4760): onCreate() com.android.mms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1020): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,W/ResourcesManager( 1178): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_10127/pid_4109/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/Mms/MmsApp( 4760): [start]    initCountryIso consume time = 335.213125
I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,W/libprocessgroup( 1020): failed to open /acct/uid_10135/pid_4197/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,D/CountryDetector( 1020): The first listener is added
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/elm:15121( 4810): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4810): ELMEngine.ELMEngine( context ).
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,D/Mms/MmsApp( 4760): [end]    initCountryIso consume time = 39.61427
D/Mms/MmsConfig( 4760): [start]    MmsConfig.init() consume time = 0.105625
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/elm:15121( 4810): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 23
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/elm:15121( 4810): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/Zygote  ( 4830): MountEmulatedStorage()
,E/Zygote  ( 4830): v2
I/libpersona( 4830): KNOX_SDCARD checking this for 10130,
,D/Mms/MmsConfig( 4760): before partial update
I/libpersona( 4830): KNOX_SDCARD not a persona
,I/SELinux ( 4830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4830 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,I/SELinux ( 4830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/DBG_DM  ( 3154): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
E/SELinux ( 4830): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3154): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/elm:15121( 4810): ElmAgentService : onCreate()
D/elm:15121( 4810): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/Mms/MmsConfig( 4760): Load Resize quality : 80
I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/EasySignUpManager_1.0.1( 4760): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 4760): isAuth is false
D/Mms/MmsConfig( 4760): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/elm:15121( 4810): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 4810): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 4810): ModuleBase.ModifySetAlarm()
D/elm:15121( 4810): MDMBridge.getInstance()
,D/elm:15121( 4810): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider( 4830): TimaSignature is unavailable
,D/ActivityThread( 4830): Added TimaKeyStore provider
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/elm:15121( 4810): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 4294:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1487): query,matched:2117, calling pid = 4760
,D/TP/MmsSmsProvider( 1487): match 2117:Elapsed time : 1.474 ms
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/SA      ( 4248): [RC New] [v2liruge] api execute + 938
I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 23
,I/SA      ( 4248): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4248): AsyncTask #1 calls detatch()
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/EasySignUpManager_1.0.1( 4760): isAuth is false
D/EasySignUpManager_1.0.1( 4760): getServiceStatus : serviceId (1) is OFF
,I/DBG_DM  ( 3154): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/SA      ( 4248): [ODM] saveOpenData( GEO_IP, PL )
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/DBG_DM  ( 3154): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 3154): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3154): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,E/CscParser( 4760): mps_code.dat does not exist
E/CscParser( 4760): customer_path =/system/csc/customer.xml
E/CscParser( 4760): fileName + /system/csc/customer.xml
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/CscParser( 4760): mps_code.dat does not exist
,E/CscParser( 4760): customer_path =/system/csc/customer.xml
E/CscParser( 4760): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_4294/cgroup.procs: No such file or directory
,D/CscParser( 4760): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4760):  enable multiwindow = false
,W/ResourcesManager( 4830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4830): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/Mms/MessageUtils( 4760): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4760): updateCountryIso : update country iso info 
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/Mms/ArtClassLoader( 4760): init [DONE] art
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 24839(1349KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.503ms total 148.425ms
,I/SA      ( 4248): [OCP] update openData : PL
,I/ActivityManager( 1020): Killing 4344:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/PackageManager( 1020): [MSG] SEND_PENDING_BROADCAST
,I/SA      ( 4248): [TPMU] getNetworkMcc : 
,D/Mms/MmsConfig( 4760): [end]    init() consume time = 286.230469
I/SA      ( 4248): [SCU] saveMccToPreferece Start
I/SA      ( 4248): [SCU] RegionMCC : 260
I/SA      ( 4248): [SSP] query invoked
,I/SA      ( 4248): [TPMU] GetMccFromDB : null
I/SA      ( 4248): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4248): [SCU] saveMccToPreferece End
,I/SA      ( 4248): [RC New] executeRequest [v2liruge] end. 1179
I/SA      ( 4248): [RC New] Execute end
,I/SA      ( 4248): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4248): [OR] GetMyCountryZoneTask Success
D/OpenGLRenderer( 3154): Render dirty regions requested: true
,D/Mms/Contact( 4760): [start]    init() consume time = 10.951198
,D/Mms/Contact( 4760): [end]    init consume time = 20.74099
,W/IntentResolver( 1020): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,D/TP/MmsSmsProvider( 1487): query,matched:13, calling pid = 4760
D/Mms/DraftCache( 4760): [start]    rebuildCache consume time = 13.108281
,D/TP/MmsSmsProvider( 1487): match 13:Elapsed time : 2.830 ms
I/PageBuddyNotiSvc( 4025): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/TP/MmsSmsProvider( 1487): query,matched:12, calling pid = 4760
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
,D/TP/MmsSmsProvider( 1487): match 12:Elapsed time : 1.503 ms
,I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/PhoneWindow( 3154): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3154): *FMB* isFloatingMenuEnabled return false
,D/Mms/MethodReflector( 4760): getSubId is called
,D/Mms/TelephonyUtils( 4760): getLongSubId from simSlot 0, return Value = -1
D/RegisteredServicesCache( 1470): empty dynamic service
,D/Mms/MethodReflector( 4760): getTelephonyProperty is called
D/Mms/DownloadManager( 4760): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4760): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4760): auto download without roaming -> true
D/Mms/DownloadManager( 4760): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4760): getSubId is called
,D/Mms/DraftCache( 4760): [end]    rebuildCache consume time = 34.563489
,D/Mms/MethodReflector( 4760): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 4760): subID is null or 0 length, so get DefaultSubId!!
,D/Mms/TelephonyUtils( 4760): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4760): getTelephonyProperty is called
,D/Mms/DownloadManager( 4760): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4760): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4760): auto download without roaming -> true
,D/Mms/DownloadManager( 4760): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,D/Mms/DownloadManager( 4760): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4760): mAutoDownload ------> true
,I/SurfaceFlinger(  260): id=14 createSurf (1x1),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1020): Focus entered window: 3154
,D/ComposerPerformance( 4760): 1457141841095 ms / [DONE] Composer constructor
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/Mms/Conversation( 4760): [start]    init() consume time = 49.830625
,D/SRIB_DCS( 3154): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3154): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3154): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3154): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3154): Local Branch: 
I/Adreno-EGL( 3154): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3154): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3154):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/CII     ( 4760): CommonIMSInterface: VoLTE CSC feature disabled.
,D/TP/MmsSmsProvider( 1487): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1487): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1487): updateThread(), thread_id = 9223372036854775807
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/OpenGLRenderer( 3154): Initialized EGL, version 1.4
,V/TP/MmsSmsDatabaseHelper( 1487): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1487): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1487): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1487): need read changed broadcast:false
,I/Mms/ReservationManager( 4760): ReservationManager()
,I/Mms/ReservationManager( 4760): resetAfterConnected()
,D/Mms/Conversation( 4760): [end]    init consume time = 25.747969
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,D/OpenGLRenderer( 3154): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3154): Enabling debug mode 0
,D/TP/MmsSmsProvider( 1487): query,matched:7, calling pid = 4760
,D/TP/MmsSmsProvider( 1487): match 7:Elapsed time : 3.508 ms
,D/Mms/MessagingNotification( 4760): [start]    init() consume time = 8.213854
,D/Mms/MessagingNotification( 4760): [end]    init consume time = 2.796719
I/Mms/ReservationManager( 4760): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/SpamFilter( 4760): [start]    SpamFilter fill() begin consume time = 5.678177
,D/TP/MmsSmsProvider( 1487): query,matched:0, calling pid = 4760
V/TP/MmsSmsProvider( 1487): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1487): match 0:Elapsed time : 1.638 ms
,D/TP/MmsSmsProvider( 1487): query,matched:400, calling pid = 4760
,D/Mms/Synchronizer( 4760): [start]    doSync consume time = 5.713698
,D/Mms/SpamFilter( 4760): [end]    SpamFilter fill() finished consume time = 2.504271
,D/TP/MmsSmsProvider( 1487): update, matched:300, calling pid = 4760
V/TP/MmsSmsProvider( 1487): syncDBData start
,V/TP/MmsSmsProvider( 1487): syncDBData sms end
,V/TP/MmsSmsProvider( 1487): syncDBData mms end
,V/TP/MmsSmsProvider( 1487): syncDBData end
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4857): MountEmulatedStorage(),
I/libpersona( 4857): KNOX_SDCARD checking this for 10068,
E/Zygote  ( 4857): v2
I/libpersona( 4857): KNOX_SDCARD not a persona,
,I/SELinux ( 4857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4857 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 4857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4857): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/Synchronizer( 4760): [end]    doSync consume time = 42.392604
,D/Mms/MmsApp( 4760): [end]    onCreate() consume time = 4.272708
,D/Mms/DownloadManager( 4760): Service state changed: Bundle[mParcelledData.dataSize=744]
I/splitIntent( 1020): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,D/Mms/DownloadManager( 4760): roaming ------> false, mSimSlot = 0
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1020): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MethodReflector( 4760): getSubId is called
,D/Mms/TelephonyUtils( 4760): getLongSubId from simSlot 0, return Value = -1
,I/ActivityManager( 1020): Killing 4221:com.android.vending/u0a26 (adj 15): empty #31
,I/BackupManagerService( 1020): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,D/TimaKeyStoreProvider( 4857): TimaSignature is unavailable
,D/Mms/MethodReflector( 4760): getTelephonyProperty is called
,D/Mms/DownloadManager( 4760): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4760): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4760): auto download without roaming -> true
D/Mms/DownloadManager( 4760): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/ActivityThread( 4857): Added TimaKeyStore provider
D/Mms/DownloadManager( 4760): mAutoDownload ------> true
,I/ActivityManager( 1020): Killing 4432:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/BackupManagerService( 1020): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1020): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@943ce0f
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/BadgeProvider( 4857): onCreate
,D/BadgeProvider( 4857): DatabaseHelper
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 4760): checkBadgeCount unreadCount=0 badgeCount=0
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Timeline( 3154): Timeline: Activity_idle id: android.os.BinderProxy@300a78da time:51145
,D/SamsungIME( 1887): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PanelView( 1178): There is/are notification(s) 
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TP/SmsProvider( 1487): query,matched:26, calling pid = 4760
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1487): match 26:Elapsed time : 3.607 ms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1020): Displayed Component not be shown by security: +1s75ms (total +1s466ms)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1836): callingUid 10011, callindPid: 1836
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1487): query,matched:6, calling pid = 4760
,D/TP/MmsSmsProvider( 1487): match 6:Elapsed time : 1.861 ms
I/GCoreNlp( 1836): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2127): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4344/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10026/pid_4221/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4879): MountEmulatedStorage(),
I/libpersona( 4879): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4879): v2,
,I/libpersona( 4879): KNOX_SDCARD not a persona
I/SELinux ( 4879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4879 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
,I/SELinux ( 4879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationProviderProxy( 1020): applying state to connected service
W/libprocessgroup( 1020): failed to open /acct/uid_10148/pid_4432/cgroup.procs: No such file or directory
,D/LocationProviderProxy( 1020): applying state to connected service
,D/AuthorizationBluetoothService( 1836): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1836): [252] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1836): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/GCoreFlp( 1836): No location to return for getLastLocation()
,D/TimaKeyStoreProvider( 4879): TimaSignature is unavailable
,D/ActivityThread( 4879): Added TimaKeyStore provider
W/FusedLocationProvider( 1836): location=null
,I/ActivityManager( 1020): Killing 4460:com.sec.modem.settings/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4460/cgroup.procs: No such file or directory
,I/OMACP   ( 4879): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Mms/Omacp( 4760): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/Zygote  ( 4897): MountEmulatedStorage()
,I/libpersona( 4897): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4897): v2
I/libpersona( 4897): KNOX_SDCARD not a persona
I/SELinux ( 4897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4879): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/TimaKeyStoreProvider( 4897): TimaSignature is unavailable
,D/ActivityThread( 4897): Added TimaKeyStore provider
,E/MTPRx   ( 4897): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
D/SecContentProvider2( 1020): mCursor = null
,D/Mms/Contact( 4760): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4760): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4760): [start]    invalidate() consume time = 573.486979
D/Mms/ContactsCache( 4760): [end]    invalidate() consume time = 0.122292
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1020): mCursor = null
,V/MTPRx   ( 4897): sealedState: false
I/ValidateNoPeople( 1020): mEvictionCount: 0
V/MTPRx   ( 4897): sealedUsbMassStorageState: false
E/MTPRx   ( 4897): check value of boot_completed is1
E/MTPRx   ( 4897): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4897): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4897): Status for mount/Unmount :removed
,E/MTPRx   ( 4897): SDcard is not available
,W/MTPRx   ( 4897): value of connected istrue
W/MTPRx   ( 4897): value of configured istrue
W/MTPRx   ( 4897): value of mtpEnabled istrue
W/MTPRx   ( 4897): value of ptpEnabled isfalse
,E/MTPRx   ( 4897): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4897): mFirstTime: false
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.release()
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{2bf19887 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t12} time:51574
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/SurfaceFlinger(  260): id=13 Removed Mauncher (5/8)
,I/SurfaceFlinger(  260): id=13 Removed Mauncher (-2/8),
D/SensorService( 1020): [SO] -0.383 0.172 9.922
,D/Launcher.HomeView( 1513): onStop
,V/ActivityThread( 1513): updateVisibility : ActivityRecord{3f3d6621 token=android.os.BinderProxy@29936a9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/Launcher( 1513): onTrimMemory. Level: 20
,D/        ( 4897): MTP: reading debug level property
,E/MTPJNIInterface( 4897): Getting CryptionKey from JAVA
E/MTPRx   ( 4897): currentUserId is 0
,E/MTPRx   ( 4897): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4897): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4897): is_Privatemode is NOT 1
,D/SettingsProvider( 1020): name = boot_time_connected
,E/MTPRx   ( 4897): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4897): noti = 17
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,D/SecContentProvider( 1020): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4897): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1020): name = mtp_running_status
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,E/MTPRx   ( 4897): else part ... so first time!!!
,E/MTPPlaObsrvr( 4897): inside setContext()
E/MTPPlaObsrvr( 4897):  inside createplafiles
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4897): playlist count is0
,E/MTPPlaObsrvr( 4897):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4897):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4897): Inside registerContentObserver
,E/MtpAdbObserver( 4897): inside setContext()
,E/MtpAdbObserver( 4897): Inside registerContentObserver
W/Settings( 4897): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1020): name = mtp_running_status
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,V/MtpMediaDBManager( 4897): inside deleteAllDB
E/MtpService( 4897): onCreate.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4897): < MTP > Registering BroadCast receiver :::::
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{1a45ee39 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,E/MtpService( 4897): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4897): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4897): onStartCommand.
,D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
,W/MTPRx   ( 4897): calling native method
E/MTPJNIInterface( 4897): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4897): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4897): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4897): noti = 10
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/MtpMediaDBManager( 4897): inside Thread updateDB
,E/Zygote  ( 4917): MountEmulatedStorage(),
I/libpersona( 4917): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4917): v2
I/libpersona( 4917): KNOX_SDCARD not a persona
,I/SELinux ( 4917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 4917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4917): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4917 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/MtpService( 4897): onStartCommand.
W/MTPRx   ( 4897): calling native method
,E/MTPRx   ( 4897): Checking the driver time out
E/MTPJNIInterface( 4897): noti = 2
E/MtpService( 4897): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/        ( 4897): deleting sockets before message queue initialization
D/        ( 4897): event handler thread is created, so set the flag
,E/MTPRx   ( 4897): called native method
,E/MTPJNIInterface( 4897): setting Media scanner status0
E/MTPJNIInterface( 4897): After setting Media scanner status0
,W/MTPRx   ( 4897): notification from stack 1
,E/        ( 4897): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4897): Getting media scanner status0
E/MtpMediaDBManager( 4897): count : 26
,E/MTPJNIInterface( 4897): DeviceName is Thali Test (Galaxy A3)
,I/art     (  315): Explicit concurrent mark sweep GC freed 8680(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 22.905ms
,D/TimaKeyStoreProvider( 4917): TimaSignature is unavailable
,D/ActivityThread( 4917): Added TimaKeyStore provider
,W/MtpMediaDBManager( 4897): sending db update complete noti to stack
E/MTPJNIInterface( 4897): noti = 29
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 16.767ms
E/SQLiteLog( 4897): (5) database is locked
,E/MTPJNIInterface( 4897): Status for mount/Unmount :removed
E/MTPJNIInterface( 4897): SDcard is not available
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 17.089ms
,E/        ( 4897): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4897): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4897): SDcard is not available
,E/SQLiteLog( 4897): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4897): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4897): (21) API call with NULL database connection pointer
E/SQLiteLog( 4897): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4897): (21) API call with NULL database connection pointer
E/SQLiteLog( 4897): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4897): (21) API call with NULL database connection pointer
E/SQLiteLog( 4897): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4897): notification from stack 2
,D/        ( 4897): [mtp_init_device] Library open with 32 bits.
D/        ( 4897): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4897): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4897): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4897):  [sua_support_present:1287] returning false 
D/        ( 4897): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
