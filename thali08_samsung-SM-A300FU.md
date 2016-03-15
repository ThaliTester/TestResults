#### Test 62947189e430ee9_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-15 19:11:32.278  4134  4157 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
03-15 19:11:32.288  4296  4296 E Zygote  : MountEmulatedStorage()
03-15 19:11:32.288  4296  4296 E Zygote  : v2
03-15 19:11:32.288  4296  4296 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
--------- beginning of system
03-15 19:11:32.288  4296  4296 I libpersona: KNOX_SDCARD checking this for 10142
03-15 19:11:32.288  4296  4296 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:32.288  1019  3387 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4296 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-15 19:11:32.298  4296  4296 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:32.298  4296  4296 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:32.298  1019  1571 I ActivityManager: Killing 3527:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
03-15 19:11:32.298  1019  1571 I ActivityManager: Killing 3449:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #32
03-15 19:11:32.308  4272  4272 D BadgeProvider: onCreate
03-15 19:11:32.308  4272  4272 D BadgeProvider: DatabaseHelper
03-15 19:11:32.318  4296  4296 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:32.328  4296  4296 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:32.338  4296  4296 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 19:11:32.348  1019  3633 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-15 19:11:32.358  4219  4295 I Process : Sending signal. PID: 4219 SIG: 9
03-15 19:11:32.358  1019  1031 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
03-15 19:11:32.378  4272  4281 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 19:11:32.388  1019  1097 V AlarmManager: waitForAlarm result :8
03-15 19:11:32.398  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.398  3849  3918 I GFX raster: took 0.541250ms for 96*96 texture 0
03-15 19:11:32.398  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7752ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7753438 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.408  3849  3918 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
03-15 19:11:32.418  1019  1041 W libprocessgroup: failed to open /acct/uid_10095/pid_3413/cgroup.procs: No such file or directory
03-15 19:11:32.418  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3434/cgroup.procs: No such file or directory
03-15 19:11:32.418  1019  1041 W libprocessgroup: failed to open /acct/uid_10098/pid_3449/cgroup.procs: No such file or directory
03-15 19:11:32.418  4083  4083 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-15 19:11:32.418  1019  1041 W libprocessgroup: failed to open /acct/uid_10055/pid_3527/cgroup.procs: No such file or directory
03-15 19:11:32.418  4083  4083 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-15 19:11:32.418  4253  4253 I SA      : [SSP] onCreated
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-15 19:11:32.418  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: Resource data:2131034112
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-15 19:11:32.428  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:32.428  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.428  3849  3918 I GFX raster: took 0.616458ms for 96*96 texture 0
03-15 19:11:32.428  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776ea18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7412588 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.438  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
03-15 19:11:32.458  1019  1571 I ActivityManager: Process com.android.email (pid 4219)(adj 9) has died(50,617)
03-15 19:11:32.478  4083  4242 D Volley  : [618] DiskBasedCache.clear: Cache cleared.
03-15 19:11:32.478  4083  4216 D Volley  : [611] DiskBasedCache.clear: Cache cleared.
03-15 19:11:32.488  1019  1031 I ActivityManager: Killing 3258:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
03-15 19:11:32.498  4083  4319 D Ads     : Skipping gmscore version check
03-15 19:11:32.518  1019  3633 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.518  1019  1140 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.518  1019  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:32.518  1019  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
03-15 19:11:32.528  1019  1340 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.528  1019  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:32.528  1019  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
03-15 19:11:32.538  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.538  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.538  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.538  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.558  4322  4322 E Zygote  : MountEmulatedStorage()
03-15 19:11:32.558  4322  4322 E Zygote  : v2
03-15 19:11:32.558  4322  4322 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:32.558  4322  4322 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:32.558  4322  4322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:32.558  1019  3631 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 19:11:32.568  4322  4322 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:32.568  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.568  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:32.568  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
03-15 19:11:32.568  4322  4322 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:32.578  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.578  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.578  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.578  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.588  4253  4253 I SA      : [TPM] There is no property file
03-15 19:11:32.588  4253  4253 I SA      : [SCU] isHaveSA() - false
03-15 19:11:32.588  4253  4253 I SA      : [TPM] getModelProperty : null
03-15 19:11:32.598  4339  4339 E Zygote  : MountEmulatedStorage()
03-15 19:11:32.598  4339  4339 E Zygote  : v2
03-15 19:11:32.598  4253  4253 I SA      : [TPM] getCSCProperty : null
03-15 19:11:32.598  4253  4253 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-15 19:11:32.598  4253  4253 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-15 19:11:32.598  4253  4253 I SA      : [DM] TFT FEATURE: false
03-15 19:11:32.598  4339  4339 I libpersona: KNOX_SDCARD checking this for 10141
03-15 19:11:32.598  4339  4339 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:32.598  4339  4339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:32.598  4253  4253 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-15 19:11:32.598  1019  1031 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4339 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-15 19:11:32.608  4253  4253 I SA      : [DM] init START
03-15 19:11:32.608  4339  4339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:32.608  4339  4339 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:32.608  4322  4322 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:32.608  4322  4322 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:32.618  4253  4253 I SA      : [DM] This device is not a Vodafone
03-15 19:11:32.628   307   307 I art     : Explicit concurrent mark sweep GC freed 8712(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 638us total 20.972ms
03-15 19:11:32.628  4083  4083 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-15 19:11:32.628  4083  4083 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
03-15 19:11:32.638   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 17.418ms
03-15 19:11:32.648  4339  4339 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:32.648  4339  4339 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:32.658  1019  1140 I ActivityManager: Killing 3568:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
03-15 19:11:32.658   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 17.006ms
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
03-15 19:11:32.668  4253  4253 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
03-15 19:11:32.678  4339  4339 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-15 19:11:32.678  4339  4339 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-15 19:11:32.678  4339  4339 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
03-15 19:11:32.678  4339  4339 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-15 19:11:32.678  4253  4253 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-15 19:11:32.688  4083  4083 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
03-15 19:11:32.688  4253  4253 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
03-15 19:11:32.698  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.698  1019  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:32.698  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
03-15 19:11:32.698  4253  4253 I SA      : [SCU] isHaveSA() - false
03-15 19:11:32.698  4253  4253 I SA      : support phone number id : false
03-15 19:11:32.698  4253  4253 I SA      : [DM] Supports Ref Jpn : true
03-15 19:11:32.698  4253  4253 I SA      : [DM] init END
03-15 19:11:32.708  4253  4253 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-15 19:11:32.708  4253  4253 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
03-15 19:11:32.708  1019  3631 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.708  1019  3631 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-15 19:11:32.708  1019  3631 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
03-15 19:11:32.718  4253  4253 I SA      : [OR] onReceive END
03-15 19:11:32.738  4253  4253 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-15 19:11:32.738  4253  4253 I SA      : [ODM] queryOpenData(key= GEO_IP )
03-15 19:11:32.748  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.748  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.748  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.748  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.758  4253  4253 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-15 19:11:32.758  4253  4253 I SA      : [LBE] REF_JPN : true
03-15 19:11:32.758  4253  4253 I SA      : [BDC] create
03-15 19:11:32.758  4360  4360 E Zygote  : MountEmulatedStorage()
03-15 19:11:32.758  4360  4360 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:32.758  4360  4360 E Zygote  : v2
03-15 19:11:32.758  4360  4360 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:32.758  4360  4360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:32.768  4360  4360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:32.768  4360  4360 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:32.768  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.768  3849  3918 I GFX raster: took 0.603385ms for 96*96 texture 0
03-15 19:11:32.768  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776ea18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7752990 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.768  1019  1570 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.768  1019  1340 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4360 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 19:11:32.768  1019  1340 I ActivityManager: Killing 3550:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
03-15 19:11:32.778  1019  3631 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.788  1019  1041 W libprocessgroup: failed to open /acct/uid_10008/pid_3258/cgroup.procs: No such file or directory
03-15 19:11:32.788  1019  1041 W libprocessgroup: failed to open /acct/uid_10056/pid_3568/cgroup.procs: No such file or directory
03-15 19:11:32.788  3849  3918 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
03-15 19:11:32.798  4083  4083 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
03-15 19:11:32.798  4360  4360 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:32.798  1019  1340 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.798  4360  4360 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:32.808  4253  4253 I SA      : [DBMV2] getEmailID
03-15 19:11:32.808  4253  4253 I SA      : [DBMV2] getDataV02ForItems
03-15 19:11:32.808  4253  4253 I SA      : [SSP] query invoked
03-15 19:11:32.818  4253  4253 I SA      : [SCU] get signed id from samsung account2.0 DB.
03-15 19:11:32.818  1019  3387 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.818  4253  4253 I SA      : [SCU] get signed id from samsung account1.0 DB.
03-15 19:11:32.818  4253  4253 I SA      : [BDC] destroy
03-15 19:11:32.828  1019  1524 I ActivityManager: Killing 3329:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-15 19:11:32.828  2130  3724 I Icing   : Internal init done: storage state 0
03-15 19:11:32.828  1019  3633 I ActivityManager: Killing 3625:com.android.managedprovisioning/u0a20 (adj 15): empty #31
03-15 19:11:32.858  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.858  2130  3724 I Icing   : Post-init done
03-15 19:11:32.858  3849  3918 I GFX raster: took 0.801042ms for 96*96 texture 0
03-15 19:11:32.858  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7405ef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb773f8f8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.878  3849  3918 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
03-15 19:11:32.878  1019  1345 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.878  1019  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:32.878  1019  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:32.888  4360  4360 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:32.888  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.898  3849  3918 I GFX raster: took 1.365260ms for 96*96 texture 0
03-15 19:11:32.898  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73adf20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7753438 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.898  4360  4360 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:32.898  4360  4360 D SecurityLogAgent: StateMachine : Current State = 1
03-15 19:11:32.898  4360  4360 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
03-15 19:11:32.898  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
03-15 19:11:32.908  1019  1041 W libprocessgroup: failed to open /acct/uid_10013/pid_3550/cgroup.procs: No such file or directory
03-15 19:11:32.918  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.918  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.918  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.918  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.918  1019  1571 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.928  1019  1515 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-15 19:11:32.938  4390  4390 I libpersona: KNOX_SDCARD checking this for 10148
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-15 19:11:32.938  4390  4390 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-15 19:11:32.938  4390  4390 E Zygote  : MountEmulatedStorage()
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-15 19:11:32.938  4390  4390 E Zygote  : v2
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-15 19:11:32.938  1019  3387 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4390 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: Resource data:2131034113
03-15 19:11:32.938  4390  4390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 19:11:32.938  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:32.938  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.938  3849  3918 I GFX raster: took 0.845468ms for 96*96 texture 0
03-15 19:11:32.938  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776ea18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb776df40 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.938  4390  4390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:32.938  4390  4390 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:32.948  1019  3387 I ActivityManager: Killing 3479:com.google.android.gm/u0a99 (adj 15): empty #31
03-15 19:11:32.948  3849  3918 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-15 19:11:32.958  4390  4390 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:32.958  4390  4390 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:32.968  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.968  3849  3918 I GFX raster: took 0.832343ms for 96*96 texture 0
03-15 19:11:32.968  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776ea18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74ade80 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:32.978  1019  1515 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.978  1019  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:32.978  1019  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:32.978  4316  4316 D AndroidRuntime: 
03-15 19:11:32.978  4316  4316 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 19:11:32.988  4316  4316 D AndroidRuntime: CheckJNI is OFF
03-15 19:11:32.988  4316  4316 D AndroidRuntime: readGMSProperty: start
03-15 19:11:32.988  4316  4316 D AndroidRuntime: readGMSProperty: already setted!!
03-15 19:11:32.988  4316  4316 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-15 19:11:32.988  4316  4316 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-15 19:11:32.988  4316  4316 D AndroidRuntime: readGMSProperty: end
03-15 19:11:32.988  4316  4316 D AndroidRuntime: addProductProperty: start
03-15 19:11:32.998  3849  3918 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-15 19:11:33.018  4390  4390 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-15 19:11:33.028  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{2e53964c u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
03-15 19:11:33.048  4272  4284 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-15 19:11:33.058  1019  1340 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.058  1019  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.058  1019  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
03-15 19:11:33.068  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.068  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.068  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.068  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.088  1509  1509 D Launcher.Model: reloadBadges entered.
03-15 19:11:33.088  4272  4281 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-15 19:11:33.088  4272  4281 D BadgeProvider: sendNotify, [notify] : null
03-15 19:11:33.088  4272  4281 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 19:11:33.088  4272  4281 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-15 19:11:33.088  4272  4281 D BadgeProvider: update, [UpdateCount] : 1
03-15 19:11:33.088  4408  4408 E Zygote  : MountEmulatedStorage()
03-15 19:11:33.088  4408  4408 E Zygote  : v2
03-15 19:11:33.088  4408  4408 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:33.088  4408  4408 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:33.098  4408  4408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:33.098  1019  1032 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4408 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-15 19:11:33.108  4408  4408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:33.108  4408  4408 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:33.108  1019  3387 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.108  1019  3387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:33.108  1019  3387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:33.108  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.108  3849  3918 I GFX raster: took 0.638853ms for 96*96 texture 0
03-15 19:11:33.108  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7787530 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb776df40 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:33.118  1019  1515 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.118  1019  1515 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.118  1019  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
03-15 19:11:33.118  3849  3918 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
03-15 19:11:33.128  1019  1031 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
03-15 19:11:33.138  4296  4329 I Process : Sending signal. PID: 4296 SIG: 9
03-15 19:11:33.148  4408  4408 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:33.148  4408  4408 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:33.178  1019  1345 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
03-15 19:11:33.178  1019  1345 I ActivityManager: Killing 3644:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
03-15 19:11:33.178  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
03-15 19:11:33.188  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.188  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.188  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
03-15 19:11:33.188  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-15 19:11:33.188  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 19:11:33.188  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-15 19:11:33.198  1019  1571 I ActivityManager: Process com.android.exchange (pid 4296)(adj 15) has died(44,628)
03-15 19:11:33.228  1019  1041 W libprocessgroup: failed to open /acct/uid_10020/pid_3625/cgroup.procs: No such file or directory
03-15 19:11:33.228  1019  1041 W libprocessgroup: failed to open /acct/uid_10014/pid_3329/cgroup.procs: No such file or directory
03-15 19:11:33.238  1019  1041 W libprocessgroup: failed to open /acct/uid_10099/pid_3479/cgroup.procs: No such file or directory
03-15 19:11:33.248  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.248  3849  3918 I GFX raster: took 0.632709ms for 96*96 texture 0
03-15 19:11:33.248  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb774a970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74ade80 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:33.258  3849  3918 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
03-15 19:11:33.278  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.278  3849  3918 I GFX raster: took 0.816614ms for 96*96 texture 0
03-15 19:11:33.278  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776d080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb776df40 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:33.278  3849  3918 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
03-15 19:11:33.328  1019  1097 V AlarmManager: waitForAlarm result :4
03-15 19:11:33.338  1019  1097 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.338  1019  1097 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.338  1019  1097 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.338  1019  1097 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.338  1019  1570 I art     : Explicit concurrent mark sweep GC freed 26005(1337KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 2.586ms total 151.836ms
03-15 19:11:33.338  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.348  3849  3918 I GFX raster: took 0.679218ms for 96*96 texture 0
03-15 19:11:33.348  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73adf20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74ade80 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:33.348  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
03-15 19:11:33.358  4433  4433 E Zygote  : MountEmulatedStorage()
03-15 19:11:33.358  4433  4433 I libpersona: KNOX_SDCARD checking this for 10117
03-15 19:11:33.358  4433  4433 E Zygote  : v2
03-15 19:11:33.358  4433  4433 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:33.358  4433  4433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:33.358  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-15 19:11:33.358  4433  4433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:33.358  4433  4433 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 19:11:33.358  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.358  3849  3918 I GFX raster: took 0.721354ms for 96*96 texture 0
03-15 19:11:33.358  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776df40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74ade80 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:33.368  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
03-15 19:11:33.378  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-15 19:11:33.378  1019  1097 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4433 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-15 19:11:33.388  1807  1807 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
03-15 19:11:33.388  1807  1807 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 19:11:33.388  1807  1807 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-15 19:11:33.388  1807  1807 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-15 19:11:33.388  1807  1807 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 19:11:33.388  1807  1807 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-15 19:11:33.388  1807  1807 D daemonapp: [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
03-15 19:11:33.388  4433  4433 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:33.388  4433  4433 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:33.398  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-15 19:11:33.398  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 19:11:33.418  4316  4316 E AffinityControl: AffinityControl: registerfunction enter
03-15 19:11:33.428  4433  4433 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:33.428  1019  1262 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-15 19:11:33.438  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-15 19:11:33.438  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.438  3849  3918 I GFX raster: took 0.516510ms for 96*96 texture 0
03-15 19:11:33.438  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ade80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb776d4a0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:33.448  3849  3918 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
03-15 19:11:33.448  1807  1807 D daemonapp: [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
03-15 19:11:33.448  1019  1345 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.448  1019  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.448  1019  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.458  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.458  4316  4316 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 19:11:33.458  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.458  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-15 19:11:33.458  1019  1524 I ActivityManager: Killing 3660:com.google.android.talk/u0a102 (adj 15): empty #31
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-15 19:11:33.458  3849  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-15 19:11:33.458  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-15 19:11:33.488  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.488  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.488  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-15 19:11:33.488  1727  1727 I Hs20UtilService: Starting #5
03-15 19:11:33.488  1727  1784 I Hs20UtilService: Message received 5007
03-15 19:11:33.498  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-15 19:11:33.498  1325  1325 I NearbySettings: MountReceiver.onReceive - Keep current state
03-15 19:11:33.508  1019  1140 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.508  1019  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.508  1019  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.508  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.508  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.508  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:33.508  3849  3918 I AMMetaDataParserService: Resource data:2131165203
03-15 19:11:33.518  3849  3918 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 19:11:33.518  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.518  3849  3918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:33.518  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.518  3849  3918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:33.518  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.518  3849  3918 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:33.518  3849  3918 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-15 19:11:33.518  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:33.518  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.518  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.518  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.528  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.528  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.528  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.528  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.528  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.528  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.528  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.538  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.538  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.538  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.538  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.548  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.548  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.548  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.548  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.548  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.548  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.558  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.558  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.558  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.558  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-15 19:11:33.558  1019  1515 E PersonaManagerService: inState():  stateMachine is null !!
03-15 19:11:33.558  1019  1515 I PersonaManagerService: PersonaId don't exist
03-15 19:11:33.558  1019  1515 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-15 19:11:33.558  3849  3918 I GFX construct_block_size_descriptor_2d second part: took 3.503752ms for 0*0 texture 0
03-15 19:11:33.558  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.558  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.558  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.568  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.568  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.568  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.568  1019  1041 W libprocessgroup: failed to open /acct/uid_10058/pid_3644/cgroup.procs: No such file or directory
03-15 19:11:33.568  1019  1041 W libprocessgroup: failed to open /acct/uid_10102/pid_3660/cgroup.procs: No such file or directory
03-15 19:11:33.568  1019  1515 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 19:11:33.578  3849  3918 I GFX generate_partition_tables: took 17.093591ms for 0*0 texture 0
03-15 19:11:33.578  3849  3918 I GFX raster: took 21.216562ms for 80*80 texture 0
03-15 19:11:33.578  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7769f58 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb776ac18 counterpartCT=4 counterpartW=80 counterparth=80
03-15 19:11:33.578  3849  3918 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
03-15 19:11:33.618  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-15 19:11:33.618  1019  1515 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 19:11:33.618  3849  3918 I GFX construct_block_size_descriptor_2d second part: took 2.095417ms for 0*0 texture 0
03-15 19:11:33.618  1019  1515 W ActivityManager: mDVFSHelper.acquire()
03-15 19:11:33.618  3849  3918 I GFX generate_partition_tables: took 5.047916ms for 0*0 texture 0
03-15 19:11:33.628  3849  3918 I GFX raster: took 8.233335ms for 80*80 texture 0
03-15 19:11:33.628  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ade328 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7ade3d0 counterpartCT=4 counterpartW=80 counterparth=80
03-15 19:11:33.628  3849  3918 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
03-15 19:11:33.688  1019  1515 D FocusedStackFrame: Set to : 0
03-15 19:11:33.718  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 19:11:33.718  1019  1515 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 19:11:33.718  1019  1515 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 19:11:33.718  1019  1515 D InputDispatcher: Focused application set to: xxxx
03-15 19:11:33.718  1019  1515 D InputDispatcher: Focus left window: 1509
03-15 19:11:33.718  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-15 19:11:33.728  4316  4316 D AndroidRuntime: Shutting down VM
03-15 19:11:33.728  1509  1509 D Launcher.HomeView: onPause
03-15 19:11:33.728  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 19:11:33.728  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.728  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.728  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.728  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:33.728  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 19:11:33.738  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.738  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.738  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.738  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-15 19:11:33.738  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.738  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.738  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.738  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 19:11:33.738  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-15 19:11:33.748   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-15 19:11:33.748  3849  3918 I GFX raster: took 0.739583ms for 80*80 texture 0
03-15 19:11:33.748  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ade328 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7adbb98 counterpartCT=4 counterpartW=80 counterparth=80
03-15 19:11:33.748  3849  3918 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
03-15 19:11:33.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.768  4453  4453 E Zygote  : MountEmulatedStorage()
03-15 19:11:33.768  4453  4453 E Zygote  : v2
03-15 19:11:33.768  4453  4453 I libpersona: KNOX_SDCARD checking this for 10167
03-15 19:11:33.768  4453  4453 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:33.778  4453  4453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:33.778  4453  4453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:33.778  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-15 19:11:33.778  1019  3633 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4453 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 19:11:33.778  3849  3918 I GFX raster: took 0.704532ms for 80*80 texture 0
03-15 19:11:33.778  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ade328 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7ada408 counterpartCT=4 counterpartW=80 counterparth=80
03-15 19:11:33.788  4453  4453 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 19:11:33.788  3849  3918 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
03-15 19:11:33.808  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.808  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.808  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.808  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.808  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.808  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.818  1019  3631 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.818  1019  3631 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:33.818  1019  3631 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-15 19:11:33.818  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.818  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{16ac2b82 token=android.os.BinderProxy@2d8c680 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-15 19:11:33.818  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.818  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.828  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.828  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.828  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.828  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-15 19:11:33.828  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.828  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.828  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.838  4453  4453 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:33.838  4453  4453 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:33.838  3849  3918 I GFX raster: took 0.738386ms for 80*80 texture 0
03-15 19:11:33.838  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776a178 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7ade220 counterpartCT=4 counterpartW=80 counterparth=80
03-15 19:11:33.838  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.838  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.838  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.848  1019  1524 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:33.848  1019  1524 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:33.848  1019  1524 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 19:11:33.848  3849  3918 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
03-15 19:11:33.848  1509  1509 D Launcher.HomeView: onStop
03-15 19:11:33.848  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{16ac2b82 token=android.os.BinderProxy@2d8c680 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 19:11:33.858  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 19:11:33.858  1019  1524 D PersonaManager: isKioskContainerExistOnDevice
03-15 19:11:33.878  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.878  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.878  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.908  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:33.908  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:33.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:33.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:33.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:33.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:33.908  1019  1507 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-15 19:11:33.908  1019  1507 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-15 19:11:33.908  1019  1507 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-15 19:11:33.918  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.918  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.918  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:33.918  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-15 19:11:33.918  1019  1019 D SensorService: [SO] activate (ident=0xb7ae03e0, enabled=0)
03-15 19:11:33.918  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-15 19:11:33.918  1019  1019 D SensorManager: unregisterListener ::   
03-15 19:11:33.928  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-15 19:11:33.928  1019  1019 D SensorService: [SO] changed settle time [1]
03-15 19:11:33.928  1019  1019 D SensorService: [SO] setDelay [66000000]
03-15 19:11:33.928  1019  1019 D SensorService: [SO] activate (ident=0xb7ae03e0, enabled=1)
03-15 19:11:33.928  1019  1019 D SensorService: [SO] AR_init
03-15 19:11:33.928  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-15 19:11:33.928  1509  1509 D Launcher: onTrimMemory. Level: 20
03-15 19:11:33.938  4316  4316 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-15 19:11:33.948  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-15 19:11:33.948  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-15 19:11:33.948  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-15 19:11:33.948  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
03-15 19:11:33.958  1445  1445 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-15 19:11:33.958  1445  1445 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-15 19:11:33.968  2611  2611 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-15 19:11:33.968  2611  2728 D HeadsetStateMachine: Disconnected process message: 10
,03-15 19:11:33.968  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:33.968  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.968  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:33.968  1019  1019 I MotionRecognitionService: Plugged
,03-15 19:11:33.968  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,03-15 19:11:33.978  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.978  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.978  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:33.978  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-15 19:11:33.978  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 19:11:33.978  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 19:11:33.978  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-15 19:11:33.978  1179  1179 D SViewCoverView: level :100 plugged : 2
,03-15 19:11:33.988  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.988  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.988  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:33.988  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.988  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.988  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:33.998  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.998  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.998  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:33.998  3849  3918 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-15 19:11:33.998  3849  3918 I GFX raster: took 0.675729ms for 80*80 texture 0
,03-15 19:11:33.998  3849  3918 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb776a178 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7769f58 counterpartCT=4 counterpartW=80 counterparth=80,
,03-15 19:11:33.998  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.998  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:33.998  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.008  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.008  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.008  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.008  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.008  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.008  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.018  1019  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 19:11:34.018  3849  3918 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 19:11:34.028  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.028  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.028  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.028  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.028  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.028  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.028  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.028  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.028  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-15 19:11:34.038  3849  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-15 19:11:34.038  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-15 19:11:34.048  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.048  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.048  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.048  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.048  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.048  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.058  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.058  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.058  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.058  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.058  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.058  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.068  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.068  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.068  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:34.078  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.078  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.078  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 19:11:34.088  1019  1042 D SensorService: [SO] -0.460 0.192 9.883
,03-15 19:11:34.088  1019  1042 D SensorService: [SO] [100 -> 255]
,03-15 19:11:34.088  1727  1727 I Hs20UtilService: Starting #6
,03-15 19:11:34.088  1727  1784 I Hs20UtilService: Message received 5007
,03-15 19:11:34.098  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 19:11:34.098  1325  1325 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 19:11:34.098  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 19:11:34.108  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-15 19:11:34.108  1325  1325 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-15 19:11:34.108  1325  1325 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:34.128  1019  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.128  1019  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.128  1019  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 19:11:34.128  1727  1727 I Hs20UtilService: Starting #7
03-15 19:11:34.128  4453  4453 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-15 19:11:34.128  1727  1784 I Hs20UtilService: Message received 5007
,03-15 19:11:34.128  4162  4162 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:34.128  3849  3918 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:34.138  1325  1325 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
03-15 19:11:34.138  1325  1325 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:34.148  4453  4453 I LibraryLoader: Loading: webviewchromium
03-15 19:11:34.148  3849  3918 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-15 19:11:34.148  3849  3918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:34.148  3849  3918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:34.148  3849  3918 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:34.148  3849  3918 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 19:11:34.148  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.148  3849  3918 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:34.148  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:34.148  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.148  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-15 19:11:34.148  4453  4453 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5943-5948)
03-15 19:11:34.148  4453  4453 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:11:34.168  1019  1571 I ActivityManager: Killing 3681:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-15 19:11:34.178  1019  1140 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
03-15 19:11:34.188  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-15 19:11:34.188  1019  1570 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
03-15 19:11:34.188  1019  1570 D SecContentProvider2: mCursor = null
03-15 19:11:34.188  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
03-15 19:11:34.188  1019  1140 D SecContentProvider2: uri = 15 selection = getToastGravity
03-15 19:11:34.188  1019  1140 D SecContentProvider2: mCursor = null
03-15 19:11:34.188  4453  4453 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {250481c5}
03-15 19:11:34.198  1019  1032 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-15 19:11:34.198  1019  1032 D SecContentProvider2: mCursor = null
,03-15 19:11:34.198  1019  1345 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-15 19:11:34.198  1019  1345 D SecContentProvider2: mCursor = null
,03-15 19:11:34.198  1019  1507 D SecContentProvider2: uri = 15 selection = getToastEnabledState
03-15 19:11:34.198  1019  1507 D SecContentProvider2: mCursor = null
03-15 19:11:34.198  4453  4453 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:11:34.198  3849  3918 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:34.208  1019  1515 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
03-15 19:11:34.208  1019  1515 D SecContentProvider2: mCursor = null
,03-15 19:11:34.208  4453  4453 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 19:11:34.208  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.208  1019  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:34.208  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-15 19:11:34.218  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:34.248  1019  1262 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.248  1019  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.248  1019  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.268  1019  1262 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 19:11:34.268  1019  1262 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver,
,03-15 19:11:34.268  1019  1262 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-15 19:11:34.268  1019  1262 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 19:11:34.268  1483  4482 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
03-15 19:11:34.268  4453  4453 I BrowserStartupController: Initializing chromium process, renderers=0
,03-15 19:11:34.268  1019  1262 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.268  1019  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.268  1019  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.278  1483  4482 E File    : fail readDirectory() errno=2
,03-15 19:11:34.278  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3681/cgroup.procs: No such file or directory
,03-15 19:11:34.288   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=4, Uoast
,03-15 19:11:34.288  4453  4453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:34.298  3849  3918 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
03-15 19:11:34.298  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.298  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.298  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.308  1019  1340 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,03-15 19:11:34.308  1019  3633 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.308  1019  3633 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:34.308  1019  3633 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.308  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:34.318  1179  1179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 19:11:34.328   258   446 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
,03-15 19:11:34.328   258   439 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
,03-15 19:11:34.348  1019  1570 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.348  1019  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.348  1019  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.358  3849  3918 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:34.358  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-15 19:11:34.358  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-15 19:11:34.358  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.358  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:34.358  3849  3918 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:34.368  3849  3918 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:34.368  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:34.368  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.368  1019  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.368  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.368  4453  4453 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-15 19:11:34.368  4453  4453 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,03-15 19:11:34.368  4453  4453 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-15 19:11:34.378  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:34.388   289   289 E SMD     : DCD OFF
,03-15 19:11:34.388  1019  1570 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.388  1019  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.388  1019  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.388  1827  1827 D WearableService: callingUid 10011, callindPid: 1827
,03-15 19:11:34.398  3849  3918 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:34.408  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.408  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:34.408  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.418  1827  4492 E MDM     : [233] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:11:34.418  4453  4453 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 19:11:34.418  4453  4453 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 19:11:34.418  4453  4453 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 19:11:34.418  4453  4453 I Adreno-EGL: Local Branch: 
03-15 19:11:34.418  4453  4453 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 19:11:34.418  4453  4453 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 19:11:34.418  4453  4453 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 19:11:34.418  1019  3631 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.418  1019  3631 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.418  1019  3631 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.428  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:34.438  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.438  1019  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.438  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.438  2130  4502 D LocationInitializer: Restart initialization of location
,03-15 19:11:34.438  1019  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.438  1019  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.438  1019  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.448  1019  1570 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.448  1019  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.448  1019  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.448  3849  3918 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:34.458  1019  1515 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.458  1019  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.458  1019  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.478  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:34.488  1019  3631 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.488  1019  3631 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:34.488  1019  3631 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.488  3849  3918 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:34.498  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:34.508  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:34.548  1019  1051 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-15 19:11:34.568  1019  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.568  1019  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.568  1019  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:34.568  3849  3918 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:34.578  4453  4453 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-15 19:11:34.588  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:34.588  1019  1140 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.588  1019  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.588  1019  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-15 19:11:34.588  1483  1499 D TP/SmsProvider: query,matched:0, calling pid = 2130
,03-15 19:11:34.598  1483  1499 D TP/SmsProvider: match 0:Elapsed time : 1.711 ms
,03-15 19:11:34.598  4453  4499 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-15 19:11:34.598  3849  3918 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:34.618  1483  1493 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2130
,03-15 19:11:34.618  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:34.628  1483  1730 D TP/SmsProvider: query,matched:0, calling pid = 2130
,03-15 19:11:34.638  1483  1730 D TP/SmsProvider: match 0:Elapsed time : 1.709 ms
,03-15 19:11:34.648  1483  1499 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2130
,03-15 19:11:34.718  3849  3918 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:34.718  4453  4453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:34.728  4453  4453 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 19:11:34.738  4453  4453 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-15 19:11:34.738  4453  4453 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-15 19:11:34.738  4453  4453 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-15 19:11:34.748  4453  4453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:34.748  4453  4453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:34.808  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-15 19:11:34.808  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.808  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:34.808  3849  3918 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:34.808  3849  3918 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:34.808  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:34.818  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:34.858  3849  3918 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:34.858  4453  4524 D OpenGLRenderer: Render dirty regions requested: true
,03-15 19:11:34.858  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.858  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:34.868  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.868  1019  1032 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 19:11:34.868  1019  1032 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 19:11:34.868  1019  1032 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 19:11:34.868  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 19:11:34.868  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:34.868  4453  4453 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 19:11:34.868  4453  4453 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 19:11:34.878  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:34.888   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-15 19:11:34.908  1019  3631 D InputDispatcher: Focus entered window: 4453
,03-15 19:11:34.908  4453  4453 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 19:11:34.908  4453  4524 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 19:11:34.908  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:34.908  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:34.928  4453  4524 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-15 19:11:34.928  4453  4524 D OpenGLRenderer: Enabling debug mode 0
,03-15 19:11:34.948  1827  1827 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:11:34.948  2130  4512 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-15 19:11:34.958  3849  3918 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:34.958  1019  1524 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 19:11:34.968  1827  1827 D a       : Opening database auth.proximity.permit_store...
,03-15 19:11:34.968  1019  4532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:34.968  1019  3387 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.978  1019  3387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:34.978  1019  3387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.978  1179  1179 D PanelView: There is/are notification(s) 
,03-15 19:11:34.988  4453  4453 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38865758 time:46783
,03-15 19:11:34.988  1019  1262 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.998  1019  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:34.998  1019  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.008  1019  4535 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:35.008  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s254ms
,03-15 19:11:35.018  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:35.018  1019  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:35.018  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-15 19:11:35.018  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a69f10 u0 com.test.thalitest/.MainActivity t11} time:46816
03-15 19:11:35.018  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 19:11:35.078  1877  1877 I SamsungIME: getCurrentCandidateView
,03-15 19:11:35.078  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.078  1019  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:35.078  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.088  1019  3633 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:35.088  1019  3633 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:35.088  1019  3633 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.088  3849  3918 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:35.098  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity,
03-15 19:11:35.098  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:35.098  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant,
03-15 19:11:35.098  3849  3918 I AMMetaDataParserService: Resource data:2131099648
03-15 19:11:35.098  1019  1340 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.098  1019  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:35.098  1019  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.098  3849  3918 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:35.098  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:35.108  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:35.118  1827  1827 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:35.118  3849  3918 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:35.118  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.118  1019  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:35.118  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.128  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:35.128  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:35.128  1019  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:35.138  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.148  3849  3918 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:35.148  4134  4156 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 19:11:35.158  3398  3398 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-15 19:11:35.158  3398  3398 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-15 19:11:35.158  3398  3398 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-15 19:11:35.168  3398  3398 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:35.168  1827  2147 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:11:35.168  1019  1140 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
03-15 19:11:35.168  1019  1140 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-15 19:11:35.168  1827  4533 W FusedLocationProvider: location=null
,03-15 19:11:35.168  1019  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.168  1019  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.168  1019  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.168  1019  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.178  4134  4156 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 19:11:35.188  4134  4156 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy,
,03-15 19:11:35.188  4546  4546 E Zygote  : MountEmulatedStorage()
03-15 19:11:35.188  4546  4546 E Zygote  : v2
03-15 19:11:35.188  4546  4546 I libpersona: KNOX_SDCARD checking this for 10108
03-15 19:11:35.188  4546  4546 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:35.188  4134  4156 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts,
03-15 19:11:35.188  4546  4546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:35.188  4134  4156 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-15 19:11:35.188  4546  4546 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:35.198  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-15 19:11:35.198  4546  4546 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 19:11:35.198  1019  1140 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4546 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:35.208  4134  4156 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 19:11:35.208  4134  4156 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 19:11:35.208  4134  4156 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 19:11:35.218  1745  1745 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 19:11:35.228  3598  3598 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 15 19:11:35 GMT+01:00 2016
,03-15 19:11:35.228  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.228  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:35.228  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 19:11:35.238  3598  3598 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-15 19:11:35.248  4546  4546 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:35.248  4546  4546 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:35.248  3598  3598 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-15 19:11:35.258  3598  3598 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 19:11:35.258  3598  3598 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-15 19:11:35.258  1877  1877 D SamsungIME: Dismiss ExpandCandiate
03-15 19:11:35.258  1807  1816 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 20
,03-15 19:11:35.268  3598  4561 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-15 19:11:35.278  4134  4134 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:35.278  1745  1745 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
03-15 19:11:35.278  1745  1745 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-15 19:11:35.278  3598  4561 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-15 19:11:35.288   258  1779 I SurfaceFlinger: id=10 Removed uhalitest (7/9)
,03-15 19:11:35.288  1745  1745 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-15 19:11:35.288  1745  1745 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
03-15 19:11:35.288  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:35.308  1745  1745 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 19:11:35.308  4134  4564 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 19:11:35.308  1745  1745 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 19:11:35.318  4134  4564 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-15 19:11:35.318  4134  4564 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-15 19:11:35.328  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11,
,03-15 19:11:35.328  3849  3918 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:35.328  4194  4194 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false,
03-15 19:11:35.328  3598  4561 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-15 19:11:35.338  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.338  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.338  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.338  1019  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.338  3598  4561 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,03-15 19:11:35.338  1877  1877 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 19:11:35.338  3598  4561 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,03-15 19:11:35.348  4134  4564 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 19:11:35.348  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,03-15 19:11:35.348  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:35.348  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
,03-15 19:11:35.348  3849  3918 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:35.358  4567  4567 E Zygote  : MountEmulatedStorage()
,03-15 19:11:35.358  4567  4567 E Zygote  : v2
03-15 19:11:35.358  4567  4567 I libpersona: KNOX_SDCARD checking this for 10077
03-15 19:11:35.358  4567  4567 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:35.358  1019  1340 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4567 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:35.358  4567  4567 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:35.358  4567  4567 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 19:11:35.358  4567  4567 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-15 19:11:35.368  1019  1570 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:35.368  4253  4253 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-15 19:11:35.368  4253  4253 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,03-15 19:11:35.368  4253  4253 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-15 19:11:35.378  1019  1345 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:35.378  3598  4561 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,03-15 19:11:35.378  4253  4253 I SA      : [SLFUCHKMGR] constructor called
,03-15 19:11:35.388  3598  4561 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,03-15 19:11:35.388  3849  3918 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:35.388  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:35.388  3598  3598 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
03-15 19:11:35.388  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:35.398  4567  4567 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:35.398  4567  4567 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:35.408  4360  4360 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:35.408  4360  4360 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:35.408  4360  4360 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 19:11:35.408  4360  4360 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-15 19:11:35.408  4453  4453 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 19:11:35.418  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 19:11:35.428  4134  4564 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-15 19:11:35.428  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-15 19:11:35.438  3849  3918 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:35.438  4134  4564 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
03-15 19:11:35.438  4253  4253 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-15 19:11:35.438  4253  4253 I SA      : [OR] == isSIMCardReady false ==
,03-15 19:11:35.438  4253  4253 I SA      : [SCU] == networkStateCheck == true
,03-15 19:11:35.448  4253  4253 I SA      : [DM] getCountryCodeFromCSC : PL
03-15 19:11:35.448  4253  4253 I SA      : isChinaCountryCode : false
03-15 19:11:35.448  4253  4253 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-15 19:11:35.448  4253  4253 I SA      : [OR] == networkStateCheck true ==
,03-15 19:11:35.458  4253  4253 I SA      : [OR] GetMyCountryZoneTask
,03-15 19:11:35.458  4253  4253 I SA      : [OR] onReceive END
03-15 19:11:35.458  4134  4564 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 19:11:35.458  3849  3918 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:35.458  4134  4564 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-15 19:11:35.468  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:35.478  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:35.478  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:35.478  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 19:11:35.488  1019  3387 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-15 19:11:35.498  1019  3387 D SecContentProvider2: mCursor = null
,03-15 19:11:35.528  4253  4585 I SA      : [SRS] prepareGetMyCountryZone,
,03-15 19:11:35.528  4253  4585 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 19:11:35.528  4253  4585 I SA      : [SSP] query invoked
,03-15 19:11:35.638  1019  1524 I art     : Explicit concurrent mark sweep GC freed 29478(1676KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.654ms total 142.039ms
,03-15 19:11:35.638  4253  4585 I SA      : [TPMU] GetMccFromDB : null
,03-15 19:11:35.638  4253  4585 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-15 19:11:35.648  4253  4585 I SA      : [TPM] isNoProxy(default) : true
,03-15 19:11:35.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.758  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.778  4590  4590 E Zygote  : MountEmulatedStorage(),
03-15 19:11:35.778  4590  4590 E Zygote  : v2
03-15 19:11:35.778  4590  4590 I libpersona: KNOX_SDCARD checking this for 10110
,03-15 19:11:35.778  4590  4590 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:35.778  1019  3633 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4590 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:35.778  4590  4590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:35.778  1019  3633 I ActivityManager: Killing 3705:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-15 19:11:35.778  4590  4590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:35.778  4590  4590 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 19:11:35.798  4590  4590 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:35.798  4590  4590 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:35.808  4253  4585 E File    : fail readDirectory() errno=2
,03-15 19:11:35.828  2130  4607 I iu.SyncManager: SYNC; picasa accounts
,03-15 19:11:35.848  4546  4546 I MusicStore: Database version: 104
,03-15 19:11:35.888  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3705/cgroup.procs: No such file or directory
,03-15 19:11:36.048  1877  1877 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 19:11:36.048  2130  2130 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-15 19:11:36.048  2130  2130 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-15 19:11:36.058  1019  3387 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.058  1019  3387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:36.058  1019  3387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:36.068  1877  1877 I SamsungIME: KeybaordView init() : load resources
,03-15 19:11:36.088  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.088  1019  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:36.088  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.098  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.098  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.098  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.098  1019  3633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.098  2130  4607 I iu.UploadsManager: num queued entries: 0
,03-15 19:11:36.098  2130  4607 I iu.UploadsManager: num updated entries: 0
,03-15 19:11:36.108  2130  4607 I iu.SyncManager: NEXT; no task
,03-15 19:11:36.108  4614  4614 E Zygote  : MountEmulatedStorage()
,03-15 19:11:36.108  4614  4614 E Zygote  : v2
03-15 19:11:36.108  4614  4614 I libpersona: KNOX_SDCARD checking this for 10009
03-15 19:11:36.108  4614  4614 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:36.108  4614  4614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:36.108  1019  3633 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4614 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,03-15 19:11:36.118  4614  4614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:36.118  4614  4614 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 19:11:36.138  4614  4614 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:36.138  4614  4614 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:36.198  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-15 19:11:36.198  1877  1877 I SamsungIME: getCurrentKeyboard
03-15 19:11:36.198  1877  1877 I SamsungIME: getTextKeyboard
,03-15 19:11:36.328   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 19:11:36.328   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:36.328  4590  4631 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 19:11:36.328   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 19:11:36.328   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:36.328  4590  4631 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 19:11:36.338  4614  4614 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-15 19:11:36.348   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 19:11:36.348   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:36.348  4590  4635 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 19:11:36.348  1877  1877 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-15 19:11:36.368   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 19:11:36.368   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:36.368  4590  4635 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 19:11:36.378  4546  4546 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:11:36.378  4546  4546 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:11:36.408  4546  4546 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:11:36.428  4614  4614 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-15 19:11:36.428  1019  1262 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-15 19:11:36.458  4546  4546 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 19:11:36.468  4546  4546 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29496bc9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 19:11:36.468  4546  4546 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-15 19:11:36.468  4546  4546 D AndroidMusic: GMSCore installation verified
,03-15 19:11:36.468  3849  3918 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:36.478  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:36.478  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:36.478  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:36.478  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:36.488  4546  4546 I ConfigStore: Config Database version: 1
,03-15 19:11:36.498  4453  4542 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-15 19:11:36.498  4453  4542 I chromium: 
,03-15 19:11:36.508  3849  3918 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-15 19:11:36.528  3849  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationM,apActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-15 19:11:36.528  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-15 19:11:36.578  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-15 19:11:36.578  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:36.578  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:36.578  3849  3918 I AMMetaDataParserService: Resource data:2131165197
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:36.578  3849  3918 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 19:11:36.578  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:36.598  1019  2786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:36.658  3849  3918 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 19:11:36.658  4453  4648 D jxcore_app_log: JniHelper::setJavaVM(0xb73b2448), pthread_self() = -1214146104
,03-15 19:11:36.668  4453  4648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 19:11:36.668  4453  4648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 19:11:36.668  4453  4648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 19:11:36.668  4453  4648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 19:11:36.668  4453  4648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-15 19:11:36.668  4453  4648 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5be607 added. We now have 1 listener(s)
,03-15 19:11:36.668  4453  4648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-15 19:11:36.678  4453  4648 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-15 19:11:36.678  4453  4648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-15 19:11:36.678  4453  4648 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 19:11:36.678  3849  3918 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 19:11:36.678  4453  4648 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1755eed2 added. We now have 1 listener(s)
03-15 19:11:36.678  4453  4648 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 19:11:36.718  4453  4648 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-15 19:11:36.718  4453  4648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-15 19:11:36.718  4453  4648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-15 19:11:36.718  4453  4648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 19:11:36.718  4453  4648 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-15 19:11:36.718  1019  1515 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.718  1019  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:36.718  1019  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.728  4453  4648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 19:11:36.728   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 19:11:36.728   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
03-15 19:11:36.728  4546  4546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
03-15 19:11:36.728  4453  4648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
03-15 19:11:36.738  1019  1140 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.738  1019  1140 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-15 19:11:36.738  1019  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 19:11:36.738  4453  4648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 19:11:36.738  4453  4648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 19:11:36.738  4453  4648 D io.jxcore.node.ConnectivityMonitor: start: OK
03-15 19:11:36.738  4453  4453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-15 19:11:36.748  4453  4453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-15 19:11:36.758  4614  4614 D hcjo    : AutoUpdateManager:IDLE:execute
,03-15 19:11:36.768  4614  4614 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-15 19:11:36.768  4614  4614 D InitializeManagerStateMachine: exit::IDLE
03-15 19:11:36.768  4614  4614 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-15 19:11:36.778  4614  4614 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-15 19:11:36.778  4614  4614 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-15 19:11:36.778  4614  4614 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-15 19:11:36.778  4614  4614 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-15 19:11:36.778  4614  4614 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-15 19:11:36.778  4614  4614 D InitializeManagerStateMachine: entry::SUCCESS
03-15 19:11:36.778  4614  4614 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-15 19:11:36.778   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 19:11:36.778   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:36.778  4546  4546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 19:11:36.778  4614  4614 D hcjo    : AutoUpdateTriggerManager:REQUEST2:requestInterval
,03-15 19:11:36.788   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 19:11:36.788   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
03-15 19:11:36.788  4453  4453 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-15 19:11:36.788  4546  4546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 19:11:36.788  4590  4590 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-15 19:11:36.798  4590  4590 I LibraryLoader: Loading: webviewchromium
,03-15 19:11:36.808  1019  1340 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:36.818  1019  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:36.818  1019  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
03-15 19:11:36.818  4590  4590 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 8597-8612)
03-15 19:11:36.818  4590  4590 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:11:36.848  4614  4614 I Volley  : RestApi Request Add : 2307
,03-15 19:11:36.868  4590  4590 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29e6420b}
,03-15 19:11:36.868  4590  4590 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:11:36.868  4590  4590 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 19:11:36.888  3849  3918 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 19:11:36.898  4614  4614 E File    : fail readDirectory() errno=2
,03-15 19:11:36.898  1019  1262 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 19:11:36.908  1019  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 19:11:36.908  1019  1031 I AudioService: getStreamVolume 3 index 0
,03-15 19:11:36.908  4546  4546 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-15 19:11:36.918  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: Resource data:2131165197
,03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 19:11:36.928  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:36.938  4546  4546 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 19:11:36.938  4590  4590 I BrowserStartupController: Initializing chromium process, renderers=0
,03-15 19:11:36.938  4590  4590 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:36.948  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.948  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.948  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.948  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.958  3849  3918 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 19:11:36.968  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4662 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:36.968  4662  4662 E Zygote  : MountEmulatedStorage(),
03-15 19:11:36.968  4662  4662 E Zygote  : v2
03-15 19:11:36.968  4662  4662 I libpersona: KNOX_SDCARD checking this for 10001
,03-15 19:11:36.968  4662  4662 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:36.978  4662  4662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:36.978  4662  4662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:36.978  4662  4662 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:36.978  1019  1524 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 19:11:36.998  4662  4662 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:36.998  4662  4662 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:37.008  4546  4546 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 19:11:37.008  3849  3918 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 19:11:37.018  4590  4590 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-15 19:11:37.028  4590  4682 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-15 19:11:37.038  4590  4590 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,03-15 19:11:37.038  4590  4590 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,03-15 19:11:37.088  3849  3918 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 19:11:37.108  4590  4590 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 19:11:37.108  4590  4590 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 19:11:37.108  4590  4590 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 19:11:37.108  4590  4590 I Adreno-EGL: Local Branch: 
03-15 19:11:37.108  4590  4590 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 19:11:37.108  4590  4590 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 19:11:37.108  4590  4590 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 19:11:37.128  1644  3848 I art     : Explicit concurrent mark sweep GC freed 3626(144KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 4MB/6MB, paused 3.660ms total 80.863ms
,03-15 19:11:37.138  1019  1316 E Watchdog: !@Sync 1
,03-15 19:11:37.158  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.158  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.158  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.158  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.168  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 19:11:37.178  4693  4693 E Zygote  : MountEmulatedStorage(),
03-15 19:11:37.178  4693  4693 E Zygote  : v2
03-15 19:11:37.178  4693  4693 I libpersona: KNOX_SDCARD checking this for 1000,
03-15 19:11:37.178  4693  4693 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:37.178  4693  4693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:37.188  1019  1031 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-15 19:11:37.188  1019  1139 D SettingsProvider: name = audio_safe_volume_state
03-15 19:11:37.188  1019  1031 I ActivityManager: Killing 3727:com.wssnps/1000 (adj 15): empty #31
,03-15 19:11:37.188  4693  4693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:37.188  4693  4693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:37.208   307   307 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 27.130ms
,03-15 19:11:37.208  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-15 19:11:37.228   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 19.436ms
,03-15 19:11:37.228  4693  4693 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:37.228  4693  4693 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:37.248   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 652us total 17.699ms
,03-15 19:11:37.258  4253  4265 W art     : Suspending all threads took: 14.043ms
,03-15 19:11:37.258  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
,03-15 19:11:37.258  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
,03-15 19:11:37.258  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.258  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.258  3849  3918 I AMMetaDataParserService: Resource data:2131165197
,03-15 19:11:37.268  3849  3918 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 19:11:37.268  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:37.288  4590  4590 I NSApplication: Starting up...
,03-15 19:11:37.288  3849  3918 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 19:11:37.318  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3727/cgroup.procs: No such file or directory
,03-15 19:11:37.318  1019  1524 I ActivityManager: Killing 3795:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,03-15 19:11:37.318  1019  1524 I ActivityManager: Killing 3754:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #32
,03-15 19:11:37.328  3849  3918 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 19:11:37.368  3849  3918 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 19:11:37.378  3849  3918 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 19:11:37.388   289   289 E SMD     : DCD OFF
,03-15 19:11:37.388  4024  4024 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:37.388  4024  4024 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-15 19:11:37.388  4024  4024 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-15 19:11:37.398  3849  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-15 19:11:37.398  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-15 19:11:37.408  3849  3918 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 19:11:37.408  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:37.408  3849  3918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:37.408  3849  3918 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 19:11:37.408  3849  3918 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-15 19:11:37.408  3849  3918 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 19:11:37.428  1019  1041 W libprocessgroup: failed to open /acct/uid_10065/pid_3795/cgroup.procs: No such file or directory
,03-15 19:11:37.428  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3754/cgroup.procs: No such file or directory
,03-15 19:11:37.438  3849  3918 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-15 19:11:37.448  4693  4693 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-15 19:11:37.468  3849  3918 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-15 19:11:37.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-15 19:11:37.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-15 19:11:37.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-15 19:11:37.498  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-15 19:11:37.498  3849  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-15 19:11:37.598  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-15 19:11:37.598  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.598  3849  3918 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.598  3849  3918 I AMMetaDataParserService: Resource data:2131165220
,03-15 19:11:37.608  3849  3918 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-15 19:11:37.608  3849  3918 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 19:11:37.608  3849  3918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:37.608  3849  3918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:37.608  3849  3918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:37.608  3849  3918 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 19:11:37.608  3849  3918 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-15 19:11:37.608  3849  3918 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:37.648  3849  3918 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-15 19:11:37.658  4693  4693 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-15 19:11:37.668  4693  4693 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-15 19:11:37.668  4693  4693 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:37.678  4693  4693 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-15 19:11:37.678  4693  4693 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-15 19:11:37.678  4693  4693 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-15 19:11:37.678  3849  3918 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-15 19:11:37.688  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-15 19:11:37.688  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-15 19:11:37.688  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-15 19:11:37.688  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
,03-15 19:11:37.688  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.688  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
,03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-15 19:11:37.698  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loo,p for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-15 19:11:37.718  3849  3918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity,
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundl,e  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.738  1019  1262 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 49536
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-15 19:11:37.708 , 3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-15 19:11:37.738  1019  1262 D PowerManagerService: [s] UserActivityState : 2 -> 1
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.738  1019  1262 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.738  1019  1262 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3436)
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-15 19:11:37.758  1019  1340 I ActivityManager: Killing 3829:com.samsung.helphub/1000 (adj 15): empty #31
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-15 19:11:37.708  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.a,ndroid.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
,03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-15 19:11:37.718  3849  3918 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
,03-15 19:11:37.858  4134  4150 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-15 19:11:37.858  4134  4150 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-15 19:11:37.858  4134  4150 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 19:11:37.858  4134  4143 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 19:11:37.868  4134  4143 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 19:11:37.868  4134  4143 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 19:11:37.888  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3829/cgroup.procs: No such file or directory
,03-15 19:11:37.908  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-15 19:11:37.908  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-15 19:11:37.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:37.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:37.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:37.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:37.998  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.998  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.998  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.998  1019  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.018  1019  3387 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4716 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:38.018  4716  4716 E Zygote  : MountEmulatedStorage(),
03-15 19:11:38.018  4716  4716 I libpersona: KNOX_SDCARD checking this for 10008
03-15 19:11:38.018  4716  4716 E Zygote  : v2
03-15 19:11:38.018  4716  4716 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.018  4716  4716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 19:11:38.028  4716  4716 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:38.028  4716  4716 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.028  1019  1097 V AlarmManager: waitForAlarm result :4
,03-15 19:11:38.058  4716  4716 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.058  4716  4716 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.148  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{1a1dc061 u0 com.samsung.android.providers.context/.ContextService}
,03-15 19:11:38.148  4453  4660 W jxcore-log: Initializing JXcore engine
03-15 19:11:38.148  4453  4660 W jxcore-log: JXcore engine is ready
,03-15 19:11:38.218  4253  4585 I SA      : [RC New] Execute method=[GET] start
03-15 19:11:38.218  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-15 19:11:38.228  1871  1871 E audit   : type=1400 msg=audit(1458065498.228:205): avc:  denied  { ioctl } for  pid=4660 comm="Thread-712" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-15 19:11:38.228  1871  1871 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:38.228  1871  1871 E audit   : type=1300 msg=audit(1458065498.228:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9371f8f8 items=0 ppid=307 ppcomm=main pid=4660 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-712" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-15 19:11:38.228  1871  1871 E audit   : type=1320 msg=audit(1458065498.228:205): 
,03-15 19:11:38.228  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{27d5fe36 u0 com.android.settings/.wifi.WifiCredService}
,03-15 19:11:38.238  2901  4338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-15 19:11:38.238  4614  4614 D InitializeManagerStateMachine: exit::SUCCESS
03-15 19:11:38.238  4614  4614 D InitializeManagerStateMachine: entry::IDLE
,03-15 19:11:38.248  3164  3164 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
03-15 19:11:38.248  3164  3164 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-15 19:11:38.248  3164  3164 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
03-15 19:11:38.248  4453  4660 W jxcore-log: Starting JXcore engine
,03-15 19:11:38.248  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-15 19:11:38.258  2901  2901 I Process : Sending signal. PID: 2901 SIG: 9
,03-15 19:11:38.278  1019  1059 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-15 19:11:38.288  4614  4735 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-15 19:11:38.288  4614  4735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 19:11:38.288  4614  4735 I System.out: (HTTPLog)-Static: isShipBuild true
03-15 19:11:38.288  4614  4735 I System.out: (HTTPLog)-Thread-718-846988468: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 19:11:38.288  4614  4735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 19:11:38.298   258  1104 I SurfaceFlinger: id=11 Removed Uoast (8/8)
,03-15 19:11:38.298   258   446 I SurfaceFlinger: id=11 Removed Uoast (-2/8)
,03-15 19:11:38.298  4253  4585 I SA      : [RC New] Security=[true]
,03-15 19:11:38.298  4253  4585 I System.out: Thread-650(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 19:11:38.298  4253  4585 I System.out: Thread-650(ApacheHTTPLog):isSBSettingEnabled false
03-15 19:11:38.298  4253  4585 I System.out: Thread-650(ApacheHTTPLog):isShipBuild true
03-15 19:11:38.298  4253  4585 I System.out: Thread-650(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 19:11:38.298  4253  4585 I System.out: Thread-650(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 19:11:38.298   279  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-15 19:11:38.298   279  1000 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,03-15 19:11:38.308   279  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-15 19:11:38.308   279  1000 D Netd    : getNetworkForDns: using netid 502 for uid 10009
,03-15 19:11:38.328  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,03-15 19:11:38.338  4003  4003 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-15 19:11:38.338  1019  1019 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-15 19:11:38.348  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:38.348  1019  1032 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-15 19:11:38.348  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-15 19:11:38.348  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-15 19:11:38.358  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.358  1019  1507 I ActivityManager: Process com.sec.android.app.sysscope (pid 2901)(adj 0) has died(25,587)
,03-15 19:11:38.368  4453  4660 W jxcore-log: Platform android
03-15 19:11:38.368  4453  4660 W jxcore-log: 
,03-15 19:11:38.368  4453  4660 W jxcore-log: Process ARCH arm
03-15 19:11:38.368  4453  4660 W jxcore-log: 
,03-15 19:11:38.378  1469  1469 D RegisteredServicesCache: empty dynamic service
,03-15 19:11:38.378  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.408  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.418  1019  3633 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-15 19:11:38.418  1019  3633 D SecContentProvider2: mCursor = null
,03-15 19:11:38.428  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.448  4716  4716 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 19:11:38.458  4614  4735 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 19:11:38.458  4716  4716 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
03-15 19:11:38.458  4614  4735 I qtaguid : Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 4614, getuid(): 10009
,03-15 19:11:38.458  1019  1140 I ActivityManager: Killing 3776:com.vlingo.midas/u0a28 (adj 15): empty #31
,03-15 19:11:38.458  4716  4716 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-15 19:11:38.458  4716  4716 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-15 19:11:38.468  1019  3631 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,03-15 19:11:38.468  1019  3631 I ActivityManager: Killing 3849:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-15 19:11:38.508  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-15 19:11:38.508  1019  1019 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 19:11:38.508  1019  1019 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 19:11:38.518  1019  1019 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
03-15 19:11:38.518  1019  1019 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-15 19:11:38.518  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.528  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.528  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.528  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.538  4744  4744 E Zygote  : MountEmulatedStorage()
,03-15 19:11:38.538  4744  4744 E Zygote  : v2
03-15 19:11:38.538  4744  4744 I libpersona: KNOX_SDCARD checking this for 10058
03-15 19:11:38.538  4744  4744 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.538  4744  4744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:38.538  1019  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4744 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-15 19:11:38.548  4744  4744 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:38.548  4744  4744 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.558  1019  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:38.558  1019  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:38.558  1019  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 19:11:38.568  4716  4716 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 19:11:38.568  1019  1019 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 19:11:38.568  1019  1019 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32781f40
,03-15 19:11:38.578  4744  4744 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.578  4744  4744 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.608  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 19:11:38.608  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 19:11:38.608  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-15 19:11:38.608  1019  3631 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:38.608  1019  3631 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:38.608  1019  3631 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 19:11:38.618  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 19:11:38.618  4360  4360 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:38.618  4360  4360 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:38.618  4360  4360 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 19:11:38.618  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 19:11:38.628  4716  4716 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-15 19:11:38.628  1807  1807 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-15 19:11:38.628  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.628  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.628  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.628  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.628  1807  1807 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 19:11:38.628  1807  1807 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-15 19:11:38.628  1807  1807 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-15 19:11:38.628  1807  1807 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-15 19:11:38.628  1807  1807 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-15 19:11:38.628  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 19:11:38.638  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-15 19:11:38.638  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
03-15 19:11:38.638  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 19:11:38.638  1807  1807 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-15 19:11:38.648  1019  3631 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4762 uid=10153 gids={50153, 9997} abi=armeabi-v7a,
,03-15 19:11:38.658  4762  4762 E Zygote  : MountEmulatedStorage(),
,03-15 19:11:38.658  4762  4762 E Zygote  : v2,
03-15 19:11:38.658  4762  4762 I libpersona: KNOX_SDCARD checking this for 10153
03-15 19:11:38.658  4762  4762 I libpersona: KNOX_SDCARD not a persona,
,03-15 19:11:38.658  4762  4762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 19:11:38.658  4762  4762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 19:11:38.668  4762  4762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.668  1807  1807 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 19:11:38.668  1019  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-15 19:11:38.678  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 19:11:38.678  1807  1807 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-15 19:11:38.678  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.678  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.688  3598  3598 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Mar 15 19:11:38 GMT+01:00 2016
,03-15 19:11:38.688  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:38.688  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:38.688  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 19:11:38.688  4762  4762 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.688  1019  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:38.688  1019  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:38.688  1019  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:38.688  4762  4762 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:38.688  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.708  1807  1807 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-15 19:11:38.708  1807  1807 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 19:11:38.708  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 19:11:38.718  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 19:11:38.718  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 19:11:38.718  1019  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 19:11:38.718  4744  4744 I ExternalOEMControlProvider: onCreate
,03-15 19:11:38.728  3598  3598 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-15 19:11:38.728  3598  3598 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-15 19:11:38.738  4762  4762 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:38.748  3598  3598 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 19:11:38.748  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:38.748  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:38.748  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:38.758  1745  1745 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-15 19:11:38.758  3598  3598 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 19:11:38.758  1745  1745 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 19:11:38.768  3598  4778 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-15 19:11:38.768  3598  4778 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,03-15 19:11:38.768  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.768  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.778  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.778  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.778  3598  4778 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Mar 15 19:11:38 GMT+01:00 2016,
,03-15 19:11:38.788  4780  4780 E Zygote  : MountEmulatedStorage(),
03-15 19:11:38.788  4780  4780 I libpersona: KNOX_SDCARD checking this for 10081
03-15 19:11:38.788  4780  4780 E Zygote  : v2
03-15 19:11:38.788  4780  4780 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.788  4780  4780 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-15 19:11:38.788  4780  4780 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:38.788  1019  3631 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4780 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:11:38.788  4780  4780 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.798  3598  4778 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,03-15 19:11:38.808  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.808  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.808  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.808  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.808  1827  1827 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-15 19:11:38.818  4796  4796 E Zygote  : MountEmulatedStorage()
03-15 19:11:38.818  4796  4796 E Zygote  : v2
03-15 19:11:38.818  4796  4796 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:38.818  4796  4796 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.818  4796  4796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:38.818  4253  4253 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
03-15 19:11:38.818  1019  3631 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4796 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 19:11:38.818  4796  4796 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:38.828  4796  4796 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-15 19:11:38.828  4780  4780 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:38.828  4780  4780 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.828  4744  4779 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-15 19:11:38.848  3598  3598 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-15 19:11:38.868  4796  4796 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.868  4796  4796 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.888  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.888  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.888  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.888  4614  4735 I qtaguid : Untagging socket 26
,03-15 19:11:38.888  4780  4780 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 19:11:38.888  4780  4780 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:38.888  4780  4780 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:38.888  4780  4780 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:38.888  4780  4780 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-15 19:11:38.888  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.908  4811  4811 E Zygote  : MountEmulatedStorage()
,03-15 19:11:38.908  4811  4811 E Zygote  : v2
03-15 19:11:38.908  4811  4811 I libpersona: KNOX_SDCARD checking this for 10041
03-15 19:11:38.908  4811  4811 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.908  4811  4811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:38.908  1019  1032 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4811 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-15 19:11:38.908  4811  4811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:38.908  4811  4811 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.908  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:38.908  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:38.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:38.908  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:38.918  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:38.918  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:38.918  1019  3633 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:38.918  1019  3633 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:38.918  1019  3633 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:38.928  4453  4660 I jxcore-log: JXcore Cordova bridge is ready!
03-15 19:11:38.928  4453  4660 I jxcore-log: 
,03-15 19:11:38.928  4453  4660 W jxcore-log: JXcore engine is started
,03-15 19:11:38.938  4453  4648 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-15 19:11:38.958  1019  3631 I ActivityManager: Killing 3931:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-15 19:11:38.968  4453  4660 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 19:11:38.968  4453  4660 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 19:11:38.968  4811  4811 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.968  4811  4811 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.978  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3849/cgroup.procs: No such file or directory
03-15 19:11:38.978  1019  1041 W libprocessgroup: failed to open /acct/uid_10028/pid_3776/cgroup.procs: No such file or directory
,03-15 19:11:38.978  4453  4453 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-15 19:11:38.998  4811  4811 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-15 19:11:38.998  4811  4811 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:11:38.998  4811  4811 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:38.998  4811  4811 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:38.998  4811  4811 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 19:11:39.128  1019  1345 D FocusedStackFrame: Set to : 0
,03-15 19:11:39.128  4796  4796 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458065499140,
03-15 19:11:39.128  4796  4796 D         : TimeServiceNative: User Time to be set is 1458065499140
03-15 19:11:39.128  4796  4796 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-15 19:11:39.128  4796  4796 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-15 19:11:39.128  4796  4796 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458065499140
03-15 19:11:39.128  1019  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-15 19:11:39.128  1019  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 19:11:39.128  1019  1345 D InputDispatcher: Focused application set to: xxxx
,03-15 19:11:39.128  1019  1345 D InputDispatcher: Focus left window: 4453
,03-15 19:11:39.128   318   435 D QC-time-services: Daemon: Connection accepted:time_genoff
03-15 19:11:39.128  4796  4796 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458065499140
03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458065499140, operation = 0
,03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/10/70 21:48:18
,03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:Value read from RTC seconds = 21851298000
03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:new time 1458065499140 
,03-15 19:11:39.128   318  4829 D QC-time-services: Daemon: delta 1436214201140 genoff 1436214201140 
03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201140 to memory
03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-15 19:11:39.128   318  4829 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-15 19:11:39.138  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:39.138  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:39.148  4614  4614 D hcjo    : AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,03-15 19:11:39.158   318  4829 D QC-time-services: Updating the TOD offset
03-15 19:11:39.158   318  4829 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201140 to memory
03-15 19:11:39.158   318  4829 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-15 19:11:39.158   318  4829 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-15 19:11:39.158   318  4829 E QC-time-services: Daemon:Update to modem bit set,
03-15 19:11:39.158   318  4829 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-15 19:11:39.158   318  4829 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249401140
03-15 19:11:39.158  4796  4796 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-15 19:11:39.158   318   432 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
03-15 19:11:39.158   318   435 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-15 19:11:39.228  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,03-15 19:11:39.228  3164  3233 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-15 19:11:39.278  1019  3387 I art     : Explicit concurrent mark sweep GC freed 35595(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 3.158ms total 277.454ms
,03-15 19:11:39.278   258  1104 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (218 us)
,03-15 19:11:39.328  4453  4648 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 343ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 19:11:39.328  1019  1031 I ActivityManager: Killing 3896:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-15 19:11:39.338  1019  3387 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.338  3164  3233 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
03-15 19:11:39.338  1019  3387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:39.338  1019  3387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.338  3164  3233 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-15 19:11:39.338  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.338  1019  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:39.338  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-15 19:11:39.338  4614  4614 D hcjo    : AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,03-15 19:11:39.338  4614  4614 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
03-15 19:11:39.338  4614  4614 D hcjo    : SelfUpdateManager:IDLE:execute
,03-15 19:11:39.348  1019  1524 I ActivityManager: Killing 3966:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-15 19:11:39.358  1019  1570 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:39.358  1019  1570 W ActivityManager: mDVFSHelper.acquire()
,03-15 19:11:39.368  1019  1570 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 19:11:39.368  1019  1570 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 19:11:39.368  1019  1570 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 19:11:39.378  4433  4472 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 19:11:39.388  1509  1509 D Launcher: onRestart, Launcher: 951088449
,03-15 19:11:39.388  4811  4811 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-15 19:11:39.398  4614  4614 D hcjo    : SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,03-15 19:11:39.398  1509  1509 D Launcher: onStart, Launcher: 951088449
03-15 19:11:39.398  1019  1041 D LocationProviderProxy: applying state to connected service
03-15 19:11:39.398  1509  1509 D Launcher.HomeView: onStart
,03-15 19:11:39.398  1509  1509 D Launcher: onResume, Launcher: 951088449
,03-15 19:11:39.408  1019  1041 D LocationProviderProxy: applying state to connected service
,03-15 19:11:39.408  3164  3233 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-15 19:11:39.408  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-15 19:11:39.408  1019  1019 D SensorService: [SO] activate (ident=0xb7ae03e0, enabled=0)
03-15 19:11:39.408  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 19:11:39.408  1019  3631 D SettingsProvider: name = kids_home_mode
03-15 19:11:39.408  1019  3631 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 19:11:39.408  1019  3631 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 19:11:39.408  1019  3631 D SettingsProvider: selectionArgs: false
03-15 19:11:39.408  1019  3631 D SettingsProvider: selectionArgs: 10006
03-15 19:11:39.408  1019  3631 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 19:11:39.408  1019  3631 D SettingsProvider: ret = -1
,03-15 19:11:39.408  1509  1509 D Launcher.HomeView: onResume
,03-15 19:11:39.418  1019  1019 D SensorManager: unregisterListener ::   
,03-15 19:11:39.418  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-15 19:11:39.418  1019  1019 D SensorService: [SO] changed settle time [0]
03-15 19:11:39.418  1019  1019 D SensorService: [SO] setDelay [200000000]
03-15 19:11:39.418  1019  1019 D SensorService: [SO] activate (ident=0xb740fde8, enabled=1)
03-15 19:11:39.418  1019  1019 D SensorService: [SO] AR_init
03-15 19:11:39.418  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 19:11:39.418  3164  3233 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 19:11:39.418  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 19:11:39.418  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3931/cgroup.procs: No such file or directory
,03-15 19:11:39.428  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3896/cgroup.procs: No such file or directory
,03-15 19:11:39.428  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-15 19:11:39.428  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3966/cgroup.procs: No such file or directory
,03-15 19:11:39.428  4614  4614 I Volley  : RestApi Request Add : 2346
,03-15 19:11:39.428  3164  3233 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-15 19:11:39.428  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220],
03-15 19:11:39.428  4614  4733 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 19:11:39.428  1509  1509 D MenuAppsGridFragment: onResume
,03-15 19:11:39.438  1019  1031 D SettingsProvider: name = next_alarm_formatted
03-15 19:11:39.438  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 19:11:39.438  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 19:11:39.438  1019  1031 D SettingsProvider: selectionArgs: false
03-15 19:11:39.438  1019  1031 D SettingsProvider: selectionArgs: 10081
03-15 19:11:39.438  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 19:11:39.438  1019  1031 D SettingsProvider: ret = -1
,03-15 19:11:39.438  1509  1509 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-15 19:11:39.438  1509  1509 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-15 19:11:39.438  3164  3233 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-15 19:11:39.438  3164  3233 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-15 19:11:39.438  4614  4733 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 19:11:39.438  4614  4733 I qtaguid : Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 4614, getuid(): 10009
,03-15 19:11:39.448  1019  1262 D ActivityManager: handle home activity for 0
03-15 19:11:39.448  1019  1262 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-15 19:11:39.448  1019  1262 D KnoxTimeoutHandler: post home show event for user 0
03-15 19:11:39.448  1019  1262 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 19:11:39.448  1019  1262 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 19:11:39.448  1019  1262 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 19:11:39.448  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-15 19:11:39.448  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-15 19:11:39.448  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 19:11:39.448  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:39.448  3164  3234 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-15 19:11:39.458  4253  4585 I SA      : [RC New] [v2liruge] api execute + 1159
,03-15 19:11:39.458  4253  4585 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
03-15 19:11:39.458  4253  4585 I System.out: AsyncTask #1 calls detatch()
,03-15 19:11:39.458  3164  3233 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-15 19:11:39.458   258   258 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,03-15 19:11:39.458  3164  3234 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-15 19:11:39.458  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:39.468  3164  3233 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-15 19:11:39.468  4253  4585 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-15 19:11:39.468  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:39.468  1019  1571 D InputDispatcher: Focus entered window: 1509
,03-15 19:11:39.468  1509  1509 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-15 19:11:39.468  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:39.468  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:39.478  4253  4585 I SA      : [OCP] update openData : PL
,03-15 19:11:39.488  3164  3233 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-15 19:11:39.498  4253  4585 I SA      : [TPMU] getNetworkMcc : 
,03-15 19:11:39.498  4253  4585 I SA      : [SCU] saveMccToPreferece Start
03-15 19:11:39.498  4253  4585 I SA      : [SCU] RegionMCC : 260
03-15 19:11:39.498  4253  4585 I SA      : [SSP] query invoked
03-15 19:11:39.498  3164  3234 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,03-15 19:11:39.498  3164  3234 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-15 19:11:39.498  4253  4585 I SA      : [TPMU] GetMccFromDB : null
,03-15 19:11:39.498  4253  4585 I SA      : [SCU] getMccFromPreferece mcc = 260
03-15 19:11:39.498  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 19:11:39.498  4253  4585 I SA      : [SCU] saveMccToPreferece End
,03-15 19:11:39.498  1019  3387 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 19:11:39.508  4253  4585 I SA      : [RC New] executeRequest [v2liruge] end. 1285
,03-15 19:11:39.508  4253  4585 I SA      : [RC New] Execute end
,03-15 19:11:39.508  4253  4253 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-15 19:11:39.508  4253  4253 I SA      : [OR] GetMyCountryZoneTask Success
,03-15 19:11:39.508  3164  3234 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-15 19:11:39.508  1179  1179 D PanelView: There is/are notification(s) 
,03-15 19:11:39.508  4453  4453 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-15 19:11:39.518  1019  4834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:39.528  1877  1877 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 19:11:39.538  1019  1340 I ActivityManager: Killing 3981:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-15 19:11:39.538  1509  1509 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d8c680 time:51333
,03-15 19:11:39.538  3164  3234 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-15 19:11:39.538  1019  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:39.548  1019  1049 I ActivityManager: Displayed Component not be shown by security: +191ms
,03-15 19:11:39.568  3164  3234 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-15 19:11:39.568  3164  3234 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,03-15 19:11:39.568  3164  3164 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-15 19:11:39.578  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 19:11:39.578  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-15 19:11:39.588  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-15 19:11:39.598  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-15 19:11:39.598  3164  3234 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
03-15 19:11:39.598  3164  3164 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-15 19:11:39.598  3164  3164 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2439f8fc
,03-15 19:11:39.598  4811  4811 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 132.592ms
,03-15 19:11:39.608  3164  3234 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 19:11:39.608  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-15 19:11:39.618  3164  3164 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,03-15 19:11:39.618  3164  3164 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-15 19:11:39.618  3164  3164 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:51413
,03-15 19:11:39.618  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3981/cgroup.procs: No such file or directory
,03-15 19:11:39.618  1019  1524 E PersonaManagerService: inState():  stateMachine is null !!
,03-15 19:11:39.618  1019  1524 I PersonaManagerService: PersonaId don't exist
,03-15 19:11:39.618  1019  1524 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 19:11:39.618  4780  4780 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 157.256ms
,03-15 19:11:39.628  1019  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 19:11:39.628  1019  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:39.628  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.628  1019  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:39.628  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 19:11:39.628  1019  1524 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:39.638  1019  1524 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:39.638  1019  1524 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:39.638  1019  1524 W ActivityManager: mDVFSHelper.acquire()
,03-15 19:11:39.638  1019  1524 D FocusedStackFrame: Set to : 0
,03-15 19:11:39.648  1509  1509 D Launcher.HomeView: onPause
,03-15 19:11:39.648  1019  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 19:11:39.648  1019  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:39.648  1019  1524 D InputDispatcher: Focused application set to: xxxx
03-15 19:11:39.648  1019  1524 D InputDispatcher: Focus left window: 1509
,03-15 19:11:39.648  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 19:11:39.648  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 19:11:39.648  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:39.678  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-15 19:11:39.678  1019  1019 D SensorService: [SO] activate (ident=0xb740fde8, enabled=0)
03-15 19:11:39.678  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 19:11:39.678  1019  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.678  1019  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.678  1019  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.678  1019  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.688  1019  1019 D SensorManager: unregisterListener ::   ,
03-15 19:11:39.688  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-15 19:11:39.688  1019  1019 D SensorService: [SO] changed settle time [1]
,03-15 19:11:39.688  4811  4811 D Mms/TelephonyPermission: start operation mode monitor
,03-15 19:11:39.688  1019  1019 D SensorService: [SO] setDelay [66000000]
03-15 19:11:39.688  1019  1019 D SensorService: [SO] activate (ident=0xb740fde8, enabled=1)
03-15 19:11:39.688  1019  1019 D SensorService: [SO] AR_init
03-15 19:11:39.688  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1,
,03-15 19:11:39.698  4838  4838 E Zygote  : MountEmulatedStorage()
03-15 19:11:39.698  4838  4838 E Zygote  : v2
03-15 19:11:39.698  4838  4838 I libpersona: KNOX_SDCARD checking this for 10090
03-15 19:11:39.698  4838  4838 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:39.698  4838  4838 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-15 19:11:39.698  4811  4837 D Mms/ArtClassLoader: init before art
03-15 19:11:39.698  1019  1515 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4838 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-15 19:11:39.698  1019  1515 I ActivityManager: Killing 4039:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
03-15 19:11:39.698  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-15 19:11:39.708  4838  4838 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:39.708  4838  4838 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.728  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,03-15 19:11:39.728  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-15 19:11:39.728  4811  4811 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 19:11:39.728  4838  4838 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:39.728  4838  4838 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.738  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:39.748  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 19:11:39.748  4811  4811 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,03-15 19:11:39.748  4811  4811 D Mms/TelephonyPermission: isDefault true
,03-15 19:11:39.748  4811  4811 D Mms/MmsApp: onCreate() com.android.mms
,03-15 19:11:39.748  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:39.758  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:39.758  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:39.758  3164  3164 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:51558
,03-15 19:11:39.758  1019  1032 E PersonaManagerService: inState():  stateMachine is null !!
,03-15 19:11:39.768  1019  1032 I PersonaManagerService: PersonaId don't exist
,03-15 19:11:39.768  1019  1032 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-15 19:11:39.768  1019  1042 D SensorService: [SO] currT = 51561081000, prevT = 51201096000, diff = 359985000, [-0.460 0.192 9.902]
,03-15 19:11:39.768  1019  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 19:11:39.768  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.768  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.768  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 19:11:39.768  1019  1032 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:39.768  1019  1032 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 19:11:39.768  1019  1032 W ActivityManager: mDVFSHelper.acquire()
,03-15 19:11:39.778  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-15 19:11:39.778  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:39.778  1019  1032 D InputDispatcher: Focused application set to: xxxx
,03-15 19:11:39.788  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,03-15 19:11:39.788  1019  1031 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-15 19:11:39.788  1019  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 19:11:39.788  1019  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 19:11:39.788  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 19:11:39.788  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
03-15 19:11:39.788  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:39.788  1019  1019 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,03-15 19:11:39.798  1019  3631 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:39.798  1019  3631 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:39.798  1019  3631 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-15 19:11:39.798  4811  4811 D Mms/MmsApp: [start]    initCountryIso consume time = 411.450573
,03-15 19:11:39.798  1019  1032 D CountryDetector: The first listener is added
,03-15 19:11:39.818  4811  4811 D Mms/MmsApp: [end]    initCountryIso consume time = 17.55625
03-15 19:11:39.818  4811  4811 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.114896
,03-15 19:11:39.818  4838  4838 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-15 19:11:39.818  4838  4838 D elm:15121: ELMEngine.ELMEngine( context ).
,03-15 19:11:39.828  4838  4838 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-15 19:11:39.828  1019  1041 W libprocessgroup: failed to open /acct/uid_10127/pid_4039/cgroup.procs: No such file or directory
,03-15 19:11:39.828  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.828  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.828  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-15 19:11:39.828  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 19:11:39.828  4838  4838 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-15 19:11:39.838  1019  1042 D SensorService: [SO] currT = 51631226000, prevT = 51201096000, diff = 430130000, [-0.479 0.192 9.902]
03-15 19:11:39.838  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.838  1019  1042 D SensorService: [SO] -0.479 0.192 9.902
03-15 19:11:39.838  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.838  1019  1042 D SensorService: [SO] [100 -> 255]
03-15 19:11:39.838  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.838  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.838  4838  4838 D elm:15121: ElmAgentService : onCreate()
,03-15 19:11:39.838  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:39.838  4811  4811 D Mms/MmsConfig: before partial update
,03-15 19:11:39.838  4838  4855 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-15 19:11:39.848  4857  4857 E Zygote  : MountEmulatedStorage(),
03-15 19:11:39.848  4857  4857 I libpersona: KNOX_SDCARD checking this for 10130
03-15 19:11:39.848  4857  4857 E Zygote  : v2
03-15 19:11:39.848  4857  4857 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:39.848  4857  4857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:39.848  4811  4811 D Mms/MmsConfig: Load Resize quality : 80
,03-15 19:11:39.858  4857  4857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-15 19:11:39.858  4857  4857 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.858  4838  4855 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).,
03-15 19:11:39.858  4838  4838 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-15 19:11:39.858  4838  4838 D elm:15121: ModuleBase.ModifySetAlarm()
03-15 19:11:39.858  4838  4838 D elm:15121: MDMBridge.getInstance()
03-15 19:11:39.858  4838  4838 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-15 19:11:39.858  4811  4811 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-15 19:11:39.858  4811  4811 D EasySignUpManager_1.0.1: isAuth is false
,03-15 19:11:39.858  1019  1031 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4857 uid=10130 gids={50130, 9997} abi=armeabi-v7a
03-15 19:11:39.868  4811  4811 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
03-15 19:11:39.868  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:39.868  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 24
,03-15 19:11:39.868  4838  4838 D elm:15121: ElmAgentService : onDestroy().
,03-15 19:11:39.878  1019  1570 I ActivityManager: Killing 1411:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-15 19:11:39.878  4857  4857 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:39.888  4857  4857 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.888  1483  1493 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4811
,03-15 19:11:39.888  1483  1493 D TP/MmsSmsProvider: match 2117:Elapsed time : 3.805 ms
,03-15 19:11:39.898  4811  4811 D EasySignUpManager_1.0.1: isAuth is false
03-15 19:11:39.898  4811  4811 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-15 19:11:39.918  4857  4857 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:39.918  4857  4857 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-15 19:11:39.928  4811  4811 E CscParser: mps_code.dat does not exist
,03-15 19:11:39.928  4811  4811 E CscParser: customer_path =/system/csc/customer.xml
03-15 19:11:39.928  4811  4811 E CscParser: fileName + /system/csc/customer.xml
,03-15 19:11:39.938  4811  4811 E CscParser: mps_code.dat does not exist
03-15 19:11:39.938  4811  4811 E CscParser: customer_path =/system/csc/customer.xml
03-15 19:11:39.938  4811  4811 E CscParser: fileName + /system/csc/customer.xml
,03-15 19:11:39.938  3164  3164 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-15 19:11:39.938  3164  3164 D PhoneWindow: *FMB* installDecor flags : -2139029248
,03-15 19:11:39.948  4811  4811 D CscParser: getInstance fileName =/system/csc/customer.xml,
,03-15 19:11:39.948  4811  4811 D Mms/MmsConfig:  enable multiwindow = false
,03-15 19:11:39.948  1019  1041 W libprocessgroup: failed to open /acct/uid_10003/pid_1411/cgroup.procs: No such file or directory
,03-15 19:11:39.958  4811  4811 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-15 19:11:39.958  4811  4811 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-15 19:11:39.958  4811  4811 D Mms/MmsConfig: [end]    init() consume time = 148.180729
,03-15 19:11:39.958  4811  4811 D Mms/Contact: [start]    init() consume time = 0.970468
,03-15 19:11:39.968  1483  1730 D TP/MmsSmsProvider: query,matched:13, calling pid = 4811
,03-15 19:11:39.978  4811  4811 D Mms/Contact: [end]    init consume time = 10.946771
,03-15 19:11:39.978  1483  1730 D TP/MmsSmsProvider: match 13:Elapsed time : 6.315 ms
,03-15 19:11:39.978  1019  1507 I ActivityManager: Killing 4173:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-15 19:11:39.978   258  1779 I SurfaceFlinger: id=12 Removed NainActivit (7/8)
,03-15 19:11:39.978  4811  4875 D Mms/DraftCache: [start]    rebuildCache consume time = 6.198802
,03-15 19:11:39.978   258   439 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,03-15 19:11:39.988  4811  4811 D Mms/MethodReflector: getSubId is called
03-15 19:11:39.988  4811  4811 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 19:11:39.988  1483  1493 D TP/MmsSmsProvider: query,matched:12, calling pid = 4811
,03-15 19:11:39.988  1483  1493 D TP/MmsSmsProvider: match 12:Elapsed time : 2.317 ms
,03-15 19:11:39.998  4811  4811 D Mms/MethodReflector: getTelephonyProperty is called
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: auto download without roaming -> true
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-15 19:11:39.998  4811  4811 D Mms/MethodReflector: getSubId is called
,03-15 19:11:39.998  4811  4811 D Mms/MethodReflector: getDefaultSmsSubId is called
03-15 19:11:39.998  4811  4811 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-15 19:11:39.998  4811  4811 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,03-15 19:11:39.998  4811  4811 D Mms/MethodReflector: getTelephonyProperty is called
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: auto download without roaming -> true
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: auto download during roaming secondary -> false
03-15 19:11:39.998  4811  4811 D Mms/DownloadManager: mAutoDownload ------> true
,03-15 19:11:39.998  4811  4875 D Mms/DraftCache: [end]    rebuildCache consume time = 19.521511
,03-15 19:11:40.008  4811  4811 D ComposerPerformance: 1458065500017 ms / [DONE] Composer constructor
,03-15 19:11:40.008  4811  4877 D Mms/Conversation: [start]    init() consume time = 9.199948
,03-15 19:11:40.008  1483  1499 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-15 19:11:40.008  1483  1499 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,03-15 19:11:40.018  1483  1499 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-15 19:11:40.018  1483  1499 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-15 19:11:40.018  1483  1499 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:40.018  1483  1499 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:40.018  1483  1499 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:40.018  1483  1499 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:40.018  1483  1499 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:40.018  1483  1499 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-15 19:11:40.028  4614  4733 I qtaguid : Untagging socket -1
,03-15 19:11:40.028  4614  4733 I qtaguid : Failed write_ctrl(u -1) res=-1 errno=9
03-15 19:11:40.028  4614  4733 I qtaguid : Untagging socket -1 failed errno=-9
03-15 19:11:40.028  4614  4733 W NetworkManagementSocketTagger: untagSocket(-1) failed with errno -9
,03-15 19:11:40.028  4614  4614 D hcjo    : SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,03-15 19:11:40.028  4811  4811 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
03-15 19:11:40.028  4614  4614 D hcjo    : AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
03-15 19:11:40.028  4811  4811 I Mms/ReservationManager: ReservationManager()
03-15 19:11:40.028  4614  4614 D hcjo    : SellerAppAutoUpdate:clearFlag
03-15 19:11:40.028  4811  4811 I Mms/ReservationManager: resetAfterConnected()
,03-15 19:11:40.028  1483  1499 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-15 19:11:40.028  1483  1499 D TP/MmsSmsProvider: need read changed broadcast:false
,03-15 19:11:40.038  4811  4877 D Mms/Conversation: [end]    init consume time = 27.542812
,03-15 19:11:40.038  1483  1730 D TP/MmsSmsProvider: query,matched:7, calling pid = 4811
,03-15 19:11:40.038  1483  1730 D TP/MmsSmsProvider: match 7:Elapsed time : 2.337 ms
,03-15 19:11:40.048  4811  4811 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-15 19:11:40.048  4614  4614 D SellerAppAutoUpdateManagerStateMachine: execute::IDLE:EXECUTE
,03-15 19:11:40.048  4614  4614 D SellerAppAutoUpdateManagerStateMachine: exit::IDLE
03-15 19:11:40.048  4614  4614 D SellerAppAutoUpdateManagerStateMachine: entry::TOKENCHECK
,03-15 19:11:40.048  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 19:11:40.048  4811  4811 D Mms/MmsApp: [end]    onCreate() consume time = 15.067604
,03-15 19:11:40.048  4811  4877 D Mms/MessagingNotification: [start]    init() consume time = 1.160365
,03-15 19:11:40.048  4811  4811 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744],
03-15 19:11:40.058  4811  4811 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
03-15 19:11:40.058  4614  4614 D SellerAppAutoUpdateManagerStateMachine: execute::TOKENCHECK:TOKEN_RECEIVED
03-15 19:11:40.058  4614  4614 D SellerAppAutoUpdateManagerStateMachine: exit::TOKENCHECK
,03-15 19:11:40.058  4614  4614 D SellerAppAutoUpdateManagerStateMachine: entry::FAILED
03-15 19:11:40.058  4614  4614 D hcjo    : AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
03-15 19:11:40.058  4614  4614 D SellerAppAutoUpdateManagerStateMachine: exit::FAILED
03-15 19:11:40.058  4614  4614 D SellerAppAutoUpdateManagerStateMachine: entry::IDLE
,03-15 19:11:40.058  4811  4811 D Mms/MethodReflector: getSubId is called
03-15 19:11:40.058  4811  4811 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 19:11:40.058  4811  4811 D Mms/MethodReflector: getTelephonyProperty is called
03-15 19:11:40.058  4811  4811 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 19:11:40.058  4811  4811 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 19:11:40.058  4811  4811 D Mms/DownloadManager: auto download without roaming -> true
03-15 19:11:40.058  4811  4811 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,03-15 19:11:40.058  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 19:11:40.058  1019  1570 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-15 19:11:40.058  1019  1570 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.068  1019  1570 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:40.068  1019  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.068  1019  1570 I ActivityManager: Killing 4322:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-15 19:11:40.068  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 19:11:40.068  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.068  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.068  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.078  4811  4877 D Mms/MessagingNotification: [end]    init consume time = 23.083281
03-15 19:11:40.078  4811  4811 D Mms/DownloadManager: mAutoDownload ------> true
,03-15 19:11:40.078  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.078  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.078  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.078  1019  1340 I ActivityManager: Killing 4083:com.android.vending/u0a26 (adj 15): empty #31
,03-15 19:11:40.078  4811  4837 D Mms/ArtClassLoader: init [DONE] art
,03-15 19:11:40.078  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:40.088  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.088  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.088  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.088  1019  1041 W libprocessgroup: failed to open /acct/uid_10135/pid_4173/cgroup.procs: No such file or directory
,03-15 19:11:40.088  4811  4878 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 12.305208
,03-15 19:11:40.088  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.088  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.088  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.088  1483  1493 D TP/MmsSmsProvider: query,matched:0, calling pid = 4811
,03-15 19:11:40.088  1483  1493 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-15 19:11:40.098  4811  4879 D Mms/Synchronizer: [start]    doSync consume time = 5.432032
,03-15 19:11:40.098  1483  1493 D TP/MmsSmsProvider: match 0:Elapsed time : 2.469 ms
,03-15 19:11:40.098  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.098  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.098  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.098  1483  1499 D TP/MmsSmsProvider: query,matched:400, calling pid = 4811
,03-15 19:11:40.098  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.098  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.098  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.108  1019  1524 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-15 19:11:40.108  1019  1524 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:40.108  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.108  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.108  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.108  1483  1493 D TP/MmsSmsProvider: update, matched:300, calling pid = 4811
,03-15 19:11:40.108  1483  1493 V TP/MmsSmsProvider: syncDBData start
,03-15 19:11:40.108  1483  1493 V TP/MmsSmsProvider: syncDBData sms end
,03-15 19:11:40.108  1019  1019 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-15 19:11:40.108  1483  1493 V TP/MmsSmsProvider: syncDBData mms end
,03-15 19:11:40.108  4811  4878 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 18.303489
03-15 19:11:40.108  1483  1493 V TP/MmsSmsProvider: syncDBData end
,03-15 19:11:40.108  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 19:11:40.118  4811  4879 D Mms/Synchronizer: [end]    doSync consume time = 2.232552,
03-15 19:11:40.118  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
03-15 19:11:40.118  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.118  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.118  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.118  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.118  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.118  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.118  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:40.118  1179  1189 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:40.128  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.128  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.128  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.128  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-15 19:11:40.128  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.128  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.128  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.128  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:40.128  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.128  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.128  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.138  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.138  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.138  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.138  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.138  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.138  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:40.148  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 19:11:40.148  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.148  1019  1019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.148  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.158  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:40.158  4811  4877 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-15 19:11:40.158  1019  1262 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 19:11:40.158  1019  1262 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-15 19:11:40.158  1019  1262 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-15 19:11:40.158  1019  1262 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 19:11:40.158  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:40.158  1019  1262 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.158  1019  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.158  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
03-15 19:11:40.158  1019  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.168  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 19:11:40.168  1483  1730 D TP/SmsProvider: query,matched:26, calling pid = 4811
,03-15 19:11:40.168  1483  1730 D TP/SmsProvider: match 26:Elapsed time : 1.095 ms
,03-15 19:11:40.178  3398  3398 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-15 19:11:40.178  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:40.178  3398  4880 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-15 19:11:40.178  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.178  1019  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.178  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.178  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:40.188  1019  1042 D SensorService: [SO] -0.479 0.192 9.902
03-15 19:11:40.188  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:40.188  1179  1179 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-15 19:11:40.188  3398  4880 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-15 19:11:40.188  3398  4880 I ReactiveServiceManager: Supported : 1
,03-15 19:11:40.188  1019  1524 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-15 19:11:40.188  1019  1524 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 19:11:40.198  1483  1499 D TP/MmsSmsProvider: query,matched:6, calling pid = 4811
,03-15 19:11:40.198  1179  1179 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-15 19:11:40.198  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.198  1019  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.198  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.198  1179  1179 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-15 19:11:40.198  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
03-15 19:11:40.198  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:40.198  1483  1499 D TP/MmsSmsProvider: match 6:Elapsed time : 7.188 ms
,03-15 19:11:40.208  1179  1179 D PanelView: There is/are notification(s) 
03-15 19:11:40.208  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:40.208  1019  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4322/cgroup.procs: No such file or directory
03-15 19:11:40.208  1019  1041 W libprocessgroup: failed to open /acct/uid_10026/pid_4083/cgroup.procs: No such file or directory
,03-15 19:11:40.208  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] ,
03-15 19:11:40.208  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
03-15 19:11:40.208  1179  1179 D PanelView: There is/are notification(s) 
03-15 19:11:40.208  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
03-15 19:11:40.208  1019  3633 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.208  1019  3633 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.208  1019  3633 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:40.208  1019  1524 D QSEECOMAPI: : Loaded image: APP id = 10
,03-15 19:11:40.208  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.208  1019  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.208  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.218  1827  1827 D WearableService: callingUid 10011, callindPid: 1827
,03-15 19:11:40.218  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 19:11:40.218  1019  1524 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 19:11:40.218  1019  1524 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-15 19:11:40.218  1019  1524 E terrier : handleString: Failed to handle string(-4)
03-15 19:11:40.218  1019  1524 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-15 19:11:40.218  3398  4880 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-15 19:11:40.218  3398  4880 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-15 19:11:40.218  1019  3387 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.218  1019  3387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.218  1019  3387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.218  3398  4880 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-15 19:11:40.228  3398  4880 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 19:11:40.228  3398  4880 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 19:11:40.228  3398  4880 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-15 19:11:40.228  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.228  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.228  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.228  1827  4881 E MDM     : [249] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:11:40.228  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.228  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.228  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.238  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.238  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.238  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:40.238  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:40.238  1827  1827 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:11:40.238  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.238  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.238  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-15 19:11:40.238  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.238  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 24
,03-15 19:11:40.248  1019  3387 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.248  1019  3387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.248  1019  3387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.248  2130  4882 D LocationInitializer: Restart initialization of location
,03-15 19:11:40.248  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 19:11:40.248  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.248  1019  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.248  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.248  1019  1340 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.258  1019  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-15 19:11:40.258  1019  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.258  1827  1827 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:40.258  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 19:11:40.268  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.268  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.268  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.268  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 19:11:40.268  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.268  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.268  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.268  1019  3631 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.278  1179  1179 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-15 19:11:40.288  1019  3631 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4885 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
03-15 19:11:40.288  4885  4885 E Zygote  : MountEmulatedStorage()
,03-15 19:11:40.288  4885  4885 E Zygote  : v2,
03-15 19:11:40.288  4885  4885 I libpersona: KNOX_SDCARD checking this for 10023
03-15 19:11:40.288  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.288  4885  4885 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:40.288  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
03-15 19:11:40.288  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:40.288  4885  4885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-15 19:11:40.288  4885  4885 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:40.288  4885  4885 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:40.298  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.298  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.298  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.298  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:40.298  1019  3633 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.298  1019  3633 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.298  1019  3633 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.318  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.318  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.318  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 19:11:40.318  1019  1515 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-15 19:11:40.318  1019  1515 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:40.328  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-15 19:11:40.328  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 19:11:40.328  4885  4885 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.328  4885  4885 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.328  1827  2147 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:11:40.328  1019  1571 I ActivityManager: Killing 4390:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,03-15 19:11:40.328  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
03-15 19:11:40.328  1827  4884 W FusedLocationProvider: location=null
,03-15 19:11:40.338  3164  3164 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:40.338  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:40.348  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.348  3164  3164 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-15 19:11:40.348  1179  1179 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-15 19:11:40.348  3164  3164 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-15 19:11:40.348  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:40.348  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 19:11:40.348  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
03-15 19:11:40.348  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:40.348  1179  1179 D PanelView: There is/are notification(s) 
03-15 19:11:40.348  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:40.348  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:40.348  1179  1179 D PanelView: There is/are notification(s) 
03-15 19:11:40.348  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:40.358  1019  1570 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.358  1019  1570 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.358  1019  1570 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.368  3164  4901 D OpenGLRenderer: Render dirty regions requested: true
,03-15 19:11:40.368  1019  1571 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 19:11:40.368  1019  1571 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 19:11:40.368  1019  1571 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 19:11:40.368  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 19:11:40.368  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:40.378  3164  3164 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 19:11:40.378  3164  3164 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 19:11:40.388   289   289 E SMD     : DCD OFF
,03-15 19:11:40.418  1179  1179 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-15 19:11:40.438  4885  4885 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-15 19:11:40.438  4811  4877 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-15 19:11:40.448  1019  3633 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.448  1019  3633 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.448  1019  3633 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-15 19:11:40.458   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=404, YUIInstallC
,03-15 19:11:40.458  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:40.458  1019  1041 W libprocessgroup: failed to open /acct/uid_10148/pid_4390/cgroup.procs: No such file or directory
,03-15 19:11:40.468  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,03-15 19:11:40.468  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.468  1019  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 19:11:40.468  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-15 19:11:40.478  1019  1262 D InputDispatcher: Focus entered window: 3164
03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
03-15 19:11:40.478  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:40.478  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
03-15 19:11:40.478  3164  3164 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-15 19:11:40.478  3164  4901 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
03-15 19:11:40.478  3164  4901 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 19:11:40.478  3164  4901 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 19:11:40.478  3164  4901 I Adreno-EGL: Local Branch: 
03-15 19:11:40.478  3164  4901 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 19:11:40.478  3164  4901 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 19:11:40.478  3164  4901 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
03-15 19:11:40.478  3164  4901 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-15 19:11:40.478  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-15 19:11:40.488  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{24ec63a6 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,03-15 19:11:40.488  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-15 19:11:40.488  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-15 19:11:40.488  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-15 19:11:40.488  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-15 19:11:40.488  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-15 19:11:40.488  4885  4885 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-15 19:11:40.508  3164  4901 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 19:11:40.508  3164  4901 D OpenGLRenderer: Enabling debug mode 0
,03-15 19:11:40.508  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.508  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 19:11:40.508  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.528  1827  1827 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-15 19:11:40.538  1019  1524 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.538  1019  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 19:11:40.538  1019  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.548  1019  3631 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.548  1019  3631 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-15 19:11:40.548  1019  3631 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.558  1019  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.558  1019  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.558  1019  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.558  1019  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.568  4905  4905 E Zygote  : MountEmulatedStorage()
03-15 19:11:40.568  4905  4905 E Zygote  : v2
,03-15 19:11:40.568  4905  4905 I libpersona: KNOX_SDCARD checking this for 1000
,03-15 19:11:40.568  4905  4905 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:40.568  4905  4905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:40.578  4905  4905 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-15 19:11:40.578  4905  4905 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:40.578  1019  1524 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4905 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 19:11:40.578  1019  1032 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 19:11:40.578  1019  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:40.598  1019  1049 I ActivityManager: Displayed Component not be shown by security: +801ms (total +942ms)
,03-15 19:11:40.598  1179  1179 D PanelView: There is/are notification(s) 
,03-15 19:11:40.608  1019  4918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:40.618  1877  1877 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 19:11:40.618  4905  4905 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.618  4905  4905 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.618  1019  1019 I ValidateNoPeople: mEvictionCount: 0
,03-15 19:11:40.628  4811  4811 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-15 19:11:40.628  3164  3164 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@265e1c4 time:52427
,03-15 19:11:40.638  4811  4923 D Mms/ContactsCache: [start]    invalidate() consume time = 521.85625
,03-15 19:11:40.638  4811  4923 D Mms/ContactsCache: [end]    invalidate() consume time = 0.647448
,03-15 19:11:40.638  4811  4811 D Mms/Contact: performUpdate:widgetCount=0
,03-15 19:11:40.668  4905  4905 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-15 19:11:40.668  1019  3631 D SecContentProvider2: uri = 14 selection = getSealedState
,03-15 19:11:40.668  1019  3631 D SecContentProvider2: mCursor = null
,03-15 19:11:40.668  1019  1515 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-15 19:11:40.668  1019  1515 D SecContentProvider2: mCursor = null
,03-15 19:11:40.668  4905  4905 V MTPRx   : sealedState: false
03-15 19:11:40.668  4905  4905 V MTPRx   : sealedUsbMassStorageState: false
03-15 19:11:40.668  4905  4905 E MTPRx   : check value of boot_completed is1
03-15 19:11:40.668  4905  4905 E MTPRx   : check booting is completed_sys.boot_completed
,03-15 19:11:40.668  4905  4905 E MTPRx   : Sd-Card path/storage/extSdCard
,03-15 19:11:40.678  4905  4905 E MTPRx   : Status for mount/Unmount :removed
03-15 19:11:40.678  4905  4905 E MTPRx   : SDcard is not available
,03-15 19:11:40.678  4905  4905 W MTPRx   : value of connected istrue
,03-15 19:11:40.678  4905  4905 W MTPRx   : value of configured istrue
03-15 19:11:40.678  4905  4905 W MTPRx   : value of mtpEnabled istrue
03-15 19:11:40.678  4905  4905 W MTPRx   : value of ptpEnabled isfalse
,03-15 19:11:40.678  4905  4905 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-15 19:11:40.678  4905  4905 E MTPRx   : mFirstTime: false
,03-15 19:11:40.688  4905  4905 D         : MTP: reading debug level property
,03-15 19:11:40.688  4905  4905 E MTPJNIInterface: Getting CryptionKey from JAVA
03-15 19:11:40.688  4905  4905 E MTPRx   : currentUserId is 0
,03-15 19:11:40.688  4905  4905 E MTPRx   : Start observing USB_STATE_MATCH 
,03-15 19:11:40.698  4905  4905 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-15 19:11:40.698  4905  4905 E MTPRx   : is_Privatemode is NOT 1
,03-15 19:11:40.698  1019  1340 D SettingsProvider: name = boot_time_connected
,03-15 19:11:40.698  4905  4905 E MTPRx   : Sending NORMAL_BOOT to stack
03-15 19:11:40.698  4905  4905 E MTPJNIInterface: noti = 17
,03-15 19:11:40.698  1019  3633 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 19:11:40.708  1019  1032 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-15 19:11:40.708  4905  4905 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-15 19:11:40.708  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.708  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.708  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 19:11:40.708  1019  1345 D SettingsProvider: name = mtp_running_status
,03-15 19:11:40.718  1019  1031 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 19:11:40.718  4905  4905 E MTPRx   : else part ... so first time!!!
03-15 19:11:40.718  4905  4905 E MTPPlaObsrvr: inside setContext()
03-15 19:11:40.718  4905  4905 E MTPPlaObsrvr:  inside createplafiles
,03-15 19:11:40.728  4905  4905 E MTPPlaObsrvr: playlist count is0
03-15 19:11:40.728  4905  4905 E MTPPlaObsrvr:  inside try branch createplafiles
,03-15 19:11:40.728  4905  4905 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-15 19:11:40.728  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 19:11:40.728  4905  4905 E MTPPlaObsrvr: Inside registerContentObserver
,03-15 19:11:40.728  4905  4905 E MtpAdbObserver: inside setContext()
,03-15 19:11:40.728  4905  4905 E MtpAdbObserver: Inside registerContentObserver
,03-15 19:11:40.728  4905  4905 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-15 19:11:40.728  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.728  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.728  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 19:11:40.738  1019  1032 D SettingsProvider: name = mtp_running_status
,03-15 19:11:40.738  1019  3631 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 19:11:40.738  4905  4926 V MtpMediaDBManager: inside deleteAllDB
,03-15 19:11:40.738  4905  4905 E MtpService: onCreate.
,03-15 19:11:40.738  4905  4905 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-15 19:11:40.738  4905  4905 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-15 19:11:40.748  4905  4905 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-15 19:11:40.748  4905  4905 E MtpService: onStartCommand.
,03-15 19:11:40.748  4905  4905 W MTPRx   : calling native method
03-15 19:11:40.748  4905  4905 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-15 19:11:40.748  4905  4927 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler },
,03-15 19:11:40.748  4905  4905 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-15 19:11:40.748  4905  4905 E MTPJNIInterface: noti = 10
,03-15 19:11:40.748  4905  4905 E MtpService: onStartCommand.
,03-15 19:11:40.748  4905  4905 W MTPRx   : calling native method
03-15 19:11:40.748  4905  4905 E MTPRx   : Checking the driver time out
03-15 19:11:40.748  4905  4905 E MTPJNIInterface: noti = 2
,03-15 19:11:40.748  4905  4905 D         : deleting sockets before message queue initialization
03-15 19:11:40.758  4905  4905 D         : event handler thread is created, so set the flag
,03-15 19:11:40.758  4905  4905 E MTPRx   : called native method
03-15 19:11:40.758  4905  4905 E MTPJNIInterface: setting Media scanner status0
03-15 19:11:40.758  4905  4905 E MTPJNIInterface: After setting Media scanner status0
03-15 19:11:40.758  4905  4927 E MtpService: handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 19:11:40.758  1019  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.758  1019  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.758  1019  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 19:11:40.758  4905  4905 W MTPRx   : notification from stack 1
,03-15 19:11:40.768  4905  4928 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-15 19:11:40.768  4905  4928 E MTPJNIInterface: Getting media scanner status0
,03-15 19:11:40.768  4905  4928 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-15 19:11:40.768  1229  1229 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-15 19:11:40.778  4905  4926 V MtpMediaDBManager: inside Thread updateDB
,03-15 19:11:40.778  1019  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.778  1019  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.778  1019  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.778  1019  1570 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.788  4929  4929 E Zygote  : MountEmulatedStorage()
03-15 19:11:40.788  4929  4929 E Zygote  : v2
03-15 19:11:40.788  4929  4929 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:40.788  4929  4929 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:40.788  4929  4929 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-15 19:11:40.798  1019  1570 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-15 19:11:40.798  4905  4926 E MtpMediaDBManager: count : 26
,03-15 19:11:40.808  4929  4929 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-15 19:11:40.808  4929  4929 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:40.818   307   307 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 20.814ms
,03-15 19:11:40.828  4905  4926 W MtpMediaDBManager: sending db update complete noti to stack
03-15 19:11:40.828  4905  4926 E MTPJNIInterface: noti = 29
,03-15 19:11:40.828  4905  4928 E SQLiteLog: (5) database is locked
,03-15 19:11:40.838   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 17.850ms
,03-15 19:11:40.848  4905  4928 E MTPJNIInterface: Status for mount/Unmount :removed
,03-15 19:11:40.848  4905  4928 E MTPJNIInterface: SDcard is not available
,03-15 19:11:40.858   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 18.174ms,
03-15 19:11:40.858  4929  4929 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.858  4929  4929 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.878  4905  4928 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-15 19:11:40.888  4905  4928 E MTPJNIInterface: Status for mount/Unmount :removed
,03-15 19:11:40.888  4905  4928 E MTPJNIInterface: SDcard is not available
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:40.888  4905  4928 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-15 19:11:40.888  4905  4905 W MTPRx   : notification from stack 2
,03-15 19:11:40.888  4905  4944 D         : [mtp_init_device] Library open with 32 bits.
03-15 19:11:40.888  4905  4944 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-15 19:11:40.888  4905  4944 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-15 19:11:40.888  4905  4944 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-15 19:11:40.888  4905  4944 E         :  [sua_support_present:1287] returning false 
03-15 19:11:40.888  4905  4944 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
