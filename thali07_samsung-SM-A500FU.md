#### Test 62509094058a2d4_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
W/BaseAppContext( 1903): Using Auth Proxy for data requests.
--------- beginning of system
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/AuthZen ( 1903): Starting Enrollment...
E/Zygote  ( 4039): MountEmulatedStorage()
E/Zygote  ( 4039): v2
I/SELinux ( 4039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/libpersona( 4039): KNOX_SDCARD checking this for 10146
I/libpersona( 4039): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4039 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/ConfigFetchService( 1903): ConfigApi connection successful.
I/ActivityManager( 1021): Killing 3306:com.sec.factory.camera/1000 (adj 15): empty #31
I/ActivityManager( 1021): Killing 3290:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #32
D/TimaKeyStoreProvider( 4039): TimaSignature is unavailable
D/ActivityThread( 4039): Added TimaKeyStore provider
,D/SystemUpdateService( 1903): onDestroy
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/BadgeProvider( 4006): onCreate
D/BadgeProvider( 4006): DatabaseHelper
I/GFX raster( 3662): took 0.702864ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
D/AuthZen ( 1903): getting auth token. Attempt 0
W/ResourcesManager( 4039): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/ActivityManager( 1021): Killing 3336:com.fmm.dm/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BadgeProvider( 4006): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1021): getTasks: caller 10145 does not hold GET_TASKS; limiting output
I/Process ( 3925): Sending signal. PID: 3925 SIG: 9
I/GLSUser ( 1722): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1722): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1722): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1722): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1722): Explicit concurrent mark sweep GC freed 12422(745KB) AllocSpace objects, 7(172KB) LOS objects, 39% free, 10MB/17MB, paused 1.474ms total 698.296ms
V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1021): Process com.android.email (pid 3925)(adj 9) has died(123,1067)
D/Launcher.Model( 1508): reloadBadges entered.
D/BadgeProvider( 4006): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4006): sendNotify, [notify] : null
D/BadgeProvider( 4006): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4006): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4006): update, [UpdateCount] : 1
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/EventLogService( 1903): Aggregate from 1458042125962 (log), 1458042125962 (data)
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
D/PowerManagerService( 1021): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1181 (0x0)
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4065): MountEmulatedStorage()
E/Zygote  ( 4065): v2
I/libpersona( 4065): KNOX_SDCARD checking this for 10033
I/libpersona( 4065): KNOX_SDCARD not a persona
I/SELinux ( 4065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4065): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4065 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3193/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1021): applying state to connected service
W/libprocessgroup( 1021): failed to open /acct/uid_10094/pid_3211/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10003/pid_3245/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3306/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10060/pid_3290/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3336/cgroup.procs: No such file or directory
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.539427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb87a78a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d29848 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4080): MountEmulatedStorage()
E/Zygote  ( 4080): v2
I/libpersona( 4080): KNOX_SDCARD checking this for 1000
I/libpersona( 4080): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3662): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
I/SELinux ( 4080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4065): TimaSignature is unavailable
D/ActivityThread( 4065): Added TimaKeyStore provider
I/art     (  319): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 779us total 28.295ms
I/dex2oat ( 3776): dex2oat took 2.448s (threads: 4)
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 20.850ms
D/DexOptUtils( 1903): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1903): Set odex to world readable.
D/DexOptUtils( 1903): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
D/FileApkUtils( 1903): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
D/TimaKeyStoreProvider( 4080): TimaSignature is unavailable
D/ActivityThread( 4080): Added TimaKeyStore provider
W/art     ( 3857): Suspending all threads took: 6.427ms
I/ActivityManager( 1021): Killing 3353:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 891us total 19.772ms
D/GmsModuleFndr( 1903): Beginning GMS chimera module scan
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/GCoreUlr( 1776): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
E/Zygote  ( 4097): MountEmulatedStorage()
E/Zygote  ( 4097): v2
I/libpersona( 4097): KNOX_SDCARD checking this for 10145
I/libpersona( 4097): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4097 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1021): failed to open /acct/uid_10100/pid_3353/cgroup.procs: No such file or directory
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/Zygote  ( 4104): MountEmulatedStorage()
I/ActivityManager( 1021): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4104): v2
I/libpersona( 4104): KNOX_SDCARD checking this for 1000
I/libpersona( 4104): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Killing 3373:com.samsung.helphub/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131165203
W/ResourcesManager( 3662): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3373/cgroup.procs: No such file or directory
I/SELinux ( 4097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/SELinux ( 4097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/AuthZen ( 1903): Error getting auth token
E/AuthZen ( 1903): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1903): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1903): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1903): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 1903): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1903): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1903): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1903): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1903): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux ( 4104): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/GmsModuleFndr( 1903): Module pkg com.google.android.apps.kids.familylink not installed, skipping
D/ChimeraCfgMgr( 1903): Beginning module configuration check
D/ChimeraCfgMgr( 1903): Module APKs unchanged, check complete
D/a       ( 1903): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 1903): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1903): Clearing transaction cache
I/AMMetaDataParserService( 3662): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
D/TimaKeyStoreProvider( 4097): TimaSignature is unavailable
D/ActivityThread( 4097): Added TimaKeyStore provider
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1021): Killing 3412:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
I/GFX construct_block_size_descriptor_2d second part( 3662): took 3.724114ms for 0*0 texture 0
D/TimaKeyStoreProvider( 4104): TimaSignature is unavailable
D/ActivityThread( 4104): Added TimaKeyStore provider
W/ResourcesManager( 4065): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/GFX generate_partition_tables( 3662): took 11.226667ms for 0*0 texture 0
W/ResourcesManager( 4065): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/GFX raster( 3662): took 15.840677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d257c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d25e30 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3662): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 1.022448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b51950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b519f8 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 4097): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4097): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4097): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4097): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4097): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3662): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
W/ResourcesManager( 4065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.774115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b51950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4fad8 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 4065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4065): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4065): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3662): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/libprocessgroup( 1021): failed to open /acct/uid_10062/pid_3412/cgroup.procs: No such file or directory
I/GFX raster( 3662): took 0.967292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b51950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d29be8 counterpartCT=4 counterpartW=96 counterparth=96
D/SecurityLogAgent( 4104): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4104): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4104): StateMachine : Current State = 1
D/SecurityLogAgent( 4104): BootReceiver : completed task. Failed to return wakelock . 
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3662): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
E/Zygote  ( 4133): MountEmulatedStorage()
I/libpersona( 4133): KNOX_SDCARD checking this for 10152
E/Zygote  ( 4133): v2
I/libpersona( 4133): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4133 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 4133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1021): Killing 3430:com.fmm.ds/1000 (adj 15): empty #31
I/SELinux ( 4133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4133): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 3992): Suspending all threads took: 5.561ms
D/TimaKeyStoreProvider( 4133): TimaSignature is unavailable
D/ActivityThread( 4133): Added TimaKeyStore provider
I/Babel_SMS( 3992): MmsConfig: mnc/mcc: 0/0
E/SMD     (  291): DCD OFF
I/Babel_SMS( 3992): MmsConfig.loadMmsSettings
I/Babel_SMS( 3992): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3992): MmsConfig.loadFromDatabase
D/AndroidRuntime( 4058): 
D/AndroidRuntime( 4058): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4058): CheckJNI is OFF
D/AndroidRuntime( 4058): readGMSProperty: start
D/AndroidRuntime( 4058): readGMSProperty: already setted!!
D/AndroidRuntime( 4058): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4058): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4058): readGMSProperty: end
D/AndroidRuntime( 4058): addProductProperty: start
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3430/cgroup.procs: No such file or directory
E/Babel_SMS( 3992): canonicalizeMccMnc: invalid mccmnc 
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
I/Babel_SMS( 3992): MmsConfig.loadFromResources
E/Babel_SMS( 3992): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3992): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
D/PCWCLIENTTRACE_AccountAppFacade2_0( 3383): unregister AuthInfo UpdateReceiver v2.0
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
E/SQLiteLog( 4133): (284) automatic index on shooting_modes(title_id)
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.595468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d28ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b51bf0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/GCoreUlr( 1776): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4168): MountEmulatedStorage()
E/Zygote  ( 4168): v2
I/libpersona( 4168): KNOX_SDCARD checking this for 1000
I/libpersona( 4168): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4168 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/AMMetaDataParserService( 3662): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
I/SELinux ( 4168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
D/TimaKeyStoreProvider( 4168): TimaSignature is unavailable
D/ActivityThread( 4168): Added TimaKeyStore provider
W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  286): getCameraInfo: X
I/ActivityManager( 1021): Killing 3447:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  286): getCameraInfo: X
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/AffinityControl( 4058): AffinityControl: registerfunction enter
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 4058): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4191 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/Zygote  ( 4191): MountEmulatedStorage()
E/Zygote  ( 4191): v2
I/libpersona( 4191): KNOX_SDCARD checking this for 1101
I/libpersona( 4191): KNOX_SDCARD not a persona
I/SELinux ( 4191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 3463:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.644219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d28ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b59fb8 counterpartCT=4 counterpartW=96 counterparth=96
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
D/TimaKeyStoreProvider( 4191): TimaSignature is unavailable
D/ActivityThread( 4191): Added TimaKeyStore provider
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/AMMetaDataParserService( 3662): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.acquire()
I/CalendarProvider2( 3848): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/FocusedStackFrame( 1021): Set to : 0
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : -2122120936
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1508
I/art     ( 1021): Explicit concurrent mark sweep GC freed 22375(1281KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/40MB, paused 3.015ms total 170.295ms
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
D/Launcher.HomeView( 1508): onPause
D/AndroidRuntime( 4058): Shutting down VM
D/Launcher( 1508): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, uhalitest
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference,
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
W/Settings( 3992): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 3992): startup - clean
I/GCoreUlr( 1776): Unbound from all location providers
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3447/cgroup.procs: No such file or directory
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4191): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
E/Zygote  ( 4216): MountEmulatedStorage()
E/Zygote  ( 4216): v2
I/libpersona( 4216): KNOX_SDCARD checking this for 10174
I/libpersona( 4216): KNOX_SDCARD not a persona
I/Babel   ( 3992): deleted: false for 0
I/SELinux ( 4216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4216): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4216 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/SmartcardService( 4191): main Received broadcast
V/SmartcardService( 4191): Starting smartcard service after boot completed
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3463/cgroup.procs: No such file or directory
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
D/TimaKeyStoreProvider( 4216): TimaSignature is unavailable
D/ActivityThread( 4216): Added TimaKeyStore provider
I/ActivityManager( 1021): Killing 3484:com.wssnps/1000 (adj 15): empty #31
W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/ActivityManager( 1021): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/ActivityThread( 1508): updateVisibility : ActivityRecord{17d6bf5b token=android.os.BinderProxy@2a4bf343 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/System.out( 3857): INFO:Resource not found:/Common.properties Using default values
D/Launcher.HomeView( 1508): onStop
V/ActivityThread( 1508): updateVisibility : ActivityRecord{17d6bf5b token=android.os.BinderProxy@2a4bf343 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1021): isKioskContainerExistOnDevice
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
W/ResourcesManager( 3662): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3662): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.714896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb907c920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb907c030 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/BadgeProvider( 4006): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
W/art     ( 4058): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/ActivityManager( 1021): Killing 3505:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/Process ( 4065): Sending signal. PID: 4065 SIG: 9
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1021): [SO] activate (ident=0xb8f44348, enabled=0)
,I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/BadgeProvider( 4006): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4006): sendNotify, [notify] : null
D/BadgeProvider( 4006): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4006): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4006): update, [UpdateCount] : 1
,D/SensorManager( 1021): unregisterListener ::   
,I/Sensors ( 1021): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1021): [SO] changed settle time [1]
,D/SensorService( 1021): [SO] setDelay [66000000]
D/SensorService( 1021): [SO] activate (ident=0xb8f44348, enabled=1)
D/SensorService( 1021): [SO] AR_init
,I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3662): took 2.715938ms for 0*0 texture 0
,D/SensorManager( 1021): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,W/ResourcesManager( 3977): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3977): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3977): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/GFX generate_partition_tables( 3662): took 8.870364ms for 0*0 texture 0
,I/GFX raster( 3662): took 12.574167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d25c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1021): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/AMMetaDataParserService( 3662): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.621510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3484/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3662): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/Launcher( 1508): onTrimMemory. Level: 20
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3505/cgroup.procs: No such file or directory
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3662): took 0.637812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorService( 1021): [SO] Reset Rotation Old [100], Init [1]
,E/Zygote  ( 4236): MountEmulatedStorage(),
E/Zygote  ( 4236): v2
,I/libpersona( 4236): KNOX_SDCARD checking this for 1000
I/libpersona( 4236): KNOX_SDCARD not a persona
I/SELinux ( 4236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4236): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4236 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/AMMetaDataParserService( 3662): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/Process ( 4039): Sending signal. PID: 4039 SIG: 9
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/Launcher.Model( 1508): reloadBadges entered.
I/GFX raster( 3662): took 0.787240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1021): Process com.sec.android.app.sns3 (pid 4065)(adj 0) has died(89,1086)
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4250): MountEmulatedStorage()
I/libpersona( 4250): KNOX_SDCARD checking this for 10034
E/Zygote  ( 4250): v2
I/libpersona( 4250): KNOX_SDCARD not a persona
,I/SELinux ( 4250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1021): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4250 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 4250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4250): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1021): [SO] 0.172 0.402 10.266
D/SensorService( 1021): [SO] [100 -> 255]
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.730781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,I/WebViewFactory( 4216): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3662): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1021): Process com.android.exchange (pid 4039)(adj 15) has died(88,1087)
I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
I/LibraryLoader( 4216): Time to load native libraries: 2 ms (timestamps 4042-4044)
I/LibraryLoader( 4216): Expected native library version number "",actual native library version number ""
D/TimaKeyStoreProvider( 4236): TimaSignature is unavailable
D/TimaKeyStoreProvider( 4250): TimaSignature is unavailable
D/ActivityThread( 4236): Added TimaKeyStore provider
D/ActivityThread( 4250): Added TimaKeyStore provider
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
W/ResourcesManager( 3977): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3662): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.846875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb907c920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
,V/WebViewChromiumFactoryProvider( 4216): Binding Chromium to main looper Looper (main, tid 1) {29b2b449}
I/LibraryLoader( 4216): Expected native library version number "",actual native library version number ""
I/chromium( 4216): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/GCoreUlr( 1776): DispatchingService.onDestroy()
,I/GCoreUlr( 1776): Unbound from all location providers
,W/ContextImpl( 4236): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,I/BrowserStartupController( 4216): Initializing chromium process, singleProcess=true
,W/art     ( 4216): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4216): ApplicationContext is null in ApplicationStatus
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.638281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d25c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/ActivityManager( 1021): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4273 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3662): took 0.643021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b521f8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4273): MountEmulatedStorage()
I/libpersona( 4273): KNOX_SDCARD checking this for 10157
E/Zygote  ( 4273): v2
I/libpersona( 4273): KNOX_SDCARD not a persona
,I/SELinux ( 4273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/chromium( 4216): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/SELinux ( 4273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3662): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/art     ( 3857): Suspending all threads took: 12.110ms
,E/libEGL  ( 4216): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4216): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4216): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4216): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4216): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4216): Local Branch: 
I/Adreno-EGL( 4216): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4216): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4216):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/VideoCapabilities( 3992): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3992): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 4273): TimaSignature is unavailable
,W/AudioCapabilities( 3992): Unsupported mime audio/qcelp
,D/ActivityThread( 4273): Added TimaKeyStore provider
,W/AudioCapabilities( 3992): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3992): Unsupported mime audio/mpeg-L2
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.661875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3992): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3992): Unsupported mime audio/x-ima
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,W/AudioCapabilities( 3992): Unsupported mime audio/qcelp
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,W/ResourcesManager( 4273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/AudioCapabilities( 3992): Unsupported mime audio/evrc
,I/AMMetaDataParserService( 3662): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3662): took 0.640885ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4290): MountEmulatedStorage(),
I/ActivityManager( 1021): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4290 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4290): v2
I/libpersona( 4290): KNOX_SDCARD checking this for 1000
I/SELinux ( 4290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4290): KNOX_SDCARD not a persona,
I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
I/SELinux ( 4290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3662): took 0.730208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4312): MountEmulatedStorage()
I/libpersona( 4312): KNOX_SDCARD checking this for 10159
E/Zygote  ( 4312): v2
I/libpersona( 4312): KNOX_SDCARD not a persona
W/VideoCapabilities( 3992): Unsupported mime video/wvc1
I/ActivityManager( 1021): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4312 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 3521:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
I/SELinux ( 4312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/VideoCapabilities( 3992): Unsupported mime video/x-ms-wmv
,D/TimaKeyStoreProvider( 4290): TimaSignature is unavailable
D/ActivityThread( 4290): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3662): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/SELinux ( 4312): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 3992): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3992): Unsupported mime video/wvc1
,W/VideoCapabilities( 3992): Unsupported mime video/x-ms-wmv
,I/art     (  319): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 53.048ms
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
,W/VideoCapabilities( 3992): Unsupported mime video/x-ms-wmv7
,I/AMMetaDataParserService( 3662): getResourceName:com.android.mms:xml/assistant_messaging
D/TimaKeyStoreProvider( 4312): TimaSignature is unavailable
,I/AMMetaDataParserService( 3662): getResourceTypeNamexml
D/ActivityThread( 4312): Added TimaKeyStore provider
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 17.960ms
W/VideoCapabilities( 3992): Unsupported mime video/x-ms-wmv8
,I/GFX raster( 3662): took 0.802500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb907c920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3521/cgroup.procs: No such file or directory
W/VideoCapabilities( 3992): Unsupported mime video/mp43
,I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 20.593ms
,W/VideoCapabilities( 3992): Unsupported mime video/sorenson
,I/Intent to TravelDirActivity( 4312): inside TravelBroadcastReceiver
,W/VideoCapabilities( 3992): Unsupported mime video/mp4v-esdp
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.668698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d25c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1021): Killing 3227:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/AMMetaDataParserService( 3662): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_POLICYDM( 4290): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4290): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.625365ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,W/art     ( 4216): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/AMMetaDataParserService( 3662): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,W/AwContents( 4216): onDetachedFromWindow called when already detached. Ignoring
,I/VideoCapabilities( 3992): Unsupported profile 4 for video/mp4v-es
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4290): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/PhoneWindow( 4216): *FMB* installDecor mIsFloating : false
I/GFX raster( 3662): took 0.649844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,D/PhoneWindow( 4216): *FMB* installDecor flags : -2139027200
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/AMMetaDataParserService( 3662): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
D/SystemWebViewEngine( 4216): CordovaWebView is running on device made by: samsung
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3662): took 0.634739ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4338): MountEmulatedStorage()
,I/libpersona( 4338): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4338): v2
I/libpersona( 4338): KNOX_SDCARD not a persona
I/SELinux ( 4338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4338 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4338): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Killing 3172:com.android.vending/u0a28 (adj 15): empty #31
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/ActivityManager( 1021): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 11000ms
,W/art     ( 4216): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4216): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/DBG_POLICYDM( 4290): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4290): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/TimaKeyStoreProvider( 4338): TimaSignature is unavailable
D/ActivityThread( 4338): Added TimaKeyStore provider
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.724271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4290): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
,I/AMMetaDataParserService( 3662): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.743959ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb907c920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b521f8 counterpartCT=4 counterpartW=96 counterparth=96
W/VideoCapabilities( 3992): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3992): Unrecognized profile 2130706433 for video/avc
I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,W/VideoCapabilities( 3992): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3992): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup( 1021): failed to open /acct/uid_10012/pid_3227/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10028/pid_3172/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.632760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d25c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b7d130 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4290): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4290): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,D/OpenGLRenderer( 4216): Render dirty regions requested: true
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,I/DBG_POLICYDM( 4290): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
,D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,W/chromium( 4216): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/DBG_POLICYDM( 4290): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4290): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,I/DBG_POLICYDM( 4290): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/15/13:15:55
,I/DBG_POLICYDM( 4290): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
D/PhoneWindow( 4216): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4216): *FMB* isFloatingMenuEnabled return false
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0,
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/vclib   ( 3992): onServiceConnected
,W/Babel   ( 3992): Attempted to change video mute state without an active call.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4361): MountEmulatedStorage(),
I/libpersona( 4361): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4361): v2
I/libpersona( 4361): KNOX_SDCARD not a persona
I/SELinux ( 4361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4361 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 4290): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
E/SELinux ( 4361): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit,
I/DBG_POLICYDM( 4290): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4290): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4290): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4290): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4290): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/ActivityManager( 1021): Killing 3265:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/InputDispatcher( 1021): Focus entered window: 4216,
,D/TimaKeyStoreProvider( 4361): TimaSignature is unavailable
D/SSRM:n  ( 1021): SIOP:: AP = 410
,D/ActivityThread( 4361): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4290): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 4216): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 4216): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4216): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4216): Enabling debug mode 0
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.616354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b521f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,I/ActivityManager( 1021): Displayed Component not be shown by security: +1s164ms
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{24d58097 u0 com.test.thalitest/.MainActivity t236} time:44814
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/SA      ( 4338): [SSP] onCreated
,I/SamsungIME( 1835): getCurrentCandidateView
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.639792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb87a78a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1021): failed to open /acct/uid_10009/pid_3265/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3662): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/Timeline( 4216): Timeline: Activity_idle id: android.os.BinderProxy@1924e87b time:44859
,E/SPPClientService( 4361): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4361): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 4361): PushLog.txt file is not deleted.
,D/SPPClientService( 4361): PushLog.txt file is not deleted.
,D/SPPClientService( 4361): ============PushLog. stop!
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.634114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b51538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4361): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
,E/SPPClientService( 4361): [SystemStateMoniter] Current Time : 44899
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4338): [TPM] There is no property file
,I/DBG_POLICYDM( 4290): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/SA      ( 4338): [SCU] isHaveSA() - false
,I/DBG_POLICYDM( 4290): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/SA      ( 4338): [TPM] getModelProperty : null
I/SA      ( 4338): [TPM] getCSCProperty : null
,I/SA      ( 4338): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4338): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4338): [DM] TFT FEATURE: false
,I/SA      ( 4338): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4338): [DM] init START
,D/SamsungIME( 1835): Dismiss ExpandCandiate
,I/SA      ( 4338): [DM] This device is not a Vodafone
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.750052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87a78a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SamsungIME( 1835): getDebugLevel  : 0x4f4c
,W/ResourceType( 4338): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
,W/ResourceType( 4338): No package identifier when getting value for resource number 0x00000000
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3662): getResourceName:com.android.mms:xml/assistant_messaging
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ResourceType( 4338): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourceType( 4338): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
I/GFX raster( 3662): took 0.687552ms for 96*96 texture 0
W/ResourceType( 4338): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d28ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d29b70 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourceType( 4338): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4338): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4338): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/Zygote  ( 4388): MountEmulatedStorage()
E/Zygote  ( 4388): v2
I/libpersona( 4388): KNOX_SDCARD checking this for 10166
I/libpersona( 4388): KNOX_SDCARD not a persona
,I/SELinux ( 4388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4388): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SA      ( 4338): [SCU] isHaveSA() - false
,I/SA      ( 4338): support phone number id : false
I/SA      ( 4338): [DM] Supports Ref Jpn : true
,I/ActivityManager( 1021): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4388 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 3555:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/SA      ( 4338): [DM] init END
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.666458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d25c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb87a9510 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4338): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 4338): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4338): [OR] onReceive END
,I/AMMetaDataParserService( 3662): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4388): TimaSignature is unavailable
,D/ActivityThread( 4388): Added TimaKeyStore provider
,I/SA      ( 4338): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3662): took 0.649635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b521f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4338): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3662): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/SA      ( 4338): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4338): [LBE] REF_JPN : true
I/SA      ( 4338): [BDC] create
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (-2/8)
,W/BindingManager( 4216): Cannot call determinedVisibility() - never saw a connection for the pid: 4216
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.648125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb87a78a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4338): [DBMV2] getEmailID
,I/SA      ( 4338): [DBMV2] getDataV02ForItems
,I/SamsungIME( 1835): getDebugLevel  : 0x4f4c
,I/SA      ( 4338): [SSP] query invoked
,I/AMMetaDataParserService( 3662): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4338): [SCU] get signed id from samsung account2.0 DB.
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
W/libprocessgroup( 1021): failed to open /acct/uid_10069/pid_3555/cgroup.procs: No such file or directory
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/DBG_POLICYDM( 4290): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/GFX raster( 3662): took 0.636302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b51538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SamsungIME( 1835): KeybaordView init() : load resources
,I/SA      ( 4338): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4338): [BDC] destroy
,I/ActivityManager( 1021): Killing 3574:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.821512ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
,I/AMMetaDataParserService( 3662): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.697760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d28ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
,I/SamsungIME( 1835): getCurrentKeyboard
I/SamsungIME( 1835): getTextKeyboard
,E/SQLiteLog( 1722): (10) POSIX Error : 11 SQLite Error : 3850
,I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3574/cgroup.procs: No such file or directory
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.760208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d25c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d29b70 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4388): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4388): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3662): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.619948ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b521f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb87a78a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1835): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3662): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,V/JNIHelp ( 4388): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ActivityThread( 4388): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4388): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1273262f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4388): Installed default security provider GmsCore_OpenSSL
,E/Zygote  ( 4415): MountEmulatedStorage()
,I/libpersona( 4415): KNOX_SDCARD checking this for 10012
E/Zygote  ( 4415): v2
I/libpersona( 4415): KNOX_SDCARD not a persona
I/SELinux ( 4415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4415 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 4415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4415): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4415): TimaSignature is unavailable
,D/ActivityThread( 4415): Added TimaKeyStore provider
,D/JsMessageQueue( 4216): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 4415): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4415): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.641667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b7ab48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b3fa50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/MultiDex( 4415): VM with version 2.1.0 has multidex support
I/MultiDex( 4415): install
I/MultiDex( 4415): VM has multidex support, MultiDex support library is disabled.
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.657448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8b51538 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b51858 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,V/JNIHelp ( 4415): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.825520ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb8d29848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5c278 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
D/jxcore_app_log( 4216): JniHelper::setJavaVM(0xb87a1450), pthread_self() = -1194297360
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788a586 added. We now have 1 listener(s)
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$Servi,ceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): setBluetoothMacAddress: 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4216): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4216): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4216): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4216): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Bluetooth MAC address: 7C:F9:0E:51:18:22
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169d979d added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4216): addListener: New listener added - the number of listeners is now 1
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131165197
W/ResourcesManager( 3662): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityThread( 4415): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4415): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2038a20d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4415): Installed default security provider GmsCore_OpenSSL
I/AMMetaDataParserService( 3662): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4216): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4216): setScanMode: 1 -> 2
I/AMMetaDataParserService( 3662): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4216): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4216): initialize: My bluetooth address is 7C:F9:0E:51:18:22
I/ActivityManager( 1021): Killing 3592:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
I/AMMetaDataParserService( 3662): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
V/io.jxcore.node.ConnectivityMonitor( 4216): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 4216):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 4216):     - is Bluetooth LE multiple advertisement supported: SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 4216):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4216):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4216):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 4216):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 4216):     - active network type is Wi-Fi: true
D/io.jxcore.node.JXcoreExtension( 4216): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 4216): start: OK
V/io.jxcore.node.ConnectivityMonitor( 4216): updateConnectivityInfo: No relevant state changes
V/io.jxcore.node.ConnectivityMonitor( 4216): updateConnectivityInfo: No relevant state changes
,I/AMMetaDataParserService( 3662): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1021): failed to open /acct/uid_10014/pid_3592/cgroup.procs: No such file or directory,
D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,I/chromium( 4216): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1445): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1445): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131165197
,V/HeadsetService( 2714): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2714): Disconnected process message: 10
,I/AMMetaDataParserService( 3662): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/AMMetaDataParserService( 3662): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/art     ( 4216): Background sticky concurrent mark sweep GC freed 26790(2MB) AllocSpace objects, 8(128KB) LOS objects, 0% free, 11MB/11MB, paused 24.101ms total 98.998ms
,I/AMMetaDataParserService( 3662): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3662): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/art     ( 4388): Suspending all threads took: 12.074ms
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,V/AlarmManager( 1021): waitForAlarm result :4
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131165197
,I/AMMetaDataParserService( 3662): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,I/AMMetaDataParserService( 3662): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3662): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3662): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3662): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131099648
,I/iu.UploadsManager( 1903): End new media; added: 0, uploading: 0, time: 118 ms
,W/ResourcesManager( 3662): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3662): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3662): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3662): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,E/YouTube MDX( 4388): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/dex2oat ( 4446): ----------------------------------------------------
I/dex2oat ( 4446): <SS>: S T A R T I N G . . .
I/dex2oat ( 4446): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 4446): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1930133188.jar --oat-fd=25 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1930133188.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 4446): dex2oat took 50.720ms (threads: 4)
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:assistant
I/AMMetaDataParserService( 3662): Resource data:2131165220
,W/ResourcesManager( 3662): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3662): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3662): getResourceTypeNamexml
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.714114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb9278a38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9278768 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3662): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3662): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3662): took 0.611875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3662): Bitmap=0xb9278888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb928bd18 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3662): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/ActivityManager( 1021): Killing 3653:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
,I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/art     ( 4388): Suspending all threads took: 5.014ms
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Lo,op for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3662): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3662): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3662): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1021): failed to open /acct/uid_10125/pid_3653/cgroup.procs: No such file or directory
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{120ba211 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4388): Found 10012
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/AndroidHttpClient( 4388): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/AndroidHttpClient( 4388): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 4388): Thread-739(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/Zygote  ( 4501): MountEmulatedStorage()
E/Zygote  ( 4501): v2
I/libpersona( 4501): KNOX_SDCARD checking this for 10101
I/libpersona( 4501): KNOX_SDCARD not a persona
I/System.out( 4388): Thread-739(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4388): Thread-739(ApacheHTTPLog):isShipBuild true
I/System.out( 4388): Thread-739(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4388): Thread-739(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/SELinux ( 4501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/EnterpriseController(  278): uids 10166
I/SELinux ( 4501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10166
,E/SELinux ( 4501): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4501 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/TimaKeyStoreProvider( 4501): TimaSignature is unavailable
,D/ActivityThread( 4501): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 3662:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3662/cgroup.procs: No such file or directory
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/jxcore-log( 4216): Initializing JXcore engine
W/jxcore-log( 4216): JXcore engine is ready
,I/Gmail   ( 4501): getAccountsCursor
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/audit   ( 1967): type=1400 msg=audit(1458044157.881:205): avc:  denied  { ioctl } for  pid=4437 comm="Thread-666" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1967):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1967): type=1300 msg=audit(1458044157.881:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=9b8018f8 items=0 ppid=319 ppcomm=main pid=4437 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-666" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1967): type=1320 msg=audit(1458044157.881:205): 
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4501): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/jxcore-log( 4216): Starting JXcore engine
,I/System.out( 4388): Thread-739 calls detatch()
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4501): Observing account changes for notifications
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 4501): Error finding the version of the Email provider.....
E/Gmail   ( 4501): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4501): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 4501): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4501): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4501): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4501): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 4501): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4501): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4501): getAccountsCursor
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 4216): Platform android
W/jxcore-log( 4216): 
,W/jxcore-log( 4216): Process ARCH arm
W/jxcore-log( 4216): 
,E/Zygote  ( 4537): MountEmulatedStorage()
,E/Zygote  ( 4537): v2
I/libpersona( 4537): KNOX_SDCARD checking this for 10092
I/libpersona( 4537): KNOX_SDCARD not a persona
I/SELinux ( 4537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4537 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/SELinux ( 4537): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider( 4537): TimaSignature is unavailable
,D/ActivityThread( 4537): Added TimaKeyStore provider
,E/SQLiteLog( 4501): (283) recovered 37 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,E/File    ( 4501): fail readDirectory() errno=2
,I/Gmail   ( 4501): notifyAccountChanged
,I/Gmail   ( 4501): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4501): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 37372(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/40MB, paused 2.760ms total 172.203ms
,I/Gmail   ( 4501): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4501): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 4501): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d1130e5 that was originally bound here
E/ActivityThread( 4501): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d1130e5 that was originally bound here
E/ActivityThread( 4501): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4501): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4501): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4501): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4501): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4501): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4501): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4501): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4501): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4501): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4501): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4501): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4501): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4501): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4501): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1021): Unbind failed: could not find connection for android.os.BinderProxy@18c1df46
,I/Gmail   ( 4501): getAccountsCursor
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 4501): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4501): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 4501): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,I/ActivityManager( 1021): Killing 3705:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Gmail   ( 4501): getAccountsCursor
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1021): failed to open /acct/uid_10131/pid_3705/cgroup.procs: No such file or directory
,V/GLSActivity( 1722): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerService( 1021): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1021): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1021): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1021): lcd : 19 +
,D/lights  ( 1021): lcd : 19 -
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 19 -> 19
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,D/DisplayPowerController( 1021): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4557): MountEmulatedStorage()
,E/Zygote  ( 4557): v2
I/libpersona( 4557): KNOX_SDCARD checking this for 10092
I/libpersona( 4557): KNOX_SDCARD not a persona
,I/SELinux ( 4557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4557 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4557): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4557): TimaSignature is unavailable
,D/ActivityThread( 4557): Added TimaKeyStore provider
,I/jxcore-log( 4216): JXcore Cordova bridge is ready!
I/jxcore-log( 4216): 
,W/jxcore-log( 4216): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4216): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4216): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/DBG_POLICYDM( 4290): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/jxcore  ( 4216): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4216): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/DBG_POLICYDM( 4290): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/com.dropbox.android.service.DropboxNetworkReceiver( 4537): Setting receiver enabled: false
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/chromium( 4216): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/chromium( 4216): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
D/FocusedStackFrame( 1021): Set to : 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 4216
I/DBG_POLICYDM( 4290): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (157 us)
,W/PluginManager( 4216): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
,E/ActivityThread( 4537): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/SensorService( 1021): [SO] activate (ident=0xb8f44348, enabled=0)
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1508): onRestart, Launcher: 644365180,
I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
I/ActivityManager( 1021): Killing 3737:com.android.managedprovisioning/u0a22 (adj 15): empty #31
D/Launcher( 1508): onStart, Launcher: 644365180
D/Launcher.HomeView( 1508): onStart
D/Launcher( 1508): onResume, Launcher: 644365180
D/SettingsProvider( 1021): name = kids_home_mode
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10007
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
D/SensorManager( 1021): unregisterListener ::   
I/Sensors ( 1021): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1021): [SO] changed settle time [0]
D/SensorService( 1021): [SO] setDelay [200000000]
D/SensorService( 1021): [SO] activate (ident=0xb9017a90, enabled=1)
D/SensorService( 1021): [SO] AR_init
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/Launcher.HomeView( 1508): onResume
,D/SensorManager( 1021): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/Launcher( 1508): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1508): onResume
,D/ActivityManager( 1021): handle home activity for 0
,I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1021): post home show event for user 0
,D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1021): Focus entered window: 1508
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1508): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1508): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,W/IInputConnectionWrapper( 4216): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1835): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/dbxyzptlk.db300200.aw.h( 4537): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,I/Timeline( 1508): Timeline: Activity_idle id: android.os.BinderProxy@2a4bf343 time:48152,
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/breakpad( 4537): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
I/dbxyzptlk.db300200.aw.h( 4537): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
I/dbxyzptlk.db300200.aw.h( 4537): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,I/ActivityManager( 1021): Displayed Component not be shown by security: +142ms
,W/libprocessgroup( 1021): failed to open /acct/uid_10022/pid_3737/cgroup.procs: No such file or directory
,D/SensorService( 1021): [SO] Reset Rotation Old [100], Init [1]
,D/AndroidRuntime( 4575): 
D/AndroidRuntime( 4575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4575): CheckJNI is OFF,
D/AndroidRuntime( 4575): readGMSProperty: start
D/AndroidRuntime( 4575): readGMSProperty: already setted!!
D/AndroidRuntime( 4575): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4575): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4575): readGMSProperty: end
D/AndroidRuntime( 4575): addProductProperty: start
I/libDropboxSync.so( 4537): Setting global terminate handler.
,I/dbxyzptlk.db300200.aw.h( 4537): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,I/com.dropbox.sync.android.L( 4537): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/com.dropbox.sync.android.L( 4537): Removing unclaimed file/directory in cache: "local-dbapp_noauth",
,I/com.dropbox.sync.android.bf( 4537): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,W/art     ( 4537): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4537): Attempt to remove local handle scope entry from IRT, ignoring
,E/AffinityControl( 4575): AffinityControl: registerfunction enter,
,I/com.dropbox.sync.android.aS( 4537): Created NativeDbappNoAuthClientProvider
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,D/SensorService( 1021): [SO] currT = 48471066000, prevT = 48001082000, diff = 469984000, [0.192 0.402 10.247]
,D/SensorService( 1021): [SO] 0.192 0.402 10.247
W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/SensorService( 1021): [SO] [100 -> 255]
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,D/AndroidRuntime( 4575): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1021): START PACKAGE DELETE: observer{702578955}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{2}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1021): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 4216:com.test.thalitest/u0a174 (adj 1): stop com.test.thalitest cause uninstall pkg
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/System.out( 4537): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4537): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4537): (HTTPLog)-Static: isShipBuild true
I/System.out( 4537): (HTTPLog)-Thread-702-671335484: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4537): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10092
,D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10092
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (7/8)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/8)
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{2a575571 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:48592
,E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
,W/PackageSettings( 1021): Skipping PackageSetting{26ccd8e com.example.hello/10175} due to missing metadata
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
,I/System.out( 4537): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1835): mOCRHelper is null
,W/GeofencerStateMachine( 1776): Ignoring removeGeofence because network location is disabled.
,V/NetworkStats( 1021): removeUidsLocked() for UIDs [10174]
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
V/NetworkStats( 1021): performPollLocked(flags=0x3)
,D/RegisteredComponentCache( 1468): Collect Tech packages for Knox
,D/PersonaManager( 1468): isKioskContainerExistOnDevice
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,V/NetworkStats( 1021): performPollLocked() took 12ms
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,I/com.dropbox.sync.android.DbxSyncService( 4537): DbxSyncService starting.
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,E/Zygote  ( 4608): MountEmulatedStorage()
E/Zygote  ( 4608): v2
I/libpersona( 4608): KNOX_SDCARD checking this for 10057
I/libpersona( 4608): KNOX_SDCARD not a persona
,I/SELinux ( 4608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4608 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,I/SELinux ( 4608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 4608): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 1468): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1468): empty dynamic service
,I/ActivityManager( 1021): Killing 3629:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1021): no available spell checker services found
,D/TimaKeyStoreProvider( 4608): TimaSignature is unavailable
,D/ActivityThread( 4608): Added TimaKeyStore provider
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/com.dropbox.sync.android.aF( 4537): Created new socket: SSL socket over Socket[address=api.dropbox.com/108.160.172.205,port=443,localPort=60935]
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1021): PackageReceiver onReceive()
,I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1021): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1021): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1021): DBIntegrity::getInstance - New instance created
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/OTPFW   ( 1021): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,I/OTPFW   ( 1021): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1021): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10174
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10174
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
,D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1021): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1021): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1021): failed to open /acct/uid_10015/pid_3629/cgroup.procs: No such file or directory
,D/WallpaperManager( 1508): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1508): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/DBG_DM  ( 3115): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 37836(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/45MB, paused 5.771ms total 356.773ms
,D/PackageManager( 1021): delete codoeFile: 
,D/AASAuninstall( 1021): userId = 0, info.removedAppID = 10174, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10174 Target=com.test.thalitest
,D/PackageManager( 1021): result of delete: 1{702578955}
,D/AndroidRuntime( 4575): Shutting down VM
,D/TaskPersister( 1021): removeObsoleteFile: deleting file=236_task.xml
,D/TaskPersister( 1021): removeObsoleteFile: deleting file=236_task_thumbnail.png
,D/LocationManagerService( 1021): getProviders()=[passive]
,E/SMD     (  291): DCD OFF
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4629): MountEmulatedStorage()
E/Zygote  ( 4629): v2
I/libpersona( 4629): KNOX_SDCARD checking this for 10015
I/libpersona( 4629): KNOX_SDCARD not a persona
,I/SELinux ( 4629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4629 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 4629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4629): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/TimaKeyStoreProvider( 4629): TimaSignature is unavailable
,D/ActivityThread( 4629): Added TimaKeyStore provider
,W/art     ( 4575): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/PackageManager( 1021): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1021): userId{-1}
D/PackageManager( 1021): andCode{true}
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/splitIntent( 1021): Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/AlarmManager( 1021): waitForAlarm result :8
,I/ActivityManager( 1021): Killing 3757:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 3717:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/ActivityManager( 1021): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/accuweather( 1610): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1610): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1610): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1610): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1610): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1610): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1610): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/accuweather( 1610): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1610): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/accuweather( 1610): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 16
,D/ActivityManager( 1021): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Search.SharedPreferencesProto( 4608): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak

```
